# ZZZ Fast Track UI proposal

Interactive mockup for discussing how members could find, test, and report on small Fast track tasks in the ZZZ community. This is a community concept with illustrative task states, not a live deployment or an official implementation.

## Try it

Open `index.html` in a browser, or serve this folder locally with `python -m http.server 8000` and visit `http://localhost:8000/`. Use the Desktop and Mobile buttons to compare layouts. Open the emoji task, try the sample picker, and build a feedback draft. The draft stays in the browser until you choose to copy it. Links to ZZZ task discussions open the live forum, but the mockup does not submit anything there.


`index.html` contains the interface markup, styling, and interaction code in one file. Icons load from a version-pinned [Lucide](https://lucide.dev/) CDN; there is no build step, API key, or private configuration. The two tasks and their status labels are examples for discussion. Feedback is prepared locally and is never posted automatically.

