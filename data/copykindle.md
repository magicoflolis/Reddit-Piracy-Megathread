## Guide to Copy Kindle Content to PDF using Calibre
![](https://raw.githubusercontent.com/aaronthecodpro/Reddit-Privacy-Megathread/master/data/redditprivacy.png)
I've re-posted this thread because the old one has now become archived preventing new comments. If you want to read the comments on the old post you can read it here

This link is an additional resource for DeDRM tools in case you are having issues: https://apprenticealf.wordpress.com/ Additionally Apprentice Alf’s tool removes the unique user ID in ebooks (Header 208)
LAST UPDATE:

August 3rd, 2018

 

 

Below is a reworked guide I made based on the other reddit post titled: ["[Updated Tools] Easy to follow beginner's guide for DeDRMing amazon trial, rental, and purchased eBooks"] (https://www.reddit.com/r/Piracy/comments/4bvsnz/updated_tools_easy_to_follow_beginners_guide_for/ "Original Reddit Guide"); which was written by [coralrabbit] (https://www.reddit.com/user/coralrabbit). Hopefully this will help some of you out there. Especially with the new school semesters starting and the high cost of school books these days.

 

Don't get put off or intimidated by all the steps. I made it a lot of steps so I could be as specific as possible to reduce any chance of a mistake. I wrote this as though I was explaining it to a 5 year old and do not assume any of you should know how to do any of this. I check my reddit mail often so if you have a question please leave a comment!

 

You can view the original reddit thread here: https://www.reddit.com/r/Piracy/comments/4bvsnz/updated_tools_easy_to_follow_beginners_guide_for/

 

*I have updated some of the steps to reflect the changes (such as icon appearances) in the most recent version of [Calibre v2.82] (http://calibre-ebook.com/download_windows).

 

 

            Guide to Copy, Convert and Save Kindle Content to PDF using Calibre


         Easy-to-Follow Beginner's Guide to DeDRMing Amazon Trial and Purchased eBooks.

 

For starters, I will describe to you the type of books you can DeDRM (remove blocking restrictions). The categories include:

    Purchased Versions

    Trial Versions might not be all pages

    Rental Books in most versions

 

This method works best with .azw4 file types.

 

 

                                     The Required Tools:

 
Calibre

[http://calibre-ebook.com/download_windows] (http://calibre-ebook.com/download_windows "NEWEST Version of Calibre")

*version 2.21 [here] (https://download.calibre-ebook.com/2.21.0/ "Calibre Version 2.21 Download Link") *

Calibre is an eBook management tool that is used for the conversion of eBooks in various formats to other formats. It can open most files, but is slow when compared to programs such as Adobe Digital Editions when trying to open .epub books to read. The current version should work, however, I am using the older version of Calibre 2.21. If You follow these steps to the point and it does not work for you, consider uninstalling Calibre and installing the older version.

 
Kindle for PC

http://www.amazon.com/gp/kindle/pc/download

*Kindle for PC v1.17 [here] (http://filehippo.com/download_kindle_for_pc/69970/) *

Kindle for PC is Amazon's official kindle book reader for PC. It allows you to read books downloaded from Amazon's store that are in the .azw4 format. You will need it to download the books that you wish to DeDRM.

IMPORTANT! I've been PMed by other users that Kindle for PC 1.17 is the LAST version that still downloads .azw4 files (the files that Calibre uses best). If you are having issues get that version (link above) or an OLDER version.

 
DeDRM Plugin [NEW]

http://www.mediafire.com/download/3y3r9z2bk8c71t1/DeDRM_plugin.zi

This plugin allows your version of Calibre to DeDRM Amazon's .azw4 files. For that reason, it is not allowed in Calibre's official plugin download tool. You must download this .zip file and use Calibre to load the plugin from it. This particular download is pre-modified, meaning that you do not have to edit any code for this plugin to function. Note: unzipping the tool does nothing for you. It is my suggestion that you leave it as is.

 
Additionally You Will Also Need:

    [Amazon Account] (https://www.amazon.com/ap/register%3F_encoding%3DUTF8%26openid.assoc_handle%3Dusflex%26openid.claimed_id%3Dhttp%253A%252F%252Fspecs.openid.net%252Fauth%252F2.0%252Fidentifier_select%26openid.identity%3Dhttp%253A%252F%252Fspecs.openid.net%252Fauth%252F2.0%252Fidentifier_select%26openid.mode%3Dcheckid_setup%26openid.ns%3Dhttp%253A%252F%252Fspecs.openid.net%252Fauth%252F2.0%26openid.ns.pape%3Dhttp%253A%252F%252Fspecs.openid.net%252Fextensions%252Fpape%252F1.0%26openid.pape.max_auth_age%3D0%26openid.return_to%3Dhttps%253A%252F%252Fwww.amazon.com%252Fgp%252Fyourstore%252Fhome%253Fie%253DUTF8%2526ref_%253Dnav_custrec_newcust "Direct Link to Sign Up for Amazon") Either make a fake one or use a school email to receive free Amazon Prime

    Credit/Debit/Gift Card with the exception of trial versions you will purchasing/renting the books FIRST, then returning them for an IMMEDIATE REFUND after saving your converted copy

 

 

                                             Steps:

PART 1:
Setting Up Your Amazon Account, Kindle for PC and Calibre with DeDRM Plugin

Most of PART 1 you will only have to do ONCE. Every other time you can skip to PART 2

 

1)	Download and install Calibre and Kindle for PC on your device.

 

2)	Login or create an account on Amazon.com. I would suggest that this not be your personal account that you use to buy things with normally.

 

3)	Log in to the same account on your Kindle for PC app.

 

4)	Pick the book that you want to strip the DRM from.

 

5)	Select the "try free" or "7-Day Trial" button, whichever you see. If you can't get the full book free via Kindle then you can purchase the book and return it for a full (and instant) refund after you make your copy with Calibre.

 

6)	Click the pull down menu, and select "Your name's Kindle for PC" as the device. If your device does not appear, I would suggest reviewing this. I often find that I am not logged in the same account on both the web browser and the PC, and this results in the issue.

 

7)	Allow the Amazon application to be launched. On my chrome browser, I am given a prompt in which I click "Launch application."

 

8)	Make sure your book is downloaded. This can be found by opening the Kindle app and clicking the "downloaded" section. You might have to open it once in order for it to load. If your book is in this section, and displays a red bar with white text saying "x days left of trial," then the book is downloaded. If it does not appear, it may be likely that you sent it to the wrong device. In this situation, you would have to make a new account entirely to access the trial again, as Amazon only seems to like allowing one device to have the trial.

 

9)	Open Calibre. Ignore any welcoming stuff it may have for you, as it's unnecessary to learn about the program at this point.

 

10)	Click on the double arrows that appear next to "Remove Books". Depending on your screen size, they may be placed differently or may not exist at all.

 

11)	Click the preferences icon that has a crew and wrench icon. (You might have to scroll all the way to the right with the double arrows on the top right of the screen to see this)

 

12)	Scroll down and click the green puzzle piece icon labelled "Plugins".

 

13)	Click the yellow puzzle piece icon that says "Get New Plugins”.

 

14)	Click on the “Kindle Unpack” plugin, and click install.

 

15)	Give it confirmation on anything it prompts you with. If it asks you, have it loaded onto the navigation/favorites/plugin bar.

 

16)	Download the DeDRM plugin I linked you to if you haven't already.

 

17)	Once again access the preferences as in step 11. This time choose the option "Change Calibre Behavior".

 

18) Click on the green puzzle icon name "Plugins" in the bottom left under "Advanced"

 

19) On the bottom right of this next screen you'll see an option that says "Load plugin from file". Click that and browse to the DeDRM plugin.

 

20)	Confirm and accept any warnings it gives (don't worry about any virus warnings, this is hack tool after all).

 

21)	Once it is installed, close Calibre, and then open it again.

 

                                        DeDRMing Your eBook

PART 2:
DeDRMing and Converting to a Savable PDF

After you have successfully completed the initial program downloads and setup for the first time, you can just get any book from Amazon and SKIP PART 1

 

1)	Open your Windows Explorer, and go to /documents/mykindlecontent. If you correctly downloaded the book, the .azw4 file should be here. The name will be random and alphanumeric, and as far as I know, starting with the letter B.

 

2)	Go to Calibre. Copy the .azw4 from the folder to Calibre by dragging the file to the Calibre window.

 

3)	Congratulations! You've DeDRM'd an Amazon trial book. But you're not done yet...

 

4)	Click the book you just imported so it is highlighted in blue.

 

5)	Click the arrows in the top right corner (as you did previously) and there should be a new icon (shaped like a yellow triangle with rounded edges) labelled "Kindle Unpack". You might have to click the right arrow near all the icons to scroll to it. It is usually the last icon.

 

6)	Click the icon. If your book was successfully DeDRM'd, there will be a green unlocked selection. If the DeDRM was unsuccessful, it will be red. If it is red, figure out what you did wrong and/or repeat the above steps until successful.

 

7)	Click the green unlocked icon and click "extract pdf". The .azw4 will then be converted to .PDF.

 

8)	Right click the book you just converted in Calibre, and click "open containing folder". This is the location of your PDF.

 

9)	Once you have confirmed the pdf is working properly you can then go back to Amazon and refund the book. This will remove it from your Kindle library. Remember the CONVERTED book will always be in your Calibre library.

 

                                        Refunding Your Kindle Purchase 

How to Refund Your Money AFTER Downloading and Converting the Kindle Book

This section will explain how to get your money back so you are left with a PDF of the book without spending any money

 

1)	Once you have confirmed your conversion worked sign in to Amazon in your browser.

 

2)	On the top-right of the website click on the drop down list "Account & Lists"

 

3)	Under "Your Account" select "Your Content and Devices".

 

4)	You will see a list of any DIGITAL purchases you made. Next to the eBook click the check box. Under "Actions" click the ... box. This will open a small window where you can select the option "Return for Refund". I usually choose the refund reason as "wrong book" but it doesn't matter what reason you choose.

 

5)	Once this is clicked the eBook will be removed from you Kindle folder (don't worry your Calibre folder and files are not touched) and your money will be instantly refunded!

 

                                            FAQ

I will try to periodically update this as I notice common issues or questions arise

Please check the comments below in case anyone has already asked your question or provided additional information that might help :)

Feel Free to PM me if this post becomes archived

 

Q: I can't get .azw4 files and/or convert with Calibre

 

A: Another user PMed me stating that the NEWEST versions of Kindle for PC and Calibre are breaking capability with .azw4 files (the file type needed to DeDRM successfully). The solution to this is to download the OLDER version of Calibre (v2.21) and Kindle for PC (v1.17). Links for both of these are at the TOP of this guide.

If you already have the NEWER versions simply uninstall them then install the older ones. This guide was based on the older versions anyway.

 

 

Q: Does this work on Mac?

 

A: According to PM's I've received from other users they have been able to successfully use this on Mac OS as well as PC.

 

 

Q: My file is converting to something other than a PDF?!

 

A: People have been replying that some of their files have not converted to a PDF or at all. This is because .azw4 files (the file you get from amazon when you get a kindle book) are currently the only one guaranteed to convert to a PDF. An .azw4 file is nothing more then a PDF wrapped in a DRM protection. .azw3 files usually work however they tend to only convert to ePub files in which you'll need to convert those to a PDF. This is because they are nothing more then epub files wrapped in DRM protection.

To convert the formats of the file you can use the "Convert" tool within the Calibre program itself or find a free online ePub to PDF converter like this one here.

 

 

Q: Do I need to spend money for this?

 

A: Yes, but just until you refund it back when finished converting the book. Sometimes you can do this using the "7-day Trial" option. However BUYING the book always works. If you are buying the book you will need to use a credit/debit/gift card. You should have one on file anyway because you can't make an Amazon account without one.

If you complete the entire process from purchase to > converting to > refund in less then an hour you will not even be charged. The sale will still be pending and then will just get cancelled. If it takes longer or you choose a book that is only available from a Non-Amazon seller it could take a couple of days for the refund to process.

Make sure you have enough money on your card to TEMPORARILY cover the cost of the book. YOU CAN ALWAYS REFUND ANY EBOOK ON AMAZON! There is no way to screw this up! Either you convert it to a PDF or it doesn't work, either way Amazon always accepts the refund and deletes the eBook from your kindle folder.

As far as Amazon is concerned you just made a mistake and bought the wrong book. It's not a physical item and (as far as they know) you can't even read it without their Kindle; so they have no problem instantly removing it from your account and returning your money.

 

 

Q: All the books I'm downloading aren't converting at all!

 

A: There are a few possible reasons/solutions to this:

 

    It could be an issue with Calibre: try downloading the older version (v2.21) I posted in the top of the guide.

    It could be an issue with Kindle for PC: try downloading the older version (v1.17) I posted in the top of the guide. Then turn off auto updates in: tools > options > general

    Check if there is a newer version of the DeDRM plugin available. It's possible it has updated since I posted this.

    It could be some issue with the installation. To start fresh you can try uninstalling Kindle AND Calibre, then reinstalling and following the steps to set up the plugin again.

    Finally you might just be getting unlucky and the books you're choosing are indeed only available as .azw files and NOT available as .azw3 or .azw4 files.

To test this I would try to repurchase and download a Kindle book YOU KNOW worked for you in the past with this method. Here (<-- Click the link) is a cheap school book ($25 buy/ $12 rent) that is in a .azw4 format. I have tested it and it works. You can use this book as a test (remember to get a REFUND when you're done!).

 

If (after you download and convert it), the process works fine, then that might be evidence that you are just getting unlucky and choosing books that happen to ONLY BE AVAILABLE in the .azw format. IF IT DOES NOT WORK then it means you need to try one of the above solutions.

 

 

Q: When refunding the book I'm being asked to contact customer service. What should I do?

 

A: Several people have PMed me about this along with their outcome. This "extra" step seems to be a way to discourage people from refunding books either because they get "scared" or are too lazy to go forward with the refund process. However, each person who contacted me about this said they contacted customer service and gave them some excuse for why it needs to be refunded (i.e. wrong edition, wrong book, impulse buy, dropped the class, etc.) and EVERYONE has received their refund.

I'm sure for every 1 person who goes through the refund process, 10 more don't. Congratulations, the companies found another way to profit. You can even use different Amazon accounts for each purchase if you don't want to refund several books at once from one account (or say you dropped out of school and need to refund all your books). Don't get scared, they're nice on the phone and as soon as you give them ANY reason for a refund they'll refund it no questions asked. I've done this with other items from Amazon and it's always been a pleasant and seamless process.

 

 

Q: Is this illegal and/or could I get in any trouble or have my account suspended?

 

A: No, this is not illegal. You are buying the book. Then you are making a backup copy for yourself that has had the DRM protection removed so you can use an alternate viewer then Kindle to read it. That is the reason why this DeDRM technology was created. However, it IS illegal to try and sell those copies for profit. DON'T BE A DICK, DO NOT SELL YOUR COPIES!

To be extra safe, it is suggested in this guide (and I will reiterate it here) to MAKE A NEW AMAZON ACCOUNT. Do not use your primary Amazon account. You can but it is bad practice. I was contacted by 2 or 3 people who had their account suspended and they all had 1 thing in common: All of them got greedy and tried to download then return SEVERAL books at the same time. DON'T BE THAT GUY/GIRL! If you need several books either spread out your purchase and returns over several days OR make additional Amazon accounts and use each one to only purchase/return 1-2 books. You can have as many accounts as you want, they just need to be linked to different email address.