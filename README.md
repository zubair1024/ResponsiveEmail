ResponsiveEmail
===============

Responsive email that gracefully degrades.


It is an HTML5 and CSS3 based email template build by me for my professional use. 
It has a generic template so it can be used for multiple purposes.

It is responsive in nature, i.e., it gracefully degrades as per the screen-size resolution and the client used.

The necessary changes for BBM and Yahoo mail client have be described below:


FOR YAHOO MAIL: 
1) CONVERT THE CLASS BASED SELECTORS TO ATTRIBUTE BASED SELECTORS.
table.container {} => table[class.container] {}
2) SMALL SIZE IMAGES 650 PIXELS WIDE.
3) CREATE SMALLER SET OF ICONS 50X50 PIXELS MODIFY CSS RULES.

FOR BLACKBERRY 5:
1) ALL TD SHOULD BE OF MAX LENGTH
HTML ATTRIBUTES => <td width="640" .... >
MEDIUM SCREEEN RULES => td.logo {width : 480px; ... } td.headline {width : 480px; ... } td.content {width : 480px; ... }
SMALL SCREEN RULES =>   td.logo {width : 100%; ... } td.headline {width : 100%; ... } td.content {width : 100%; ... }
