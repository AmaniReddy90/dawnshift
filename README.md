# DawnShift legal and support pages

Static site served by GitHub Pages at https://amanireddy90.github.io/dawnshift/ (branch `main`, folder `/`).
Plain HTML and one stylesheet (`style.css`); no scripts, analytics, trackers, external fonts or CDNs.

**Not legal advice — reviewed by the founder.** These pages were written from each app's own privacy, data-safety and
permission documents and the founder's decisions. Nobody with legal training has reviewed them.

## Pages

| App | Privacy | Terms | Support |
|---|---|---|---|
| Docwise | `docwise/privacy/` | `docwise/terms/` | `docwise/support/` |
| LockDo | `lockdo/privacy/` | `lockdo/terms/` | `lockdo/support/` |
| PhotoOne | `photoone/privacy/` | `photoone/terms/` | `photoone/support/` |
| GST Invoice & Quote Maker | `gst-invoice/privacy/` | `gst-invoice/terms/` | `gst-invoice/support/` |
| Bill Splitter | `bill-splitter/privacy/` | `bill-splitter/terms/` | `bill-splitter/support/` |
| AR Arcade | `ar-arcade/privacy/` | `ar-arcade/terms/` | `ar-arcade/support/` |

Effective date on every page: 10 November 2026. Support email: amakatsolutions@gmail.com (taken from the app repos).

## Updating

Edit the HTML here, change the effective date on the page you changed, run
`node "<AI Company>/tools/ai-mention-check.js" .` (and a scan of the root files, since that tool only reads app
folders), commit, and push. GitHub Pages rebuilds in about a minute. Only the founder's developer session pushes.

## For the founder to check

- Terms pages show the publisher's postal address (as in the existing GST Invoice and PhotoOne terms). Remove it if you
  do not want it public.
- LockDo's policy describes the AdMob rewarded ads decided on 9 Nov 2026; the app does not contain the ad SDK yet.
  Keep the policy and the build in step before release.
- Docwise's policy describes the optional Apple Private Cloud Compute setting and the Android Gemini Nano / "Smart
  answers" download decided on 9 Nov 2026; neither is in the app yet.
