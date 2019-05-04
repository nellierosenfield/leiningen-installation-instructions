# Windows Installation #

Howdy Windows users!

Below are step-by-step instructions on installing Leiningen. These were taken somewhat from the [Leiningen website](https://leiningen.org/#install). I added some more details as well as an external resource for added clarification.

## Installation Steps ##

There are three-ish ways to install Leiningen on a Windows system and I will go through all of them.

### Lein Installer (Easiest Way) ###

The easy way to install Leiningen is by running the unofficial Leiningen installer found here: [Leiningen Win Installer](https://djpowell.github.io/leiningen-win-installer/) by DJ Powell.

> Please note that downloading and using this installer is at **your** own risk. Obviously, scan for viruses and other malicious things before downloading something. I am not saying that there is anything wrong with this installer (I used it myself and it worked beautifully) but never hurts to do a quick scan.

Also, look towards the bottom of the installer page to understand what will be added to your computer, such as environment variables and files.

### Leiningen Directions ###

Now, if you decide against the installer above, this instructions on the Leiningen website are helpful. The steps are pretty similar for all systems but may need a few more steps for Windows users.

- Start by creating a directory to store the lein script you will need (for Windows, it will be a batch file).
- Save information found [here](https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein.bat) as 'lein.bat' into your newly created directory.
- Once saved, you will need to add the directory to your PATH environment variable.
- Either search for "Environment Variables" or right click *This PC* in a File Explorer. Then *Properties* -> *Advanced System Settings* -> *Environment Variables*. Up to you :).
- Look for your Path or PATH variable for your account (meaning the 'User variables for <account>', not 'System variables').
- Add your directory from step one to the end of your Path or PATH variable.
- After your are done with all this, open up yout command prompt and type `lein self-install`.
- Once that is done, type `lein` to comfirm all is way. Do not worry if it is slow during start up; that's just how it is ([Why is Leiningen so slow?](https://stackoverflow.com/questions/25052212/why-is-leiningen-so-slow-when-it-starts)). You should see this line followed by other things (tasks) -> *"Leiningen is a tool for working with Clojure projects."*
- Lastly, try starting up the Leiningen REPL by trying 'lein repl'. This also will have a slow start up but you should see that it has connected to a network along with other details.

## Common Issues and Possible Solutions ##

## External Resources ##

Leiningen Website | https://leiningen.org/#install

Leiningen Win Installer | https://djpowell.github.io/leiningen-win-installer/

Installing Leiningen on Windows | https://levlaz.org/installing-leiningen-on-windows/
