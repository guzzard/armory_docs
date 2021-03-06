# Contents

This section covers HTML5 specific topics.

# Building for HTML5

## Browser

Select *HTML5* in *Properties - Render - Armory Project - Target*. Hit *Publish* to export HTML5 files.

![](img/html5/0.png)

Resulting files will be located at *your_blend_file_location/build/html5*.

*Note that you need to copy these files to a web server or start a local server. Otherwise you will get a cross-origin error when opening index.html directly due to security reasons of web browsers. When playing HTML5 project from Blender, Armory starts a local server automatically. With Python installed, you can start the local server from terminal using `python -m SimpleHTTPServer` in build/html5 directory and then navigate to the http://localhost:8000 in your web browser.*

![](img/html5/1.png)
