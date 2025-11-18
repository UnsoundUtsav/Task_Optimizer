BACKGROUND TASK OPTIMIZER
=========================

A Python application that monitors and manages background processes with administrator privileges.

FEATURES
--------
- Process monitoring and termination
- Rule-based task management
- Automatic admin elevation
- Configurable modes via INI files
- Dynamic process restart

REQUIREMENTS
------------

Python Dependencies:
- Python 3.7 or higher
- psutil >= 5.9.0

System Requirements:
- Windows 7/8/10/11 (recommended)
- Administrator privileges for full functionality
- UAC (User Account Control) enabled

INSTALLATION
------------

1. Install Python dependency:
   pip install psutil

2. Run the application:
   task_Optimizer.exe

USAGE
-----

1. Run the program (it will automatically request admin privileges)

2. Select a mode from the available .ini files in the 'mode' folder

3. The program will monitor processes based on your rules

4. Controls during monitoring:
   - Press 'd' to stop completely
   - Press 'r' to restart and switch mode
   - Press Ctrl+C to exit

TROUBLESHOOTING
---------------

1. If admin elevation fails:
   - Right-click and "Run as administrator"
   - Check if UAC is enabled in Windows
   - Ensure you have admin rights on the computer

2. If processes aren't being terminated:
   - Run as administrator (required for system processes)
   - Check process names in Task Manager

3. If the program doesn't start:
   - Ensure Python is installed
   - Install required dependencies: pip install psutil