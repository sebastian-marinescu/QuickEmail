QuickEmail Extra for MODX Revolution
=======================================

**Author:** Bob Ray [Bob's Guides](http://bobsguides.com)


QuickEmail is a simple email snippet. It can be used to
send email from inside any snippet or plugin, but its
main use it simply to test your email system and diagnose
any problems with it.

If your email system is working, QuickEmail will send you
a test email with no configuration at all. Just install it
and put the following snippet tag on a page:

      [[!QuickEmail]]

When you preview the page, you should receive an email. If you don't, add the debug parameter and preview the page again:

      [[!QuickEmail? &debug=`1`]]

Please note that QuickEmail is **not an email form**. It is a snippet that sends an email.
