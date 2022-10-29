# Windows Powertool
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Windows powertool is a windows 10 and 11 utility designed to provide one click solution to reduce and trim down unnecessary burden that comes by default with windows. 

From user prospective most things are useless like Ads, Telemetry which is microsoft data collection service, Bloatware which are preinstalled sponsored apps, User activity history, diagnostic tracking services, Cortana and many more.
Windows powertool help you to Improve speed, remove bloatware, protect privacy, eliminate data collection and more.

## View Source code
Windows Powertool Source code :  [tool.windowspowertool.workers.dev](https://tool.windowspowertool.workers.dev)

## How to use
Use the following command in Powershell to start Windows Powertool OR view the source code and use that raw code in powershell.<br />
it automatically Create a System restore point when you click Optimize. This allow you to revert back completely, if you want. (undo Optimization)  
```
iwr -useb tool.windowspowertool.workers.dev | iex
```

## Main Features
### Optimization
1. Optimize
2. Revert Optimize
3. Set Services to Manual

### Removal Section
1. Remove/reinstall Bloatwares
2. Remove/reinstall OneDrive
3. Remove/reinstall Microsoft Store

### System Setting (Disable and Enable)
1. Power Throttling
2. Dark / Light Mode
3. Cortana
4. System Animation
5. Ultra Power Mode
6. Action center
7. User Activity History
7. StartMenu web Search
8. Timer Resolution
9. Background apps
10. Network Performance
11. News and Interests
12. Disk Cleanup
13. Reset Windows Update

### Backup / Restore
1. Create system restore point
2. Restore the system restore point


# Known Issues
* Read the Warning carefully before removing OneDrive. if you have enabled and logged in OneDrive then be aware that your desktop files may lose. log out from OneDrive for safer removal.
* You may experiance slow first or second restart/reboot after apply optimization, which is temporary.

# Knowledge base
* Removing bloatware does not remove xbox and it related files.
* Applying Optimization will also enable Quick animation, which can be set to default animation from system setting.
* Most setting take effects in windows local user, Run individually for other user.
