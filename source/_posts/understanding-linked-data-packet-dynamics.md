---
title: Understanding Linked Data Packet Dynamics
date: 2024-09-28T17:07:03.788Z
updated: 2024-09-29T22:59:49.256Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Understanding Linked Data Packet Dynamics
thumbnail: https://thmb.techidaily.com/3b4fc9801ceec8439e874198c6f456d3f60986d5a7e58819eb6db488dc36873e.jpg
---

## Understanding Linked Data Packet Dynamics

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
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Predefined Prerequisites](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Installation Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Files Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Prerequisite Conditions Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Chained Package Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Edit PseudoFormatted Type Dialog](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Windows Features](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Windows Server Roles](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Specify Builds Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Launch Conditions](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Merge Modules](https://tools.techidaily.com/advancedinstaller/products/)  
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

## Chained Package Behavior

A chained package can either be skipped or run as part of the main setup in the following modes:

* install
* uninstall
* maintenance

The chained package conditions are evaluated for install first, then for uninstall. Both conditions are evaluated in this order when the parent setup runs in install, uninstall and maintenance modes.

When these condition fields are left empty, then the chained package will run in the same mode as its parent setup. 

A chained package's run mode depends on three factors:

* parent setup run mode
* install condition
* uninstall condition

The following tables combine these three factors to clarify how the CP (chained package) will behave:

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)To read the table start from the top left cell then choose a column and a row based on how the conditions you have set in the [Chained Packages](https://tools.techidaily.com/advancedinstaller/products/) get resolved.

| **When the parent package is installed and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| -------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**  | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be installed                |
| **CP uninstall condition resolves to FALSE** | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be installed                |
| **CP uninstall condition field is EMPTY**    | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be installed                |

| **When the parent package is uninstalled and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| ---------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**    | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |
| **CP uninstall condition resolves to FALSE**   | \=> CP will be installed                  | \=> CP will be skipped                     | \=> CP will be skipped                  |
| **CP uninstall condition field is EMPTY**      | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |

| **When the parent package runs in maintenance mode and** | **CP install condition resolves to TRUE** | **CP install condition resolves to FALSE** | **CP install condition field is EMPTY** |
| -------------------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------------------------- |
| **CP uninstall condition resolves to TRUE**              | \=> CP will be installed                  | \=> CP will be uninstalled                 | \=> CP will be uninstalled              |
| **CP uninstall condition resolves to FALSE**             | \=> CP will be installed                  | \=> CP will run in maintenance mode        | \=> CP will run in maintenance mode     |
| **CP uninstall condition field is EMPTY**                | \=> CP will be installed                  | \=> CP will run in maintenance mode        | \=> CP will run in maintenance mode     |

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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-from-basic-players-to-gamers-paradise-the-kinemaster-android-experience/"><u>[New] 2024 Approved From Basic Players to Gamers' Paradise The KineMaster Android Experience</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-instructions-windows-movie-maker-version-6-installation/"><u>[New] In 2024, Instructions Windows Movie Maker Version 6 Installation</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-dji-quadcopters-tiers-basic-model-enhanced-version-high-definition-masterclass/"><u>[Updated] DJI Quadcopters Tiers Basic Model, Enhanced Version, High Definition Masterclass</u></a></li>
<li><a href="https://fox-useful.techidaily.com/collaborate-and-explore-ebooks-side-by-side-with-friends-at-flipbuildercom/"><u>Collaborate and Explore eBooks Side by Side with Friends at FlipBuilder.com</u></a></li>
<li><a href="https://fox-useful.techidaily.com/combining-duo-sheet-images-into-single-pages-with-flipbuilder-a-step-by-step-guide/"><u>Combining Duo Sheet Images Into Single Pages with FlipBuilder – A Step by Step Guide</u></a></li>
<li><a href="https://fox-useful.techidaily.com/compatibility-guide-moving-your-original-themes-between-applications-including-flipbuilder/"><u>Compatibility Guide: Moving Your Original Themes Between Applications, Including FlipBuilder</u></a></li>
<li><a href="https://fox-useful.techidaily.com/comprehensive-guide-mastering-the-art-with-flipwriter-by-flipbuildercom/"><u>Comprehensive Guide: Mastering the Art with FlipWriter by FlipBuilder.com</u></a></li>
<li><a href="https://fox-useful.techidaily.com/comprehensive-list-of-documents-and-media-you-can-transform-using-flipoffice-software/"><u>Comprehensive List of Documents & Media You Can Transform Using FlipOffice Software</u></a></li>
<li><a href="https://fox-useful.techidaily.com/create-and-distribute-interactive-ebooks-for-free-share-them-now-at-flipbuildercom/"><u>Create and Distribute Interactive eBooks for Free – Share Them Now at FlipBuilder.com!</u></a></li>
<li><a href="https://fox-useful.techidaily.com/digital-content-expert-tips-security-strategies-and-effective/"><u>Digital Content, Expert Tips, Security Strategies, and Effective.</u></a></li>
<li><a href="https://fox-useful.techidaily.com/effortless-conversion-transform-your-ms-word-documents-into-interactive-flipbooks-with-flipbuilder/"><u>Effortless Conversion: Transform Your MS Word Documents Into Interactive Flipbooks with FlipBuilder!</u></a></li>
<li><a href="https://fox-useful.techidaily.com/effortless-digital-reading-with-page-flip-ebooks-access-your-library-anywhere-on-pcmobile-discover-at-flipbuildercom/"><u>Effortless Digital Reading with Page Flip eBooks - Access Your Library Anywhere, On PC/Mobile! [Discover at FlipBuilder.com]</u></a></li>
<li><a href="https://win-able.techidaily.com/grand-theft-auto-v-resolved-fixes-for-gameplay-lag-issues/"><u>Grand Theft Auto V Resolved: Fixes for Gameplay Lag Issues</u></a></li>
<li><a href="https://apple-account.techidaily.com/icloud-separation-how-to-disconnect-iphone-x-and-ipad-by-drfone-ios/"><u>iCloud Separation How To Disconnect iPhone X and iPad</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/rise-in-search-results-mastering-podcast-seo/"><u>Rise in Search Results Mastering Podcast SEO</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-instructions-how-to-transfer-steam-gift-codes-securely/"><u>Step-by-Step Instructions: How to Transfer Steam Gift Codes Securely</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-apple-iphone-6-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of Apple iPhone 6</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-realme-11-5g-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Realme 11 5G | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

