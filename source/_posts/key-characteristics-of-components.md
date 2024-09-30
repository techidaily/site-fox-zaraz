---
title: Key Characteristics of Components
date: 2024-09-28T02:21:08.309Z
updated: 2024-09-29T23:36:06.083Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)If registry reflection is disabled the changes are performed only in the targeted view.

## Additional space

This section allows you to reserve an amount of disk space in any directory that depends on the installation state of a component.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Folder

Specify the destination directory.

### Run Local

The number of bytes of disk space to be reserved if the selected component is installed to run locally.

### From Source

The number of bytes of disk space to be reserved if the selected component is installed to run from source.

## Qualified Components Groups

This section allows you to add the current component to a category of qualified components.

For example, let's say you have several components that contain resource DLLs with the localized strings for your application. You can group these components into a single category, using the qualified components feature.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135403/19272" target="_top" id="2135403">
  <img src="//a.impactradius-go.com/display-ad/19272-2135403" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135403/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Adding the current component to a category.

Use the \[New \] button, the “New” list context menu item or press the Insert key while the list control is focused. The[Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed allowing you qualify this component.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Editing the qualified properties

 Use the \[Edit \] button, the “Edit” list context menu item or press the Space key while the list control is focused. The[Edit Qualified Component And Group Dialog](https://tools.techidaily.com/advancedinstaller/products/) will be displayed allowing you to edit the qualified properties for the current component.

### Removing the component from a category

Use the \[Remove \] button, the “Remove” list context menu item or press the Delete key while the list control is focused.

## Isolated Components

When creating an install package, you can specify if the installer should copy some files used by a certain application, in the application's folder rather than in a shared location.

Using Isolated Components have the following advantages:

* The application will always use the original files(the files it was installed with).
* Installing other applications that use the same files, but with a higher version, will ensure that the original files are not overwritten.

### Isolating a component

Use the \[Add... \] button, the “Add...” list context menu item or press the Insert key while the list control is focused. The Component Picker will be displayed allowing you to select a component. The selected component will be isolated with the current one.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148636/16836" target="_top" id="2148636">
  <img src="//a.impactradius-go.com/display-ad/16836-2148636" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148636/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing an isolated component

Use the \[Remove \] button, the “Remove” list context menu item or press the Delete key while the list control is focused.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-high-end-asus-monitor-4k-precision-hdr-mastery/"><u>[New] High-End ASUS Monitor 4K Precision, HDR Mastery</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-learn-to-capture-on-ipad-like-a-pro-effortlessly/"><u>[New] Learn To Capture on iPad Like a Pro - Effortlessly</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/1-ultimate-angular-ui-toolkit-pro-advanced-bootstrap-compatible-frontend-framework-by-creative-tim/"><u>1. Ultimate Angular UI Toolkit Pro: Advanced Bootstrap-Compatible Frontend Framework by Creative Tim</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/advanced-black-dashboard-for-professionals-reactive-crm-platform-using-reactstrap-and-bootstrap-v4-created-by-creative-tim/"><u>Advanced Black Dashboard for Professionals: Reactive CRM Platform Using Reactstrap and Bootstrap v4 - Created by Creative Tim</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/advanced-pro-level-nextjs-material-dashboard-by-creative-tim-exclusive-admin-templates/"><u>Advanced Pro-Level NextJS Material Dashboard by Creative Tim: Exclusive Admin Templates</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/advanced-react-native-framework-bundle-from-creative-tim-exclusive-app-development-solution/"><u>Advanced React Native Framework Bundle From Creative Tim - Exclusive App Development Solution</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/advanced-vuejs-3-and-bootstrap-5-admin-dashboard-with-vue-soft-ui-dashboard-pro-exclusive-pre-built-templates/"><u>Advanced VueJS 3 & Bootstrap 5 Admin Dashboard with Vue Soft UI Dashboard Pro - Exclusive Pre-Built Templates</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/beginners-guide-to-building-a-flutter-application-for-the-web-using-material-ui-and-code-samples-from-creativetim/"><u>Beginner's Guide to Building a Flutter Application for the Web Using Material-UI and Code Samples From CreativeTim</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/complete-paper-dashboard-pro-the-ultimate-premium-admin-interface-for-laravel-applications-with-customizable-crud-features-by-creative-tim/"><u>Complete Paper Dashboard Pro: The Ultimate Premium Admin Interface for Laravel Applications with Customizable CRUD Features by Creative Tim</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/easy-instructions-on-how-to-erase-your-tiktok-profile/"><u>Easy Instructions on How to Erase Your TikTok Profile</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exceptional-value-premium-asmr-microphones-at-low-costs/"><u>In 2024, Exceptional Value Premium ASMR Microphones at Low Costs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-upscaling-your-youtube-visuals/"><u>In 2024, Upscaling Your YouTube Visuals</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/-and-watch-your-guide-to-the-top-15-funny-youtubers/"><u>Smile and Watch Your Guide to the Top 15 Funny YouTubers</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-fixes-for-continuous-load-screen-problem-in-the-elder-scrolls-v-skyrim/"><u>Ultimate Fixes for Continuous Load Screen Problem in The Elder Scrolls V: Skyrim</u></a></li>
</ul></div>

