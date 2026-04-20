# duplicate-finder

> Find and delete duplicate files on your Mac — without touching a single terminal command.

<p align="center">
  <a href="https://YOUR_USERNAME.github.io/duplicate-finder/">
    <img src="https://img.shields.io/badge/Install-Open%20guide-0071e3?style=for-the-badge&logo=apple&logoColor=white" alt="Install — open installation guide" />
  </a>
</p>

---

## The problem

Your Mac is full. You open Storage and see "Documents: 48 GB" — but you have no idea why. Somewhere in there are hundreds of duplicate photos, downloads saved twice, and files copied across folders years ago. Finding them manually is impossible.

## What this does

`duplicate-finder` is a menu bar app that scans any folder, finds exact duplicates, and lets you delete them safely — with a clear preview before anything is removed.

- Scans by content, not just filename
- Groups duplicates so you always keep one copy
- Shows exactly how much space you'll free up
- Move to Trash, never permanent delete

## How it works

1. Click the menu bar icon
2. Choose a folder to scan (Downloads, Documents, Desktop — or your whole home folder)
3. Review grouped duplicates with file size and location
4. Select which copies to remove
5. Click **Move to Trash** — done

No files are deleted without your confirmation. Ever.

## Screenshots

| Scan in progress | Results grouped by duplicate |
|---|---|
| ![scan](screenshots/scan.png) | ![results](screenshots/results.png) |

## Requirements

- macOS 13 Ventura or later
- Apple Silicon or Intel

## Privacy

All scanning happens on your device. No files, filenames, or metadata ever leave your Mac.

## Contributing

Pull requests welcome. Please open an issue before starting large changes.

```bash
cd duplicate-finder
open duplicate-finder.xcodeproj
```

## License

MIT
