# API Finder - update channel

Public host for the [API Finder](https://addons.mozilla.org) Firefox add-on's self-distribution auto-update: `updates.json` plus the signed `.xpi` files it links to. The add-on's source lives elsewhere; only these distributable artifacts are here.

Firefox reads `updates.json` from this repo (declared as the add-on's `update_url`) and installs any newer signed build automatically.
