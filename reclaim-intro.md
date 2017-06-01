# Personal/project website examples

[Marisa Parham](http://mp285.com/)

[Whitney Trettien](http://whitneyannetrettien.com/)

[Nabil Kashyap](http://www.nabilk.com/)

[David Hartt](http://davidhartt.net/)

[Mel Chin](http://melchin.org/)

# Brainstorm: what could you do with your domain?

# Set up sites

[https://reclaimhosting.com/](https://reclaimhosting.com/)

# Reclaim basics

To edit your site, click on cPanel (in the menu bar along the top). This is your control panel, which will let you manage applications and edit/add files to the site.

## Working with applications

You can use various applications to build/design your site for you instead of coding it yourself (for example, Wordpress or Omeka). In the cPanel, click All Applications. Scroll through the options. Try installing one.

## Working with the file manager

From cPanel, click File Manager in the menu bar.

The public_html folder contains the files that generate the "front end" or visible part of your site. This is the folder you'll be working with when you edit your site.

# Exercise: html5up

[https://html5up.net/](https://html5up.net/)

Find a template that appeals to you and experiment with customizing it!

(If you don't have it already, try downloading [Atom](https://atom.io/), a text editor that will help you view and edit your website files.)

## Uploading an html5up theme to your Reclaim site

Reclaim's file manager is set up to only let you upload a single file at a time - frustrating if you want to use a complicated, multi-file html5up (or similar) theme on your site! One way around this is to use FTP (file transfer protocol - [see instructions here](https://community.reclaimhosting.com/t/ftp-file-transfer-protocol/304)). But if you don't want to set that up, here's a shortcut:

+ Create a zip file of the folder containing your edited html5up theme by selecting the folder (NOT the files inside) and compressing it.

![Compressing a folder](/html5up-images/html5up-0.png)

+ Open the Reclaim file manager. Open the public_html folder, then click Upload (in the gray menu bar). A page that looks like this will pop up. Upload your zip folder, making sure you're placing it in the public_html folder.

![Uploading a zip file](/html5up-images/html5up-1.png)

+ Click on public_html and find your zip file in the list of files inside the directory. Click the zip file to highlight it, then click Extract (in the upper left-hand corner) to unzip it. A window that looks like this should pop up. Make sure it's set up to extract the files to /public_html and click Extract File(s).

![Extracting files](/html5up-images/html5up-2.png)

+ You should now have an unzipped folder containing your html5up theme, inside public_html. Open it and click Select All in the white menu bar to highlight all the files inside.

![Selecting files](/html5up-images/html5up-3.png)

+ Click Move (in the top left-hand corner). A window like this will pop up, allowing you to specify what location you want to move these files to. Unless you want the html5up pages to appear only on a certain subdomain of your site (say, at yoursitename.org/html5uptest/), delete anything that comes after /public_html in the file path. Click Move File(s).

![Moving files](/html5up-images/html5up-4.png)

+ Refresh the home page of your site. Your theme should now be visible! If you make any additional changes to your theme, you can either re-upload the individual files you've changed or (if you've changed a lot) go through this process again.
+ Clean up your file manager by deleting the unzipped version of your theme folder and the empty folder where your layout files used to be stored (called html5up-hyperspace in this example).

# The future

Your Reclaim account will expire in a year. If you want to keep your site, you'll have the option to either renew it for $30/year or transfer your site to a free hosting service.

[To move a Wordpress site hosted on Reclaim to a free Wordpress URL, see these instructions.](https://en.support.wordpress.com/moving-from-self-hosted-wordpress-to-wordpress-com/)

[To create a backup of your Reclaim site (which will give you a copy of your files that you can use to transfer your site to a different domain), see these instructions.](https://community.reclaimhosting.com/t/generating-a-backup/293)

You might consider moving your site to [Github Pages](https://pages.github.com/), which will host it for free at yourusername.github.io. Example: this [Early Novels Database website](https://earlynovels.github.io/), created using Jekyll and hosted on Github Pages.
