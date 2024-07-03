# sublime-build

This repository contains some [build systems](https://www.sublimetext.com/docs/build_systems.html) I use for [Sublime Text](https://www.sublimetext.com/). They're simple scripts that match specific file types, run a command to build them, and use a pattern to extract error information.

They might be useful to others, but aren't intended to be end-user artifacts.

I'm installing these into Sublime Text using symlinks to its packages directory, like so:

```
ln -s ./dotnet.sublime-build ~/.config/sublime-text/Packages/User/dotnet.sublime-build
```
