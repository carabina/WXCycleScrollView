# WXCycleScrollView
WXCycleScrollView is a scrollable image banner using Swift

# Requirements
* iOS 10.0 or later
* Swift 3.0

# Usage
Instance WXCycleScrollView and set WXCycleScrollViewDelegate,set images by setting property images,set web image by setting imageUrlStrs,and set titles by setting titles.
```
    cycleScrollView = WXCycleScrollView(frame: CGRect(x: 0, y: 0, width: view.bounds.width, height: 240))
    cycleScrollView?.delegate = self
    cycleScrollView?.imageStrs = imageStrs
    cycleScrollView?.titles = titles
```
Implement func in WXCycleScrollViewDelegate to deal the click event on image
``` 
    func cycleScrollView(_ cycleScrollView: WXCycleScrollView, didSelectAt index: Int) {
        //your code
    }
```
