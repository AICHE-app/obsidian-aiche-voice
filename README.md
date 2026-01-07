# AICHE Voice for Obsidian

Speak into your notes. Polished text appears in seconds.

## What It Does

Click record, speak naturally, get readable text with punctuation and grammar already handled. Not raw transcription — actual sentences you'd want to keep.

## Install

**Community Plugins**
1. Settings → Community Plugins → Browse
2. Search "AICHE Voice"
3. Install → Enable

**Manual**
1. Download latest release
2. Extract to `.obsidian/plugins/aiche-voice/`
3. Enable in Community Plugins

## Setup

1. Settings → AICHE Voice → Sign In
2. Authenticate in browser
3. Start recording

## Usage

| Method | Action |
|--------|--------|
| Ribbon | Click microphone icon |
| Hotkey | Set in Settings → Hotkeys → search "AICHE" |
| Command | `Ctrl/Cmd + P` → "Toggle Recording" |
| Status Bar | Click recording indicator |

Right-click status bar for quick actions.

## Settings

| Option | Description |
|--------|-------------|
| Polish text | Fix grammar and punctuation automatically |
| Insert at cursor | Text appears at cursor, not end of note |
| Show notifications | Notify when transcription completes |
| Voice notes folder | Where new notes are created |
| Attach audio | Save audio file with voice notes |
| Organize by category | Sort into Work/Life/Ideas/Misc subfolders |

## Hotkeys

Configure in Settings → Hotkeys:

- **Toggle Recording** — Start/stop recording
- **Cancel Recording** — Discard without saving
- **New Voice Note** — Create note and start recording

## Privacy

Audio is sent to AICHE servers for transcription. Audio files are deleted immediately after processing.

**Collected:**
- Audio (during processing only)
- Transcribed text (stored with your account)
- Usage metadata (timestamps, word counts)

**Not collected:**
- Audio after transcription completes
- Training data from your recordings
- Data shared with third parties

**Local storage:**
- Offline recordings are encrypted locally (AES-GCM)
- Auto-deleted after successful upload
- Encryption keys derived from vault + device

Full details: [Privacy Policy](https://aiche.app/privacy)

## Pricing

7-day free trial. $4.99/month unlimited.

[View Plans](https://aiche.app/pricing)

## Support

- [Website](https://aiche.app)
- [Help](https://aiche.app/help)
- [Issues](https://github.com/AICHE-app/obsidian/issues)

## License

MIT
