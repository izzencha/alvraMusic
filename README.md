# alvraMusic

## Build the APK (phone only)
1. Create a GitHub repo, upload everything in this folder (keep the .github folder).
2. Open the Actions tab, run "Build APK" (it also runs on every push to main).
3. When it finishes, open the run and download the `alvraMusic-apk` artifact. Unzip, install app-debug.apk.

## YouTube account sync (one-time setup)
1. console.cloud.google.com: create a project, enable "YouTube Data API v3".
2. OAuth consent screen: External, add yourself as a test user, add scope youtube.readonly.
3. Credentials > Create OAuth client ID > type "TVs and Limited Input devices".
4. In the app: Settings > Google client ID / secret, then Sign in to YouTube.
   Enter the code shown at google.com/device.
5. Menu > Library for Liked songs and your playlists. Online search also works once signed in.
