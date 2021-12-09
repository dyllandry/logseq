- DONE clean up code, remove texture mixing & movement controls _12-05_
  id:: 61ad73fd-a451-4db6-8366-50551cfd2885
- LATER do camera chapter
-
- I could swap to c++ when I do the game section for breakout.
	- I should probably stick to c, I feel like I would be changing it up too quick. Maybe? I really don't know if I should keep using C or swap to C++. The fact that I don't know probably means I should stick with C, right? People say you should write C++ with just simple classes, only one level of inheritance, and only simple templates. Then you get the benefit of wrapping methods and data in classes without C++ code that is too complicated.
- Chapter Notes
	- Camera
		-
		  2. Camera direction
			- I'm unsure about this line `glm::normalize(cameraPos - cameraTarget)`. We want a direction from the camera to the target it's looking at, but this computation gives a direction from the target to the camera. The reasoning in the article is: _"For the view matrix's coordinate system we want its z-axis to be positive and because by convention (in OpenGL) the camera points towards the negative z-axis we want to negate the direction vector. If we switch the subtraction order around we now get a vector pointing towards the camera's positive z-axis"_
				- If we want to flip the camera around the target so that the camera's position in positive, I get that. But isn't computing the direction this way also going to flip the y axis? Instead of (0,-2,-2) from camera to target, it will be (0, 2, 2) from target to camera. But maybe that's fine. I should probably just keep going onwards.
-