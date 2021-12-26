# Facebook Messenger Search Tool
### A simple tool for searching through your downloaded Facebook Messenger data.

# What you'll need:
* Download your Facebook Messenger data. You can learn more about that [here](https://www.facebook.com/help/212802592074644). Note that it will take some time, usually a few hours.
* Navigate to the chat you wish to search in and take note of the number of "message_x.json" files that are present. Remember that number!
* Paste this script in that location.
* Change the magic_string variable to your search value. Make sure it's lowercase.
* Change the number at the specfied location to the total number of message files you have inside the folder.

## Limitations
* You can only search one chat at a time.
* Script must run in the same folder as the chat.
* All cases of a string are searched, but this can be easily fixed.
    * Details on this will follow.
