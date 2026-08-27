# 1001 Pro Calculators — privacy and support

The published privacy policy and support page for **1001 Pro Calculators: All-in-1**
(Play: `com.calcverse.calcverse`; App Store: `com.calcverse.apple`). Hosted here
because both stores require public URLs that load without a login.

**Privacy:** https://kairosmaster.github.io/1001-pro-calculator-privacy/

**Support:** https://kairosmaster.github.io/1001-pro-calculator-privacy/support.html

---

## What belongs here

`index.html`, `support.html`, and this README. Nothing else.

The app itself is in a **private** repository and stays there. This repo exists
only so the stores have URLs to point at, and it is deliberately unrelated to
that one — a separate repository with its own history, rather than a branch or
a subtree of the app. A branch would have carried the app's entire history into
a public place, which is precisely what this arrangement avoids.

So: **do not add source, build output, screenshots, keys, or anything else
here.** If something needs publishing, ask whether it needs to be *this* repo.

## Editing it

The canonical text lives with the app. There are copies that must agree: the
Markdown and hostable HTML in the app repository, the app's own *Privacy &
disclaimer* screen, and the files here. A test in the app's repository holds
the in-app copies to each other.

Which means: **do not edit `index.html` or `support.html` here.** Change them
in the app repository, then copy:

- `store/privacy-policy.html` over `index.html`
- `store/support.html` over `support.html`

Editing here would make the published pages disagree with the ones in the app,
which is the failure the whole arrangement is built to prevent.

## The pages

Self-contained by design — no scripts, no external stylesheet, no fonts, no
analytics, nothing fetched from anywhere. A privacy policy that pulls a font
from a CDN reports its reader's IP address to a third party on the page
explaining what is collected. The only outbound link is a `mailto:`.

They render light and dark, and reflect the reader's system theme.
