<div align="center">
<img alt="" src="https://github.com/Faceplugin-ltd/FaceRecognition-Javascript/assets/160750757/657130a9-50f2-486d-b6d5-b78bcec5e6e2.png" width=200/>
</div>

# Open Source ID Document Liveness Detection SDK

An open-source ID document liveness detection and document anti-spoofing SDK for Windows and Linux.

Detect presentation attacks involving identity documents such as passports, national ID cards, driver's licenses, and other government-issued identity documents using on-device processing.

* * *

## 🚀 Overview

The **Open Source ID Document Liveness Detection SDK** provides developers with tools for detecting whether an identity document presented to a camera or captured in an image is a genuine physical document rather than a presentation attack.

The SDK is designed for privacy-focused identity verification applications where document images can be processed locally without sending sensitive identity data to a remote server.

It can be used as a standalone **ID document liveness detection** component or as part of a complete identity verification workflow together with ID document recognition, OCR, MRZ, barcode scanning, face recognition, and face liveness detection.

### ✨ Key Features

- 🔒 **On-Premise Processing** — Process document images locally without sending identity data to a cloud service
- 🛡️ **Document Liveness Detection** — Detect presentation attacks involving physical and reproduced identity documents
- 🎯 **Document Anti-Spoofing** — Help identify attempts to present fraudulent or reproduced documents
- 🆔 **Identity Document Support** — Designed for passports, ID cards, driver's licenses, and other identity documents
- ⚡ **Fast Processing** — Optimized for efficient document analysis
- 🔧 **Easy Integration** — Simple APIs for integrating document liveness detection into applications
- 🌐 **Cross-Platform** — Designed for Windows and Linux environments
- 🖥️ **CPU Support** — Can run on systems without a dedicated GPU
- 🆓 **Open Source** — Available for developers to inspect, modify, and integrate into their projects

### 🎯 Document Liveness Capabilities

The SDK is designed for detecting presentation attacks involving identity documents, including:

- Physical document presentation
- Printed document attacks
- Screen-based document presentation
- Reproduced document images
- Document presentation attacks
- Other spoofing attempts involving identity documents

> **Note:** Document liveness detection and document recognition are different capabilities. Liveness detection focuses on determining whether the presented document is genuine/live rather than a reproduced presentation, while document recognition extracts and verifies information such as document type, OCR data, MRZ, and barcodes.

* * *

## 🛠️ Installation
### Create anaconda environment
```
conda create -n liveness python=3.11
conda activate liveness
```

### Install project dependencies
```python
pip install opencv-python
pip install ultralytics
```

### Check document liveness of the ID documents in test_image directory
```python
python doc_liveness.py
```

* * *

## 🆔 Supported Identity Documents

The SDK is intended for use with a wide range of identity documents, including:

- Passports
- National ID cards
- Driver's licenses
- Residence permits
- Government-issued identity cards
- Other machine-readable identity documents

Support for specific document types can depend on the SDK version and underlying models.

* * *
## 🏢 More Biometric SDKs from Faceplugin

This project is developed by **[Faceplugin](https://faceplugin.com/)**, a provider of on-premise biometric and identity verification SDKs.

If you need capabilities beyond this open-source SDK, explore Faceplugin's commercial SDKs for:

| Solution | Description |
|---|---|
| 👤 **Face Recognition** | Face recognition, verification, identification, attributes, and biometric authentication |
| 🛡️ **Face Liveness Detection** | Detect presentation attacks during face verification and authentication |
| 🆔 **ID Document Recognition** | OCR, MRZ, barcode recognition, and document classification |
| 🔐 **ID Document Liveness Detection** | Detect presentation attacks involving identity documents |

Explore our complete suite of **biometric and identity verification solutions**, including face recognition, face liveness detection, ID document recognition and ID document liveness detection SDKs.


### Face Recognition SDKs
- [Face Recognition + Liveness — Android](https://github.com/Faceplugin-ltd/FaceRecognition-Android) · Java, Kotlin
- [Face Recognition + Liveness — iOS](https://github.com/Faceplugin-ltd/FaceRecognition-iOS) · Objective-C, Swift
- [Face Recognition + Liveness — Flutter](https://github.com/Faceplugin-ltd/FaceRecognition-Flutter)
- [Face Recognition + Liveness — React Native](https://github.com/Faceplugin-ltd/FaceRecognition-React-Native)
- [Face Recognition + Liveness — Ionic Cordova](https://github.com/Faceplugin-ltd/FaceRecognition-Ionic-Cordova)
- [Face Recognition + Liveness — Ionic Capacitor](https://github.com/Faceplugin-ltd/FaceRecognition-Ionic-Capacitor)
- [Face Recognition + Liveness — Docker for Linux](https://github.com/Faceplugin-ltd/FaceRecognition-Docker)
- [Face Recognition + Liveness — Windows](https://github.com/Faceplugin-ltd/FaceRecognition-Windows)
- [Face Recognition + Liveness — .NET MAUI](https://github.com/Faceplugin-ltd/FaceRecognition-.Net)
- [Face Recognition + Liveness — .NET WPF](https://github.com/Faceplugin-ltd/FaceRecognition-WPF-.Net)

### ID Document Recognition SDKs
- [ID Document Recognition — Android](https://github.com/Faceplugin-ltd/ID-Document-Recognition-Android) · Java, Kotlin
- [ID Document Recognition — iOS](https://github.com/Faceplugin-ltd/ID-Document-Recognition-iOS) · Objective-C, Swift
- [ID Document Recognition — Flutter](https://github.com/Faceplugin-ltd/ID-Document-Recognition-Flutter)
- [ID Document Recognition — React Native](https://github.com/Faceplugin-ltd/ID-Document-Recognition-React-Native)
- [ID Document Recognition — Ionic Cordova](https://github.com/Faceplugin-ltd/ID-Document-Recognition-Ionic-Cordova)
- [ID Document Recognition — Ionic Capacitor](https://github.com/Faceplugin-ltd/ID-Document-Recognition-Ionic-Capacitor)
- [ID Document Recognition — Docker for Linux](https://github.com/Faceplugin-ltd/ID-Document-Recognition-Docker)
- [ID Document Recognition — Windows](https://github.com/Faceplugin-ltd/ID-Document-Recognition-Windows)

### ID Document Liveness Detection SDK
- [ID Document Liveness Detection](https://github.com/Faceplugin-ltd/ID-Document-Liveness-Detection-Docker)

* * *


## 🤝 Support & Contact
While there are many ways to support this project, starring ⭐️ this GitHub repository is one of the simplest and most impactful. It increases discoverability and helps the project reach a wider audience. Thank you for your support 🙏
<div align="center">
  <a href="mailto:info@faceplugin.com">
    <img src="https://img.shields.io/badge/Email-info@faceplugin.com-blue.svg?logo=gmail" alt="Email"/>
  </a>
  <a href="https://wa.me/+14692784822">
    <img src="https://img.shields.io/badge/WhatsApp-faceplugin-green.svg?logo=whatsapp" alt="WhatsApp"/>
  </a>
</div>

### 📞 Get in Touch
- **Email**: [info@faceplugin.com](mailto:info@faceplugin.com)
- **WhatsApp**: [+1 (469) 278-4822](https://wa.me/+14692784822)
- **Website**: [faceplugin.com](https://faceplugin.com/)

---

<div align="center">
  <sub>Made with ❤️ by <a href="https://faceplugin.com">Faceplugin</a></sub>
</div>
