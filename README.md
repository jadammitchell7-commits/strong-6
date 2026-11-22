# Strong 6

A 6-week gym tracker: Monday and Friday sessions, 3 pairs of exercises each. Open the page, pick the week and day, log load and reps, tick sets off. Export everything to CSV for a spreadsheet.

- Works on phones (add to home screen) and computers
- No accounts, no servers: the log is saved in the browser on the device
- Download a backup from the **Export** tab to move devices

## Publish with GitHub Pages
1. Create a repo (e.g. `strong-6`) and push these files to `main`.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`.
3. After a minute the site is live at `https://<username>.github.io/strong-6/`.

## Changing the program
Edit the `DAYS` list at the top of the script in `index.html`. Each exercise has `sets`, `reps`, and `load` (the unit of the extra column, or `null` for bodyweight). Change `WEEKS` to extend the plan.
