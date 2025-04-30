---

# LiNEDATA: Efficient Returns Management System for E-Commerce Sellers

![LinedataNew](https://github.com/user-attachments/assets/353a92ac-b874-422c-8e5f-d81cd0f70584)

[![Download LiNEDATA Installer](https://img.shields.io/badge/Download-LiNEDATA%20Installer-blue?style=flat&logo=github&logoColor=white)](https://github.com/pratap-raghav/LiNEDATA-Installer/releases/download/Projects/LiNEDATA-Installer.exe)

LiNEDATA is a Python-based tool designed for eCommerce sellers to streamline return management. It captures and organizes photos and videos, integrates barcode tracking for easy order identification, and stores media files in date-based folders. By reducing manual effort, LiNEDATA helps sellers efficiently handle disputes, minimize losses, and maintain a smooth workflow.

### Note: You can use your mobile phone as a webcam with services like [Iriun Webcam](https://iriun.com/) for better video quality. Minimum resolution required: 1920x1080.

## Preview

![preview1](https://github.com/user-attachments/assets/a046f014-b137-4ab2-a87c-986db3dfdf13)


**1. Camera Selection and Configuration:** Select the desired camera and adjust settings as needed.
**2. Directory Selection:** Choose the folder where files will be saved.
**3. System Initialization:** Activate the camera and barcode scanner for seamless operation.
**4. Barcode Scanning:** Scan barcodes to link tracking IDs with return packages automatically.
<br>
![preview2](https://github.com/user-attachments/assets/24a65cfc-33d4-4c50-b8ac-13e6e2d8ddce)


**1. Manual Input:** Enter the tracking ID manually if barcode scanning fails.
**2. ID Update:** Automatically update the system with the provided tracking ID.
<br>
### Directory Structure
![structure](https://github.com/user-attachments/assets/3a6731af-3733-43c5-817b-f88ecfb945f1)
- **Main Folder:** This is the main folder where all return-related files are stored.
- **Date-Based Folders:** Subfolders are created for each day, helping organize files by date.
- **Media Files:** Photos and videos are saved within the date folders, each linked to a specific tracking ID for easy access.

### Images
![Untitled design](https://github.com/user-attachments/assets/6a43e654-9728-44fd-8316-be07604d29c7)

---

LiNEDATA is a tool designed to simplify returns management for e-commerce sellers by automating the process of collecting and organizing return evidence. It combines video recording, photo capture, and barcode scanning into one seamless workflow, ensuring that every return is accurately documented with timestamps and tracking IDs.

### How It Works:
- **Evidence Collection**: When a return is initiated, LiNEDATA captures video and photos of the returned product. Each image and video is tagged with a timestamp and tracking ID to ensure accurate documentation.
- **Barcode Scanning**: The system scans the product's barcode to link it to the correct return, making it easier to track and verify the item.
- **Automated Organization**: LiNEDATA automatically sorts the captured media into folders based on the tracking ID and return date, eliminating the need for manual sorting.
- **Compensation Filing**: Once the evidence is organized, sellers can quickly file compensation claims on e-commerce platforms, with timestamped evidence serving as proof in case of disputes.

LiNEDATA streamlines the entire returns process, saving time, reducing errors, and preventing fraud. It is scalable, user-friendly, and designed to enhance productivity for businesses of all sizes. 


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
