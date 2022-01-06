# Chapter 3 - Customizing your bot

Welcome to Chapter 3! 
This is where we are going to teach you on how to customise your bot to your liking.
Here is the available options we can customize.

  - The Welcome Message itself
  - The Bot Status
  - The Bot Prescence (mobile, pc etc)
  - Console Startup

We will walk through these individually.

# Welcome Message Customization

To start of with please open the folder from which your bot is stored in using your preffered code editor.
Locate this part of the code:

![image](https://user-images.githubusercontent.com/79745507/148354799-87fbf19a-1335-4c99-9953-917b6e366536.png)

Once doing so there is many options you can change:

  - Colour/Color
  - Description
  - Title 
  - Content
  - Image and/or thumbnails

Before we move onto any of these, an important note.
If you want to input data into a quotation marks field, do not do that.
Use back ticks/ tildas and then you can use **${data}** to input the data into a string, integer etc.

# Colour/Color

To change the colour/color of a embed, a lot of the time you can just type out the word in full capital letters like **BLURPLE** or **GREEN**, but in the case where that will not work you can use a [hex colour/color finder/editor](https://www.color-hex.com) to find the color then put the hex code in instead.
The message before you edit it uses **YELLOW** which is a perfect example linking back to the logic named Colours/Colors. But if you did not want to use the logical named colours/colors you could of put **#ffff00** for yellow instead.
To change the colour/color please input either a logical colour/color name or use Hex Code and put it within these quotation marks:

![image](https://user-images.githubusercontent.com/79745507/148355392-1e6657ac-cb9e-4f47-b883-d4b28344ef14.png)

# Description

To change the description of an embed, it is literally as simple as replacing the text in the quotation marks to whatever you want. However there is a catch, If you have a user cache named **user** within reach you can do **user.toString()** and it will put a mention in your embed. Note: If you want to mention someone in an embed it will not work. Also another thing, if you want to create a new line type **\n** and a new line will be formed for the text after **\n**.
To input one of these, please change the data inside the back ticks/ tildas. As mentioned before, we are using back ticks and tildas in this one because we are getting data and putting it into the embed.

![image](https://user-images.githubusercontent.com/79745507/148355986-f55f515d-ed55-44d1-9beb-6e935451b952.png)

# Title

This one is pretty much the same as the Description however the text will always be bold on the Title and that cannot be changed. Also, we do not reccommend inputting data into the title since mentions and other data wont appear correctly.
To change the data in the Title please change the data inside the quotation marks:

![image](https://user-images.githubusercontent.com/79745507/148356148-ee1f771d-8164-4a94-984b-13e7884e6a22.png)

# Content

Content is something many of you might not be aware of. Did you know you could send messages (non-embed) with an embed message. This is mostly done so people can send mentions like @everyone and @here and it will actually work compared to it being in an embed.
To change or even create one varies heavily. But if you follow our way of creating a message which will be an image below, it is quite easy.
To add a content to our embeds the way we did it (if its not there) is like this:

![image](https://user-images.githubusercontent.com/79745507/148356502-9dcf5921-3655-4942-83dc-b54207787d77.png)

There are two important things you need to remember to add a content to any of our embeds, **"content"** and **,**.
**"content"** defines what this data is and where is meant to go so its vital.
**,** is not needed unless you have more than just the content, in the welcome message we do, hence we added a **,** to the end of our messaage above.

# Images and/or thumbnails

This can be simple depending on what way you do it, you can store it locally in a folder (in this case we are calling it assets) and then reference it in your **.setImage** or **.setThumbnail** but we do not reccomend that. We reccommend just simply putting a url to a image on there since it is simpler and does not waste storage.
This can be achieved in two ways:

![image](https://user-images.githubusercontent.com/79745507/148357045-f2949272-140b-44ce-b5f3-339e64eb9009.png)

#

That is all for this chapter!

# Next Chapter: [Click Me](https://github.com/PS-XYZ-Developement/Directory/blob/main/Stripped%20Down%20Bot%20Tutorials/Welcome%20Bot/Chapters/Chapter4.md)

Made for the purpose of [PS.XYZ](https://platservices.xyz).

If you run into issues not described here, email us at support@platservices.xyz.
