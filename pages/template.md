# Books
template:: Book Template
template-including-parent:: false
collapsed:: true
	- ## Meta
	  Type:: [/[Books]]
	  Status:: [/[Reading]] [/[Read]] [/[books-to-read]]
	  Cover:: ![image](){:height 172, :width 98}
	  Title:: 
	  Author:: 
	  Link:: [Goodreads]()
	  Start:: 
	  End:: 
	  Year:: 
	  Genre::
	  Format::
	  Tags::
	- ## Content/Notes
- # Project
  template:: Project Template
  template-including-parent:: false
	- ## Meta
	  Type:: [/[Project]]
	  Status:: [/[Planned]] [/[Active]] [/[Completed]] [/[Archive]]
	  Team:: 
	  Lead:: 
	  Goals:: 
	  Start:: 
	  End::  
	  areas::
	  Tags::
	- ## Objective
	- ## Scope
	- ## Project Kickoff Checklist
	- ## Tasks
		- {{query (and <% current page %> (task LATER))}}
	- ## Resources
	- ## Notes
- # Areas
  template:: Areas Template
  template-including-parent:: false
	- ## Meta
	  Type:: [/[Area]]
	  Status:: [/[Active]] [/[Archive]]
	  Team:: 
	  Tags::
	- ## Tasks
		- {{query (and <% current page %> (task LATER) )}}
	- ## Notes
- # Resource
  template:: Resource Template
  template-including-parent:: false
  collapsed:: true
	- ## Meta
	  Type:: [/[Resource]]
	  Status:: [/[Active]] [/[Archive]]
	  Description:: 
	  Tags::
	- ## Books
	- ## Web Resources
	- ## Videos
	- ## Notes
	- ## Flashcards
		- {{cards <% current page %> }}
- # Team Member
  template:: Team Member Template
  template-including-parent:: false
	- ## Meta
	  Type:: [/[Teammember]] [/[Person]]
	  name::
	  location::
	  next-birthday:: 
	  work-anniversary:: 
	  career-goals::
	  superpowers:: 
	  hobbies-etc::
	  targets::
	  preference-for-praise::
	  notes:: 
	  kudos:: 
	  areas-for-growth::
	- ## Notes
- # Meeting Template
  template:: Meeting Template
  template-including-parent:: false
	- ## Meta
	  Type:: [/[Meeting]]
	  Parent:: 
	  Areas::
	  Date:: 
	  Objective:: 
	  Attendees:: 
	  Topic:: 
	  Project:: 
	  Tags::
	- ## Notes
	- ## Actions
	- ## Next Meeting
	-
- # 1:1 Template
  template:: One-on-One Template
  template-including-parent:: false
  collapsed:: true
	- ## Check-in (5 mins)
		-
	- ## Recent Work Recap (10 min)
		-
	- ## Upcoming Work
	-
	- ## Action Items
- # Daily Journal (light)
  template:: Daily Journal Template
  template-including-parent:: false
  collapsed:: true
	- ## Goal
		-
	- ## Today's Targets
		- ### TODO 1.
		- ### TODO 2.
		- ### TODO 3.
	- ## Notes/Activity
	-
	- ## [[inbox]]
		-
	- ## Don't Forget
		-
	- ## Lessons Learned
		-
	- ## Gratitude/Reflection
		-
	- ## Wins
- # Weekly Journal Reflection
  template:: Weekly Review Template
  template-including-parent:: false
	- ## Habit/Activity Tracking
	- ## Summary of This Week's Notes
		- ### Patterns
		- ### Incidents
		- ### Discoveries
	- ## How was time spent this week re [[goals]]
		-
	- ## How will you improve next week?
		-
	- ## Biggest Lesson Learned This Week
	- ## Reflection
		- ### Highs
		- ### Lows
		- ### Memories
	- ## 3 Big Wins for the Week
		- -
		  logseq.order-list-type:: number
		- -
		  logseq.order-list-type:: number
		- -
		  logseq.order-list-type:: number
	- ## Happiest event this week
	-
- # Conference Talk Template
  template:: Conference Talk Template
  template-including-parent:: false
	- ## Meta
		- Type:: [/[Conference Talk]]
		  title:: 
		  speaker:: 
		  conference:: 
		  date:: 
		  location:: 
		  abstract::
	- ## Slides
	- ## Notes