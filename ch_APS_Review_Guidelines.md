
# 应用商店审查指南

## 序言  

我们很高兴你能付出才华和时间来为iOS开发应用程序。对于为数众多的开发者来说，不论在职业上还是在经济上，这样的经历都是有丰厚回报的，我们希望帮你加入这个成功的组织。已经发布的**应用商店审查指南**，能帮你避开在开发应用程序过程中遇到的一些问题，使你的应用程序提交后能更快的通过审核。

We're pleased that you want to invest your talents and time to develop applications for iOS. It has been a rewarding experience - both professionally and financially - for hundreds of thousands of developers and we want to help you join this successful group. We have published our App Store Review Guidelines in the hope that they will help you steer clear of issues as you develop your App and speed you through the approval process when you submit it.

我们把应用程序看作与书籍和音乐不同的东西，因为书籍和音乐不需要我们管理。如果你想作关于宗教的评论，可以写一本书。如果你想描写与性有关的事，可以写书、作曲或者开发一款医学类应用程序。不过我们已经决定不允许某些内容出现在应用商店中，虽然这么做有点复杂，但这有助于我们更加全面的考虑问题：

We view Apps different than books or songs, which we do not curate. If you want to criticize a religion, write a book. If you want to describe sex, write a book or a song, or create a medical App. It can get complicated, but we have decided to not allow certain kinds of content in the App Store. It may help to keep some of our broader themes in mind:

* 我们有很多提供给儿童下载的应用程序。虽然家长监护可以很好的保护儿童，但是开发人员也要承担应尽的责任。我们要关心孩子们。

* We have lots of kids downloading lots of Apps. Parental controls work great to protect kids, but you have to do your part too. So know that we're keeping an eye out for the kids.

* 
* We have over a million Apps in the App Store. If your App doesn't do something useful, unique or provide some form of lasting entertainment, or if your app is plain creepy, it may not be accepted.

* If your App looks like it was cobbled together in a few days, or you're trying to get your first practice App into the store to impress your friends, please brace yourself for rejection. We have lots of serious developers who don't want their quality Apps to be surrounded by amateur hour.

* We will reject Apps for any content or behavior that we believe is over the line. What line, you ask? Well, as a Supreme Court Justice once said, "I'll know it when I see it". And we think that you will also know it when you cross it.

* If your App is rejected, we have a Review Board that you can appeal to. If you run to the press and trash us, it never helps.

* If you attempt to cheat the system (for example, by trying to trick the review process, steal data from users, copy another developer's work, or manipulate the ratings) your Apps will be removed from the store and you will be expelled from the developer program.

* This is a living document, and new Apps presenting new questions may result in new rules at any time. Perhaps your App will trigger this.

Lastly, we love this stuff too, and honor what you do. We're really trying our best to create the best platform in the world for you to express your talents and make a living too. If it sounds like we're control freaks, well, maybe it's because we're so committed to our users and making sure they have a quality experience with our products. Just like almost all of you are, too.

## Table of Contents

1. [Terms and conditions](#Terms and conditions)
2. [Functionality](#Functionality)
3. [Metadata](#Metadata)
4. [Location](#Location)
5. [Push Notifications](#Push Notifications)
6. [Game Center](#Game Center)
7. [Advertising](#Advertising)
8. [Content and Intellectual Property Rights](#Content and Intellectual Property Rights)
9. [Media content](#Media content)
10. [User interface](#User interface)
11. [Purchasing and currencies](#Purchasing and currencies)
12. [Scraping and aggregation](#Scraping and aggregation)
13. [Damage or injury](#Damage or injury)
14. [Personal attacks](#Personal attacks)
15. [Violence](#Violence)
16. [Objectionable content](#Objectionable content)
17. [Privacy](#Privacy)
18. [Pornography](#Pornography)
19. [Religion, culture, and ethnicity](#Religion, culture, and ethnicity)
20. [Contests, sweepstakes, lotteries, raffles, and gambling](#Contests, sweepstakes, lotteries, raffles, and gambling)
21. [Charities and contributions](#Charities and contributions)
22. [Legal requirements](#Legal requirements)
23. [Wallet](#Wallet)
24. [Kids Category](#Kids Category)
25. [Extensions](#Extensions)
26. [HomeKit](#HomeKit)
27. [HealthKit, CareKit, and Human Subject Research](#HealthKit, CareKit, and Human Subject Research)
28. [TestFlight](#TestFlight)
29. [Apple Pay](#Apple Pay)
30. [Apple Music API](#Apple Music API)

<span id="Terms and conditions"/>
### 1. Terms and conditions

* As a developer of Apps for the App Store you are bound by the terms of the **Program License Agreement** (PLA), **Human Interface Guidelines** (HIG), and any other licenses or contracts between you and Apple. The following rules and examples are intended to assist you in gaining acceptance for your App in the App Store, not to amend or remove provisions from any other agreement.

<span id="Functionality"/>
### 2. Functionality

* Apps that crash will be rejected

* Apps that exhibit bugs will be rejected

* Apps that do not perform as advertised by the developer will be rejected

* Apps that include undocumented or hidden features inconsistent with the description of the App will be rejected

* Apps that use non-public APIs will be rejected

* Apps that read or write data outside its designated container area will be rejected

* Apps that download code in any way or form will be rejected

* Apps that install or launch other executable code will be rejected

* Apps that are "demo", "trial", or "test" versions will be rejected. Beta Apps may only be submitted through TestFlight and must follow the TestFlight guidelines

* iPhone Apps must also run on iPad without modification, at iPhone resolution, and at 2X iPhone 3GS resolution

* Apps that duplicate Apps already in the App Store may be rejected, particularly if there are many of them, such as fart, burp, flashlight, and Kama Sutra Apps

* Apps that are not very useful, unique, are simply web sites bundled as Apps, or do not provide any lasting entertainment value may be rejected

* Apps that are primarily marketing materials or advertisements will be rejected

* Apps that are intended to provide trick or fake functionality that are not clearly marked as such will be rejected

* Apps larger than 100MB in size will not download over cellular networks (this is automatically prohibited by the App Store)

* Multitasking Apps may only use background services for their intended purposes: VoIP, audio playback, location, task completion, local notifications, etc.

* Apps that browse the web must use the iOS WebKit framework and WebKit Javascript

* Apps that encourage excessive consumption of alcohol or illegal substances, or encourage minors to consume alcohol or smoke cigarettes, will be rejected

* Apps that provide incorrect diagnostic or other inaccurate device data will be rejected

* Developers "spamming" the App Store with many versions of similar Apps will be removed from the iOS Developer Program

* Apps that are simply a song or movie should be submitted to the iTunes store. Apps that are simply a book should be submitted to the iBooks Store

* Apps that arbitrarily restrict which users may use the App, such as by location or carrier, may be rejected

* Apps must follow the **iOS Data Storage Guidelines** or they will be rejected

* Apps that are offered in Newsstand must comply with schedules 1, 2 and 3 of the **Program License Agreement** or they will be rejected

* Apps that display Apps other than your own for purchase or promotion in a manner similar to or confusing with the App Store will be rejected

* Apps may display and recommend apps other than your own only if the collection is designed for a specific approved need (e.g. health management, aviation, accessibility, etc.) or provides significant added value for a specific group of customers, or they will be rejected

* If your app’s core functionality doesn’t work with the Siri remote it will be rejected. The app may, however, provide enhanced functionality in connection with a game controller or other peripheral

<span id="Metadata"/>
### 3. Metadata (name, descriptions, ratings, rankings, etc.)

* Apps or metadata that mentions the name of any other mobile platform will be rejected

* Apps with placeholder text will be rejected

* Apps with names, descriptions, screenshots, or previews not relevant to the content and functionality of the App will be rejected

* App names in iTunes Connect and as displayed on a device should be similar, so as not to cause confusion

* Small and large App icons should be similar, so as not to cause confusion

* Apps with App icons, screenshots, previews, and images displayed when an Apple TV app is in the top shelf of the Apple TV home screen that do not adhere to the 4+ age rating will be rejected

* Apps with Category and Genre selections that are not appropriate for the App content will be rejected

* Developers are responsible for assigning appropriate ratings to their Apps. Inappropriate ratings may be changed/deleted by Apple

* Developers are responsible for assigning appropriate keywords for their Apps. Inappropriate keywords may be changed/deleted by Apple

* Developers who attempt to manipulate or cheat the user reviews or chart ranking in the App Store with fake or paid reviews, or any other inappropriate methods will be removed from the iOS Developer Program
Apps that recommend that users restart their iOS device prior to installation or launch may be rejected

* Apps should have all included URLs fully functional when you submit it for review, such as support and privacy policy URLs

* Apps with screenshots, previews, and marketing text that do not clearly identify supplemental content or items that must be purchased separately (e.g. using IAP) will be rejected

* App previews may only use video screen captures of the app, narration, and textual and design overlays, or the app will be rejected
Apps with previews that display personal information of a real person without permission will be rejected

* App previews may only include music that is licensed for that purpose in all selected territories

* App previews and screenshots that include content played or streamed via the app (e.g. music, video, and related cover art) that is not licensed for use in the preview or screenshots will be rejected

<span id="Location"/>
### 4. Location

* Apps that do not notify and obtain user consent before collecting, transmitting, or using location data will be rejected

* Apps that use location-based APIs for automatic or autonomous control of vehicles, aircraft, or other devices will be rejected

* Apps that use location-based APIs for emergency services will be rejected

* Location data can only be used when directly relevant to the features and services provided by the App to the user or to support approved advertising uses

* Apps using background location services must provide a reason that clarifies the purpose of the use, using mechanisms described in the Human Interface Guidelines

<span id="Push Notifications"/>
### 5. Push Notifications

* Apps that provide Push Notifications without using the Apple Push Notification (APN) API will be rejected

* Apps that use the APN service without obtaining a Push Application ID from Apple will be rejected

* Apps that send Push Notifications without first obtaining user consent, as well as apps that require Push Notifications to function, will be rejected

* Apps that send sensitive personal or confidential information using Push Notifications will be rejected

* Apps that use Push Notifications to send unsolicited messages, or for the purpose of phishing or spamming will be rejected

* Apps cannot use Push Notifications to send advertising, promotions, or direct marketing of any kind

* Apps cannot charge users for use of Push Notifications

* Apps that excessively use the network capacity or bandwidth of the APN service or unduly burden a device with Push Notifications will be rejected

* Apps that transmit viruses, files, computer code, or programs that may harm or disrupt the normal operation of the APN service will be rejected

<span id="Game Center"/>
### 6. Game Center

* Apps that display any Player ID to end users or any third party will be rejected

* Apps that use Player IDs for any use other than as approved by the Game Center terms will be rejected

* Developers that attempt to reverse lookup, trace, relate, associate, mine, harvest, or otherwise exploit Player IDs, aliases, or other information obtained through Game Center will be removed from the iOS Developer Program

* Game Center information, such as Leaderboard scores, may only be used in Apps approved for use with Game Center

* Apps that use the Game Center service to send unsolicited messages, or for the purpose of phishing or spamming will be rejected

* Apps that excessively use the network capacity or bandwidth of Game Center will be rejected

Apps that transmit viruses, files, computer code, or programs that may harm or disrupt the normal operation of the Game Center service will be rejected

<span id="Advertising"/>
### 7. Advertising

* Apps that artificially increase the number of impressions or click-throughs of ads will be rejected

* Apps that contain empty iAd banners will be rejected

* Apps that are designed predominantly for the display of ads will be rejected

<span id="Content and Intellectual Property Rights"/>
### 8. Content and Intellectual Property Rights

* Apps must comply with all terms and conditions explained in the **Guidelines for Using Apple Trademarks and Copyrights** and the **Apple Trademark List**

* Apps that suggest or infer that Apple is a source or supplier of the App, or that Apple endorses any particular representation regarding quality or functionality will be rejected

* Apps that appear confusingly similar to an existing Apple product, interface, or advertising theme will be rejected

* Apps that misspell Apple product names in their App name (i.e., GPS for Iphone, iTunz) will be rejected

* Apps may not use protected third party material such as trademarks, copyrights, patents or violate 3rd party terms of use. Authorization to use such material must be provided upon request

* Apps that include the ability to save or download music or video content from third party sources (e.g. Apple Music, YouTube, SoundCloud, Vimeo, etc) without explicit authorization from those sources will be rejected

<span id="Media content"/>
### 9. Media content

* Apps that do not use the MediaPlayer framework to access media in the Music Library will be rejected

*App user interfaces that mimic any iPod or iTunes interface will be rejected

* Audio streaming content over a cellular network may not use more than 5MB over 5 minutes

* Video streaming content over a cellular network longer than 10 minutes must use HTTP Live Streaming and include a baseline 192 kbps or lower HTTP Live stream

<span id="User interface"/>
### 10. User interface

* Apps must comply with all terms and conditions explained in the applicable Apple Human Interface Guidelines:

	- iOS Human Interface Guidelines

	- OS X Human Interface Guidelines

	- Apple TV Human Interface Guidelines

	- Apple Watch Human Interface Guidelines

* Apps that look similar to Apps bundled on iOS or Watch OS devices, including the App Store, iTunes Store, and iBooks Store, will be rejected

* Apps that do not use system provided items, such as buttons and icons, correctly and as described in the **Apple iOS Human Interface Guidelines** may be rejected

* Apps that create alternate desktop/home screen environments or simulate multi-App widget experiences will be rejected

* Apps that alter the functions of standard switches, such as the Volume Up/Down and Ring/Silent switches, will be rejected

* Apple and our customers place a high value on simple, refined, creative, well thought through interfaces. They take more work but are worth it. Apple sets a high bar. If your user interface is complex or less than very good, it may be rejected

* Watch Apps whose primary function is telling time will be rejected

* Apps displaying Activity rings may not modify the rings or the data they represent

<span id="Purchasing and currencies"/>
### 11. Purchasing and currencies

* Apps that unlock or enable additional features or functionality with mechanisms other than the App Store will be rejected

* Apps utilizing a system other than the In-App Purchase API (IAP) to purchase content, functionality, or services in an App will be rejected

* Apps using IAP to purchase physical goods or goods and services used outside of the App will be rejected

* Apps that use IAP to purchase credits or other currencies must consume those credits within the App

* Apps that use IAP to purchase credits or other currencies that expire will be rejected

* Content subscriptions using IAP must last a minimum of 7 days and be available to the user from all of their iOS devices

* Apps that use IAP to purchase items must assign the correct Purchasability type
Apps that use IAP to purchase access to built-in capabilities provided by iOS, watchOS, and tvOS, such as the camera or the gyroscope, or Apple-branded peripherals, such as Apple Pencil or Apple Keyboard, or Apple services, such as Apple Music access or iCloud storage, will be rejected

* Apps containing content or services that expire after a limited time will be rejected, except for specific approved content (e.g. films, television programs, music, books)

* Insurance Apps must be free, in legal-compliance in the regions distributed, and cannot use IAP

* In general, the more expensive your App, the more thoroughly we will review it

* Apps offering subscriptions must do so using IAP, Apple will share the same 70/30 revenue split with developers for these purchases, as set forth in the **Program License Agreement**

* Apps that link to external mechanisms for purchases or subscriptions to be used in the App, such as a "buy" button that goes to a web site to purchase a digital book, will be rejected

* Apps can read or play approved content (specifically magazines, newspapers, books, audio, music, video and cloud storage) that is subscribed to or purchased outside of the App, as long as there is no button or external link in the App to purchase the approved content. Apple will only receive a portion of revenues for content purchased inside the App

* Apps may only use auto-renewing subscriptions for periodicals (newspapers, magazines), business Apps (enterprise, productivity, professional creative, cloud storage), and media Apps (video, audio, voice), or the App will be rejected

* Apps may enable additional approved features or functionality when used in combination with specific approved physical products (such as a toy) as long as the additional features and functionality are either completely dependent on such hardware (for example an App that is used to control a telescope) or also available through the App without the physical products, such as by way of reward for achievement or by use of IAP

* Apps may facilitate transmission of approved virtual currencies provided that they do so in compliance with all state and federal laws for the territories in which the app functions

<span id="Scraping and aggregation"/>
### 12. Scraping and aggregation

* Apps that scrape any information from Apple sites (for example from apple.com, iTunes Store, App Store, iTunes Connect, Apple Developer Programs, etc.) or create rankings using content from Apple sites and services will be rejected

* Apps may use approved Apple RSS feeds such as the iTunes Store RSS feed

* Apps that are simply web clippings, content aggregators, or a collection of links, may be rejected

<span id="Damage or injury"/>
### 13. Damage or injury

* Apps that encourage users to use an Apple Device in a way that may cause damage to the device will be rejected

* Apps that rapidly drain the device's battery or generate excessive heat will be rejected

* Apps whose use may result in physical harm may be rejected

<span id="Personal attacks"/>
### 14. Personal attacks

* Any App that is defamatory, offensive, mean-spirited, or likely to place the targeted individual or group in harm's way will be rejected

* Professional political satirists and humorists are exempt from the ban on offensive or mean-spirited commentary

* Apps that display user generated content must include a method for filtering objectionable material, a mechanism for users to flag offensive content, and the ability to block abusive users from the service

<span id="Violence"/>
### 15. Violence

* Apps portraying realistic images of people or animals being killed or maimed, shot, stabbed, tortured or injured will be rejected

* Apps that depict violence or abuse of children will be rejected

* "Enemies" within the context of a game cannot solely target a specific race, culture, a real government or corporation, or any other real entity

* Apps involving realistic depictions of weapons in such a way as to encourage illegal or reckless use of such weapons will be rejected

* Apps that include games of Russian roulette will be rejected

<span id="Objectionable content"/>
### 16. Objectionable content

* Apps that present excessively objectionable or crude content will be rejected

* Apps that are primarily designed to upset or disgust users will be rejected

<span id="Privacy"/>
### 17. Privacy

* Apps cannot transmit data about a user without obtaining the user's prior permission and providing the user with access to information about how and where the data will be used

* Apps that require users to share personal information, such as email address and date of birth, in order to function will be rejected

* Apps may ask for date of birth (or use other age-gating mechanisms) only for the purpose of complying with applicable children's privacy statutes, but must include some useful functionality or entertainment value regardless of the user's age

* Apps that collect, transmit, or have the capability to share personal information (e.g. name, address, email, location, photos, videos, drawings, the ability to chat, other personal data, or persistent identifiers used in combination with any of the above) from a minor must comply with applicable children's privacy statutes, and must include a privacy policy

* Apps that include account registration or access a user’s existing account must include a privacy policy or they will be rejected

<span id="Pornography"/>
### 18. Pornography

* Apps containing pornographic material, defined by Webster's Dictionary as "explicit descriptions or displays of sexual organs or activities intended to stimulate erotic rather than aesthetic or emotional feelings", will be rejected

* Apps that contain user generated content that is frequently pornographic (e.g. "Chat Roulette" Apps) will be rejected

<span id="Religion, culture, and ethnicity"/>
### 19. Religion, culture, and ethnicity

* Apps containing references or commentary about a religious, cultural or ethnic group that are defamatory, offensive, mean-spirited or likely to expose the targeted group to harm or violence will be rejected

* Apps may contain or quote religious text provided the quotes or translations are accurate and not misleading. Commentary should be educational or informative rather than inflammatory

<span id="Contests, sweepstakes, lotteries, raffles, and gambling"/>
### 20. Contests, sweepstakes, lotteries, raffles, and gambling

* Sweepstakes and contests must be sponsored by the developer/company of the App

* Official rules for sweepstakes and contests must be presented in the App and make it clear that Apple is not a sponsor or involved in the activity in any manner

* It must be permissible by law for the developer to run a lottery App, and a lottery App must have all of the following characteristics: consideration, chance, and a prize

* Apps that allow a user to directly purchase a raffle ticket in the App will be rejected

* Apps that offer real money gaming (e.g. sports betting, poker, casino games, horse racing) or lotteries must have necessary licensing and permissions in the locations where the App is used, must be restricted to those locations, and must be free on the App Store

* Apps that use IAP to purchase credit or currency to use in conjunction with real money gaming will be rejected

<span id="Charities and contributions"/>
### 21. Charities and contributions

* Apps that include the ability to make donations to recognized charitable organizations must be free

* The collection of charitable donations must be done via a web site in Safari or an SMS

<span id="Legal requirements"/>
### 22. Legal requirements

* Apps must comply with all legal requirements in any location where they are made available to users. It is the developer's obligation to understand and conform to all local laws

* Apps that contain false, fraudulent or misleading representations or use names or icons similar to other Apps will be rejected

* Apps that solicit, promote, or encourage criminal or clearly reckless behavior will be rejected

* Apps that enable illegal file sharing will be rejected

* Apps that are designed for use as illegal gambling aids, including card counters, will be rejected

* Apps that enable anonymous or prank phone calls or SMS/MMS messaging will be rejected

* Developers who create Apps that surreptitiously attempt to discover user passwords or other private user data will be removed from the iOS Developer Program

* Apps that contain DUI checkpoints that are not published by law enforcement agencies, or encourage and enable drunk driving, will be rejected

* Apps that calculate medicinal dosages must be submitted by the manufacturer of those medications or recognized institutions such as hospitals, insurance companies, and universities

* Apps that use iTunes music previews in an unauthorized manner will be rejected

<span id="Wallet"/>
### 23. Wallet

* Wallet passes can be used to make or receive payments, transmit offers, or offer identification (such as movie tickets, airline tickets, coupons and reward offers). Other uses may result in the rejection of the App and the revocation of Wallet credentials

* Passes must include valid contact information from the issuer of the pass or the App will be rejected and Wallet credentials may be revoked

* Passes must be signed by the entity that will be distributing the pass under its own name, trademark, or brand or the App will be rejected and Wallet credentials may be revoked

<span id="Kids Category"/>
### 24. Kids Category

* Apps in the Kids Category must include a privacy policy and must comply with applicable children's privacy statutes

* Apps in the Kids Category may not include behavioral advertising (e.g. the advertiser may not serve ads based on the user's activity within the App), and any contextual ads presented in the App must be appropriate for kids

* Apps in the Kids Category must get parental permission or use a parental gate before allowing the user to link out of the app or engage in commerce

* Apps in the Kids Category must be made specifically for kids ages 5 and under, ages 6-8, or ages 9-11

<span id="Extensions"/>
### 25. Extensions

* Apps hosting extensions must comply with the **App Extension Programming Guide**

* Apps hosting extensions must provide some functionality (help screens, additional settings) or they will be rejected

* Apps hosting extensions that include marketing, advertising, or in-app purchases in their extension view will be rejected

* Keyboard extensions must provide a method for progressing to the next keyboard
Keyboard extensions must remain functional with no network access or they will be rejected

* Keyboard extensions must provide Number and Decimal keyboard types as described in the **App Extension Programming Guide** or they will be rejected

* Apps offering Keyboard extensions must provide keyboard functionality (e.g. typed characters), have a primary category of Utilities and a privacy policy or they will be rejected

* Apps offering Keyboard extensions may only collect user activity to enhance the functionality of their keyboard extension on the iOS device or they may be rejected

<span id="HomeKit"/>
### 26. HomeKit

* Apps using the HomeKit framework must have a primary purpose of providing home automation services

* Apps using the HomeKit framework must indicate this usage in their marketing text and they must provide a privacy policy or they will be rejected

* Apps must not use data gathered from the HomeKit APIs for advertising or other use-based data mining

* Apps using data gathered from the HomeKit API for purposes other than improving the user experience or hardware/software performance in providing home automation functionality will be rejected

<span id="HealthKit, CareKit, and Human Subject Research"/>
### 27. HealthKit, CareKit, and Human Subject Research

* Apps using the HealthKit or CareKit frameworks or conducting human subject research for health purposes, such as through the use of ResearchKit, must comply with applicable law for each Territory in which the App is made available, as well as Sections 3.3.28 and 3.3.39 of the **iOS Developer Program License Agreement**

* Apps that write false or inaccurate data into HealthKit or CareKit will be rejected

* Apps using the HealthKit framework that store users’ health information in iCloud will be rejected

* Apps may not use or disclose to third parties user data gathered from the HealthKit or CareKit APIs or from health-related human subject research for advertising or other use-based data mining purposes other than improving health, or for the purpose of health research

* Apps that share user data acquired via the HealthKit or CareKit APIs with third parties without user consent will be rejected

* Apps using the HealthKit or CareKit frameworks must indicate integration with the Health app in their marketing text and must clearly identify the HealthKit and CareKit functionality in the app’s user interface

* Apps using the HealthKit or CareKit frameworks or conducting human subject research must provide a privacy policy or they will be rejected

* Apps that provide diagnoses, treatment advice, or control hardware designed to diagnose or treat medical conditions that do not provide written regulatory approval upon request will be rejected

* Apps conducting health-related human subject research must obtain consent from participants or, in the case of minors, their parent or guardian. Such consent must include the 
	- (a) nature, purpose, and duration of the research; 
	- (b) procedures, risks, and benefits to the participant; 
	- (c) information about confidentiality and handling of data (including any sharing with third parties); 
	- (d) a point of contact for participant questions; and 
	- (e) the withdrawal process

* Apps conducting health-related human subject research must secure approval from an independent ethics review board. Proof of such approval must be provided upon request.

<span id="TestFlight"/>
### 28. TestFlight

* Apps may only use TestFlight to beta test apps intended for public distribution and must comply with the full App Review Guidelines

* Apps using TestFlight must be submitted for review whenever a build contains material changes to content or functionality

* Apps using TestFlight may not be distributed to testers in exchange for compensation of any kind

<span id="Apple Pay"/>
### 29. Apple Pay

* Apps using Apple Pay must provide all material purchase information to the user prior to sale of any good or service or they will be rejected; Apps using Apple Pay to offer recurring payments must, at a minimum, disclose the length of the renewal term and the fact that it will continue until canceled, what will be provided during each period, the charges that will be billed to the customer, and how to cancel.

* Apps using Apple Pay must use Apple Pay branding and user interface elements correctly and as described in the **Apple Pay Identity Guidelines** or they will be rejected

* Apps using Apple Pay as a purchasing mechanism may not offer goods or services that violate the law of any territory in which the good or service will be delivered and may not be used for any illegal purpose

* Apps using Apple Pay must provide a privacy policy or they will be rejected

* Apps using Apple Pay may only share user data acquired via Apple Pay with third parties when provided to facilitate or improve delivery of goods and services or to comply with legal requirements

<span id="Apple Music API"/>
### 30. Apple Music API 

* Apps using the Apple Music API that trigger playback without explicit user action will be rejected

* Apps using the Apple Music API must expose and respect standard media controls such as “play,” pause,” and “skip”

* Apps using the Apple Music API may not require payment or otherwise monetize access to the Apple Music service (e.g. in-app purchase, advertising, requesting user info)

>#### Living document

> This document represents our best efforts to share how we review Apps submitted to the App Store, and we hope it is a helpful guide as you develop and submit your Apps. It is a living document that will evolve as we are presented with new Apps and situations, and we'll update it periodically to reflect these changes.

>Thank you for developing for iOS. Even though this document is a formidable list of what not to do, please also keep in mind the much shorter list of what you must do. Above all else, join us in trying to surprise and delight users. Show them their world in innovative ways, and let them interact with it like never before. In our experience, users really respond to polish, both in functionality and user interface. Go the extra mile. Give them more than they expect. And take them places where they have never been before. We are ready to help.

> ###### © Apple, 2016