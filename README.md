# iOS Empty Application Xcode Template

This used to be a default template within earlier Xcode versions but Apple removed it in Xcode 6. Unfortunately some older iOS development books and tutorials were written with this template as the starting point.

This template works on the latest Xcode 11 for both Objective-C and Swift and doesn't rely on a storyboard. It also features a cleaned up icon that looks great next to the other default template icons. It works nicely when creating small test apps with programmatic views or just starting a fresh project without the storyboard cruft.

![empty_application_xcode11](https://user-images.githubusercontent.com/499487/67164258-55331600-f32d-11e9-91e8-69aa3428a40e.png)
![sim_empty_application](https://user-images.githubusercontent.com/499487/42141444-26f3a200-7d5e-11e8-875d-b7cfeafabfe5.png)

## Installation
The recommended install method is to place `Empty Application.xctemplate` within:
```
~/Library/Developer/Xcode/Templates/Application/
```
If you just place it in the root `Templates` directory the template will appear at the bottom of the Xcode project creation screen. If you create an `Application` subdirectory though and then stick it in there it will appear in the same `Application` section as all the other project templates.

## Related links
If you're curious about doing some more Xcode Template customization these are some great places to start.
* https://littlebitesofcocoa.com/90-custom-xcode-project-templates
* https://littlebitesofcocoa.com/89-custom-xcode-file-templates
* https://www.telerik.com/blogs/how-to-create-custom-project-templates-in-xcode-7
* https://robots.thoughtbot.com/creating-custom-xcode-templates
* https://stackoverflow.com/questions/37664281/how-to-create-a-project-template
