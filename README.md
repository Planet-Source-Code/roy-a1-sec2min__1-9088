<div align="center">

## A1 Sec2Min


</div>

### Description

Convert seconds to minutes with just one line of code. I was encouraged to submit this after seeing where some guy had submitted 50 or so lines of code to do the same thing. This can be expanded to return hours, just follow the logic.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[roy](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/roy.md)
**Level**          |Beginner
**User Rating**    |3.9 (27 globes from 7 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/roy-a1-sec2min__1-9088/archive/master.zip)





### Source Code

```
Dim lSecs As Long
Dim sMin As String
lSecs = 120
sMin = Format(Fix(lSecs / 60), "#0") & _
  ":" & Format(lSecs Mod 60, "00")
MsgBox sMin
```

