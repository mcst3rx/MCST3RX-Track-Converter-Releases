
# 🏁 MCST3RX Track Converter

**Convert. Create. Race Your Way.**

The **MCST3RX Track Converter** is an independent Windows desktop application designed to inspect racing-game track assets, analyze track structures, and develop conversion workflows for NASCAR 26.

The long-term goal is to convert supported tracks from other racing games into NASCAR 26-compatible track packages that can be installed using a compatible third-party Mod Manager.

> **Development Version:** v0.3.0  
> **Public Release:** Not Yet Available  
> **Platform:** Windows x64  
> **NASCAR 26 Track Conversion:** Under Development  
> **Source Code:** Private

**Important:** The current application does not yet generate verified playable NASCAR 26 tracks. Track inspection and experimental interchange conversion are separate from full game compatibility.

---

## 📥 Download

Official Windows builds will be distributed through the **Releases** section of this repository after development, validation, and owner acceptance are complete.

➡️ **Go to Releases:**  
https://github.com/mcst3rx/MCST3RX-Track-Converter-Releases/releases

**No public release has been approved yet.**

### Planned Windows Download

The first approved Windows release is intended to provide a portable ZIP containing:

- `MCST3RX Track Converter.exe`
- Bundled Electron runtime
- Bundled Python runtime and required dependencies
- Required application resources
- Release notes
- SHA-256 verification information
- Third-party dependency notices

The portable application is designed to work without requiring users to install Node.js or Python separately.

### Verify Your Download

Official releases should include SHA-256 checksums to verify downloaded files.

Only download MCST3RX Track Converter from official MCST3RX distribution channels.

The privately validated v0.2.0 executable is unsigned. Future releases will disclose their signing status.

Do not disable antivirus or Windows security protections to run the application.

---

## ✨ Features

MCST3RX Track Converter is being developed as an offline-first racing track inspection and conversion utility.

### 🏎️ Assetto Corsa

- KN5 v5/v6 inspection within supported limits
- Track metadata inspection
- Static model and geometry analysis
- Experimental static geometry export
- glTF interchange output for supported assets
- Source-file preservation
- Validation and error reporting

### 🏁 NASCAR Heat 5

- UnityFS/SAB container inspection
- Track asset metadata analysis
- Mesh, material, and texture inventories
- Bounded and paginated metadata inspection
- Selected-instance dependency tracing
- Resource-budget protection
- Malformed-file rejection
- Experimental synthetic UnityFS conversion

### 🛠️ Desktop Application

- Professional MCST3RX Windows interface
- Dark theme with turquoise accents
- Seven application sections
- Track source selection
- Track File Inspector
- Conversion Readiness
- Conversion Workspace
- Validation Reports
- Settings and Tool Detection
- Offline operation for supported workflows
- Local validation reports

**Experimental functionality is clearly identified and does not guarantee playable NASCAR 26 output.**

---

## 🏎️ Supported Games & Formats

| Game | Format | Current Status |
|---|---|---|
| Assetto Corsa | `.kn5` | Inspection and experimental static geometry export |
| NASCAR Heat 5 | `.sab` / UnityFS | Metadata inspection and dependency analysis |
| NASCAR 26 | Unreal Engine cooked assets | Full conversion under research |

### NASCAR Heat 5 Track Research

Development research has examined:

- Canadian Tire Motorsport Park (Mosport)
- Kentucky Speedway
- Mid-Ohio Sports Car Course

These tracks are research targets.

They have **not** been confirmed as playable NASCAR 26 conversions.

---

## 🔄 Planned NASCAR 26 Conversion Workflow

The intended workflow is:

1. Select a supported racing-game track source.
2. Inspect the source track and its assets.
3. Extract and convert supported geometry and dependencies.
4. Prepare NASCAR 26-compatible Unreal Engine track assets.
5. Generate a compatible custom track ZIP.
6. Install the completed ZIP using a compatible NASCAR 26 Mod Manager.
7. Validate the track in NASCAR 26.

**This complete workflow is not yet implemented.**

MCST3RX Track Converter does not currently produce verified NASCAR 26 track packages containing all required Unreal levels, physics, AI racing data, pit systems, timing, and gameplay integration.

The third-party Mod Manager is a separate application and is not included with this tool.

---

## 🛡️ Source File Safety

Source-file integrity is a core design principle of MCST3RX Track Converter.

The supported inspection workflows use safeguards including:

- Read-only source inspection
- Source hashing and validation
- Bounded resource usage
- Malformed-file rejection
- Permission and export restrictions
- Isolated conversion workspaces
- Validation reports
- Protection against unsupported operations

The application is not intended to modify installed racing games during source inspection.

Always maintain independent backups of important files.

Do not bypass unsupported-format, authorization, or resource-limit warnings.

---

## 🚀 Installing

### Portable Windows Version

When an official portable release becomes available:

1. Open the **Releases** section.
2. Download the approved Windows portable ZIP.
3. Extract the complete ZIP to a folder of your choice.
4. Open the extracted folder.
5. Launch `MCST3RX Track Converter.exe`.
6. Select a supported track source.
7. Use the available inspection and validation features.

**Keep all bundled runtime files together.**

Do not run the executable directly from inside the ZIP archive.

### Windows Installer

A Windows installer may be considered in a future release.

No installer is currently promised.

---

## 📝 Release Notes

Every public release will include notes describing:

- New features
- Supported source formats
- Conversion improvements
- Bug fixes
- Performance improvements
- Compatibility changes
- Newly validated functionality
- Known limitations

Experimental features will be distinguished from completed and validated functionality.

---

## ⚠️ Known Limitations

- Full NASCAR 26 track conversion is not yet available.
- Real NASCAR Heat 5 geometry export remains restricted.
- Some UnityFS materials, textures, and dependencies are unsupported.
- Large source files are subject to resource limits.
- Some KN5 versions and extensions are unsupported.
- glTF export alone does not create a playable NASCAR 26 track.
- NASCAR 26 Unreal cooking and gameplay integration remain unresolved.
- Custom track ZIP acceptance by the existing Mod Manager requires further validation.
- Not all source tracks can be converted automatically.

These limitations will be updated as development progresses.

---

## 💬 Bug Reports & Feature Requests

Found a problem with MCST3RX Track Converter or have an idea for an improvement?

➡️ **Submit an Issue:**  
https://github.com/mcst3rx/MCST3RX-Track-Converter-Releases/issues/new/choose

Choose the appropriate template when available:

- 🐛 **Bug Report** — Report an application error or unexpected behavior.
- 💡 **Feature Request** — Suggest an improvement or new workflow.

### 🐛 Reporting a Bug

Before submitting a bug report:

- Check whether the problem has already been reported.
- Include your application version.
- Identify the source game and file format.
- Explain the steps needed to reproduce the problem.
- Include the exact error message when applicable.
- Attach screenshots or a short recording when helpful.
- Do not publicly upload copyrighted game assets or sensitive files.

### 💡 Requesting a Feature

Before submitting a feature request:

- Check existing issues.
- Describe the requested feature clearly.
- Explain how it would improve the application.
- Include examples or screenshots when useful.
- Submit one request per issue.

Feature requests are suggestions and are not guaranteed to be implemented.

---

## 🔒 Source Code

**MCST3RX Track Converter is not an open-source project.**

This public repository exists for:

- Official compiled releases
- Windows downloads
- Release documentation
- Bug reports
- Feature requests
- Community support

Application source code is maintained separately in a private development repository.

The applicable application license will define permitted use and redistribution before public distribution.

---

## ☕ Support MCST3RX

MCST3RX Track Converter is being developed as a community tool.

If you would like to support continued development:

**Ko-fi:** https://ko-fi.com/mcst3rx

Support is optional and does not currently unlock Track Converter features.

Any future licensing changes will be documented separately.

---

## 🌐 Community

**YouTube**  
https://www.youtube.com/@mcst3rx

**Discord**  
https://discord.gg/TyVaFfSsnT

Follow development updates, tutorials, feature previews, release announcements, and future track compatibility research.

---

## ⚠️ Disclaimer

MCST3RX Track Converter is an independent community-developed application.

It is not affiliated with, endorsed by, sponsored by, or associated with NASCAR, iRacing, Motorsport Games, 704Games, Kunos Simulazioni, game publishers, or other official rights holders.

Third-party names, trademarks, logos, and game assets remain the property of their respective owners.

Users are responsible for ensuring they have the necessary rights to use and convert source assets.

No racing game or third-party Mod Manager is included.

---

## ❤️ Built for the Community

**MCST3RX Tools**

*Built by players, for the community.*

**Convert. Create. Race Your Way.**
