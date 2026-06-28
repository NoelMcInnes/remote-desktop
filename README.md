# Creating a New Virtual Machine in Azure

Learn how to provision a new Windows 11 virtual machine within the Azure portal. This guide walks you through the necessary configuration steps, from selecting your machine group and region to choosing the appropriate hardware size.


(https://scribehow.com/o/3v683_BfRmGDvX240ciALg/viewer/Creating_a_New_Virtual_Machine_in_Azure__v1F0nCDGS3Gy1Qa_0G2O3A)

#### Portal Navigation


1\. Navigate to "Virtual machines" in the Azure portal sidebar.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/4d3d9d9c-de5f-406c-a36e-682a407d5d3c/ascreenshot_02847d64f7ad4685a84e3dfb5c411fac_text_export.jpeg)


2\. Click "Create".

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/12992d61-2130-4982-ba0f-e9bad00ad521/ascreenshot_3aec0c139bd145328804e5ec3d742340_text_export.jpeg)


3\. Select "Virtual machine" from the dropdown menu.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/bc7c26c0-9872-4f4e-aebf-892886aa6c37/ascreenshot_c89359fafcbc4222a977247aaf5127ad_text_export.jpeg)


#### Resource Group Setup


4\. Create a new resource group and name it "diffcomp-vm_group".

Throughout the entire lesson, we will use this VM as a **diff**erent **comp**uter that we will access remotely.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/5980c744-fb33-42cf-884e-907af7a18cc9/ascreenshot_1545680bf6ba40858fee7c1247919296_text_export.jpeg)


#### Instance Configuration


5\. Name the virtual machine, "diffcomp-vm"

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/0fded408-ee11-4e68-acd6-b9ba2cee9eb3/ascreenshot_df39521afa7642148d04cc50c1ecffbb_text_export.jpeg)


6\. Under Region, click "(US) East US 2"

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/5debd335-fdaa-4cd1-a0b3-98a4d909d993/ascreenshot_4a11764f998e47c3ba537dccad777f6e_text_export.jpeg)


7\. Under Image, click "Windows 11 Pro, version 25H2 - x64 Gen2"

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/67555e8e-4fc2-4a8c-be4f-73b12dc52fe9/ascreenshot_1ebf33f86d754e6b83fa6e07bd5b4a2b_text_export.jpeg)


8\. Under size, click "Standard_D2ds_v7 - 2 vcpus, 8 GiB memory ($118.99)"

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/bea717d4-170d-42a5-bb47-7bddc31391fb/ascreenshot_e1d2762644e44f468122664039406739_text_export.jpeg)


#### Administrator Credentials


9\. Make "labuser" the admin username

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/0033b24d-3ae1-4b9d-a05a-0efed1f29799/ascreenshot_4038b3b2adf64a9ca2d313a87e1a96fe_text_export.jpeg)


10\. Create a password for the admin account. For this lab, let's keep it simple. Our password will be Coursecareers1!

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/1c665c10-c7c4-4c06-8d07-dab1b17fc6b0/ascreenshot_5956dbe541134e80852f094f6d28079e_text_export.jpeg)


11\. Check the licensing confirmation box for Windows 10/11 hosting rights.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/bbd0d176-ffb6-4275-9ada-2db007dbc06b/ascreenshot_586fbf04bbe6415c87c1bb6308ffa233_text_export.jpeg)


#### Review and Deployment


12\. Click "Next : Disks >" to continue.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/e7519c65-52d9-4261-ad3a-580683a5fc11/ascreenshot_92641c8e23c147ee910f5b0c89726896_text_export.jpeg)


13\. Click "Next : Networking >" to proceed.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/1290f831-730f-44ed-a473-b83e00a61da3/ascreenshot_c8f75e1eba734821aa7e46619be3a090_text_export.jpeg)


14\. Click "Review + create" to validate your settings.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/251f5095-47ae-42e7-82bd-1713909cf571/ascreenshot_36fa39157a6d4209a64a933b601a5b1f_text_export.jpeg)


15\. Click "Create" to provision the virtual machine.

![](https://colony-recorder.s3.amazonaws.com/files/2026-06-28/df463834-af32-4023-a0d1-a76babfd6259/ascreenshot_fb3dbc9c3a98405b8f7744ae5789c719_text_export.jpeg)
