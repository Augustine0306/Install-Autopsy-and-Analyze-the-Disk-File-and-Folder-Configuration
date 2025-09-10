# Install Autopsy and Analyze the Disk File and Folder Configuration
#### Name: AUGUSTINE J
#### Reg no : 212222240015

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results

<img width="1919" height="1078" alt="Screenshot 2025-09-06 144344" src="https://github.com/user-attachments/assets/aefa9137-0b75-428d-959a-ec5b187b6715" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144430" src="https://github.com/user-attachments/assets/3571e5bc-93e4-4e9c-8267-0b889c984366" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144445" src="https://github.com/user-attachments/assets/c98099d7-418c-4e9f-a4d5-53f4dedd79b2" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144508" src="https://github.com/user-attachments/assets/6b588d0a-07b0-476b-91fd-bc87184c8718" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144525" src="https://github.com/user-attachments/assets/7de5fc9a-01ad-410e-a69e-ab94dab70f01" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144538" src="https://github.com/user-attachments/assets/8e2b0750-1214-4014-8e69-e2d58396acf9" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144656" src="https://github.com/user-attachments/assets/58650ed5-3fa4-4eb8-a72c-ee74a4209c3f" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 144734" src="https://github.com/user-attachments/assets/0b35b699-4f24-4ac1-ab40-054883f339ee" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
