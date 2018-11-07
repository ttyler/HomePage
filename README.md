# HomePage
No Scripts, just links to others pages
Looking to set the MacOS Users home Page...

Moving relevant text to the top ignore below the *********** Old School... Ignore...

google settings, simple, go here and use the pages to build your preferences.
https://www.chromium.org/administrators/policy-list-3

If you read between the lines have a look here;
https://gist.github.com/nathandarnell/749c16513f906a52787683576f66c8f7

and you could possible translate this into a Plist. If companies have provided a more beneficial list of domains and settings I will provide them. Please respond... :-)

*********** Old School... Ignore...

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
