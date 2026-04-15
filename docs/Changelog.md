# Changelog

## 1.0.10 (vs 1.0.9)

- Fixed a ticket-edit regression that could remove row-based waitlist entries during ticket saves. Waitlist rows are now preserved unless the ticket itself is intentionally deleted.
- Updated Tickets admin action flows to auto-reload the page after successful ticket-related actions (refund/cancel actions, waitlist-entry removal, and refund-request actions) so admins always see fully refreshed data.
- Added/updated documentation for both behaviors in:
  - `docs/TicketsAdmin.md`
  - `docs/TicketAttendees.md`

## 1.0.9

- Previous release baseline.
