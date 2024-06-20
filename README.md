# pyqt-python-qt
A simple code to convert a file from Qt to Python code or build it into an application

Convert `.ui` file to `.py` file use :
```Bash
pyuic5 -x Filename.ui -o Filename.py
```

Convert from `.qrc` file to `.py` file use :
```Bash
pyrcc5 Filename.qrc -o Filename.py 
```

Convert from `.qrc` file to `.exe` file use :
```Bash
pyinstaller --onefile --noconsole Filename.py
```

Warning: 
If an error notification appears during the conversion, such as:
`
'pyinstaller' is not recognized as an internal or external command,
operable program or batch file.
`

please install PyInstaller first.
```Bash
pip install pyinstaller
```
