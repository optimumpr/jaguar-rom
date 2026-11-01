# Jaguar ROM website — Batch 4

Overlay for the existing website on the `beta` branch.

## Changes
- Seven device pages: direct links to post #3 for the latest MEGA download, alongside the existing full XDA thread link.
- Devices directory and homepage: explain that post #3 is the maintained download location.
- Homepage: official Telegram announcements and discussion links.
- No release-version hardcoding or direct MEGA links; no monthly maintenance required when links within XDA post #3 change.

## Verify before merging to main
- Confirm the seven post #3 permalinks open the correct device and post.
- Verify both Telegram links.
- Review on a narrow mobile viewport and a desktop viewport.
- Confirm that XDA instructions are current for each device.
- GitHub Pages: publish from `main` root only after review.

## Preview
`python3 -m http.server 8000` from repository root, then visit `/`, `/devices/`, and any device page.
