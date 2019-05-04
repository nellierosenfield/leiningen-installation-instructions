# Mac Installation #

Hello Mac users!

Below are step-by-step instructions on installing Leiningen. These were taken directly from the [Leiningen website](https://leiningen.org/#install). I just added some small details as well as an external resource for added clarification.

## Installation Steps ##

- Start by creating a directory for housing the Leiningen script your will need. (Either by using mkdir in your bash or manually added a directory)
- Please download the ['lein script'](https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein), which contains everything needed for Leiningen to work on your system. You may need to use 'curl' command for this step ([How to Use cURL for Files](http://osxdaily.com/2014/02/13/download-with-curl/)). Please save the script as 'lein'.
- Using your bash, navigate to where your lein script is and make your script executable by using 'chmod a+x' followed by 'lein', the preferred (strongly suggested) name of your lein script.
- Next, you will need to add your Leiningen directory (the one that has your now executable lein script) to your $PATH directory. This is where my help is shaky. I am unsure how adding to the PATH works for MacOS; therefore, please go to [here](http://www.hildeberto.com/2015/07/installing-leiningen-on-mac-os.html) for this step. 
- Once you have added your directory to your $PATH, now it's time to test and see if everything worked out.
- From your bash, using the 'lein' command. Do not worry if it is slow during start up; that's just how it is ([Why is Leiningen so slow?](https://stackoverflow.com/questions/25052212/why-is-leiningen-so-slow-when-it-starts)). You should see this line followed by other things (tasks) -> *"Leiningen is a tool for working with Clojure projects."*
- Afterwards, try starting up the Leiningen REPL by trying 'lein repl'. This also will have a slow start up but you should see that it has connected to a network along with other details.

## Resources Used ##

Leiningen Website | https://leiningen.org/#install

Hildeberto Mendonça's Instructions for MacOS | http://www.hildeberto.com/2015/07/installing-leiningen-on-mac-os.html

