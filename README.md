# CRSC email assets

Public, permanent image hosting for Chesapeake Region Safety Council (CRSC) email artwork.

- The CRSC Constant Contact MCP's `publish_canva_artwork` tool writes PNG exports of approved Canva designs to `assets/crsc/email-production/<sha256>.png` on `main`.
- Files are content-addressed and never overwritten; a changed design gets a new file and URL.
- Emails reference files at `https://raw.githubusercontent.com/rohifadeyi97/crsc-email-assets/main/assets/crsc/email-production/<sha256>.png`, so do not move, rename or delete them.
- Nothing else belongs here: no code, credentials or signed provider URLs.

**Operational runbook:** [CRSC Canva → Constant Contact publishing SOP](https://github.com/rohifadeyi97/crsc-constant-contact-mcp/blob/main/docs/canva-to-constant-contact.md). Read it before editing approved artwork, hosting a PNG or replacing an email image. **Official course names and Canva document titles must not be changed without explicit user instructions.** The SOP documents a verified GitHub blob/tree/commit/ref fallback for approved assets if the standard artwork publisher's course-label validator rejects a legitimate printed title. Never bypass image approval, invent session details or overwrite existing content-addressed files.
