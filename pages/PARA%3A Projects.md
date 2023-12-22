## About
	- According to the [[Building a Second Brain]] methodology by [[Tiago Forte]], Projects are *buckets of goal-oriented tasks with fixed deadlines.*
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
	- {{query (and (property :type [[Project]]) (property :status [[Active]]) )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Upcoming Projects
	- {{query (and (property :type [[Project]]) (property :status [[Planned]]) )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Completed Projects
	- {{query (and (property :type [[Project]]) (property :status [[Archive]]) )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Archive
	- {{query (and [[Project]] [[Archive]] )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
- ## Not Categorized
	- {{query (and (property :type [[Project]]) (not (property :status [[Planned]])) (not (property :status [[Active]])) (not (property :status [[Completed]])) (not (property :status [[Archive]])) )}}
	  query-table:: true
	  query-properties:: [:page :start :end :tags]
