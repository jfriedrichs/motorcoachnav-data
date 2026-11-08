# MotorcoachNav low clearance and weight limit data

Built 2026-11-08T18:48:44Z by the MotorcoachNav weekly data job. The MotorcoachNav app downloads
`clearances.json` (low clearances) and `weights.json` (closed and weight-limited bridges, weight-limited
roads) from here, or the same split by state in `states/` (`clearances-MN.json`, `weights-MN.json`, with
sizes in `states/index.json`), each holding everything in the state or within 2 km of it.

- 9610 inventory clearances, 29645 OpenStreetMap clearances
- Outlines: 3039 reused from last week, 0 looked up (0 found, 0 double-deck), 0 failed, 0 left for the app
- Map tiles: 105, 0 failed after splitting, 0 clearances carried over
- Weight limits: 30842 closed or load-posted inventory bridges (3810 with outlines; 6500 reused, 3580 looked up, 1418 found, 0 failed, 20762 left for next week), 39611 OpenStreetMap limits
- Overpass: 417 requests, 97 retries
- Took 300.3 min

Sources: the Federal Highway Administration's National Bridge Inventory, published by USDOT in the National
Transportation Atlas Database, and OpenStreetMap. OpenStreetMap data © OpenStreetMap contributors, available
under the Open Database License (https://opendatacommons.org/licenses/odbl/); this file is a derived
database under the same license. No data here is guaranteed: always follow posted clearances and weight limits.