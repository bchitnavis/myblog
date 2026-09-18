---
layout: single
title: "MyCloudApp — Multi-Cloud Storage Manager"
permalink: /MyCloudApp.html
author_profile: true
---

*Last Updated: September 17, 2026*

## Overview

**MyCloudApp** is a modern desktop application designed to streamline the organization, synchronization, and management of files across multiple cloud storage providers—including **Google Drive**, **Microsoft OneDrive**, and local storage drives. Built with Python and PySide6, MyCloudApp provides a secure, unified interface to index metadata, eliminate duplicate files, clean up empty directories, and organize large personal or professional data libraries.

---

## Key Features

- **Unified Multi-Cloud Management**: Browse, search, and manage files stored on Google Drive, OneDrive, and local disks from a single desktop dashboard.
- **Automated Deduplication & Cleanup**: Identify and remove duplicate files and empty directories across cloud and local storage.
- **Hierarchical Tree View**: Navigate large, deeply nested directory structures with responsive desktop performance.
- **Local Metadata Caching**: High-performance local indexing using SQLite / DuckDB to enable fast searching without constant API rate limiting.
- **Secure Authentication**: Direct OAuth 2.0 authentication with cloud providers using secure, localized credential storage.

---

## Privacy Policy & Google API Data Disclosure

MyCloudApp respects user privacy and is committed to protecting all personal and cloud data. This section explains how MyCloudApp interacts with Google user data and complies with Google API Services policies.

### 1. Google Drive API Scopes & Access
MyCloudApp requests access to the Google Drive API (`https://www.googleapis.com/auth/drive` or `drive.file`) exclusively to perform user-directed file operations, including:
- Listing files and folders to display your directory structure.
- Calculating folder sizes, scanning for duplicates, and identifying empty directories.
- Moving, renaming, downloading, uploading, or organizing files as requested by the user.

### 2. Localized Data Storage & Security
- **No External Servers**: MyCloudApp runs entirely as a local desktop client. All API requests are made directly between your local machine and Google/Microsoft API servers over encrypted HTTPS connections.
- **Local Credential Storage**: OAuth 2.0 access tokens and refresh tokens are stored securely on the user's local device (`token.json` / secure OS credential store) and are **never** transmitted to any third-party server or external database.
- **No Third-Party Data Sharing**: MyCloudApp does not sell, rent, trade, or transfer your Google Drive data or personal information to third parties.
- **No AI/ML Training**: User data accessed via Google APIs is never used to train generalized artificial intelligence or machine learning models.

### 3. Google API Services User Data Policy Compliance
> **Limited Use Disclosure:**  
> MyCloudApp's use and transfer of information received from Google APIs to any other app will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements.

### 4. Revoking Access
You can revoke MyCloudApp's access to your Google Account at any time by visiting your Google Security Settings:
- [Google Account Permissions](https://myaccount.google.com/permissions)

---

## Terms of Service

1. **License & Usage**: MyCloudApp is provided for personal and administrative productivity use. You are responsible for ensuring you have appropriate authorization to manage files in connected cloud accounts.
2. **Data Backup**: While MyCloudApp includes safeguards for file organization and deduplication, users are advised to maintain backups of important files before executing bulk deletion or restructuring operations.
3. **Disclaimer**: The software is provided "as is", without warranty of any kind, express or implied. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability.

---

## Technical Specifications

- **Platform**: Desktop (macOS, Windows, Linux)
- **Language**: Python 3.10+
- **GUI Framework**: PySide6 (Qt)
- **APIs**: Google Drive API v3, Microsoft Graph API
- **Database / Metadata**: SQLite / DuckDB / SQLAlchemy 2.0

---

## Contact & Support

For questions, support, or feedback regarding MyCloudApp, please reach out via:

- **Developer**: Bharat Chitnavis
- **Website**: [https://chitnavis.com/about/](https://chitnavis.com/about/)
- **GitHub**: [https://github.com/bchitnavis/MyCloudApp](https://github.com/bchitnavis/MyCloudApp)
- **Main Blog**: [https://chitnavis.com](https://chitnavis.com)
