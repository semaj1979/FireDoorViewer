# Fire Door Viewer 0.2

Changes from 0.1:
- Bundled libVLC playback instead of Android VideoView/MediaPlayer.
- Forces RTSP over TCP with low network caching.
- Explicit Fire TV D-pad focus order for stream, secret token, Save, and Test.
- Keeps LAN listener on TCP port 7980.
- Test overlay lasts 30 seconds; `/show?token=...` lasts 60 seconds.

Default stream: `rtsp://192.168.1.233:8556/aqara_g410_clean`

The Fire TV still requires one-time `SYSTEM_ALERT_WINDOW` permission. Updating the same package should normally preserve that permission.
