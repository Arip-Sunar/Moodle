# Moodle
Adding the extra features and enabling Activity Tracking for the admin .Research work on Moodle
##Installationand set up  guide for forking and cloning MOODLE source code directly inside the VS code 
# Raylib Project Setup & Run Guide on Windows (Using MSYS2 UCRT Terminal)

Welcome to the **Raylib setup and run guide!**  
This document will walk you through installing MSYS2, setting up Raylib, and creating your first Raylib project on **Windows using the MSYS2 UCRT terminal.**

---

## 📌 What is Raylib?

Raylib is a simple and easy-to-use **C library** designed to help you learn game programming and graphics development.  
It's lightweight, beginner-friendly, and ideal for small game projects and graphical demos.

---

## ✅ Step 1: Install MSYS2

MSYS2 is a minimalist Unix-like environment for Windows, providing essential development tools via the Pacman package manager.  
We will use the **UCRT64 environment** of MSYS2, which supports modern Windows development.

### Installation Instructions:

1. Visit https://www.msys2.org/
2. Download the installer:  
   `msys2-x86_64-<version>.exe`
3. Run the installer and follow on-screen instructions.

---

## 📥 Step 2: Install Required Packages

Open **MSYS2 UCRT64 terminal** and run:

```sh
pacman -Syu
pacman -S mingw-w64-ucrt-x86_64-gcc
pacman -S mingw-w64-ucrt-x86_64-raylib
