---
title: Paperback
media_order: 'Image_10.jpeg,Image_2.jpeg,Image_3.jpeg,Image_4.jpeg,Image_5.jpeg,Image_6.jpeg,Image.jpeg,Image_11.jpeg,Image_9.jpeg,Image_1.jpeg,Image_7.jpeg,Image_8.jpeg,IMG_6211.PNG,IMG_6210.PNG,IMG_6215.PNG'
---

### Guide Overview
* [Known Limitations](#known-limitations)
* [Issues](#issues)
* [Installation](#installation)
* [Setup](#setup)
* [Progress Syncing](#progress-syncing)

!!! Big thanks to aitopu34 a.k.a ACK72 for developing this extension

! Note: Currently there's only official support for Paperback v0.7.<br/>
! Paperback only works on iOS 13.4+ or iPadOS 13.4+

## Known Limitations
* Recommendation and ReadingList feature of Kavita currently are not supported.

## Issues
**Kavya Extension:** Please report any errors [here](https://github.com/ACK72/kavya-paperback/issues/new?assignees=ACK72&labels=&template=bug_report.md&title=%5BBUG%5D). 

**Kavya Tracker Extension:** Please report any errors [here](https://github.com/ACK72/kavya-paperback-tracker/issues/new?assignees=ACK72&title=%5BBUG%5D)

Those link to the plugin's GitHub. Please do not create issues on Kavita's GitHub for extension-related issues.

## Installation

! **Make sure Kavita is updated to the latest version**

1. After that, go the to [app store and install Paperback](https://apps.apple.com/us/app/paperback-a-komga-client/id1626613373).
![Image_11](Image_11.jpeg?resize=450,450 "Image_11")

2. Go to [https://ack72.github.io/kavya-paperback/](https://ack72.github.io/kavya-paperback/) and tap "**Add to Paperback**"
![Image_10](Image_10.jpeg?resize=450,450 "Image_10")

3. Tap "Open" when prompted to Open in "Paperback"?
![Image_9](Image_9.jpeg?resize=450,450 "Image_9")

4. Tap "Add as Source Repo"
![Image_8](Image_8.jpeg?resize=450,450 "Image_8")

5. Open Paperback and go to **Settings > External Sources > Browse ACK72's Extensions**
![Image_6](Image_6.jpeg?resize=450,450 "Image_6")

6. Install Kavya
![Image_5](Image_5.jpeg?resize=450,450 "Image_5")

## Setup

To make the extension link with your Kavita instance we need the API Key.
The steps to get the API Key are:

Access your Kavita instance from your web browser and log in
1. Access your Kavita **user** dashboard
2. Switch to "3rd Party Clients" tab
3. Copy the text under the API Key
![Image_1](Image_1.jpeg?resize=450,450 "Image_1")

**Once the API KEY is obtained open Paperback**
4. Go back to External Sources page and tap on Kayva
![Image_4](Image_4.jpeg?resize=450,450 "Image_4")

7. Under Source Settings tap on "Server Settings"
![Image_3](Image_3.jpeg?resize=450,450 "Image_3")

9. Under Server Settings enter in your your Server URL in the corresponding field.
10. Enter your API key in the corresponding field.
12. Tap Save
![Image_2](Image_2.jpeg?resize=450,450 "Image_2")


13. Tap on the Book icon in the bottom left, then "Kavya" in the top of the screen.
14. Swipe down to refresh.
15. Browse your library 
![Image](Image.jpeg?resize=450,450 "Image")

## Progress Syncing
! Progress Syncing is handled at chapter/issue level, not page level. That means after a chapter/issue is finished completion is synced to Kavita.

1. Open Paperback and go to Settings
2. Tap External Trackers
![IMG_6210](IMG_6210.PNG?resize=450,450 "IMG_6210")

3. Tap Edit and "+"
![IMG_6211](IMG_6211.PNG?resize=450,450 "IMG_6211")

4. You can put whatever you would like in the name field. Add this to the URL field: `https://ACK72.github.io/kavya-paperback-tracker` and tap "Add to Paperback"
![IMG_6214](IMG_6214.PNG?resize=450,450 "IMG_6214")

5. Tap the source you just named.
6. Tap Install next to the Tracker
![IMG_6215](IMG_6215.PNG?resize=450,450 "IMG_6215")