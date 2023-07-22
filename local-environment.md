# VS Code
for writing code
### Chromebook
https://code.visualstudio.com/blogs/2020/12/03/chromebook-get-started#_install-vs-code

# Postman
for testing API routes
### Chromebook
##### Get the files
1. Download Postman from https://www.postman.com/downloads/
1. Move the downloaded zip to a location inside linux files
1. Open up the linux terminal and navigate to where you put the zip
1. Run `tar -xvf postman-linux-x64.tar.gz` (but check if you need to change the filename)
1. Run `sudo apt install libnss3`

##### Create the shortcut file
1. Run `mkdir ~/.local/share/applications`
1. Open a text editor.
1. Add the following text, making sure to change the YOURUSERNAME to your actual username. (use `pwd` to find out how it’s actually spelled)
```
 [Desktop Entry]
 Encoding=UTF-8
 Name=Postman
 Exec=/home/**YOURUSERNAME**/Postman/app/Postman %U
 Icon=/home/**YOURUSERNAME**/Postman/app/resources/app/assets/icon.png
 Terminal=false
 Type=Application
 Categories=Development;
```
1. Save that file with the name Postman.desktop
1. Move that file to the correct folder (the one you created on the 2nd part: ~/.local/share/applications
1. search for Postman it should show up right away


based on : https://community.postman.com/t/installing-the-new-native-app-in-chromeos/5115/8

# What CPU Architecture Do You Have?
```dpkg --print-architecture```


# How to set up a development environment on a macbook
https://www.robinwieruch.de/mac-setup-web-development/





