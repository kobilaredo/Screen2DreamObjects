Screen2DreamObjects - Screenshot Uploader to DreamObjects Service Workflow For Mac OS X
====

A quick hook for Mac OS X to create a snapshot and upload it to DreamObjects

### Application Files 
screen2dreamobjects.py: Create a snapshot and upload it to DreamObjects

.dho\_access: Containes your DreamObjects login and bucket (one per line)

### Mac OS X Automation Service Workflow Package
Screen2DreamObjects.workflow: Create a snapshot and upload it to DreamObjects

###Instructions:
- Install boto
```
pip install boto
```

- Copy application files to **~/**

- Uptate .dho\_access with you DreamObjects info

- Install service package: 
    1. In Finder, double click on the workflow package
    2. Click Install

- In System Preferences > Keyboard > Shortcuts > Services > General
	1. Check the Screen2DreamObject checkbox
	2. Set a keyboard shortcut

- Use it: 
   1. press on the keyboard shortcut
   2. Select the area you want to capture

- PROFIT!!!
