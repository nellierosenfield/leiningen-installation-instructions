# Linux/Ubuntu Installation #

Greetings Linux/Ubuntu users!

Below are step-by-step instructions on installing Leiningen. These were taken directly from the [Leiningen website](https://leiningen.org/#install). These steps are nearly similar to the [MacOS Installation](https://github.com/nilajawill/leiningen-installation-instructions/blob/master/mac-installation/MAC-README.md) steps, which should be expected. However, I will still go over the steps :).

## Installation Steps ##

- Start by opening your terminal, either using `CTRL-ATL-T` or from your Dash Home, if applicable. 
- Create a directory to store the neccesary Leiningen file wherever convenient. 
- Go to [Leiningen.org](https://leiningen.org/#install) and save the 'lein script' using the "Save Link As..." option or any other way you would like. By default, the lein script will be saved as a `.txt` file. Please save the file into the directory you made.
- Next, within your terminal, navigate to where your lein script is and make your script executable by using `chmod a+x` followed by `lein`, the preferred (strongly suggested) name of your lein script.
- According to [this external resource](https://lispcast.com/clojure-ubuntu/) (also listed below), within your terminal, you can simply add the lein script to your $PATH by using `export PATH=$PATH:/path/to/bin`, where `/path/to/bin` will instead contain your computer's path to where your stored your lein script. 
- If the previous step didn't work, you may need to look to see if you have the privileges neccesary to add to your path. You can go [here](https://www.linux.com/learn/how-manage-file-and-folder-permissions-Linux) for more details.
- Once added to your PATH, in your terminal, use the `lein` command. Do not worry if it is slow during start up; that's just how it is ([Why is Leiningen so slow?](https://stackoverflow.com/questions/25052212/why-is-leiningen-so-slow-when-it-starts)). You should see this line followed by other things (tasks) -> *"Leiningen is a tool for working with Clojure projects."*
- Finally, try starting up the Leiningen REPL by trying `lein repl`. This also will have a slow start up but you should see that it has connected to a network along with other details.

## Common Issues and Possible Solutions ##

## External Resources ##

Leiningen Website | https://leiningen.org/#install

LispCast | https://lispcast.com/clojure-ubuntu/

Linux.com | https://www.linux.com/learn/how-manage-file-and-folder-permissions-Linux
