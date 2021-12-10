- DONE decide on web projects for portfolio _12-05_
  id:: 61ad45c1-5491-451c-886c-86c4f6de2ce3
	- I'd like to do small manageable projects instead of large ones. I don't want to bottleneck anything.
	  collapsed:: true
		- I could build a larger project with each increment.
	- Tech I want to use:
		- **simple message queue (SMQ) on AWS**
			- [[Message Queue Project]]
			- message_producer_app_1: sends messages onto queue
			- consumer_app: reads off queue, does fake long process
			- The queue I use in the school app could be
				- client submits new grade to api
				- api pushes message on queue
		- **prisma ORM**
		  collapsed:: true
			- school app backend w/ migrations, seeding
			- include tests that involve seeding
		- **graphql api**
		  collapsed:: true
			- on top of the school prisma ORM project
			- include tests
		- **docker**
		  collapsed:: true
			- docker-compose for school database & api w/ ORM
		- **create-react-app**
			- simple frontend for school app
			-
		- **k8s**
		  collapsed:: true
			- services:
				- school api
				- school database
				- report card generator
			- school api provides route to generate report cards for each student which sends messages to smq, report card generate consumes the events as it can.
- LATER decide on criteria for new web job