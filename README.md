# Theo — public web content

This repository exists for one reason: GitHub Pages needs a **public** repository to serve from, and
Theo needs two publicly reachable pages. It is served at <https://omar-codes.github.io/theo/>.

## What lives here

| File | Purpose |
| --- | --- |
| `privacy-policy.html` | The privacy policy, linked both from the app's Settings screen and from the App Store listing's privacy policy field — App Review Guideline 5.1.1(i) requires it in both places. |
| `index.html` | The support page, intended as the App Store listing's Support / Marketing URL. (Those two listing fields are not pointed here yet — that is a later step, not something this page's existence accomplishes on its own.) |
| `.nojekyll` | Tells GitHub Pages to serve these files as-is, without running Jekyll over them. |
| `README.md` | This file. Not served as a page — it states the repository's scope for whoever commits here next. |

## What must never live here — a standing rule, not a description of today

This repository is **public**. That is a constraint accepted deliberately in exchange for Pages
hosting, not an invitation to widen what it holds. Every future commit is bound by the same scope:

- **No app source code.** Theo's source lives in a separate private repository and stays there.
- **No keys, tokens, certificates, provisioning profiles, or `.p8` files** — for any service, ever,
  including anything that would only be reachable through commit history.
- **No build artifacts** — no `.ipa`, `.app`, `.xcarchive`, `.dSYM`, and no build logs.
- **No user data**, and no screenshots or fixtures containing anyone's real records.

Anything outside "public-facing static web content for Theo" is a scope change. The fix for such a
need is a different repository, never an exception made here.

## Editing the pages

Both pages are hand-written, dependency-free static HTML: inline CSS, no JavaScript, no trackers,
and no requests to any external host. Keep them that way — a privacy policy that loads a
third-party asset undercuts the thing it is claiming.

`privacy-policy.html` carries a "Last updated" date near the top. **Change that date whenever the
policy's substance changes.** The policy makes that promise to its readers in its own "Changes to
this policy" section, and the App Store listing points at this exact URL.

---

Theo is an independent app for logging the daily care of dogs and cats.
