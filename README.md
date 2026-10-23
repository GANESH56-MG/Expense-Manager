# Varavu Selavu Offline — Notes Edition

- No cloud or account; daily use works offline.
- Separate Personal and Studio ledgers.
- Income/expense, category, date and notes.
- Search note/category/date; filter month, account and type.
- Dashboard balances and monthly reports.
- Local storage and JSON export/share backup.

## Build on a computer
1. Install Node.js LTS from https://nodejs.org/
2. Extract ZIP; open Command Prompt in this folder.
3. Run `npm install`
4. Run `npm install -g eas-cli`, then `eas login`
5. Run `eas build:configure`
6. Run `eas build -p android --profile preview`

This is source code, not a ready APK. Build requires internet, but once installed, the app's core functions work offline. Export backups regularly. App data may be lost if you uninstall or clear data; import/restore is not included in this prototype.
