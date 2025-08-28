MVP Specification: Trophaeum Genesis
🎯 Objective

Deliver a Minimum Viable Product (MVP) that demonstrates Trophaeum’s core cycle:

Users scan/link Sun 🌞, Moon 🌙, and Earth 🌍 nodes in AR/VR.

The scan triggers token emissions and treasury flows.

Balances update live, visible in counters and simple VFX.

This MVP proves that Trophaeum’s mythic story can be experienced directly as a working protocol.

🌀 Scope
In-Scope

AR/VR open plain with Sun, Moon, Earth objects.

Scanning ritual interaction (tap/gaze → API call).

Treasury counters visible and updating in real-time.

Auto wallet creation on login (custodial for MVP).

Backend API (Node/Express) for handling scans + treasury balances.

Testnet TROPHY token (ERC-20 on Avalanche Fuji).

Out-of-Scope (for MVP)

Full micro-node marketplace.

Macro node districts.

Governance voting.

Custom tokens for brands.

Advanced AR overlays or multi-user VR.

🔄 User Flow

Enter world → See open plain with Sun (sky), Moon (sky), Earth (ground).

Scan Sun → Gold beam flows to Earth.

Scan Moon → Silver ripple flows to Earth.

Scan Earth → Earth treasury updates + offering flows to Moon.

Counters update visibly for all three treasuries.

Wallet panel shows earned TROPHY balance.

Loop time: <60 seconds.

✅ Success Metrics

Cold user can complete one ritual loop in under 1 minute.

Live counters update reliably (Sun, Moon, Earth).

App runs at 60fps on Quest and <10s load time in WebGL.

No crypto knowledge required (login = wallet).

🛠 Tech Stack

Unity (URP, OpenXR) → VR + WebGL build.

Node/Express + WebSocket → backend API + live updates.

Avalanche Fuji testnet → TROPHY token + treasuries.

Web3Auth / Magic → custodial wallet on login.

📅 Timeline (MVP Build ~4 Weeks)

Week 1: Greybox Unity scene + contract deploy (TROPHY, treasuries).
Week 2: Backend API + Unity integration (scan → counters).
Week 3: Custodial login + live flows + basic VFX.
Week 4: QA, polish visuals, record demo video.

✨ Summary
This MVP proves the core Trophaeum cycle (Sun → Earth → Moon → user rewards). It sets the stage for indigenous onboarding, grant applications, and expansion into the cultural web.
