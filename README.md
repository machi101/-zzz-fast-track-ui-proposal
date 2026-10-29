# ZZZ Fast Track UI proposal

Interactive mockup for discussing how members could find, test, and report on small Fast track tasks in the ZZZ community. This is a community concept with illustrative task states, not a live deployment or an official implementation.

## Try it

Open `index.html` in a browser, or serve this folder locally with `python -m http.server 8000` and visit `http://localhost:8000/`. Use the Desktop and Mobile buttons to compare layouts. Open the emoji task, try the sample picker, and build a feedback draft. The draft stays in the browser until you choose to copy it. Links to ZZZ task discussions open the live forum, but the mockup does not submit anything there.

## Publish with GitHub Pages

Create a repository named `zzz-fast-track-ui-proposal`, upload `index.html` and `README.md` to its root, then select **Settings → Pages → Deploy from a branch → main / (root)**. GitHub Pages will serve `index.html` at `https://YOUR-USERNAME.github.io/zzz-fast-track-ui-proposal/`. Replace `YOUR-USERNAME` with the account that owns the repository. Add that live link to the [Fast track design discussion](https://zzz.protocol.link/task/a1228cc3-dbba-4e50-ba3c-e93c42d9bddc?reply=108734048637026304#reply-108734048637026304).

## Source and scope

`index.html` contains the interface markup, styling, and interaction code in one file. Icons load from a version-pinned [Lucide](https://lucide.dev/) CDN; there is no build step, API key, or private configuration. The two tasks and their status labels are examples for discussion. Feedback is prepared locally and is never posted automatically.

The narrated walkthrough can be linked in the forum separately; it is not needed to run the site. No video, captured screenshots, render scripts, or recording frames are part of this source repository.
