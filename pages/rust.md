- mutability
  collapsed:: true
	- ```rust
	  let a = 5; // variable is immutable
	  let a = 10 // but variable can be shadowed
	  let mut y = 5; // variable is mutable
	  // must be constant expression (not a runtime computation value)
	  const MAX_HP: u32 = 100;
	  ```
- data types
  collapsed:: true
	- ```rust
	  let hp: u32 = 100;
	  ```
	- tuples
		- ```rust
		  let my_tuple: (u32, boolean, char) = (100, true, 'b');
		  let num = my_tuple.0;
		  ```
	- array
		- ```rust
		  let a = [1, 2, 3];
		  let a: [u32; 3] = [1, 2, 3]; // [type; length]
		  let a = [0; 10]; // set array to 10 elements each set to 0.
		  ```
		- fixed length
- functions
  collapsed:: true
	- ```rust
	  fn my_function(x: i32) {
	    println!("The value of x is {}!", x);
	  }
	  
	  fn plus_one(x: i32) -> i32 { // the function's return type comes after ->
	    // functions automatically return their body's last expression
	    x + 1 // an express because it doesn't end with a semicolon
	  }
	  ```
- control flow
  collapsed:: true
	- if expression
		- ```rust
		  if result < 5 {
		    // true case
		  } else {
		    // false case
		  }
		  
		  // if is an expression
		  let result = if (condition) { 5 } else { 2 };
		  ```
	- loops
		- ```rust
		  loop {
		    println!("again")
		  }
		  
		  'counting_up: loop { // 'counting_up is a loop label
		    loop {
		    	// do stuff
		      // ...
		      if condition {
		        // breaks out of the loop with label 'counting_up
		        break 'counting_up;
		      }
		    }
		  }
		  
		  // loops can return values
		  let result = loop {
		    // check if something is done
		    // ...
		    if condition {
		      break counter * 2;
		    }
		  }
		  
		  // while loop
		  while condition {
		  	// do stuff  
		  }
		  
		  // for loop
		  let a = [1, 2 ,3];
		  for element in a {
		    println!("the value is: {}", element);
		  }
		  
		  // reversing a range
		  for number in (1..10).rev() {
		    println!("counting down: {}", number);
		  }
		  ```
- ownership
	- Ownership is rust's own novel concept that allows rust to make memory-safe garuntees without needed a garbage collect