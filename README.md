# GoogleAuthenticatorReader
Reads a QR Code containing exported TOTP tokens from Google Authenticator and displays the information in human-readable format.  This is intended to help you import TOTP / HOTP codes in an application that does not support importing from a QR code.

## No Installation Necessary
You can download the `GAReader.html` file to your computer and open it locally, or run it from github pages: https://bp2008.github.io/GoogleAuthenticatorReader/GAReader.html

## Why should you trust this?
You should be wary of any program that wants access to your 2-factor authentication secret keys.  Therefore everything is in one simple html page so that the code can be easily inspected before you use it.  I used some third-party dependencies for reading and decoding the data in the QR code (these dependencies are loaded via a public CDN), but otherwise all the code is self-contained in `GAReader.html`.
