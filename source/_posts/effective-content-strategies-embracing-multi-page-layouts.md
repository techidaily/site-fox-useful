---
title: "Effective Content Strategies: Embracing Multi-Page Layouts"
date: 2024-10-03T21:10:00.448Z
updated: 2024-10-10T22:44:43.305Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes Effective Content Strategies: Embracing Multi-Page Layouts"
thumbnail: https://thmb.techidaily.com/91f7f58741561326931ca324590beadc475f32b45bcc3a270b10ca0d40e00353.jpg
---

## Effective Content Strategies: Embracing Multi-Page Layouts

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Product Details](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Digital Signature](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Updater](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Upgrades](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Licensing Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [CD/DVD Autorun](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Multiple Instances Page](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Instance Properties Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Instance Components Tab](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Multiple Instances Page

This page allows you to install multiple instances of your product on the target computer. The existence of multiple instances is verified by the [EXE setup file](https://tools.techidaily.com/advancedinstaller/products/). This is why the corresponding option must be checked in the [Configuration Tab](https://tools.techidaily.com/advancedinstaller/products/) page.

![Multiple instances](https://cdn.advancedinstaller.com/img/ui/multiple-instances.png "Multiple instances")  

Windows Installer permits only one instance of the ProductCode to be installed per machine and one instance to be installed per user. Starting with Windows Installer 3.x or later multiple instances can be installed by applying ProductCode transforms (called instance transforms) to the base MSI package.

Advanced Installer creates a transform for each defined instance with the same name as in the “Instance IDs” pane and streams it into the MSI database. When the package runs the Multiple Instances selection dialog displayed by the EXE allows the user to install new instance or maintain an already installed one.

The instances are uniquely distinguished by a new**ProductCode** and additionally by the **InstanceId** property. Other properties can be created in the [Instance Properties](https://tools.techidaily.com/advancedinstaller/products/) page. When the first instance is created the InstanceId property, it is added to the project with "#0" as value for the selected build. You can change it in the [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/) page.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The "#0" value is reserved for the base package.

 Advanced Installer uses the name of an instance from “Instance IDs” pane as the InstanceId property value for the corresponding instance. The InstanceId property **will not** be resolved outside the Multiple Instances page.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148648/16836" target="_top" id="2148648">
  <img src="//a.impactradius-go.com/display-ad/16836-2148648" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148648/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Creating a new instance

 Use the “New Instance” command from the context menu or press the Insert key while the “Instance IDs” panel is selected, in order to create a new instance.

### Renaming an instance

 Use the “Rename” command from the context menu or press the F2 key while an element is selected, to rename an instance.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing an instance

 Use the “Delete” command from the context menu, or press the Delete key while an element is selected, to remove an instance.

### Specifying the instances' installation order

Use the “Move Up” / “Move Down” context menu item or press the Shift+Up /Shift+Down keys while an instance is selected.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529">
  <img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Generate instances at install time

This option enables generating custom name instances at install time for the selected build. It implies loosing all previously created instances.

## Build major upgrades for multiple instances

The package is built with major upgrades support. This option has effect only after changing the [Product Version](https://tools.techidaily.com/advancedinstaller/products/). 

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)You cannot author major upgrades and generate instances at install time. The two options above are not compatible.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Instance Properties Tab](https://tools.techidaily.com/advancedinstaller/products/)  
In this tab you can set/overwrite properties for an instance.
* [Instance Components Tab](https://tools.techidaily.com/advancedinstaller/products/)  
In this page you can overwrite components for an instance.

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
<li><a href="https://fox-hovers.techidaily.com/updated-removing-borders-quick-and-effective-image-retouch-methods-for-2024/"><u>[Updated] Removing Borders Quick & Effective Image Retouch Methods for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/abbyy-achieves-soc-2-compliance-bolsters-trust-in-transactional-processes/"><u>ABBYY Achieves SOC #2 Compliance, Bolsters Trust in Transactional Processes</u></a></li>
<li><a href="https://fox-useful.techidaily.com/best-7-virtual-meeting-platforms-enhancing-remote-work-productivity/"><u>Best 7 Virtual Meeting Platforms Enhancing Remote Work Productivity</u></a></li>
<li><a href="https://fox-useful.techidaily.com/easy-techniques-for-retrieving-deleted-whatsapp-conversations-on-your-ios-device/"><u>Easy Techniques for Retrieving Deleted WhatsApp Conversations on Your iOS Device</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/from-novice-to-expert-conquering-business-vernacular/"><u>From Novice to Expert: Conquering Business Vernacular</u></a></li>
<li><a href="https://extra-support.techidaily.com/how-to-make-picture-in-picture-videos-on-mac-os-sierra-for-2024/"><u>How to Make Picture in Picture Videos on Mac OS Sierra for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-honor-magic-5-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Honor Magic 5 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-vivo-y27-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://fox-useful.techidaily.com/mastering-complex-software-deployment-a-guide-to-advanced-installation-techniques/"><u>Mastering Complex Software Deployment: A Guide to Advanced Installation Techniques</u></a></li>
<li><a href="https://fox-useful.techidaily.com/modify-application-settings-in-policy-management-dashboard/"><u>Modify Application Settings in Policy Management Dashboard</u></a></li>
<li><a href="https://facebook.techidaily.com/navigating-the-new-era-musicians-income-on-facebook-platform/"><u>Navigating the New Era: Musicians' Income on Facebook Platform</u></a></li>
<li><a href="https://fox-useful.techidaily.com/optimize-update-detection-processes-using-installed-base-detector-tool/"><u>Optimize Update Detection Processes Using Installed Base Detector Tool</u></a></li>
<li><a href="https://win-dash.techidaily.com/overcoming-common-driver-challenges-with-intel-hd-graphics-630-on-windows-systems/"><u>Overcoming Common Driver Challenges with Intel HD Graphics 630 on Windows Systems</u></a></li>
<li><a href="https://fox-useful.techidaily.com/tutorial-how-to-save-your-screen-from-anywhere-using-remote-desktop-on-pcs-and-macbooks/"><u>Tutorial: How to Save Your Screen From Anywhere Using Remote Desktop on PCs and MacBooks</u></a></li>
<li><a href="https://fox-useful.techidaily.com/ultimate-guide-how-to-change-your-mkv-movie-downloads-into-high-quality-mp3-music-playlists/"><u>Ultimate Guide: How to Change Your MKV Movie Downloads Into High-Quality MP3 Music Playlists</u></a></li>
<li><a href="https://fox-useful.techidaily.com/understanding-the-new-whatsapp-terms-a-deep-dive-into-recent-privacy-policy-updates-with-malwarefox/"><u>Understanding the New WhatsApp Terms: A Deep Dive Into Recent Privacy Policy Updates with MalwareFox</u></a></li>
<li><a href="https://fox-useful.techidaily.com/understanding-xml-documents-a-comprehensive-guide/"><u>Understanding XML Documents - A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-to-the-latest-version-of-wacom-istudio-draw-drivers-for-ultimate-control/"><u>Update to the Latest Version of Wacom iStudio Draw Drivers for Ultimate Control</u></a></li>
<li><a href="https://tech-hub.techidaily.com/voice-activated-chatgpt-now-available-in-mercedes-benz-cars/"><u>Voice-Activated ChatGPT Now Available in Mercedes-Benz Cars</u></a></li>
</ul></div>

