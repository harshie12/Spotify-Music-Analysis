# Spotify Music Analysis

**Project year:** 2025  
**Tool:** Microsoft Power BI Desktop  
**Report file:** [`Spotify-Music-Analysis.pbix`](./Spotify-Music-Analysis.pbix)

## Overview

An interactive report exploring music streaming performance, track counts, average streams, release dates, monthly patterns, daily streams, and top-streamed tracks.

This README documents the visuals and labels present in the report. It intentionally does not state numerical findings or conclusions that have not been verified against the report.

## Dashboard preview

Add clear screenshots of the report to the `images/` folder, then uncomment and update the following example:

```markdown
![Dashboard overview](./images/dashboard-overview.png)
```

Make sure screenshots are readable and do not expose private or restricted information.

## What is included

- KPI cards labelled Streams, Tracks, and Avg Streams
- A line chart labelled Streams by Released Date
- A table labelled Tracks and Streams by Month
- A bar chart labelled Daily Streams for all Tracks
- A visual labelled Top 5 Most Streamed Tracks
- Slicers labelled Tracks, Date, and Artist(s)

## Questions this dashboard can help explore

- How are streams distributed across tracks and release dates?
- How do track streams vary by month and day?
- Which tracks rank among the most streamed in the report?

These are exploratory questions based on the report's visible labels, not claims about the results.

## Data source and methodology

- **Dataset/source:** Add the original dataset name and source URL.
- **Data preparation:** Describe the transformations only after confirming them in the PBIX.
- **Calculations:** Document verified DAX measures, calculated columns, or other calculations, if used.
- **Limitations:** Note any known data-quality or scope limitations.

## Key insights

-**Overall streaming activity**: The dashboard's Streams KPI displays approximately 231 billion streams across the currently selected report data.

-**Track coverage**: The report displays 443 tracks, with monthly summaries showing track counts and average streams.

-**Daily streaming patterns**: Wednesday has the longest bar in the displayed daily-streams chart, while Thursday has the shortest. These comparisons reflect the current report view.

-**Top-streamed tracks**: The report includes a Top 5 Most Streamed Tracks visual, with Shape of You appearing first in the displayed selection.

## How to open

1. Download the `.pbix` file linked above.
2. Open it using Microsoft Power BI Desktop.
3. If prompted, connect only to data sources you are authorized to access.

## Privacy, licensing, and attribution

Confirm that the dataset can be redistributed and that no restricted source data or credentials are included.

Credit the dataset owner and follow the dataset's license and terms. Do not publish credentials, confidential data, or personal information.

