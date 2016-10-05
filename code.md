# disco
Makes your CapsLock, NumLock, and ScrollLock lights flash rapidly.



This code is for a vbs script https://en.wikipedia.org/wiki/VBScript


Not currently working correctly.



Set wshShell =wscript.CreateObject("Wscript.Shell")
do
wscript.sleep 20
WScript.Timeout = x20seconds
strtimeneed2 = strtimeneed * 1000
wshshell.sendkeys "{CAPSLOCK}"
wshshell.sendkeys "{NUMLOCK}"
wshshell.sendkeys "{SCROLLLOCK}"
loop
