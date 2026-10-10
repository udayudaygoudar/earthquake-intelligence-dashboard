# Earthquake Intelligence Dashboard

An interactive earthquake dashboard that retrieves earthquake
data from the United States Geological Survey (USGS) API.

## Project Overview

This project presents earthquake information in a simple,
browser-based dashboard.

Users can filter events by date range and minimum magnitude,
view summary metrics, explore magnitude distribution, and
open individual earthquake event pages.

## Features

- Live earthquake data from the USGS API
- Date-range filtering
- Minimum-magnitude filtering
- Earthquake count and magnitude statistics
- Magnitude distribution chart
- Recent earthquake events table
- Links to official USGS event pages
- Basic API error handling

## Technologies Used

- HTML5
- CSS3
- JavaScript
- USGS FDSN Event Web Service
- GeoJSON

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Ensure that an internet connection is available.
4. Select the date range and minimum magnitude.
5. Click **Load earthquakes** to refresh the data.

## API Reference

USGS FDSN Event Web Service:

https://earthquake.usgs.gov/fdsnws/event/1/

The dashboard requests GeoJSON data using HTTP GET.
No API key is required.

## Important Limitation

Each request is limited to 100 events. Dashboard statistics
describe the returned records and may not represent every
earthquake in the selected period.

## Documentation

See `Earthquake_Dashboard_Technical_Documentation.docx`
for the technical write-up and verification notes.
