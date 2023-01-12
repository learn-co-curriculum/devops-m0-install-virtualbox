# Setup

If on a 64-bit processor (Windows, Intel Macs, Linux), follow this guide.

## Ubuntu image

Before we get started, we need to download the **Ubuntu Server** image, which contains the installer. You can [download it here](https://ubuntu.com/download/server).

## VirtualBox

**VirtualBox** is the *Hypervisor* we will be using in this course to create and run our Linux virtual machine.

You can [download VirtualBox here](https://www.virtualbox.org/). Once downloaded, install it.

Once installed, go ahead and open the `VirtualBox Manager`. You should be greeted by screen similar to:

![VirtualBox Manager](./virtualbox-manager.png)

Now we are ready to create our virtual machine! Click the `New` button or go to `Machine -> New` to begin the new machine wizard.

First thing it will ask is for some general information; fill it as follows:

- **Name**: This can be whatever you want. Just *Ubuntu* works fine.
- **ISO Image**: This is the **Ubuntu Server** image we downloaded earlier. Click the dropdown arrow and hit `Other...` to browse to the image file.

The rest can be left at its default values; hit next to continue.

The next page will ask information relating to how much hardware we wish to allocate on our guest machine. This varies depending on your system:

- **Base Memory**: This is how much RAM you wish to allocate; try to allocate at least 4 gigabytes of RAM.
- **Processors**: How many dedicated CPU threads we wish to allocate. As a rule-of-thumb, set this to 1/2 of your available threads.

Both of these settings can be changed afterwards, so if your host computer slows down too much, feel free to tweak them for better performance.

Going onto the next page, we get to set how much storage space we wish our guest machine can utilize. Set the `Disk Size` to 22 GB and hit next.

Review the settings, and click `Finish` to finalize the setup.

We are now ready to run our virtual machine and install **Ubuntu Server** on it! In order to launch, simply right-click the VM and click `Start`.
