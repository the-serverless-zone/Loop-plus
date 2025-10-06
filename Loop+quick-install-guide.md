Loop+quick-install-guide

Loop+ install quick guide. 9/30/2025

- - - 

In this install fill in 4 fields on script-1, then launch it in Cloudshell.
Add in 2 sms fields + the original 4 into script-2, launch in CloudShell.

IMPORTANT NOTES
1. Leave AWS CloudShell open for the few minutes it takes to run.
2. Keep the tab selected. Failing to do so will terminate the install.
3. When adding data, put it inside the quotes
4. Do not leave whitespace after the quotes. 

- - -

Note, permissions are provided. (Optional) make a granular version from the permissions in the link below.

https://github.com/the-serverless-zone/loop-code/blob/main/Permissions

Open Script 1, below. 

https://github.com/the-serverless-zone/loop-code/blob/main/Setup%20script%201%20-%20account

>>> Copy the raw file to a text editor, call it script1.txt

Inside the quotes, below.

line 22	Add an account number, which you can monitor during the install. 

line 24	Add a cell phone number you can use throughout the install. 

line 26	Add an email address you can review throughout the install. 

line 28	Add a Slack webhook. 

Slack accounts are free. The product video details how to create a webhook here. 

https://youtu.be/mFoOnipn5QQ?t=184

Make sure there are no whitespaces after the last quote. 

>> Copy and paste the completed script 1 into CLOUDSHELL

Read and wait for the messages to complete. 

On your phone you will get a message containing a registration number and a secret id

Make a careful note of those. Pasting these to an email on your phone is less troublesome most times. 

Open Script 2:

https://github.com/the-serverless-zone/loop-code/blob/main/Setup_script_2_configure

>>> Copy the raw file to a text editor, call it script2.txt

Add data inside the quotes, and make sure no white space exists after the last quote. 

Lines 22, 24, 26, and 28 are the same account, SMS, email address, and Slack webhook as above. 

Then add 

line 32 	registration_number

line 34 	secret_id 

>> Copy and paste the completed script 2 into CLOUDSHELL

Two more messages will appear. 

(i). Configure confirmation. Allow up to 4 minutes from when the CloudShell script has started to run.

(ii). A final comms test message. Allow 3 more minutes.

When you receive this final message, you are set up. 

To test, the video URL time is here:

https://youtu.be/mFoOnipn5QQ?t=379
