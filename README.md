# Why are nonviolent campaigns winning less often?

A single-page data story built on 622 resistance campaigns from 1900 to 2019. It tests three explanations for the recent fall in the success rate of nonviolent campaigns: unfinished campaigns being scored as failures, crowding, and falling freedom.

## Files

- `index.html` — the page. Charts are drawn in the browser with Plotly, loaded from `cdn.plot.ly`.
- `data.js` — the data the page reads: one row per campaign, a freedom-index series per country, and the world average by year.

There is no build step. Any static host can serve the two files as they are.

## Data sources

- **Campaigns:** NAVCO 1.3 list, Erica Chenoweth and Christopher Wiley Shay (Harvard Dataverse).
- **Freedom index:** V-Dem Civil Liberties Index (`v2x_civlib`), V-Dem Institute.

Regions were assigned by hand, because the campaign file has none. The page's "About the data" section lists the other choices made.
