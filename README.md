# ThinkCentre-M900-hackintosh
ThinkCentre M900 Hackintosh EFI.
This EFI will only work for macOS Monterey OR Big Sur. 
No support provided for Ventura or Sonoma **Natively**, EFI for Ventura and Sonoma will come out soon!!

Please have basic information about OpenCore, information about your hardware.
Do not point a finger at me if you mess up and brick your device I won't be responsible for any data loss or any other type of loss.

You can find how to setup a USB here: https://dortania.github.io/OpenCore-Install-Guide/installer-guide/


You can find the BIOS settings below:
(Credits: OpenCore Install Guide)

Intel BIOS settings
Note: Most of these options may not be present in your firmware, we recommend matching up as closely as possible but don't be too concerned if many of these options are not available in your BIOS
# Disable
Fast Boot
Secure Boot
Serial/COM Port
Parallel Port
VT-d (can be enabled if you set DisableIoMapper to YES)
Compatibility Support Module (CSM) (Must be off in most cases, GPU errors/stalls like gIO are common when this option is enabled)
Thunderbolt (For initial install, as Thunderbolt can cause issues if not setup correctly)
Intel SGX
Intel Platform Trust
CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable AppleXcpmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)
# Enable
VT-x
Above 4G Decoding
Hyper-Threading
Execute Disable Bit
EHCI/XHCI Hand-off
OS type: Windows 8.1/10 UEFI Mode (some motherboards may require "Other OS" instead)
DVMT Pre-Allocated(iGPU Memory): 64MB or higher
SATA Mode: AHCI




