# Linux SystemD service for mounting Onedrive with Rclone
Setup and configure an rclone remote for your cloud storage solution: https://rclone.org/onedrive/

Add new folder locally to mount remote: 
mkdir /home/USERNAME/mnt && mkdir /home/USER/mnt/OneDrive

Create system file in /etc/systemd/system/Rclone-OneDrive.service
touch /etc/systemd/system/Rclone-OneDrive.service

And configure the system service to suit.

Configure systemctl to start the mount as needed.
