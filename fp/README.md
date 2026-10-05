# fp/ : temporary media for two Instagram posts

These are the rendered slides and Reels for episodes 1 and 2 of the "Owner's Second Brain"
Instagram page: 16 carousel JPEGs (`ep-1/jpeg`, `ep-2/jpeg`), two Reel cover JPEGs and two
captions-only Reel MP4s (`reels/`). About 4.3 MB in total.

Why they are here: Instagram's publishing API fetches every image and video itself from a
public https URL, and the publisher never uploads. This folder is that URL.

Temporary: delete the whole `fp/` folder in a commit as soon as both episodes are live on the
account. They carry only the same text and pictures that become public in the posts. No client
names, no personal data, no EXIF or GPS tags (checked on 5 Oct 2026).

Search engines: these are binary files, so there is no place for a robots meta tag. A
`robots.txt` for a GitHub Pages project site only works at the domain root, which this repo does
not own, so nothing here can be set to noindex. The folder is short-lived on purpose instead.
