# mumbai-gtfs
This repo houses GTFS feeds built for services run by KDMT, TMT, and BEST.
### gtfs.zip
This file stores data in the original format. If a route was sent with (UP) and (DOWN) variants they are not merged with or have direction_ids.
### gtfs_compat.zip
This file stores data in the most compatible format. Routes are merged for simplicity, trips may have different stop sequences and directions. Stops and route names use Title Case when appropriate. Ideal for Passenger Information Services like [transitrouter](https://transitrouter.pages.dev), [catenary maps](https://maps.catenarymaps.org), etc.

