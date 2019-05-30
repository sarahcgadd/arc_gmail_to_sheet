# arc_gmail_to_sheet

google apps code to take information from job completed emails from UofL ARC scheduler and put it in a spreadsheet

Based on code from here(http://bionicteaching.com/auto-logging-email-via-google-script/) and here (https://stackoverflow.com/questions/14956479/remove-html-formatting-when-getting-body-of-a-gmail-message-in-javascript)

You could probably make this code better

To set up:
1) Make a filter in your arc gmail account to label emails from root and containing the word "complete" with the label "complete"
2) Make a google sheets spreadsheet with a sheet called "data" (using the same gmail account as you get your arc emails in)
3) Click on tools, script editor and paste the code from the Scripts file on here in there
4) Click on the strange time icon and set the triggers for this script to run -- I run it every time I open the sheet.

The complete label will be removed from your email so you don't put it in your spreadsheet twice
The value of the variables specified in each line of the email will form a column each, so you could make column headers to say what they are.
