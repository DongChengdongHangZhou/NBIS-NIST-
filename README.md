# NBIS-(NIST)
How to download and compile the NBIS fingerprint system including bozorth3, mindtct, nfiq etc.

## Download 
Find the software in the page https://www.nist.gov/itl/iad/image-group/products-and-services/image-group-open-source-server-nigos  

Then open the Users's Guide to NIST Biometric Image Software https://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir7392.pdf

## Install
Follow the instructions in the book (page 5) https://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir7392.pdf

  1. sh setup.sh <FINAL INSTALLATION DIR> [--without-X11]
  2. make config
  3. make it
  4. make install
  5. make catalog
  
It is recommended to add --without-X11. I fail to compile this project when --without-X11 is not added.  

## Use
Enter the <FINAL INSTALLATION DIR> and find the ./bin folder. Then use the programmes in this folder.
  
# NFIQ2
The softwares provided in NBIS-NIST only contain NFIQ1. If you want to use NFIQ2, please refer to https://github.com/usnistgov/NFIQ2 
  
and the compiled files can be found in the Releases: https://github.com/usnistgov/NFIQ2/releases
