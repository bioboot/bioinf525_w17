# BIOINF 525: Foundations of Bioinformatics and Systems Biology
BIOINF525 course website for 2017, see:  http://bioboot.github.io/bioinf525_w17/


This is a [jekell based static site](http://jekyllrb.com/docs/home/). 

To view locally on your own machine (i.e. before pushing or submitting a pull 
request to this [bioinf525_w17 GitHub](https://github.com/bioboot/bioinf525_w17) repo) 
you will need to have the **jekyll** and **github-pages** gem setup, i.e.:

Consider updating RubyGems first (likely need sudo for these).

	sudo gem update --system

Then install the Jekyll Gem and the GitHub Gem

	sudo gem install jekyll bundler -n/usr/local/bin
	sudo gem install github-pages -n/usr/local/bin


## Basics of Jekyll websites
Jekyll websites are configured based on the contents of the various underscore prefixed files and folders. You can find out more about these here: http://jekyllrb.com/docs/structure/

However, most likely you will want to leave most of these alone and just add  
content to the day{2,3,4,5}.md files and create new files in the **class-material/** 
directory (i.e. add lecture slides, handouts, cheat-sheets etc.)

Please remember that all content is on the **gh-pages** branch! 
So you will want to be working on this branch and push back to this branch.

A typical workflow for folks that have been added as **"Collaborators"** would look something like this:

	## One time only clone
	git clone https://github.com/bioboot/bioinf525_w17.git
	cd bioinf525_w17

	## Edit your files (e.g. module3.md)
	vi module3.md

	## Check changes localy
	jekyll serve

	## Pull recent changes
	git pull origin gh-pages

	## Stage, commit and push your changes
	git status
	git add module3.md
	git commit -m "Your msg about changes"
	git push origin gh-pages


## How this site was built
Bassically, cloned forward from previous years work, see: [2016](https://github.com/bioboot/bioinf525_w16), [2015](https://github.com/bioboot/web-2016), etc...



