
For users facing ISP throttling and they can't afford a VPN, Google Colab offers internet speeds ranging from 2 to 10 Mbps. I suggest uploading your files to a university drive and then downloading them again. This workaround can effectively bypass torrent blocking and mitigate the impact of ISP throttling.













Download and Upload Torrent Game to Google Drive using Google Colab
This Python script allows you to download a torrent game using its magnet link or torrent file and upload it to Google Drive using Google Colab. The script utilizes the libtorrent library to handle torrent downloads and integrates with Google Colab for cloud-based execution.






Features:
Downloads torrent files or magnet links provided by the user.
Utilizes libtorrent for efficient handling of torrent downloads.
Uploads the downloaded game to Google Drive for cloud storage.




#For v1.0.1

Just upload the .ipynb file to Google Colab and run all the cells. Afterward, you will find your folder in your Google Drive.

##Features:
Fast and easy to use.
##Drawbacks:
1-Issues encountered while downloading.
2-Errors during the download process may result in resetting progress to zero.
3- when the an erro happen during the dowlaod it return to 0 



#for the v2

## Table of Contents

- [Setup](#setup)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Setup

1. **Install Google Drive for Desktop:** [Download Link](https://www.google.com/drive/download/)
2. **Create a Folder:** Create a folder on your desktop named "torrent."
3. **Add to Google Drive:**
   ![Screenshot](https://github.com/AzizBahloul/Download-and-upload-a-torrent-game-to-Google-Drive-using-Google-Colab/assets/74460680/09b59c1e-e01e-4415-96cb-30ecf94a8fa0)
4. **Syncing Options:**
   ![Screenshot](https://github.com/AzizBahloul/Download-and-upload-a-torrent-game-to-Google-Drive-using-Google-Colab/assets/74460680/6306a35e-ea14-4637-a48a-888a0acec0ac)
5. **Set Sync Destination:** Point syncing to the "torrent" folder on your desktop.
6. **Upload and Connect:** Upload `torrentv2.ipynb` to Google Colab and connect with your Google Drive account.

Now, the torrent will automatically download to your computer.


