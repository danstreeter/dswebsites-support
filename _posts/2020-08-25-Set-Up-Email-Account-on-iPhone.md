---
layout: post
title:  "Set Up Email Account On iPhone"
date:   2020-08-25 21:15:51 +0100
categories: how-to
---
Once you have your email account, you may want to set it up on your iPhone.

Step-by-step guide
------------------

Open Settings > Mail > Add Account > Other > Add Mail Account, then you'll need to fill the right configurations for you mailbox:

**Name**: _Anything_  
**Email**: example@yourdomain.com  
**Password**: Mailbox Password  
**Description**: Work, Business...etc

**IMAP**:

Incoming Mail Server  
**Host Name**: imap.stackmail.com  
**Username**: example@yourdomain.com _(this should be your own email address)_  
**Password**: Mailbox Password

Outgoing Mail Server  
**Host Name**: smtp.stackmail.com  
**Username**: example@yourdomain.com _(this should be your own email address)_  
**Password**: Mailbox Password

Click on save

---

Getting a "Verifying server Identity" error on iOS devices?
-----------------------------------------------------------

If you are getting constant popup messages about "verifying server identity" - follow the steps below.

This is due to the way that apple iOS devices handle certificates (how communications are secured). iOS devices do not seem to allow ‘updating’ of certificates, and once it has spoken to a server once, stores the certificate for use later - this is why upon the next time seeing it, the server shows the iOS device a different certificate it shows an error about it being invalid, because the new certificate from the server does not match the old one it had stored.

Remove the account from all effected Apple devices

Re add the accounts as required in line with the details shown above.
