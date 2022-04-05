# Assign
SFA_GetUserSid #RequireAdmin   ; due to FTYPE command #include &lt;array.au3>; For _ArrayDisplay() ; default for my .txt:  ftype Notepad++_file="C:\Program Files\Notepad++\notepad++.exe" "%1" Local $sExt, $sCmd, $sResult, $aArray, $sFtype, $sApp $sExt = InputBox("Assign an app to a file type", "Enter file type to alter ", ".txt") $sExt = "." &amp; StringReplace
