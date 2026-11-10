# OnePort365 Operations Dashboard

A single-page operations dashboard: active shipments, the four pipeline
phases (Prospect, Pre-Booking, Booking, Post Booking) and a shipment
tracker with a detail drawer showing who handled each step and when.

- `index.html` — the dashboard (open it in a browser; no build step)
- `rfq.html` — the RFQ table; the RFQ step in a shipment's detail drawer
  opens it with that shipment's RFQ highlighted
- `quotes.html` — the quotes list and quote document; the Quote issued step
  in a shipment's detail drawer opens it on that shipment's quote
- `crm.html` — the CRM pipeline board; the Prospect heading in a shipment's
  detail drawer opens it with that deal highlighted in its stage
- `design/tokens.css` — OnePort 365 colours, type, spacing and shadows
- `design/DESIGN_SYSTEM.md` — the design system reference

The data is deterministic sample data generated in the page. The RFQ step
in the drawer links to `RFQ_TABLE_URL` (currently `rfq.html`). The Prospect link goes to `CRM_BOARD_URL`
(currently `crm.html`).
