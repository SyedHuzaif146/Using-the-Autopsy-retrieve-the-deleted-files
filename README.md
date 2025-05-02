# Using-the-Autopsy-retrieve-the-deleted-files
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![image](https://github.com/user-attachments/assets/e9f6588b-7aac-44c2-8816-9ef2e95f93c7)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/e35ed940-df40-49bb-b746-afae0016ecf9)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/60d0fa98-996f-4ab9-be9c-94c8abe657e0)


- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/f88471d4-d38c-4833-b3ee-f24d193b7c49)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/f19e85f7-32b7-499a-963c-a3c3aa1ee083)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
![image](https://github.com/user-attachments/assets/f72ae3af-73b8-4514-8022-d181629815d6)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
![image](https://github.com/user-attachments/assets/c7f5a958-222c-4f87-b341-b25e6d28656c)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![image](https://github.com/user-attachments/assets/d43c3ed6-533c-44be-95dd-f48ecbc40be2)

### Folder after deleting the files
![image](https://github.com/user-attachments/assets/6b983bc7-3e78-4d29-97df-e5b172c80fc8)

### Folder after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/e3229720-002a-49c6-bc27-303185f4a02e)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
