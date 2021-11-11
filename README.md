![simpleytdlgui.v1.1](simpleytdlgui.png)

# Simple-Youtube-DL-Gui # 

## Supported Operating Systems ##
Windows 7 **(x64)**, Windows 8 **(x64)**, and Windows 10 **(x64)**

# How to use #
## Main Gui ##
1. Extract program from archive to a folder of your choice or Run program from the archive
2. Paste any video link into the "Paste Link" box
3. Select "Add Link"
4. Choose from the list of available options
5. Choose where you'd like to save the final file
6. Press "Start Job"

## Guide to building the program yourself: (Windows)
1. Install python x64 3.8.8 (https://www.python.org/ftp/python/3.8.8/python-3.8.8-amd64.exe) 
(This version supports Win7 - 11 x64)
2. Download https://github.com/jlw4049/Simple-Youtube-DL-GUI/archive/refs/heads/main.zip and extract 
3. Open command prompt and navigate to where ever you extracted step 2
4. In command prompt type 'pip install -r requirements.txt'
5. After words you can use pyinstaller to make a binary.exe if you'd like with the following command
- 'pyinstaller -w --onefile --icon"Runtime\Images\youtubeDLicon.ico" "SimpleYoutubeDLGui.py"'
6. Then you can place .exe along side of the runtime/apps folder and you're good to go
