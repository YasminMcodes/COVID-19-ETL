# COVID-19 ETL Project

This repository contains a Python ETL (Extract, Transform, Load) script that fetches, processes, and saves historical COVID-19 confirmed cases data for Italy using the [Disease.sh API](https://disease.sh/).

## Overview

- **Extract:** Downloads Italy's COVID-19 historical confirmed cases data.
- **Transform:** Converts raw data into a clean format, calculates daily new cases, and filters out negative values.
- **Load:** Saves the transformed data as a CSV file for further analysis.

## Getting Started

### Prerequisites

- Python 3.x
- `requests` and `pandas` libraries

You can install the required Python packages using pip:

```bash
pip install requests pandas
