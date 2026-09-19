# Formula 1

Everything for the upcoming Grand Prix at a glance: weekend schedule in your own timezone, the circuit layout and the current standings. After qualifying the starting grid takes over.

<a href="https://trmnl.com/recipes/251959"><img width="150" alt="Works with TRMNL" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" /></a>

## Features
- Session schedule (practice, sprint, qualifying, race) in local time, with live and done states
- Circuit map, round, location and a race-day countdown
- Driver and constructor standings, or the starting grid after qualifying
- Sprint weekends supported

## Settings
- **Time format:** 24h or 12h

Data from the [Jolpica F1 API](https://github.com/jolpica/jolpica-f1) (Ergast successor). Results can take a while to appear after a session.

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Questions or ideas? trmnl@achtnegen.nl or @Bastronautica on Discord.
