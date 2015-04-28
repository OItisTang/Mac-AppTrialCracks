RetryCurio: Curio 9 trial workaround
	Create a new account "Test".
	Login as "Test".
	Set time to the far future like 2018-09-24.
	Open Curio 9.
	Agree EULA.
	Quit Curio 9.
	Copy out /Users/test/Library/Caches/.3112532943 to /tmp/Curio9-cache
	(.3112532943 this part differs. To find this file, run "ls -a ~/Library/Caches/ | egrep ^\.[0-9]+$")

	Switch back to your normal account.
	Copy /tmp/Curio9-cache to ~/Curio9-cache
	When ever Curio9 expires:
	Quit Curio9.
	run "cp ~/Curio9-cache ~/Library/Caches/.3462516372"
	Reopen Curio9.


RetryFlexiglass
	FlexiGlass is an awesome tool to implement Aero Snap feature on the Mac.
	BetterSnapTool is kind of same tool, now I have bought that from the App Store.

	Crack:
	In ~/Library/Preferences/com.nulana.flexiglassWild.plist, change timestamp with one line command:
	defaults write ~/Library/Preferences/com.nulana.flexiglassWild.plist v1_trialStartDate -date 'now'


RetryiMindmap
	iMindmap8 is out

	The crack method for Mac: rm /Library/Application\ Support/JSoft/.mm_meta8/*


RetrySketch: Sketch 3 trial workaround
	Whenever trial expires,
	remove the following file with command:
	rm -f ~/Library/Application\ Support/com.bohemiancoding.sketch3/.license

