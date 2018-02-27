# LocalSlideshow

LocalSlideshow is a single html static file that allows you to specify a local folder and it display a slideshow of the pictures in this folder and any sub-folder. Nothing is uploaded to any server. Everything is kept locally in your browser. This works offline if you save the page first.

There's not many bells or whisles. This was just a little experiment to build the most lightweight tool for this without using external dependencies.

Pull requests to improve or add functionalities are welcome.

One of the main missing thing is a loading indicator while the browser reads the folders. I tested with 21k files in 200+ sub-folders. It works but takes a good few minutes to reach loading the first image.

# Compatibility
Uses webkitdirectory [https://caniuse.com/#search=webkitdirectory] so this page is currently only compatible with Edge, Chrome and Firefox as well as their derivative. The mobile versions of these browsers may not support this yet.

# Minimalism
The whole code of the slideshow page is less than 9KB or 200 lines of pure html + CSS + JS.
