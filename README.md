# My personal website

This is my website repository while I learn HTML and CSS and whatever.

## Deployment Process

*   Procure, e.g., a GCP compute instance.
*   Follow a [webserver setup guide](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-centos-7)
    * Be sure to follow the VirtualHost setup section as well
*   Install `git` and [set up a bare repo](https://git-scm.com/book/en/v2/Git-on-the-Server-Getting-Git-on-a-Server)
*   Set up some [post-receive hooks](https://www.digitalocean.com/community/tutorials/how-to-use-git-hooks-to-automate-development-and-deployment-tasks)
*   Locally, `git remote add` the webserver, and push to it to deploy!
