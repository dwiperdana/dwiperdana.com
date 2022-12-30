```dataview
table without ID 
	link(file.link,title) as Title, 
	draft as isDraft,
	dateformat(file.mday,"MMM-dd") as "Last"
from "posts"
sort file.mday desc
```