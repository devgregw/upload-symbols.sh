# upload-symbols.sh
This shell script uses the Crashlytics symbol upload script to upload your iOS app dSYMS to Firebase.

# Usage
Save the script then complete lines 13 and 14 to be the path to the Fabric upload script in your Pods directory and the path to the GoogleService-Info.plist file, respectively.

Before executing the script, open Xcode Organizer, select the archive you want to upload symbols for, and click "Download Debug Symbols" under "Archive Information".

Open a new terminal and drag the script in.  Navigate to your archive directory in Finder (`~/Library/Developer/Xcode/Archives`).  When you locate the correct `.xcarchive` file, drag it into Terminal next to the script.  Press return.
