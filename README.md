# UnRaid Docker Templates (sethcarstens)

##Applications

- CloudFlare-DDNS

##Description

unRAID Docker Templates for Docker images in the "sethcarstens" repository.

##Usage

First, you need to be running unRAID ver 6.X.X or later, once installed follow the instructions below. If you are looking for references on how to setup your UnRaid server, you can check out the [forums](http://lime-technology.com/forum/) at  or you can try following the documentation I made for myself on github, that I follow when I setup a new unraid server.

https://github.com/scarstens/unraid-setup

### Automatic Repositories
LT (Lime-Technology) now recommends the use of the Applications Plugin in order to find and install both plugins and docker containers. Please see this thread for more details. http://lime-technology.com/forum/index.php?topic=37958.0

### Manually adding repositories
1. Navigate to "Docker" tab and then the "Docker Repositories" sub-tab in the unRAID webui
2. Enter in a URL of https://github.com/binhex/docker-templates in the "Template repositories" field
3. Click on the "Save" button
4. Click back to "Docker" tab and then click on the "Add Container" button
5. Click on the "Template" dropdown menu and select the desired Docker image
6. Click the "Advanced View" toggle on the top right and fill in required fields e.g. volume data, environment variables etc
7. Click on the "Create" button at the bottom of the window to begin pulling down the Docker image
8. Once the image is downloaded you should see it appear in the "Docker Containers" sub-tab

## Say Thanks?

If you appreciate my work, then please consider buying me a beer  :D

[![PayPal donation](https://www.paypal.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=DMEDRB9WT358S)
