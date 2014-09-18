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

Taking captures for App Store
---

Layout with Auto Layout and take screen captures in all device sizes.
Also you can i18n.

This is the scalable way to take screen captures.

Concerns
---

- How to acheive taking AppStore screenshots?
  * Leveraging AutoLayout, it is able to render screenshots with texts.
