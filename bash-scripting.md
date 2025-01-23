## Commands

* sudo apt update: To update all packages for Linux
* sudo apt upgrade-y: used to upgrade and answer all questions yes to prevent any questions being asked


* update = sudo apt update

* upgrade= sudo apt upgrade -y

* install nginx= sudo apt install -y

* restart nginx= sudo systemctl restart nginx

* enable nginx - enabled means it will start up when virual machine starts up = sudo systemctl enable nginx



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

Got the new webpage up and running however wasn't able to implement the new image.


