# GIFT License v1.0 (Dual License: CC0 + MWL)

## 📜 1. Theory License: CC0 1.0 Universal

All theoretical constructs, mathematical formulations, moral architecture, and constants defined under The GIFT framework are released under the Creative Commons Zero 1.0 Universal license (CC0). This means:

- You may use, copy, modify, and distribute the theory freely.
- Attribution is appreciated but not required.

<https://creativecommons.org/publicdomain/zero/1.0/>

## 🔐 2. Applications License: GIFT Moral Worth License (MWL)

All implementations, software, hardware, AI models, policy frameworks, economic instruments, and any derived systems from the GIFT framework are governed by the following MWL conditions:

| Moral Worth (MW) | License Outcome              |
|------------------|------------------------------|
| MW > 0           | Free to use (beneficial use) |
| MW = 0           | φ × base_cost                |
| MW < 0           | Prohibited                   |

Where:
- MW is defined as: `MW = -ΔK × J(state) × γ × P`
- φ = golden ratio ≈ 1.618
- base_cost = production or deployment cost

Usage with negative MW, including exploitative surveillance, ecological destruction, or coercive governance, is explicitly forbidden under this license.

## 🛡️ 3. Enforcement and Trust

All rights not explicitly granted are reserved by The GIFT of Truth LLC (Washington State, USA | UBI #605 995 464). This license grants no authority to claim GIFT-derived systems for profit or control without MW-compliant evaluation.

This file is binding under GIFT Claim 75–76 and supported by international moral contract law.

---

**This is the GIFT. You are free if you act in good faith.**
"""

# Write the LICENSE file to disk
license_path = Path("/mnt/data/LICENSE")
license_path.write_text(license_text.strip())

license_path.name  # Return the filename for download

