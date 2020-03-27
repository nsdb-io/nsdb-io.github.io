---
layout: pages
title: NSDB Natural Series Database
subtitle: Scalable, high-performance, open source Time series Database for real-time analytics
module-title: Module Row Title
title-short: Short Title
txt-short: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet dui diam. Vestibulum rhoncus posuere tellus, bibendum euismod diam ultricies ut.
button-txt: Tech documentation
button-link: https://github.com/radicalbit/NSDb
---

[![Build Status](https://travis-ci.org/radicalbit/NSDb.svg)](https://travis-ci.org/radicalbit/NSDb)
[![codecov](https://codecov.io/github/radicalbit/NSDb/coverage.svg?branch=master)](https://codecov.io/github/radicalbit/NSDb?branch=master)
[![License](https://img.shields.io/github/license/radicalbit/NSDb.svg)](LICENSE)


NSDb is a **time-series** database **streaming oriented** optimized for the serving layer. It is conceived having streaming real-time analytics in mind. Besides managing time-series data, it perfectly fits the read side of Kappa Architectures or systems based on Command Query Responsibility Segregation pattern. Still, NSDB unifies the storage and retrieval of historical time-series data with real-time one. The plus is to store metrics and bind directly the incoming indexed data to the final users, thanks to pushing technologies like WebSocket.

___
## License
NSDb is distributed under the [Apache 2](http://www.apache.org/licenses/LICENSE-2.0) license.

## Main Features

* Optimized time series management
* Focus on read performance [(doc)](docs/Architecture.md)
* High availability and clustering [(doc)](docs/Architecture.md)
* Ad-hoc publish-subscribe streaming feature (using WebSockets) [(doc)](docs/Websocket.md)
* SQL like query language [(doc)](docs/SQL_doc.md)
* Fluent Java / Scala Api [(doc)](docs/JVM_API_doc.md)

