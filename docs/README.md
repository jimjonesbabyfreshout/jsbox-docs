*This document is based on [Docsify] (https://docsify.js.org ) Deployed on [GitHub] (https://github.com/cyanzhong/jsbox-docs ), welcome to improve together*

# JSBox APIs

It provides a powerful extension for JSBox through JavaScript, supports ES6 standard syntax, and provides a rich API to interact with native code.

# JSBox Node.js

Starting from 2.0, JSBox provides access to Node.js runtime support. For the content of this part, please refer to the special documentation:https://cyanzhong.github.io/jsbox-nodejs/#/

# How to run code in JSBox

-Write directly in JSBox

  > JSBox has a built-in simple js editor, which currently only provides basic code highlighting and auto-completion. A better editor will be provided with future version updates.

-Online installation via URL Scheme

  > For example, by clicking on the iOS device: jsbox://import?url=url&name=name&icon=icon
  > The JSBox automatic installation script will be opened, which supports 3 parameters: `url`, `name` (optional), and `icon` (optional), all of which require URL Encoding.
  > For the specific name of icon, please refer to:https://github.com/cyanzhong/xTeko/tree/master/extension-icons
  > Please use the pure English name in the online file URL

-Synchronous editing via VSCode plug-in

  > 1. Open any script in JSBox, enter the settings page to open the debugging mode
  > 2. After returning to the desktop, reopen the application, open the settings Tab to view the local HOST
  > 3. Search for and install the 'JSBOX` plugin in VSCode's extension store
  > 4. Open the JavaScript file in VSCode, click the'set Host` option in the menu to fill in the HOST in Step 2
  > 5. At this point, after editing and saving the JavaScript file, it will run synchronously to the JSBox application

-Transfer script via AirDrop

  > You can transfer the script to JSBox via file sharing or AirDrop, but you need to manually synchronize the imported script
  > Synchronization can be performed through a script similar to this sample:https://github.com/cyanzhong/xTeko/blob/master/extension-demos/sync-inbox.js

-Use your creativity and use the interface provided by JSBox to get scripts

  > For example, this example:https://github.com/cyanzhong/xTeko/blob/master/extension-demos/addin-gallery.js

# Open source project

In order to provide more sample code, we have prepared an open source project:https://github.com/cyanzhong/xTeko

Welcome to improve this project together, through [Submit Issue] (https://github.com/cyanzhong/xTeko/issues/new ) or [Submit PR] (https://github.com/cyanzhong/xTeko/compare ) and other contribution methods.

# Contact us

If you have any questions about the document, you can contact us in the following ways：

- Email: [log.e@qq.com](mailto:log.e@qq.com)
- Weibo: [@StackOverflowError](https://weibo.com/0x00eeee)
- Twitter: [@JSBoxApp](https://twitter.com/JSBoxApp)

*Ready, [quick start>] (quickstart/intro.md)*

> This document is currently in the testing phase and may be subject to changes in the future. If there are any errors, please correct them.
