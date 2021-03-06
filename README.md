## CircularCollectionView
Circular Collection View along with circular scroll title view.

This component is used for creating a circular collection view along with title in a scroll bar for those collection views.
This can be useful for presenting multiple view controllers in one screen in a nice scrollable way.

## Pod
You can use following command for integrating via cocoapods:
```
pod 'CircularCollectionView'
```
## Example
(This is after 2 mins of integrating the controller.)

![demo](http://i.imgur.com/x7uMtQB.gif)

# With arrow

![arrow](http://i.imgur.com/uJLXJlr.gif)

## How to use ?

1> Import JCECircularCollectionViewController.h into your code.
```
#import "JCECircularCollectionViewController.h"
```
2> Initialize JCECircularCollectionViewController with a title array and your view controllers.
```
JCECircularCollectionViewController *circularCollectionViewController = [[JCECircularCollectionViewController alloc] initWithTitleArray:titleArray dataViewControllers:@[vc1, vc2, vc3, vc4]];
```
3> To show arrow set the show arrow flag and give arrow color.
```
circularCollectionViewController.showArrow = YES;
circularCollectionViewController.arrowColor = [UIColor whiteColor];
```
4> That's it. Now you can use circularCollectionViewController as you want.

## Todo's

1> Include example project.
2> Make it more customizable.


