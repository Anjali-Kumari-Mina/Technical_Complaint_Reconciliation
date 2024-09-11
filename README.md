# Technical_Complaint_Reconciliation


This project provides a desktop application for comparing CCC and EDC Excel sheets using a Python script.

## .desktop File

The `.desktop` file allows you to create a launcher for your Python script on Linux desktop environments.

### Instructions

1. **Download the Python Script and Icon:**
   - Place `Technical_Complaint_Reconciliation.py` in a directory of your choice.
   - Save the `TCC_Icon.jpeg` icon file in the same directory or update the path in the `.desktop` file accordingly.

2. **Modify the `.desktop` File:**
   - Download the `Technical_Complaint_Reconciliation.desktop` file from this repository.
   - Open the `.desktop` file in a text editor.
   - Update the `Exec` and `Icon` paths to match the locations of your Python script and icon. For example:
     ```ini
     [Desktop Entry]
     Name=Technical Complaint Reconciliation
     Comment=Compare CCC and EDC Excel sheets
     Exec=python3 "/path/to/your/Technical_Complaint_Reconciliation.py"
     Icon=/path/to/your/TCC_Icon.jpeg
     Terminal=false
     Type=Application
     Categories=Utility;
     ```

3. **Set Permissions:**
   Make sure the `.desktop` file is executable:
   ```bash
   chmod +x /path/to/your/Technical_Complaint_Reconciliation.desktop
