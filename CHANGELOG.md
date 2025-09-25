> `Changelog:`
> - All significant changes to this project will be documented here.
---

> [3.50.4] - `20250925`
>
> - Renamed functions in `customize.sh` for clarity: `print_time` to `display_current_time`, `print_device` to `display_device_info`, added `display_ram_info` for RAM status.  
> - Enhanced `display_device_info` in `customize.sh` with capitalized device name and model for better readability.  
> - Added `print_random_devil_message` and `post_install_actions` in `customize.sh` for modularized message and post-install logic.  
> - Extended random devil messages in `customize.sh` with "Beelzebub" and updated terminology (e.g., "Demon" to "Devil").  
> - Improved notification in `customize.sh` from "Install successfully" to "Module installed successfully. Please reboot your device."  
> - Simplified `module.prop` description in `service.sh` by removing square brackets for cleaner presentation.  
> - Enhanced notification in `service.sh` to include SQLite version (`3.50.4`) for clarity.  
> - Removed icon (`Sqlite3_01.png`) from `service.sh` notification to streamline delivery.  
> - Added `installisasi` function in `customize.sh` to streamline SQLite3 binary extraction, replacing redundant loops.  
> - Maintained robust root detection in both `service.sh` and `customize.sh` for KernelSU, Magisk, and APatch.  
> - Kept Android SDK-specific emoji mapping in `service.sh` for consistent visual feedback.  
> - Optimized permission setting in `customize.sh` with `EXEC_FILES` for SQLite3 binary.
---

> [3.50.4] - `20250819`
>
> - Update sqlite3 to the latest version `3.50.4`.
> - Now only supports `Android 10+`
> - Updated to be compatible with all `ARCH` devices (still in testing phase).
> - Everything else is still the same as before.
---

> [3.50.3] - `20250804`
>
> - Update sqlite3 to the latest version `3.50.3`.
> - Updates to the code in `customize.sh` and changed the name from arch to sqlite3.
> - Updated `README.md` to be more professional and understandable.
> - Updated `module.prop` root use method detector to be more complex.
> - Add module banner for KernelSU Next.
> - Add notifications with `icons` to make them more attractive.
> - And other minor changes updates.
---

> [3.50.2] - `20250710`
>
> - Update sqlite3 to the latest version `3.50.2`.
---

> [3.50.1] - `20250619`
>
> - Update sqlite3 to the latest version `3.50.1`.
> - updated `update-binary` to be more optimal.
> - The rest is still the same as the previous version.
---

> [3.49.1] - `20250515`
>
> - Add `verify.sh` to automate the `integrity` check.
> - Added `i386` and `armv8l` and `armeabi` architectures but I don't know if this works or not.
> - Add `service.sh` to update `module.prop`.
---

> [3.49.1] - `20250310`
>
> - Update `customize` and `functions`, this applies to all future modules.
> - Update `LICENSE`,`README` and add `changelog.md`.
> - Delete all messages in `install.sh`.
> - Sqlite version `3.49.1`.
---

> [3.49.0] - `20250217`
>
> - Initial release.
> - Supports ARM64, ARMv7a, x86, and x86_64 architectures.
> - Automatic architecture detection.
> - Automatic updating of `module.prop` file with root and Android data.
> - Delete unused binary files automatically.
> - Sqlite version `3.49.0`.
---