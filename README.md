# Website Catalog

A filterable gallery of reference websites, tagged by industry, style and type.

## Add a site
1. Put the cover in `media/` as `<id>.jpg` (about 900px wide). If you have a video cover, add `<id>.mp4` too.
2. In `index.html`, add a line to the `SITES` list:
   ```js
   {id:"example", name:"Example", url:"https://example.com/", v:1, t:["Technology","Clean","SaaS"]},
   ```
   Leave out `v:1` when there is no video. Tags must match the names in `TAGS`.

## Run locally
Open `index.html` in a browser, or run `npx serve .` in this folder.
