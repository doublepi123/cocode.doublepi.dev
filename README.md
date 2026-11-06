# CoCode website compatibility redirect

Public bilingual product page for [CoCode](https://github.com/doublepi123/co_code), the Android app that runs Cox locally without root.

**Website: https://doublepi.dev/cocode/**

The product page is now built with Cox's website from `site/cocode/` in `doublepi123/cox`
and published under `cocode/` in `doublepi123/doublepi123.github.io`.
This repository retains its history, original assets, license and notice, but its entry
page only redirects to the new location. It does not contain an app binary, credentials,
user projects or a hosted coding-agent service.

GitHub Pages still publishes the root of `main`. Preserve the existing `CNAME` to avoid
reassigning the legacy custom domain. The redirect source is `site/redirects/cocode.html`
in `doublepi123/cox`; old-domain redirects work only if that domain's DNS and HTTPS are
reachable. The new page does not depend on the old domain.

The new page links to [Cox](https://doublepi.dev/), and the Cox homepage links back to it.
CoCode and Cox run independently; the website does not imply a remote connection between them.
