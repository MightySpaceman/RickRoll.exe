# RickRoll.exe
A harmless piece of jokeware made in python, compiled into an EXE file for portability without needing python or the involved libraries on the target computer.

# What It Does (Step By Step)

- Download image of rick astley into the C:\tmp directory using the CURL command.
- Open Never Gonna Give You Up in default web browser
- Set the newly downloaded 'rick.jpg' in the tmp directory as desktop background

# Limitations
As of the current revision, RickRoll.exe only works on windows. This may change in the future, but time will tell.
When running the source code within python, the script uses the following modules: ctypes, time, subprocess, os
