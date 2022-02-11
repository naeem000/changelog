Note:
==============================

Device changes:
==============================
sdm660-common: Fix neverallows
sdm660-common: rootdir: Force Enable DT2W
Quick-Tap enabled
Priv-app permissions updated
SELinux status Enforcing
User Build
------------------------------

ROM changes:
==============================
2/9
Evolver: Add VoLTE icon from Motorola
PixelPropsUtils: Remove spoofing for currently supported Pixels
SystemUI: Fix method for disabling unlock ripple animation
SystemUI: Introduce ColumbusCompatibilityHelper
SystemUIGoogle: Build android.frameworks.stats
SystemUIGoogle: Fix StatusBarGoogle injection and cleanup code
SystemUIGoogle: Import proto deps for columbus CHRE impl
SystemUIGoogle: Optimize proguard rules
Update SystemUIGoogle
fixup! Screenrecord: add blinking stop dot and low quality options
vendor: CarrierSettings: Update from SQ1A.220205.002

2/8
Evolver: Alert Slider: Add toggle to disable notifications (OnePlus devices only)
Evolver: Update SearchIndexable for our fragments
Evolver: Update SwitchPreference for CPU overlay toggle
Merge February 2022 security patches
PixelPropsUtils: Update to February 2022 fingerprints
Re-implement Alert Slider (OnePlus devices only)
fixup! base: add CPU info overlay
sepolicy_vndr: Remove duplicate hwservice_contexts
sepolicy_vndr: generic: Add app_data_file_type to vendor_radio_data_file
sepolicy_vndr: legacy: Update vendor property types
sepolicy_vndr: qva: Allow vendor_cnd to read wifi_hal_prop
sepolicy_vndr: qva: Update vendor property types
zygote: Enable USAP by default for S

2/7
Settings: Add preference for one shot auto-brightness
QS: Use Settings.Panel intent for Volume Tile
QS: Use Settings.Panel intents for WiFi and NFC

2/6
Evolver: User toggle for unlimited ph0t0s st0rage
ScreenshotHelper: ignore timeout when taking partial screenshots
SystemUI: add public setting keys for monet tunables
VolumeDialog: Display default row when active row is notification
VolumeDialog: Don't hide the default stream when adjusting the music stream

2/5
Settings: add title for Beam main switch
Settings: BluetoothDeviceDetailsFragment: fix edit menu icon tint
Settings: Disable Storage Manager

2/4
Evolver: Improve Secure QS tile behavior toggle
Settings: Improve code for time spent in app

2/3
Remove Advanced nav/Extended swipe gestures
SystemUI: Update NFC tile drawable
SystemUI: Use same NFC icon as that in QS tile

2/2
Evolver: Bring back Optional screenshot type toggle
Evolver: Refactor Notification settings fragment
Evolver: Refactor Status bar icons preference category
ScreenshotTile: Make default state inactive
ScreenshotTile: Use secondary label to indicate mode
Settings: fingerprint: hide link icon when there's no link

2/1
Evolver: Refactor Themes fragment
Fixes ubsan shift-out-of-bounds SIGABRT
Zygote: Fix an issue when emptying the usap pool
libgui: Dispatch vsync when receiving vsync timeout

1/31
Evolver: Add dividers to some preferences
Evolver: Add new black theme
KeyguardIndication: Fix glitchy charging info on lockscreen
Switch to a better Network Traffic implementation
Update translations

1/30
DefaultPermissionGrant: Fix google search crash
Evolver: Allow disabling ripple effect on unlock
Evolver: Move Monet settings to separate fragment
FingerprintManager: Fix NPE due to sensorProps
Navbar: Fix issue where pill disappears in gestural mode
Settings: Add missing android title for top_level_settings
Settings: Add LTE only setting
Settings: Cache current context before creating a new user
Settings: Drawables: Dark mode support for app installation restriction icon
Settings: NFC: Get outer NFC preference to listen for changes
apns: Add DITO PH
apns: Add Unifi

1/29
Evolver: Launch default music player on headset connect
base: Fix NPE in ImageWallpaper

1/28
SystemUI: FPSInfoService: initialize fpsInfoView without posting in handler
overlay: SystemUI: Remove power menu shadow

1/27
Deprecate LiveDisplay and LOS FOD stuff
PixelPropsUtils: Whitelist ARCore
SystemUI: rewrite fps info tile in kt and bind service to the tile

1/26
Settings: Import missing lottie swipe fingerprint from redfin
SystemUI: rewrite FPSInfoService in kt from scratch
UdfpsResources: Add more UDFPS icons
UdfpsResources: Convert remaining png to webp
apps: Build Repainter integration service
overlay: Add config for Repainter integration service
overlay: core: Use accent color for progress bar background
sepolicy: Nuke LiveDisplay and Lineage FOD
sepolicy: Resolve turbo_adapter denial

1/25
Evolver: Rename FP pressed color default to Cyan
GamingMode: LockGestureTile: load state from preferences in init
GamingMode: remove overlay menu switch
overlay: core: Add chroma to light surface highlight color

1/24
Battery Styles: Set proper battery style on init
Fix incorrect SID matching for bio prompts
Evolver: Remove Expanded option for network traffic
Evolver: Themes: Rearrange the categories
IconPackKaiAndroidOverlay: fix for carriers using 5 bars of signal
QuickSettings: Use tick instead of vibrate for normal tap on qs tile
SystemUI: Limit keyguard charging stats updates
SystemUI: Keyguard: Check for a null errString
SystemUI: Make sure notification icons are sticked to the left
SystemUI: use DOUBLE_TAP_TO_WAKE setting also for wake from aod
base: InputManager: handle housed stylus event
gms: Remove non-battery TurboAdapter
neko/Cat: Mark FLAG_IMMUTABLE PendingIntent with FLAG_MUTABLE
overlays: Add acherus icon pack

1/23
PixelPropsUtils: Remove GamesProps
RecoverySystem: make the package readable before checking capex
SystemUI: PeopleSpaceWidgetManager: don't spam logcat
SystemUI: ic_brightness_*: drawables get surface color
base: AudioService: bail out if ringer mode is not recognized
fonts: Bring back more font overlays

1/22
Settings: Fix invalid private DNS help text if URI is missing
Settings: WifiDisplaySettings: Fix some NPE
