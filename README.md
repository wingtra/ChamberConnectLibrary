# ChamberConnectLibrary
Python library for interfacing with Espec North America temperature chambers via ethernet connection. This is a fork from upstream which is adapted to work with our temperature chamber SU-242. Unfortunatly the upstream library is using python 2.7 with no update in sight. 

## Requirements
python 2.7.x

## Installation
```pip install chamberconnectlibrary```

## Updating
Do to some renaming to make the library pep8 compliant some files have been renamed from version 1.x to 2.0.0.
To ensure that the current version is used uninstall and then reinstall the library:
```pip uninstall chamberconnectlibrary```
```pip install chamberconnectlibrary```

## Testing

To test run chamberconnectlibrary-test.py(on windows using COM port #3, test script is located in Python2.7\Scripts directory)

P300: ```chamberconnectlibrary-test.py Espec Serial \\.\COM3 19200```

SCP-220: ```chamberconnectlibrary-test.py EspecSCP220 Serial \\.\COM3 9600```

Watlow F4T: ```chamberconnectlibrary-test.py WatlowF4T RTU \\.\COM3 38400```

Watlow F4: ```chamberconnectlibrary-test.py WatlowF4 RTU \\.\COM3 19200```

## Documentation
See [controllerinterface.md](controllerinterface.md)
