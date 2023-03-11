## Embed Block for GitHub
* This WordPress plugin adds your favorite GitHub Repositories as a Embed Block to the Block Editor.
<p align="center">
<a href="url"><img  src="https://user-images.githubusercontent.com/55065075/224489524-46b58108-e1c3-4848-94ea-4cfb09b2a662.png" height="auto" width="600">
</p>
</p>
* This plugin is a modified version of the "embed-block-for-github" wordpress plugin written by audrasjb 

(see:[embed-block-for-github](https://jeanbaptisteaudras.com/en/2019/08/new-plugin-github-embed-block-for-gutenberg/))

## Stuff to fix&modify: 
* Unfortunately, the original plugin has some issues which needed to be fixed.
Therefore, it has been modified regarding the points shown below. 

<kbd>FIX API RATE LIMIT EXCEEDED </kbd> & <kbd> REMOVE DARKMODE </kbd> <br>
* The issue comes from the way how GitHub counts requests for rate limit. For unauthorized requests, it is limited by IP-address as shown in the picture below. <br>
* Additionally, I don't see the need for having a "darkmode" option in the plugin.

<p align="center">
<a href="url"><img  src="https://user-images.githubusercontent.com/55065075/224512080-27c44354-89e3-4d12-a160-e9da3dfc21f1.png" height="auto" width="900"></a>
</p>

<kbd> FIX LINKS NOT CLICKABLE</kbd> & <kbd> REMOVE AVATAR </kbd>  <br>
* Links on card are not clickable!<br>
* Moreover, I belive that an avatar shown on the card is a nice gimmick but not essential. <br> 


<p align="center">
<a href="url"><img src="https://user-images.githubusercontent.com/55065075/224512669-75d102f6-5ede-45f5-9056-2e866c080c3e.png" height="auto" width="450">>


## Concept & Result: 
<kbd>FIX API RATE LIMIT EXCEEDED </kbd> , <kbd> REMOVE DARKMODE </kbd> & <kbd> REMOVE AVATAR </kbd><br> 
* Use authorized API requests at the github api through personalized bearer access token. (see: [WordPress Auth](https://developer.wordpress.org/apis/making-http-requests/authentication/) & [GitHub rate limit](https://docs.github.com/en/rest/rate-limit?apiVersion=2022-11-28))<br>
* In Addition, the plugin's inspector needed an extra text field to enter the personalized access token. <br>
<p align="center">
<a href="url"><img src="https://user-images.githubusercontent.com/55065075/224512310-8a1f00c7-5e04-4b0b-b842-4272c17d75ac.png">

<kbd> MAKE CLICKABLE LINKS </kbd><br>
* Issue was already solved but never merged to the master branch. (see:[pull request](https://github.com/audrasjb/embed-block-for-github/pull/11))<br>


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

