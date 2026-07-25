# Temporary Gmail UI Demo

An unofficial, static Gmail-style interface prototype for UI demonstration.

- It is not affiliated with Google.
- It does not connect to Gmail or Google Accounts.
- Do not enter a real Google password.
- Temporary access is implemented locally in the browser and is not secure authentication.
- The 18-character demo access code changes at fixed 3-hour boundaries.

## Viewing the current demo password

Open the deployed page, open the browser Developer Tools (`F12`), select
**Console**, then run:

```js
getTemporaryPassword()
```

The console shows the active password, when it became valid, and when it will
change. Because this is a static website, the rotation logic is shipped to every
visitor and must not be treated as secure server-side authentication.

Public mailbox route: `/mail/u/0/#inbox`

Custom domain: `google-temporary.my.id`
