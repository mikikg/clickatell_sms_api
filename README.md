# CLICKATELL SMS API - Archived

This PHP class is meant to send SMS messages (with unicode support) via 
the Clickatell gateway and provides support to authenticate to this service, 
spending an vouchers and also query for the current account balance. This class
use the fopen or CURL module to communicate with the gateway via HTTP/S.

For more information about CLICKATELL service visit http://www.clickatell.com

# CHANGE LOG
13 June 2007, Version 1.6

- Changed maximum mesage lenght to 458 characters (tnx to Adam Hamer)
- Typo fix

12 Jan 2006, Version 1.5

- Fixed bug in function encode_message (tnx Neil)

17 Dec 2005, Version 1.4

- Added facility for delivering Unicode messages
- Added function token_pay() for spending vouchers

4 Jan 2005, Version 1.3d

- Added class documentation in package
- Rewritten code comments

13 Nov 2004, Version 1.3

- Added support for concatenated messages (up to 465 characters)
- Added support for API callback (please read Clickatell HTTP API 
  specifications, section 2.1.5)
- Minor bug fix and improvements

14 Apr 2004, Version 1.2
- Added CURL proxy support 

9 Apr 2004, Version 1.1
- Added fopen method for communicating with gateway 

13 Jan 2004, Version 1.0
- First Sourceforge SMS API release 
