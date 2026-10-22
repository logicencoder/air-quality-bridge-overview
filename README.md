# Slovak Air Quality Dashboard

A single pollution reading is hard to interpret without knowing the station, time and surrounding history. This dashboard brings Slovakia's monitoring-station readings into a searchable board and geographic map, helping users explore where a measurement comes from and how it has changed.

## Tech stack

| Layer | Technologies |
|---|---|
| Core stack | Python; PHP; WordPress; JavaScript; SQLite |

## Start with the current picture

The overview groups available station readings with their observation times. Quality bands help users scan the information before opening a more detailed view. Sorting, filtering and paging keep a larger monitoring network manageable.

## Find a station on the map

A geographic map uses station locations to connect readings with place. Search the station list, select an observation or use fullscreen when examining a wider area. Station context helps avoid treating one location's reading as representative of an entire region.

## Examine the pollutants

Dedicated pollutant views cover the supported particulate and gaseous measurements, including PM10, PM2.5, nitrogen dioxide, ozone and sulphur dioxide. Compact panels help compare the available readings. Units and timestamps remain part of interpreting what is being shown.

## Compare periods carefully

History and day comparisons help explore changes beyond the latest observation. Coverage information matters when looking at an average or comparing days with different amounts of data. Hourly readings should be understood as hourly observations rather than assumed to describe a complete day.

## Keep the source in view

The dashboard uses published information from the Slovak national monitoring network, SHMU. A guide and presentation preferences support using the information consistently. It provides an organised view of the observations without claiming that every place or time has complete coverage.

---

Private code: [air-quality-bridge](https://github.com/logicencoder/air-quality-bridge)

See [REPOS.md](REPOS.md) for related repositories.

**[Logic Encoder](https://logicencoder.com)** · [GitHub](https://github.com/logicencoder) · [Contact](https://logicencoder.com/contact/)
