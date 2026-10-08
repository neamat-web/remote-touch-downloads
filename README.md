# Remote Touch — Windows pilot

[Download for Windows](https://github.com/neamat-web/remote-touch-downloads/raw/refs/heads/main/RemoteTouch-Setup.zip) · [Open Remote Touch](https://remote-touch.onrender.com)

1. Download RemoteTouch-Setup.zip and extract it completely.
2. Open Start.cmd on Windows 11. First launch automatically downloads and verifies the official Node.js runtime (about 35 MB). Then click Start.
3. Open the website on your phone, tablet or computer. Enter the Computer ID and temporary Access code.
4. Approve the request on Windows. Click STOP / DISCONNECT to end access.

No certificate installation or router setup is required. Keep the host open and the computer awake.

This is an unsigned experimental pilot. The free relay can take about a minute to wake and may assign new Computer IDs after a restart. Audio, unattended access and lock/UAC-screen control are not available. HTTPS terminates at the relay; traffic is not end-to-end encrypted. Physical-device WAN acceptance testing is still pending.

Verified: 14 Node tests, Windows CI build and protected identity check, public HTTPS client loading, runtime download and checksum verification, and execution of the downloaded Node runtime.
