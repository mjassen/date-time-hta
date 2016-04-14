# date-time-hta
An HTA application (HTML + VBScript + JavaScript) That presents the current date+time - good for getting a timestamp for copying + pasting

## Purpose of the script:
When working on Windows environment, I often want to be able to paste a Date + time representing the current date + time, in different formats. 
For example I want a YYYYMMDD_HHMM timestamp to be able to paste it as the name of a new folder that I'm creating. Or I want a Timestamp of the format of YYYY-MM-DD HH:MM to paste it into a text file in which i'm making a note.
But there's not a keyboard shortcut on Windows that does what I want. 
So I make this .hta file which can be launched from one's desktop, which immediately presents the timestamps in the format that I want.

## Instructions:
Save the date_time.hta file as an .hta file (text file with file extension of .hta).
Put the .hta file on one's Windows Desktop. 
Now whenever one double-clicks / launches the .hta file, it will open a browser window with the current date+time in three different formats handy for copying +pasting.

##Timestamp formats supported:
Upon first publish, this script supports these formats:
YYYY-MM-DD HH:MM
YYYYMMDD_HHMM
YYYYMMDD_HHMMSS
