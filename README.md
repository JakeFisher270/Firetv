# E Streams Blue (v1.0)

A **new, separate Android TV app**, application ID `com.estreams.blue`.

## Features
- Black and electric-blue TV interface, focusable remote buttons
- Xtream Codes live TV login and M3U URL import
- Provider category names preserved, sports/news/movie/series discovery by category and name
- Live playback via Android VideoView
- Asynchronous channel import, channel search, settings and provider reset
- No included playlist or channels

## Build
Open this directory in Android Studio, install Android SDK 35, and build `assembleDebug`.
Alternatively upload the **contents** to a GitHub repo and run the included GitHub Actions workflow; download the APK under the workflow's Artifacts.

## Known limitations
This is an **initial, untested MVP**, not a full TiviMate replacement. It does not yet have EPG, VOD API, local channel caching, pagination beyond 350 displayed matches, or advanced ExoPlayer codec support. Movies/Series tabs currently filter live channels only. The login credentials are stored in app-private SharedPreferences (not encrypted). Debug APK signatures differ between build environments, so upgrades may require uninstall/reinstall. Use only with content you have rights to access.
