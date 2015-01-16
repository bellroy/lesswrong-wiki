lesswrong-wiki
===================


Repository for the skins and extension in use on the lesswrong wiki

The $MEDIA_WIKI_HOME/skins and extension directories will need to not have any skins or extensions with the same names in them.

To upgrade the leswrong instal to use this repo you may need to do teh following:

- Back up skins and extensions
- cd to $MEDIA_WIKI_HOME
- rm -rf skins/LessWrong.*
- rm -rf skins/lesswrong/
- cd extensions
- rm -rf AbuseFilter/ AkismetKlik/ CategoryTree/ Cite/ ConfirmEdit/ CreateBox/ HTMLets/ Math/
