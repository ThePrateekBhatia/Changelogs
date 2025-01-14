![Changelog](https://i.imgur.com/MsgqFFz.png)

### Project Elixir for Redmi K20 Pro/Mi 9T Pro (Raphael/in) Changelogs

### v4.2

```
- Remove zram fstab
- Make less cores available for background tasks
- Silence OpenGLRenderer log spam
- Clean-Up useless log spam
- Build android.media.audio.common.types-V2-cpp
- Update vendor.audio-hal service configuration
- Clean up libqti-perfd-client
- Remove obsolete config_keyboardTapVibePattern
- Use the fragment for QTI vibrator HAL
- Update vibration settings
- Drop haptic level adjustment
- Import qcom-caf thermal HAL
- Fix battery drain due to statsd
- Fully drop mi_thermal (It's summertime, so expect complaints about slow charging. Let's drop it.)
- Parts: Apply layout to parts in system page
- Enable battery cycle count
- Update uclamp tune to waffle kernel
- Adapt waffle kernel for QPR2 changes (69 bpf patches)
- Switch to android.hardware.usb@1.3-service.dual_role_usb
- Don't explicitly include updatable_apex.mk
- Parts: Enable use_resource_processor for all sysui deps
- Parts: Convert to SwitchPreferenceCompat
- Parts: Migrate to CompoundButton.OnCheckedChangeListener
- Add BUILD_BROKEN_INCORRECT_PARTITION_IMAGES
- Many more fixes and changes here and there
```

### v4.1

```
- Drop cgroup_presure at kernel cmd
- Fixup: Allow system_server to get app_zygote pgid
- Reduce WiFi Scan Interval
- Set config_screenBrightnessDoze to 12
- Use 'quicken' filter for app installing
- gps: Localise NTP to improve GPS TTFF
- Switch to Lawnchair A14
- Switch to Leica 5.0 latest camera
- Switch to soviet uclamp tune
- Switch to soviet kernel
- Enable Camera Vendor Tags for Xiaomi devices
- Compile power hal dependency for gnss
- Build OMX service
- Move Enable FUSE Passthrough
- Replace isolated_app with isolated_app_all
```

### v4.0

```
- Initial A14 buid
- Leica+MiuiCam included
- Switch to Dynamic+Erofs build
- Drop duplicates manifest entry
- Switch to AIDL WiFi service
- Rename libstdc++.vendor to libstdc++_vendor
- Target current sdk
- Declare exported flags in manifest
- Fix Pop-Up camera caliberation
- Build libprotobuf both varients
- Patch more blobs to load libprotobuf-cpp-full-3.9.1
- Switch to full IWLAN mode
- Move UDFPS enroll radius to settings
- Disable display refresh rate override
- Disable zram writeback
- Add KProfile support
- Build Lineage Health Hal (charging control)
- Adapt to Bool-X uclamp tune
- Many more under the hood changes..
```

<br>

> [!Important]
> **Credits: A very special thanks to - Amir, itzdfplayer, BULLA, ඞ Rian, Croesus,  Silent Boy & Project Elixir & TEAM**
> * **Donate**: [Do consider donating or buying us a coffee](https://projectelixiros.com/donate)
> * Android 14 Recovery Link : [Tap here for link](https://projectelixiros.com/download)
> * Any Extra File link if required : [Tap Here for link](https://sourceforge.net/projects/project-elixir/files/fourteen)

<br>

> [!Note]
> * Installation Guide: [Tap here](https://projectelixiros.com/download)
> * Gapps is already included in zip no need to flash additionally
> * Use latest a11 firmware of your region
> * Use Dynamic ofox recovery
> * Based on OSS vendor and latest Soviet kernel
> * For fixing play integrity: Open Updater, click on 'Update PlayIntergrity Fp' then clear play store data and reboot once
> * If you are coming from PORTs then you need to Format Data and flash latest firmware [depending on the device]
> * If you are coming from Android 12 or 13 to Android 14 then clean flash is compulsory and format data.
> * If you are encrypted do format Data before flashing build to avoid bugs.
