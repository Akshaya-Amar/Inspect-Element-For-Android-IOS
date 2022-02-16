# Inspect-Element-For-Android-IOS

## Steps

**1. Open your favourite browser**

**2. Open a new tab**<br><br>
<img style="border: 5px solid #555;" src="./Images/1.jpg" width="40%" height="40%">
<br><br><br>

**3. Bookmark it**<br><br>
<img src="./Images/2.jpg" width="40%" height="40%"><br><br><br>

**4. You should see a toast message as Bookmarked at the bottom, where you have to click on edit button**<br><br>
<img src="./Images/3.jpg" width="40%" height="40%"><br><br><br>

**5. You will be redirected to Edit bookmark page where you can see Name, Folder and URL**<br><br>
<img src="./Images/4.jpg" width="40%" height="40%"><br><br><br>

**6. Edit name as Inspect Element (or any name you may feel like)**<br><br>
<img src="./Images/5.jpg" width="40%" height="40%"><br><br><br>

**7. Now, copy the following code and paste it in URL section**<br>

```javascript
javascript:(function () { var script = document.createElement('script'); script.src="//cdn.jsdelivr.net/npm/eruda"; document.body.appendChild(script); script.onload = function () { eruda.init() } })();
```

<img src="./Images/6.jpg" width="40%" height="40%"><br><br><br>

**8. Now, go back and visit the page/website you want to inspect**<br><br>
<img src="./Images/7.jpg" width="40%" height="40%"><br><br><br>

**9. In the search/address bar, enter the name as Inspect Element. You will see the link that you just recently bookmarked**<br><br>
<img src="./Images/8.jpg" width="40%" height="40%"><br><br><br>

**10. Click on that URL and you will see an icon**<br><br>
<img src="./Images/9.jpg" width="40%" height="40%"><br><br><br>

**11. Click on that icon to open the tool**<br><br>
<img src="./Images/9.1.jpg" width="40%" height="40%"><br><br>
That's it. You are good to go now.
 
<hr>
 
# Do you want to execute some script on Console?

**1. You will see a small arrow on bottom left, just click on that to start writing scripts**<br><br>
<img src="./Images/10.jpg" width="40%" height="40%"><br><br><br>

**Try the following code**<br>
```
console.log(((5 & 1) != 0) ? "Odd" : "Even");
```
<br><br>
**2. Click on the Execute button**<br><br>
<img src="./Images/11.jpg" width="40%" height="40%"><br><br><br>

**3. After execution**<br><br>
<img src="./Images/12.jpg" width="40%" height="40%"><br><br>
<hr>

# Want to play more around it?

**1. Theme**<br>
* **Go to Settings tab**<br><br>
<img src="./Images/13.jpg" width="40%" height="40%"><br><br><br>

* **Select Theme and change as per your choice**<br><br>
<img src="./Images/14.jpg" width="40%" height="40%"><br><br><br>

* **After changing theme**<br><br>
<img src="./Images/15.jpg" width="40%" height="40%"><br><br>

**2. Display**<br><br>
* **Resize the display**<br><br>
<img src="./Images/16.jpg" width="40%" height="40%"><br><br><br>

* **After changing display size**<br><br>
<img src="./Images/17.jpg" width="40%" height="40%"><br><br><br>

# Features

**Credits**



You can play around with more stuffs like these on your own. Give it a try

If you find this useful, give a star
