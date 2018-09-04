# fable-pc-app-release-yosemite
Release of Fable Blockly for macOS Yosemite with official Apple code signing certificate

## How to build
Yosemite cannot sign packages. Therefore the build has to be done in High Sierra.

Done in a similar way as the win32 release. The server is built manually on a Yosemite Mac. Its then copied to a High Sierra Mac.

Finally, the build_32 command is ran on the High Sierra Mac.
