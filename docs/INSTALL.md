# Installing Control Deck

Windows 10/11 (x64).

## 1. Download

Grab the latest `Ctrl Deck Setup.exe` from the
[Releases page](https://github.com/joffewilliam/control-deck-public/releases).

## 2. Run the installer (expect a SmartScreen prompt)

The installer is **not code-signed yet**, so Windows SmartScreen will show a blue
**"Windows protected your PC / Unknown publisher"** dialog. This is expected for
now. To continue:

1. Click **More info**.
2. Click **Run anyway**.

The installer then runs with no further prompts. Control Deck installs **per-user**
(no admin needed) to `%LocalAppData%\ctrl_deck` and adds a **Start Menu** shortcut —
that's how you launch it afterward.

> Signed builds (no SmartScreen warning) are on the way.

## 3. First run

- Accept the License Agreement.
- Enter your license key to activate Control Deck. Your key is in the purchase
  email from license@ctrldeck.dev and works on two devices.
- Complete the short onboarding (tool check + voice setup).
- Git is required; the agent CLIs (Claude, Codex, Cursor, OpenCode) are optional —
  install only the ones you use.

## Updates

Control Deck updates itself in the background. New versions install on the next
launch — no need to re-download. Your Founder license covers all updates.

## Reporting problems

Use **Settings → Help & Feedback → Report a problem**, or open an issue on the
[public repo](https://github.com/joffewilliam/control-deck-public/issues).
Please don't paste API keys, tokens, license keys, private prompts, or full
terminal transcripts into public issues.

## Uninstall

Settings → Apps → *Ctrl Deck* → Uninstall (or the Start Menu uninstall shortcut).
Your decks and settings under `%AppData%` remain unless you remove them manually.
