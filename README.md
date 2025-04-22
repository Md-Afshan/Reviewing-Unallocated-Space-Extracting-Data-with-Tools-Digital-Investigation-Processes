# LAB-05 Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
<BR>

#### Command 1
```bash
lsblk
```
#### Command 2
```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
#### Command 3
```bash
mmls ~/disk.img
```
#### Command 4
```bash
sudo ls -lh disk.img
```
#### Command 5
```bash
strings disk.img | less

```

## OUTPUT:
#### Command 1

![alt text](<Lab5 Img1.png>)
#### Command 2

![alt text](<Lab5 Img2.png>)
#### Command 3

![alt text](<Lab5 Img3.png>)
#### Command 4

![alt text](<Lab5 Img4.png>)
#### Command 5

![alt text](<Lab5 Img5.png>)
## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
