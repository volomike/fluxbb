# FluxBB 1.5.11 Fork 1.1 Readme

## COMING IMPROVEMENTS IN THIS FORK (SOON!)

* Pen test report and security improvements.
* Plugins (if necessary, otherwise code forks):
  - Markdown Plugin: Removes BBCode altogether and switches it with Markdown, as well as Markdown toolbar.
  - File Attachment Plugin: Ability to attach files to messages, but restricts file size and file extension type, as well as does security checks before files are enabled for download. Admin settings let you decide possible file extensions.
  - Registration Admin Plugin: Ability to turn off regular registrations and require an admin to add someone via email address, and no email confirmation.
  - No Guest View Plugin: Turns off ability to view anything except a login form unless registered and logged in.

## About

FluxBB is an open source forum application released under the GNU General Public
Licence. It is free to download and use and will remain so. FluxBB was conceived and
designed to be fast and light with less of the "not so essential" features that some
of the other forums have whilst not sacrificing essential functionality or usability.

## Requirements

* A webserver
* PHP 5.6.4 or later
* A database such as MySQL 5.0.6 or later, PostgreSQL 7.0 or later, or SQLite 2

## Recommendations

* Make use of a PHP accelerator such as APC or XCache
* Make sure PHP has the zlib module installed to allow FluxBB to gzip output

## Links

* Homepage: https://fluxbb.org
* Documentation: https://fluxbb.org/docs/v1.5
* Community: https://fluxbb.org/forums/
* Resources: https://fluxbb.org/resources/
* IRC: irc://irc.freenode.net/fluxbb
* Development: https://github.com/fluxbb/fluxbb
