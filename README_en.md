## 📥 Download & Installation

You can download the latest executable and required components from the [Releases](https://github.com/wenfa43/DSP4_logEnt/releases/latest) page.

### Executables
* **Main Program:** [DSP4_logEnt.exe](https://github.com/wenfa43/DSP4_logEnt/releases/latest/download/DSP4_logEnt.exe)
* **Required Plugins:** `ffmpeg.exe` and `ffprobe.exe` (included in the release assets)

> **Note:** For the application to function correctly, please ensure that `DSP4_logEnt.exe`, `ffmpeg.exe`, and `ffprobe.exe` are placed in the **same folder**.

## 📸 Image
![Logo](images/image.jpg)

## 📖 Documentation & Guide
For detailed information regarding development background, features, and step-by-step instructions, please visit my blog post:
👉 [**DuplicateSlayerPro V4 - Detailed Introduction & User Guide**](https://one4ok.blogspot.com/2026/03/duplicateslayerpro-v4.html)


# Duplicate Slayer Pro v4
**Version:** 26.03.20.logEnT
**Author:** austin_tseng

## Introduction
Duplicate Slayer Pro v4 is a professional "Duplicate File Comparison and Deletion Tool" designed to quickly identify duplicate documents, images, and videos on your hard drive.
 The program features real-time, multi-format file and multi-page previews, allowing you to verify file contents before organizing or deleting them, preventing the accidental deletion of important data.

### v4 Upgrade Highlights:
- **Upgraded PDF Preview Engine**: Now uses the high-performance native package (PyMuPDF). Parsing speed is drastically improved, external dependency on `poppler` is eliminated, and the background black-window flashing issue is resolved!
- **Scrolling Multi-page Previews**: When clicking on PDFs or text documents, the right preview pane now supports deep **mouse wheel scrolling**.
- **Built-in Bilingual Toggle**: An immediate "Language: EN / 語言: 繁中" toggle button is available at the top of the interface.

### Key Features:
1. **Multiple Comparison Modes**:
   - **Content Similarity**: Accurately finds identical or similar files by reading the file's Hash and checking filename similarity.
   - **Extension and Size**: Quickly matches files with exactly the same extension and file size.
2. **Powerful Preview Engine**:
   - **Multimedia**: Supports standard images and grabs the first frame of various video formats (mp4, mov, avi, mkv, etc.) for previewing.
   - **Office Documents**: Supports high-speed Word (doc/docx) and PDF previews.
   - **Code and Text**: Supports txt, csv, md, json, log, cpp, h, ino, etc. Features automatic Chinese font detection to ensure text previews are displayed perfectly.
3. **Optimized User Experience**:
   - The window supports drag-to-adjust split proportions.
   - The search process runs in the background using multi-threading, preventing UI freezing, and includes a loading status window.

---

## Instructions

### System and Dependency Requirements
To maximize the application's capabilities for multimedia files, ensure the following auxiliary components are located in the same `DSP4_logEnt` folder when running `DSP4_20260320_logEnt.exe`:
* `ffmpeg.exe` / `ffprobe.exe`: Auxiliary components for video processing.
*(Note: As of v4, the `poppler` folder is no longer required!)*

### Steps to Use
1. **Launch Program**: Double-click `DSP4_20260320_logEnt.exe`.
2. **Set Path**: Paste the target folder path you want to scan into the "Folder Path" (資料夾路徑) input box using `Ctrl+V`.
3. **Set Comparison Parameters**:
   - Choose **Content Similarity** (內容相似度) or **Extension & Size** (副檔名及Size).
   - For Content Similarity, you can modify the `Comparison Value` (please keep the default spacing at 10, which acts as the sampling block size).
4. **Start Search**: Click the "Start Search" (搜尋開始) button and wait patiently for the system to compare the files.
5. **Preview Files**:
   - Search results will be listed in the left pane (separated by dashed lines for different duplicate groups).
   - Click any item in the list to preview its content in the right pane (use the mouse wheel to scroll through long texts and multi-page PDFs).
6. **Delete Files**:
   - Once you confirm it is an unnecessary duplicate, select the row and click the **Delete File** (刪除檔案) button to remove it.

---

## Important Notes & Disclaimer
1. **Permanent Deletion Risk**: Deletions performed by this program **cannot be restored from the Recycle Bin**. Please double-check the file content or back up important data before deleting.
2. **Trial Limit**: The current version has a usage limit (default is 100 launches). When the limit is reached, a prompt will appear and the program will automatically close. To remove the limit, please contact the administrative personnel.
3. **Permission Issues**: If deletion fails, it may be because the file is set to read-only, is currently in use by another running program, or you lack sufficient permissions. Please manually handle the file at its specified path.
4. **Disclaimer**: This program is for educational and trial purposes only. The author is not responsible for any accidental file deletion or data loss.

## Contact Information
* **Version Name**: Duplicate Slayer Pro_V4 26.03.20.logEnt
* **Contact Email**: iamtwf43@gmail.com
* **Official Website**: [https://myservercloud.tw](https://myservercloud.tw)
