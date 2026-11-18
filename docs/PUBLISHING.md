# Publishing checklist

- [x] Replace `YOUR-GITHUB-USER` (`DKAnord`) and `<YOUR NAME>` (`DKAnord`) — git author `DKAnord <12734694+DKAnord@users.noreply.github.com>`
- [ ] Test on a **clean HA** (or a fresh browser profile / fresh dashboard) using only `examples/dashboard.yaml`
- [ ] Test with no videos, with partial videos, and with all 9
- [ ] Test `language: en` and `da`, and a non-Danish HA location/time zone for the sleigh tracker
- [ ] Take screenshots (board, cams, sleigh, nice list) → `docs/`
- [ ] Grep for private data: IPs, hostnames, family names, entity IDs, ntfy URLs, tokens
- [ ] `git init`, commit, push, **tag `v2.1.0`** and create a GitHub Release (HACS needs a release for versioning)
- [ ] Attach `nordpol-videos.zip` to the release (optional pack, with licence note)
- [ ] (Optional) Submit to the HACS default list: https://github.com/hacs/default
