# Privacy Policy for Cache Cleaner for Windows

**Last updated:** November 2026

**Cache Cleaner for Windows** ("the Application") is developed by **MrKalita**. Your privacy is critically important to us.

---

### 1. 100% Offline Execution & Zero Data Collection
Cache Cleaner for Windows operates entirely on your local PC:
- The Application does not collect, log, transmit, or share any personal information, files, metadata, telemetry, or browsing history.
- The Application runs 100% offline. It contains zero third-party analytics SDKs, advertising beacons, tracking cookies, or remote reporting frameworks.
- No network connections are made during scanning, cleaning, or maintenance operations.

### 2. Local File & Cache Operations
- **Temporary Cache Cleaning:** The Application inspects and cleans temporary directories (`%TEMP%`, `C:\Windows\Temp`, Windows Update cache) solely upon your explicit instruction.
- **Empty Folder Pruning:** The Application scans selected disk drives to detect and remove empty, abandoned directories. It operates with a strict, built-in safety whitelist that prevents modification of critical system directories (`C:\Windows`, `Program Files`, `ProgramData`), development repositories (`.git`, `.svn`), and system root junction points.
- No files are ever sent to the cloud, moved off-device, or inspected for private contents.

### 3. Local Preferences & Licensing
- User interface preferences (such as selected theme, drive selections, and window state) are stored strictly on your local device.
- License status verification for Microsoft Store In-App Purchases is conducted directly through the secure local Windows Runtime Store API (`Windows.Services.Store.StoreContext`) provided by Windows.

### 4. Contact
For questions, feedback, or support regarding this Privacy Policy, please open an issue on the project's GitHub repository or contact the developer via the Microsoft Store.
