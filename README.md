# MotorcoachNav low clearance and weight limit data

Built 2026-10-26T20:45:22Z by the MotorcoachNav weekly data job. The MotorcoachNav app downloads
`clearances.json` (low clearances) and `weights.json` (closed and weight-limited bridges, weight-limited
roads) from here.

- 9610 inventory clearances, 29503 OpenStreetMap clearances
- Outlines: 3039 reused from last week, 0 looked up (0 found, 0 double-deck), 0 failed, 0 left for the app
- Map tiles: 105, 0 failed after splitting, 0 clearances carried over
- Weight limits: 30842 closed or load-posted inventory bridges (977 with outlines; 0 reused, 2420 looked up, 977 found, 40 failed, 28382 left for next week), 39580 OpenStreetMap limits
- Overpass: 406 requests, 142 retries
- Took 300.7 min

Sources: the Federal Highway Administration's National Bridge Inventory, published by USDOT in the National
Transportation Atlas Database, and OpenStreetMap. OpenStreetMap data © OpenStreetMap contributors, available
under the Open Database License (https://opendatacommons.org/licenses/odbl/); this file is a derived
database under the same license. No data here is guaranteed: always follow posted clearances and weight limits.