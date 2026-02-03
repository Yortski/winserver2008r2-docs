# **VirtualBox Setup**
!!! note
    I am using VirtualBox v7.1. Older or newer version of VirtualBox may have different steps or interface.

![virtualboxdbsetup1](images/insta1.png)

From the interface above, click **New** and when a window pops up, set these configurations. You may tinker with more or less values depending on the capability of your machine

---

- ### **VM Configurations**
If a field was not mentioned, keep it as default.

    - **VM Name:** ```Windows Server 2008 R2```
    - **VM Folder:** (Choose your own)
    - **Base Memory:** ```4096 MB```
    - **Number of CPUs:** ```4```
    - **Disk Size**: ```32.00Gb``` (This is default value, you may change according to your machine's capabilities)

    !!! warning
        Giving these settings with less values may cause longer wait time during installation and slower performance of the machine. 
        
        Be careful though, larger values may be faster but can torture your machine.

        My Suggestion, stay within the green area

    ![virtualboxdbsetup2](images/insta2.png)
    ![virtualboxdbsetup3](images/insta3.png)
    ![virtualboxdbsetup4](images/insta4.png)

---

- ### **Attach the Disk**
After completing the Virtual Machine's config by clicking **```Finish```**, Select the machine we have just created and then click Settings.

    ![virtualboxdbsetup5](images/insta5.png)

    Make sure you are on **```Expert```** or **```Advanced```** mode then click Storage Tab.

    Then under devices, click the **```empty disk```**, the side panel on the right should change.

    Right at the Optical Drive attribute, click the disk icon then select **```Choose a Disk File...```**

    After that navigate to the folder where your **```Windows Server 2008 R2.iso```** is located and select it.

    ![virtualboxdbsetup6](images/insta6.png)

    Complete the process by clicking **```OK```**

---

<center>
SETUP COMPLETE - You may now start the machine.
</center>

---