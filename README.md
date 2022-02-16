**If you find this useful, give it a** &#11088;

# Inspect Element For Android/IOS 

## Follow the Steps to enable the Developer tool in your mobile's browser

**1. Open your favourite browser**<br>
It can be either **Google Chrome** or **Firefox** or **Safari**. **100%** Working on all mentioned browsers.

**2. Open a new tab**<br>

<img src="./Images/1.jpg" width="60%" height="60%">
<br><br>

**3. Bookmark it**<br>

<img src="./Images/2.jpg" width="60%" height="60%">
<br><br>

**4. You should see a toast message as Bookmarked at the bottom, where you have to click on edit button**<br>

<img src="./Images/3.jpg" width="60%" height="60%">
<br><br>

**5. You will be redirected to Edit bookmark page where you can see Name, Folder and URL**<br>

<img src="./Images/4.jpg" width="60%" height="60%">
<br><br>

**6. Edit name as Inspect Element (or any name you may feel like)**<br>

<img src="./Images/5.jpg" width="60%" height="60%">
<br><br>

**7. Now, copy the following code and paste it in URL section**<br>

```javascript
javascript:(function () { var script = document.createElement('script'); script.src="//cdn.jsdelivr.net/npm/eruda"; document.body.appendChild(script); script.onload = function () { eruda.init() } })();
```
<br>
<img src="./Images/6.jpg" width="60%" height="60%"><br><br>

**8. Now, go back and visit the page/website you want to inspect**<br>

<img src="./Images/7.jpg" width="60%" height="60%"><br><br>

**9. In the search/address bar, enter the name as Inspect Element. You will see the link that you just recently bookmarked**<br>

<img src="./Images/8.jpg" width="60%" height="60%"><br><br>

**10. Click on that URL and you will see an icon**<br>

<img src="./Images/9.jpg" width="30%" height="30%">
<br>

**11. Click on that icon to open the tool**<br>

<img src="./Images/9.1.jpg" width="60%" height="60%">
<br><br>

**That's it. You are good to go now.**
<br>
 
# Do you want to execute some script on Console?

**1. You will see a small arrow on bottom left, just click on that to start writing scripts**<br>

<img src="./Images/10.jpg" width="60%" height="60%">
<br><br>

**Try the following code**<br>
```
console.log(((5 & 1) != 0) ? "Odd" : "Even");
```
<br>

**2. Click on the Execute button**<br>

<img src="./Images/11.jpg" width="60%" height="60%">
<br><br>

**3. After execution**<br>

<img src="./Images/12.jpg" width="60%" height="60%">
<br>

# Want to play more around it?

**1. Theme**<br>

* **Go to Settings tab**<br>

<img src="./Images/13.jpg" width="60%" height="60%">
<br><br>

* **Select Theme and change as per your choice**<br>

<img src="./Images/14.jpg" width="60%" height="60%">
<br><br>

* **After changing theme**<br>

<img src="./Images/15.jpg" width="60%" height="60%">
<br><br>

**2. Display**<br>

* **Resize the display**<br>

<img src="./Images/16.jpg" width="60%" height="60%">
<br><br>

* **After changing display size**<br>

<img src="./Images/17.jpg" width="60%" height="60%">
<br>

You can play around with more stuffs like these on your own. Give it a try

## Features

* [Console](doc/TOOL_API.md#console): Display JavaScript logs.
* [Elements](doc/TOOL_API.md#elements): Check dom state.
* [Network](doc/TOOL_API.md#network): Show requests status.
* [Resource](/doc/TOOL_API.md#resources): Show localStorage, cookie information.
* [Info](doc/TOOL_API.md#info): Show url, user agent info.
* [Snippets](doc/TOOL_API.md#snippets): Include snippets used most often.
* [Sources](doc/TOOL_API.md#sources): Html, js, css source viewer.

## Credits 
[Eruda](https://github.com/liriliri/eruda)<br>
Eruda is an open source javascript package publicly hosted on github.

**If you find this useful, give it a** &#11088;
