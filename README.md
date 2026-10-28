# ADAM Keel: governed change plane (prototype)

Interactive prototype for an AI-led infrastructure, cloud and FinOps operations module inside ADAM Control Tower.
Agents propose changes; people approve them; autonomy is earned per action type and every change is verified with automatic rollback.

**Live prototype:** https://YOUR-USERNAME.github.io/adam-keel-prototype/

## Try these three moments
1. **Approve INT-4471** (order-api rolling restart). Verification passes and the held TLS rotation is released.
2. **Approve INT-4468** (rightsize db-orders-primary). A verification rule fails, the change rolls back automatically and the action type is demoted from L2 to L1.
3. **Open the Autonomy ledger** and promote "Clear a log volume" to L3 with evidence.

You can also halt execution from the left rail during a run, then resume it; paused intents continue from the step where they stopped.

## Notes
- All figures are illustrative sample data for a fictional client, Meridian Retail Group (2,140 hosts across AWS, Azure and two data centres).
- Single self-contained `index.html`; no build step. Fonts load from Google Fonts.
