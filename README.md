orgmode for sublime text editor
=============

handles .org files.

This is a fork of danielmugnussons' repository. I have only added a few changes to make it work with Linux. I won't have the time to maintain it.

Use this repository, if you use Windows: https://github.com/danielmagnussons/orgmode

If you are using Linux, you should apply my changes and get updates from one of the other sources, as well.

The rest of this document is copied from the original repo.

HOWTO
=============

	cd c:\Users\USER\AppData\Roaming\Sublime Text 2\Packages\
	git clone git@github.com:danielmagnussons/orgmode.git
	restart sublime
	open c:\Users\USER\AppData\Roaming\Sublime Text 2\Packages\README.org in sublime


Stuff that have been added
=============

	[X] HelpIt integrated, alt+f1 looks up th eword on google.
	[X] redmine, [[redmine:9726]], [[issue:9726]], [[#9726]]
	[X] local file not working well for windows
	      [X] åäö problems
	[X] open cmd line at "[[cmd:c:\dev]]"
	      - [[cmd:c:\dev\]]
	      - [[prompt:c:\dev\apps]]

	[X] http resolver, make urls with # work
	    - [[http://www.sublimetext.com/forum/viewtopic.php?f=5&t=1838&p=18483#p18483]]
	    [X] https is not working, [[https://www.google.com/]]
	        -https resolver..

	[X] navigation history
	[X] src refactor, moved settings to Global.sublime-settings
	[X] added default theme in orgmode dir.


MISC
=============

forked from https://bitbucket.org/theblacklion/sublime_orgmode/
