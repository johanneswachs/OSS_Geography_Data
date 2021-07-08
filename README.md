# OSS Geography Data
Data on the geography of active GitHub Contributors, by country and region.

The data consist of geographically aggregated counts of active GitHub accounts at different spatial resolutions. Each CSV has a geographic scope, either countries in the world, European NUTS2 regions, or subnational regions from the US, China, Russia, India, Japan or Brazil. 

GitHub accounts are considered active if they made at least 100 commits across 2019-2020. Accounts were geolocated via the Bing Maps API in early 2021 using data from the GitHub account location field, data from linked Twitter accounts, or email address suffixes (country resolution only), tried in that order. When applicable, the data includes counts of active GitHub accounts identified via each alternative. The data also include population estimates. 

If you use this data, please reference:

> J. Wachs, M. Nitecki, W. Schueller, A. Polleres. "The Geography of Open Source Software: Evidence from GitHub." Arxiv preprint: 2107.03200. (2021)
(https://arxiv.org/abs/2107.03200)


The geocoding pipeline is described here: https://github.com/n1tecki/Geography-of-Open-Source-Software

Notes:
- NUTS2 regions refer to the 2016 definitions.
- Within the NUTS2 file the London regions are aggregated into a single region (to be able to resolve the common location of "London").


