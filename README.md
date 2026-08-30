# daytrip-invite

Hosts the redirect page DayTrip's friend-invite links point to.

- `invite.html` — turns `?code=<uuid>` into the `daytrip://invite/<uuid>` deep
  link, so a link shared over SMS/WhatsApp/email can hand off into the app.

Served via GitHub Pages:
https://tr3yv3n.github.io/daytrip-invite/invite.html?code=<code>

This repo is a mirror pushed from `docs/invite/` in the main (private)
DayTrip repo — that's the source of truth to edit.
