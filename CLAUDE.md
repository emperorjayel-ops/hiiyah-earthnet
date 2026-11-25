# CLAUDE.md — HIIYAH (HIIYAH Telecom / EarthNet)

Created by OPS' Broker

## Project

**HIIYAH** (spoken "hi-yah") — the telecom / EarthNet app of OMNI-PRESENT SOLUTIONS, INC: open-source media and telecommunications (voice-over-IP calling, video chat, voice chat, texting, large-file sharing, screen sharing) with a world map. Owner: Honorable Jay Ladon Dickey Sr. EL.

Front domain: **none picked yet** — do not invent one. The app serves from its GitHub Pages address until the owner picks a domain. Google Play package: `com.omnipresentsolutions.hiiyah`.

## Tech in this folder

- `index.html` — the entire app: one self-contained HTML file (HTML/CSS/JavaScript inline, no build step, no framework, no server). Edit it directly.
- `privacy.html` — the hosted privacy policy page for the Play Store listing.
- `README.md` — project note. Keep it accurate when behavior changes.

There is no backend. Calling/chat features are demo/session-only in the browser unless this file says otherwise.

## Standing rules (apply to every change)

- **Cross-platform, no exceptions:** must work on the owner's Samsung Galaxy S9 (SM-G960U), iPhones (Safari/WebKit), all other phones, and laptops/desktops. Responsive at every width.
- **Adjust to the device:** runtime feature detection and progressive enhancement — WebGL2 → WebGL1 → CSS fallback; camera/microphone features fall back gracefully where unsupported; auto quality scaling; honor reduced-motion and low-power signals.
- **Lane separation — strict:** HIIYAH keeps a **world map**. **No Excalibur Line train in HIIYAH material, and no HIIYAH material in Excalibur Line.** The hologram for HIIYAH is its own world/network globe, never the train or sword.
- **One-picture rule:** visuals blend into one seamless picture — matched lighting, perspective, color, shadows. Logos merge into the design with no visible outlines or background-box edges.
- **Cross-app sidebar:** every app in this family (Excalibur Line, FinSwap, HIIYAH, Dominion Network, PMI God's Eye) carries a sidebar linking to all the others. Keep it intact and uniform. Member-to-admin talk in PMI God's Eye routes "via HIIYAH" — keep that naming consistent.
- **Credit:** the line "Created by OPS' Broker" / "Shared by OPS' Broker" stays in the files. Do not remove it, do not add any other creator name.
- **Honesty:** never present a demo or session-only feature as live, and never present an eSIM/SIM activation as real — there is no provider connection.

## ⭐ PAYMENTS — scoped, and the eSIM hold

HIIYAH's payment work is **telecom payments only**, and part of it is on hold by the owner's direct order:

- **eSIM/SIM provider work is SHELVED.** The owner shelved it on 2026-11-24 until he delivers the provider information himself. Do **not** build eSIM activation, do not integrate any eSIM provider, and do not present activation as possible. When the provider information arrives, payments for plans/eSIM are to be **real transactions**: end users pay from their own real wallets on the open-source Bitcoin stack (**Bitcoin Core + Counterparty**), supporting **Bitcoin (BTC), PERFECTCERTS, WEALTHTICKET**, and **Alpine Gold-backed currencies**.
- **Never hold, request, receive, store, or transmit a user's seed phrase or private key — server-side or anywhere else.** Users sign in their own wallets; a public address is all a flow may ask for.
- The rest of the app (calling, chat, maps, interface) is worked on normally — the hold covers eSIM/provider work only.
- Label honestly anything not yet live.

## Working notes

- Test every change at phone width (Galaxy S9) and desktop width before calling it done, and check Safari/WebKit behavior for anything using newer APIs.
- Report only completed, verified results. An attempt is not a result.
