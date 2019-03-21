## Easy-to-follow beginner's guide to DeDRMing Amazon trial and purchased ebooks
![](https://raw.githubusercontent.com/aaronthecodpro/Reddit-Privacy-Megathread/master/data/redditprivacy.png)
First off, I would like to thank i<3cabbage and The Dark Reverser, because the standalone deDRM scripts are credited to them by the creator of the particular plugin I am using. Second, I would like to thank /u/amosqu. He has introduced us all to new tools and has done a great job of explaining how to use them, but I will take this a step farther - I will do a step-by-step installation and setup guide for you that includes links to all the relevant tools(the tools, not illegal content itself) in a way that you should be able to understand even if you are a beginner.

For starters, I will describe to you the type of books you can deDRM. The categories include purchased and trial versions of amazon books. This does not include rentals.

The required tools:

Calibre

Calibre is an ebook management tool that is used form conversion of ebooks in various formats to other formats. It can open most files, but is slow when compared to programs such as Adobe Digital Editions when trying to open .epub books to read.

http://calibre-ebook.com/download_windows

The current version should work, however, I am using the old version of Calibre 2.21. If You follow these steps to the point and it does not work for you, consider uninstalling calibre and installing an older version.

Kindle for PC

Kindle for PC is Amazon's official kindle book reader for PC. It allows you to read books downloaded from Amazon's store that are in the .azw4 format. You will need it to download the books that you wish to deDRM.

http://www.amazon.com/gp/kindle/pc/download

DeDRM plugin

This plugin allows your version of calibre to deDRM amazon's .azw4 files. For that reason, it is not allowed in calibre's official plugin download tool. You must download this .zip file and use calibre to load the plugin from it. This particular download is pre-modified, meaning that you do not have to edit any code for this plugin to function. Note: unzipping the tool does nothing for you. It is my suggestion that you leave it as is.

http://www.mediafire.com/download/eepjc4w8h9a8kyx/DeDRM_plugin.zip

Steps

    Download and install calibre and Kindle for PC on your device.

    Login or create an account on Amazon.com. I would suggest that this not be your personal account that you use to buy things with normally.

    Log in to the same account on your Kindle for PC app.

    Pick the book that you want to strip the DRM from. Select the "try free" or "7-Day Trial" button, whichever you see. Click the pulldown menu, and select "Yourname's Kindle For PC" as the device. If your device does not appear, I would suggest reviewing this: http://www.amazon.com/gp/help/customer/display.html?nodeId=201216000. I often find that I am not logged in the same account on both the web browser and the PC, and this results in the issue.

    Allow the amazon application to be launched. On my chrome browser, I am given a prompt in which I click "Launch application."

    Make sure your book is downloaded. This can be found by opening the Kindle app and clicking the "downloaded" section. If your book is in this section, and displays a red bar with white text saying "x days left of trial," then the book is downloaded. If it does not appear, it may be likely that you sent it to the wrong device. In this situation, you would have to make a new account entirely to access the trial again, as Amazon only seems to like allowing one device to have the trial.

    Open calibre. Ignore any welcoming stuff it may have for you, as it's unnecessary to learn about the program at this point.

    Click on the double arrows that appear next to "Remove books." Depending on your screen size, they may be placed differently or may not exist at all.

    Click the preferences icon that has 3 gears.

    Scroll down and click the green puzzle piece icon labelled "plugins."

    Click the yellow puzzle piece icon that says "get new plugins."

    Click on the kindleunpack plugin, and click install. Give it confirmation on anything it prompts you with. Also, if it asks you, have it loaded onto the navigation/favorites/plugin bar.

    Download the DeDRM plugin I linked you to if you haven't already.

    Click the bottom right option on the plugins screen in calibre that you should still be on that is labelled "Load Plugin from file." Confirm and accept any warnings it gives, and point it to the .zip file I had you download.

    Once it is installed, close calibre, and then open it again.

    Open your windows explorer, and go to /documents/mykindlecontent

    If you correctly downloaded the book, the .azw4 file should be here. The name will be random and alphanumeric, and as far as I know, starting with the letter B.

    Go to calibre. Copy the .azw4 from the folder to calibre.

Congratulations! You've deDRM'd an Amazon trial book.

But you're not done yet.

19. Click the book you just imported so it is highlighted in blue.

20. Click the arrows in the top right corner(as you did previously) and there should be a new icon, shaped like a triangle with rounded edges, and labelled "Kindle Unpack."

21. Click the icon. If your book was successfully deDRM'd, there will be a green unlocked selection. If the deDRM was unsuccessful, it will be red. If it is red, figure out what you did wrong or repeat the above steps for success.

21. Click the green unlocked icon and click "extract pdf." The .azw4 will then be converted to .PDF.

22. Right click the book you just converted in calibre, and click "open containing folder". This is the location of your PDF.

Final words:

Please do your best to share the file you make. If you remember how hard it was to find the book on torrent sites, and how people helped you out, consider making a torrent of the book.

This is not a request thread. I am deDRMing trial books from amazon up until 9/19/2015, and you may message me with the amazon link up until the 19th and I will send you a link with a PDF by the 19th of September. Do not post "can you please help me find --------- by --------?"

The most complete guide to finding ebooks is here

https://www.reddit.com/r/Piracy/comments/3i9y7n/guide_for_finding_textbooks/

The old thread by /u/ManWithoutModem contains many sites that are no longer functional, so this is the best option.

I am not an expert. I have perfected a process for myslef that has worked on multiple machines, and have shared that with you so that it may help. Everyone's circumstances are different. If you can't get this program to work, feel free to comment here and I will try to help you as best I can, but I make no promises.