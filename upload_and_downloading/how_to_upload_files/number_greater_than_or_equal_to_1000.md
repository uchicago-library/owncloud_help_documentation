# Introduction

If you need to upload 1000 or more files, it's recommended that you use the WebDAV server available at

- https://s3.lib.uchicago.edu/owncloud/remote.php/webdav/

## Windows 7 Configuration

1. Download [WinSCP](https://winscp.net/eng/download.php)
1. Click to install WinSCP
1. Open WinSCP
1. Click on New Site option
1. Fill in the form with the following information
    - Host name should be the url aboe
    - Port should 22
    - User name should be your ownCloud username
    - Password should be the password you use to login to ownCloud

## Windows 10 Configuration

1. Open the File Explorer
1. Click on the Quick Action labelled "This PC"
1. Click on the Computer ribbon
1. Click on "Map a network drive"
1. Enter the url above in the input field labelled Folder
1. Click to select Connect using different credentials
1. Make sure Reconnect on login is selected
1. Click on the Finish button

## How to upload files

When you are connected to the ownCloud WebDAV, navigate to the folder that you want to put the new files in. If you want to create a new folder, right-click in the folder and select New folder and create one. 

Once you are in the folder that you want to put new files, click-and-drag the files from the old location to the location on WebDAV.

Wait until the upload is complete. As files are uploaded they will appear in the web interface.
