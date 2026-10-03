# Season Command Center

Season Command Center is a personal, noncommercial fantasy hockey dashboard being developed by an individual developer. It runs locally and helps one user review their own Yahoo Fantasy hockey league, compare player performance, and plan roster decisions.

This repository provides a public project description for the Yahoo Fantasy Sports API access application. The dashboard itself is private and is not offered as a public service.

## Current development

The local dashboard includes roster projections, schedule analysis, free-agent watchlists, and trade-fit analysis based on saved research and league snapshots. A read-only Yahoo connector is in development; live Yahoo API access is pending approval.

## Planned Yahoo API use

After approval, the dashboard would use Yahoo-authorized read access to retrieve:

- League settings, scoring rules, standings, and matchups.
- Teams and player rosters within the user's league.
- Player statistics, eligible positions, and league ownership or free-agent status.
- League transaction history to keep the local analysis current.

The intended audience is one user analyzing their own league. There is no planned sale, advertising, public distribution of league data, or commercial API service.

## Access and privacy

Yahoo access would use OAuth 2.0 with the user's authorization and remain limited to data available to that account. API credentials, authorization tokens, and private league snapshots would remain outside this public repository.

All lineup changes, adds, drops, and trades would be reviewed and performed manually in Yahoo Fantasy. The dashboard requests read access only.

## Attribution

When displaying Yahoo API data, the dashboard will include the attribution [Fantasy data provided by Yahoo Fantasy](https://sports.yahoo.com/fantasy/) and the required official Yahoo Fantasy branding.

This is an independent project and is not affiliated with or endorsed by Yahoo.
