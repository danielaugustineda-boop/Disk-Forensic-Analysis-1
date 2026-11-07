# Disk Forensic Analysis Using Autopsy

## Project Overview

This project demonstrates a practical digital forensic investigation using **Autopsy**, an open-source digital forensics platform built on The Sleuth Kit (TSK).

The project walks through the examination of digital storage media to identify, recover, analyze, and document digital evidence. It covers the forensic examination of disk images, file-system structures, deleted files, user activities, browser artifacts, metadata, and other potentially relevant evidence.

The objective is to demonstrate how a digital forensic investigator can examine a storage device systematically while preserving the integrity and evidential value of the acquired data.

This repository is designed for cybersecurity students, digital forensic beginners, SOC analysts, incident responders, and anyone interested in practical digital forensic investigations.

## 1. Learning Objectives

By completing this practical exercise, learners should be able to:

1. Explain the fundamentals of digital forensics and disk forensic analysis.
2. Understand forensic imaging and why it is necessary.
3. Explain the importance of evidence integrity and chain of custody.
4. Install and configure Autopsy.
5. Create and manage forensic investigation cases.
6. Add disk images and logical data sources to an Autopsy case.
7. Configure and execute Autopsy ingest modules.
8. Examine file-system structures and directory contents.
9. Identify and recover deleted files where recovery is possible.
10. Perform keyword searches across acquired evidence.
11. Examine file metadata and timestamps.
12. Analyze browser artifacts and user activities.
13. Identify suspicious files and file-extension mismatches.
14. Generate forensic timelines.
15. Calculate and verify cryptographic hashes.
16. Generate and interpret forensic investigation reports.

## 2. What Is Disk Forensic Analysis?

Disk forensic analysis is the process of acquiring, preserving, examining, and interpreting digital evidence stored on computer storage media.

These storage devices may include:

- Hard Disk Drives (HDDs).
- Solid State Drives (SSDs).
- USB flash drives.
- External storage devices.
- Memory cards.
- Virtual machine disk images.
- Other digital storage media.

During an investigation, an examiner may look for:

- Deleted documents and photographs.
- Recently accessed files.
- Browser history and downloaded files.
- User-created documents.
- Suspicious executable files.
- Evidence of unauthorized access.
- Hidden files and directories.
- File-system metadata.
- Evidence of data exfiltration.
- Potential indicators of malicious activity.

### Why Is Disk Forensics Important?

Disk forensic analysis is useful in:

- Cybercrime investigations.
- Incident response.
- Insider-threat investigations.
- Malware investigations.
- Data theft investigations.
- Corporate security investigations.
- Legal and regulatory investigations.
- Recovery of deleted or lost information.

## 3. Tools and Technologies

The following tools are used or referenced in this project.

| Tool | Purpose |
|---|---|
| Autopsy | Digital forensic examination and analysis |
| The Sleuth Kit (TSK) | File-system forensic analysis framework |
| FTK Imager | Forensic image acquisition and examination |
| WinHex / HxD | Hexadecimal examination of files and storage data |
| PowerShell | Hash calculation and file verification |
| SHA-256 | Cryptographic integrity verification |
| Windows / Linux | Forensic laboratory operating systems |

### Primary Tool: Autopsy

Autopsy provides a graphical interface for investigating disk images and other digital evidence.

Its capabilities include:

- File-system analysis.
- Deleted-file identification.
- Keyword searching.
- Hash calculation and lookup.
- File-type identification.
- Browser artifact extraction.
- Timeline analysis.
- Metadata examination.
- Evidence tagging.
- Forensic report generation.

Official resources:

- Autopsy website: https://www.autopsy.com/
- Autopsy downloads: https://www.autopsy.com/download/
- Autopsy documentation: https://www.sleuthkit.org/autopsy/docs/
- The Sleuth Kit: https://www.sleuthkit.org/

## 4. Laboratory Environment and Requirements

### Hardware Requirements

Recommended laboratory specifications:

| Component | Minimum Recommendation |
|---|---|
| Processor | Dual-core processor |
# Disk Forensic Analysis Using Autopsy

## Project Overview

This project demonstrates a practical digital forensic investigation using **Autopsy**, an open-source digital forensics platform built on The Sleuth Kit (TSK).

The project walks through the examination of digital storage media to identify, recover, analyze, and document digital evidence. It covers the forensic examination of disk images, file-system structures, deleted files, user activities, browser artifacts, metadata, and other potentially relevant evidence.

The objective is to demonstrate how a digital forensic investigator can examine a storage device systematically while preserving the integrity and evidential value of the acquired data.

This repository is designed for cybersecurity students, digital forensic beginners, SOC analysts, incident responders, and anyone interested in practical digital forensic investigations.

## 1. Learning Objectives

By completing this practical exercise, learners should be able to:

1. Explain the fundamentals of digital forensics and disk forensic analysis.
2. Understand forensic imaging and why it is necessary.
3. Explain the importance of evidence integrity and chain of custody.
4. Install and configure Autopsy.
5. Create and manage forensic investigation cases.
6. Add disk images and logical data sources to an Autopsy case.
7. Configure and execute Autopsy ingest modules.
8. Examine file-system structures and directory contents.
9. Identify and recover deleted files where recovery is possible.
10. Perform keyword searches across acquired evidence.
11. Examine file metadata and timestamps.
12. Analyze browser artifacts and user activities.
13. Identify suspicious files and file-extension mismatches.
14. Generate forensic timelines.
15. Calculate and verify cryptographic hashes.
16. Generate and interpret forensic investigation reports.

## 2. What Is Disk Forensic Analysis?

Disk forensic analysis is the process of acquiring, preserving, examining, and interpreting digital evidence stored on computer storage media.

These storage devices may include:

- Hard Disk Drives (HDDs).
- Solid State Drives (SSDs).
- USB flash drives.
- External storage devices.
- Memory cards.
- Virtual machine disk images.
- Other digital storage media.

During an investigation, an examiner may look for:

- Deleted documents and photographs.
- Recently accessed files.
- Browser history and downloaded files.
- User-created documents.
- Suspicious executable files.
- Evidence of unauthorized access.
- Hidden files and directories.
- File-system metadata.
- Evidence of data exfiltration.
- Potential indicators of malicious activity.

### Why Is Disk Forensics Important?

Disk forensic analysis is useful in:

- Cybercrime investigations.
- Incident response.
- Insider-threat investigations.
- Malware investigations.
- Data theft investigations.
- Corporate security investigations.
- Legal and regulatory investigations.
- Recovery of deleted or lost information.

## 3. Tools and Technologies

The following tools are used or referenced in this project.

| Tool | Purpose |
|---|---|
| Autopsy | Digital forensic examination and analysis |
| The Sleuth Kit (TSK) | File-system forensic analysis framework |
| FTK Imager | Forensic image acquisition and examination |
| WinHex / HxD | Hexadecimal examination of files and storage data |
| PowerShell | Hash calculation and file verification |
| SHA-256 | Cryptographic integrity verification |
| Windows / Linux | Forensic laboratory operating systems |

### Primary Tool: Autopsy

Autopsy provides a graphical interface for investigating disk images and other digital evidence.

Its capabilities include:

- File-system analysis.
- Deleted-file identification.
- Keyword searching.
- Hash calculation and lookup.
- File-type identification.
- Browser artifact extraction.
- Timeline analysis.
- Metadata examination.
- Evidence tagging.
- Forensic report generation.

Official resources:

- Autopsy website: https://www.autopsy.com/
- Autopsy downloads: https://www.autopsy.com/download/
- Autopsy documentation: https://www.sleuthkit.org/autopsy/docs/
- The Sleuth Kit: https://www.sleuthkit.org/

## 4. Laboratory Environment and Requirements

### Hardware Requirements

Recommended laboratory specifications:

| Component | Minimum Recommendation |
|---|---|
| Processor | Dual-core processor |
| RAM | 8 GB |
| Storage | 50 GB available space |
| Operating System | Windows 10/11 or supported Linux |
| Display | 1366 × 768 or higher |

For larger forensic images, 16 GB RAM or more and additional SSD storage are recommended.

### Software Requirements

1. Autopsy.
2. A supported operating system.
3. A forensic disk image or controlled sample evidence.
4. A hashing utility.
5. Optional: FTK Imager.

### Laboratory Safety

Only investigate storage devices and forensic images that you own or have explicit authorization to examine.

**Important forensic principles:**

- Never modify original evidence unnecessarily.
- Always work from a forensic image or verified working copy.
- Record the source and acquisition details.
- Calculate cryptographic hashes.
- Preserve original evidence separately.
- Document every important investigative action.
- Do not interpret an automated finding as proof of criminal activity without corroboration.

## 5. Project Directory Structure

A recommended directory structure for this practical exercise is:

```text
Disk-Forensic-Analysis/
│
├── README.md
│
├── evidence/
│   ├── original/
│   ├── working-copy/
│   └── sample-data/
│
├── acquisition/
│   ├── acquisition-notes.md
│   └── hash-verification.txt
│
├── autopsy-case/
│   └── CASE-001/
│
├── screenshots/
│   ├── 01-autopsy-dashboard.png
│   ├── 02-case-creation.png
│   ├── 03-data-source.png
│   ├── 04-ingest-configuration.png
│   ├── 05-file-analysis.png
│   ├── 06-deleted-files.png
│   ├── 07-keyword-search.png
│   ├── 08-timeline-analysis.png
│   └── 09-forensic-report.png
│
├── reports/
│   ├── autopsy-report/
│   └── investigation-summary.md
│
└── documentation/
    ├── chain-of-custody.md
    └── investigation-notes.md
```

*Note: The evidence directories and screenshots are placeholders for the actual laboratory files. Do not commit confidential evidence, private personal information, or large forensic disk images to a public GitHub repository.*

---

# 6. Practical Walkthrough: Disk Forensic Investigation

The practical investigation follows the standard digital forensic workflow:

**Evidence identification → Acquisition → Preservation → Examination → Analysis → Reporting**

## Phase 1: Preparing the Forensic Laboratory

### Step 1: Install Autopsy

1. Visit https://www.autopsy.com/download/.
2. Download the supported Autopsy installer for your operating system.
3. Run the installer.
4. Follow the installation wizard.
5. Launch Autopsy after installation.
6. Confirm that the application opens successfully.

On Windows, Autopsy may request administrator privileges for certain acquisition and disk-access operations.

**Expected outcome:** Autopsy launches and displays its welcome screen.

### Step 2: Prepare Your Evidence

For this exercise, obtain a controlled forensic disk image or create a sample image from a storage device you are authorized to examine.

Common forensic image formats include:

- RAW/DD (`.dd`, `.img`, `.raw`).
- Expert Witness Format (`.E01`).

A forensic image should preserve the relevant data and structure of the source storage medium.

You can obtain educational forensic datasets from:

- NIST Computer Forensic Reference Data Sets (CFReDS): https://cfreds.nist.gov/
- Digital Forensics Tool Testing: https://www.dfrws.org/

Keep the original evidence in a protected directory and use a separate working copy for examination.

### Step 3: Calculate the Evidence Hash

A cryptographic hash helps establish whether evidence has changed between acquisition and examination.

On Windows PowerShell:

```powershell
Get-FileHash "C:\Evidence\sample.dd" -Algorithm SHA256
```

On Linux:

```bash
sha256sum sample.dd
```

Record the resulting hash in your evidence documentation.

Example:

```text
Evidence ID: EVD-001
Evidence Name: sample.dd
Hash Algorithm: SHA-256
Hash Value: [INSERT ACTUAL HASH]
Date Acquired: [INSERT DATE]
Examiner: [INSERT NAME]
```

Do not use an invented hash value in your investigation report.

For segmented forensic images, preserve and verify the complete image set according to the acquisition tool's procedure.

## Phase 2: Creating a Forensic Case in Autopsy

### Step 4: Launch Autopsy

1. Open Autopsy.
2. Select **Create New Case**.
3. The New Case Information wizard will appear.

### Step 5: Enter Case Information

Provide the following details:

| Field | Example |
|---|---|
| Case Name | Disk_Forensic_Investigation |
| Base Directory | C:\ForensicCases |
| Case Type | Single-user |
| Case Number | CASE-001 |
| Examiner | Your Name |
| Organization | Cybersecurity Training Laboratory |

Use a unique case number for every investigation.

Click **Next** and complete the additional case information fields available in your installed version.

Click **Finish**.

**Expected outcome:** Autopsy creates the investigation case and prepares the environment for evidence examination.

## Phase 3: Adding the Evidence Source

### Step 6: Add a Data Source

After creating the case:

1. Select **Add Data Source**.
2. Choose the appropriate data source type.
3. For a forensic image, select **Disk Image or VM File**.
4. Browse to the location of your forensic image.
5. Select the image.
6. Confirm the relevant time-zone setting.
7. Complete the wizard.

Autopsy supports common forensic image formats, including RAW and E01.

For a physical disk examination, use the appropriate acquisition and write-protection procedures rather than treating an ordinary live disk connection as equivalent to a forensic image.

### Step 7: Configure the Ingest Modules

Autopsy uses ingest modules to automate different aspects of forensic examination.

The available modules depend on the installed Autopsy version and configuration.

For this laboratory, enable relevant modules where available:

| Ingest Module | Investigation Purpose |
|---|---|
| Recent Activity | Extract browser and operating-system activity |
| Hash Lookup | Compare files against configured hash databases |
| File Type Identification | Identify actual file types |
| Extension Mismatch Detector | Identify files whose extensions do not match their contents |
| Keyword Search | Search indexed evidence for specified terms |
| Embedded File Extractor | Examine supported embedded and archive content |
| Picture Analyzer | Analyze supported image information |
| Encryption Detection | Identify potential encrypted files |
| Interesting Files Identifier | Identify files matching configured criteria |

Select the modules relevant to the exercise.

Avoid enabling every available module indiscriminately, particularly when investigating large disk images or working with limited hardware resources.
