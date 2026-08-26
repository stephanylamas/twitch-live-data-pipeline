# Twitch Live Data Pipeline

An end-to-end, event-driven ELT data pipeline that ingests real-time streaming metrics from the Twitch API, stages immutable source data in Amazon S3, and builds an analytical lakehouse layer in Snowflake.

## Tech Stack & Architecture
Twitch API & Twitch EventSub -> AWS S3 -> Snowflake

## Project Status
Architecture and Data Modeling

### Twitch API Documentation
https://dev.twitch.tv/docs/api/

### Twitch EventSub Documentation
https://dev.twitch.tv/docs/eventsub/
