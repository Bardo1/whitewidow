#Whitewidow SQL Vulnerability Scanner
Whitewidow is an open source automated SQL vulnerability scanner that makes it easy to find SQL errors within web pages.
It accomplishes this task by either running through a list of known sites using the `whitewidow.rb -f <path/tp/file>`
flag and checking for incorrectly close syntax. Alternately Whitewidow can be run in a default mode and will scrape
Google for incorrectly closed SQL syntax: `whitewidow.rb -d`.
#Screenshots
[!alt text](http://s21.postimg.org/z9o50xjwj/githubpic.jpg)
[!alt text](http://s28.postimg.org/askpmd1ex/githubpic2.jpg)
#Download
As of right now you can only clone the repository, when Whitewidow reaches version 1.0.5 it will have a tarball and a zip file to download.
#Usage
`ruby whitewidow.rb -h` Will print the help page
`ruby whitewidow.rb -hh` Will print the examples page
`ruby whitewidow.rb -f <path/to/file>` Will run Whitewidow through a file
`ruby whitewidow.rb -d` Will run Whitewidow in default mode and scrape Google
#Misc
Being an open source project, feel free to contribute your ideas and open pull request. You can fork it clone it do pretty much whatever you want to do with it.