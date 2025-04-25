<p align="center">
    <img src="./Public/res/AFlogo2.png" width="188" title="Timelapse" alt="Timelapse">
</p>

# <span style="color:orange;font-weight:900">Timelapse</span>

Hello and welcome to Timelapse!<br>
	  
Timelapse is a light, simple, software on premise to build and own your photo blog.<br>
	   
Timelapse is released under GPLv3 license, it is supplied AS-IS and we do not take any responsibility for its misusage.<br>
	   
First step, use the password box and salt fields to create the hash to insert in the config file. Remember to manually set there also the salt value.<br>
	   
As you are going to run Timelapse in the PHP process context, using a limited web server or phpfpm user, you must follow some simple directives for an optimal first setup:<br>

<ol>
<li>Check the write permissions of your "data" folder in your web app Private path; and set its path in the config file.</li>
<li>Set the default Locale.</li>
<li>Set FILE_MAX_SIZE (remember that some PHP settings could limit the upload behaviour of Timelapse too)</li>
<li>Set BLOG_MAX_POSTS to limit the number of visible posts in the blog.</li>
</ol> 

You can access your avatar by http://yourdomain.com/<your_avatar>. Login with the password for the admin view. Drag-n-drop all your resources in the browser window.<br>

For any need of software additions, plugins and improvements please write to <a href="mailto:info@5mode.com">info@5mode.com</a>  

To help please donate by clicking <a href="https://gaox.io/l/dona1">https://gaox.io/l/dona1</a> and filling the form. 

### Public view:

![Timelapse in action #1](/Public/res/screenshot1.png)<br>

### Admin view:

![Timelapse in action #2](/Public/res/screenshot2.png)<br>

Feedback: <a href="mailto:code@gaox.io" style="color:#e6d236;">code@gaox.io</a>

