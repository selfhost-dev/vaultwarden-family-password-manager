# B44: Family Password Manager with Vaultwarden on Selfhost.dev

This repository contains the documentation and setup checklist for deploying Vaultwarden as a family password manager on Selfhost.dev.

## Setup Checklist
1. Deployed Vaultwarden on Selfhost.dev UAT (2 vCPU, 4 GB RAM, `cpx22`, Nuremberg).
2. Logged into `/admin` with Admin Token. Checked SMTP (empty by default).
3. Invited 4 users via Admin Panel. Registered all accounts at `/#/signup`.
4. Created "Family" organization with "Home" and "Streaming" collections.
5. Set Kid account restricted to only see "Streaming".
6. Connected browser extension and phone app to Selfhost.dev URL.
7. Enabled 2FA via Authenticator App.
8. Exported "My vault" (3 items) and "Family" org (2 items). Imported into fresh account (5 items total). Restore test successful.

## Collections Layout
* **Home:** Wi-Fi password, Router admin.
* **Streaming:** Netflix, Spotify.

## Restore Test
* Items before export: 5.
* Export size: 1,478 bytes.
* Items after import: 5 (2 from Family org + 3 from personal vault).

## Built by
Himanshu Rathod
