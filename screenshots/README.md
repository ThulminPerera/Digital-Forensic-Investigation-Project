Steps of your investigation process

Phase 1 – Suspected machine creation for the investigation 

First, we set up a virtual machine (Windows 7/10) with a 50GB hard disk. The disk was divided into two partitions: 40 GB – C, 10 GB – E. Inside D, I have created a folder named with our EID, downloaded some images into it, and then permanently deleted the folder. This step simulates real user activity and prepares deleted data for recovery.


•	Creation of suspect virtual machine (Windows 10)

 <img width="854" height="513" alt="image" src="https://github.com/user-attachments/assets/000354c0-022a-4957-b611-0c46cebcab3d" />



•	Pre-allocation of 50 GB
<img width="862" height="525" alt="image" src="https://github.com/user-attachments/assets/4152a7fb-bd17-47f2-bee7-0f6b51e98fc0" />

 

•	Installation of virtual machine

 <img width="876" height="657" alt="image" src="https://github.com/user-attachments/assets/015f588a-c5ad-4c00-8f9d-3a73c1ed8a42" />


•	Partition of HD (40 GB – C, 10 GB – E)

 <img width="904" height="442" alt="image" src="https://github.com/user-attachments/assets/8e136e26-34cf-4a5b-970c-a28d1792744a" />



•	Creation of folder relevant to my EID – 252226

 <img width="890" height="435" alt="image" src="https://github.com/user-attachments/assets/d6b45b9e-7830-43b9-98c2-7e4eeb852697" />


•	Downloading images using the internet browser and moving them to the relevant folder 
<img width="902" height="441" alt="image" src="https://github.com/user-attachments/assets/6b5a2b12-607c-4325-9927-2e9a945e61a2" />

 <img width="895" height="438" alt="image" src="https://github.com/user-attachments/assets/ee23ac31-3df5-4bb6-bffe-93e06bff5eca" />


 


Downloaded images moved into the folder -
 
<img width="893" height="436" alt="image" src="https://github.com/user-attachments/assets/13838901-6f6b-424a-a184-a56673a57456" />


•	Deleting images permanently. (Folder – E252226)
<img width="898" height="439" alt="image" src="https://github.com/user-attachments/assets/a2e97a11-cc65-432f-993a-f03976ee731c" />

 


•	After doing this the virtual machine should shut down 

According to Phase I, I created a suspected virtual machine and installed a fresh operating system to simulate a target environment for forensic investigation. Using the web browser, I visited multiple websites and downloaded several images, which were then moved into a single folder that I renamed with my EID for identification purposes. To simulate evidence tampering, I permanently deleted the images from the folder and ensured they were removed from the system, before finally shutting down the virtual machine. This process generated realistic user activity and artifacts, such as browsing history, cached data, and deleted file traces, which could later be recovered and analyzed using forensic tools. The screenshots provided serve as proof of each stage and demonstrate how forensic investigators can recreate, document, and later examine digital evidence in a controlled environment.

Phase 11 - Forensic workstation creation for the investigation and conducting the investigation.

Next, we should install and opened FTK Imager and added the virtual disk as an evidence item. This allowed us to preview the disk contents and confirm that the deleted items were still present on the drive. This preview is important before creating a forensic image.

Installing FTK Imager

 <img width="774" height="618" alt="image" src="https://github.com/user-attachments/assets/aac72da7-641a-4bd7-96e0-705b508f68f3" />


•	FTK Imager Interface 

<img width="857" height="397" alt="image" src="https://github.com/user-attachments/assets/260cde11-5581-4adc-b4f5-0ca5b6e97e2d" />
 

•	Adding evidence item

<img width="851" height="393" alt="image" src="https://github.com/user-attachments/assets/a118d769-7b5f-444f-9274-c604bb31610c" />


•	Loading the .vdi file into the FTK Imager 

 <img width="901" height="507" alt="image" src="https://github.com/user-attachments/assets/e72e70dd-16c2-4814-a8b9-210fc2ead00c" />



•	Creation of new Disk Image 

 <img width="874" height="640" alt="image" src="https://github.com/user-attachments/assets/6483dfa4-fee2-4f6d-a9cc-2a18df77e143" />


•	Giving the Source path of .vdi
 <img width="800" height="760" alt="image" src="https://github.com/user-attachments/assets/f2c7e2a9-282c-43bf-ab78-bb107f087c00" />


 

•	By Clicking Add giving .E01 Image type 

 <img width="975" height="525" alt="image" src="https://github.com/user-attachments/assets/5934d45a-f807-49e9-8d29-9f8c39efea7a" />


•	Filling case no. and the relevant details

 <img width="799" height="617" alt="image" src="https://github.com/user-attachments/assets/f1cc5374-938c-4451-b28e-829c82c856fc" />


•	Browse and give the Image destination folder (Analysis folder Created) and make the Fragment – 0 and Compression – 6

 <img width="975" height="588" alt="image" src="https://github.com/user-attachments/assets/013df916-959c-4bf6-aa32-0238f69edcc9" />


•	Click Finish after giving them 

 <img width="693" height="557" alt="image" src="https://github.com/user-attachments/assets/0f320859-9fad-4f5f-99c7-8455c8699970" />


•	It starts to create the Images 

 
<img width="488" height="441" alt="image" src="https://github.com/user-attachments/assets/e606537a-0f28-4940-94da-34746bdd1062" />
<img width="581" height="453" alt="image" src="https://github.com/user-attachments/assets/925fb8a6-4429-4976-9c64-9cc920971bc0" />

 

 

•	Final Output (Image Summary)
<img width="975" height="519" alt="image" src="https://github.com/user-attachments/assets/b74b18e7-4bae-40c6-9432-a29d273716d8" />


•	Deleted Image recovery Output results 

 <img width="916" height="614" alt="image" src="https://github.com/user-attachments/assets/4a547e1f-e477-4599-8e8f-e2ab795abbc3" />
<img width="920" height="597" alt="image" src="https://github.com/user-attachments/assets/9c2b383c-dc38-4a8c-80b0-2d82d4d130c0" />
<img width="876" height="585" alt="image" src="https://github.com/user-attachments/assets/80111722-fd65-4323-abe7-4b8eed118d32" />
<img width="882" height="652" alt="image" src="https://github.com/user-attachments/assets/61622464-146e-4c26-869e-0bb2171802de" />


 

 

 


After imaging, we used Hash Calc to generate hash values (MD5/SHA1) for the E01 file. These hashes act as digital fingerprints and prove that the image remains unchanged during the investigation. We recorded these values for our report.


Installation of Hash calc

 <img width="792" height="619" alt="image" src="https://github.com/user-attachments/assets/4ac01fb7-d63d-4278-b59a-890421a6b0b1" />


•	Hash calc Interface 
<img width="589" height="807" alt="image" src="https://github.com/user-attachments/assets/f2fc6387-1475-4446-968e-6ff8a906304d" />

 

•	Loading the .E01 file into Hash Calc 
<img width="831" height="1052" alt="image" src="https://github.com/user-attachments/assets/a3015c58-2ffb-4612-8ed5-5b6934798235" />

 



•	Output of Hash Values 
 <img width="747" height="1022" alt="image" src="https://github.com/user-attachments/assets/13c9ae43-8bf1-4b26-8a33-535f88e9e4b0" />


Values 

Hash Calc generated multiple hash values for that file –

•	MD5 - 0d2e5787f3a9396091020bd232c8ba03
•	SHA1 - df9696e73dff0683a07763914f73e7056972503
•	RIPEMD160 - 3e36e28908676308c71d985136918c0e41765252
•	CRC32 - e42b1e0c


In digital forensics, hashing is critical because MD5 and SHA1 values prove the integrity of the evidence. Even a tiny change, such as altering a single bit in the file, will completely change the hash values. This ensures that the evidence has not been tampered with, maintaining the chain of custody and guaranteeing authenticity when presenting it in court or in official documentation.

We then used OSF Mount to mount the E01 file as a read-only disk. The software assigned drive letters to the emulated partitions, making them accessible just like normal drives. This step allows us to run forensic tools directly on the mounted image without altering evidence.

Installation of OSF Mount 
<img width="909" height="734" alt="image" src="https://github.com/user-attachments/assets/dfaacaae-3ac4-4c78-8891-6bc2cd5248c6" />

 

•	OSF Mount Interface 
 <img width="975" height="458" alt="image" src="https://github.com/user-attachments/assets/1b55dac5-ead9-43a2-957b-672a47b98c18" />


•	Selecting Image file .E01 
<img width="872" height="783" alt="image" src="https://github.com/user-attachments/assets/6aa41eb8-cbd3-416e-beb1-571f0596ce74" />

 
•	Select all drives to mount
<img width="928" height="827" alt="image" src="https://github.com/user-attachments/assets/4cba1766-4909-4b3d-ac03-c2cb71db34a9" />

 


•	Select Drive emulation Logical Drive Emulation and set Auto for both Drive type and Drive letter 
 <img width="945" height="849" alt="image" src="https://github.com/user-attachments/assets/dcb3600f-f54e-4324-b4eb-c7a00f536c8a" />



•	Output after mounting 
 
<img width="975" height="480" alt="image" src="https://github.com/user-attachments/assets/d7385dca-d6e8-44b3-b5e1-e48238f4b6f5" />
<img width="975" height="527" alt="image" src="https://github.com/user-attachments/assets/ef9ccd51-6ada-4c59-afc4-0120533e7d6a" />

 

Next, we opened Autopsy as administrator and added the mounted disk as a data source. Autopsy scanned the drive and displayed deleted items. We located the deleted images from our EID folder and exported them to the local PC for further study. This is how we recovered the deleted files.

Installation of Autopsy 

 <img width="918" height="717" alt="image" src="https://github.com/user-attachments/assets/638d4dee-7321-416c-a75a-b1171495089c" />


•	Run as Administrator and select New Case 

 <img width="926" height="492" alt="image" src="https://github.com/user-attachments/assets/e76ccbc4-6207-4833-b661-20a6f633fd70" />


•	Adding the evidence item 

 <img width="975" height="562" alt="image" src="https://github.com/user-attachments/assets/c048c31b-45bf-4c68-bdc4-fcec6fc62213" />
<img width="975" height="574" alt="image" src="https://github.com/user-attachments/assets/fcf394e2-4454-4e5f-9d3b-b6aab19cabc4" />


 

•	Selecting Local Disk 

 <img width="884" height="556" alt="image" src="https://github.com/user-attachments/assets/653f6238-2152-4365-8939-9a005a233f28" />


•	Selecting the relevant emulated (10GB) disk (F)
 <img width="863" height="557" alt="image" src="https://github.com/user-attachments/assets/8a1d40cd-9612-41c9-883f-093d345fc1d4" />


 

•	Loading evidence and the finding the Deleted files 

 <img width="975" height="612" alt="image" src="https://github.com/user-attachments/assets/91bf39eb-edb9-4ed4-ae38-d1fbcbadf089" />


 

 
 
•	From Discovering option loading deleted images 

<img width="882" height="695" alt="image" src="https://github.com/user-attachments/assets/bb119b30-aacf-495a-9988-e71850c29fa4" />

 

•	Outputs found – The deleted Images 

 <img width="975" height="523" alt="image" src="https://github.com/user-attachments/assets/ff0dacd7-76b6-4c43-bc1e-a83d59d48d3b" />
<img width="975" height="516" alt="image" src="https://github.com/user-attachments/assets/38a8f649-2d17-4634-bdd7-7d5e8d36afc3" />


 





•	Exporting Image Folder to the Local PC to Recovery Folder
<img width="875" height="617" alt="image" src="https://github.com/user-attachments/assets/1a7b4053-4b9f-496f-ba27-e67674035ee7" />

 
•	Recovered output results from the Local PC
<img width="916" height="519" alt="image" src="https://github.com/user-attachments/assets/2807b4aa-561e-4cdb-9d64-c9ff05ffce2a" />

 

Next, to support our findings, we ran Browsing History View as administrator. We loaded browser history from the mounted Users folder on the emulated drive. The tool showed the history of downloaded items and websites, which linked to the deleted images, providing useful context about user actions.

Installation of Browsing viewer history 
<img width="975" height="415" alt="image" src="https://github.com/user-attachments/assets/a630df9a-2ca4-4fbf-8217-71078b77eb79" />

 

•	Run as administrator

In here should choose 

•	“Load History items from any time” 
•	 “Load History from specific folder (C:\ users)” 
•	Select the path of 40 GB drive 
<img width="969" height="1066" alt="image" src="https://github.com/user-attachments/assets/7bdc596d-3540-4861-90fa-9af5b8b29f48" />

 


•	Output Browser viewing History 

 <img width="975" height="519" alt="image" src="https://github.com/user-attachments/assets/4ae46d78-292d-4b4d-ae53-752cea634ef6" />


Finally, we used ExifTool on the recovered images to extract metadata such as timestamps, camera details, or software used. This information helped us understand more about the origin and properties of the images, strengthening the evidence analysis.

Installation of Exif tool 
<img width="838" height="471" alt="image" src="https://github.com/user-attachments/assets/58a5b343-06aa-4123-a576-1b7ebddc2899" />

 

•	Copy as path of Exif tool

 <img width="820" height="461" alt="image" src="https://github.com/user-attachments/assets/e8616809-e293-46b4-a00c-e2f531a3b828" />




•	Copy as path of recovered image
<img width="908" height="511" alt="image" src="https://github.com/user-attachments/assets/cd66b746-8fdf-4192-93c7-d9faca53a1c9" />

 




•	Open CMD and paste the “Exif tool path” and Recovered Image path and load the Exif Tool details –
Outputs -
 
<img width="975" height="327" alt="image" src="https://github.com/user-attachments/assets/f185f639-f50c-460f-ba89-db1eb42497ee" />
<img width="975" height="318" alt="image" src="https://github.com/user-attachments/assets/024de0d2-63cf-43b6-8ea7-10c117552b30" />

 


