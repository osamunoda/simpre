# simpre
Requirement : Mac( Yosemite~ , Safari ver8~ ), FileMaker ver14~, standalone(FileMaker sharing not supported)

This is a presentation tool built on FileMaker.

tutorial video : https://www.youtube.com/watch?v=y_DB3RVshCg

- change log -
06/13/2016 :
New presentation 'FileMaker with JSON' is added.
Bug fix: CSS default value calculation ( in each slide - advanced option )

06/15/2016 : 
Add '-webkit-' prefix to flex and some other properties.

06/16/2016
add prefix : animationend --> webkitAnimationEnd

Now
Simpre Requirement changes to 
Safari ver8.0.8~

08/08/2016 : 
Simpre controller is availbale.
Open simpre( which is hosted by Mac ) using your iPhone(FileMakerGo)!
 
 * use-device-orientation option:
 I know it's nonsense, but just for fun.Tilting the device more than 45 degrees, you can go and back in the slideshow.
https://www.youtube.com/watch?v=TPnpSnX2czE
 
 
 04/18/2017
 update for OSX 10.12.4
 Changed the file path specification in the webviewer
 
 ~0SX10.12.3  “file:/“ & Get(TemporaryPath) & targetFile 
 (This was the basic pattern.But now, invalid.)
 
 OSX10.12.4~  “file:/volumes“ & Get(TemporaryPath) & targetFile 
 ( Now this pattern is valid.)
 
 It seems that the path handling in the WebViewer engine has changed, I think.
 
 
 07/18/2017
 Simpre2 is released.
 This repository is renewed as simpre2.
