# Word Helper
Find the definition of a word and save it in a notepad file automatically

Uses Google Dictionary API in order to find the definition of the words. The API returns a JSON object which can then be parsed for definitions and examples as well. 

Uses an AutoHotKey script to copy selected word to clipboard and run the executable of the python script (generated by PyInstaller) in order to add the word definition entry to the notepad file. 

Required Python libraries:
1. Requests - to fetch the JSON object from the URL API
2. Pyinstaller - in order to package the script neatly into an executable.

Note: `pyinstaller --onefile --noconsole wordhelper.py` generates the required exe file.
