AUTHOR=Ricky Divjakovski
VERSION=1.1
DESCRIPTION=How to create a patch file

# Lines beginning with # will be ignores
# Code is delimited by the | (pipeline) character
# Assume you are in the root(/) of the device

# This function will recursively search and delete a file - SearchDeleteFile|SEARCH STRING
# SearchDeleteFile|/system|*netflix*.apk

# This function will recursively search and delete a directory - SearchDeleteDir|SEARCH STRING
# SearchDeleteDir|/system|priv*app

# This function will delete a specific file - DeleteFile|FILE PATH
# DeleteFile|/system/preinstall/weather.apk

# This function will delete a specific directory - DeleteDir|DIR PATH
# DeleteDir|/system/preinstall/app

# This function will copy a file from one location to another - CopyFile|FILE TO COPY|DESTINATION FILE|Overwrite(Y/N)
# CopyFile|/system/preinstall/netflix.apk|/system/app/netflix.apk|Y

# This function will copy a directory from one location to another - CopyDir|FILE TO COPY|DESTINATION DIR|Overwrite(Y/N)
# CopyDir|/system/preinstall|/system/app/AnotherPreinstall|Y

# This function will move a file from one location to another - MoveFile|FILE TO COPY|DESTINATION FILE|Overwrite(Y/N)
# MoveFile|/system/preinstall/netflix.apk|/system/app/netflix.apk|Y

# This function will move a directory from one location to another - MoveDir|FOLDER TO COPY|DESTINATION DIR|Overwrite(Y/N)
# MoveDir|/system/preinstall|/system/app/OldPreinstall|Y

# This function will create a new file - CreateFile|FILE TO COPY|DESTINATION FILE
# CreateFile|/system/MyNewFile.txt

# This function will create a new directory - CreateDir|DESTINATION FILE|Overwrite(Y/N)
# CreateDir|/system/MyNewDir

# This function will append text to a file - AppendFile|FILE TO APPEND|TEXT TO APPEND
# Note, \n will be replaced with the new line character
# AppendFile|/system/build.prop|\n# MyNewProperty=1

# This function will replace a line in a file - ReplaceText|FILE|SEARCH POSITION|SEARCH STRING|REPLACEMENT LINE
# START will search for text at the start of a line, END will search for text at the end of a line, CONTAINS will search for text anywhere in the line
# Note, \n will be replaced with the new line character
# Examples below will edit ro.service.bootvideo=1 in /system/build.prop

# ReplaceLine|/system/build.prop|START|beo|ro.service.bootvideo=1
# ReplaceLine|/system/build.prop|END|deo=999999999|ro.service.bootvideo=1\n# line after
# ReplaceLine|/system/build.prop|CONTAINS|oodeo|ro.service.bootvideo=1

# This function will replace text in a file - ReplaceText|FILE|SEARCH STRING|REPLACEMENT
# Note, \n will be replaced with the new line character
# ReplaceText|/system/build.prop|bootvideo|bootanimation

# This function will download a file - Download|OUTPUT FILE|Overwrite if exists(Y/N)|DIRECT DL LINK
# Download|/system/app/netflix.apk|Y|https://direct.download.link

# This function will unzip a file into the directory specified - Unzip|ZIPFILE|OUTPUT directory
#Unzip|/system/text.zip|/system
