# Before you start

Close the game and any launcher completely. The tool needs exclusive access and will fail if something is still holding a handle.

> Run everything as administrator. Most "it did nothing" reports come from a normal-privilege launch.

## Requirements

| Item | Requirement |
|---|---|
| OS | Windows 10 21H2 or Windows 11 |
| Secure Boot | Disabled |
| Antivirus | Real-time protection off during setup |

## Setup

1. Download the package from your **Manage Purchases** page.
2. Extract it somewhere outside Downloads — for example `C:\Rogue`.
3. Right-click the loader and choose *Run as administrator*.
4. Paste your licence key when prompted.
5. Wait for the confirmation message, then restart.

### Verifying it worked

Open a terminal and run:

```
wmic diskdrive get serialnumber
```

If the value has changed from what you noted earlier, you're done.

---

## Common problems

**Loader closes instantly**
Your antivirus removed it. Add the folder to your exclusion list and extract again.

**"Invalid licence" on a key you just bought**
Keys sync within a few minutes of purchase. If it's still failing after ten, open a ticket with your order ID.

**Black screen after restart**
Boot into Safe Mode and run the included restore tool, then start over from step 2.

Still stuck? Open a support ticket in Discord and include a screenshot of the error.
