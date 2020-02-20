# midi-ql

A quicklook plugin to play midi files on OS X

### Note

I (originally developed)[https://discussions.apple.com/thread/5502114] this in 2016 and have not tested it since OS X 10.9ish

### Disclaimer

Forewarning, the reason this was taken out of OS X is due to a security vulnerability it caused; while not a major security flaw, Apple opted to discontinue midi preview, I'm guessing because it was relatively infrequently used when considering your average user. For me, it is worth the risk to have midi previews.

Developer is not responsible for any damage or errors that may occur, use this at your own risk and please know what you're doing, this isn't for beginners.

### Installation
First, download the latest release of midi-ql.zip and unzip.

1. Move `midiQL.qlgenerator` to `~/Library/QuickLook`
2. Move `Audio.qlgenerator` to `/System/Library/QuickLook`
3. Move `Music.qldisplay` to `/System/Library/Frameworks/Quartz.framework/Versions/A/Frameworks/QuickLookUI. framework/Versions/A`
4. Open `/Applications/Utilities/Terminal.app` and run `qlmanage -r && qlmanage -r cache`
5. Preview audio and midi to your heart's content!

### Possibble Errors

To change system files you will have to (disable SIP)[https://apple.stackexchange.com/questions/208478/how-do-i-disable-system-integrity-protection-sip-aka-rootless-on-macos-os-x]
