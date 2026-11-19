[README.md](https://github.com/user-attachments/files/35075709/README.md)
# Dr.-Naheem-K.-T.-Academic-Portfolio
Academic profile of Dr. Naheem K. T., Pondicherry University, showcasing his publications, research metrics, awards, professional experience and peer review activity in Library and Information Science.
# Academic Dashboard: Dr. Naheem K. T.

A searchable, editable academic profile dashboard (publications, metrics, awards, experience, peer review). It is a plain static site: no build step, no dependencies.

## Files
| File | Purpose |
|---|---|
| `index.html` | The dashboard (search, filters, charts, CSV export) |
| `data.js` | **All content.** Edit this file to update the dashboard |
| `photo.jpg` | Profile photo (replace with the same name, or change `photo` in `data.js`) |

## Publish on GitHub Pages
1. Create a repository and upload these three files to the root.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
3. Your dashboard will be live at `https://<username>.github.io/<repo>/` within a minute or two.

You can also open `index.html` directly in a browser to preview locally.

## Update the content
Open `data.js` and edit the values. Commit the change and the site updates.

- **Add a publication:** copy any block inside `"publications"` and edit it. Fields: `type` (`journal`, `chapter` or `conference`), `year`, optional `month`, `authors`, `title`, `source`, optional `scopus` and `wos` citation counts, `doi`, `id`, `award`, `extra`. Give it the next number in `n`.
- **Add an award:** add an item to `"awards"`. Add an `"award"` field to the matching publication to show a ★ badge and make it appear under "Awarded only".
- **Update metrics:** edit `"metrics"` (rows and the `asOf` date). KPI cards and totals are calculated automatically from the publication list.

## Using the dashboard
- Press `/` to jump to search. Search covers publications, awards, experience, education, skills and peer review. Multiple words must all match.
- Filter by type, year (or click a bar in the chart), awarded only; sort by date or Scopus citations.
- **Export CSV** downloads the currently filtered publications.
- Light and dark themes follow the visitor's system setting; the page is print-friendly.

Compiled by: Dr. Naheem KT, ARP Library, Pondicherry University
