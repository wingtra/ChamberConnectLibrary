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


## Documentation
See [controllerinterface.md](controllerinterface.md)
