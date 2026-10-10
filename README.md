# QR Generator

**Version 1.0.0 | Windows Desktop Application**

A free, easy-to-use QR code generator for Windows, developed in C# using Windows Forms and the QRCoder NuGet library.

Create personalised QR codes, customise their appearance, add text labels and save high-quality PNG images.

**[Download QR Generator v1.0.0](https://github.com/tuckbloor/QR-Generator/releases/latest)**

---

## Features

- Generate QR codes from website addresses or plain text
- Custom foreground and background colours
- Built-in Windows colour picker
- Adjustable QR code width from 100 to 2,000 pixels
- Custom left, top and bottom margins
- Optional text above and below QR codes (up to 50 characters each)
- Automatically scaled label font size
- Four QR error correction levels
- Preview before downloading
- Export as PNG
- Windows installation wizard
- Start Menu shortcut and optional desktop shortcut
- Uninstaller included

## Minimum System Requirements

| Component | Requirement |
|---|---|
| Operating system | Windows 11 64-bit; compatible supported Windows 10 LTSC/Enterprise editions |
| Processor | x64-compatible processor |
| Framework | .NET 10 Windows Desktop |
| RAM | 4 GB recommended |
| Storage | At least 200 MB free recommended |
| Internet | Needed for initial download only |
| Administrator access | Required for installation for all users |

The installer is intended to include the required .NET runtime, so a separate .NET installation should not be necessary.

The application has been published for Windows x64. Other architectures have not been tested.

## Installation Instructions

**Step 1 — Download**

Visit the [latest GitHub release](https://github.com/tuckbloor/QR-Generator/releases/latest) and download:

`QRGenerator-Setup-1.0.0.exe`

**Step 2 — Install**

1. Double-click the downloaded installer.
2. Approve the Windows administrator permission prompt if you trust the installer.
3. Follow the installation wizard.
4. Choose whether to create a desktop shortcut.
5. Complete the installation.

**Step 3 — Launch**

Open **QR Generator** from your Start Menu or desktop shortcut.

## Windows Security Warning

### Why does Windows say "Windows protected your PC"?

Microsoft Defender SmartScreen may show a blue warning when launching the installer.

This can happen because QR Generator is a newly released application without an established publisher reputation or recognised code-signing signature.

**A warning does not automatically mean the application contains malware, but it is not proof that the file is safe either.**

Before proceeding:

- Download only from this project's official GitHub release.
- Check the downloaded filename.
- Keep Microsoft Defender enabled.
- Scan the file if you are unsure.
- Do not continue if the file or publisher is unexpected.

Some Windows configurations allow users to review additional information and choose whether to run an unrecognised application. Managed computers may prohibit this.

The publisher intends to investigate digitally signing future releases to improve installation trust.

## Using QR Generator

1. Enter a website address or text.
2. Set your preferred image width.
3. Click the foreground and background fields to select colours.
4. Set margins if needed.
5. Optionally enter a heading above or below the QR code.
6. Choose an error correction level.
7. Click **Generate**.
8. Preview the result.
9. Click **Download** to save your PNG image.

For the best scanning results, use a dark foreground against a light background and retain clear space around the QR code.

## Error Correction Levels

| Level | Approximate recovery capability |
|---|---|
| L — Low | 7% |
| M — Medium | 15% |
| Q — Quartile | 25% |
| H — High | 30% |

Medium is selected by default.

## Troubleshooting

**The application won't open**

Check that you're using a compatible 64-bit Windows system. If the application reports a missing runtime, contact the developer with the exact message.

**QR code won't scan**

Try black foreground on white background, increase the QR code size, and ensure the code has sufficient clear space around it.

**Installer is blocked**

Check that you downloaded the official installer. Security restrictions on managed PCs may require help from an administrator. Do not disable Windows security protections.

**PNG won't save**

Choose a folder where you have permission to save files, such as Documents or Pictures.

## Uninstalling

Open **Windows Settings → Apps → Installed apps**, find **QR Generator**, and select **Uninstall**.

## Technology

- C#
- .NET 10
- Windows Forms
- QRCoder
- System.Drawing
- Inno Setup

## Release History

### Version 1.0.0 — Initial Release

The first Windows release includes QR generation, custom colours, image sizing, margins, text labels, error correction, PNG downloads and a Windows installer.

## Developer

**TuckBloor**

[GitHub Repository](https://github.com/tuckbloor/QR-Generator)

For bug reports and feature suggestions, please use the GitHub Issues section.

---

*QR Generator v1.0.0 — Created with C# and Windows Forms.*
