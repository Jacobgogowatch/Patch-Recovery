# Patch-Recovery
This CI service patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://github.com/phhusson/samsung-galaxy-a51-gsi-boot)

# How to use:
- Fork this repo.
- Upload your recovery to https://www.filesend.jp/l/en-US/ or any other file hosting sites. Once uploaded right click on the Download button and copy the URL
- Head over to Actions tab. Click on RECOVERY and then Run workflow. Insert the copied URL in the RECOVERY URL field and Start the workflow
- The Patching process will start
- A Patched-Recovery.zip will be uploaded at the end of the process. Download it and extract your patched recovery image
![](https://s3.bmp.ovh/imgs/2022/04/19/91ef3a3ee9255e9c.png)

# Credits
- [Phhusson](https://github.com/phhusson) Without his script nothing would be possible at the first place
- [James Nguyen](https://github.com/thongass000) Helping me in simplifying the scripts and tweaking it
