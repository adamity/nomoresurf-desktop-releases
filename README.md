# Nomoresurf Releases

This repository contains official releases for **Nomoresurf**, a productivity-focused website blocker for macOS.

## Overview

**Nomoresurf** helps you stay focused by blocking distracting websites and making it harder to unblock them.

## Downloads & Installation

Find the latest version under the [Releases](https://github.com/adamity/nomoresurf-desktop-releases/releases) section.

### Installation Steps

1. Download the latest `.dmg` file.
2. Open the downloaded file.
3. Drag the app into the **Applications** folder.
4. Open **Nomoresurf** from the **Applications** folder.

## Bypassing Gatekeeper (App Not Signed)

Since the app is not yet signed, macOS will block it by default. To run it anyway:

1. Open **Terminal** and enter:

   ```bash
   codesign --deep --force --verbose --sign - "/Applications/Nomoresurf.app"
   ```

2. Try opening the app by double-clicking it.
3. macOS will show a warning:
   _"“Nomoresurf” Not Opened: Apple could not verify “Nomoresurf” is free of malware that may harm your Mac or compromise your privacy."_
4. Click Done to close the warning.
5. Open System Settings → Privacy & Security.
6. Under Security, find the message about Nomoresurf being blocked.
7. Click Open Anyway.
8. Try opening the app again.

## Support & Future Plans

I plan to release Nomoresurf on the Mac App Store once I can cover the costs of an Apple Developer ID.

If you’d like to support this effort, consider [donating](https://buymeacoffee.com/consistentcat).

## More Information

Visit the [official website](https://nomoresurf.com/) for additional details.

## License

This project is licensed under an appropriate license. See the LICENSE file for details.

## Disclaimer

Use Nomoresurf responsibly. Be aware of its blocking features and how they affect your workflow.
