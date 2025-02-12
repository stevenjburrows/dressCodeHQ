# dressCodeHQ

The demo html file is to show the usage of each component.  The components will be in the component folder in separate files with the idea that you can add them in any order you want and just make the small changes you need.

a couple of things that will be true for any of theses components.  

- To change an image replace the url, remember everything is relative to the index.html file so in my examples they all start with `/image` as I have them all in the image folder.  Just remember to add any folder names you add to this folder.
- To change a url of a link replace the href path.  This is the only one that is not relative to the index.html file. even linking to an internal page it is better to give it the full URL



# Templates

## HTML template

This is just the basic boiler plate for an html file.  Just add the components you want to the body of the file.  Also make sure the path to the css file is correct.

## Headers

I have added 4 header templates in the components folder.  you have just a simple text header, a text header with a link, a header with a background image and a header with a background image with a link.  This should give you he basics for each.

## Parallax Images

I have added 2 parallax image templates in the components folder.  you have just a simple parallax image and a parallax image with text.

## Paragraphs

I haven't added a compenent for paragraphs as all you do is put the text bewtween the `<p></p>` tags.

## Video section

I have added a YouTube video template in the components folder. One with no formatting and one where it is centred in the container.  This is pulled from YouTubes website and all you need to do is change the `src` attribute to the video you want.  Also alter the height and width to what you need.  I would always recommend using a video hosting service such as YouTubes as it gives a better performance.

## Images

I have added a basic image template in the components folder.  This is pulled from the image folder and all you need to do is change the `src` attribute to the image you want.  Also alter the height and width to what you need.  You can also add a class of `center-video` to the image if you want it to be centred in the container.

If the image is decorative then leave the alt attribute blank but if the image is not decorative then add a description to the alt attribute.  You do not need to add the word image in the description.
