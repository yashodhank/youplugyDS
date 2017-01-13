# youplugyDS
Youplugy DS is an open-source version of the famous Xibo Android Digital Signage Player 

##Motivation##
The **youplugyDS** was built after the Youplugy founders tried to adopt one of the most famous Digital Signage players to their business model.    


So we took the [Xibo Android Player](http://http://xibo.org.uk/)  and developed a very similar player - **yes, we used common reverse engineering techniques** and our big knowledge, of years, about their Player and their open-source [CMS](http://xibo.org.uk/get-xibo/) to develop a player that fits our needs, like:
* Run as a Android Laucher *android.intent.category.HOME*
* Be able to handle user's touch interaction inputs
* Block users to the Android OS or other functions - Kiosky Mode
* Be able to present a media based on "external" inputs/events. For instance, some user is connected to the Tablet through a Beacon and for some way, the backend application knows she is a 40years old lady. The traditional Digital Signage players would don't care and present the scheduled media, even though it is a muscle car advertising focusing the males. We want our player to be able to present a content based on an event. 
* **Zero or the minimal cost!!!**


There are other motivations but at that moment point it was clear to us that, for a *startup* like us, we should invest our money in other things instead of keep paying the licences. We had great Android skills and the nights were unbooked. So why not?

##Xibo - They are the guys##
Yes, they are. They created one of the best Digital Signage CMS and open-sourced it. Thanks Dan and his team!
They also offer their services to host CMS for the players - Android is payed while Windows is free: [Spring Signage](https://springsignage.com/)

**IMPORTANT**
Really, we are opening here to the communuty couple dozens of hours of our time debugging, studying, coding and mounting the puzzle we had in our hands which was the Xibo Client APK and its connection to their CMS.
If you like it and you want to try the best Digital Signage Experience go to springsignage.com



##How to Begin##
You can run the youplugyDS in any environment with PHP 5.3.3 or above, MySQL with PHP PDO support and Apache / IIS / Ngiex

###Docker - soon###

###Cloud (Amazon AWS) - soon###

###Local Windows / Linux Setup###
*Download Xibo Open-Source CMS Version 1.7.9 here http://xibo.org.uk/get-xibo/ or https://github.com/youplugy/youplugyDS/blob/master/cms/xibo-cms-1.7.9.zip
*Follow the Xibo CMS Setup Instructions here: http://xibo.org.uk/manual/en/install_environment.html
*Download the Beta youplugyDS player: (send me an email: ricardogil@youplugy.com.br and I will provide you the apk. The source code I should upload soon to this repo)


##Current / Supported features##
* Registration and connectivity with CMS
* Download Schedule, Files
* Upload Logs and Stats
* Play Images, Videos, Text(some issues), WebPage, DataSet, RSS(did not try yet)
* Play layouts with single and many regions
* Play different Schedules, Default Layout, change layouts, etc
* Load new layouts and its medias as soon something is updated in the CMS
* Starts on boot as Launcher

##Missing features / Need help from the community##
* Small fixes on interface, menus, texts, etc
* TBD -- there are some things yet to add here...












