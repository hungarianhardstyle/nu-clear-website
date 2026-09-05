# Nu-Clear project state

Status: CLOSED / READY TO RESUME
Last saved: 2026-09-06

- Astro static website for Nu-Clear, Hungarian/English language switcher.
- Production domain: https://nu-clearmusic.com/
- GitHub: https://github.com/hungarianhardstyle/nu-clear-website
- Cloudflare Pages project: `nu-clear-website`.
- GitHub Actions deploy is active.
- Cloudflare DNS is active for `nu-clearmusic.com`.
- Web records are proxied; mail records are DNS only.
- FTP record: `ftp.nu-clearmusic.com` → `37.9.175.172`, DNS only.
- Current Event JSON-LD includes `offers`, `image`, `description`, and `organizer`.
- Scroll Craft was reviewed but not integrated; the current Nu-Clear design remains unchanged.

The project is considered complete for now. Resume from the latest commit on `main`.
The full Git history and GitHub Actions deployment history are the source of truth.

Local upload packages are kept in `outputs/` and are intentionally not part of the Git history.
