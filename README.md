# Police Data Accessibility Project Scrapers
This repo contains the data scrapers for [Police Data Accessibility Project](https://pdap.io). Thank you for being here!

Scrapers are one piece of the puzzle of making police data more accessible. For a broader look at the work we're doing, and where our attention is focused, start with the docs: https://docs.pdap.io/ and the roadmap: https://github.com/orgs/Police-Data-Accessibility-Project/projects/17

# How to run a scraper
Right now, this requires some Python knowledge and patience. We're in the early stages: there's no automated scraper farm or fancy GUI yet.

1. Install Python.
2. [Clone this repo](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
3. Find the scraper you wish to run. These are sorted geographically, so start by looking in `/USA/...`.
4. Run the `scraper.py` file with something like `python3 <scraper path>` depending on how you  installed it.

## Did it work?
If it worked, discuss your findings in our [Discord](https://discord.gg/wMqex8nKZJ). If it didn't, make an issue in this repo or reach out in Discord.

# How to contribute
To write a scraper, start with [CONTRIBUTING.md](https://github.com/Police-Data-Accessibility-Project/PDAP-Scrapers/blob/main/CONTRIBUTING.md). Be sure to check out the [/common folder](https://github.com/Police-Data-Accessibility-Project/PDAP-Scrapers/tree/main/common/)!

For everything else, start with [docs.pdap.io](https://docs.pdap.io/).

## What data are we scraping?
The [data sources listed here](https://www.dolthub.com/repositories/pdap/data_sources) are our to-do list. If we should targeting a new data type, suggest it in Discord or make a DoltHub PR!

## Resources
Potentially useful tools. If you find something useful, or if one of these is out of date, make a PR!
- https://www.scrapingbee.com/
- https://github.com/CJWorkbench/cjworkbench
