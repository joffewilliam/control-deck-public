# Known limitations — Free Trial Preview

This is an early, time-limited preview from a solo developer. Expect rough edges
and please report anything that blocks you.

- **Unsigned installer** — Windows SmartScreen warns on first install
  ("Unknown publisher"); use **More info → Run anyway**. Signed builds come with
  the paid release.
- **Windows x64 only** for this trial. macOS and Linux are not part of the first
  public trial.
- **First voice use downloads models** — the local speech engine fetches model
  files on first use; this can take a while on slow connections.
- **Provider CLIs are yours to install and authenticate** — Control Deck drives
  Claude, Codex, Cursor, and OpenCode if you have them installed and logged in.
  Some agent features require an installed CLI.
- **No hosted Control Deck account** — the app is local-first. There is no cloud
  sync and no Control Deck server for the trial.
- **Trial window** — the preview unlocks everything through **2026-07-06**, then
  locks paid surfaces. Your decks and settings are not deleted.
- **No data-migration guarantee across major changes** — normal deck data should
  persist across updates, but this is a preview; keep your own backups of anything
  important.

Found something not listed here?
[Open an issue.](https://github.com/joffewilliam/control-deck-public/issues/new/choose)
