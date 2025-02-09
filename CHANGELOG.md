## 6.4.705 - 2021-03-22
### Fixed:
- fixed a startup issue on RPi
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.7-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.7-3)
- Collabora Office tag [cp-6.4-31](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-31)

## 6.4.704 - 2021-03-21
### Fixed:
- fixes related to app:check-code (fixes #118)
- call clearstatcache() whenever seems to be necessary
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.7-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.7-3)
- Collabora Office tag [cp-6.4-31](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-31)

## 6.4.703 - 2021-03-20
### Fixed:
- fixed upgrade from previous version
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.7-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.7-3)
- Collabora Office tag [cp-6.4-31](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-31)

## 6.4.702 - 2021-03-19
### Fixed:
- fix startup problems when exec() is disabled (#100)
- prefix internal URLs with index.php/ (#103 and #59)
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.7-2](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.7-2)
- Collabora Office tag [cp-6.4-30](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-30)

## 6.4.608 - 2021-03-13
### Fixed:
- use posix_kill() instead of querying /proc
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.6-8](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.6-8)
- Collabora Office tag [cp-6.4-28](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-28)

## 6.4.607 - 2021-03-06
### Fixed:
- get cached hosting/capabilities (faster start)
- Fix ARM64 app name in info.xml (fixes #99)
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.6-7](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.6-7)
- Collabora Office tag [cp-6.4-28](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-28)

## 6.4.606 - 2021-03-01
### Fixed:
- Reduced AppImage size (removed some fonts and unused files)
- Support Nextcloud 21 #108
- Use port 9983 instead of 9982 which is used by tvheadend #110
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.6-6](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.6-6)
- Collabora Office tag [cp-6.4-27](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-27)

## 6.4.601 - 2021-02-11
### Fixed:
- remove stale lockfile
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.6-1](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.6-1)
- Collabora Office tag [cp-6.4-23](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-23)

## 6.4.503 - 2021-02-05
### Fixed:
- fixed logical error in startup code
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.5-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.5-3)
- Collabora Office tag [cp-6.4-22](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-22)

## 6.4.403 - 2021-02-01
### Fixed:
- do not start loolwsd if it is started already (better fix)
- fix crash with libfontconfig in Nextcloud snap
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.4-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.4-3)
- Collabora Office tag [cp-6.4-20](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-20)

## 6.4.303 - 2021-01-17
### Fixed:
- do not start loolwsd if it is started already
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.3-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.3-3)
- Collabora Office tag [cp-6.4-19](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-19)

## 6.4.302 - 2021-01-12
### Fixed:
- pidof was not available under Nextcloud snap, use pidfile instead
- disown was not available under Nextcloud snap's default shell (dash), force bash
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.3-2](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.3-2)
- Collabora Office tag [cp-6.4-19](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-19)

## 6.4.301 - 2021-01-08
### Fixed:
- Translation updates
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.3-1](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.3-1)
- Collabora Office tag [cp-6.4-19](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-19)

## 6.4.203 - 2020-12-19
### Fixed:
- Fixed user ID check in Nextcloud snap: https://github.com/nextcloud/richdocuments/issues/1282
- Translation updates
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.2-3](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.2-3)
- Collabora Office tag [cp-6.4-15](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-15)

## 6.4.202 - 2020-12-03
### Fixed:
- Check permissions before chmod
- Translation updates
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.2-2](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.2-2)
- Collabora Office tag [cp-6.4-15](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-15)

## 6.4.14 - 2020-10-28
### Fixed:
- Add Collabora Office's program directory to LD_LIBRARY_PATH in AppImage on ARM64, in order to find the right libxml2.so
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.0-14](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.0-14)
- Collabora Office tag [cp-6.4-10](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-10)

## 6.4.13 - 2020-10-25
### New feature:
- New major release based on CODE 6.4
- Freeze rows and columns in spreadsheets
- PDF annotation
### Fixed:
- Update location of screenshots
- Update default AppImage url
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-6.4.0-13](https://github.com/CollaboraOnline/online/releases/tag/cp-6.4.0-13)
- Collabora Office tag [cp-6.4-9](https://git.libreoffice.org/core/+/refs/tags/cp-6.4-9)

## 4.2.900 - 2020-10-15
### Fixed:
- ARM64 detection
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.9-1](https://github.com/CollaboraOnline/online/releases/tag/cp-4.2.9-1)
- Collabora Office tag [cp-6.2-24](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-24)

## 4.2.800 - 2020-09-08
### New feature:
- Search in embedded PDF files
### Fixed:
- Small UI fixes and improved translations
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.8-1](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.8-1)
- Collabora Office tag [cp-6.2-23](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-23)

## 4.2.602 - 2020-07-31
### New feature:
- Possibility to lock the document for editing
- Add support for BreadcrumbDocName
### Fixed:
- Fixed Chinese (Taiwan) localization
- Fixed displaying of close button
- Send Action_Save_Resp when notification was requested on save as
- Fixed clipboard handling when copying is disabled
- Other small cosmetic fixes
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.6-2](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.6-2)
- Collabora Office tag [cp-6.2-21](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-21)

## 4.2.503 - 2020-06-29
### New feature:
- Added localizations of admin panel strings
### Fixed:
- Fixed image URLs of help and about box logo
- Fixed default user avatar image
- Fixed sidebar panel scrolling
- Fixed messed up view when deleting from multiline content in Calc
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.5-3](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.5-3)
- Collabora Office tag [cp-6.2-18](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-18)

## 4.2.407 - 2020-06-23
### Fixed:
- Another try for the right check how to detect musl-based distros
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.4-6](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.4-6)
- Collabora Office tag [cp-6.2-17](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-17)

## 4.2.406 - 2020-06-22
### Fixed:
- Better check for the fail on musl-based distros
- Try to set en_US.UTF-8 locale, if C.UTF-8 locale is not available
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.4-6](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.4-6)
- Collabora Office tag [cp-6.2-17](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-17)

## 4.2.405 - 2020-06-21
### New feature:
- Compatibility with snap: it needs a specific unix socket name
### Fixed:
- Fixed 'Save as' and 'Insert local image' features
- Fixed Chinese (Taiwan) localization of sidebar
- Fixed a crash in Japanese Calc
- Disabled tooltips on Calc formula bar, that overlapped the entered text
- Fixed: in Impress hyperlink were inserted as button instead of text object
- Fixed: in Writer first-line indent, paragraph indent, and tab spaces on ruler
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.4-5](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.4-5)
- Collabora Office tag [cp-6.2-17](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-17)

## 4.2.404 - 2020-06-09
### New feature:
- Add the Admin Settings page in Nextcloud
- Add 'Remove tabstop' option to ruler
### Fixed:
- Fixed 'Download as' and 'Print' features
- Re-try with --appimage-extract-and-run when normal run of AppImage fails.
- Check for fontconfig in proxy.php?status
- Show icons on mobile user interface
- Do not check for root user when started with --disable-lool-user-checking (snap)
- Disable seccomp for AppImage
- Make native drawing of FormattedField work [tdf#133498](https://bugs.documentfoundation.org/show_bug.cgi?id=133498)
- Don't enter the OLE editing mode right after inserting a chart.
- Formula bar: missing text selection handles
- Make sure document title bar is not above dialogs
- Do not flicker during zoom in Writer
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.4-3](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.4-3)
- Collabora Office tag [cp-6.2-15](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-15)

## 4.2.403 - 2020-06-02
### Fixed:
- Disabled Welcome message, because links did not work
### AppImage version:
- Collabora Online Development Edition (CODE) tag [cp-4.2.4-2](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.4-2)
- Collabora Office tag [cp-6.2-14](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-14)

## 4.2.402 - 2020-06-02
- First public release, based on:
  - Collabora Online Development Edition (CODE) tag [cp-4.2.4-2](https://git.libreoffice.org/online/+/refs/tags/cp-4.2.4-2)
  - Collabora Office tag [cp-6.2-14](https://git.libreoffice.org/core/+/refs/tags/cp-6.2-14)
