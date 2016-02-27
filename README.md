# Cloud-Storage-EncryptionDecryption
Cloud storage Encryption/Decryption

Description

Sync Secure Application lets users upload files to Drop box and Google Drive. To secure the files uploaded, the application uses the AES public key encryption algorithm to encrypt the files before uploading. A digital signature is used to digitally sign the files. The files can be decrypted and downloaded only by running the application and providing the correct password entered while uploading the file. The following files can be encrypted: .pdf, .txt, .mp3, .jpg
The application lets the user choose between four options:

a) Upload to DropBox: Encrypts and uploads the file to DropBox 
b) Download from DropBox to Local: Downloads the file from DropBox to the local machine and decrypts it 
c) Upload to Google Drive: Encrypts and uploads the file to Google Drive 
d) Sync with Google Drive and Dropbox: Encrypts and syncs the file between Google Drive and Dropbox 

Procedure to run the application on an other machine

a) Download and install the required python packages including the pycrypto module. 
b) Download and install the Drop Box and the Google Drive APIs 
c) Get the App Key, secret and access token for DropBox 
d) Get the Client ID and Secret for Google Drive 
e) Create a folder on the local machine 
f) Create a .py file in the same folder and copy paste the code (Code At the end of this document) 
g) Update the App key, Client ID, access token and Secret in the code. 
h) Run the program in IDLE, MAC terminal or in the windows command prompt. 
i) When asked for the filename, give the filename of a file which is in the same folder as the .py file. 

REFERENCES
https://pypi.python.org/pypi/pycrypto https://console.developers.google.com https://www.dropbox.com/developers https://docs.python.org/ http://en.wikipedia.org/wiki/Block_cipher_mode_of_operation https://www.youtube.com/watch?v=lSrrhP2vFS8- 1 (Sumanth Pikkili - 1001100941)
