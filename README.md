# HomePage
No Scripts, just links to others pages
Looking to set the MacOS Users home Page...


thinking of using;
sudo jamf help setHomePage

Usage:	 jamf setHomePage -homepage <homepage> [-feu] [-fut] [-username <username>]
		 [-removeDownloadLocation] [-skipIE] [-skipFirefox] [-skipMozilla] [-skipSafari]


	 -homepage 		 The URL for the homepage

	 -feu 			 Set the homepage for existing users

	 -fut 			 Set the homepage in the User Templates

	 -username 		 Set the homepage only for this user

	 -ffmstone 		 Specify the milestone version for FireFox

	 -mozmstone 		 Specify the milestone version for Mozilla (Netscape)

	 -removeDownloadLocation Remove the default download location

	 -skipIE 		 Do not set the homepage for Internet Explorer

	 -skipFirefox 		 Do not set the homepage for Firefox

	 -skipMozilla 		 Do not set the homepage for Mozilla based browsers (Netscape)

	 -skipSafari 		 Do not set the homepage for Safari
   
   
 DONT.... when was the last time we (mac Users used Internet Explorer, do not laugh... I used it)
 
 attached here are a few plist settings that you can use to apply these settings via Jamf using "Custom Settings" or other providers.... 
