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
- todo
	- LATER create user stories
		- DONE first pass, try to cover everything I can think of right now
		- LATER group user stories & write them much more granularly
			- for example:
				- "A teacher can set the name of their class."
				- "A teacher can edit the name of their class."
				- "A teacher can optionally set their class's course number."
				- "A teacher can edit their
	- LATER sketch UI
	- LATER create wireframes
	- LATER create data model
	  :LOGBOOK:
	  CLOCK: [2021-12-10 Fri 14:47:02]--[2021-12-10 Fri 14:47:03] =>  00:00:01
	  :END:
		- [Data Modeling: Conceptual vs Logical vs Physical Data Model](https://online.visual-paradigm.com/knowledge/visual-modeling/conceptual-vs-logical-vs-physical-data-model/)
		- LATER create conceptual data model
		- LATER upgrade to logical data model