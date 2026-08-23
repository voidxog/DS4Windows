# DS4Windows

DS4Windows is a portable, extract-anywhere application that gives you the best **DualShock 4 experience on Windows**. By emulating an Xbox 360 controller, DS4Windows makes your controller compatible with many more games.

Other controllers are supported as well, including:

- 🎮 DualShock 4
- 🎮 DualSense
- 🎮 Nintendo Switch Pro Controller
- 🎮 Joy-Con controllers

> **Note:** Only first-party Nintendo hardware is supported.

This project is a fork of the original work by **Jays2Kings**.

![DS4Windows Preview](https://raw.githubusercontent.com/voidxog/DS4Windows/refs/heads/main/ds4_screen.png)

---

## 📜 License

DS4Windows is licensed under the terms of the **GNU General Public License v3.0**.

You can read the full license here:

[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.txt)

A copy of the license is also included in this repository as [`COPYING`](./COPYING).

---

## 📦 Downloads

Get the latest builds from the GitHub Releases page:

**[⬇️ Download DS4Windows](https://github.com/voidxog/DS4Windows/releases)**

---

## 💻 Requirements

### Operating System

- **Windows 10 or newer**

### .NET Desktop Runtime

- **Microsoft .NET 10.0 Desktop Runtime**
- [Download for Windows x64](https://dotnet.microsoft.com/en-us/download/dotnet/10.0)

> **Note:** DS4Windows requires the **Desktop Runtime**, not the ASP.NET Core Runtime or .NET Runtime.

### Visual C++ Redistributable

- **Microsoft  Visual C++ 2015–2022 Redistributable**

- [Download for Windows x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)

### ViGEmBus (This project has retired)

[ViGEmBus](https://github.com/nefarius/ViGEmBus) is required for virtual controller emulation.

> **DS4Windows will install the ViGEmBus driver for you.**

---

## 🎮 Supported Controllers

DS4Windows supports a variety of controllers, including:

| Controller | Support |
|---|:---:|
| Sony DualShock 4 | ✅ |
| Sony DualSense | ✅ |
| Nintendo Switch Pro Controller | ✅ |
| Nintendo Joy-Con | ✅ |
| Other compatible controllers | ⚠️ |

> Nintendo controller support is limited to **first-party hardware**.

---

## 🔌 Connection Methods

You can connect your controller using:

### USB

- Micro USB
- USB Type-C

### Bluetooth

Bluetooth 4.0 or newer can be used through:

- Built-in Bluetooth
- A compatible USB Bluetooth adapter
- Sony Wireless Adapter

> **Important:** Only the **Microsoft Bluetooth stack** is officially supported.

CSR Bluetooth stacks are confirmed to cause compatibility issues with the DS4, although some CSR-based adapters can work when configured to use the Microsoft Bluetooth stack.

Toshiba Bluetooth adapters are currently **not supported**.

### Sony Wireless Adapter

You can also use the official Sony Wireless Adapter

---

## ⚙️ Troubleshooting Bluetooth & Latency

If you're experiencing latency or connectivity issues, try disabling:

> **Enable output data**

This option can be found in the controller profile settings.

⚠️ **Disabling it will also disable lightbar and rumble support.**

---

## 🎮 Steam Configuration

If you're using DS4Windows with Steam, disable the following Steam Input options:

- ❌ **PlayStation Configuration Support**
- ❌ **Xbox Configuration Support**

This prevents Steam from interfering with DS4Windows' virtual controller.

---

## 🚀 Getting Started

1. **Download** the latest DS4Windows build from [Releases](https://github.com/voidxog/DS4Windows/releases).
2. Install the required **.NET Desktop Runtime**.
3. Launch DS4Windows.
4. Connect your controller via **USB or Bluetooth**.
5. Install **ViGEmBus** if prompted.
6. Configure your controller profile.
7. Start playing. 🎮

---

<div align="center">

**DS4Windows — Like those other DS4 tools, but sexier.**

</div>
