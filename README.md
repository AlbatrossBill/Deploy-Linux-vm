# Building Linux system on VM / windows10 x64

## My Hardware

**System**        Windows10 x64

**CPU**	          Intel(R) Core(TM) i5-6500 CPU @ 3.20GHz 3.20 GHz

**GPU** NVIDIA    GeForce GTX 1060 6GB Zotac

**Motherboard**   ASUSTek H110M-A/DP Intel H1108GB 

**Memory**        Kingston DDR4-2400(1200MHz) 8GB * 2

**SSD**           ADATA SP550 223GB & WDC 931 GB

As you can see my hardware is kind of 'worn-out', but install an linux enviorment on my VM is still work pretty well. So don't worry about your device, it can't cause big problem, unless you can't split 2GB Ram/Memory or 2 cores from CPU or about 20-50GB capacity of hard drive to the Linux system. Will...If this is really happened. I have two ways for you. One is endure the lag from vm, one is update your hardware(Please do this, now is 20 Century, Ryzen and Intel not expensive, also Memory as well. If you don't have 50GB empty capacity in your ssd, please..please, look out side the window, there is a really and great world.)

# First step: 
Download Ubuntu or any other iso(Fedora，Centos，OpenSUSE, etc..). Because of Ubuntu is the kindest to nooby. So I will introduce it base on Ubuntu.
```
https://www.ubuntu.com/download/desktop
```
# Second step:
Download VMware, it is the software that can activite the VM. Please look careful, click the right bottom, download the right file.
```
https://www.vmware.com/ca/products/workstation-player/workstation-player-evaluation.html
```
![image](https://user-images.githubusercontent.com/78173335/132923148-46b0bc63-7f41-4dc9-a955-f2fe4ac02612.png)

Now you have both and all things that can accomplish your goal.

# Third step:
Set up your VM. 
Click the bottom in the red circle.(My system language is not Enhlish, but not a big deal, you can just follow the image)

![image](https://user-images.githubusercontent.com/78173335/132923525-85c8340a-2224-4e3d-922f-b70c221211d8.png)

![image](https://user-images.githubusercontent.com/78173335/132923668-0c9cae3e-fc85-4db9-977b-3f485e763259.png)
Choose your Ubuntu .iso file which you just download.

![image](https://user-images.githubusercontent.com/78173335/132923853-21823b99-641e-4978-9dd9-4e7f49326558.png)
DIY your Linux login information, you know what is that mean.

![image](https://user-images.githubusercontent.com/78173335/132923968-66153e70-0021-45df-aed5-15c6bb44e62f.png)
Then the name of your VM, and install location.

![image](https://user-images.githubusercontent.com/78173335/132924162-04662e2a-e120-483b-b461-67bbc16460c6.png)
Between 20-50GB will be ok. But you know, larger is better.

The hardware setting, I personally recommend set it in this way, it can be occupied less resources of your computer and work well.

Memory
![image](https://user-images.githubusercontent.com/78173335/132924361-d100ede4-5db2-4510-9817-0298cf757bd3.png)

CPU
![image](https://user-images.githubusercontent.com/78173335/132924406-a9a401fc-9ade-4f0b-a9a1-8e61b35f5703.png)

Internet adapter
![image](https://user-images.githubusercontent.com/78173335/132924490-78ad1a41-cebc-4aa1-be12-cd0965e4e52b.png)

Others you can just use default setting will be good.

# Final step:
Test!! Run the VMware Workstation 16 Player

Run your vm on your Ubuntu Linux enviorment that you just created for testing. 
When you seeing this(By the way the username and background might be different, please don't care about that, because I am doing it in my place)
![image](https://user-images.githubusercontent.com/78173335/132924708-ec567e40-d93c-411d-9d3a-2b9669dc14f3.png)
![image](https://user-images.githubusercontent.com/78173335/132924799-4c8a8351-214c-4fc9-9fcc-83ab9fb745d9.png)

Congratulation!!! You successfully install the Linux enviorment in your VM. You can start to download application and using it. 

Have fun :)
