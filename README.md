# Facebook Messenger Search Tool
### A simple tool for counting words or phrases within your Facebook Messenger data.
Ever wondered how many times a specific word or phrase was used in a Facebook chat? This is the tool for you.

This is an easily modifiable tool that should come in handy as a solid starting point for more intricate scripts. This was a quick and dirty project to see how many messages my friends and I have sent over the last 11 years. We've had a fairly active groupchat -- the total was just over 360,000 messages! The script went through 2.3M lines of JSON in 32 files in less than a third of a second.

# What you'll need + Usage:
* A working Python 3 installation.
* Download your Facebook Messenger data. You can learn more about that [here](https://www.facebook.com/help/212802592074644). Note that it will take some time before it's availible for download, usually a few hours.
* Navigate to the chat you wish to search in and take note of the number of "message_X.json" files that are present. Remember that number!
* Paste this script in that location.
* Open the script and change the magic_string variable to your search value. Make sure it's lowercase as this script will search for all cases of a string.
* Change the number at the specfied location to the total number of message files you have inside the folder.
* Open a command prompt inside the folder and run the script: ``` python ./message_search.py ```

## Limitations
* You can only search one chat at a time.
* Script must run in the same folder as the chat.
* All cases of a string are searched, but this can be easily fixed.
    * Details on this will follow.
* Not fully automated: you still have to 'edit' the script to use it.

Questions? Email me [here](mailto:82dannyalvarez@gmail.com)
