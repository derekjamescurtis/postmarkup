This is fork of http://code.google.com/p/postmarkup/

Generates XHTML snippets from BBCode.

See the wiki http://code.google.com/p/postmarkup/wiki/Usage for how to use this module, or http://www.willmcgugan.com/?s=bbcode for more information.

You can experiment with bbcode on the Postmarkup test server:

http://postmarkup.willmcgugan.com/

Differents from original project:

 * `optional, enabled by default` Right tag [right]text with right align\[/right] (Issue #24)
 * `optional, enabled by default` Restore PharagraphTag [p]
 * `optional, disabled by default` Support of local links [link=/photos/]See photos\[/link] (Issue #32)
 * Fix cleaning tags with spaces (Issie #30)
 * Use \n instead of \n\n for paragraphs
