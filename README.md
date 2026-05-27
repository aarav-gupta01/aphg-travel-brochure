# APHG Travel Brochure

Interactive AP Human Geography travel brochure for a two-person world tour. The site is a single-page HTML project with tabbed country pages, itinerary details, APHuG concept connections, activity maps, an overall trip map, and a running budget balance.

## Live Site

This repo is set up for GitHub Pages. The main file is:

```text
index.html
```

GitHub Pages should serve the project from the repository root.

## Trip Overview

- Total budget: `$35,000`
- Travelers: `2`
- Trip dates: `June 3-24, 2026`
- Route: `SFO -> NYC -> Trinidad and Tobago -> Uruguay -> Nigeria -> France -> Taiwan -> Australia -> SFO`
- Final estimated remaining balance: `~$19,714`

## Flight Logistics

| Leg | Date | Airline | Departure | Duration | Cost |
| --- | --- | --- | --- | --- | --- |
| SFO to NYC | Jun 3 | Alaska Airlines | 6:15 AM | 5h 48m | $312/person |
| NYC to Trinidad and Tobago | Jun 6 | American Airlines | 5:35 AM | 8h 36m | $217/person |
| Trinidad and Tobago to Uruguay | Jun 9 | Copa Airlines | 3:50 AM | 20h 12m | $1,312/person |
| Uruguay to Nigeria | Jun 12 | Qatar Airways / Airlines Brasil | 12:00 PM | 39h 25m | $1,287/person |
| Nigeria to France | Jun 15 | Royal Air Maroc | 6:55 AM | 9h 25m | $545/person |
| France to Taiwan | Jun 17 | Multiple airlines | 1:25 PM | 15h 35m | $565/person |
| Taiwan to Australia | Jun 19 | Multiple airlines | 12:20 PM | 18h 40m | $905/person |
| Australia to SFO | Jun 24 | Philippine Airlines | 10:15 AM | 27h 55m | $866/person |

Total flight cost for two people: `$12,018`.

## Viewing Locally

Open `index.html` directly in a browser, or run a local server from the repo folder:

```bash
python3 -m http.server 8001
```

Then visit:

```text
http://localhost:8001/
```

## External Assets

The project does not require local image files. It loads remote assets from:

- Google Fonts
- Wikimedia Commons images
- OpenStreetMap map tiles

An internet connection is required for the fonts, images, and map backgrounds to load correctly.

## Project Structure

```text
.
├── index.html
└── README.md
```

