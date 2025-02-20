# Nomoresurf Releases

This repository contains official releases for **Nomoresurf**, a productivity-focused website blocker for macOS.

## Overview

Nomoresurf is a productivity website blocker that helps you block distracting websites and make it harder to unblock them. It is designed to help you focus on your work and avoid distractions.

## Downloads & Installation

Find the latest releases under the [Releases](https://github.com/adamity/nomoresurf-desktop-releases/releases) section.

## App Signing & Gatekeeper Bypass

Currently, the app is not signed due to a limited budget. If you try to open it, macOS will block it because the app is unsigned. If you really want to use it, you’ll need to bypass Gatekeeper by right-clicking the app, selecting Open Anyway, and then manually signing it using the command below:

```bash
codesign --deep --force --verbose --sign - "/path/to/Application Name.app"
```

## Support

Since I don’t have the budget for an Apple Developer ID yet, I plan to release the app on the App Store in the future. If you’d like to support this, consider [donating](https://buymeacoffee.com/consistentcat) to help me cover the costs.

## More Information

Visit the [official website](https://nomoresurf.com/) for additional resources.

## License

This project is distributed under an appropriate license. Refer to the LICENSE file for details.

## Disclaimer

Use Nomoresurf responsibly and understand the implications of its blocking features.