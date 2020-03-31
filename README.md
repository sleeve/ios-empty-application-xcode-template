# iOS Empty Application Xcode Template

This used to be a default template included with early versions of Xcode but it was removed in Xcode 6 and is still missing in modern versions of Xcode. Unfortunately some older iOS development books, projects and tutorials were written specifically using this empty template as the starting point. Most of the other versions floating around of this template are just the raw template file taken from Xcode 5. This old template has some issues running on more recent versions of Xcode though. This updated template includes a few improvements that make it actually functional.

It works with the latest Xcode 11 for both Objective-C and Swift 5.x and doesn't rely on a storyboard. It also features a cleaned up modern icon that matches the latest design language of the other templates. It works nicely when creating small test apps with programmatic views or just starting a fresh project without the storyboard cruft.

![empty_template-xcode_11 4](https://user-images.githubusercontent.com/499487/78055191-022ba900-7338-11ea-8336-e0e266e3991c.png)

![sim_empty_application_xcode11](https://user-images.githubusercontent.com/499487/67164330-64ff2a00-f32e-11e9-8171-67ed6727b106.png)

## Installation
The recommended install method is to place `Empty Application.xctemplate` within:
```
~/Library/Developer/Xcode/Templates/Application/
```
If you just place it in the root `Templates` directory the template will appear at the bottom of the Xcode project creation screen. If you create an `Application` subdirectory though and then stick it in there it will appear in the same `Application` section as all the other project templates.

## Color
I changed the default window background from White to Cyan to make it easier to see when the AppDelegate loads. The Launch Screen image/storyboard default color is white so it was impossible to see when the AppDelegate actually loaded when the background color was white. Feel free to change it to whatever color you want. 🎨 

## Related links
If you're curious about doing some more Xcode Template customization these are some great places to start.
* https://littlebitesofcocoa.com/90-custom-xcode-project-templates
* https://littlebitesofcocoa.com/89-custom-xcode-file-templates
* https://www.telerik.com/blogs/how-to-create-custom-project-templates-in-xcode-7
* https://robots.thoughtbot.com/creating-custom-xcode-templates
* https://stackoverflow.com/questions/37664281/how-to-create-a-project-template
