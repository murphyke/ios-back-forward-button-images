ios-back-forward-button-images
==============================

Triangular back and forward button images that one might use in an iOS app, for example.
The images resemble the ones used by Safari and Firefox.

License: public domain.

Format: SVG and PNG.

These images are suitable for toolbar and navigation bar buttons on an iPad or iPhone as of April, 2013.
For devices beyond the iPhone 5 or third generation iPad, one would have to re-export from the .svg source files.

Drag the .png images into your project and use in the normal way, e.g.:

    backButton = [[UIBarButtonItem alloc] initWithImage:[UIImage imageNamed:@"backButton"]
                                          style:UIBarButtonItemStylePlain
                                          target:self
                                          action:@selector(goBack)];
