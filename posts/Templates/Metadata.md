---
<%*if(tp.file.path(true).includes("/")){-%>
aliases: [<% tp.file.title %>, <% tp.file.cursor(0)%>]
tags: [dates/<% tp.date.now("YYYY/MM/DD") %>, <% tp.file.cursor(1)%>]
<%-*}else{_%> 
aliases: []
tags: [dates/<% tp.date.now("YYYY/MM/DD") %>, ]<%* } %>
---
<%* if (tp.file.path(true).includes("/")){-%>
 - [l] [[<%tp.file.path(true).substr(0,tp.file.path(true).lastIndexOf("/"))%>|<%tp.file.path(true).substr(0,tp.file.path(true).lastIndexOf("/")).replaceAll("/"," / ")%>]]
---
<%*}%> 
<%*if(tp.file.path(true).includes("/")){-%>
<% tp.file.cursor(2) %>
<%-*}_%> 