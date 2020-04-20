## Modfied

This is a modified fork of Puppeteer as a service to deploy a copy since the original is now no longer up / maintainted.

# puptraas

<a href="https://github.com/NickFoden/pptraas.com"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_darkblue_121621.png" alt="Fork me on GitHub"></a>

## Render

### Render page as a PNG

https://puptraas.herokuapp.com/screenshot?url=https://www.liberiachimpanzeerescue.org/ (full page)

https://puptraas.herokuapp.com/screenshot?url=https://developers.google.com&size=400,400

https://puptraas.herokuapp.com/screenshot?url=https://www.wikipedia.org&element=.central-featured

### Render page as a PDF

https://puptraas.herokuapp.com/pdf?url=https://www.liberiachimpanzeerescue.org/

### Render generated static markup of page ("SSR")

https://puptraas.herokuapp.com/ssr?url=https://angular2-hn.firebaseapp.com/

### Render as Google Search bot

Detects what features a page is using and cross references them with the features
supported by the [Google Search bot](https://developers.google.com/search/docs/guides/rendering).

https://puptraas.herokuapp.com/gsearch?url=https://www.liberiachimpanzeerescue.org/

## Performance

### Get a timeline trace

https://puptraas.herokuapp.com/trace?url=https://www.liberiachimpanzeerescue.org/

#### View the trace in trace-viewer:

https://chromedevtools.github.io/timeline-viewer/?loadTimelineFromURL=https://puptraas.herokuapp.com/trace?url=https://www.liberiachimpanzeerescue.org/

### Get metrics

https://puptraas.herokuapp.com/metrics?url=https://www.liberiachimpanzeerescue.org/

## Misc

### Print UserAgent / Chromium version

https://puptraas.herokuapp.com/version

---
