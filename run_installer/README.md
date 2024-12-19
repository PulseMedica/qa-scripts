### Setup
1. Open VSCode or terminal in admin mode.
2. Run ```python run_installer.py```
3. The program will promopt you for an input for the installer path. Simply provide one.
    - Example: ```"C:\Users\nathan_pulsemedica\Downloads\FSS-Setup-v1.2.0.386.exe"```
    - Include the double quotes. The script will strip it for you.
4. Let the automation run on its own. Takes around 20 seconds.

**Note:** The script will install FSS under ```C:\FSS_Tested```
    - This is to ensure the version # of FSS is not included in the path.
    - And so that TestComplete (or any other automation tool) can simply look for FSS UI in the above path without worrying about the version number.
    - If there's already a FSS installed there, it'll automatically overwrite it.
