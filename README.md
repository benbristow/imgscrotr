Imgscrotr
=============

Description
-----------
Fork of Vid Maric's ([esdf](http://github.com/esdf)) imgupr script. Instead of selecting a file to upload, imgscrotr takes a screenshot and uploads the screenshot directly to [imgur](http://www.imgur.com), the popular online image hosting site. Screen region selecting is enabled by default. Extremely useful for quickly sharing screenshots.

Requirements
------------
+ Scrot
+ cURL
+ (Optional, for copying to clipboard) xclip

Install to run from terminal
---------------------
1. Download imgscrotr from git.
> git clone https://github.com/benbristow/imgscrotr/
2. CD into the directory.
> cd imgscrotr
3. Make imgscrotr writeable
> chmod +x imgscrotr
4. Make sure dependencies installed. On Debian/Ubuntu:
> sudo apt-get install scrot curl xclip
5. Test it
> ./imgscrotr
6. If all works, copy to /usr/bin
> sudo mv imgscrotr /usr/bin/imgscrotr
7. Run from anywhere!
