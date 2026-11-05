# NavbatGo

**NavbatGo** is an early-stage web prototype for discovering local service providers and exploring future appointment-booking workflows in Uzbekistan.

The project aims to make it easier for people to find professionals in one place and, over time, help independent service providers establish a more accessible digital presence.

> **Project status:** Public front-end prototype. NavbatGo is not yet a production service or a working booking platform. The current interface includes demonstration data and simulated interactions.

## The problem

People looking for services such as healthcare, tutoring, vehicle repair, beauty, and home maintenance may need to search across several unrelated channels. Small and independent providers can also find it difficult to be discovered online.

NavbatGo explores a unified, Uzbek-language experience for service discovery and, in future versions, appointment scheduling.

## What is available today

The current prototype includes:

- A responsive landing page in Uzbek.
- Twelve visual service categories.
- An interactive map centered on Tashkent, built with Leaflet and OpenStreetMap tiles.
- Demonstration service-provider listings and map markers.
- A service-provider registration form **for interface demonstration only**.

**Please note:** The service providers and map markers in the prototype are sample data. Search, account sign-in, appointment booking, actual provider registration, payment processing, and persistent storage are **not implemented**. The registration form currently shows a simulated confirmation; it does not send an application to a server. App Store and Google Play buttons are presentation elements, not links to published mobile apps.

## Technology

This version is a static HTML page using:

- HTML, CSS, and vanilla JavaScript
- Tailwind CSS via CDN
- Leaflet and OpenStreetMap
- Font Awesome icons
- Google Fonts

There is currently no backend, database, build pipeline, or package registry release.

## Run the prototype

1. Download or clone this repository:
   ```bash
   git clone https://github.com/fsaidov03/navbatgo-app.git
   cd navbatgo-app
   ```
2. Open `index.html` in a modern web browser.

The page loads several libraries, fonts, and map tiles from third-party services, so an internet connection is required for the complete experience.

## Development roadmap

These are **planned features**, not existing functionality:

- [ ] Improve and validate the HTML structure and accessibility.
- [ ] Add functional search and location-based filtering.
- [ ] Build a backend API and persistent database.
- [ ] Implement customer and service-provider accounts.
- [ ] Add verified provider profiles and availability management.
- [ ] Implement appointment booking and cancellation.
- [ ] Add security checks, automated tests, and continuous integration.
- [ ] Improve documentation and define a contributor workflow.
- [ ] Expand language support based on community needs.

## Collaboration

NavbatGo is at an early stage. Feedback, issue reports, and technical suggestions are welcome. Please open a GitHub issue to discuss a problem or proposal before undertaking a large change.

NavbatGo is licensed under the [MIT License](LICENSE) (Copyright © 2026 Farrukh Saidov). A formal contribution guide has not yet been added; please open an issue before proposing substantial changes.

## Project owner

Maintained by [Farrukh Saidov](https://github.com/fsaidov03), based in Tashkent, Uzbekistan.

The project is intended to grow through responsible development, clear documentation, and future community participation.
