gappy
=====

Learn Phonegap and some of the issues with it.


What is PhoneGap?
-----------------

PhoneGap (or the open source base cordova) is a technology that allows you create websites which interact with native features of mobile platforms. It turns your static site into a native application by running it in a browser session that has linking code to the actual platform. This allows you to write native plugins for advance functionality, while writing the bulk of your program in a way that doesn't require you to write the entire thing in a platform-specfic way. 


Signing up to important things
------------------------------

Create an account on PhoneGap, at http://build.phonegap.com

Do _not_ sign up with Github. It is not supported properly from the command line, and will lead to headaches.


Create an account on Github http://github.com


Installing the tools
--------------------

- Git

For Linux, use your package manager to install git.
The easiest way by far is to follow the guide found at https://help.github.com/articles/set-up-git

- Node.js

For Linux, use your package manage to install Node.
Grab the binary from http://nodejs.org/

- phonegap (from npm)

Run `npm install -g phonegap`


What are the tools, in a nutshell?
-------------------

- Git

A piece of software that allows you to log changes to your code and store code in a way that allows you to easily change it back and discover the changes between different versions of code. It also allows you use advance features like branching, which allows you to maintain mutliple versions of the same code at the same time and then join them together.

- Node.js

A non-browser based Javascript engine which allows you to access the local system in such a way that you can write traditional applications in Javascript. Node.js comes with builtin server support which allows you to create scalable non-blocking servers without too much hassle (other than the JS enviroment)

- phonegap

A tool used to simplify the management of your phonegap applications.
