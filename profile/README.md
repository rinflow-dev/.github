**Rinflow** shares one keyboard and mouse between your Mac, Windows and Linux computers. Push the pointer past a screen edge, and it continues on the next one.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rinflow-dev/rinflow/main/images/platforms-en-US-dark.png">
    <img src="https://raw.githubusercontent.com/rinflow-dev/rinflow/main/images/platforms-en-US-light.png" alt="Rinflow's device window on macOS, Windows and Linux">
  </picture>
</p>

**Download:** [macOS](https://github.com/rinflow-dev/rinflow-macos/releases/latest) · [Windows](https://github.com/rinflow-dev/rinflow-windows/releases/latest) · [Linux](https://github.com/rinflow-dev/rinflow-linux/releases/latest)

## Why Rinflow

- **Fast.** Your input goes from the system to the network in compiled native code, and one Rust library does the networking on every platform. There is no browser engine or interpreter on the way.
- **Native.** Each app is written with its system's own toolkit: SwiftUI on macOS, WinUI 3 on Windows, GTK 4 on Linux. It looks and behaves like the system around it, and the download is 3 to 18 MB.
- **Easy to set up.** Devices find each other on your local network. To pair two of them, check that both show the same six-digit code.
- **No server.** Every computer is equal: any of them can control the others, and be controlled.
- **Clipboard and files.** Copy text, images or files on one computer and paste them on another.
- **Encrypted.** Every connection uses TLS 1.3.

## Repositories

| Repository | Contents |
| --- | --- |
| [rinflow-macos](https://github.com/rinflow-dev/rinflow-macos) | macOS app (Swift) |
| [rinflow-windows](https://github.com/rinflow-dev/rinflow-windows) | Windows app (Rust, WinUI 3) |
| [rinflow-linux](https://github.com/rinflow-dev/rinflow-linux) | Linux app (Rust, GTK 4) |

Free and open source, under the [Mozilla Public License 2.0](https://www.mozilla.org/MPL/2.0/).
