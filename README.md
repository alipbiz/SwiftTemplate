## Swift MVVP Template

A Xcode Template for Generating minimum required files to create a module with MVVM model in Swift.
When the template is installed, it will create a View Controller, View Manager, Logic Manager, View Nib hooked up with View Manager and View Model to follow the standard Model-View-ViewModel ([MVVM][href]) design pattern.
[href]: http://artsy.github.io/blog/2015/09/24/mvvm-in-swift/
### Install
If you are using If you are using [Alcatraz][href], you should be able to download it from there.

[href]: https://github.com/supermarin/Alcatraz

If you aren't using Alcatraz, just type the commands below in terminal.

    $ git clone https://github.com/freesuraj/SwiftTemplate.git
    $ cd Swift MVVM
    $ ./install-templates.sh

* Using Node.js

Alternatively, if you want to create the templates without relying on Xcode, you can do so by using following commands

    $ git clone https://github.com/freesuraj/SwiftTemplate.git
    $ cd node
    $ npm install
    $ node app.js -c ModuleName -d Directory/To/Save

### Uninstall
      $ ./uninstall-templates.sh

### Usage
* After you've installed the template in Xcode, restart the Xcode. In your Xcode project, when you create a new file, you can select **Swift MVVM** as follows.
![ScreenShot](https://raw.githubusercontent.com/freesuraj/SwiftTemplate/master/Screenshot.png)
