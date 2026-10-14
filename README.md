# Tawazun

A personal gym workout app: full equipment training generated fresh every session
(no day-to-day or week-to-week repeats), with a back/abs-focused split, weekly
scheduling, progressive difficulty, weight tracking, and local push reminders — no
internet or account needed.

## Getting the APK

Every push to `main` builds the app automatically on GitHub's servers.

1. Go to the **Actions** tab of this repo.
2. Open the latest **Build Tawazun APK** run (green check = success).
3. Under **Artifacts**, download `tawazun-apk` — it's a zip containing
   `app-debug.apk`.
4. Send that `.apk` to the phone (email, Drive, USB, etc.), open it, and allow
   "install from unknown sources" when prompted. That's it — no Play Store needed.

To trigger a fresh build without changing anything, go to **Actions → Build Tawazun
APK → Run workflow**.
