# Symbolicate Crash Reports
This script is based on Apple's symbolicate script. With some minor changes it now symbolicates macOS default crash reports (tested on 10.9 and 10.13)

Written in Perl.

## Usage

```
DEVELOPER_DIR="/Applications/Xcode.app" /Path/To/symbolicatecrash /Path/To/report.crash > /Path/To/readable_report.crash
```

Use -v for verbose logging.

## Credits

You will find the original script here: 
```
/Applications/Xcode.app/Contents/SharedFrameworks/DVTFoundation.framework/Versions/A/Resources/symbolicatecrash
```

Copyright (c) 2008-2015 Apple Inc. All Rights Reserved.
