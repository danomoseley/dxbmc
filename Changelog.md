# Introduction #
  * **[r014](https://code.google.com/p/dxbmc/source/detail?r=014)** Added: Revision number to main GUI
  * **[r014](https://code.google.com/p/dxbmc/source/detail?r=014)** Changed: Options now greyed out if parent option is not selected, ie if ftp is not selected then all ftp options are greyed out
  * **[r014](https://code.google.com/p/dxbmc/source/detail?r=014)** Changed: Hidden ftp as folder settings when user doesn't need them
  * **[r014](https://code.google.com/p/dxbmc/source/detail?r=014)** Changed: Hidden custom SMTP settings when user doesn't need them
  * **[r014](https://code.google.com/p/dxbmc/source/detail?r=014)** Added: Support for smtp servers with no login.

  * **[r013](https://code.google.com/p/dxbmc/source/detail?r=013)** Fixed: Cut the size of the exe in half by compressing pictures used by the program
  * **[r013](https://code.google.com/p/dxbmc/source/detail?r=013)** Fixed: Fixed more of the error checking / general code layout

  * **[r012](https://code.google.com/p/dxbmc/source/detail?r=012)** Added: Custom SMTP server support as requested by _gehx_
  * **[r012](https://code.google.com/p/dxbmc/source/detail?r=012)** Updated: updated a few more error messages to match the standard
  * **[r012](https://code.google.com/p/dxbmc/source/detail?r=012)** Fixed: Batch mode settings wasn't in the settings file, and there was an uneeded ftpmode settings there (you may need to delete settings.xml, you'll get an error if you need to)
  * **[r012](https://code.google.com/p/dxbmc/source/detail?r=012)** Fixed: Throws error when unable to update settings.xml too
  * **[r012](https://code.google.com/p/dxbmc/source/detail?r=012)** Fixed: Now throws errors if there's a problem opening or parsing the settings.xml

  * **[r011](https://code.google.com/p/dxbmc/source/detail?r=011)** Changed to not send email on "abort" too

  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Changed: Error handling/program exit conditions/and error logging
  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Updated: Logging behavior
  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Fixed: Email sending now syncronous instead of asyncronous, log file was probably locked when trying to send email
  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Removed: "skipped" steps from log
  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Fixed: When ftp as folder was checked, but no rename text entered the program would error, now it default ftps to folder "Build"
  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Fixed: Redundant shutdown conditions, let me know if anything there is messed up.
  * **[r010](https://code.google.com/p/dxbmc/source/detail?r=010)** Added: Emails are now always sent before environment exit if the option is checked, only time they are not is if error in command line option or exit through "cancel" or "close" buttons