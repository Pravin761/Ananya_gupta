# Ananya_gupta

Aim
To demonstrate the recovery of deleted files using the Autopsy Digital Forensics Tool by 
creating a forensic image with FTK Imager, deleting selected files, and analyzing the image in 
Autopsy.
System Prerequisites
• Computersystem with Windows Operating System
• FTK Imager installed on the system
• Autopsy installed on the system
• Minimum 4 GB RAM (8 GB recommended)
• Sufficient free disk space to store image and case files
• Administrator privileges on the system
Tools Required
• FTK Imager
• Autopsy Digital Forensics Tool
• Externalstorage device or test folder
• Sample test files(documents, images, text files, etc.)
About Autopsy
Autopsy is an open-source digital forensics platform used for analyzing disk images and 
recovering digital evidence. It provides a graphical interface for The Sleuth Kit and allows
investigatorsto examine file systems, recover deleted files, analyze metadata, and generate 
forensic reports. Autopsy is widely used in academic laboratories and professional 
investigations for post-acquisition forensic analysis.
Procedure (Attach Screenshotsfor Each Step)
Step 1: Create Test Files
1. Create a folder on the system (e.g., Test_Evidence).
2. Add five test files of different types (e.g., .txt, .pdf, .jpg, .docx, .png).
Step 2: Create Forensic Image Using FTK Imager
3. Open FTK Imager with administrator privileges.
4. Click File → Create Disk Image.
5. Select Contents of a Folder and choose the Test_Evidence folder.

  6. Select the image format (RAW or E01).
7. Enter case details and choose a destination path.
8. Enable hash calculation and start imaging.
9. Wait for the image creation to complete and verify hash values.
Step 3: Delete Test Files
10. Go to the original Test_Evidence folder.
11. Delete all five test files.
12. Empty the Recycle Bin to ensure permanent deletion.
Step 4: Analyze and Recover Files Using Autopsy
13. Launch Autopsy and create a New Case.
14. Enter case name, examiner details, and select case directory.
15. Add data source → Disk Image or VM File.
16. Browse and select the forensic image created using FTK Imager.
17. Configure ingest modules (file system, deleted file recovery, hash lookup).
18. Start the analysis process.
19. Navigate to Deleted Files section.
20. Identify and recover the deleted test files.
21. Export recovered files if required.

