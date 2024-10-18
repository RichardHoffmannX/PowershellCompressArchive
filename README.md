# Powershell Compress Archive
Powershell Compress Archive for Batch File Windows OS

# Insert into batch file:

--- 
'''
set sourcepath='D:\[sourcedirectory]'
set targetpath='D:\[targetdirectory]\[targetfilename].zip'

powershell.exe Compress-Archive -Path %sourcepath% -DestinationPath %targetpath%

REM Pause if needed
pause
'''
