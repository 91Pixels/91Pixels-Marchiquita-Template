91Pixels/Marchiquita
Personal Portfolio Template
Marchiquita holds a special place in my heart as it was the beach where I spent my childhood, resembling a playful paradise. Its name serves as a beautiful tribute to this enchanting natural haven.

If you have any questions that are beyond the scope of this documentation file, please feel free to contact me​ anytime.


General Information
Template version: 2.0.0
By: Mike
Template files structure
documentation - The current folder
Template - Contains Template files
css - Contains Stylesheets files
fonts - Contains Font files
img - Contains Images
js - Contains JavaScript files
php - Contains PHP files
*.html - Main HTML files
Basic minimal file structure
<!DOCTYPE html>
<html lang="zxx">

<head>
  <!-- Title of the page, scripts, styles -->
</head>

<body>
  <!-- Preloader-->
  <!-- Navbar-->
  <!-- Home-->
  <!-- About lightbox-->
  <!-- Resume lightbox-->
  <!-- Portfolio lightbox-->
  <!-- Blog lightbox-->
  <!-- Contact lightbox-->
  <!-- Scripts-->
</body>

</html>
Notes
For Template customization, please add your custom styles and scripts to css/custom.css and js/custom.js. This will make it easier for you to install template updates.

Variants Customizations
Variants List

Video Background Variant
We have used jquery.mb.YTPlayer component in this variant, it lets you play YouTube videos as a background. Simply, open video.html file, search homeVideo and in the data-property attribute, replace https://youtu.be/YOUR_VIDEO_ID with the link of your YouTube video:

<div class="player" id="homeVideo" data-property="{videoURL:'https://youtu.be/KR97TgpMyrc',containment:'#home',autoPlay:true, mute:true, showControls:false, stopMovieOnBlur:false, showYTLogo: false}"></div>
General Customizations
Color schemes
We have created 24 various color options, choose your favorite...

To switch colors, you just have to edit the following line in your HTML file:

<link id="color-scheme" rel="stylesheet" href="css/colors/main-COLOR_NAME.css">
Available color options
main-blue.css         main-darkpink.css      main-pink.css
main-blueviolet.css   main-darkred.css       main-purple.css
main-brown.css        main-darkyellow.css    main-red.css
main-cyan.css         main-green.css         main-redpink.css
main-dark.css         main-indigo.css        main-royalblue.css
main-darkblue.css     main-moodyblue.css     main-tangopink.css
main-darkgreen.css    main-nightskyblue.css  main-teal.css
main-darkmagenta.css  main-orange.css        main-yellowgreen.css
Icons
We have used Ionicons pack in this Template, you can easily add any icon by getting it's name from Here.

How to:

Visit https://ionicons.com/v4
Select the icon you want to use
A bar will appear, click on USAGE >
Scroll down to the bottom of the page, look for the Using the Font Icon section and use the code that's shown under Basic usage
Contact form
To configure this form, open php/contact.php and edit the following line:

// Email recipient
$EmailTo = "YOUR_EMAIL@EXAMPLE.COM";
If the Contact form is not working after configuring it, there are some possibilities that could block this form from sending you submissions:

Check your spam folder
Make sure to enable the PHP mail() function on your server
Upgrade the PHP version running on your server (Contact your hosting provider if you don't know how to upgrade)
Global Classes
.button-main - The main button style (White)
.button-scheme - An additional class for .button-main to inherit the current color scheme (E.g: blue, red...)
.element-cover-bg - Adds an overlay background to the element
.color-scheme - Current scheme color:
.background-scheme - Current scheme background-color:
.anchor-basic - Removes the the color from <a> tags
Bootstrap spacing classes
You can also use a wide range of shorthand responsive margin and padding utility classes from Bootstrap.

Uploading to your Server
Assuming you already have a Domain name and Hosting, You need to get your FTP details from your Hosting control panel, then use those login details to connect to your server using an FTP client such as FileZilla, then you can start uploading your files.

Note: You can also upload the template using the file manager from your control panel

Due to local security restrictions, some features will not work locally. But everything will work once you upload your files to your server.

Support
We will be happy to help you solve any issues. If you have any questions, suggestions or ideas. Please feel free to contact me anytime.



And Follow our profile

Once again. Thank you for visiting!


Designed and Developed with ❤️ by Michael A. Camacho.
