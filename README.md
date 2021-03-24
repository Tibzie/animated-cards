# animated-cards

On-hover cards to use with different animation (animation directions, zoom animation) + scroll behaviour + 90deg navigation.  
I commented out the "lazy" scrolling behaviour setting. It's there if "aggressive" one does not fit anyone's need.

This bit below is commented out. (it's there to use tho)
```
scroll-snap-type: y proximity;
``` 
I personally prefer this:
```
scroll-snap-type: y mandatory;
```
Bear in mind, that accoding to https://developer.mozilla.org/, 
```
scroll-snap-type: y
```
is deprecated. However, some browsers may still support it (It works for me on Chrome...)
