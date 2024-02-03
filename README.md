# POS System Installation Guide

This guide will help you set up the POS System V1.2.0 on your machine. Please follow the steps below carefully to ensure a smooth installation process.

## Prerequisites

Before installing the POS System V1.2.0, make sure you have the following software installed on your machine:

- .Net Framework 4.6.1
- SQL Server Express 2016
- Crystal Report Viewer 13.0.22

If any of the above software is missing, please install them before proceeding with the installation.

## Installation Steps

### Step 01

If the required software (.Net Framework 4.6.1, SQL Server Express 2016, and Crystal Report Viewer 13.0.22) is not installed, please install them before proceeding with the installation of the POS System V1.2.0.

### Step 02

Open "SQL Server Configuration Manager" and stop "SQL Server (SQLEXPRESS)" if it's running.

### Step 03

Navigate to the following location: `C:\Program Files\Microsoft SQL Server\MSSQL13.SQLEXPRESS\MSSQL\DATA` and paste the database files (`pos_system.mdf` and `pos_system_log.ldf`) there.

### Step 04

Double-click on "POS System Setup" and enter one of the serial numbers from the provided list.

### Step 05

Follow the instructions provided and proceed with the installation. Once prompted, show the "Configure SQL Connection" window.

### Step 06

- Server: .\SQLEXPRESS
- Uncheck the "Trusted Connection" checkbox.
- Username: genesip
- Password: genesip
- Database: Click the "..." button and select the "pos_system" database.
- Click "Install" and proceed with the installation.

### Step 07

After completing the installation, open the POS system using the desktop shortcut.

### Step 08

Use the default login details to access the system:
- Username: Admin
- Password: Admin

### Step 09

Now you can log in to the system and start working.

### Step 10

It's important to set up security questions for the admin account. Go to the "USERS" window, double-click the "Admin" data row, select a security question, provide an answer, and click the update button.

### Step 11

Don't forget to update the "Company details" as per your requirements.

### Step 12

Enjoy using the POS System V1.2.0!

---

Follow these steps carefully to ensure a successful installation of the POS System V1.2.0. If you encounter any issues during the installation process, feel free to reach out for assistance.
