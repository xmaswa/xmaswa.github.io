---
permalink: /
title: "Hello there, I'm Diego"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


About me 
------
I'm a 23 year old developer, graduated in 2023 in CS. Currently working as a consultant I matured a strong interest towards game developing while I was approaching the very end of my academic career, I started with simple projects in Unity and then I switched to Unreal Engine in order to gain further knowledge and to face more difficult challenges.


Unity
------
The very start consisted of relatively small tasks such as adding small features or fixing broken code in the provided projects by Unity itself. Thereafter I started my "major" project, a top down RPG, I spent quite a while (approximately 7/9 months) developing this game and it was fun, I explored a lot of concepts regarding an RPG, my intention was serious about it and I genuinely wanted to release it but it lacked of environments and I wasn't really into scene building but rather developing technical aspects. I was greatly inspired by *Metin2* when developing this game.

These are some of the features that I was able to implement in the game:
1. **Character creation**: it wasn't bone oriented (such as deforming/manipulating bones) but rather choice oriented, i.e. selecting hair, eyebrows, type of face etc.. and also adjusting the color based on your likings. After the customization the player is prompted to choose the class of your character between warrior, mage and ninja.
1. **Skill system**: I implemented a simple skill tree, it consisted of single target, area of effect and buff skills. In order to get ahold of the powerful skills the player had to unlock the previous ones, hence why it's called a skill tree.
1. **Crafting system**: the user could talk to the blacksmith and upgrade the weapons to a certain point, after which the weapon would evolve to a powerful one with better stats. Or you could craft it from scratch but at a higher prices and number of materials.
1. **Quest & Dialogue**: I actually used a wonderful plugin so I didn't make this from scratch, but it was helpful in order to read the documentation and explore every aspect of the plugin.
1. **Item stats**: every item was filled with stats for the solely purpose of powering the player, plus every item required a certain class in order to be worn. Every piece of equipment (armor and weapons) had their own effect based on the rarity. Moreover they provided a special status effect applied to the enemy only if the criteria met the requirements in order to be triggerable.
1. **Save system**: I made this from scratch, very basic save system, nothing complex.
1. **Classic RPG features**: looting, killing mobs, experience system (following Runescape's method), skill slot, chests and so on.

Unreal Engine
------
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
