# iOS 10 Animation demo

If you like **DotsAnimation**, or the code was useful for you, please, give your :star: to this repository. 

**DotsAnimation sample** is a sequence of series of different, separate animations, created to demonstrate usage of iOS 10 Animations API, described in [the article](http://handsome.is/crafting-delightful-animations-in-ios-10/).

![Dots Animation Gif](https://user-images.githubusercontent.com/2081318/28453452-474e46e0-6e19-11e7-9dc0-74b463d11f9b.gif "Dots Animation")

### Here are some of the things that you’ll find in the code
 
 * Creating of Animation Objects using custom timing functions:
    * Cubic Bézier curves;
    * New *UISpringTimingParameters* that allow manipulating the mass, stiffness, damping, and initial velocity parameters;
 * Adding new animation blocks to existing objects on the fly (take a look into *ViewController.startReversedDotsAnimation* method);
 * Adding completion action on the fly (it's used to begin new animations phase, when the third dot is finishing its last jump);
 * Other possibilities of working with *UIViewPropertyAnimator* objects.
 
### Requirements
- iOS 10.0+
- Xcode 8.1+
- Swift 3.0+

### License

Sample is released under the Apache License, Version 2.0. See [LICENSE](./LICENSE) file for details.



