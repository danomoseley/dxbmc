# Introduction #

The program will run in autonomous mode when supplied with any arguments (no matter what they are or if they are valid, this has been designed this way). The program will load your previous settings and use them if not overidden by a command line argument. Command line arguements will NOT be saved to your permanent settings.


# Details #
> [0/1] indicates option takes an argument of 0 or 1.
  * **Build** [0/1] - Sets whether or not you would like a new build to be downloaded and built.
  * **BuildType** - an option of "Update", "Fresh", or "Local" can be supplied. Automatically sets Build to 1.
  * **Rebuild** [0/1] - Sets whether or not you would like to do a clean rebuild rather than an updated build. Automatically sets Build to 1.
  * **FTP** [0/1] - Sets whether or not to ftp the build.
  * **IP** - Sets the IP to be used when connecting to the FTP server. Automatically sets FTP to 1 when used.
  * **Port** - Sets the port to be used when connecting to the FTP server. Automatically sets FTP to 1 when used.
  * **User** - Sets the username to be used when connecting to the FTP server. Automatically sets FTP to 1 when used.
  * **Pass** - Sets the password to be used when connecting to the FTP server. Automatically sets FTP to 1 when used.
  * **RemotePath** - Sets the remote server path to be used when transferring to the FTP server. Automatically sets FTP to 1 when used.
  * **FTPasFolder** [0/1] - Sets whether or not you would like the build to be sent as a folder. Automatically sets FTP to 1 when used.
  * **Rename** - Sets the folder name to be used when transferring the folder to the ftp server. Automatically sets FTP and FTPasFolder to 1 when used.
  * **Overwrite** - Sets whether or not you would like to overwrite the UserData folder. Automatically sets FTP and FTPasFolder to 1 when used.
  * **Delete** - Sets whether or not you would like the local rar build to be deleted after a successful FTP session. Automatically sets FTP to 1 when used.
  * **Email** [0/1] - Sets whether or not you would like to recieve an email.
  * **Emailto** - Sets the email to send to
  * **GUser** - Sets the google username to use for SMTP access. Automatically sets Email to 1.
  * **GPass** - Sets the google pasword to use for SMTP access. Automatically sets Email to 1.
  * **Shutdown** [0/1] - Sets whether or not you would like your computer to be shutdown after a successful session.



## Some examples ##
> dXBMC.exe /BuildType:Update /Rebuild:0 /FTP:1 /Rename:XBMC /Shutdown:1