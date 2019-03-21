## [GUIDE] How to "rent" your textbooks for free from Amazon using DeDRM Tools & Kindle Unpack
![](https://raw.githubusercontent.com/aaronthecodpro/Reddit-Privacy-Megathread/master/data/redditprivacy.png)
Guide

Going to college? Living off top ramen for dinner? Let me show you have to "rent" your textbooks for free & for life!

For this example, we will use this book. If you have found another book that is eligible to rent for free, feel free to try it with that one. http://smile.amazon.com/dp/B00HQO05X0/ref=mt_kindle

Download the Kindle for PC application, and send your book there. http://smile.amazon.com/gp/kindle/pc/download

Prerequisites:

    Download Python 2.7 (ActivePython is the best version) https://www.activestate.com/activepython/downloads

    Download Notepad++ (possibly the best text editor out there, however you're free to use whatever you have on your computer) https://notepad-plus-plus.org/download/

    Download & Extract the latest DeDRM package (6.3.4 at time of writing) https://github.com/apprenticeharper/DeDRM_tools/releases/tag/v6.3.4

You have a few options at this point. You can use the standalone Windows application or use the Calibre Plugin. Your choice.

Standalone:

    Navigate to DeDRM_App\DeDRM_lib\lib\ then find and edit the mobidedrm.py file

    At time of writing, somewhere around the line 440 is where you will need to comment out (using # at beginning of the line) or delete the following code:

     if val406 != 0:
     raise DrmException(u"Cannot decode library or rented ebooks.")

    Save the file, and find eDRM_Drop_Target.bat within the DeDRM_App folder

    Now find your Kindle eBook within the My Kindle Content folder with your Documents folder. Drag and drop your .azw4 file on the batch script. It will begin to process.

    Congrats! You're now DRM free! Look in the folder where your .azw4 is (in this example, within My Kindle Content) to find a companion file with "_nodrm" at the end of the file name

https://www.reddit.com/r/Piracy/comments/3kv9k6/easytofollow_beginners_guide_to_dedrming_amazon/

Now that you have a deDRM Kindle ebook, you're thinking of converting it with Calibre to PDF right?

STOP! DON'T RUIN YOUR NEW EBOOK!!

Download Kindle Unpack, this will preserve ALL formatting and graphics within the ebook. AZW4 files are simply PDFs with DRM after-all, so there's no reason to convert!

https://github.com/kevinhendricks/KindleUnpack/archive/master.zip

    Unzip the KindleUnpack-master.zip file

    Run KindleUnpack.pyc from the KindleUnpack folder

    Browse for your nodrm version of the Kindle eBook, then create a new output directory (trust me, this will unpack a lot of useless files you will soon delete

    Start the unpacking process. You will then have a folder full of tons of files. Within that folder is a .PDF

Congrats! You now have within your possession a high quality PDF you can take anywhere, anytime, forever!

If instead standalone apps aren't your thing, or you already use Calibre, here's a guide to get started with the help of molotoviphone from his guide: http://www.reddit.com/r/Piracy/comments/3kv9k6/easytofollow_beginners_guide_to_dedrming_amazon/

Calibre:

    Navigate to DeDRM_calibre_plugin and extract DeDRM_plugin.zip

    Inside the directory with the extracted files, find and edit the mobidedrm.py file

    At time of writing, somewhere around the line 440 is where you will need to comment out (using # at beginning of the line) or delete the following code:

     if val406 != 0:
     raise DrmException(u"Cannot decode library or rented ebooks.")

    Save the file, and create a new zip archive of the entire contents of this folder

    In Calibre, go to Preferences (by clicking the arrow on the right), Plugins, and Load Plugin from File. Find the new zip you made and select Open. Then select Yes. While you're there, install the latest KindleUnpack plugin (0.81.2 at time of writing) https://github.com/dougmassay/kindleunpack-calibre-plugin/releases/download/v0.81.2/kindle_unpack_v0812_plugin.zip

    Now find your Kindle eBook within the My Kindle Content folder with your Documents folder. Drag and drop your .azw4 file into Calibre. It will begin to process.

    Congrats! You're now DRM free! Look in the folder where your Calibre Library is (in this example, within my Documents folder). Drill down the folder paths till you find the Kindle Book.

    Now find KindleUnpack within Calibre, located in the toolbar menu by clicking the same small arrow on the right where you found Preferences.

    Select the Extract PDF option. Then right click the ebook in Calibre and click "open containing folder". This is the location of your newly created deDRM'd PDF!