Ritito:
This is a web app I made that lets you type text and download it as a .gcode file, So your 3d printer can literally draw it with a pen. 

What it does:
1. you type something in the box on the left
2. it shows up on the printer bed preview in the middle
3. you can pick a font from the panel (changes how it looks on the preview)
4. Hit Download .gcode and it gives you a file you can send straight to your ender 3 (currnetly works properly for that)

The font buttons:
There are 5 fonts you can pick from. clicking one changes the text on the bed preview to that font. its just for looks tho, the gcode always uses the same single stroke style because thats what pen plotters need. And real font change is yet to be added.

The gcode:
The downloaded file works on a 220x220mm bed (Ender 3). just attach a pen to your printer instead of the extruder and it'll draw your text. pen goes down to Z0 when drawing and lifts to Z5mm when moving between letters.

Note:
Fonts are just placebo buttons right now (they change the preview but not the gcode output)
Only uppercase is supported. 

AI use:
Used AI to get the values for each letter and number in G-code.

Made for Beest by Siddharthan.
Thank you </> Happy hacking



