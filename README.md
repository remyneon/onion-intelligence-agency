# The Onion Intelligence Agency

Welcome to OIA Headquarters (:

This project aims to compile the most complete possible
* catalogue of onion URLs, past and present
* archival of onion sites
* hashed blacklist of potential CSAM onions
* OSINT and statistical analysis opportunities for onion sites

Is measuring completeness even possible?
- No, given the nature of tor sites, probably not.

By collecting and combining information from a huge number of sources, however, I believe the finished project will be the most comprehensive publicly available dataset.

## Stages/todo

1. Link and blacklist collection
- Gathering of onion links from (many!) various current and historical sources
- Gathering of onion blacklists from available sources such as https://ahmia.fi/blacklist/

2. Ingestion
- Scrapes of link sources -> database

3. Content collection and categorisation
- Full source code (text-only) scrapes of current onion sites and archival material wherever possible
- Blacklisting of all pornographic URLS to ensure no potential CSAM sites are included in link collection
- Site categorisation and collation

## Analytics

There are many possible data-points of interest:
* Number of phishing links per DarkNet Market (DNM) or other onion service
* Site obscurity based on occurence in link sources
* Email address and crypto-wallet scrapes
* Prevalence of Javascript required sites, and detection of malicious code
* Much more to come!
