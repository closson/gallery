A lightly interactive slideshow, made for ambience at special events like birthday parties, weddings, etc.  Created in 2012.  I was gathering pictures for a family birthday party, and was so underwhelmed with the style and features in free slideshow products I wrote my own.

The intent was to use jQuery just for DOM manipulation and browser events, and try out the new CSS3 animation capabilities.  At the time, only Safari had smooth enough framerates for my taste.  I considered adding captions along the bottom of the images like a Polaroid photo, but didn't have time and couldn't read the handwriting on most of them!  Adding pictures involves manually changing the code, since when it was developed I was handling everything myself and didn't need to make it user-friendly.

Some animation and behavior parameters can be changed on the fly.  For example, many people liked to sit down in front of the TV or projector and browse leisurely, either slowing down the rate of new pictures, or pausing it entirely and showing new pictures themselves.  It turned out to be a really popular feature, especially so the audience could share their memories to go along with the photos.

# Controls

Click any picture to bring it to the front of the pile.  Dragging pictures not supported.

P to pause or unpause the periodic addition of new pictures.

Space bar to show a new picture manually.  Doesn't affect the periodic additions.

F to go fullscreen.  Some browsers' behaviors have changed since 2012 and this doesn't work reliably; for example in Safari.

Q/E to change the animations' speed

A/S to change the period between adding new pictures.

# License/Copyright

Code and logic in index.html is unlicensed.  Have fun, go nuts.

All sample pictures were originally taken by my family and may not be reproduced, in part or whole, in any format.

[jQuery](http://jquery.com/) is included under the [MIT license](http://opensource.org/licenses/MIT).
