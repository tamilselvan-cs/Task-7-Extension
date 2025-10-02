#Task 7 — Identify & Remove Suspicious Browser Extensions

Student: C Tamilselvan  
Date: 2025-10-02  
Browser: Microsoft Edge (Chromium)  
OS: Windows 10/11 (Host)

---

##Steps Performed
1. Opened Microsoft Edge and navigated to `edge://extensions/`.
2. Captured a "before" screenshot of all installed extensions.
3. Reviewed each extension’s **Details** and checked permissions.
4. Found only one extension installed: **Google Docs Offline**.
5. Verified publisher = Google (official), permissions are expected (offline editing).
6. No suspicious extensions detected, so no removals required.
7. Documented results in `removed_extensions.csv`.

---

## Findings
- **Google Docs Offline**: Official extension from Google, safe to keep.
- No malicious or suspicious extensions present.

---

## Screenshots
- `screenshots/01-edge-before.png` — Extensions list before check  
- `screenshots/02-edge-details.png` — Extension details (permissions view)  

---

## CSV File
See [removed_extensions.csv](./removed_extensions.csv) for details.

---

## Notes
- If a suspicious extension is ever detected, the safe procedure is:  
  1. Disable → Remove extension.  
  2. Restart Edge and verify removal.  
  3. Run Windows Security / AV scan.  
  4. Change sensitive passwords from a clean device.