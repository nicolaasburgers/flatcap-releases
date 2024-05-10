# FlatCap
Use the links on this page to find installation files, documentation, issue tracking and discussions related to the FlatCap plug-in for Grasshopper.

### How to get yourself up and running with FlatCap
#### 1. Install using PackageManager
FlatCap can be found on PackageManager, with the "include pre-releases" checkbox ticked.

#### 2. Optional: set up connection to server
To enable the CncSimEx command ("CNC simulation: extended"):
2.1 Post a request on the discussion board (or contact the author) for a user access key and wait to receive the key
2.2 If the `%appdata%\FlatCap` folder doesn't exist, it will need to be created
2.3 A text file called `settings.json` will need to be created containing this text: `{"UserAccessKey": "00000000-0000-0000-0000-000000000000"}`, where the value full of zeroes is replaced with the given user access key
2.4 Restart Rhino

### Notes
This plug-in is still an alpha release, so you will likely encounter bugs - please post them on the discussion board.  Without any user access key, the CncSimEx command will not work.  There are other settings you can set in the `settings.json` file - more information is in the Wiki.
