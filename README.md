## What is Mail Stats  

Mail Stats is an open source sample app for [Emailbox](https://getemailbox.com), that is built using HTML, CSS, and Javascript. It has been tested on Android and iOS.  

Pull requests are welcome!  

## Current status 

[Download the Android APK on the Mail Stats site](http://mailstats.getemailbox.com)  

Mail Stats is pretty simple, it shows your Sent vs. Received numbers for the previous 7 days. Additional interesting stats such as time-to-respond, wordiness level, and contacts analytics are in development. 


## Contents of this Repository  
Source for the Mail Stats sample app. The app works in conjunction with a server-side component (running the stats queries) and the Emailbox API (https://getemailbox.com/docs).  

## Requirements to run:  
- Android Phone running 2.2+ (not ready for Tablets) 

## Build Option 1: PhoneGap Build  
1. Fork this repo (optional)
1. Sign up for Adobe PhoneGap Build: http://build.phonegap.com/plans/free 
1. Create a new project in PhoneGap Build using your forked GitHub URL (or just the https url for this repo)  
1. Build the project, then download and install the created Android build (.apk). Takes about 30 seconds. [Use a barcode scanner](https://play.google.com/store/apps/details?id=com.google.zxing.client.android&hl=en) for easy download! 

## Design and Debugging  
Try out [debug.phonegap.com](http://debug.phonegap.com) (super buggy and slow, but a useful HTML view) or open up index.html in your browser and use the native developer tools. 

## Server-side   
By default the basic server is used. If you want to run your own server:  

1. Register as an emailbox developer (https://getemailbox.com/login/first)
1. Follow instructions at repo: https://github.com/emailbox/mailstats_server    








