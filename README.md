# Google Cloud Platform | Cloud Vision API
Google Cloud | Cloud Vision API. This is an appliction using mobile images or images taken through camera to take information present in it. Analyse the image through provided API.

# Cloud Vision API
Cloud Vision API provides powerful Image Analytics capabilities as easy to use APIs. It enables application developers to build the next generation of applications that can see and understand the content within the images.

<img src='https://assets.pcmag.com/media/images/514343-google-cloud-platform-logo.jpg' alt='google cloud' width='40%' height='auto'/> --- <img src='https://miro.medium.com/max/600/1*sMfvSUW1NE3nusitFEZCDw.png' alt='the cloud vision api image' width='40%' height='auto'/>

# Using Camera
- Here is the quick demostration of application that how it will use the device hardware from the side of end user.
- The application uses only device's camera to get the image.
- Then we convert taken image into bitmap format, so it is easy to read the image. After this, it is encoded into base64.
- Which take the image and compare to the information available on server to provided image.

<img src='https://martdk.com/logfiles/images/git/1.gif' alt='the cloud vision api image' width='25%' height='auto'/> ---------- <img src='https://martdk.com/logfiles/images/git/2.png' alt='the cloud vision api image' width='25%' height='auto'/>

# Using Device Files
- Here is the quick demostration of application that how it will work on already stored files.
- The application uses only image format files stored in your local storage.
- After this, all procedure is as similar as in case of camera. It convert the image into bitmap format, so it is easy to read the image and it is encoded into base64.

<img src='https://martdk.com/logfiles/images/git/3.gif' alt='the cloud vision api image' width='25%' height='auto'/> ---------- <img src='https://martdk.com/logfiles/images/git/4.png' alt='the cloud vision api image' width='25%' height='auto'/>

# Steps to install in your local system
**Step 1 :** First go to **Google Cloud Console** and search for Google Vision API. Enable the API and copy **API key** and save it for later.<br/>
*If you won't have Billing account then continue from step 2 else jump to step 3.*<br/>
**Step 2 :** Go to qwiklabs.com and search **Google Vision API lab**. (*you might find many labs so choose any one of them*).<br/>
**Step 3 :** As shown in step 1, copy the API key from student account of qwiklabs and save it for later.<br/>
**Step 4 :** Select your desired local system directory to clone the project using step 5 command.<br/>
**Step 5 :** ``` $ git clone DSC-SVVV/Google-Cloud-Platform-_-Cloud-Vision-API```<br/>
**Step 6 :** Open this project through **Android Studio**.<br/>
**Step 7 :** Now, go to line number **50** of your **MainActivity.java** and paste the **API key**.<br/>
**Step 8 :** Yeah! Now you are able to get information through images.<br/>
<br/>
# Future Scope
- We want to optimse our application as much responsive as possible.
- We are trying to manage the running camera like a recording view.
- Shows the image information very quickly on camera view, not in another activity.
