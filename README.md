## Embed Block for GitHub - modifed
This WordPress plugin adds your favorite GitHub Repositories as a Embed Block to the Block Editor.
<br>
This plugin is a modified version of the "embed-block-for-github" wordpress plugin (see: [GitHub](https://github.com/audrasjb/embed-block-for-github).)<br>
Unfortunately, the original plugin has some issues which needed to be tackled. 
Thus, "embed-block-for-github" has been modified regarding the shown points below. 
## Stuff to modify: 
1) <kbd>FIX API RATE LIMIT EXCEEDED </kbd><br>
Github limits unauthorized user-client requests to 15.000 calls per hour.  
If the "embed-block-for-github" plugin runs on a hosted server (which calls Github with its public IP address), there is a risk that the number of allowed calls is reached in a very short time. <br>
<kbd> <a href="url"><img src="https://user-images.githubusercontent.com/55065075/223845380-09b160d1-e05c-44cb-9e80-54005d8fb7d2.png" height="auto" width="650"></a> </kbd> <br>
2) <kbd> REMOVE DARKMODE </kbd><br>
Personally, i do see the need to have a "darkmode" option in the plugin. <br> 
3) <kbd> MAKE CLICKABLE LINKS </kbd><br>
The hyperlinks are not clickable!<br>
4) <kbd> REMOVE AVATAR </kbd> <br>
Having an avatar on the card is a nice gimmick but not necessary in my opinion. <br> 
## Concept & Result: 
1) <kbd>FIX API RATE LIMIT EXCEEDED </kbd><br>
Use authorized API requests at the github api through personalized bearer token. Furthermore, the plugin's inspector needs an extra text field to enter the personalized access token. <br>
2) <kbd> REMOVE DARKMODE </kbd><br> 
Removed dark mode from files.<br>
3) <kbd> MAKE CLICKABLE LINKS </kbd><br>
4) <kbd> REMOVE AVATAR </kbd>

## HOW TO: 
Easy to use!
1. Download this repository 
2. Install the plugin and activate.
3. Insert GiHub Repo Block.
4. Go to the editor and choose GitHub Repo block.
5. Add the URL of the repository AND your GitHub token and see the magic happen.
6. Embed your GitHub Repositories in your Post content.

## Status:
Works fine. 
Potential for enhancements, Open for Contributions. 

## Author: 
* Kian David Warias 
* Original Contributors: audrasjb, whodunitagency, pedromendonca, vsc55 (see: https://github.com/audrasjb/embed-block-for-github) 
## Disclaimer: 

