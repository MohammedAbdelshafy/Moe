# Nadeen Bridal RSVP

Production-ready RSVP microsite for Nadeen Omar Abdelshafy.

Live app: https://nadeen-bridal-rsvp-suztwr.v2.appdeploy.ai/

## Final specification
- September 5, 7 PM
- Sqeel Family House
- Blush pink / ivory feminine editorial aesthetic
- Supplied invitation artwork as the visual reference
- Muslim-friendly: no alcohol/champagne references
- RSVP: full name, WhatsApp/phone, attending, Beef or Chicken, dietary notes, message
- No plus-one field
- Persistent server-side RSVP storage
- Private host dashboard with Attending / Not attending / All responses
- CSV export
- Responsive mobile-first UX

## OpenCode / Antigravity handoff prompt
Use this repository as the source of truth. Continue from the current production RSVP implementation without deleting working functionality. Preserve the visual design from the supplied invitation artwork and the live app. Audit the entire RSVP flow end-to-end on mobile and desktop. Fix any defects, accessibility issues, validation edge cases, and persistence failures. Ensure the public guest page is beautiful, fast, and touch-friendly. Ensure there is exactly one public RSVP workflow, no plus-one option, and meal choice is only shown when attending. Keep the admin dashboard private and never expose the admin password or raw guest data in client code. Keep CSV export working and safe. Add automated tests for submit-attending, submit-not-attending, validation failure, and admin export. Do not seed fake guests. Commit every stable improvement to a dedicated branch first, then merge only after tests pass. Do not replace the existing working deployment unless the replacement is verified. Add Telegram CSV delivery only through a secure server-side secret/configuration path, never hard-code bot tokens. Preserve rollback capability at all times.