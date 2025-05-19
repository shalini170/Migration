# EX 6: MOVING FILES BETWEEN VIRTUAL MACHINES
# NAME: shalini venkatesulu
# REG NO: 212223220104
# Aim:
To move the files between virtual machine. You can move files between virtual machines in several ways: • You can copy files using network utilities as you would between physical computers on your network. To do this between two virtual machine: • Both virtual machines must be configured to allow access to your network. • Any of the networking methods (host-only, bridged and NAT) are appropriate. • With host-only networking, you copy files from the virtual machines to the host and vice-versa, since host-only networking only allows the virtual machines see your host computer. • With bridged networking or NAT enabled, you can copy files across your network between the virtual machines. • You can create a shared drive, either a virtual disk or a raw partition, and mount the drive in each of the virtual machines.

# Procedure:
How to Enable File sharing in VirtualBox.
# Step 1. Install Guest Additions on the Guest machine. Step 2. Configure File Sharing on VirtualBox.

# Step 1. Install Guest Additions on the Guest machine.

1.Start the Virtuabox Guest Machine (OS).
2.From Oracle's VM VirtualBox main menu, select Devices > Install Guest Additions *
a. Open Windows Explorer b. Double click at the "CD Drive (X:) VirtualBox Guest additions" to explore its contents.
![image](https://github.com/user-attachments/assets/bc38f710-601b-4219-a813-6ac3bcd8c2d5)

C.Right click at "VBoxWindowsAdditions" application and from the pop-up menu, choose "Run as administrator".

![image](https://github.com/user-attachments/assets/8ba89b90-3138-4a8f-9992-52419bb22e8a)

3.Press Next and then follow the on screen instructions to complete the Guest Additions installation.

![image](https://github.com/user-attachments/assets/dec2d664-d62e-4e40-9cc8-216025d0281a)

4. When the setup is completed, choose Finish and restart the Virtuabox guest machine. Step 2. Setup File Sharing on VirtualBox Guest Machine.

5. From VirtualBox menu click Devices and choose Shared Folders -> Shared Folder Settings.

6. ![image](https://github.com/user-attachments/assets/342ad016-b81f-464c-a54d-5d31a2a6f19b)

2.Click the Add new shared folder icon.
![image](https://github.com/user-attachments/assets/6412b7ce-86b6-4182-bfa8-bed5fda0563c)

3.Click the drop-down arrow and select Other.

![image](https://github.com/user-attachments/assets/66f8f1ac-f2b7-4ff6-8cd5-115b51f88915

Locate and highlight (from the Host OS) the folder that you want to share between the VirtualBox Guest machine and the Host and click Select Folder. *
Note: To make your life easier, create a new folder for the file sharing, on the Host OS and give it with a recognizable name. (e.g. "Public")

![image](https://github.com/user-attachments/assets/e6636806-7460-45a3-9fec-e5302265639d)

4.Now, in the 'Add Share' options, type a name (if you want) at the 'Folder Name box, click the Auto Mount and the Make Permanent checkboxes and click OK twice to close the Shared Folder Settings.

![image](https://github.com/user-attachments/assets/e743729c-8394-447f-86d9-e06177afe9b7)

5. You 're done! To access the shared folder from the Guest OS, open Windows Explorer and under the 'Network locations' you should see a new network drive that corresponds to the shared folder on the Host OS.
## Result:
Thus the virtual machine files are moved to another VM.



