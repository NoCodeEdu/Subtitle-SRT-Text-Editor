# Subtitle Text Editor

A single-file web app for editing the text of `.srt` subtitle files. Sequence numbers and timecodes are locked, so only the caption text can change.

No install and no internet connection needed: open the HTML file in any modern browser. It uses no external libraries; fonts load from Google Fonts when online and fall back to system fonts offline.

## File

- `SRT-Editor.html`: the whole app in one file

## Features

- Open `.srt` or `.txt` subtitle files with Upload or by dragging and dropping onto the page
- Edit caption text only; numbers and timecodes stay read-only
- Find text with highlighting, plus Replace all with Undo
- Show only edited cues
- Restore last session: recovers unsaved edits if the window was closed by accident
- Split a file into named parts by cue range, then save each part or all parts as a .zip
- Merge parts back into the original file, or combine them into a new file
- Your last theme and caption colors are remembered for next time

## Saving

**Save .srt** downloads the edited file. The original line endings and encoding mark are preserved. To continue editing later, upload the newly saved file.

## Restore last session

Private or Incognito windows, and clearing history, cookies or site data, will delete the restore. Always use Save .srt to keep your work.

A restored session can't change its encoding. Upload the original file again to do that.
