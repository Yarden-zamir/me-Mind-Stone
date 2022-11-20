## <% tp.date.now("dddd") %>  #dates/<% tp.date.now("YYYY/MM/DD") %>
```dataview
Table WITHOUT ID
	file.link as Shard,
	file.etags as Tags
FROM 
	#dates/<% tp.date.now("YYYY/MM/DD") %> and 
	!"Templates" and
	!"Logs"
```

