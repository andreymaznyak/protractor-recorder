# Protractor Recorder
Chrome extension to record Protractor E2E test scripts

## How to Install
1. Download ZIP and unzip to folder on your local machine
2. Start Chrome browser and navigate to *chrome://extensions*
3. Click on **Load unpacked extension** and select location of unzipped folder
4. Enable the Protractor Recorder extension
 
## How to Use
1. Open your web site in Chrome
2. Launch **Developer Tools** by pressing F12
3. Select **Protractor** tab
4. Interact with your web site.  Each action is recorded in the Protractor Recorder console.
5. When you're done, click **Copy to Clipboard** to copy the recorded script.

## Should I disable automatic synchronization?
Check this box if the recorded scripts are timing out when run in Protractor.  Protractor has known issues with AngularJS applications that use **$timeout**.  See Protractor issues [#169](https://github.com/angular/protractor/issues/169) and [#2950](https://github.com/angular/protractor/issues/2950).
