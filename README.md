# Three Wars Timeline

An interactive [TimelineJS](https://timeline.knightlab.com/) timeline of three major wars:

- **American Civil War** (1861–1865)
- **World War I** (1914–1918)
- **World War II** (1939–1945)

Each event links to its Wikipedia article as media.

## Files

- `index.html` loads TimelineJS3 from the Knight Lab CDN
- `timeline.json` holds the timeline data (title, eras and events)

## Run locally

TimelineJS fetches `timeline.json` over the network, so serve the folder instead of opening the file directly:

```
python -m http.server 8000
```

Then open http://localhost:8000.
