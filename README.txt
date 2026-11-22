CVC OFFLINE VERSION 8.1

LOGIN AND USER ACCOUNTS
First login on a device:  Username: admin   Password: admin123
Login goes straight in. Change the password yourself from "Change password" in the top bar.

Admin: click "Manage users" (top bar) to
- add users (role CVC or Admin) with a starting password
- reset a user's password
- change a user's role, or delete a user
- Export users / Import users, to copy the same accounts to other devices

Everyone: "Change password" and "Logout" are in the top bar.

Accounts are stored on each device (offline, no server). Create them on one device,
then use Export users -> Import users to set up the other devices.
Passwords are stored as salted hashes. This is a sign-in gate, not strong security:
the child records are inside index.html, so keep the files on authorized devices only.

CUP / CUV TRACKING
Open the "CUP / CUV Tracking" tab. Only RC with a sponsor (status "មានអ្នកទំនុកបំរុង") are listed.
- Top: totals and progress by village (Sponsored RC, CUP done, CUV done, Complete, Pending).
- Click a village to open its checklist, then tick CUP and CUV for each RC. Untick to undo.
  The date and the username that ticked are saved with each tick.
- COULD NOT PROCESS: if an RC cannot get CUP/CUV, click "Could not process" in that row, choose a reason
  (add a note; a note is required for "Other") and Save. Use Edit to change it or Remove status to undo.
  Such RC are counted separately and are no longer counted as Pending. If CUP and CUV are both ticked later,
  the mark is removed automatically.
- Totals now show: CUP done, CUV done, Complete, Could not process, Pending.
- ADMIN OVERVIEW (admin login only, bottom of the tab): ticks per CVC user (CUP, CUV, could not process, last
  activity), could-not-process count per reason, and the full could-not-process RC list with reason, note,
  date and user. Export buttons give Excel CSV.
  Data is stored per device. To see all CVC users together, each CVC user uses Backup tracking, and the admin
  uses Import / merge on the admin device.
- Export summary / Export all open in Excel (CSV).
- Ticks are saved on each device. To combine devices: Backup tracking on one, Import / merge on the other.
- Admin only: Clear all ticks.

QUICK START
1. Open index.html directly for normal offline search and PDF printing.
2. For installation as an app, upload this whole folder to a PRIVATE HTTPS host.
3. Open the hosted address in Chrome or Safari and choose Install App / Add to Home Screen.
4. While online, choose one village and click Save visible photos offline. Repeat for each village needed offline.
5. Use Generate PDF. The print layout is A4 landscape with exactly 10 RC cards per page.

UPDATING AN INSTALLED COPY
This version uses a new offline cache (cvc-v8-5). Replace all files on the host, then open the
app once while online so it refreshes. Existing accounts on a device are kept; an older
single "CVC" login is carried over as a CVC user.

PRIVACY
This package contains child records and external photo links. Keep it on authorized devices only. Do not publish it to a public GitHub repository. Use a private or access-controlled hosting location.
