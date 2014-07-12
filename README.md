#arch-pkgbuilds
##tinyCA2 - version 0.7.5-2
* The source is avilaible at https://github.com/glennie/tinyca2
* The package contains also 'fix-tinyca-paths.patch' and the modified PKGBUILD from arch aur repository. I'm not sure the author for fix-tinyca-paths.patch', but, the credits for the PKGBUILD must go to Marti Raudsepp <marti@juffo.org>

###My contribution to this package
* New github repo from debian's source
* Cleaned the debian patches by removing debian specific stuff
* Added arch sub directory with arch linux related stuff

###Changelog
version 0.7.5-2 - Tue May 31 2014
  * Added arch related stuff
  * Cleaned debian related stuff
  * Moved templates from /usr/share/tinyca2 to /etc/tinyca

##linux-nemesis
  * PKGBUILD for my custom kernel. The sources are pulled from Linus' git repository

##File::Rename
Version 0.20-1 - 26 June 2014
* This will build file-rename which can be used to rename files' using perl regular expressions. This package is different from perl-rename. As debian debian user, I used to use File::Rename provided by 'rename' package on debian. This PKGBUILD will build that same package and install it as file-rename. Add "alias rename='file-rename'" to use this as the default.

##python-robobrowser
Version 0.3.1 - Sat July 12 2014
  * RoboBrowser is a simple, Pythonic library for browsing the web without a standalone web browser.
