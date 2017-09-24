How to Install TeamViewer on your Debian 64 bits.
-------------------------------------------------
----------


 - Get the [team viewer.deb](https://download.teamviewer.com/download/teamviewer_i386.deb) from the official page.
 - On the Downloads directory or whatever directory you saved the .deb
   run this command with SU Privileges:

<pre><cod>dpkg --add-architecture i386</code></pre>

 - Update your repositories

<pre><code>apt-get update</code></pre>

 - Also install needed libraries
 
 <pre><code>apt-get install libdbus-1-3:i386 libasound2:i386 libexpat1:i386 libfontconfig1:i386 libfreetype6:i386 libjpeg62:i386 libpng12-0:i386 libsm6:i386 libxdamage1:i386 libxext6:i386 libxfixes3:i386 libxinerama1:i386 libxrandr2:i386 libxrender1:i386 libxtst6:i386 zlib1g:i386 libc6:i386</code></pre>
 
 - Install Team Viewer

<pre><code>dpkg -i teamviewer_*.deb</code></pre> 

 - That's it! :simple_smile:
