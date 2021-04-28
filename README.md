# j-lawyer-server-installer
j-lawyer.org Server Installer 

## Code Signing for macOS

### Prerequisites

* XCode install is required - version 10.1 is the latest supported on macOS 10.13.6
* Copy apple-codesigning-jkitconsult.p12 to the installers directory

### Generating installers

* Launch install4j
* Under "General Settings" - "Code Signing", enable "Sign macOS media files"
* Provide the relative path to the certificate: ./apple-codesigning-jkitconsult.p12
* Enable "Notarize with Apple ID" and provide the primary mail address of Jens Kutschke IT Consulting je[..].k[..]@j-d[...].com
* Leave "Provider short name" unselected and empty
* certificate and app-specific password stored in KeyPass
