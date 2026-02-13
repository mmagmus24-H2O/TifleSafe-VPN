🛡️ TifleSafe VPN
A Discord-inspired VPN client with built-in encrypted media chat.

TifleSafe is a high-performance, WPF-based VPN utility designed for users who want a familiar, social interface while maintaining absolute privacy. It combines a sleek "Discord-Blurple" UI with persistent background protection and a local-first chat system.

✨ Key Features
Discord-Style UI: Familiar sidebar navigation, animated server icons, and a dark-mode aesthetic built from the ground up in C#.

Persistent IP Protection: Built-in hardware-locked login system. If the app is moved to another PC, it requires re-authentication to prevent account theft.

Advanced Media Chat: An integrated chat system that supports:

Images: Automatic rendering of .jpg and .png.

Video & Audio: Play .mp4 and .mp3 files directly within the chat feed.

Local Assets: All shared files are organized in a dedicated TifleAssets directory.

Always-On Security: Includes a classic-style installer that can configure the app to run on Windows startup, ensuring your IP is protected from the moment you log in.

Floating VPN Toggle: A sleek, glowing FAB (Floating Action Button) allows you to toggle the VPN tunnel without interrupting your workflow.

🚀 Installation & Setup
Download: Grab the TifleSafe_Setup.exe from the Releases page.

Classic Installer: Run the 98-style wizard. Make sure to check "Always run in background" for 24/7 IP protection.

Authentication: On first launch, create your local account. Your data is encrypted and bound to your specific PC hardware.

🛠️ Technical Details
Language: C#

Framework: .NET Framework 4.8 / WPF

Networking: System.Net.Http with asynchronous IP tunneling logic.

UI Logic: Custom XAML templates with DoubleAnimation for smooth, responsive transitions.

📁 Project Structure
TifleData/: Stores your encrypted account credentials and hardware keys.

TifleAssets/: The local database for all media sent through the chat.

tiflesafe.ico: High-resolution application branding.
