# Update-Node
A extremely simple script that auto updates Node when you boot up your Windows computer

You will need nvm for this to work. Download it <a href="https://github.com/nvm-sh/nvm">here</a>

# Instructions

First you will want to download the # updateNode.bat file from here and put it into # C:\Windows\System32.

Next you will need to hit ⊞ + R, which opens a run window.

Next you will want to type shell:startup and hit enter. This will open up a folder that will allow you to change what starts at boot.

Next create a shortcut in the startup folder and when it asks you where it should be too, type in # "C:\Windows\System32\cmd.exe /c start updateNode.bat"

After you do that you can name it anything. You should then be good to exit out of everything.

And next time you boot up your pc it should start it, update Node, and then close it self.

# NOTE [IT MIGHT ASK FOR PERMISSION EVERYTIME IT TRIES TO UPDATE. IF YOU HAVE ANY SOLUTION TO THIS HAPPENING, PLEASE MAKE A PULL REQUEST WITH YOUR SOLUTION AND I WILL MOST LIKELY ADD IT]

