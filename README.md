# Global Time Zone Converter

A simple, reliable, and powerful time zone converter built with a focus on long-term stability and ease of use.

---

## Live Demos

- [**Global Time Zone Converter Pro**](https://gripper36.github.io/Global-Time-Zone-Converter/pro_version.html)
- [**Classic Version**](https://gripper36.github.io/Global-Time-Zone-Converter/classic_version.html)

---

### Core Benefits

This project was designed from the ground up to be a completely self-contained and highly reliable tool. Instead of relying on external APIs that can break or require subscriptions, it uses a large, curated JavaScript database of cities. This ensures maximum simplicity for the user—no API keys, no sign-ups, and no complex setup are required. The application works offline and is guaranteed to function reliably for years to come.

## Features (Pro Version)

- **Dual/Triple City Mode:** Compare two or three time zones simultaneously.
- **Analog & Digital Clocks:** A clean visual representation for each selected city.
- **Time Explorer:** Use an interactive slider to scrub forwards and backwards in time and see the corresponding time changes in all locations.
- **Business Hours Indicator:** A simple color-coded system (blue for business hours, grey for outside hours) to help with scheduling.
- **Comprehensive Search:** A fast, responsive search powered by the built-in city database.

## Technical Design

- **Two-File Solution:** The entire Pro application consists of just two files: `pro_version.html` for the interface and logic, and `city_database.js` for the data.
- **No External Dependencies:** Built with vanilla JavaScript, HTML, and CSS. It requires no frameworks, libraries, or build steps.
- **IANA Timezones:** Uses the industry-standard IANA timezone database (e.g., `America/New_York`, `Australia/Sydney`) to ensure Daylight Saving Time is handled automatically and accurately.

## Running Locally

1. Download the `pro_version.html` and `city_database.js` files.
2. Place them in the same folder.
3. Open `pro_version.html` in your web browser.

## Future Work

The primary focus for future updates is to continue expanding the `city_database.js` file with more cities, airports, and universities to make the search even more comprehensive.
