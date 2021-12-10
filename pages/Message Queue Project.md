- language is TypeScript so I can focus on learning SMQ, and so I can combine everything later into the school app project more quickly.
- architecture
	- message_producer_app sends messages onto `queue_a`
	- message_consumer_app: reads off `queue_a`, does fake long process
- todo
	- LATER read docs on SMQ
		- about the types of queues
		- read any tips about how to use them properly
			- article called Working with Amazon SQS messages is pretty good
		- decide which kind of queues to use
		- example projects to see how they interact with the api
	- LATER setup SMQ
	- LATER setup `queue`
	- LATER setup github repo _message-queue-project_
	- LATER send messages to `queue` from message_producer_app
	- LATER consume messages on `queue` from message_consumer_app_a
	- LATER consume messages on `queue_b` from message_consumer_app_b
	- LATER store messages that couldn't be consumed in a _dead-letter queue_
	  :LOGBOOK:
	  CLOCK: [2021-12-09 Thu 19:57:53]--[2021-12-09 Thu 19:57:53] =>  00:00:00
	  :END:
	- LATER investigate benefits of using CloudWatch with SMQ
	-