# os

# Windows Operating System Lab Exercises

## 1. Exploring the OS Interface

### Navigating the File System

1. Open **File Explorer** from the taskbar or press `Windows + E`.
2. On the left, you'll see **Quick Access**, **This PC**, and other main folders.
3. **Quick Access** shows frequently used folders and recent files.
4. **This PC** shows you the main drives and devices connected to your computer.
5. By clicking on folders, you can navigate deeper into the directory structure. Clicking on the backward arrow at the top takes you back to the previous directory.

   > **Task**: Navigate to the `Documents` folder and take a screenshot.

### Adjusting System Settings

1. Open **Settings** by clicking on the Start Menu and selecting the gear icon.
2. You'll see various categories: System, Devices, Phone, Network & Internet, etc.
3. **System**: Here you can adjust display settings, notifications, power options, and more.
4. **Devices**: Manage printers, mouse, keyboard, and other connected devices.
5. **Network & Internet**: Connect to Wi-Fi, manage VPN, and view network properties.

   > **Task**: Adjust your display brightness and take a screenshot of the setting.

## 2. Command Line Basics

### Opening the Command Prompt

1. Press `Windows + R`, type `cmd`, and hit Enter.

### Basic Commands

- **Changing Directory**: `cd path_to_directory`. Example: `cd Documents`.
- **Listing Files/Folders**: `dir`.
- **Changing Drive**: To switch to the D drive, simply type `D:` and press Enter.
- **Creating a New Directory**: `mkdir new_directory_name`.
- **Removing a Directory**: `rmdir directory_name`.
- **Viewing Contents of a File**: `type filename.txt`.
- **Help on Commands**: `help` or specific command help using `command_name /?`.

   > **Task**: Create a new directory named `OSLab` in the `Documents` folder and take a screenshot.

## 3. Basic Scripting (using Batch files)

1. Create a new text document (Right-click on the desktop or in File Explorer > New > Text Document).
2. Rename it to `myscript.bat`.
3. Right-click on it and select Edit.
4. Type the following:
    ```batch
    echo Hello, world!
    pause
    ```
5. Save and double-click the batch file to run it.

   > **Task**: Take a screenshot of the command prompt after running the batch file.

## 4. Process Monitoring

1. Press `Ctrl + Shift + Esc` to open Task Manager.
2. Here you can see the processes running, their CPU, Memory, and Disk usage.

   > **Task**: Take a screenshot of the Processes tab in Task Manager.

## 5. Memory Management

1. In **Task Manager**, go to the Performance tab.
2. Here you can see memory usage, CPU statistics, and more.

   > **Task**: Take a screenshot of the Memory section in the Performance tab.

## 6. Disk Management

1. Press `Windows + R`, type `diskmgmt.msc`, and press Enter.
2. This opens the Disk Management tool.

   > **Task**: Take a screenshot showing your drives and their partitions.

## 7. Networking Commands

- **ping**: Check if a website or IP is reachable. Example: `ping www.google.com`.
- **tracert**: Trace the route packets take to reach a website or IP. Example: `tracert www.google.com`.
- **ipconfig**: View your computer's network configuration and IP address.

   > **Task**: Run the `ipconfig` command and take a screenshot of the output.

## 8. Installing Software

1. Navigate to the software's official website.
2. Download the `.exe` or `.msi` installer.
3. Double-click the downloaded file and follow the installation instructions.

   > **Task**: Install a software of your choice and take a screenshot of the installation progress or completion page.

## 9. User Account Management

1. Open **Control Panel** (you can search for it in the Start Menu).
2. Go to **Administrative Tools** > **Computer Management** > **Local Users and Groups**.

   > **Task**: Take a screenshot of the User Accounts list.

## 10. Understanding System Logs

1. Press `Windows + R`, type `eventvwr.msc`, and press Enter.
2. This opens the Event Viewer.

   > **Task**: Navigate to the System logs, choose an event, and take a screenshot.

## 11. Exploring OS Virtualization

1. Download and install VirtualBox.
2. Download an OS ISO (like a Linux distribution).
3. In VirtualBox, create a New Virtual Machine.
4. Follow the steps, allocating RAM, hard disk space, and when asked, point to the downloaded ISO.
5. Start the virtual machine and proceed with the OS installation in the virtual environment.

   > **Task**: Take a screenshot of the OS installation process inside the virtual machine.

---

**Note**: For each task, make sure to save your screenshots with meaningful names and submit them as per your instructor's guidelines.
