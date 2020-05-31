## Commands for ArtSaver Server
|Command|Purpose|
|-------|-------|
|BLANK  |Blanks the screen. Useful if inappropriate image appears in a public setting.|
|UNBLANK|Unblanks the screen.|
|ADVANCE|Advances to the next image|
|BACK(n)|Go backwards n images. n must be provided; typically it will be 1|
|ROTATE(deg)|Rotate image by deg degrees. Typically deg will be 90,180,or 270. Rotation must be enabled on server and client must have write access. Returns UID of rotated image|
|HIDE|Hide this image from this set. Client must have WRITE access. Returns UID of hidden image.|
|UNHIDE(uid)|Unhides image uid. Client must have WRITE access.|
|GETINFO|Provides a dictionary of information about the current image, including (uid)|
|SHOWINFO(mask)|Show information described by mask on the screen|
|UPDATEINFO(dict)|Update information to the image. Requires WRITE access|
