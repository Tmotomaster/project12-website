# The website for Project 12

This website contains all the latest client game files to download and play Project 12.  
***These game files are currently configured to connect to the default game server! If you are hosting your own session, you may need to set up and configure [project12-local](https://github.com/Tmotomaster/project12-local)!***


## How to configure on Ubuntu Server using nginx

1. Install nginx using apt (`sudo apt install nginx`).
2. Start and enable nginx if necessary (see status with `systemctl status nginx`, then if needed, do `sudo systemctl start nginx` and then `sudo systemctl enable nginx`).
3. Import these files to your website folder (by default, it's `/var/www/html/`) for example by using `git clone` and extracting files there. You may need `sudo` privileges for this.
4. Using your favorite web browser, enter your server's ip address into the URL bar (you may need to prepend `http://` to your address especially if you don't have HTTPS).
5. If you get a blue page with three buttons, your website should be working! Congratulations! Now you may test downloading the latest[^1] version of Project 12!

[^1]: You will need to update your website regularly to actually serve newer versions!
