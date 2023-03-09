## Embed Block for GitHub - modifed
This WordPress plugin adds your favorite GitHub Repositories as a Embed Block to the Block Editor.
<br>
It is based on a plugin called "embed-block-for-github" ([GitHub](https://github.com/audrasjb/embed-block-for-github))<br>
Unfortunately, the original plugin did not work as expected and had some issues which needed to be tackled. 
The plugin is modified to fulfill the shown Requirements below. 
## Stuff to modify: 
1) <kbd>FIX API RATE LIMIT EXCEEDED </kbd><br>
Github limits unauthorized user-client requests to 15.000 calls per hour.  
If the "embed-block-for-github" plugin runs on a hosted server (which calls Github with its public IP address), there is a risk that the number of allowed calls is reached in a very short time.  <kbd> <a href="url"><img src="https://user-images.githubusercontent.com/55065075/223845380-09b160d1-e05c-44cb-9e80-54005d8fb7d2.png" height="auto" width="650"></a> </kbd> <br>
2) <kbd> REMOVE DARKMODE </kbd><br>
Personally, i do not line the "darkmode" option in the original plugin. Therefore I wanted it to be removed. <br>
3) <kbd> MAKE CLICKABLE LINKS </kbd><br>
The hyperlinks are not clickable!<br>

## Concept & Result: 
1) <kbd>FIX API RATE LIMIT EXCEEDED </kbd><br>
Use authorized API requests at the github api through personalized bearer token. Furthermore, the plugin's inspector needs an extra text field to enter the personalized access token. <br>
2) <kbd> REMOVE DARKMODE </kbd><br> 
Removed dark mode from files.<br>
3) <kbd> MAKE CLICKABLE LINKS </kbd><br>

## HOW TO: 
1. Easy to use!
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
