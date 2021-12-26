# Facebook Messenger Search Tool
### A simple tool for counting words within your Facebook Messenger data.
Ever wondered how many times a spcific word or phrase was used in a Facebook chat? This is the tool for you.

This is a quick and dirty project to see how many messages my friends and I have sent over the last 11 years. We've had a fairly active groupchat -- the total was just over 360,000 messages!

# What you'll need:
* Download your Facebook Messenger data. You can learn more about that [here](https://www.facebook.com/help/212802592074644). Note that it will take some time, usually a few hours.
* Navigate to the chat you wish to search in and take note of the number of "message_x.json" files that are present. Remember that number!
* Paste this script in that location.
* Change the magic_string variable to your search value. Make sure it's lowercase as this script will search for all cases of a string.
* Change the number at the specfied location to the total number of message files you have inside the folder.

## Limitations
* You can only search one chat at a time.
* Script must run in the same folder as the chat.
* All cases of a string are searched, but this can be easily fixed.
    * Details on this will follow.
* Not fully automated: you still have to 'edit' the script to use it.
