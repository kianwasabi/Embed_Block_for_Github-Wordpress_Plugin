## Embed Block for GitHub
This WordPress plugin adds your favorite GitHub Repositories as a Embed Block to the Block Editor.
<br>
This plugin is a modified version of the "embed-block-for-github" wordpress plugin written by audrasjb (see: [GitHub Repo](https://github.com/audrasjb/embed-block-for-github).)<br>
Unfortunately, the original plugin has some issues which needed to be tackled. 
Therefore, "embed-block-for-github" has been modified regarding the points shown below. 
## Stuff to fix&modify: 
1) Fix 
1.1) <kbd>FIX API RATE LIMIT EXCEEDED </kbd><br>
Github limits unauthorized user-client requests to 15.000 calls per hour.  
If the "embed-block-for-github" plugin runs on a hosted server (which calls Github with its public IP address), there is a risk that the number of allowed calls is reached in a very short time. <br>
<kbd> <a href="url"><img src="https://user-images.githubusercontent.com/55065075/223845380-09b160d1-e05c-44cb-9e80-54005d8fb7d2.png" height="auto" width="650"></a> </kbd> <br>
1.2) <kbd> FIX LINKS NOT CLICKABLE</kbd><br>
The hyperlinks are not clickable!<br>
2) Modify Appearance
2.1) <kbd> REMOVE DARKMODE </kbd><br>
Personally, i do see the need to have a "darkmode" option in the plugin. <br> 
2.2) <kbd> REMOVE AVATAR </kbd> <br>
In my opinion, having an avatar on the card is a nice gimmick but not necessary. <br> 
## Concept & Result: 
<kbd>FIX API RATE LIMIT EXCEEDED </kbd> & <kbd> MAKE CLICKABLE LINKS </kbd><br>
https://developer.wordpress.org/apis/making-http-requests/authentication/
Use authorized API requests at the github api through personalized bearer token. 
* In Addition, the plugin's inspector needs an extra text field to enter the personalized access token. <br>
INSERT PIC <br>
<kbd> REMOVE DARKMODE </kbd> & <kbd> REMOVE AVATAR </kbd><br> 
INSERT PIC <br>
## HOW TO: 
Easy to use!
1. Create personal access token: (see: [GitHub_token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token))
2. Download this repository as .zip file.
3. Install the plugin and activate in wordpress.
4. Insert the "GitHub Repo Block".
5. Go to the editor and choose GitHub Repo block.
6. Add the URL of the repository & your GitHub token and see the magic happen.
7. Embed your GitHub Repositories in your Post content.

## Status:
Works fine. 
Potential for enhancements - Open for Contributions. 

## Author: 
* Kian David Warias 
* Original Contributors: audrasjb, whodunitagency, pedromendonca, vsc55 (see: https://github.com/audrasjb/embed-block-for-github) 
## Disclaimer: 

