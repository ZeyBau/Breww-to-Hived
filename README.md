# Breww-to-Hived
A tool to match customer invoices and orders.

# Download the zip folder above
1. **Extract** the whole ZIP into a normal folder.
2. **Keep all files together.**
3. Double-click RUN_TOOL_WINDOWS.bat.
4. Select the two current-day Breww CSV exports.
5. Choose the date and output location.
6. Click Process today's orders.
7. Upload the generated ***_upload.csv** file to Hived.
8. Review ***_manual_processing.csv** before printing.

# Important note: Python 3.11 or newer is required. No extra packages are needed.
https://www.python.org/downloads/

Just download this, the script requires you to have python.

# Adding new flavours
The zip folder contains a file called 'settings' or 'settings.json'
This is a .json file that contains the "rules" of the script. i.e. what are the flavours we sell and how do we shorten them?
**When we start doing a new flavour - this file must be ammended ** otherwise the script will not recognise the flavour

For example: we are going to start doing Watermelon as the new flavour
- we must ammend the "settings" file

**How do we do this?**

We open the setting
