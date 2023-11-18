# Increasing disk size


Before
!["Filled disk size"](./Fedora-Images/insufficient%20space.jpg "Fiiled disk screenshot")

Steps
1. Backup Your Data
Before making any changes, it's crucial to back up your data to prevent data loss in case of unforeseen issues.

On Your Virtual Box, navigate to your fedora VM whose size needs to be increased. 
!["Fedora"](./Fedora-Images/fedora.png "fedora")



On the files menu, navigate to Tools -->Vitaul Media Manager
!["navigate"](./Fedora-Images/File-tools-.png "navigate")

On the vitual media manager window, I looked for my fedora VM vdi image and increased the disk space from 15G to 45G.  

![""increasing size](./Fedora-Images/increasing_size.png "increasing size")

I started my VM, and on typing the command df -H to check for disk size, it was still the same

!["df -H"](./Fedora-Images/df%20-%20H%20before.PNG "df -H before")

I installed growpart tool to grow my parttion 3
!["installi growpart"](./Fedora-Images/grow%20part.PNG "growpart")

!["growing the root partion"](./Fedora-Images/grow-part.PNG "growpart")