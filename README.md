# Daily Frame

One photo prompt a day for documenting a real life on film: home, the cats, James, friends, work, shows, nature, the Westminster / Denver area, and yourself. Not about making a good photo. It's about taking one.

- Each day rotates through nine parts of life: Home, Cats, Friends, Work, Me (self-portraits), Nature, James, Shows (live music), Around here. On weekends the Work day becomes Around here, Nature, or Friends.
- The prompt for a given day is worked out from the date, so it's the same on every device.
- "Different one" gives one swap per day, within the same part of life.
- "I shot the prompt" logs the day. "Shot something else" logs any other photos (a show, a trip, anything) with an optional note, and those count too. Your log is saved on the device.
- The calendar shows every month you've logged. Tap a day to see what you shot, remove something, or add photos you forgot to log.
- Every part of life has its own color. Calendar days are striped with whatever you shot, and each month shows a breakdown of what you shot most.
- In the first week of a new month, a tap-through recap of last month opens once. Any month's recap can be replayed from the calendar.
- After 3 or more days without a frame, the app says so and swaps in one of the easiest prompts to get back in.
- On this day: if you logged something on today's date in an earlier year, it shows up under today.
- What's loaded: note the camera, film, and exposures. Each thing you log counts as a frame, the count can be fixed by hand, and finished rolls are kept as a list.
- Backup: "Save backup" exports everything (log, rolls, recaps seen) as a .json file; "Restore backup" merges one back in. The log otherwise lives only on the device.
- Year in review: the same recap for a whole year, replayable from the calendar, and opened once in the first week of January.
- No notifications. Open the app and tap.

## Editing prompts

All prompts live in the `BANK` object near the top of the script in `index.html`. Add, remove, or reword freely. Bump `VERSION` in `sw.js` after changes so installed copies refresh.

## Hosting

GitHub Pages: Settings, Pages, deploy from the `main` branch, root folder. Then open the Pages URL on your phone and use Add to Home Screen.
