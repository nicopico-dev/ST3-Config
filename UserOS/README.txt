OS specific settings

For these settings to work, you must create a symbolic link in the parent Directory (Package)
for Windows (as an administrator) -> mklink /D UserOS User\UserOS
for OSX/Linux -> ln -s User/UserOS

/!\ "Common" settings override OS specific settings /!\