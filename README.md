# iOS Empty Application Xcode Template
I wanted an empty iOS application template for Xcode 10 that didn't rely on a storyboard. It works nicely when creating small test apps with programatic views or just starting a fresh project without the storyboard cruft.

![xcode_empty_application_retina](https://user-images.githubusercontent.com/499487/42140791-86f6753e-7d58-11e8-8361-fe74594367db.png)
![sim_empty_application_retina](https://user-images.githubusercontent.com/499487/42140793-893ac5ca-7d58-11e8-822f-7b8538d4e7f3.png)

## How do I install it?
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
