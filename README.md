# Valorant-Custom-Home-Wallpaper-2.0
Automatically swap custom Valorant wallpapers. User-friendly interface. Set up automatic updates. Create standalone exe file. | Automatischer Austausch benutzerdefinierter Valorant-Hintergrundbilder. Benutzerfreundliche Oberfläche. Automatische Updates einrichten. Erstelle eigenständige EXE-Datei.

Valorant Custom Wallpaper Swapper
This Python project allows users to automatically swap custom wallpapers for the game Valorant. It provides a simple and user-friendly interface to select the wallpapers and set up automatic updates. The project also includes the ability to create an executable file (exe) to run the program on other systems without Python installation.

Features
• Select Wallpaper Folder: Users can specify the folder where the desired wallpapers are located.
• Automatic Wallpaper Swapping: The program automatically swaps between the wallpapers in the selected folder.
• Previous and Next Wallpaper: Users can manually switch to the previous or next wallpaper.
• Configurable Time Intervals: The time interval between wallpaper changes can be customized by the user.
• Support for Custom Wallpaper Names: Users can specify the name of the wallpaper to make it more personalized.
• System Tray Integration: The program runs in the system tray and can be controlled from there.
• Deployment as an Executable File: The project includes the ability to create an executable file (exe) to run the program on other systems without Python installation.

Technologies Used
• Python: The program was developed using the Python programming language.
• PyStray: PyStray was used to integrate the program into the system tray.
• Tkinter: Tkinter was used for creating the user interface.
• PyQt5: PyQt5 was used for certain functionalities of the user interface.
• JSON: JSON was used for storing settings and configurations.
• PyInstaller: PyInstaller was used to convert the Python program into an executable file (exe).

Requirements
• Python 3.x
• The required Python libraries are listed in the requirements.txt file.

Installation and Usage
1. Clone the repository or download the ZIP file.
2. Ensure Python is installed.
3. Install the required libraries by running the command pip install -r requirements.txt.
4. Run the file ValorantHomeWallpaperSwaper.py to start the program.
5. Select the wallpaper folder and configure the desired settings.
6. The program will run in the system tray and automatically swap between wallpapers according to the set preferences.

Deployment as an Executable File (exe)
1. Install the required libraries by running the command pip install -r requirements.txt.
2. Use the PyInstaller tool to convert the Python program into an executable file (exe). To do this, run the command pyinstaller --onefile ValorantHomeWallpaperSwaper.py.
3. Once the process is complete, you will find the created executable file in the dist directory.
4. Copy the exe file to the target device and run it to execute the program without Python installation.

Contributors
• ChangChi
• ChatGPT from OpenAI

License
This project is licensed under the MIT License.

Adjust the project description accordingly to your specific requirements and add any additional information if desired.
