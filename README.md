# CloudComputing-exam2
Second exam of Cloud Computing at National University of Mexico (2022-2)

Karime Ochoa Jacinto karime8aj@gmail.com

GNU/GPL License 3.0
## Exercise description 
Implement the command:

**[Mb, time_up, time_download] = pingmb -n <Mb> -ip <dst>**
  
  Where:
  * Mb = File size in Mb 
  * dst = IP destination
  
  Then test it for two interfaces (10.99.1.138 and 132.247.186.67)from 92.168.0.200 since 1Mb, 10Mb, 20Mb,... until 100Mb (in 10Mb steps).
  
  Finally plot size vs. time for upload and download for each interface.

 ## Metodology
  1) Exchange keys between web and storage servers.
  2) Copy the file into the public directory in the web server.
  3) Use wget and scp for the data upload and download.
  4) Create a GitHub repository.
  
