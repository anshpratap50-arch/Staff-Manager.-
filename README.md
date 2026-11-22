# Staff Manager Android

This is a simple Android WebView wrapper for the Staff Manager app.

## Build APK using GitHub Actions (phone-friendly)
1. Create a new GitHub repository.
2. Upload the contents of this ZIP (not the ZIP itself) to the repository.
3. Add the workflow file below at `.github/workflows/build.yml`.
4. Open the repository's **Actions** tab and run **Build Staff Manager APK**.
5. When the workflow finishes, open the run and download the `StaffManager-debug-apk` artifact.

The app is an initial working version. The original HTML pasted in chat ended mid-file, so this project recreates the core screens (Home, Staff, Attendance, Work, Reports, Settings) rather than pretending the missing code was available.
