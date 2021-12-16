- links
	- [milanote](https://app.milanote.com/1MWRjm18rVBz14/lms)
- infrastructure
  collapsed:: true
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
- desired features
	- ~teachers and students can both use this~
	- teachers can create classes & add students to them
	- student gets an email to register
	- teachers can create assignments with attachments
	- students can submit their work to an assignment
	- teachers can grade student's submissions & leave comments
	- sends notification to students when teacher grades their submissions
	- sends notification to students when an unsubmitted assignment is due soon
	- teacher can see a student's performance across all grades
- todo
  collapsed:: true
	- LATER create user stories
	- LATER sketch UI
	- LATER create wireframes
	- LATER create data model
	  :LOGBOOK:
	  CLOCK: [2021-12-10 Fri 14:47:02]--[2021-12-10 Fri 14:47:03] =>  00:00:01
	  :END:
		- [Data Modeling: Conceptual vs Logical vs Physical Data Model](https://online.visual-paradigm.com/knowledge/visual-modeling/conceptual-vs-logical-vs-physical-data-model/)
		- LATER create conceptual data model
		- LATER upgrade to logical data model