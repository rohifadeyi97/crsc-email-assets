# CRSC email assets

Public, permanent image hosting for Chesapeake Region Safety Council (CRSC) email artwork.

- The CRSC Constant Contact MCP's `publish_canva_artwork` tool writes PNG exports of approved Canva designs to `assets/crsc/email-production/<sha256>.png` on `main`.
- Files are content-addressed and never overwritten; a changed design gets a new file and URL.
- Emails reference files at `https://raw.githubusercontent.com/rohifadeyi97/crsc-email-assets/main/assets/crsc/email-production/<sha256>.png`, so do not move, rename or delete them.
- Nothing else belongs here: no code, credentials or signed provider URLs.
