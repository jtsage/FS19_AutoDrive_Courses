# How to contribute

Fork this repository, add your course file (1 course definition per folder please).

Include in the folder name - map name and your name or username.

For more information on how to fork a repository and submit a pull request, see the [GitHub Documentation](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

## Requirements:

Course file and the _course-readme-template.md_ file, properly edited.

## Recommended:

Screen capture from the course editor showing the routes on the PDA map.  The repo owner will try and help out where possible when this is not possible.

# Translations

Sadly, the repo owner only speaks English - however, should anyone want to translate either the readme.md or course files (destination names), they will gladly be accepted.  Please fork the repository and submit a pull request so that proper credit is shown.

When contributing course files with translations, please append the language code to the file.  i.e.

```AutoDrive_config.xml -> AutoDrive_config.en.xml```

Please leave _AutoDrive_config.xml_ in the original contributors language.

_readme.md_ translations should be saved as the localized name, i.e. "_readme_de.md_" and linked in the original file.

### REGEX For destinations

If you have a good editor, this will extract the name of the points from the AutoDrive XML.  Don't save.

```
<mm.+?>\n.+?\n.+?<name>(.+?)</name>\n.+?\n.+?</mm.+?>
```