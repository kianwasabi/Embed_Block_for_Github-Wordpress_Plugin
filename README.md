## Embed Block for GitHub
This WordPress plugin adds your favorite GitHub Repositories as a Embed Block to the Block Editor.
<br>

<img width="640" alt="Screenshot 2023-03-11 at 15 13 40" src="https://user-images.githubusercontent.com/55065075/224489524-46b58108-e1c3-4848-94ea-4cfb09b2a662.png">

This plugin is a modified version of the "embed-block-for-github" wordpress plugin written by audrasjb (see: [embed-block-for-github](https://jeanbaptisteaudras.com/en/2019/08/new-plugin-github-embed-block-for-gutenberg/))<br>
Unfortunately, the original plugin has some issues which needed to be tackled. <br>
Therefore, "embed-block-for-github" has been modified regarding the points shown below. 

## Stuff to fix&modify: 

### FIX <br>
<kbd>FIX API RATE LIMIT EXCEEDED </kbd><br>
* The issue comes from the way how GitHub counts requests for rate limit. For unauthorized requests, it limits by IP - risky whenever the plugin runs on a shared hosting server. <br>
<kbd> <a href="url"><img src="https://user-images.githubusercontent.com/55065075/223845380-09b160d1-e05c-44cb-9e80-54005d8fb7d2.png" height="auto" width="650"></a> </kbd> <br>

<kbd> FIX LINKS NOT CLICKABLE</kbd><br>
* Links are not clickable!<br>

### MODIFY <br>
<kbd> REMOVE DARKMODE </kbd> & <kbd> REMOVE AVATAR </kbd>  <br>
* Personally, I don't see the need for having a "darkmode" option in the plugin. Moreover, I belive that an avatar shown on the card is a nice gimmick but not essential. <br> 

## Concept & Result: 
<kbd>FIX API RATE LIMIT EXCEEDED </kbd> <br>
* Use authorized API requests at the github api through personalized bearer access token. (see: [WordPress Auth](https://developer.wordpress.org/apis/making-http-requests/authentication/) & [GitHub rate limit](https://docs.github.com/en/rest/rate-limit?apiVersion=2022-11-28))<br>
* In Addition, the plugin's inspector needed an extra text field to enter the personalized access token. <br>
<kbd> MAKE CLICKABLE LINKS </kbd><br>

![Screenshot 2023-03-07 at 23 50 59](https://user-images.githubusercontent.com/55065075/224489770-f65bc239-02d1-4234-b845-e3668ccd3342.png)


* Modification in .css - Issue was already solved but never merged to the master branch. (see:[pull request](https://github.com/audrasjb/embed-block-for-github/pull/11))<br>
<kbd> REMOVE DARKMODE </kbd> & <kbd> REMOVE AVATAR </kbd><br> 

## HOW TO: 
Easy to use!
1. Create personal access token: (see: [GitHub Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token))
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
* Original Contributors: audrasjb, whodunitagency, pedromendonca, vsc55 (see: [audrasjb etc.](https://github.com/audrasjb/embed-block-for-github))

