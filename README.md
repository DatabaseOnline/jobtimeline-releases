# SQLTreeo Job Timeline downloads

This repository only hosts the release files of **SQLTreeo Job Timeline**, the tool by
[SQLTreeo](https://www.sqltreeo.com/job-timeline) that shows the SQL Server Agent jobs of all your
servers together: what runs now, which jobs overlap, which run longer than their own norm and what failed.
The installed application reads the releases here to offer automatic updates.

- **Download:** the `JobTimeline-win-Setup.exe` asset of the [latest release](../../releases/latest)
  (Windows 10/11, 64-bit, no .NET installation needed). `JobTimeline-win-Portable.zip` runs without
  installing.
- **Product page, pricing and license keys:** https://www.sqltreeo.com/job-timeline
- **Support:** https://www.sqltreeo.com

SQLTreeo Job Timeline is commercial software. It is licensed, not sold: see [LICENSE.txt](LICENSE.txt) (end-user
license agreement). The first start on a computer begins a free 30-day trial with every feature enabled.
Afterwards the application stays free for up to three servers; more servers require a license key.
It only reads from your servers (SELECT on the msdb job tables) and installs nothing on them.
Third-party open-source components are listed in `THIRD-PARTY-NOTICES.txt` inside every download.

The `.nupkg` and `releases.*.json` files are used by the updater and are not meant to be downloaded manually.
