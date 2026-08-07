SB SSD Temps v1.33 RC

<img width="1920" height="1080" alt="Screenshot 2026-08-06 211555" src="https://github.com/user-attachments/assets/abb3a39d-ba9b-4b56-ae2b-6e29aa54d01c" />

<img width="1920" height="1080" alt="SB_SSD_Temps_Desktop_20260806_190957" src="https://github.com/user-attachments/assets/8046ac8f-8f1f-491c-bb9e-39030b20ef24" />

SB_SSD_Temps_v1.33.exe

SHA-256
1F2A363A7164B0679D17F26B598729BCF31A7891B3E2486DF5D100EC5E7DA148
NOTE: May need to run as administrator because the app access data through third party apps for accuracy.

• Added a new Sensor Thresholds window with expanded NVMe SMART threshold information and explanations.
• Added session-based memory for TACH window size and position on a per-drive basis.
• TACH windows now reopen in their previous location while remaining on a visible monitor.
• Redesigned the Thermal Info, Threshold Info, Support, About, and Info windows.
• Fixed overlapping controls and partially hidden Close buttons.
• Restored the main application's Always on Top behavior while maintaining screenshot functionality.
• Improved window resizing and overall interface consistency.
• Added a portable single-file executable build.
• Digitally signed using Microsoft Azure Trusted Signing (SHA-256 with trusted timestamp).

OLDER VERSIONS NOTES/UPDATES ---->
v1.32
SHA-256 Checksums

EXE
C769BAE458B8C6BB186237F77EA631E6E04DC36A91C47D9F7F81FCE38629B0A9

ZIP
3E1F11BE0AAB19F630E45CB99B1CF752AF40330A9A525604A0E51733140CC989

SB SSD Temps v1.32 greatly expands drive-temperature monitoring while preserving the application’s read-only design. This release is available as a signed, single-file portable Windows executable.

NOTE: May need to run as administrator because the app access data through third party apps for accuracy. Windows reporting alone is not adequate nor accurate.

OLDER VERSIONS - v1.32 and below --->

* Displays every readable temperature sensor reported by the selected drive.
* Keeps the primary NAND, Controller, and Composite cards visible, showing `N/A` when a channel is unavailable.
* Automatically adds separate cards for additional temperature sensors.
* Expands the main sensor layout horizontally while maintaining responsive card rows.
* Adds all available temperature channels to Mini Temps.
* Adds per-sensor thermal status indicators:

  * **NORMAL**
  * **WARNING**
  * **DANGER**
  * Flashing **CRITICAL**
* Adds an adjustable 20–100°C early-warning slider.
* Auto warning begins 10°C before the drive-reported warning threshold.
* Custom warning settings reset to Auto when another drive is selected.
* Adds Composite Thermal History with:

  * Current Drive
  * Selected Drives
  * All Drives
* Reads NVMe Warning-Temperature Time and Critical-Temperature Time directly from the drive’s standard SMART/Health log through Windows when supported.
* Shows valid `0 min` readings separately from unsupported `N/A` fields.
* Adds a concise `T-TIME INFO` explanation covering the counters, data source, firmware thresholds, and prolonged high-temperature risk.
* Adds rounded borderless windows with drag-to-reposition support.
* Improves resizing, redraw smoothness, icon rendering, and child-window shutdown behavior.
* Locks Mini Temps and Mini Tachs borders to protect their layouts.
* Consolidates accent, RGB, and background controls under **APP COLORS**.
* Updates the built-in Support pages for the new sensors, warnings, Thermal History, and compatibility behavior.

### Portable Signed Release

`SB_SSD_Temps_v1.32_PORTABLE.exe` is a signed, single-file portable build. It contains the application, runtime libraries, assets, and documentation inside one executable.

No installation is required:

1. Download the portable EXE or ZIP.
2. Optionally verify its SHA-256 checksum.
3. Run `SB_SSD_Temps_v1.32_PORTABLE.exe`.
4. Approve the Windows administrator prompt required for direct hardware-sensor access.

The portable application extracts its private runtime payload under the current user’s Local AppData directory. It does not require the original ZIP, an adjacent runtime folder, or a separate PowerShell script.

### Requirements

* 64-bit Windows 10 or Windows 11
* Administrator permission
* A storage device exposing readable temperature information

NVMe SSDs, SATA SSDs, and mechanical hard drives may be listed. Available sensors, thresholds, health information, and temperature-time counters depend on what the drive firmware, controller, adapter, and Windows storage path expose.

### Read-Only Operation

SB SSD Temps monitors information only. It does not benchmark, write to, optimize, configure, or control the selected drive. It does not control fans, RGB hardware, TEC modules, or cooling equipment.


### Public Testing

Additional drive models and unusual sensor layouts are especially useful for testing. If a drive is missing, mislabeled, displays unexpected sensors, or reports `N/A`, please include:

* Drive model
* Windows version
* Application screenshot
* `SB_SSD_Temps_Storage_Report.txt` created with **Sensor Details**

Reports help improve compatibility without requiring the application to collect or transmit telemetry.




SB SSD Temps v1.31

Version 1.31 introduces an officially signed release of SB SSD Temps.

What’s included
Digitally signed by Jon Bauer / ShrimpBrime
Signed through Microsoft Azure Artifact Signing
Microsoft timestamped for long-term signature validity
Verified successfully with Windows SignTool
Tested after signing to confirm normal operation
Portable—no installation required

Download SB_SSD_Temps_v1.31, extract the executable, and run it.
[SB_SSD_Temps_v1.31.zip](https://github.com/user-attachments/files/30638672/SB_SSD_Temps_v1.31.zip)

SHA-256
B30085174991B95626FFFE5DE87310CA5392FB17426B7AF1D3765AE86C76F4FE

This hash is for the signed .exe file and can be used to verify that the download has not been modified.


SB SSD Temps

EXE SHA-256: e12e252e536e6f88ca3ba35644c8e42718972873a9b5466c20a3b119aa371cc4

ZIP SHA-256: 37d89219260b1f7b5c9be834c3b160e9b6b5c132114fa3542eb9c48f5f582a75

A focused Windows utility for SSD temperature, health, and live drive-activity monitoring.

SB SSD Temps provides a clean, purpose-built interface for viewing the temperature information exposed by supported solid-state drives and hard drives. It was created for enthusiasts, technicians, system builders, reviewers, and everyday users who want useful storage information without navigating a large general-purpose hardware-monitoring suite.

The application is distributed as a portable, digitally signed Windows executable. It does not require a conventional installer and is designed to remain read-only during normal monitoring.



https://github.com/user-attachments/assets/deab227a-a927-4eea-8433-c94a375e2eb3

<img width="1920" height="1080" alt="SB_SSD_Temps_Desktop_20260802_112745" src="https://github.com/user-attachments/assets/5bfe8e1e-4964-407c-9399-9adaa6292656" />

<img width="1920" height="1080" alt="SB_SSD_Temps_Desktop_20260802_112750" src="https://github.com/user-attachments/assets/9eeac2fa-0fb5-4cd5-8aef-dd693a44d110" />


<img width="1920" height="1080" alt="Screenshot 2026-07-31 220953" src="https://github.com/user-attachments/assets/eb54625b-f032-4854-b0fb-e335b2f7ac00" />


<img width="1920" height="1080" alt="Screenshot 2026-07-31 220127" src="https://github.com/user-attachments/assets/d234cf5f-5a1a-476f-b576-7e093f510a47" />

Log - Release v1.29

Version: 1.29

Platform: 64-bit Windows 10 and Windows 11

Distribution: Portable single-file executable

Publisher: Copyright © 2026 Jon Bauer / ShrimpBrime. All rights reserved.

Price: Freeware

Download: Use the latest file under the repository's Releases section

Support: https://sb-ssd-temps.proboards.com/

Overview

Modern storage devices may expose one temperature, several temperature channels, drive-health information, warning thresholds, and real-time transfer counters. The amount of information available varies by drive model, controller, connection type, firmware, system configuration, and storage driver.

SB SSD Temps organizes the available information into a straightforward dashboard. When multiple temperature channels are exposed, the program can display NAND or primary temperature data, controller or secondary sensor data, and composite temperature data separately. Unsupported readings remain clearly marked as N/A instead of being estimated or invented.

The program also includes a dedicated live-drive-activity window with analog-style read and write tachometers. These gauges provide an immediate visual representation of current storage traffic, while compact history graphs show recent temperature behavior.

Main Features

Displays available SSD and HDD temperature sensors

Supports NVMe, SATA, and other storage devices when Windows and the device expose readable data

Separate NAND, controller, secondary, and composite temperature presentation when available

Displays minimum, maximum, and average temperature statistics

Celsius and Fahrenheit modes

Drive-health or remaining-life display when reported by the device

Drive-reported warning and critical temperature thresholds when available

Multiple-drive selection through a convenient drop-down list

Graceful N/A mode for drives without accessible temperature sensors

Adjustable monitoring interval

Live system time display

Read-only monitoring design

Resettable temperature statistics

Portable single-file distribution

Digitally signed release executable

Live Drive Activity

The Live Drive Activity window is one of the defining features of SB SSD Temps. It combines storage throughput and temperature behavior in a single visual panel.

Its features include:

Separate analog-style read and write gauges

Automatic throughput range selection

Live B/s, KB/s, MB/s, and GB/s presentation

Smooth needle movement for easier visual tracking

Recent-history temperature graphs

Independent NAND, controller, and composite graph channels when available

Graph reset control that does not interrupt live monitoring

Selected physical-disk identification

The tachometers are intended as an intuitive live activity display. They are not a replacement for a dedicated storage benchmark and should not be interpreted as benchmark certification. Transfer values can differ from benchmark results because normal Windows activity is sampled over time rather than generated as a controlled workload.

Visual Customization

SB SSD Temps includes several appearance controls so users can adapt the interface to their system or personal preference.

Adjustable accent color

Static background-color selection

Default, black, charcoal, monochrome, and light visual options

RGB accent effects

Font selection

Celsius and Fahrenheit controls

Optional saved visual profile

Default appearance restored when no profile has been saved

Saved visual settings are loaded again when the application is restarted. Users may clear the saved profile at any time to return to the original appearance.

Screenshots and Reporting

The application provides two screenshot functions:

App screenshot: Captures the SB SSD Temps application window

Desktop screenshot: Captures the complete Windows desktop

The Sensor details function creates a storage report containing the drive information exposed to the application. Reports can help with compatibility testing, troubleshooting, documentation, or support requests.

Reports may contain hardware-identification information such as device names, physical-disk numbers, interface information, firmware details, and Plug and Play identifiers. Review a report before posting it publicly if you prefer not to share system-identification details.

Mini Monitor and System Tray

SB SSD Temps can minimize to the Windows system tray instead of occupying taskbar space. The tray menu provides quick access to commonly used functions, including:

Restore the main window

Open the compact temperature display

Open Support

Open About

Exit the application

The mini temperature window is useful while benchmarking, gaming, copying files, or performing other work where the full dashboard is unnecessary.

Compatibility

SB SSD Temps is intended for:

64-bit Windows 10

64-bit Windows 11

Compatibility depends on the information exposed by the storage device, its firmware, the storage controller, the Windows driver, and the system's hardware-access configuration.

Possible device categories include:

NVMe solid-state drives

SATA solid-state drives

SATA hard-disk drives

PCI Express storage devices

Some Intel Optane devices

Some RAID-member or virtual storage devices

Detection of PCIe add-in cards, Optane hardware, RAID volumes, USB bridges, vendor-specific controllers, and externally attached drives is not guaranteed. Some devices provide complete sensor data, some provide only a single composite temperature, and others expose identification data without a readable temperature sensor.

If no compatible sensor is detected, the application should still open and display N/A readings. Other controls, drive information, reporting, screenshots, themes, Support, and About remain available.

Installation and First Run

SB SSD Temps is portable and does not use a conventional installation wizard.

Download the current signed executable from the Releases section.

Verify the SHA-256 checksum if desired.

Place the executable in a folder where you want to keep it.

Double-click the executable.

Approve the Windows elevation request if it appears.

Select a detected drive from the drop-down list.

The elevation request allows the monitoring components to access hardware information that ordinary desktop applications may not be permitted to read. SB SSD Temps is designed for monitoring and does not intentionally alter drive firmware, storage configuration, temperatures, performance modes, partitions, or user files.

Windows Security and SmartScreen

Official releases are digitally signed. Windows should identify the publisher instead of reporting an unknown publisher.

A newly released executable may still trigger a Microsoft Defender SmartScreen reputation message. Code signing establishes publisher identity and file integrity, while SmartScreen reputation develops separately through distribution history and user adoption.

Download SB SSD Temps only from the official repository, Microsoft Store listing, or support website. Compare the downloaded file's SHA-256 value with the checksum published for that release.

SHA-256 for Version 1.29

e12e252e536e6f88ca3ba35644c8e42718972873a9b5466c20a3b119aa371cc4

To calculate the checksum in Windows PowerShell:

Get-FileHash ".\SB_SSD_Temps_v1.29.exe" -Algorithm SHA256

The calculated value must match the published checksum exactly. A different value means the file is not byte-for-byte identical to the official release.

Basic Operation

Launch SB SSD Temps.

Select the desired storage device.

Choose Celsius or Fahrenheit.

Adjust the polling interval if desired.

Use Reset statistics before beginning a new temperature test.

Open Tach to view live read/write activity and recent temperature history.

Use the screenshot or report controls when documenting results.

Minimize the program to access its tray and mini-monitor functions.

Changing the polling interval changes how often the interface requests updated information. A faster interface polling rate cannot force a drive or controller to refresh its internal temperature sensor more frequently than the hardware supports.

Understanding Sensor Labels

Storage manufacturers do not use one universal sensor layout. Labels in SB SSD Temps describe the most likely role of the data exposed by the device, but exact sensor placement depends on the model.

NAND / Sensor 1: Primary device temperature or NAND-related reading when identifiable

Controller / Sensor 2: Controller or secondary temperature channel when identifiable

Composite: Overall temperature selected or calculated by the drive firmware

Drive temperature: A general temperature reading when only one channel is available

Two displayed values may occasionally be identical because the drive reports the same underlying sensor through more than one field. SB SSD Temps presents the information supplied by the hardware and does not manufacture additional precision.

Temperature Accuracy

Temperature accuracy is determined primarily by the sensor, firmware, controller, and driver. The application displays the values made available by the device. Decimal presentation, update frequency, and sensor granularity do not necessarily represent laboratory-grade measurement accuracy.

For controlled testing, record ambient temperature and use the same workload, drive state, airflow, polling interval, and test duration for every comparison.

Troubleshooting

The application shows N/A

The selected drive may not expose a readable temperature channel through the current hardware and driver path. Try another detected drive and generate a Sensor details report for support.

No storage devices appear

Confirm that Windows Disk Management or Device Manager detects the drive. Some storage controllers, USB adapters, RAID configurations, and vendor drivers may hide the physical device information required for monitoring.

The displayed temperature does not change rapidly

The drive may update its internal temperature data more slowly than the application's interface interval. This is normal and cannot be corrected by requesting the same value more frequently.

The tachometer differs from a benchmark

The live tachometer samples current operating-system activity. A benchmark controls workload size, queue depth, cache behavior, access pattern, and test duration. The two measurements serve different purposes and should not be expected to match continuously.

Windows displays a SmartScreen warning

Confirm that the file is digitally signed and that its SHA-256 checksum matches the official release. SmartScreen reputation is separate from signature validity and may take time to develop for a new application.

Antivirus software flags the application

Hardware-monitoring applications use low-level access methods that security software may inspect more aggressively than ordinary programs. Submit the exact warning, antivirus product name, detection name, app version, and SHA-256 checksum through the support forum. Do not disable security software merely to run the application.

A feature does not fit on screen

Confirm that Windows display scaling and resolution are within normal desktop ranges. Include a screenshot and scaling percentage in the support report.

Privacy

SB SSD Temps is intended to operate locally. It does not require a user account, subscription, advertising profile, or cloud login for normal monitoring.

The application does not intentionally collect or transmit personal information. User-created screenshots and sensor reports remain under the user's control unless the user chooses to upload or share them.

Support and Compatibility Reports

Support resources are available at:

https://sb-ssd-temps.proboards.com/

When reporting a problem, include:

SB SSD Temps version

Windows version and build

Storage-device model

Connection type, if known

Storage-controller or RAID configuration, if applicable

Screenshot of the problem

Sensor details report

Exact error message

Whether the problem occurs with administrator access

Do not post private recovery keys, passwords, account credentials, or other confidential information.

Release Philosophy

SB SSD Temps was developed as a focused enthusiast utility rather than a replacement for every hardware-monitoring or storage-benchmarking package. Its purpose is to make the most relevant drive-temperature and activity information easy to read, visually engaging, and convenient to document.

Future revisions may improve device compatibility, reporting, presentation, packaging, and Store integration. Feature availability may differ according to the selected drive and system configuration.

Ownership and Usage Terms

Copyright © 2026 Jon Bauer / ShrimpBrime. All rights reserved.

SB SSD Temps — Changelog

Current version: v1.29
Supports 64-bit Windows 10 and Windows 11.

v1.24–v1.29 — Interface and drive-health polish

• Added drive-reported remaining health, such as “100% Remaining.”
• Uses Life or NVMe Percentage Used data when available.
• Displays “Not Reported” when the drive provides no compatible health reading.
• Removed clutter from the tachometer gauge faces.
• Simplified and repositioned the tachometer status line.
• Final placement centers the status beside Reset Graphs and Close.

v1.19–v1.23 — Live Drive Activity

• Added separate live READ and WRITE tachometers.
• Added precise B/s, KB/s, MB/s and GB/s readouts.
• Added gold, silver and bronze temperature-history graphs.
• Added smooth needle movement and stabilized rendering.
• Added automatic 10, 20, 40, 80 and 160 GB/s gauge ranges.
• Added graph-only reset without interrupting live monitoring.
• Fixed a Reset Graphs error affecting the branded executable.

v1.12–v1.18 — Compatibility and layout improvements

• Added graceful N/A operation for drives without readable temperature sensors.
• Kept screenshots, reports, visual settings and other controls functional in N/A mode.
• Improved multi-drive selection and sensor labeling.
• Added SATA SSD and hard-drive support when sensors are exposed.
• Reworked warning placement so messages no longer cover controls.
• Standardized button sizes, spacing, sliders and footer positioning.

v1.6–v1.11 — Visuals, tray operation and launcher

• Added minimize-to-tray operation.
• Added an always-on-top Mini Monitor.
• Added live temperatures to the tray menu.
• Added Support and About tray commands.
• Added the branded Chiller Cube icon and Windows launcher.
• Added dark, black, charcoal and Light visual modes.
• Added static colors, rainbow, pulse and chase RGB effects.
• Added saved visual preferences.
• Improved About, Support and attribution text.

v0.15–v1.5 — Multi-drive release development

• Standardized the application name as SB SSD Temps.
• Added drive selection and multi-device reports.
• Added Samsung 990 PRO NAND, controller and composite identification.
• Added single-temperature layouts for other storage devices.
• Added Celsius/Fahrenheit selection.
• Added adjustable polling from 0.5 to 5.0 seconds.
• Added app and desktop screenshots.
• Added Sensor Details and Reset Statistics.
• Added font, accent-color and background controls.

v0.1–v0.14 — Initial prototypes

• Created the original read-only storage-temperature monitor.
• Added current, minimum, maximum and session-average readings.
• Added drive-reported warning and critical thresholds.
• Corrected early degree-symbol and text-encoding problems.
• Expanded detection beyond the original Samsung 990 PRO.

Current highlights

• Read-only monitoring
• NVMe, SATA SSD and HDD support when sensors are exposed
• PCIe and Optane support when SMART/NVMe data is accessible
• Multi-drive selector
• Remaining drive-health display
• Live READ/WRITE tachometers
• Recent temperature graphs
• Adjustable polling and temperature units
• Screenshots and detailed sensor reports
• Saved themes, colors, RGB effects and fonts
• Minimize-to-tray and Mini Monitor
• Graceful N/A mode
• Windows 10 and Windows 11 support

SB SSD Temps v1.29 is considered feature-complete and ready for controlled external testing. The current build is unsigned, so Windows or antivirus reputation warnings may appear.

SB SSD Temps is proprietary freeware. Permission is granted to download and use an unmodified official copy for personal use. Unless separately authorized in writing, permission is not granted to repackage, modify, resell, impersonate the publisher of, or distribute altered versions of the application. Applicable statutory rights remain unaffected.

The absence of an open-source repository license does not place SB SSD Temps in the public domain. The original application, interface, documentation, branding, artwork, packaging, and project-specific code remain protected by applicable copyright law.

Third-party components remain governed by their respective licenses.

Third-Party Software and Acknowledgments

SB SSD Temps includes components from Libre Hardware Monitor, an independent open-source project used to access hardware information exposed by supported systems.

Libre Hardware Monitor is licensed under the Mozilla Public License 2.0 (MPL-2.0). The applicable license notice is included with the SB SSD Temps distribution. Libre Hardware Monitor source code and project information are available from its official repository:

https://github.com/LibreHardwareMonitor/LibreHardwareMonitor

The MPL-2.0 license is available at:

https://www.mozilla.org/MPL/2.0/

SB SSD Temps and ShrimpBrime are not affiliated with or endorsed by the Libre Hardware Monitor project or its contributors. Third-party names and trademarks belong to their respective owners.
