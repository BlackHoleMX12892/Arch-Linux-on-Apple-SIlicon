# 02 - Creating the VM
This chapter will focus on the creation of the machine inside of UTM.

> You can skip this section if you are using another virtualization software or have experience setting up virtual machines, make sure to use aarch64 and the alpine iso.

---

![UTM Hypervisor](../.github/assets/1.png)
> To get started click "Create a New Virtual Machine"

![Create a New Virtual Machine](../.github/assets/2.png)
> Then select Virtualize, as we are using the host arquitecture.

![Platform Selection](../.github/assets/3.png)
> Choose Linux.

![Resources](../.github/assets/4.png)
> I gave the machine 4 Gb of memory, 4 cores, and enabled hardware OpenGL acceleration.

![ISO Image](../.github/assets/5.png)
> Select the Alpine Live ISO as the boot image.

Don't add a shared folder for now and create the virtual disk, give the VM a name and complete the creation.

You have succesfully created the machine, now it's time to boot.