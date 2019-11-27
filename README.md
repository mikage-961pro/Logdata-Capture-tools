# Logdata Capture Tools

Capture Data is tool to gather logging information for further analysis.
To begin, select the type(s) of data to gather,then press Start.


### How to use:
1. Double-click on the Capture Data application.
2. Select the desired options (described later in this document).
3. Click the Start button.
4. Enter your user's password when prompted. If prompted for a username and password, enter an admin user's name and password. You may be prompted to enter the admin user's password multiple times before Capture Data completes.
5. Enter a description of the issue along with the date and time that the issue last occurred, when prompted. Without the date and time, it will be more difficult for AppleCare to identify the issue. 

Once the application is complete, the captured information is saved into a file or directory named "ACCD_computerName_x" in /var/tmp/CaptureData, where computerName is the name of the computer as shown in Sharing preferences, and x is a number. 

You can open this location by clicking the [Open] button when complete, or by using Finder (Go > Go to Folder > /var/tmp/CaptureData)

Note: ***The application may sometimes appear to become unresponsive when *gathering data. Do not quit the application. You should wait for the application to complete or produce an error message.***

## Learn more:
Capture Data has several options available to select from depending on the issue. This is a brief overview of the options available in Capture Data.

These options gather logging that has already occurred

▪	Default information:  This option is enabled by default and cannot be turned off.

▪	macOS Mail Information:  Use this option when troubleshooting Mail issues. This will create a folder named "Mail.app-Info" that contains further details about the Mail application, such as the preference file com.apple.mail.plist.

▪	Logs from Previous System Folder: Use this option after performing an archive and install to gather the logs from the previous system folder. (This option will only be available if there is a previous System Folder.)

▪	Sysdiagnose: This generates a system diagnostic file with redacted information.

▪	Mobile Device logs: This gathers files that are synced from an iOS device.

▪	Time Machine information:  Use this option if you are troubleshooting a Time Machine-related issue. This will create a folder named "Time_Machine" that contains further details about Time Machine, such as the preference file com.apple.Time Machine.plist.
