
# Finanvo Bulk MCA V3 Document Downloader




## Overview

This tool facilitates the seamless download of Bulk MCA V3 documents from Finanvo using Corporate Identification Numbers (CIN) listed in a CSV file. This project aims to simplify and expedite the retrieval process, enhancing efficiency in managing and accessing crucial financial documents.
## Features

- Efficiency: Download multiple V3 documents effortlessly.
- User-friendly: Intuitive CSV input for easy CIN management.
- Time-saving: Automate the retrieval process for enhanced productivity.


## How to use

1. Download a file named "V3Docs.zip".
2. Unzip the downloaded file.
3. Open a file called "userdata.json" and replace the placeholders for Useremail and Userpassword with your Finanvo credentials. Save the changes and close the file.
4. Open a file named "ToDownloadCINV3Docs.csv" and add CIN (Corporate Identification Number) values to the "CIN" column. Save the changes and close the file.
5. Install Python and the Pandas library on your computer, and make sure to set the installation path.
6. Navigate to the folder where the Python script (MainProgram.py) is located.
7. Open the command prompt in that folder by typing "cmd" in the address bar.
8. In the command prompt, type the following command:
       # python MainProgram.py
10. This command will initiate the downloading process using the CIN numbers from the CSV file.


## Dependencies

Python 3.x
Requests library
## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.
