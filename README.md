# scrcpy-gui
- A beautifull gui for scrcpy using javascript

## ✨Features

- **lightness** (native, displays only the device screen)
- **performance** (30~60fps)
- **quality** (1920×1080 or above)
- **low latency** ([35~70ms](https://github.com/Genymobile/scrcpy/pull/646))
- **low startup time** (~1 second to display the first image)
- **non-intrusiveness** (nothing is left installed on the device)
- **No need for ROOT**
- **Wired and wireless can be connected**
- **You can adjust the interface and bit rate**
- **Pictures can be cut at will, with a screen recording**
- **Support multiple devices to screen at the same time**
- **Control your phone with your computer's keyboard and mouse**
- **Mobile computer sharing clipboard**
- **Automatically detect USB connected apps**
- **Can directly add the LAN IP of the device to achieve the effect of wireless control**
- **Automatically save the connected IP address, automatically reminder the next time you enter**
- **Support device alias**
- **Support for Chinese and English**
- **Tray menu**
- **etc...**

## 🎇Instructions

### connection method

#### Prerequisites

- Make sure **adb , scrcpy** are working properly
- Make sure the phone is turned on for USB debugging and certified for computer debugging

#### Wired connection

1. Make sure the phone is connected to the computer via the data cable

2. Wait for the software to automatically detect the device
3. Select the device and click `Open Selected Mirror`.
4. Wait for the device to open

#### Wireless connections

1. Please make sure the phone is on the same LAN as the computer.
2. When connecting for the first time:
   - **Please make sure your phone is connected to your computer via the cable**
   - **Please make sure that only one mobile phone is connected to the computer via the data cable**
   - The first time you need to set the port, you can connect to the phone later, just add the static IP of the phone.
3. Enter the LAN IP address of the phone (if the IP is DHCP assigned, please change to static IP)
4. Click `Open wireless connection`
5. Waiting for the wireless connection to succeed
6. Select the device and click `Open Selected Mirror`.
7. Wait for the device to open



## Shortcuts

| Action                                  | Shortcut                      | Shortcut (macOS)             |
| --------------------------------------- | ----------------------------- | ---------------------------- |
| Switch fullscreen mode                  | `Ctrl`+`f`                    | `Cmd`+`f`                    |
| Resize window to 1:1 (pixel-perfect)    | `Ctrl`+`g`                    | `Cmd`+`g`                    |
| Resize window to remove black borders   | `Ctrl`+`x` \| *Double-click¹* | `Cmd`+`x` \| *Double-click¹* |
| Click on `HOME`                         | `Ctrl`+`h` \| *Middle-click*  | `Ctrl`+`h` \| *Middle-click* |
| Click on `BACK`                         | `Ctrl`+`b` \| *Right-click²*  | `Cmd`+`b` \| *Right-click²*  |
| Click on `APP_SWITCH`                   | `Ctrl`+`s`                    | `Cmd`+`s`                    |
| Click on `MENU`                         | `Ctrl`+`m`                    | `Ctrl`+`m`                   |
| Click on `VOLUME_UP`                    | `Ctrl`+`↑` *(up)*             | `Cmd`+`↑` *(up)*             |
| Click on `VOLUME_DOWN`                  | `Ctrl`+`↓` *(down)*           | `Cmd`+`↓` *(down)*           |
| Click on `POWER`                        | `Ctrl`+`p`                    | `Cmd`+`p`                    |
| Power on                                | *Right-click²*                | *Right-click²*               |
| Turn device screen off (keep mirroring) | `Ctrl`+`o`                    | `Cmd`+`o`                    |
| Expand notification panel               | `Ctrl`+`n`                    | `Cmd`+`n`                    |
| Collapse notification panel             | `Ctrl`+`Shift`+`n`            | `Cmd`+`Shift`+`n`            |
| Copy device clipboard to computer       | `Ctrl`+`c`                    | `Cmd`+`c`                    |
| Paste computer clipboard to device      | `Ctrl`+`v`                    | `Cmd`+`v`                    |
| Copy computer clipboard to device       | `Ctrl`+`Shift`+`v`            | `Cmd`+`Shift`+`v`            |
| Enable/disable FPS counter (on stdout)  | `Ctrl`+`i`                    | `Cmd`+`i`                    |

*¹Double-click on black borders to remove them.*
*²Right-click turns the screen on if it was off, presses BACK otherwise.*



## 🎯Develop

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue)@[8fae476](https://github.com/SimulatedGREG/electron-vue/tree/8fae4763e9d225d3691b627e83b9e09b56f6c935) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).

Feel free to open issues or PRs for any problem you may encounter, typos that you see or aspects that are confusing. Contributions are welcome, open an issue or email me if you have something you want to work on.

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build

# lint all JS/Vue component files in `src/`
npm run lint
```

