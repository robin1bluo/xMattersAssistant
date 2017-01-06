
# xMattersAssistant Introduction
A handy tools to handle xMatters SMS with below features:

  1. Auto reply xMatters SMS if matched pre-defined SMS rules.
  2. SMS rules are configuable for two kinds of matching mechanism, Keyword or Regular Expression.
  3. Notification with one-tap-to-reply button for those xMatters SMS did not match with pre-defined rules.
  4. Work as SMS router that can send new SMS to specified phone number, and handle SMS reply (for xMatters) from that phone number.
  
## Simple Guide
0. This is a beta version, bugs are expected.

1. Interface:
&nbsp;&nbsp;&nbsp;&nbsp;<b>Rule1</b>: RegExp matching pattern. <a href="http://regular-expressions.mobi/refquick.html">Reference</a>

&nbsp;&nbsp;&nbsp;&nbsp;<b>Rule2</b>: Keyword matching pattern

&nbsp;&nbsp;&nbsp;&nbsp;<b>Router</b>: Specify phone number that SMS should be routed to

&nbsp;&nbsp;&nbsp;&nbsp;<u>Above three only works when check box ticked</u>

&nbsp;&nbsp;&nbsp;&nbsp;<b>Enable / Disable</b>: Master switch

&nbsp;&nbsp;&nbsp;&nbsp;<b>Kill Me!</b>: Disable and quit

2. For keyword match, can use "/" as a splitter. e.g. PBS001/SAS001 in keyword rule can match SMS with either keyword PBS001 or SAS001.

*. You are welcome to raise issue in <a href="https://github.com/robin1bluo/xMattersAssistant">the project github</a>. Any urgent query, please contact Robin1 B Luo.

## What's the Next?
0. Testing the SMS rule within the App
