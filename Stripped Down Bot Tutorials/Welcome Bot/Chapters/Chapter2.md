# Chapter 2 - De-cluttering your stripped down bot

Welcome to Chapter 1!
This is where we will teach you how to get rid of those startup inputs for your token, guild id, client id and welcome channel.

# Step 1: Open your text editor of choice

Once you have opened your text editor of choice, please open up the folder where you have stored your Welcome Bot.

# Step 2: Find the section where we input our data

Look for this selection of code from your **index.js** file.

![image](https://user-images.githubusercontent.com/79745507/147964788-d29c48a2-ac97-49bc-a95c-1966c074fefc.png)

# Step 3: Edit your selection of code

This is the only bit of coding required.

**1.** Where it says **const token =**, you would want to proceed to remove everything past **=**. 
       After the **=**, you would want to put one space then in quotation marks paste your bot token from the Developer Portal. 
       Like so:

   ![image](https://user-images.githubusercontent.com/79745507/147965038-c4ae7b58-78f0-4eed-800a-18b368db03a5.png)

**2.** Where it says **const clientid =**, you would want to proceed to remove everything past **=**.
       After the **=**, you would want to put once space then in quotation marks paste your client id from the OAuth2 page of your bot.
       Like so:

![image](https://user-images.githubusercontent.com/79745507/147979781-868e3925-7d11-4945-a1f0-569212b4baf1.png)

**3.** Where it says **const guildid =**, you would want to proceed to remove everything past **=**.
       After the **=**, you would want to put one space then in quotation marks paste your guild/server id from which the bot will be running in.
       Like so: 

![image](https://user-images.githubusercontent.com/79745507/147980003-beeb5ad5-5698-42c9-80f1-c7a4853f796a.png)

**4** Where it says  **const welcomechanneld =**, you would want to proceed to remove everything past **=**.
      After the **=**, you would want to put one space then in quotation makrs paste your welcome channel id from which the welcome message will be sent.
      Like so:

![image](https://user-images.githubusercontent.com/79745507/147980303-99f7b9cf-c171-444b-9671-11095688dfca.png)

# Step 4: Testing

The bot should not be able to ask for the data and should startup without any issues.
If it starts up and crashes, this means one of the following:

       - You have inputted one of the ids incorrectly from Step 3
       - You havent saved your file

That is all for this chapter!

# Next Chapter: [Click Me](https://github.com/PS-XYZ-Developement/Directory/blob/main/Stripped%20Down%20Bot%20Tutorials/Welcome%20Bot/Chapters/Chapter3.md)
   
Made for the purpose of [PS.XYZ](https://platservices.xyz).

If you run into issues not described here, email us at support@platservices.xyz.
