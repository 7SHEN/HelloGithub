# HelloGithub
The first try by myself
## Test Code
```vba
Function PopupShowStr(string)
 Dim WshShell
 Set WshShell = WScript.CreateObject("WScript.Shell")
 'remind msg 
 call WshShell.Popup(string,3,"定时提醒：")
End Function
```
