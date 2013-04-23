ios-back-forward-button-images
==============================

Triangular back and forward button images that one might use in an iOS app, for
example.  The images resemble the ones used by Safari and Firefox.

License: public domain.

Format: SVG and PNG.

These images are suitable for toolbar and navigation bar buttons on an iPad or
iPhone as of April, 2013.  For convenience, each SVG image has been rendered at
20px and 40px high.  For devices beyond the iPhone 5 or third generation iPad,
re-export from the .svg source files will probably be in order.

Drag the .png images into your project and use in the normal way, e.g.:

    backButton = [[UIBarButtonItem alloc] initWithImage:[UIImage imageNamed:@"backbutton"]
                                          style:UIBarButtonItemStylePlain
                                          target:self
                                          action:@selector(goBack)];
