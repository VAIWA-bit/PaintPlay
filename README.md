# PaintPlay
![prev](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/prev.png)
# Prerequisites
- ## Tested only on Windows 10
- ## Paint must be installed in **C:\Windows\system32**
- ## If you want to play Doom - **GZDoom** and **Doom Enhanced** won't work, use **Crispy Doom** instead
- ## The laucnher is built using **Microsoft Edge WebView2**. If you don't have it installed, you will need to install it. However, it comes pre-installed by default on Windows 10 and later.
# 1. Download PaintPlay.zip and install it
# 2. Setup
- ## **Required:** Ensure the game is set to run in windowed mode, modify its resolution, and verify that it is using OpenGL or Vulkan
- ## **Optional:** Launch Paint, hide the status bar, and minimize the ribbon if necessary
# 3. Play
##  Open the launcher and click the edit button to change the game path, then click play
## **Required:** The game path must not include non-English characters. The game path must include executable name.
### **Ex:**
```
C:\gog games\Braid\braid.exe
```
# 4. Custom Window Size (**Optional**)
## If a game cannot change its resolution, you can force a resize. However, be aware that each game manages resize events differently. Click on the edit icon and enter a custom resolution, e.g., 320x180. Check the box to use the custom window size
# 5. Custom Window Title (**Optional**)
## If the game crashes immediately after launching, you can specify its title. Click on the edit icon and enter a custom title, for example, 'Braid.' Check the box to use the custom window title. To obtain the window title, you can use the PowerShell code provided below
```
Get-Process | Where-Object { $_.MainWindowTitle } | Select-Object Id, ProcessName, MainWindowTitle
```
# 6. Custom Client Area (**Optional**)
## If you launch a game and see black bars on the right or bottom of the game frame, it indicates that you need to specify a custom client area resolution. Click on the edit icon and enter a custom resolution, such as 312x172. Check the box to use the custom client area
# 7. Launch with Arguments (**Optional**)
## If you want to play an emulator, and it supports this feature, you can specify the game path for it to load. Ensure that the arguments do not contain non-English characters. Click on the edit icon and enter the custom arguments. Check the box to use the custom arguments
# 8. Check for Corrupt Data (**Optional**)
## Use this option only if you have a capable PC, as it may slightly reduce your FPS. This option loads a bitmap from the clipboard and compares it with the one stored in RAM
# If you believe this project deserves your contribution, it would be greatly appreciated
# **Bitcoin**
![Bitcoin](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/bitcoin.png)
## bc1qtjvtktp5hkspzehaaaw6827crawhqkwgn7sf7u
# **Ethereum / Tether**
![Ethereum](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/Tether.png)
## 0xf516751FD82c942aA10430Cb52A12B10333E6BdE
# **Toncoin**
![Toncoin](https://raw.githubusercontent.com/VAIWA-bit/PaintPlay/refs/heads/main/img/toncoin.png)
## EQA3OYCxwhDVstIcIaquAeLvFR_PknhuB4WH-jpvMKpdRgeV
