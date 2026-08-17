# 1001 Pro Calculator — privacy policy

The published privacy policy for the Android app **1001 Pro Calculator**
(`com.calcverse.calcverse`), hosted here because Google Play requires the
policy to be reachable at a public URL that loads without a login.

**Live at:** https://kairosmaster.github.io/1001-pro-calculator-privacy/

---

## This repository holds one file on purpose

`index.html` and this README. Nothing else belongs here.

The app itself is in a **private** repository and stays there. This repo exists
only so Play has a URL to point at, and it is deliberately unrelated to that
one — a separate repository with its own history, rather than a branch or a
subtree of the app. A branch would have carried the app's entire history into a
public place, which is precisely what this arrangement avoids.

So: **do not add source, build output, screenshots, keys, or anything else
here.** If something needs publishing, ask whether it needs to be *this* repo.

## Editing it

The canonical text lives with the app, as `PRIVACY.md`, and there are three
copies that must agree: that Markdown, the hostable HTML, and the app's own
*Privacy & disclaimer* screen. A test in the app's repository holds them to
each other.

Which means: **do not edit `index.html` here.** Change the policy in the app
repository, then copy `store/privacy-policy.html` over this file and commit.
Editing here would make the published policy disagree with the one in the app,
which is the failure the whole arrangement is built to prevent.

## The page

Self-contained by design — no scripts, no external stylesheet, no fonts, no
analytics, nothing fetched from anywhere. A privacy policy that pulls a font
from a CDN reports its reader's IP address to a third party on the page
explaining what is collected. Its only outbound links are Google's own privacy
policy and a `mailto:`.

It renders light and dark, and reflects the reader's system theme.
