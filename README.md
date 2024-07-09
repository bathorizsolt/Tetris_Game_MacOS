This build contains 2 type of MacOS builds -> Intel 64-bit -> Render_MacOS<br>
                                              Apple silicon-> MacOS
  
If you have problems with opening the app follow the next steps:

1. Open Terminal
2. Locate the donwloaded folder (make sure it's not an iCloud folder)
3. type in the next command: cd "Folder Name" (for example: Downloads, Desktop)
If you can see "Folder Name %" then
4. type in the next command: chmod 755 MacOS.app/Contents/MacOS/'Tetris'<br>
                       or    chmod 755 Render_MacOS.app/Contents/MacOS/'Tetris'
It should open by Double Click on the Application

If you still have a problem and your Mac says you should move it to the trash bin, then follow the next steps:

1. Open Terminal
2. Locate the donwloaded folder (make sure it's not an iCloud folder)
3. type in the next command: sudo spctl --master-disable
4. type in your Password, then hit Enter
5. type in the next command: xattr -cr
   drag your MacOS or Render_MacOS file after the command so it will paste your destination instead of writing it all the way<br>
   If you can see the destination, for example: "xattr -cr /Users/Username/Downloads/Tetris_Game_MacOS-main/MacOS.app" then hit Enter
6. type in the next command: chmod 755 MacOS.app/Contents/MacOS/'Tetris'<br>
                       or    chmod 755 Render_MacOS.app/Contents/MacOS/'Tetris'

These solutions should solve your problems. If your Mac is still asking for permissions, then:
1. Open System Preferences
2. Click Security and Privacy (or similar I don't remember)
3. Click on General Tab
4. On the bottom you should click Open anyway.

Everything should be fine after following these steps.

Have fun, and please don't forget to give feedback :)
