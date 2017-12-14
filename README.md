This is a simple python scripts which creates a compressed file of a directory using the gzip compression ratio.

After compression is done,file is  uploaded to an FTP server using the current date.

This script uses the ftplib,os,datetime,sys and tarfile modules.

The script was tested the pure-ftpd server and Microsoft FTP server.Other FTP servers should work as well.

This was tested using python 3.5 and 2.7 but should work on most versions.

All suggestions and comments which will make the script better are welcome.
