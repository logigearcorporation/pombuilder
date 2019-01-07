# POM Builder

<a href="https://imgur.com/Xc8l7OK"><img src="https://i.imgur.com/Xc8l7OK.png" title="source: imgur.com" style="width:100%;"/></a>

## What is it?
POM Builder is a Chrome extension that helps you quickly generate the most robust locator for your web elements. The suggested output might be either XPath, CSS selector, Id, Name, linkText, etc. You can use these locators with [Selenium](https://www.seleniumhq.org/), [Protractor](https://www.protractortest.org) or [TestArchitect](https://www.testarchitect.com/).


Get the Chrome extension [here](https://chrome.google.com/webstore/detail/pombuilder-%E2%80%93-auto-generat/akcejfbfkkjnghlfngighgncolfaghco).


## Who is it for?
All developers and testers who aspire to automate their web apps using popular automation frameworks like Selenium, Protractor and TestArchitect.

## Why use it?
### Smart Gen
 **Smart Gen** leverages Pattern Recognition (AI) to contextually guess the best locator for you. The best locator should be:
 1. Short
 2. Insensitive to GUI changes 
 3. Easy to understand

How to use? 
1. Right click on a web element, then select `POM Builder - Quick Copy` > `Suggested Locator` to copy the recommended locator to clipboard.

<img src="https://media.giphy.com/media/MTs2byIkPjnabjm6dK/giphy.gif" alt="Quick Copy" style="width:300px;"/>

2. Press `F12` or right click > `Inspect` to open Chrome DevTools then click on the `POM Builder` tab (usually the last sub-tab of the `Elements` tab). Whenever, you inspect an element, the POM Builder tab will refresh to show the new recommended locator for that element.

### Locator Test
You can evaluate the recommended locator or your customized locator to check whether that locator uniquely identifies the web element of interest. 

How to use? Open the `POM Builder` tab (see above) > paste the locator in question to the textbox below LOCATOR TEST > click the magnifying glass button. If it shows 1/1, you're good. Otherwise, refine the locator.

<img src="https://media.giphy.com/media/e7PjUrVJxC8wnntpMV/giphy.gif" alt="Quick Copy" style="width:300px;"/>

### POM Code Gen
After designing the best locator for your web element, POM Builder can further help you to generate the corresponding POM code snippet. This code snippet can be pasted directly into your Selenium, Protractor or TestArchitect project. 

How to use? 
* Open the `POM Builder` tab (see above) > look for the **Output** dropdown list > select your desired output (raw value/Selenium Java/Protractor/TestArchitect). 
* If you want to add your own output template, click the **Gear** button > **Add New** button > name the new template > format it however you like > click **Apply**

## Notes
* After installation, please restart Chrome. We've received feedback that the extension wouldn't work if you don't restart Chrome.
* POM Builder does NOT track your browsing history in any way, nor does it transmit any data over the internet. All data remains on your local hard disk drive at all times. However, POM Builder needs "webNavigation" and "tabs" permissions in order to generate locators for elements inside iFrames. 

## Contacts
* LogiGear Corp.
* Email: pombuilder@logigear.com
* Address: 1730 S Amphlett Blvd Suite 110, San Mateo, CA 94402, US