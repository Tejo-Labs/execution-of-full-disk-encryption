# README: Demonstration of Full Disk Encryption via BitLocker

## Overview
This project demonstrates the execution of full disk encryption using BitLocker on a removable drive (e.g., USB or pendrive). The document highlights the step-by-step process for enabling encryption, managing recovery keys, and verifying encryption status through both GUI and command-line methods.

## Key Features
1. **BitLocker Configuration**:
   - Demonstrates enabling BitLocker encryption on removable drives when system drives are pre-configured.
   - Provides step-by-step instructions for activating BitLocker through the Control Panel.

2. **Recovery Key Management**:
   - Emphasizes the importance of saving the recovery key in multiple formats:
     - As a file.
     - Printed as hard copy for backup in case of file corruption.

3. **Encryption Completion**:
   - Showcases the process to monitor and confirm the encryption status via BitLocker settings.

4. **Command-Line Verification**:
   - Explains how to use the `Manage-bde -status` command to verify the encryption state of the drive.
   - Demonstrates the locking and unlocking process after ejecting and re-attaching the encrypted drive.

5. **Screenshots**:
   - Includes detailed screenshots for each stage, from enabling encryption to final verification, to aid visual learners.

## Prerequisites
- A removable drive (USB or pendrive) for encryption.
- Windows operating system with BitLocker enabled.
- Administrator privileges on the system.
- Group policies configured to allow BitLocker management.

## Steps to Reproduce
1. **Enable BitLocker**:
   - Open the `Manage BitLocker` option from the Control Panel.
   - Select the removable drive and enable BitLocker encryption.

2. **Save Recovery Key**:
   - Choose to save the recovery key as a file and print it for backup.

3. **Complete Encryption**:
   - Follow the on-screen instructions to complete the encryption process.

4. **Verify Encryption**:
   - Use the `Manage-bde -status` command in the Command Prompt to verify the encryption status.
   - Eject and re-attach the drive to confirm that it is locked.

5. **Unlock Drive**:
   - Enter the password or recovery key to unlock the encrypted drive.

## Screenshots
Screenshots documenting each step are provided in the project file to help users replicate the process.

## Notes
- This demonstration is limited to removable drives since the system drives were pre-configured for encryption and group policies restricted changes to those settings.
- Ensure that recovery keys are securely stored as they are critical for unlocking the drive in case of forgotten passwords.

## Benefits of Full Disk Encryption
- Protects sensitive data on removable drives from unauthorized access.
- Ensures data confidentiality, even if the drive is lost or stolen.

## Limitations
- Requires administrator privileges for setup.
- Relies on proper recovery key management to prevent data loss.

## Conclusion
This project serves as a practical guide to implementing and managing full disk encryption with BitLocker, emphasizing the importance of data security and backup measures. By following the outlined steps and best practices, users can effectively secure their sensitive information on removable drives.

---
**For detailed screenshots and step-by-step instructions, refer to the accompanying PDF file.**
