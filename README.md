# Technical_Complaint_Reconciliation

Overview

This repository provides a Python script for comparing CCC and EDC Excel sheets. It includes a .desktop file to create a launcher for the script and an icon image for the launcher. This setup allows you to easily run the Python script from your Linux desktop environment.

Contents :-

    Technical_Complaint_Reconciliation.py: The Python script that performs the comparison of Excel sheets.
    Technical_Complaint_Reconciliation.desktop: A desktop entry file to create a launcher for the Python script.
    TCC_Icon.jpeg: The icon image used for the launcher.

Setup Instructions
1. Clone the Repository

Start by cloning this repository to your local machine:

git clone https://github.com/Anjali-Kumari-Mina/Technical_Complaint_Reconciliation

Navigate to the cloned directory:

cd your-repository-name

2. Prepare the Files

Download the Python Script and Icon:

    Place Technical_Complaint_Reconciliation.py in a directory of your choice.
    Save the TCC_Icon.jpeg icon file in the same directory or update the path in the .desktop file accordingly.

3. Modify the .desktop File:

    Download the Technical_Complaint_Reconciliation.desktop file from this repository.

    Open the .desktop file in a text editor.

    Update the Exec and Icon paths to match the locations of your Python script and icon. For example:

    [Desktop Entry]
    Name=Technical Complaint Reconciliation
    Comment=Compare CCC and EDC Excel sheets
    Exec=python3 "/path/to/your/Technical_Complaint_Reconciliation.py"
    Icon=/path/to/your/TCC_Icon.jpeg
    Terminal=false
    Type=Application
    Categories=Utility;

3. Set Permissions

Make sure the .desktop file is executable:

chmod +x /path/to/your/Technical_Complaint_Reconciliation.desktop
