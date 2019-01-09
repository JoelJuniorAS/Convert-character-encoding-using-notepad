# Convert-character-encoding-using-notepad
Easily convert your project character encoding to UTF-8 or any other NotePad++ support. Reference: https://pw999.wordpress.com/2013/08/19/mass-convert-a-project-to-utf-8-using-notepad/

1- Download and install Phyton Script from Source Forge:
(https://sourceforge.net/projects/npppythonscript/files/Python%20Script%201.0.8.0/). 

2- NotePad++ have to be in English. 

  2.1- To change: Settings -> Preferences -> General -> Localization

3- Plugins -> Phyton Script -> New Script, paste the code. 

  3.1- Or download and paste in: C:\Users\-YOURUSER-\AppData\Roaming\Notepad++\plugins\config\PythonScript\scripts.

4- Chage the "filePathSrc" to your project path.

  4.1- If you want to convert to another character encoding just change line 9.
       Ex: line 9- notepad.runMenuCommand("Encoding", "Convert to ANSI")

5- Puglins -> Phyton Script -> Scripts(you should find the name of your script) -> UTF-8 no Dom converter.

OBS: You can change line 6 to only accept your project's language.
     Ex: line 6- if fn[-5:] == '.java'
