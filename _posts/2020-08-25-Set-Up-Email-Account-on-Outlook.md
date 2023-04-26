---
layout: post
title:  "Set Up Email Account On Outlook"
date:   2020-08-25 21:15:51 +0100
categories: how-to
---
Once you have your email account, you may want to set it up on your Microsoft Outlook mail client.

Step-by-step guide
------------------

We make use of 'autodiscover' technology, so that in the majority of cases, Microsoft Outlook can set up your account for you with only an email address and a password.

**Automatic Setup**

1.  In Outlook, choose the **File **tab
2.  Under 'Account Information', choose **Add Account**
3.  On the Auto Account Setup page, enter your name, email address, and password, and then choose **Next**
4.  Choose **Finish**

**Manual Setup**

If automatic setup failed, you can choose Manual setup or additional server types to enter your settings manually. Use these settings:

**Account type:** IMAP  
**Incoming mail server:** [imap.stackmail.com](http://imap.stackmail.com/).  
**Outgoing mail server:** [smtp.stackmail.com](http://smtp.stackmail.com/).  
**Incoming server port (IMAP):** 993  
**Use the following type of encrypted connection:** SSL  
**Outgoing server port (SMTP):** 465 (or 587)  
**Use the following type of encrypted connection:** TLS

When setting up your account, please choose More Settings > Outgoing Server and check the box for 'My outgoing server (SMTP) requires authentication'.

If you experience any problems with the connection or receive a certificate warning, please disable SSL/TLS encryption and change the incoming server port to 143.