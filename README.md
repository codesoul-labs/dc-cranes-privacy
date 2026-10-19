# DC-Cranes — Document Scanner & Operations Cloud Sync

[![Platform: Android](https://img.shields.io/badge/Platform-Android-3DDC84.svg?style=flat&logo=android)](https://www.android.com/)
[![Target SDK: Android 14+](https://img.shields.io/badge/Target_SDK-34%2B-blue.svg?style=flat)](https://developer.android.com)
[![Storage: Google Drive REST API](https://img.shields.io/badge/Storage-Google_Drive_v3-4285F4.svg?style=flat&logo=googledrive)](https://developers.google.com/drive)
[![Architecture: Zero--Retention](https://img.shields.io/badge/Architecture-Zero--Retention-green.svg?style=flat)](#data-privacy--zero-retention-model)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat)](LICENSE)

**DC-Cranes** is an enterprise-grade mobile document capture, inspection sheet compilation, and cloud synchronization utility engineered specifically for crane rental logistics, heavy machinery site managers, and field operators. 

Built with a strict **zero-retention security footprint**, DC-Cranes eliminates third-party backend servers and intermediaries. Scanned paperwork, equipment logs, and customer invoices are processed in volatile memory and synced directly to the user's personal Google Drive via secure OAuth 2.0 authorization.

---

## Key Features

* **High-Speed Document Capture:** Real-time camera processing optimized for on-site paperwork, delivery challans, and machine safety inspection logs.
* **Multi-Page Swipable Carousel:** Seamless horizontal preview pager with real-time dynamic page counters (`Page X of Y`) for reviewing multi-leaf contracts before sync.
* **Context-Aware Smart Sharing:**
  * **Single Page:** Shared instantly as a compressed high-resolution image (`.jpg` / `.png`).
  * **Multi-Page / Batch Selection:** Dynamically rendered into an organized, publication-ready multi-page `.pdf` using Android's native graphics engine.
* **Direct Google Drive Cloud Storage:** Automatically organizes and syncs files into a designated `DC-Cranes_Documents` workspace folder using the least-privilege `drive.file` scope.
* **Native Android Authentication:** Powered by Android Credential Manager and OAuth 2.0. Completely free of Firebase, third-party analytics trackers, or external databases.
* **One-Time Per-Account Consent:** Enforces a persistent, non-intrusive legal agreement checkpoint tied directly to authenticated account credentials.

---

## Architectural Workflow
