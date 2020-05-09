#Hackintosh Catalina 10.15.4 (19E266) Installation Guide for MSI b360m bazooka motherboard & opencore EFI Folder

⚠️ Please Read the whole readme file for better understanding. Also I will share some tips and tricks.

My Hardware:
- CPU: Intel i5 8400 & 8600 (all processor without a graphic chip should work as well)
- GPU: Sapphire Radeon RX 580 4GB
- Motherboard: MSI b360m bazooka motherboard


What's Working?
- Sleep/Wake
- Ethernet
- Audio ALC892 (native AppleALC audio)
- iGPU Quick Sync + RX 580 GPU
- All USB ports (USB 2 + USB 3)
- Logitech G Hub support with G502 Mouse and G910 Keyboard
- 4K 60hz supported on HDMI 2.0 and DP 1.2

Additional information 
- Add Native DisplayBrightness to use F1 & F2 to controll brightness on MHL supported Monitor
- Use SoundSource to Adjust volume on DP port


bios setting：
-Load Optimized Defaults (optional)
-If your CPU supports VT-d, disable it 
-If your system has CFG-Lock, disable it
-Secure Boot Mode, disable it 
-If your system has IO Serial Port, disable it 
-Set XHCI Handoff to Enabled 
-Save & exit
