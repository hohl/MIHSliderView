MIHSliderView
=============

MIHSliderView is a Core Animation slider view for OS X. Any subclass of NSView can be displayed as a slide and integration into your project is as easy as using any other view since it is just a single file NSView subclass.

After you have added the slider view with the Interface Builder you can add slides to it as easy as the following lines of code:

``` objective-c
NSImageView *imageView1 = [[[NSImageView alloc] init] autorelease];
[imageView1 setImage:[NSImage imageNamed:@"MySlide1.png"]];
[self.sliderView addSlide:imageView1];
    
NSImageView *imageView2 = [[[NSImageView alloc] init] autorelease];
[imageView2 setImage:[NSImage imageNamed:@"MySlide2.png"]];
[self.sliderView addSlide:imageView2];
    
// ...
```


How To Get Started
------------------

You either can drag & drop the `MIHSliderView.h` and `MIHSliderView.m` into your project or use CocoaPods to add the dependency. If you choose the drag & drop solution you have to link your application against the [QuartzCore.framework](http://developer.apple.com/library/mac/#documentation/graphicsimaging/reference/QuartzCoreRefCollection/_index.html "Quartz Code Framework Reference").

For details on how to use the MIHSliderView have a look at the interface deceleration and read the comments.



What It Can Look In Production Use
----------------------------------

*Attention: The following image is from closed source project which uses the MIHSliderView component and the images and source codes of this project are not contained by the MIHSliderView project and license!*

![MIHSliderView Sample Usage](https://raw.github.com/hohl/MIHSliderView/master/Project/SampleUsage.png)
