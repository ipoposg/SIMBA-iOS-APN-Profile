# SIMBA iOS APN Profile

This profile enables **IPv6 connectivity** for SIMBA Telco users on iOS devices. By default, the general carrier profile provided by Apple only supports basic connectivity, leaving IPv6 unavailable. Installing this profile configures your device for SIMBA's **IPv4 and IPv6 network**, ensuring seamless dual-stack connectivity.

## Installation Instructions

1. Click on the `.mobileconfig` file in this repository.
2. Download the file directly onto your iOS device.
3. Follow the on-screen instructions to install the profile.

Once installed, your device will be configured to access SIMBA's full IPv4 and IPv6 network capabilities.

## Important Note

If you decide to use another telco's services, such as a travel eSIM or if you are porting out of SIMBA to another telco, you **must remove this profile** to ensure proper network configuration for the new provider. You can always reinstall the profile on your device if needed.

*Disclaimer: This repository is not affiliated with SIMBA Telecom Pte Ltd.*