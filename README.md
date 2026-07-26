# Miningcore_WebUI
Web UI that runs on standard html servers for Miningcore using the port API calls. Tested with RetroMike's verson of Miningcore. Can be installed directly into a www folder or can be installed along with the Apache Docker install script. If deploying publically, change the favicons and support link urls. Also setting a conical link will service search engines efficantly. Add the link: ``` <link rel="canonical" href="https://mining_pool_example.com/" /> ``` to your website url as the first link in index.html

This webui requires it to be installed on a webserver Miningcore is running. If using a docker version like RetroMike's Miningcore you can install it by simply downloading dockerwebui.sh and executing it as root on your machine ``` sudo ./dockerwebui.sh ```. This will install apache web server and create a www folder in the /var directory of the docker host drive. If you need to install SSL certificates, you will need to access the apropriate config file in /etc/apache2/sites-available in the apache docker container via SSH with the command:```  docker exec -it apache bash ```

This is a fork from https://github.com/minernl/Miningcore.WebUI and offers a more modern look on the index page with a basic monocolor color scheme in the other sections. Scripts have been tested with RetroMike's Miningcore docker installation.

