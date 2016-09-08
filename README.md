# linuxdeployqt
An imitation of macdeployqt and windeployqt for the linux platform.

See linuxdeployqt --help for usage.

##Why another port?
... because the other two that existed at the time of this writing were quite limited.

It was written with the possibility in mind that it could be absorbed into the official Qt project.
I have amended the license to allow for this.

A third port on github was coincidentally started just about the same time as this project.  It shows
promise and probably stands a better chance of being incorporated into the official Qt project since
it is based on an existing Qt codebase.

##Bash?
This project is written in bash, which IMO is an appropriate language for what this tool does.  It
makes a minor use of python to deal with a need to patch a binary file.

##Limitations
My writing of this project is primarily for my own purposes.  As such, it does not include deliberate
support for qml (I don't use the stuff (yet)).  And so if qml needs to be supported, the script may
need some tweaks.

