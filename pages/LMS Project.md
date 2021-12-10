- infrastructure
	- Next.js app
		- Next.js web client
		  collapsed:: true
			- ssr, typescript
				- twin css (tailwind + emotion)
		- Next.js api
		  collapsed:: true
			- typescript
			- graphql
			- prisma
	- notification message queue
	  collapsed:: true
		- emails users notifications
		- creates notification rows in db for notifications in the web client
	- postgresql database
	- redis session management
- capabilities
	- teachers and students can both use this
	- teachers can create classes & add students to them
	- teachers can create assignments with attachments
	- students can submit their work to an assignment
	- teachers can grade student's submissions & leave comments
	- notifications to students when teacher grades submissions
	- notification to students when an assignment is due soon
	-