Google recently stopped supporting a feature called less secure apps which is what enabled you to access your Gmail using such a program.
 
Option 1: Upgrade to a modern email client
The first thing you should look to do is upgrade to a modern email client that supports modern authentication, then follow the steps on screen when logging into the new client with your Gmail account. You then won't need to enable 2 step verification, should you not want to, and won't need to follow any of the steps below. 
 
Option 2: Continue using a legacy client
Going forward, you will need to follow the steps below if you want to continue to access your Gmail using a legacy client. By following these steps. you should be aware that your Google account is less secure because it's linked to a mail client that doesn't support modern authentication.
Turn on 2-step verification. That's a requirement to use app passwords. 

Important: Make sure you store the backup codes in a safe place, multiple safe places if possible. Don't store them solely on your phone or tablet that could break or be stolen, and don't store them in Google products, that obviously become inaccessible if you need to recover your account.
 
Once enabled, generate an app password:
Go to myaccount.google.com.
Click the "Security" tab on the left-hand side.
Underneath "Signing in to Google", click "App passwords". (Remember you will not see this unless 2-step verification is enabled).
Click the "Select app" dropdown and select "Mail".
Click the "Select device" dropdown and I recommending selecting "Other" so you can give it a custom name that you'll recognise.
Enter the custom name and click "Generate".
Store this code somewhere safe and don't share it with anyone.
 
Turn on IMAP:
Open Gmail.
At the top right, click the Settings cog and then "See all settings".
Click on the "Forwarding and POP/IMAP" tab.
In the 'IMAP access' section, select Enable IMAP.
Click Save changes.
 
Configure your email client with the following settings as needed.
Incoming mail (IMAP) server
imap.gmail.com
Requires SSL: Yes
Port: 993
 
Incoming mail (POP) server
pop.gmail.com
Requires SSL: Yes
Port: 995
 
Outgoing mail (SMTP) server
smtp.gmail.com
Requires SSL: Yes
Requires TLS: Yes (if available)
Requires Authentication: Yes
Port for SSL: 465
Port for TLS/STARTTLS: 587
 
Full name or display name: Your name
Account name, username or email address: Your full email address
 
When prompted for the password, don't use the account password. Enter the app password you generated in step 2 instead. If these steps don't work initially, you may need to remove your account from the legacy mail app (if it's already added) and try again.
 
Important: If this is the only way you access your Gmail (Google) account it's really important you set up and keep up to date your recovery options. If you don't setup recovery options, it will be virtually impossible to recover your account should you need to.
