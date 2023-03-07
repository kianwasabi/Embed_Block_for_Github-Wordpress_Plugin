## Embed Block for GitHub - modifed
* Plugin for wordpress that displays github repositories on a card.
* Forked from repository "embed-block-for-github"
## Idea/requirements for modifications: 
* Github limits (unauthorized) user-client requests to 15.000 calls/hour public.  
Whenever you run the original plugin on a hosted server, that requests github.com with its public IP address, the risk that the number of allowed api calls is already reached. 
* Workaround: authorized API requests @ github instead of anonymous ones
* Design: Remove "darkmode" option. 
## Concept: 
* Incluced authorized request to https://api.github.com through Bearer token
* Removed dark mode from .css/.php/.js files
-----------------------------------------
## Status:
Works fine, potential for enhancements 
* stuff to fix: uref not clickable!

## Author: 
*  modified by Kian David Warias (Original Contributors: audrasjb, whodunitagency, pedromendonca, vsc55)
-----------------------------------------
## Orginal README written by audrasjb: 
=== Embed Block for GitHub ===
Contributors: audrasjb, whodunitagency, pedromendonca, vsc55
Donate link: https://www.paypal.me/audrasjb
Tags: GitHub, embed, block, Gutenberg, bloc, gist, git, repository, card
Requires at least: 5.2
Tested up to: 5.4
Stable tag: 0.3
Requires PHP: 5.6
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily embed GitHub repositories in Gutenberg Editor.

== Description ==

This plugin adds a GitHub Repository Embed Block to the Block Editor.

It is developed on [GitHub](https://github.com/audrasjb/embed-block-for-github). Contributions welcome!

Special thanks:
- [@pedro-mendonca](https://github.com/pedro-mendonca) for i18n/l10n fixes and portuguese translation.
- [@vsc55](https://github.com/vsc55) for Dark Mode Enhancement, full code refresh and spanish translation.

== Screenshots ==

1. Easy to use!
2. Insert GiHub Repo Block.
3. Embed your GitHub Repositories in your Post content.
4. Integrates well with your theme stylesheet.

== Installation ==

1. Install the plugin and activate.
2. Go to the editor and choose GitHub Repo block.
3. Add the URL of the repository and see the magic happen.

== Changelog ==

= 0.3 =
* Code refresh and dark mode support. Props @vsc55: https://github.com/audrasjb/embed-block-for-github/pull/2
* Added @vsc55 as plugin contributor for his multiple contributions ♥️

= 0.2 =
* Localization/internationalization fixes. Props @pedro-mendoza: https://github.com/audrasjb/embed-block-for-github/pull/1

= 0.1.1 =
* Small fixes

= 0.1 =
* Plugin initial commit. Works fine :)
