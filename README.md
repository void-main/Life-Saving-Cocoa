Life-Saving-Cocoa
=================

Tell us the most life-saving cocoa APIs.

## Why
As a rookie Cocoa (Touch) developer, I got astonished from time to time by how much time I could have saved should I know that API earlier. That's why I started this repo, and hope my (and your) experience could save others' lives.

## Contribution
To contribute to the list, please fill-in the following fields:

```
### API Name
- Before: Time consuming way
- After: Life saving way
- Dependency: Does the API come with Cocoa or 3rd party libries. Omit if it comes with Cocoa.
```

And send me a pull-request. You can write the sample code with Objective-C or Swift (or both). 

Please make sure to sort the list in ascending alphabetic order when inserting your own life-saving API.

## The List
### NSStringFromRect
- Before: NSLog(@"Rect: %f %f %f %f", rect.origin.x, rect.origin.y, rect.size.width, rect.size.height);
- After: NSLog(@"Rect: %@", NSStringFromRect(rect));

