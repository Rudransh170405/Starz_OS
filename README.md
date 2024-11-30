# Starz_OS
 STARZ OS is a custom operating system featuring a bootloader, FAT file system support, and disk I/O functionality. It includes efficient FAT12 file handling for reading and writing, a kernel loader, and BIOS-based low-level routines. Designed for floppy disk environments, it demonstrates robust OS development principles and modular design.



STARZ Operating System
STARZ is a minimalistic, custom-built operating system designed from the ground up. This repository contains the foundational components of the OS, demonstrating its capability to interact with FAT12 filesystems, read data from disks, and bootstrap its core functionalities. It showcases the following key features:

Bootloader: A hand-written bootloader that initializes the system and loads the kernel.
FAT12 Filesystem Support: Implementation of reading and parsing FAT12 file systems, including navigation of the directory structure and file retrieval.
Disk Operations: Efficient sector-based reading of data from disk images, leveraging BIOS interrupts and low-level memory management.
Modular Design: Carefully structured code for extensibility and readability, utilizing both assembly and C for a hybrid, low-level approach.
