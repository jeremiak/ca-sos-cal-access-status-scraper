# How often is [Cal-Access](https://cal-access.sos.ca.gov) down?

I'm not sure, this scraper is an attempt to figure that out. I'm using Github actions to get the HTTP status code from https://cal-access.sos.ca.gov. The scraper runs every five minutes and commits the status if it has changed. I plan to use [`git-history`](https://datasette.io/tools/git-history) to do the analysis.

[![Get status of Cal-Access](https://github.com/jeremiak/ca-sos-cal-access-status-scraper/actions/workflows/scrape.yml/badge.svg)](https://github.com/jeremiak/ca-sos-cal-access-status-scraper/actions/workflows/scrape.yml)

## What is Cal-Access?
It's the California Secretary of State's basic tool for campaign finance data. It's really old and it's been in the process of being replaced for multiple SoS administrations, but that [replacement has been paused until further notice, perhaps indefinitely](https://www.sos.ca.gov/campaign-lobbying/cal-access-replacement-system-project-cars-updates/cars-news-and-updates).
