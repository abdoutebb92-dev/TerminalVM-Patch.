# APK analysis runner

This repository's Actions workflow decodes the APK with Apktool and uploads a short-lived analysis artifact.

## Run
1. Open **Actions**.
2. Select **APK analysis runner**.
3. Click **Run workflow** and confirm.

The workflow does not alter or re-sign the APK yet. The analysis bundle is used to identify the exact compatibility gate before making a narrowly scoped change. Bypassing a UI check alone does not provide underlying Android VM / kernel / virtualization support.
