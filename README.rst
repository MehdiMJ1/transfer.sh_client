=====================
transfer.sh-uploader
=====================

Python client for uploading files to transfer.sh (https://transfer.sh)

============
Usage:
============
 - Start script::

     transfer_files

 - Enter directory, which files you want to upload (as a parameter, or interactively)::

    transfer_files ./ 

 - After download link received and copied to clipboard automatically, confirm weather keep files in directory or delete them(or to delete just the created archive)::

    Delete files in the directory?(y/n, Y/N, archive):
 - Share created download link where ever you want!

============
Download
============
::

  pip3 install transfersh_client

==================
Requirements
==================
 - pyperclip
 - requests

==================
Sample output
==================
::

  transfer.sh-uploader|master⚡ ⇒ transfer_files ./                                     
  Creating zipfile from files in... ./
  Added file:  README.md
  Added file:  .idea
  Added file:  requirements.txt
  Added file:  transfer_file.py
  Added file:  .git
  Added file:  LICENSE
  
  Sending zipfile:  files_archive_08-28_15:22.zip   
   Link to download zipfile:
  https://transfer.sh/eoqSx/files_archive_08-28_15:22.zip
   
   Delete files in the directory?(y/n, Y/N, archive): n
   OK, files will be there
