# RaceOptiData – F1 Data Dumps (Ergast-compatible)

Since late 2024, the Ergast Motor Racing Data API is no longer updated.  
RaceOptiData aims to keep its data schema alive by providing up-to-date, downloadable dumps (MySQL + CSV) built from a custom pipeline.

The dumps follow the original Ergast structure, but are refreshed after each race using a modern data collection pipeline (Python + FastF1 + Azure).

👉 Visit https://www.raceoptidata.com for the latest version  
🗓️ Last update: post-2025 Italian Grand Prix

## What's inside

- MySQL-compatible `.sql` schema file
- Full `.csv` dumps per table
- `manifest.json` to describe the dump content and update time

## License

Distributed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), following Ergast's original license model.
