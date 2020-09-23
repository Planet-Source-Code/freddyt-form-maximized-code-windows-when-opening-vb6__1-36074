<div align="center">

## Form Maximized Code windows when opening VB6


</div>

### Description

This code is not for everyone, just for those of us who like to work with maximized windows. This will explain how to force Visual Basic 6 to always maximize your code windows when opening projects. This method will always open windows maximized, not like VB5 when it would rememeber your settings.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[FreddyT](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/freddyt.md)
**Level**          |Intermediate
**User Rating**    |4.9 (88 globes from 18 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/freddyt-form-maximized-code-windows-when-opening-vb6__1-36074/archive/master.zip)





### Source Code

```
This requires modification to your registry, please take steps required before making changes here.
Navigate to:
HKEY_CURRENT_USER\Software\Microsoft\Visual Basic\6.0
Look to see if you have a string value of MDIMaximized, if not create a new one and set its value to 1. A value of 0 will return to normal sized windows.
Next time you open VB enjoy one less step of maximizing your windows.
```

