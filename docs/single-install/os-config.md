# OS Configuration
Login to the web GUI through the IP address of server machine. Use the username and password that was just recently entered.

## Network Configuration

## Storage Configuration
https://www.truenas.com/docs/hub/initial-setup/storage/

**Keypoints**
- Make sure that the disks are all the same size otherwise you wouldn't get the maximum capacity out of each disk. Sometime it is better to just create separate vdisk if the sizes are not all them same to maximize capacity.
- Make sure there's a between redundancy and storage space. There should be at least a one drive fault tolerance for every 5 drives.
- Add SSD's as cache drives in order to speed up read and write time.
- Drives should be encrypted and keys should be stored in a safe and secure location.
- You can setup email alerts when drives fail, so that they can be replaced through physical means. Software-based automatic replacement is an available when setting up the pools.
