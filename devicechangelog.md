* Device Changelog:
• Fix Reboot Issue
• Fix all audio issue
• Latest 4.19.218 Kernel Version
• Updated blobs from S62Pro RKQ1.210406.002 
• Replaced DeviceSettings with minimalist XiaomiParts
• Bluetooth (aptX) - from sunfish RQ1A.201205.008
• Witch to Raven Build FP

ROM changes:
==============================
11/24
Evolver: Add option to auto hide status-bar clock
PixelPropsUtils: Whitelist GoogleCamera
SettingsGoogle: Don't translate fingerprint strings
SystemUI: Dismiss keyguard on boot if disabled by current profile
SystemUIGoogle: Fix injection of KeyguardIndicationControllerGoogle
keyguard: Do not trigger a wake up when hiding lockscreen

11/23
SystemUI: QS: SoundTile: Don't toggle DND
SystemUI: Update SoundTile
TwilightService: Save and use last fetched location
TwilightService: Use temporary TwilightState when location is not available

11/22
AudioService: Cancel old toasts when switching ringer mode
Settings: Add back DataUsageSlice
Settings: Add vibration patterns from OOS
Settings: Allow choosing a custom vibration pattern
Settings: AppInfo: Add time spent in app from Wellbeing
Settings: Enable Quick Wallet settings for all devices with NFC
Settings: Fix data usage display on mobile panel
Settings: MobileDataPanel: Remove VoLTE slice
Settings: Optional haptic feedback on back gesture
Settings: navigation mode settings
base: Remove aosp's 'show battery percentage' setting

11/21
BatteryService: Add support for oem fast charger detection
Evolver: Add back big dotted and big circle battery indicator
QuickStatusBarHeader: don't disable estimate mode for centered notch devices
Settings: Bring in missing lottie animations
Sharesheet: Set max ranked items to 8
SystemUI: Adapt screen record dialog switches UI to 12
SystemUI: Fix uneven DND icon padding in status bar
base: FPS Info: Make new formatting works with old kernel
base: Improve FPS Info output formatting and performance
camera: allow GPU usage for isSurfaceForHwVideoEncoder
telephony: show ICCID by default for all

11/20
AudioService: Remove Analog Dock from fixed-volume devices
BatteryService: Add support for battery Moto Mods
PixelPropsUtils: Use redfin props for some apps
Port changes from SettingsGoogle
Port changes from SystemUIGoogle
Settings: Comment some overlays
Settings: Force disable top level support preference
SystemUI: Add support for persistent usb drive notification
SystemUIGoogleOverlay: unset camera gesture package
hwui: Silence Davey logs for now
vendor: Update props from SD1A.210817.015.A4
vendor: rro_overlays: Add back missed prefs animations

11/19
Increase the time limit for low performance fail
SettingsLib: Update 4G+ icon to Silk design as well
SystemUI: Kill fake navbar once again

11/18
QuickStatusBarHeader: Add date & clock click actions
base: Add reset_stats to settings specific permissions
fixup! SystemUI: Add status bar NFC icon

11/17
PixelPropsUtils: Add chrome into extra packages list
Powermenu Torch: Allow simultaneous access
Screenrecord: Add an option to record for longer
Screenrecord: Add blinking stop dot and low quality options
Screenrecord: Make low quality bitrate scalable per device
Screenrecord: Save and load set preferences
SystemUI: AnimatableClockView: set color first and then animate
base: dont call roundStorageSize on Storage API for getting sizes
data: Update PackageInstaller/PermissionController whitelist

11/14 (SNOW)
Allow opening power menu when screen is off
Bring back Pocket lock support
Bring back support for toggling Navbar and other navbar settings
Bring in Carrier Label support
Evolver: Add toggle to disable wired charging animation
Evolver: Double tap to wake on doze
Implement burn-in protection for status/navbar
PhoneStatusBarPolicy: Show battery level for all devices
Settings: Remove aosp battery percentage option
SystemUI: Add Compass tile
SystemUI: Add tile to show volume panel
