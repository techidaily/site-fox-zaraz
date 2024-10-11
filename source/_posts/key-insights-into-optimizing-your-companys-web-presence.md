---
title: Key Insights Into Optimizing Your Company's Web Presence
date: 2024-10-04T04:20:18.596Z
updated: 2024-10-10T18:42:42.068Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Key Insights Into Optimizing Your Company's Web Presence
thumbnail: https://thmb.techidaily.com/1c9229fb0800113350dfae57f612d2aef9036646b6591dcd5ed2f832a16cf380.jpg
---

## Key Insights Into Optimizing Your Company's Web Presence

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Organization](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Search Pane](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Feature Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Component Properties](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Feature Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Builds](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Analytics](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [SCCM](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [ActiveSync](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Organization Page

Windows Installer organizes a product in features and components. A feature is a set of components that are installed together. A component is a piece of the product to be installed and it is the smallest piece of a product that Windows Installer can install.

![Organization page](https://cdn.advancedinstaller.com/img/ui/organization-page.png "Organization page")  

This page allows you to create new features and to select which components belong to a feature. In the left pane there is a tree that hierarchically displays the product's organization. On the first level of the hierarchy there are the features. A feature can contain sub-features and components. A component is made of resources. A resource can be a file, a folder, a registry key or value, a data source, a shortcut, an extension, an environment variable, a service installation, a service operation, an ODBC driver or an ODBC translator. 

Every component has a key resource that can be only a file, a folder, a registry key or value or a data source. The resources are displayed under their component. The key resources are displayed with a key overlaid over the resource's usual image. During an installation Windows Installer decides which features to install along with all the sub-features and the components of the selected features. When a component is installed, all the resources of that component are installed (and only then).

### Organizing components

The components in an Advanced Installer project are created by following the Windows Installer rules and best practices. Therefore, you should follow these rules when reorganizing your installation package:

* Never create two components that install a resource under the same name and target location.
* Two components must not have the same key path file.
* Do not create components containing resources that will need to be installed into more than one directory on the user's system.
* Do not include more than one COM server per component.
* Do not specify more than one file per component as a target for the Start menu or a Desktop shortcut.
* Define a new component for every .exe, .dll, and .ocx file and designate these files as the key path files of their components.
* Define a new component for every .hlp or .chm help file and designate these files as the key path files of their components.
* Define a new component for every file that serves as a target of a shortcut and designate these files as the key path files of their components.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Creating components which don't respect these rules may result in an installation package which doesn't work correctly.

### Creating new features

![New Feature](https://cdn.advancedinstaller.com/img/toolbar/feature-new.png "New Feature") Use the \[New Feature \] toolbar button, the “New Feature” tree context menu item or press the Insert key while the “Features And Components” panel is focused. The new feature will be added after the last sub-feature of the selected feature. The feature will get a default name, which you can edit anytime. 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151872/7443" target="_top" id="2151872">
  <img src="//a.impactradius-go.com/display-ad/7443-2151872" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151872/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)When a new component is created and there is no feature in the project, a new feature, named "MainFeature" will be automatically created. Also when you create a feature from this page and there is no other feature in the project, that feature will also get the name "Main Feature". All the components will be added by default in the "Current Feature".

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135409/19272" target="_top" id="2135409">
  <img src="//a.impactradius-go.com/display-ad/19272-2135409" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135409/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Renaming a feature

 Use the “Rename” tree context menu item or press the F2 key while a feature is selected. Only the features names can be edited. 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Renaming a component

 Use the “Rename” tree context menu item or press the F2 key while a component is selected. This identifier is used in conditions to refer to the installed state or the action state of a component.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)When changing the name of a component, all the conditions that refer to this identifier must be updated accordingly.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Moving a feature up, down, left or right

 Use the “Move Up”, “Move Down”, “Move Left” or “Move Right” tree context menu items or press Shift + Up, Shift + Down, Shift + Left or Shift + Right. When moving to the left, the feature will be moved after the last feature of its parent feature. When moving to the right, the feature will be moved after the last feature of the feature before it. You can also move features and components by drag and drop. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)A feature's position among its siblings is important because at install time, in the Customize dialog, the features will be displayed in the order they appear in the left tree.

### Setting the Current Feature

 Use the “Set As Current” tree context menu item. The Current Feature will be displayed in **bold** text. Newly created components for various resources (files, registry keys, etc.) will always be added to the Current Feature. 

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)You can also set the Current Feature using the drop-down list box in the toolbar of the Component-producing pages.

### Moving a component between features

 Drag and drop the component to the new feature. 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934288/19272" target="_top" id="1934288">
  <img src="//a.impactradius-go.com/display-ad/19272-1934288" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934288/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Moving resources between components

Use the drag and drop to move the resources (file, registry or data source etc) between components.

When moving resources between components the following restrictions must be taken into consideration:

* The files that are target for Service Installs, File Associations or Advertised Shortcuts, are made key members and cannot be moved into a new component.
* The files of CHI or CNT type cannot be moved. (they follow automatically the component of the corresponding CHM and HLP files)
* If a resource is the only one from the component that can be a key member(e.g. files) and the rest of the resources in the component cannot be key members(e.g. Environments),then the file cannot be moved.
* Resources can only be moved between components if they have the same Directory attribute.
* All the files related to a Java Product cannot be moved because they must be attached to the Java Product file.

### Moving a resource to a new component

Use the "Move To New Component" tree context menu item. The current resource will be moved into a newly created component, in the same feature.

### Setting a resource as Key Member

Use the "Make Key Member" tree context menu item.

### Locating a resource

 Use the “Go To Resource” context menu item or press the F8 key on a selected resource. This command will activate the appropriate page and will select the tree or list item corresponding to the resource.

### Sharing a component

 Drag and drop the component to a new feature while theShift key is pressed, use the “Share” context menu or ribbon button. The component will be present under both features. 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Sharing a feature

Drag and drop the feature to a new feature, while theShift key is pressed. All the components of the dragged feature will be present under both features.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118325/7443" target="_top" id="2118325">
  <img src="//a.impactradius-go.com/display-ad/7443-2118325" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118325/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding resources to the search list

Use the “Add to list” context menu item or press theF4 key while a tree item is selected.

Use the “Add Children to List” option or press theShift + F4 key to add all the item's children to the list.

### Removing features and shared components

![Remove Feature](https://cdn.advancedinstaller.com/img/toolbar/remove.png "Remove Feature") Use the\[Delete \] toolbar button, the “Delete” tree context menu item or press the Delete key while a feature or component is selected. 

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)A feature must be empty before you can remove it. A regular component cannot be removed, only a shared one. 

### Searching for a feature, component or resource

![Find](https://cdn.advancedinstaller.com/img/ui/search-icons/magnifier.png "Find") Type the label text that you want to search in the top right corner edit box. Press theEnter key to trigger the search.

![Find Next](https://cdn.advancedinstaller.com/img/ui/search-icons/down.png "Find Next") To search for the next value use the _Find Next_ button or press theF3 key. The search results are displayed in the[Search Pane](https://tools.techidaily.com/advancedinstaller/products/).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052059/7443" target="_top" id="2052059">
  <img src="//a.impactradius-go.com/display-ad/7443-2052059" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052059/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Find and Append](https://cdn.advancedinstaller.com/img/ui/search-icons/plus.png "Find and Append") Use the_Find and Append_ button to append the search results to the search pane list.

If you want to search for the whole word you must enclose the string from the combo in quotes (").

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The search is case insensitive.

## Topics

* [Search Pane](https://tools.techidaily.com/advancedinstaller/products/)  
Contains the results of the search.
* [Feature Properties](https://tools.techidaily.com/advancedinstaller/products/)  
Setting a Feature's properties in Advanced Installer.
* [Component Properties](https://tools.techidaily.com/advancedinstaller/products/)  
Setting a Component's properties in Advanced Installer.
* [Feature Picker Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
The "Feature Picker" dialog

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-skills.techidaily.com/updated-step-by-step-inserting-chapters-into-your-youtube-content/"><u>[Updated] Step-by-Step Inserting Chapters Into Your YouTube Content</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/capture-and-keep-best-five-extensions-for-fb-videos-for-2024/"><u>Capture and Keep Best Five Extensions for Fb Videos for 2024</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/complete-guide-restoring-lost-files-on-your-samsung-galaxy-using-the-galaxy-data-recovery-app/"><u>Complete Guide: Restoring Lost Files on Your Samsung Galaxy Using the Galaxy Data Recovery App</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/dynamic-wallpaper-change-the-editors-companion-list/"><u>Dynamic Wallpaper Change The Editor's Companion List</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/frustrating-tips-and-tricks-to-watch-your-dvds-on-windows-8/"><u>Frustrating Tips and Tricks to Watch Your DVDs on Windows 8</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-honor-magic5-ultimate-frp-by-drfone-android/"><u>Full Guide to Bypass Honor Magic5 Ultimate FRP</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-xiaomi-13-ultra-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Xiaomi 13 Ultra</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-zte-nubia-z60-ultra-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos From ZTE Nubia Z60 Ultra to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-lava-blaze-pro-5g-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Lava Blaze Pro 5G Phone FRP Lock</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/manage-your-profile-detailed-guide-to-navigating-account-preferences/"><u>Manage Your Profile: Detailed Guide to Navigating Account Preferences</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/navigating-the-complex-world-of-ai-as-a-mental-health-aide/"><u>Navigating the Complex World of AI as a Mental Health Aide</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/streamline-your-event-planning-with-advanced-editing-tools-and-features/"><u>Streamline Your Event Planning with Advanced Editing Tools and Features</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/ultimate-tutorial-how-to-stream-and-watch-flv-videos-on-your-android-device/"><u>Ultimate Tutorial: How to Stream and Watch FLV Videos on Your Android Device</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/wireless-connection-guide-linking-your-google-pixel-smartphone-with-a-windowsmac-computer/"><u>Wireless Connection Guide: Linking Your Google Pixel Smartphone with a Windows/Mac Computer</u></a></li>
</ul></div>

