## Commands

* sudo apt update: To update all packages for Linux
* sudo apt upgrade-y: used to upgrade and answer all questions yes to prevent any questions being asked


# Self study task- Deploy a website on your vm
## Blocker: This is what I have done so far in order to do the back up 
**cd /var/www** <br>
adminuser@tech501-vineet-first-vm:/var/www$ **sudo cp -r html html-backup** <br>
adminuser@tech501-vineet-first-vm:/var/www$ **ls -l html-backup** <br>
**total 4** <br>
-rw-r--r-- 1 root root 612 Jan 23 16:26 index.nginx-debian.html

## Creating a new page:
1. sudo nano /var/www/html/index.html
2. <!DOCTYPE html>
<html>
<head>
<title>My Custom Webpage</title>
</head>
<body>
<h1>Welcome to My Custom Nginx Webpage!</h1>
<p>This is my first custom webpage on Azure.</p>
<img src="image.jpg" alt="Custom Image">
</body>
</html>

<br>

Got the new webpage up and running and also managed to get the image working as well
To download image curl "input url here" --output cat.jpg


#!/bin/bash = used to specify the language for it to read
* update = sudo apt update

* upgrade= sudo apt upgrade -y

* install nginx= sudo apt install -y

* restart nginx= sudo systemctl restart nginx

* enable nginx - enabled means it will start up when virual machine starts up = sudo systemctl enable nginx

* "mv" moves files and renames file <br>
* "cp" copy command <br>
* "rm" "-r" is to remove, and then adding that to the end of rm means recurssively <br>
* "echo" = display to the screen <br>
* "tree" = show the whole directory <br>
* "sudo wget --output-document=cat.jpg https://www.wallpaperflare.com/static/260/510/512/muzzle-cat-whiskers-eyes-wallpaper.jpg" = to download the image
* "cd .." = change directroy to to the parent one
* "cat" = displays the information inside the file.
* "pwd" = print working directory
* "cd /" = Go to root directory
* "head -2" = display the first 2 lines of a file
* "tail -2" = display the last 2 lines of a file

## Processes
* "ps aux" = gives all the processes use "top" for the live view of the processes- refreshed every 3 seconds
* "sleep "&"" = The & means the process will run in the background
* "kill -l" = softest level of kill for process
* "kill" = medium level of kill (gracefully)
* "kill -9" = Harshes of the kills to force the process to be killed
* 

* To reference a variable you have to use "$" before the name of it