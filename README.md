# arc_gmail_to_sheet

google apps code to take information from job completed emails from University of Leeds ARC and put it in a spreadsheet

Based on code from here(http://bionicteaching.com/auto-logging-email-via-google-script/) and here (https://stackoverflow.com/questions/14956479/remove-html-formatting-when-getting-body-of-a-gmail-message-in-javascript)

You could probably make this code better

To set up:
1) Make a filter in your arc gmail account to label emails from root and containing "complete" with the label "complete"
2) Make a google sheets spreadsheet with a sheet called "data" (using the same gmail account as you get your arc emails in)
3) Click on tools, script editor and paste the code from here in there
4) Click on the strange time icon and set the triggers for this script to run -- I run it every time I open the sheet.
