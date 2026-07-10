# Known limitations

Control Deck is an early product from a solo developer. Expect some rough edges
and please report anything that blocks you.

- **Windows x64 only** for now. macOS and Linux are not available yet.
- **First voice use downloads models** — the local speech engine fetches model
  files on first use; this can take a while on slow connections.
- **Provider CLIs are yours to install and authenticate** — Control Deck drives
  Claude, Codex, Cursor, and OpenCode if you have them installed and logged in.
  Some agent features require an installed CLI.
- **No hosted Control Deck account** — the app is local-first and has no cloud
  deck sync. Network access is still used for license activation, signed update
  checks, optional provider/model downloads, and crash reports only when enabled.
- **No data-migration guarantee across major changes** — normal deck data should
  persist across updates, but keep your own backups of anything important.

Found something not listed here?
[Open an issue.](https://github.com/joffewilliam/control-deck-public/issues/new/choose)
