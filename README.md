# OnePort365 Operations Dashboard

A single-page operations dashboard: active shipments, the four pipeline
phases (Prospect, Pre-Booking, Booking, Post Booking) and a shipment
tracker with a detail drawer showing who handled each step and when.

- `index.html` — the dashboard (open it in a browser; no build step)
- `design/tokens.css` — OnePort 365 colours, type, spacing and shadows
- `design/DESIGN_SYSTEM.md` — the design system reference

The data is deterministic sample data generated in the page. The RFQ step
in the drawer links to `RFQ_TABLE_URL` (currently `/rfq`) — set it to the
backoffice RFQ table address.
