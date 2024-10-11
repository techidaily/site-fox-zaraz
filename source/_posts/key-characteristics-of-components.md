---
title: Key Characteristics of Components
date: 2024-10-09T04:15:13.196Z
updated: 2024-10-11T04:34:22.963Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Key Characteristics of Components
thumbnail: https://thmb.techidaily.com/2ca46c2a129dc1360b713c04a30f75e3e36c2cb0f971400d44a0a7430d69515d.jpg
---

## Key Characteristics of Components

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
                                             * [Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                                             * [Edit Component Policies Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Component Properties

![Component Properties](https://cdn.advancedinstaller.com/img/ui/component-properties.png "Component Properties")  

## General Properties

* GUID  
 A globally unique ID for this component, version, and language. Every component gets a default GUID at its creation, but you can change it anytime.
* Do not register this component with Windows Installer  
 If this option is selected the component will have an empty GUID, and thus it will not be registered. This means that the component cannot be removed, repaired or patched by the installer. This might be useful if you intend to service/uninstall the component yourself (using a custom action, for instance).
* Directory  
 This is the directory where the component will install. You can change the directory of a component by using the \[... \] button, but it must only contain empty folders or registries.
* Condition  
 A Windows Installer condition which is evaluated and the result determines the component's installation. If the condition is null or is evaluated to false, the component is not installed. Use the \[... \] button to [edit the conditional statement.](https://tools.techidaily.com/advancedinstaller/products/)

## Attributes

* Run From Source Only  
 The component can only be run from source.
* Optional  
 The component can run locally or from source.
* Shared DLL Reference Count  
 Windows Installer increments the reference count in the shared DLL registry of the component's key file.
* Permanent  
 This component is not removed during an uninstall.
* Transitive  
 Windows Installer reevaluates the statement from the Condition field after a reinstall.
* Never Overwrite  
 The component is not installed or reinstalled if a key path file or a key path registry entry for the component already exists. This affects only future installers which try to overwrite the component key path; it doesn't affect already installed resources.
* 64-bit Component  
 This component is marked as a 64-bit component.
* Disable registry reflection  
This option applies only to 64-bit systems with Windows Installer 4.0\. If this option is not enabled for a component, Windows Installer makes the associated registry changes in both 64 and 32-bit registry views.
* Uninstall on supersedence (Windows Installer 4.5 or higher)  
 The installation of a superseding patch can leave behind an unused component on the computer. To avoid this behavior, you can set this option. The same effect can be obtained for all components by setting the _MSIUNINSTALLSUPERSEDEDCOMPONENTS_ property to "1".
* Shared amongst packages (Windows Installer 4.5 or higher)  
This option marks the component as shared among multiple packages. In doing so, if a package containing this component is uninstalled, the highest version of it (installed by other packages) will still be shared by Windows Installer. It is enough to mark the component as shared in one package for it to become shared among multiple packages. If the_DisableSharedComponent_ policy is set to "1", this flag is ignored for all components.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)Shared components must have the same component GUID and the same key path resource. Also, their resources must be installed under the same location.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If registry reflection is disabled the changes are performed only in the targeted view.

## Additional space

This section allows you to reserve an amount of disk space in any directory that depends on the installation state of a component.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Folder

Specify the destination directory.

### Run Local

The number of bytes of disk space to be reserved if the selected component is installed to run locally.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### From Source

The number of bytes of disk space to be reserved if the selected component is installed to run from source.

## Qualified Components Groups

This section allows you to add the current component to a category of qualified components.

For example, let's say you have several components that contain resource DLLs with the localized strings for your application. You can group these components into a single category, using the qualified components feature.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding the current component to a category.

Use the \[New \] button, the “New” list context menu item or press the Insert key while the list control is focused. The[Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed allowing you qualify this component.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Editing the qualified properties

 Use the \[Edit \] button, the “Edit” list context menu item or press the Space key while the list control is focused. The[Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed allowing you to edit the qualified properties for the current component.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing the component from a category

Use the \[Remove \] button, the “Remove” list context menu item or press the Delete key while the list control is focused.

## Isolated Components

When creating an install package, you can specify if the installer should copy some files used by a certain application, in the application's folder rather than in a shared location.

Using Isolated Components have the following advantages:

* The application will always use the original files(the files it was installed with).
* Installing other applications that use the same files, but with a higher version, will ensure that the original files are not overwritten.

### Isolating a component

Use the \[Add... \] button, the “Add...” list context menu item or press the Insert key while the list control is focused. The Component Picker will be displayed allowing you to select a component. The selected component will be isolated with the current one.

### Removing an isolated component

Use the \[Remove \] button, the “Remove” list context menu item or press the Delete key while the list control is focused.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Add a component to a group of qualified components.
* [Edit Component Policies Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
Modify the Component Policies

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
<li><a href="https://youtube-blog.techidaily.com/xpert-director-sound-and-picture-synthesis/"><u>[New] Expert Director Sound & Picture Synthesis</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/he-strategic-use-of-tags-a-guide-to-youtube-success/"><u>[New] The Strategic Use of Tags A Guide to YouTube Success</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-experience-the-old-school-games-anywhere-with-best-in-class-pc-gb-emulators/"><u>[Updated] 2024 Approved Experience the Old School Games Anywhere with Best-in-Class PC GB Emulators</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/1-ultimate-guide-to-ifolder-sync-mastering-your-filters/"><u>1. Ultimate Guide to iFolder Sync: Mastering Your Filters</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-laughterbox-easy-entry-endless-entertainment/"><u>2024 Approved LaughterBox Easy Entry, Endless Entertainment</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-top-social-networking-grounds-for-youtube-growth/"><u>2024 Approved Top Social Networking Grounds for YouTube Growth</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/best-5-free-and-easy-to-use-pdf-editor-software-beyond-adobe-acrobat-in-2020/"><u>Best 5 Free and Easy-to-Use PDF Editor Software, Beyond Adobe Acrobat in 2020</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/effective-strategies-for-managing-file-replicas-conversations/"><u>Effective Strategies for Managing File Replicas Conversations</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/essential-guide-to-customizing-uniform-interface-design-in-tab-settings/"><u>Essential Guide to Customizing Uniform Interface Design in Tab Settings</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-lava-yuva-2-pro-easily-by-drfone-android/"><u>In 2024, How To Unlock a Lava Yuva 2 Pro Easily?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/latest-way-to-get-shiny-meltan-box-in-pokemon-go-mystery-box-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>Latest way to get Shiny Meltan Box in Pokémon Go Mystery Box On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/simple-techniques-for-mkv-video-subtitle-retrieval/"><u>Simple Techniques for MKV Video Subtitle Retrieval</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-dawn-of-voice-activated-chatgpt-in-cars/"><u>The Dawn of Voice-Activated ChatGPT in Cars</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/the-top-methods-for-seamless-music-transition-between-galaxy-s4-and-s6-edge-devices/"><u>The Top Methods for Seamless Music Transition Between Galaxy S4 and S6 Edge Devices</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/top-ranking-tools-for-effortless-text-removal-from-images/"><u>Top-Ranking Tools for Effortless Text Removal From Images</u></a></li>
</ul></div>

