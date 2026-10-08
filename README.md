# European Ports Analytics

## Overview

This project analyzes European maritime transport and port activity using official Eurostat datasets.

The goal is to build a complete data analytics workflow, including data profiling and cleaning in PostgreSQL, dimensional modeling, exploratory data analysis in Python, Snowflake, and the development of an interactive Power BI dashboard.

## Data Sources

The project uses Eurostat Maritime Transport datasets:

- `mar_mg_aa_pwhd` — Gross weight of goods handled by port and direction
- `mar_mg_am_pwhc` — Gross weight of goods handled by port and cargo type
- `mar_mg_am_pvh` — Container traffic in TEUs by port
- `mar_mt_am_csvi` — Vessel traffic by vessel type

Raw data files are not included in the repository and are excluded from version control through `.gitignore`.

## Project Structure

- `data/` — local raw data files
- `docs/` — project documentation
- `images/` — charts and screenshots
- `notebooks/` — exploratory analysis and validation
- `powerbi/` — Power BI files
- `sql/` — SQL scripts
- `src/` — reusable Python code

## Status

Project in progress.