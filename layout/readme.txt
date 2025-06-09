Please open the attached json file in https://www.keyboard-layout-editor.com/#/ (drag+drop it)

Then go to Raw Data section and copy out the layout which at the moment is as follows:

["ESC","!\n1","@\n2","#\n3","$\n4","%\n5","^\n6","&\n7","*\n8","(\n9",")\n0","_\n-","+\n=",{w:2},"Backspace"],
[{w:1.5},"Tab","Q","W","E","R","T","Y","U","I","O","P","{\n[","}\n]",{w:1.5},"|\n\\"],
[{w:1.75},"Caps Lock","A","S","D","F","G","H","J","K","L",":\n;","\"\n'",{w:2.25},"Enter"],
[{x:0.5,w:1.75},"Shift","Z","X","C","V","B","N","M","<\n,",">\n.","?\n/",{w:2.25},"Shift","↑"],
[{x:0.5,w:1.25},"Ctrl","Fn",{w:1.25},"Alt",{x:0.25,a:7,w:6.25},"",{x:0.25,a:4,w:1.25},"Alt","Pause",{x:0.5},"←","↓","→"]

Paste this into the following web site and check that the wiring is correct
https://kbfirmware.com/

Now you can use the Compile section to generate the firmware to upload to the microcontroller
