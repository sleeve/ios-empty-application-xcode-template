# iOS Empty Application Xcode Template
I wanted an empty iOS application template for Xcode 8 that didn't rely on a storyboard. It works nicely when creating small test apps with programatic views or just starting a fresh project without the storyboard cruft.

![image](https://cloud.githubusercontent.com/assets/499487/17272907/5a2fbb74-5658-11e6-9ee4-ed1775161158.png)

## How do I install it?
The recommended install method is to place `Empty Application.xctemplate` within:
```
~/Library/Developer/Xcode/Templates/Application/
```
If you just place it in the root `Templates` directory the template will appear at the bottom of the Xcode project creation screen. If you stick it in an `Application` directory though it will appear in the same section as all the other project templates.
