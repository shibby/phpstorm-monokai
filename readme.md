## THIS IS A FORK FROM https://github.com/DmitryLanda/phpstorm-monokai
#### This version supports Objective-C (for AppCode), Java (for IntelliJ IDEA), Ruby (for RubyMine, even though it already has a Monokai color scheme), and has better PHP support (PhpStorm)

This is a port of the Monokai theme from Sublime Text 2 to IntelliJ IDEA-based IDEs. It looks a bit like this:

![Monokai_Sublime screenshot](https://raw.github.com/OtaK/jetbrains-monokai-sublime/master/screenshot.png)

Note: I have created an issue on the Jetbrain's bug-tracker.
The issue is related to selecting text that is highlighted after searching.
Link: http://youtrack.jetbrains.net/issue/WI-9576?projectKey=WI

# Installation

You can manually place the XML file in the correct location, or within PhpStorm go to File -> Import Settings and
locate the included .jar file. This will only import the colour scheme.

To manually install the colour theme, go to Preferences -> Editor -> Colors and Fonts. Create a new color
scheme called "Monokai Sublime".

Click Apply.

Search your hard drive for a file called "Monokai_Sublime.xml"

Replace that file with the one in this github repository.

On a Mac, you'll find that file at
`~/Library/Preferences/WebIDE10/colors/Monokai_Sublime.xml`

On Linux the file is located at
`~/.WebIde10/config/colors/Monokai_Sublime.xml`

On Windows, the files are located in
`C:\Documents and Settings\<Your username>\.WebIde10\config\colors`

