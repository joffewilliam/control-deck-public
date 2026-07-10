# Installing Control Deck

Windows 10/11 (x64).

## 1. Download and verify

Download the latest `Ctrl Deck Setup.exe` and
`release-checksums-sha256.txt` from the
[Releases page](https://github.com/joffewilliam/control-deck-public/releases).

In PowerShell, run:

```powershell
Get-FileHash '.\Ctrl Deck Setup.exe' -Algorithm SHA256
```

Compare the result with the checksum file from the same release.

## 2. Run the signed installer

The public installer is Authenticode signed. Cancel installation and report the
release if Windows shows **Unknown publisher** or reports an invalid signature.

The installer then runs with no further prompts. Control Deck installs **per-user**
(no admin needed) to `%LocalAppData%\ctrl_deck` and adds a **Start Menu** shortcut —
that's how you launch it afterward.

## 3. First run

- Accept the License Agreement.
- Enter your license key to activate Control Deck. Your key is in the purchase
  email from license@ctrldeck.dev and works on two devices.
- Choose the default agent permission level and whether workers may delegate
  externally.
- Complete the short onboarding (tool check + optional voice setup).
- Git is required; the agent CLIs (Claude, Codex, Cursor, OpenCode) are optional —
  install only the ones you use.

## Updates

Control Deck checks the signed Windows release feed in the background. When an
update is ready, use the in-app restart action to apply it. Your Founder license
covers all updates.

## Reporting problems

Use **Settings → Help & Feedback → Report a problem**, or open an issue on the
[public repo](https://github.com/joffewilliam/control-deck-public/issues).
Please don't paste API keys, tokens, license keys, private prompts, or full
terminal transcripts into public issues.

## Uninstall

Settings → Apps → *Ctrl Deck* → Uninstall (or the Start Menu uninstall shortcut).
Your decks and settings under `%AppData%\Ctrl Deck` remain unless you remove them
manually.
