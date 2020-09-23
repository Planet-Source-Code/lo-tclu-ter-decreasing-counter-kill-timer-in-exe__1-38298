<div align="center">

## Decreasing Counter  \- Kill Timer In Exe

<img src="PIC2002825191159816.GIF">
</div>

### Description

<font color = red>INTENDED ONLY FOR EDUCATIONAL PURPORSES! USE IT AT YOUR OWN RISK!<br></font>

<font color = blue>Yeah, don't forget to backup your dll :)</font><br>

Patching msvbvm60.dll <-

<br>HEX's View On It :)

<br>How to find string and replace it with hex editor
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Lo$tClu$ter](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/lo-tclu-ter.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/lo-tclu-ter-decreasing-counter-kill-timer-in-exe__1-38298/archive/master.zip)





### Source Code

Ok..
<br><font size = 2>
So what we got ?
<br>
1. Before application starts we see a very nice
 screen with a decreasing counter.
 5...4.....3...2...1.... Ok -> cOol
<br>
2. Now we can push a button and use this application..
<br>Well, I guess we don't want to wait ;)
<br>So now we'll patch <b>msvbvm60.dll</b>
<br>Open this dll with hex editor and look
for :<b>57 FF 74 24 14 FF 74 24</b>
<br>Replace<font color =red> 57 with 50</font> (push eax)
<br>:)</font>

