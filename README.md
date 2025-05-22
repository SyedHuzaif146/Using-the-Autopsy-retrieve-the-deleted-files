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


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**


![dfdi3](https://github.com/user-attachments/assets/934da0c2-6fc6-4166-937d-78fce3c18617)


- Select **Local Disk** → **next**
- ![dfdi4](https://github.com/user-attachments/assets/d9589646-8c79-45bc-8d3c-0953af07d3f1)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![dfdi5](https://github.com/user-attachments/assets/6e8a0655-b707-491a-902e-c4908d96bc01)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).
- ![a6](https://github.com/user-attachments/assets/f7063263-697f-485f-ad92-ccb0e8a17552)
- ![image](https://github.com/user-attachments/assets/d41a0934-c3ff-4c7a-8a72-901f68c45ea6)



- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  



- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.
![image](https://github.com/user-attachments/assets/23e4b226-b6e5-409b-af45-ef8094c908a5)




## OUTPUT:
## Folder before deleting the files
![image](https://github.com/user-attachments/assets/bf1668bb-f665-4bea-a45f-fdcf31f29168)

## Foldet after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/bcbc6cfc-aa33-486e-906e-be4e9546c4cc)



## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
