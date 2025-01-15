---

# LiNEDATA: Efficient Returns Management System for E-Commerce Sellers

LiNEDATA is a Python-based tool designed for eCommerce sellers to streamline return management. It captures and organizes photos and videos, integrates barcode tracking for easy order identification, and stores media files in date-based folders. By reducing manual effort, LiNEDATA helps sellers efficiently handle disputes, minimize losses, and maintain a smooth workflow.
[![Download LiNEDATA Installer](https://img.shields.io/badge/Download-LiNEDATA%20Installer-blue)](https://github.com/pratap-raghav/LiNEDATA-Installer/releases/download/Projects/LiNEDATA-Installer.exe)



### Key Features of LiNEDATA  
- **Media Capture**: Easily capture photos and videos of return packages.  
- **Barcode Tracking**: Link media to orders with barcode scanning.  
- **Organized File Management**: Save files in date-based folders for easy access.  
- **Timestamps & Tracking IDs**: Overlay timestamps and IDs on media for authenticity.  
- **User-Friendly Interface**: Intuitive GUI for seamless operation.  
- **Multi-Tasking**: Efficiently handles simultaneous tasks like saving media.  
- **Custom Controls**: Keyboard shortcuts for quick actions.  

### Technologies Used:
- **Python**: Core programming language for building the tool.  
- **OpenCV**: For capturing and processing photos and videos.  
- **Pyzbar**: For barcode scanning and tracking ID extraction.  
- **Tkinter**: For creating the graphical user interface (GUI).  
- **Multiprocessing**: For efficient handling of tasks like photo capturing and saving.      
- **OS Module**: For file management and directory creation.  

### Controls:
- **M:** Enter tracking ID.
- **R:** Start recording a video.
- **S:** Stop recording the video.
- **Spacebar:** Capture a photo.
- **Q:** Quit the program.

---
## Preview

![preview1](https://github.com/user-attachments/assets/c9525995-bdfa-44f0-8adf-0fc0779ec2d6)

**1. Camera Selection and Configuration:** Select the desired camera and adjust settings as needed.
**2. Directory Selection:** Choose the folder where files will be saved.
**3. System Initialization:** Activate the camera and barcode scanner for seamless operation.
**4. Barcode Scanning:** Scan barcodes to link tracking IDs with return packages automatically.
<br>
![preview2](https://github.com/user-attachments/assets/714bb9c0-1e4c-4b85-9b5c-a0dc3ca6d161)

**1. Manual Input:** Enter the tracking ID manually if barcode scanning fails.
**2. ID Update:** Automatically update the system with the provided tracking ID.
<br>
### Directory Structure
![structure](https://github.com/user-attachments/assets/3a6731af-3733-43c5-817b-f88ecfb945f1)
- **Main Folder:** This is the main folder where all return-related files are stored.
- **Date-Based Folders:** Subfolders are created for each day, helping organize files by date.
- **Media Files:** Photos and videos are saved within the date folders, each linked to a specific tracking ID for easy access.
