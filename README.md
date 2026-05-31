# Clip-Stack

## Fork

This is a fork of [heruoxin's Clip-Stack](https://github.com/heruoxin/Clip-Stack) by [Willie Shen](https://github.com/Willie169).

## Features

- Remember clipboard history.
- Make clipboard history survive reboots. 
- Search, edit, and delete clipboard items with swipe gesture.
- Export clipboard history to text file.
- Show clipboard history in a notification.
- Share clipboard items to other apps.
- Automatically clean up this app's cache and RAM. 
- Support Android 4.0 and above and work better for Android 5.0 and above.

## Permission Usage

- `RECEIVE_BOOT_COMPLETED`:  Start a background service to listen to clipboard changes. You can disable it in Settings if you don't want it.
- `WRITE_EXTERNAL_STORAGE` and `READ_EXTERNAL_STORAGE`:  Only for exporting clipboard history.

## Credits

* [heruoxin/Clip-Stack](https://github.com/heruoxin/Clip-Stack)
* [nispok/Snackbar](https://github.com/nispok/snackbar)
* [brnunes/SwipeableRecyclerView](https://github.com/brnunes/SwipeableRecyclerView)
* [EatHeat/FloatingExample](https://github.com/EatHeat/FloatingExample)
* selio/icon

## Translate

* [Traditional Chinese: jacky030607](http://apk.tw/thread-645505-1-1.html)
* [Serbian: pejakm](https://github.com/heruoxin/Clip-Stack/pull/4)
* [French: RyDroid](https://github.com/heruoxin/Clip-Stack/pull/10)
* [Korean: 준모](https://twitter.com/cns_)
* [Japanese: 厨二病少女699](http://weibo.com/ikaemon)
* [Spanish: Guillem](https://github.com/Usak)
* [Russian: Владислав Сухов](https://github.com/Vladislav4KZ)

## License

- [app/src/main/res](app/src/main/res) is heruoxin's proprietary work and is not part of this project. It will be removed from the repo once I complete my independent version of it.
- The original Java code of [heruoxin/Clip-Stack](https://github.com/heruoxin/Clip-Stack) is licensed under MIT license.
- This project is licensed under GPL-3.0-or-later. Refer to [LICENSE.txt](LICENSE.txt).
