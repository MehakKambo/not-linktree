# Not-LinkTree
This is a simple HTML code for creating a clone of LinkTree, a platform that allows users to create a personalized webpage with links to their various social media profiles or websites. The code provides a template for displaying a profile picture, user name, and a list of links to different social media platforms.

# Usage
To use this code, follow the steps below:

1. Create an HTML file and copy the code into it.
2. Save the profile picture as "profile.png" in the same directory as the HTML file.
3. If you want to customize the style, create a CSS file named "style.css" and link it to the HTML file using the ```<link rel="stylesheet" href="style.css">``` tag. Make sure the CSS file is also saved in the same directory.

# Structure
The code consists of the following elements:

- ```<a id="profilePicture" href="#popup">```: This is a link that displays the profile picture. Clicking on it opens a popup window showing a larger version of the profile picture.
- ```<div class="overlay" id="popup">```: This is the overlay for the popup window.
- ```<div class="popup">```: This is the container for the popup window content.
- ```<div class="popup-photo">```: This div contains the enlarged profile picture as a link to open it in a new tab.
- ```<div class="popup-quote">```: This div displays a quote or text associated with the profile.
- ```<a class="popup-close" onclick="history.back()">&times;</a>```: This is a close button for the popup window.
- ```<div id="userName">```: This div displays the user name or handle.
- ```<div id="links">```: This div contains a list of links to different social media platforms.
- ```<a class="link" href="...">```: These are individual links to social media platforms, each with an associated icon and text.
- ```<div id="hashtag">```: This div displays a hashtag or a message associated with the user.

# Customization
To customize the code, you can make the following changes:

- Replace "profile.png" with your own profile picture. Make sure to save the image in the same directory as the HTML file.
- Update the text within the ```<div id="userName">``` to display your desired user name or handle.
- Modify the links within the ```<div id="links">``` to point to your own social media profiles or websites. You can also add or remove links as needed.
- Change the text within the ```<div id="hashtag">``` to display your own hashtag or message.

Additionally, if you want to customize the appearance of the page, you can create a CSS file named "style.css" and define your own styles. Remember to link the CSS file to the HTML file using the ```<link rel="stylesheet" href="style.css">``` tag.

# Dependencies
The code relies on the following external resources:

- Google Fonts: This link provides the Lato font styles used in the page.
- Font Awesome: This library provides the icons used for the social media links.

Make sure you have an internet connection to access these resources, or you can download the required fonts and icons and reference them locally instead.

# License
Feel free to modify and use it according to your needs.