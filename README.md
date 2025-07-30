More about github pages can be found here: https://pages.github.com/

Please note, I am figuring this out mostly as I go, but I want others to have the same opportunity of having a free podcast!

# About

This is a GitHub Pages Template used for supporting a podcast.
This idea and the base code came from ChatGPT, but has been edited to actually work.
Further files have been added as examples on how to use this template.

This is intended to be used with The Internet Archive (https://archive.org/)

You can find an active version of one GitHub Pages made with this [here](https://rambling-bramble-blog.github.io/podcast/).

<hr>

# Using the Internet Archive

1. Create an account on archive.org (Found in upper-right corner).

<img width="673" height="782" alt="New Account Sign Up" src="https://github.com/user-attachments/assets/bbb0fff5-da0c-4c20-b91a-5b4926e077a2" />

2. Click "Upload" (Also in upper-right corner).

2a. Select "Upload" (It is unlikely you will be uploading to the Live Music Archive, but feel free to hit the info icon if you are unsure).

<img width="562" height="298" alt="First Upload Page" src="https://github.com/user-attachments/assets/6e8e55d8-0daa-450d-b4f2-9ae133bbaa1d" />

2b. Drag and Drop you **MP3** files. Make sure the file name has **NO SPACES**. Use hyphens ( - ) or underscores ( _ ) instead.

<img width="354" height="150" alt="Second Upload Page with Drag & Drop" src="https://github.com/user-attachments/assets/a31aa6a8-29b9-4e7b-99c6-dc677fe2572e" />

3. Complete the Upload Process! ( More Details in screen shot and typed out below).

<img width="1020" height="796" alt="Upload Process" src="https://github.com/user-attachments/assets/0e3334de-cbec-4910-a0a4-54a47e4e9b9e" />

## Internet Archive Upload Process in more detail

<img width="1020" height="796" alt="Upload Process" src="https://github.com/user-attachments/assets/0e3334de-cbec-4910-a0a4-54a47e4e9b9e" />

1. Page Title (Your Podcast Title/Name)
2. Page URL (your-podcast-name-with-hyphens_or_underscores)
3. Description (Describe your podcast)
4. Subject Tags (podcast, podcast episodes, YOUR PODCAST NAME, YOUR CREATOR NAME, etc...) (This is all up to you! It appears as "Topics" on your Internet Archive "Item Page")
5. Creator (Not required, but you can use your PEN NAME or your REAL NAME)
6. Date (Not required, but you can use the current date)
7. Collection (“Community Audio” — Unlikely to be another option, but feel free to look at the drop down)
8. Test Item (“No” — Unless you want to create a trial item. Test items are deleted after 30 days)
9. Language (Main Language of the Material: i.e. "English")
10. License ( I suggest CC and Prohibit Commercial Use: CC-BY-ND-NC) (https://creativecommons.org/licenses/by-nc-nd/4.0/) 

<img width="511" height="263" alt="CC By ND NC Licensing" src="https://github.com/user-attachments/assets/125150ff-cfbc-414a-9c7e-e1c907411e44" />

11. More Options (I put nothing here, but use it if you like!)

<hr>

# Using This Template

Create a new repository from the template (note: do not "Fork").

Files in need of edits:
- everything in /_episodes
- /assets/logo.jpeg (If you change the file name or type from "logo.jpeg" you will need to make furthere edits to "".)
- _config.yml (This is where most of your information will go).
- feed.xml (iTunes Categories Only : https://podcasters.apple.com/support/1691-apple-podcasts-categories )
- index.md (This is your main page!)
- LICENSE.md (Add your specific information, but keep in mind what the audio file may be licensed under--especially if using the InternetArchive for file hosting.)


## Editing Your Episode Files

1. Change "title" to your episode title.
2. Change "date" to your release date (i.e. current date) 
3. "audio_url" should be the link you the specific episode's MP3 file on the Internet Archive.
<img width="1151" height="395" alt="Which file?" src="https://github.com/user-attachments/assets/5f1efb79-24ef-41fe-8e3a-853b7568efc2" />
  a. You will need to copy the link address for the MP3 file (right click to copy) (I recommend an internet search if you do not know how to get the right-click menu up for your specific device)
<img width="1164" height="597" alt="Copy Link Address" src="https://github.com/user-attachments/assets/6bf02fe9-898c-4502-8d19-4d57325cf73d" />
  b. Paste the copied link between the double quotation marks ("").
6. "audio_size" is your file size converted to **binary** bytes (for MB to bytes: mutiple your file size by 1048576 and round to the nearest whole number) (<a href="https://www.gigacalculator.com/converters/convert-mb-to-bytes.php#table">a conversion chart</a>) 
7. "duration" is the length of your episode in minutes and seconds.
8. The "body" of the page (everything after the second "---"): Put whatever you want here and it will appear as your episode description. Keep in mind, the syling (html and md) will be removed on the streaming platforms, so extra spaces (" ") or pipes/vertical bars and spaces (" | ") work well to create separation. (I chose to use extra spaces.)

<hr>

# Submitting your Podcasts!

Conduct an internet search for "Podcast Databases" and select the ones you wish to submit to.

Your RSS feed link is the "feed.xml" file. Right click to copy the file address.

Here are a few options for places to submit your podcast (I suggest reading the Terms, as I am not vetting these for you):
1. <a href="https://podcasters.apple.com/">Apple Podcasts</a>
2. <a href="https://pocketcasts.com/submit/">Pocket Casts</a>
3. <a href="https://podcastindex.org/add">Podcast Index</a>
4. <a href="https://podcasters.amazon.com/">Amazon Music</a>
5. <a href="https://www.simplecast.com/pandora">Pandora, Stitcher, & SiriusXM via SimpleCast</a>
6. <a href="https://podcasters.iheart.com/">iHeart Radio</a>

<hr>

# I hope you enjoy!

If you have any questions, comments, or concerns about the Podcast Template for GitHub Pages: please contact rambling.bramble.blog@gmail.com or comment/message me via GitHub (I will be slow to respond, but will respond...eventually).
