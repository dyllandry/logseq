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
	- DONE teachers and students can both use this
	  :LOGBOOK:
	  CLOCK: [2021-12-16 Thu 08:44:01]--[2021-12-16 Thu 08:44:02] =>  00:00:01
	  :END:
	- DONE teachers can create classes & add students to them
	  :LOGBOOK:
	  CLOCK: [2021-12-16 Thu 08:45:06]--[2021-12-16 Thu 08:45:07] =>  00:00:01
	  :END:
	- DONE student gets an email to register
	- DONE teachers can create assignments with attachments
	  :LOGBOOK:
	  CLOCK: [2021-12-16 Thu 08:45:26]--[2021-12-16 Thu 08:45:27] =>  00:00:01
	  :END:
	- DONE students can submit their work to an assignment
	  :LOGBOOK:
	  CLOCK: [2021-12-16 Thu 08:45:41]--[2021-12-16 Thu 08:45:42] =>  00:00:01
	  :END:
	- LATER teachers can grade student's submissions & leave comments
	- LATER sends notification to students when teacher grades their submissions
	- LATER sends notification to students when an unsubmitted assignment is due soon
	- LATER teacher can see a student's performance across all grades
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