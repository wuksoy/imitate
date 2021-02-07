# Imitate
 Imitate is a small personal project where I try to imitate my friends text messaging patterns using an ai. This was made possible due to the relatively huge amount of text messages that has been sent among us within a span of almost 7 years. I would also like to clarify that I pulled all the messages and started this project with their consent, not sure if that matters or not but I thought it had to be said

 ## Part 01: Messages and Text Cleaning
 This part involve collecting text messages of the group of people you would want to imitate, and then processing and cleaning the data. Most of the popular messaging apps have a feature where you are able to export a record of all messages sent within the group. In my case I have collected messages from WhatsApp and Telegram and will go through how to clean and process these two very different forms of outputs.

 ### current issues
    I have written a very rough start to cleaning the text messages. These are some of the issues that need to be resolved in this data cleaning process.
     - current group has multiple references to the same person. Need a way to combine all of these names under one name for each person.
     > For example in my case Person A is referred to as Person A in first half of text file, until his phone number changed and he was added to group as a new user.
     - current text file has users messages on multiple lines. Need a way to bring all of their consecutive texts onto one line.