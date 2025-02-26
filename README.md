
# Terminal Context Menu for Windows

This repository provides a Windows Registry file that adds a unified Terminal context menu to both the Desktop and Directory backgrounds in Windows Explorer. With this script, you can quickly open various terminal applications directly from the context menu, streamlining your workflow.

----------

## Features

-   **Unified Terminal Menu:**  
    Adds a single "Terminal" entry to the right-click context menu on both the desktop and within directory backgrounds.
    
-   **Multiple Shell Options:**  
    Choose from several terminal options:
    
    -   **Command Prompt**
    -   **PowerShell**
    -   **PowerShell 7**
    -   **Git Bash**
-   **Admin Mode Variants:**  
    Each shell option includes an administrative version that launches with elevated privileges.
    
-   **Custom Icons and Commands:**  
    Each context menu entry features its own icon and customized command to launch the terminal in the current directory.
    
-   **Clean Context Menu:**  
    Hides the default Windows context menu entries for Command Prompt, PowerShell, Windows Terminal, and Git Bash to reduce clutter.
    
![alt text](https://github.com/Antariksh-Singh-07/Complete-Terminal-Context-Menu/blob/main/image.png?raw=True "Overview Example Image")

----------

## Installation

1.  **Backup Your Registry:**  
    Before applying any changes, ensure you back up your registry or create a system restore point.
    > Registry Editor < File < Export...
    
2.  **Merge the Registry File:**
    
    -   Double-click the `.reg` file (`complete-terminal-context-menu.reg`).
    -   Confirm any prompts to merge the file into your Windows Registry.
3.  **Restart Windows Explorer (if necessary):**  
    Changes should take effect immediately; however, if you do not see the new context menu, try restarting Windows Explorer through task manager or rebooting your system.
    

----------

## Usage

After installation, right-click on any empty space on your Desktop or within a folder background. You will see a "Terminal" option with a submenu that lets you select the desired terminal application (normal or admin mode). The chosen terminal will open with its working directory set to the current folder.

----------

## Customization

-   **Modifying Paths:**  
    If your installations of Git Bash or PowerShell 7 are in non-default locations, adjust the paths in the registry file accordingly.
    
-   **Removing Options:**  
    To remove a specific terminal option, either edit the registry file before merging or manually delete the corresponding registry keys after installation.

-   **Adding Options:**  
    To add a specific terminal option, either edit the registry file before merging or manually add the corresponding registry keys after installation.
    

----------

## Uninstallation

To revert the changes, you can run the uninstall reg provided, or manually remove the added registry entries, or restoring from a backup or using a system restore point is recommended if you wish to undo the modifications.

----------

## Disclaimer

**Warning:** This registry file modifies system settings and should be used with caution. Ensure you back up your registry before making any changes. The author is not responsible for any damage or system issues that may occur as a result of using this file. Use at your own RISK.

----------

## Contributing

Contributions, bug reports, and feature suggestions are welcome. Feel free to open an issue or submit a pull request with your improvements.

----------

### Enjoy!
