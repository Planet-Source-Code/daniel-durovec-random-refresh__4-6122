<div align="center">

## Random Refresh


</div>

### Description

This ASP page is randomly refreshed. The refreshing time is from 5 up to 20 seconds. You can use it with displaying a commercial banners.
 
### More Info
 
There is no side effects.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Daniel Durovec](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/daniel-durovec.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/daniel-durovec-random-refresh__4-6122/archive/master.zip)





### Source Code

```
<%@ Language=VBScript %>
<%Randomize
nRefresh=int(15*rnd())+5%>
<HTML>
<HEAD>
 <META HTTP-EQUIV="REFRESH" CONTENT="<%=nRefresh%>;default.asp">
</HEAD>
<BODY>
Hello, my friends.
</BODY>
</HTML>
```

