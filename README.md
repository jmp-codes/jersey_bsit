# Jersey Payments Tracker

A single-page tracker showing who has paid for their jersey order.

## Use
Open `index.html` (or the GitHub Pages address). Sign in with the admin username and password.

- Tick the circle when a person has paid in full.
- Open **Details** to enter a partial amount or a note.
- Payments are saved in the browser you use. **Save backup** downloads them as a file, and **Load backup** restores that file on any device.

## Publish on GitHub Pages
1. Create a repository and upload `index.html`.
2. Go to Settings > Pages, choose the `main` branch and the root folder, then save.
3. Open the address GitHub shows after a minute.

## Privacy
The order list (names, sizes, jersey numbers) is encrypted inside `index.html` with the sign-in password, so it is unreadable without it. Anyone who guesses the password can read the list, so keep the password private and do not share it in public. A private repository is still the safer choice.
