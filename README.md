# Real Editor

**Real Editor** is a powerful Arabic text editor designed for text processing and storage. Built using Java 1.8, it provides users with robust features to manage and analyze Arabic text. The editor integrates seamlessly with MariaDB for file storage and supports a wide array of text processing functionalities.

---

## Features

- **File Management**
  - Save files to MariaDB.
  - Create, update, delete files.
  - Import files from your PC.

- **Text Processing Capabilities**
  - Term Frequency-Inverse Document Frequency (**TF-IDF**).
  - Pointwise Mutual Information (**PMI**).
  - PKL computation.
  - Part-of-Speech Tagging (**POS Tagging**).
  - Stemming.
  - Lemmatization.
  - Root extraction.

---

## Installation Links

Download the appropriate installer for your setup from the links below:

- **Single PC Setup**: [Download](https://drive.google.com/drive/folders/1aAInCbb5Oj6JfZfKciYHTXTgazPWUIy4?usp=sharing)
- **Server PC Setup**: [Download](https://drive.google.com/drive/folders/1w8qyK11KukpnU69mzSEO6ZzbApvQzco_?usp=drive_link)
- **Client PC Setup**: [Download](https://drive.google.com/drive/folders/16gFYIJnO1a_W3SbACUSC_Rz4xTG8jInc?usp=sharing)

## Documentation

For detailed instructions, usage guidelines, and a comprehensive feature report, please refer to the documentation provided:

- **Report**: [View Report](https://drive.google.com/drive/folders/185O5gpF0_EKI380CtnB6A0AK-Tph2Uz-?usp=sharing)

---
## Added Auto-Save boundary test task (Issue #1)

## Issue #2 – TF-IDF positive case
- TODO: Add positive TF-IDF test (manual ±0.01)

## Issue #4 — TF-IDF Negative Case

Test verifies:
- Empty string input
- Special characters only input
Expected:
- No crash
- TF-IDF returns zero or safe value
## Issue #6 – Hash integrity (MD5/SHA1)
- TODO: Add test to verify hash output matches expected for known input.
- Expected: Correct MD5/SHA1 value, consistent results, no crash.

