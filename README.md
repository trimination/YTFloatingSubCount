# YTFloatingSubCount
Floating Subscription Count for YouTube Streamers

# Usage

You will require your channel ID from YouTube, this is the part that comes after `/channel/` in the URL, 
it can either be a random string or a specified channel name. For example, the channel name for Shroud is:

https://www.youtube.com/channel/**UCoz3Kpu5lv-ALhR4h9bDvcw**

You will require a YouTube Data API KEY as detailed here: https://developers.google.com/youtube/v3/getting-started

Why?
YouTube **limit API requests to 10k requests per day, so I can't give you one. Easy to make, do not share.**

You will require YouTube Data API access for your given key, again detailed in the above URL.

Run the Executable JAR file by double-clicking on it; A dialog should appear in the top right of your display. 
Right-click the dialog to access the settings and input your API KEY, Channel ID and Tick Rate. The **Tick rate** is 
expected in milliseconds so 5000 would be a rate of 1 update every 5 seconds. 

**Your API KEY is limited to 10k requests per day which is why you must use your own, it's free, but there are limits. 
If you stream for a solid 24 hours, your maximum refresh rate should be 8640 to prevent exceeding the quota set by Google.**

# Compilation

`javac YTFloatingSubCount/*.java`

# Execution

`java YTFloatingSubCount/YTFloatingSubCount`

# Packaging

`jar cvfe YTFloatingSubCount.jar YTFloatingSubCount.YTFloatingSubCount YTFloatingSubCount/*.class`

Feel free to modify, adapt, overcome or whatever, attribution preferred.