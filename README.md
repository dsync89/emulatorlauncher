# About

I created this fork from retrobat-6.1 to add AutoHotKeyv2 emulator.

Usage:

Simply pass the value `-emulator autohotkeyv2` to the `emulatorLauncher.exe` to invoke the AutoHotKeyGenerator class to run the .ahk file. 

Also setup BatGUI.exe to hard code the `-emulator` value. For example, my Nintendo Switch roms are a bunch of `.ahk` files.

![image](https://github.com/dsync89/emulatorlauncher/assets/12208390/48bf1857-fe3a-4732-ab49-f0ffedf9aa88)

```
"C:\RetroBat\emulationstation\emulatorLauncher.exe"  -gameinfo "C:\Users\Gary\AppData\Local\Temp\emulationstation.tmp\game.xml" -p1index 0 -p1guid 030000005e040000e002000000007200 -p1path "BTHENUM\{00001124-0000-1000-8000-00805F9B34FB}_VID&0002045E_PID&02E0\7&1F7A91F6&0&E417D844FE76_C00000000" -p1name "Xbox One S Controller" -p1nbbuttons 16 -p1nbhats 1 -p1nbaxes 6  -system switch -emulator autohotkeyv2 -core  -rom "Z:\roms-noset\nintendo-switch\Darkest Dungeon [01008A700989A000].ahk"
```

