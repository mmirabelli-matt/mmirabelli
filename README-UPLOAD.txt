MATTHEW MIRABELLI PHOTOGRAPHY
UPLOAD-READY WEBSITE
====================

This folder contains the finished website. You do not need to install anything,
run a build, or set up a database.

PAGES INCLUDED
--------------
index.html               Home
press/index.html         Press gallery (61 photographs)
sports/index.html        Sports gallery (46 photographs)
weddings/index.html      Weddings, including 107 gallery photographs
biography/index.html     Biography and awards
contact/index.html       Contact details

The photos, audio and assets folders must stay beside these HTML files.

HOW TO UPLOAD WITH FTP
----------------------
1. Unzip the downloaded file on your computer.
2. Open the folder named mmimages-website.
3. Connect to your web host with your FTP application.
4. Open your host's public website folder. It is usually called public_html,
   htdocs or www.
5. Upload EVERYTHING INSIDE mmimages-website into that public folder,
   keeping the same folder structure.
6. Make sure index.html lands at the TOP of the public folder, not inside an
   extra mmimages-website subfolder.

The finished structure should look like this:

public_html/
  index.html
  README-UPLOAD.txt
  assets/
  photos/
  audio/
  press/
  sports/
  weddings/
  biography/
  contact/

Then visit your domain in a browser. If your old website is still there,
check that you uploaded to the same public folder your domain uses.

IMPORTANT
---------
These files use addresses beginning with /photos and /assets. Upload the site
at the root of your domain (for example www.mmimages.com), not inside a
subfolder such as www.mmimages.com/portfolio.
