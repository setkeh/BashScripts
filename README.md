BashScripts
===========

My Personal Collection of Hand Written BashScripts

CHANGES
-------

	28-jul-12: Added Upload_Dropbox

	28-jul-12: Added Upload_Screens

	29-jul-12: Optimised Dropbox Code, Fixed --help Issues, Disabled "win" Due to known issues.
	
	29-jul-12: Appended Dropbox Changes to ftp script, Fixed "win" Timing Issue Now Re-enabled.
	
	29-jul-12: Depricated xmessage In favor of copying links to "xclip primary" and "xclip clipboard"

TODO
----

1. Depricate Xmessage from ftp_screens and update it to current method in dropbox_screens.

Known Issues
------------

1. None As Yet. 


Dropbox Usage
-------------
dropbox_screens <args>
        
       ` --help =    Show this Help.`
       ` win    =    Select A Window Border With the Mouse.`
       ` scr    =    Take Screenshot of Entire Screen.`
       ` area   =    MultiHead Display Support (1 Shot each Screen).`

Dropbox_screens No Longer uses xmessage to display links. 
Instead links are copied into Pirmary and Clipboard.
To Use the Links you can either right click and paste "This is the Clipboard" OR
You and Middle Mouse Click (Also Bound to "shift + ins") "This is Primary.
And so you know that the script has done its work you will be presented with a
DBUS notify-send popup.

Please Remember that Dropbox can sometime take a fe minutes to sync (Depending on your connection)
so if you imidiatly try the link and get a 404 error THIS IS NOT A BUG just try the link again in a few minutes
and make sure you have your dropbox daemon running.

FTP Usage
---------
ftp_screens <args>
        
       ` --help =    Show this Help.`
       ` win    =    Select A Window Border With the Mouse.`
       ` scr    =    Take Screenshot of Entire Screen.`
       ` area   =    MultiHead Display Support (1 Shot each Screen).`

LICENCE
-------

All Scripts in this repository are open source
Please leave any comments, Attributes, links and references 
attached to the files if you plan to modify them
and redistribute them.


SHARE AND ENJOY :)
------------------
