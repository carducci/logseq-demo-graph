## About
	- According to the [[Book/Building a Second Brain]] methodology by [[Tiago Forte]], Projects are *buckets of goal-oriented tasks with fixed deadlines.*
	- Organize these by time-bound projects. Once these particular projects are complete no longer relevant to you, change the status to Archive. Examples of projects are:
		- The current stories you are implementing
		- Operational incidents you are working
		- Training classes you are completing
	- Within a project bucket, capture anything that seems interesting e.g.
		- Meetings
		- Training Modules
		- Etc.
- ## Active Projects
  title:: PARA: Projects
	- {{query (and [[Project]] [[Active]] )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Upcoming Projects
	- {{query (and [[Project]] [[Planned]] )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Completed Projects
	- {{query (and [[Project]] [[Completed]] )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Archive
	- {{query (and [[Project]] [[Archive]] )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]