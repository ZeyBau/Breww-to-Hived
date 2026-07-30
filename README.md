# Breww-to-Hived
A tool to match customer invoices and orders.

# Important note: Python 3.11 or newer is required. No extra packages are needed.
https://www.python.org/downloads/

Just download this, the script requires you to have python.
- open the installer
- read the prompts and type "y" and press enter
- do this until python is installed

# Download the "Breww_to_Hived_v1.2.zip" folder
1. **Extract** the whole ZIP into a normal folder.
2. **Keep all files together.**
3. Double-click RUN_TOOL_WINDOWS.bat.
4. Select the two current-day Breww CSV exports.
5. Choose the date and output location.
6. Click Process today's orders.
7. Upload the generated ***_upload.csv** file to Hived.
8. Review ***_manual_processing.csv** before printing.

# After downloading and extracting - read the "README" and "START_HERE" files inside the folder
These will explain how the app works and how to use it

**If you are still confused, contact Zey**

# Adding new flavours
The zip folder contains a file called 'settings' or 'settings.json'
This is a .json file that contains the "rules" of the script. i.e. what are the flavours we sell and how do we shorten them?
**When we start doing a new flavour - this file must be ammended** otherwise the script will not recognise the flavour

For example: we are going to start doing Watermelon as the new flavour
- we must ammend the "settings" file

**How do we do this?**

We open the "settings.json" file
- this contains lines for the different flavours such as:
  
      {"name": "Elderflower", "code": "E", "priority": 2, "aliases": ["Elderflower"]},
  
- we look at the final line of this text, which should be the Turmeric line
- add a comma to the end of this line
- then below it paste this exact line
  
      {"name": "NAME", "code": "CODE", "priority": 8, "aliases": ["ALIAS"]}
  
- make sure this is in line with all the other text
- **then, we are going to fill in all the sections that are in BLOCK CAPITALS**
- so for watermelon, we replace **"NAME"** with **"Watermelon"** or however it appears on the Breww orders
- we replace **"CODE"** with **"W"** or however you want to shorten watermelon
- we replace **"Alias"** with **"Watermelon"** or however it may be otherwise called e.g. for blood orange, sometimes it is referred to simply as "**Blood Orange"** and other times it is called **"Carmelo's Blood Orange"**, **this is also case sensitive**
- after replacing those three fields **SAVE THE FILE**
- then you should be able to run the app.

  # If anything goes wrong and you cannot fix it, please grab Zey
  

