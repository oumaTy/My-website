### **Description**  
These are the first three static web pages I ever wrote. You can customize them and give them as a gift to your friends, your significant other, a friend who stays a friend after receiving it, or a friend who becomes something more after receiving it. 😂  

Since these pages were originally written as gifts, there may be some issues. Please excuse any problems you may encounter while using them.  

---

### **Live Demo**  
[Click here to preview online](http://119.23.212.211:8080/birthday-basic/)  
- **Username:** 123  
- **Password:** 123  

---

### **Requirements for Use**  
- If you have experience in front-end development, you can freely modify this template. However, I warn you: my old code might drive you mad! (Just kidding… but not really. Even I get frustrated looking at it now.)  
- If you have no experience in front-end development, maybe consider gifting something else?  
- If you have a basic understanding of front-end development, you can follow the guide below to learn how to modify the template.  

---

### **Template Guide**  

#### **Changing the Login Credentials**  
In the current directory, locate the file: **`js/login.js`**  

Modify the **username** and **password** by changing `123` to your desired credentials:  

```js
// Change "123" and "123" to update the username and password
if(userName=="123" &&  pwd=="123"){
  event.preventDefault();
  $('form').fadeOut(500);
  $('.wrapper').addClass('form-success');
  setTimeout(function(){location.href="BirthdayCake.html";},2000);
}
```

---

#### **Replacing Text and Images in the Memories Page**  
Example of modifying the **third section**:  

```html
<!-- Third Section -->
<div class="section">
    <!-- These two divs represent the timeline and the small ball on the left -->
    <div class="timeline"></div>
    <div class="timepoint21"></div>
    
    <div class="ly-box21">
        <div class="ly-txt21">
            <!-- Change the date here -->
            201X-1X-2X
        </div>
        <div class="ly-txt22">
          <!-- Change the text content here. Use <p></p> to wrap paragraphs -->
           <p> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
           <p>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</p>
        </div>
        <div class="ly-imgbox21">
          <!-- Change the image here. First, rename your image and place it inside the 'img' folder.
               If you don't know CSS, it's best to crop the image to a suitable size.
               If you know CSS, you can adjust the width settings in the corresponding CSS file. -->
          <img class="ly-img21" src="img/2014.11.26-1.png">
        </div>
    </div>
    <div class="ly-triangle21"></div>

    <div class="ly-box22">
        <div class="ly-txt23">
          <!-- Similar to above, modify accordingly -->
            201X-1X-1X
        </div>
        <div class="ly-txt24">
            XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        </div>
        <div class="ly-imgbox22">
          <img class="ly-img22" src="img/2014.12.19-1.png">
        </div>
    </div>
    <div class="ly-triangle22"></div>

     <div class="ly-box23">
        <div class="ly-txt25">
            201X-1X-2X
        </div>
        <div class="ly-txt26">
            XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
        </div>
        <div class="ly-imgbox23">
          <img class="ly-img23" src="img/2014.12.20-1.jpg">
        </div>
    </div>
    <div class="ly-triangle23"></div>
</div>
```

---

### **How to Share the Website**  

#### **Option 1: Send a Compressed ZIP File**  
- Simply compress all the files and send them to your friend.  

#### **Option 2: Deploy to a Cloud Server or Virtual Hosting**  

**Deploying on a Cloud Server**  
You’ll need your own cloud server. There are many deployment methods, but I recommend the following:  

1. **Using Tomcat**  
   - Download and extract **Tomcat** on your server.  
   - Open the **webapps** folder.  
   - Create a new folder with an **English name** (this will be the site path).  
   - Copy all project files (**HTML, CSS, JS**) into this new folder.  
   - Restart Tomcat, and your site should be live.  

2. **Using Nginx**  
   - The process is similar to Tomcat. I won’t go into details—Google it if needed.  

**Deploying on Virtual Hosting**  
- Check the hosting provider’s documentation for detailed instructions.  

**Using a Custom Domain**  
- Purchase a domain name.  
- Follow the provider’s tutorial to link it to your website.  

---

### **Important Notes**  
🚀 **Use Google Chrome for the best experience!**  
📱 **No mobile version available yet!**   

These improvements will be made whenever I have free time—stay tuned! 🎉
