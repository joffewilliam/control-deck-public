# Control Deck — Privacy Note

_Last updated: 2026-07-02_

Control Deck is **local-first**. Your decks, settings, and credentials are stored
on your own device. Secrets (API keys and tokens) are kept in your operating
system's credential store, not in plaintext. The Developer does **not** operate a
hosted Control Deck account and does **not** collect analytics or telemetry from
the app.

**What the Developer receives:**

- **Purchase.** When you buy a license, payment is handled by Stripe, Inc. The
  Developer receives your email address and purchase details from Stripe but never
  your full card number. Your license key is emailed to you through Resend.
- **Activation.** To activate and periodically re-validate your license, the
  Software sends your **license key** along with a device identifier and device
  name to the Developer's licensing server (hosted on Supabase) so it can enforce
  the two-device limit and return a signed entitlement the app can check offline.
  No decks, prompts, or file contents are sent.

This information is used only to sell and license the Software, provide support,
and prevent abuse. It is kept only as long as needed for those purposes and to
meet legal and accounting obligations, is never sold, and is not used for
advertising. You may request access to or deletion of your data, subject to
records the Developer is required to keep, by emailing license@ctrldeck.dev.

Feedback is collected only through **GitHub Issues**, and only when you choose to
file one. When you do, do not paste API keys, OAuth tokens, license keys, private
prompts, customer data, or full terminal transcripts into a public issue.

The Software connects to third-party AI providers, command-line tools, and update
services that you configure or that are needed to deliver updates. Those services
have their own privacy policies and receive data according to your use of them.
