AutomatedScreenshots-iOS
========================

Automatically take screenshots of iPhone 4S, iPhone 5S, iPhone 6, iPhone 6 Plus, iPad, iPad mini.

Background
---

There are too many screen sizes and it seems really hard to keep the layout safe.
Because iOS had kept its screen width 320px, there are many AutoLayouts which assumes 320px width.
To solve this, it seems to be nice to take screenshots in all devices automatically.

(And it also can be used to take screenshots for AppStore release.)

Here is list of iPhone screens. http://www.iphoneresolution.com/

How?
---

Use `KIF` and `KIScreenshot`.

1. To demonstrate interaction, use `KIF`.
2. To take a screenshot, use `KIScreenshot`

They should be achieve in `XCTest`.

To do this in many devices, simply write shell for it. To perform test, use `xcodebuild`.

