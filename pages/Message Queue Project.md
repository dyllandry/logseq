- language is TypeScript so I can focus on learning SMQ, and so I can combine everything later into the school app project more quickly.
- architecture
	- message_sender_app: sends messages onto `queue_a` & `queue_b`
	- message_consumer_app_a: reads off `queue_a`, does fake long process
	- message_consumer_app_a: reads of `queue_b`, does fake long process
- todo
	- LATER read docs on SMQ
		- about the types of queues
		- read any tips about how to use them properly
		- decide which kind of queues to use
		- example projects to see how they interact with the api
	- LATER setup SMQ
	- LATER setup `queue_a`
	- LATER setup `queue_b`
	- LATER setup github repo _message-queue-project_
	- LATER send messages to `queue_a` from message_sender_app
	- LATER send messages to `queue_b` from message_sender_app
	- LATER consume messages on `queue_a` from message_consumer_app_a
	- LATER consume messages on `queue_b` from message_consumer_app_b
	- LATER store messages that couldn't be consumed in a _dead-letter queue_
	  :LOGBOOK:
	  CLOCK: [2021-12-09 Thu 19:57:53]--[2021-12-09 Thu 19:57:53] =>  00:00:00
	  :END:
	- LATER investigate benefits of using CloudWatch with SMQ
	-