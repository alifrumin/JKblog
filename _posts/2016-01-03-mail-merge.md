---
layout: post
title:  "Mail Merging"
date:   2016-01-03 23:51:52 -0500
---

Over Break I went into NCCA (where I worked before I started GA) to help them with some conference prep. I found looking at the tools, and the set up for executing the task at hand now, after all we have learned the past couple of months extremely interesting. The technical skills involved essentially boiled down to doing a mail merge.

When I thought about a mail merge pre GA my first thoughts were of an Excel Spreadsheet and a word document template. Lets say for instance one wanted to make a bunch of certificates with peoples names and titles, one would create a spreadsheet with at table header (row 1) with columns for "name" and "title" and then a template document in word... and follow the mail merge wizard to insert the tokens for name and title where you wanted them to go. Then one would run the mail merge and word.. or the magical wizard who lives inside word would create a page for each row of your excel document.

Looking at the mail merge we were setting up at NCCA over break (using [Yet Another Mail Merge][yet-another-mail-merge] a google chrome add on that makes it so one can use a google sheet to do a mail merge into gmail) what I see now is for all essential purposes a for loop...Im sure its more complicated than that, especially when interacting with gmail but...a mail merge which used to seem like wizardry looks very very familiar and far less complicated and like a lot of things we have seen (like a show page and the spreadsheet is like a very simple noSQL table). 

I decided to look into the documentation and a little research confirmed my suspicions the following [article][google-dev-blog] runs thru code snippets used in yet another mail merge.

[yet-another-mail-merge]: https://sites.google.com/site/scriptsexamples/available-web-apps/mail-merge
[google-dev-blog]:  http://googleappsdeveloper.blogspot.fr/2011/10/4-ways-to-do-mail-merge-using-google.html
