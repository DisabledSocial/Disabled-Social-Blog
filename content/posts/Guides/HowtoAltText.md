---
title: "Alternative Text"
date: 2023-01-07
categories: ["Guides"]
---

NOTE: This guide was written for Mastodon 4.0.

## Introduction

Alternative text, or alt text for short, is descriptive text that conveys the meaning and context of visual items including images and videos. Alt text is critical for those who use screen readers to navigate visual content. Alt text is also the text that will show up if an image is not rendered correctly on a webpage.

Writing alt text can seem daunting at first. There’s a balance between describing the media well enough so that the user knows what’s going on while not being overly wordy. With some practice, adding alt text to images will become second nature.

In this guide, we will show you:

- the mechanics of how to add alt text when crafting a toot
- how to correct missing alt text
- how to ask for help alt texting if you have conflicting access needs and are unable to
- how to craft alt text descriptions for four main situations: videos, pictures, screenshots of graphs, and screenshots of text. 

Resources on how to craft alt text are shared at the end of the guide.






## Text-Only Instructions

### How to Add Alt Text 

#### Videos

Alt text for videos must be added in the toot itself. Unlike images, there is not a designated spot for you to add it. The process is the same whether you are on your desktop or mobile phone.

#### Images

##### Desktop

**Step 1.** After uploading an image, you will notice at the bottom of the image that there is a banner with the words: “No description added.” Click on it.

**Step 2.** A new window will open where you can enter in the alt text. There is also the option to detect from the picture. It's best to manually write out the alt text, as the auto-generated alt text usually turns out to be gibberish. Once you are finished adding the alt text, click ‘Apply.’ Then click ‘Publish’ to post the toot.

**Step 3.** To double check whether or not the alt text worked, you will need to click on the image to expand it, right click it and click ‘inspect.’ In the panel, it will highlight the part of code that pertains to the photo. You will see in the code block, the words alt = . That’s where the alt text goes. If there’s no alt text, that tag won’t even be there.

##### Mobile

NOTE: These instructions were written for the Tusky app. Being able to visualize the alt text after publishing is not possible with all of the apps. The most foolproof way is to either check it with a screen reader OR to go to a desktop and use the inspect tool.

**Step 1.** After uploading the image, click on the little black circle in the lower right hand corner with the A and the checkmark. A menu will pop up. Tap “Set caption.”

**Step 2.** A window will pop up where you can add the alt text. Click ‘OK’ when finished.

**Step 3.** To double check whether or not the alt text worked, you will need to click on the image to expand it. If the alt text published correctly (for Tusky app, this is not universally true for all apps), you will see it below the image.

### How to Correct Missing Alt Text

If you have forgotten the alt text when initially uploading the image or screenshot, there is no way to correct it directly in the original image by using the built in Mastodon tools. At this point, you have a few options:

1. Completely delete the toot and start over
    - You can do this on both Desktop and in any app
2. Put it directly in the toot with the format: “Alt text: [insert your alt text here].” An example of the latter is shown below.
    - You can edit a toot on Desktop but you cannot edit a toot in Tusky (I am not sure if this is the case with other apps).
3. Re-upload the photo and add in the alt text.
    - You can edit a toot on Desktop but you cannot edit a toot in Tusky (I am not sure if this is the case with other apps).
    
To edit a toot on the desktop to do either options 2 or 3, navigate to the toot with the missing alt text, click the three dots in the lower right hand corner, click edit, and the alt text box shown above will open and you can follow the same steps as before.







## Text + Screenshots Instructions

### How to Add Alt Text 

#### Videos

Alt text for videos must be added in the toot itself. Unlike images, there is not a designated spot for you to add it. The process is the same whether you are on your desktop or mobile phone.

#### Images

##### Desktop

**Step 1.** After uploading an image, you will notice at the bottom of the image that there is a banner with the words: “No description added.” Click on it.

![A blank toot with an image uploaded. At the bottom of the image is a banner with the words: "No description added."](/img/Guides/AltText/DesktopUploadImage.png)

**Step 2.** A new window will open where you can enter in the alt text. There is also the option to detect from the picture. The top screenshot below is a manually written alt text description and the bottom one is the auto generated one. You can see that didn’t work out too well! Once you are finished adding the alt text, click ‘Apply.’ Then click ‘Publish’ to post the toot.

![The alt text window that pops up after clicking on "No description added" on the uploaded image. There is a textbox for you to add the description. Below that is the option to try an auto generated description. Below that is the Apply button. The example description here says the following: "A hot cup of cocoa sits on a wooden serving board. Surrounding it are shortbread cookies, mini marshmallows, a tea towel, and some holiday decorations."](/img/Guides/AltText/AltTextBoxDesktop.png)

![The alt text window that pops up after clicking on "No description added" on the uploaded image. There is a textbox for you to add the description. Below that is the option to try an auto generated description. Below that is the Apply button. The auto generated example description here is a bunch of random gibberish.](/img/Guides/AltText/ImageAltDetectFromPic.png)

**Step 3.** To double check whether or not the alt text worked, you will need to click on the image to expand it, right click it and click ‘inspect.’ In the panel, it will highlight the part of code that pertains to the photo. You will see in the code block, the words alt = . That’s where the alt text goes. If there’s no alt text, that tag won’t even be there.

![Google console HTML code on the elements tab after right clicking on an image and clicking inspect. This is where you can check to see if the added alt text actually published with the image.](/img/Guides/AltText/RightClickAlt.png)

##### Mobile

NOTE: These instructions were written for the Tusky app. Being able to visualize the alt text after publishing is not possible with all of the apps. The most foolproof way is to either check it with a screen reader OR to go to a desktop and use the inspect tool.

**Step 1.** After uploading the image, click on the little black circle in the lower right hand corner with the A and the checkmark. A menu will pop up. Tap “Set caption.”

![A screenshot of an empty toot box on the Tusky app after clicking on the lower right hand corner of an uploaded image. A menu pops up with the options: set caption, set focus point, edit image, and remove. At the bottom of the toot are the usual other tools along with the publish button.](/img/Guides/AltText/MobileSetCaption.png)

**Step 2.** A window will pop up where you can add the alt text. Click ‘OK’ when finished.

![Alt text window where you can enter in the alt text. Above the textbox is the image that you are alt texting. At the bottom from left to right are the options to cancel or click OK.](/img/Guides/AltText/MobileAltTextBox.png)

**Step 3.** To double check whether or not the alt text worked, you will need to click on the image to expand it. If the alt text published correctly (for Tusky app, this is not universally true for all apps), you will see it below the image.

![The image is at the top and the published alt text appears at the bottom.](/img/Guides/AltText/MobileAltTextCheck.png)

### How to Correct Missing Alt Text

If you have forgotten the alt text when initially uploading the image or screenshot, there is no way to correct it directly in the original image by using the built in Mastodon tools. At this point, you have a few options:

1. Completely delete the toot and start over
    - You can do this on both Desktop and in any app
2. Put it directly in the toot with the format: “Alt text: [insert your alt text here].” An example of the latter is shown below.
    - You can edit a toot on Desktop but you cannot edit a toot in Tusky (I am not sure if this is the case with other apps).
3. Re-upload the photo and add in the alt text.
    - You can edit a toot on Desktop but you cannot edit a toot in Tusky (I am not sure if this is the case with other apps).
    
To edit a toot on the desktop to do either options 2 or 3, navigate to the toot with the missing alt text, click the three dots in the lower right hand corner, click edit, and the alt text box shown above will open and you can follow the same steps as before.

![Original toot with image with missing alt text. In the lower right hand corner is the three dots that can be clicked to open up a menu. Once opened, the menu contains the following options: expand this post, copy link to post, embed, bookmark, pin on profile, mute conversation, edit, delete, delete & re-draft.](/img/Guides/AltText/EditMenuDesktop.png)

## How to Alt Text in Different Situations

### Videos

When uploading a video to Mastodon, it should contain three elements for accessibility: no flashing lights, closed captioning, and an alt text description of what goes on in the video.

For example, if I were to upload a video of a cat climbing a Christmas tree that later crashes to the ground, I might say something like: “A rambunctious cat launches himself into the middle of the tree and begins climbing the tree with wide and excited eyes. The tree eventually comes crashing to the ground.” For closed captioning, I would indicate if there is music playing in the background and what type (e.g., smooth jazz), if there is laughter (e.g., a woman laughs), and if there is any speech and what is being said.

### Pictures

Depending on the context, the following things are generally included when alt texting a picture: the location or setting, the subject, and/or a description of the foreground, background, color, and directional orientation of objects. The hot cocoa picture used throughout this guide is an example of alt texting a picture.

### Screenshots of Graphs

Alt texting screenshots of graphs can be tricky. There is an entire resource dedicated towards teaching people how to alt text various types of technical charts. Please see the resource at the end of this guide for a thorough discussion of how to handle different types of graphs. In general, you should describe the type of graph (e.g., pie chart, bar graph, scatter plot, etc.), the axis titles, the range of the axes, any chart labels, and the general trends. 

### Screenshots of Text

When alt texting screenshots of text, the alt text should contain all of the text contained within the screenshot.

## How to Ask for Help Alt Texting

We understand that there can be conflicting access needs when needing to alt text media. Our first preference is for you to wait and post the material when you are able to alt text it properly. If it is extremely urgent information that needs to be posted right away (e.g., emergency information, public health information, mutual aid, etc.), then please hashtag it with #AltTextHelp, and hopefully someone in the community will help. 

## Mastodon Alt Text Bots

There are two alt text reminder bots on Mastodon that you can follow and have remind you if you forget to alt text. Their handles are: @alt_text@mastodon.social (images only) and @PleaseCaption@botsin.space (images and videos).

## Resources

This [resource](https://poet.diagramcenter.org/how.html) is one of the best I have found for learning how to alt text different types of images. For each type of image, it gives you the general guidelines, a way to practice describing if you want, and what the alt text might look like for that type of image. 

I know alt text can be overwhelming to learn at first. But practice makes perfect, and there are lots of people out there who are willing to help you refine your skills!



