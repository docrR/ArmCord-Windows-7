# ArmCord-Windows-7
Re-packaged ArmCord clients with Supermium Electron (currently v.28)

Supermium Electron may be obtained here: https://github.com/win32ss/supermium-electron/releases/tag/v28-testing

Supermium Electron is currently a work in progress. Expect some caveats. 

This currently supports Windows 7 and Windows Vista (with Extended Kernel).

How to reproduce this yourself:
- Download the x64 Supermium Electron archive
- Install ArmCord
- Replace all items (except resources) in the ArmCord install directory with the Supermium Electron archive
- Delete ArmCord.exe
- Execute electron.exe to open ArmCord
