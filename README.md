# PlantML.github.io
Project Webiste

## General Info

See Feeling Responsive's [website](https://phlow.github.io/feeling-responsive/getting-started/) for more help.

- For help with markdown:
	- [Intro to Markdown](https://www.markdownguide.org/getting-started/)
	- [Helpful Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- For converting mediawiki page to markdown:
  - [See here](https://github.com/philipashlock/mediawiki-to-markdown)

- Basic info for website
	- See the configuration file (\_config.yml) file to change the description/slogan, credits, github URL, icons, social media links, etc.
	- Most other changes are made in .yml files in the \_data directory. 
		- To change or add social media links go to \_data/socialmedia.yml
		- To change the structure/navigation (i.e. what goes in the drop down panel) go to \_data/navigation.yml
	- See Feeling Responsive's [website](https://phlow.github.io/feeling-responsive/getting-started/) for more help

- Adding new pages
	- See instructions on changing the structure for how to add a page to the navigation bars
	- Either copy an existing page (in /pages/) or start from scratch with a new page design template (/\_drafts/)
	- For examples of what the draft templates look like, see the [Feeling Responsive example site](https://phlow.github.io/feeling-responsive/design/)

- Changing Page banners (top image)
	- Put the new image in /images/
	- Open to the .md file for the page you want to modify
	- In the control section for that page, change the header: image_fullwidth: "new_header_image.jpg" 

- Change page title/slogan in logo
	- This is not the same as the title/slogon in the contig.yml file.
	- Change logo.png in _asset/img_.

## Homepage

- Location of .md file to control banner image, widgets, etc. on the landing/home page: /pages/pages-root-folder/index.md
- Images for this page are saved in the base /images/ directory. 
	- Banner size: 1026x304 pixels. Resolution = 300 pixels/inch
	- Widget image size: ~1000x550 pixels (width x height). Resolution ~150 pixels/inch

## People

1. Current People

- Location of .md file: /pages/people_current.md
- Where to add new images: /images/people/
- Photo size: 240x287 pixels (width x height). Resolution = 150 pixels/inch

2. Past Members

- Location of .md file: /pages/people_past.md
- Where to add new images: /images/people_past/
- Photo size: 50x60 pixels (width x height). Resolution = 72 pixels/inch
