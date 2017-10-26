@echo off
mkdir c:\pics\
setlocal enableextensions enabledelayedexpansion

set /a countz = 1
for /R %%i in (*.jpg) DO (
	mklink /H "C:\pics\!countz!.jpg" "%%i"
	set /a countz += 1
)
endlocal

echo "END OF LINE"
