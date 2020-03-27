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


NSDb is a **time-series** database **streaming oriented** optimized for the serving layer. It is conceived having streaming real-time analytics in mind. Besides managing time-series data, it perfectly fits the read side of Kappa Architectures or systems based on Command Query Responsibility Segregation pattern. Still, NSDB unifies the storage and retrieval of historical time-series data with real-time one. The plus is to store metrics and bind directly the incoming indexed data to the final users, thanks to pushing technologies like WebSocket.

Time series database is now the fastest growing database segment, and the interest around this technology has more than doubled in recent years. 
As the name suggests, time-series databases are designed to store data that changes with time. This can be any kind of data that was collected over time. It might be metrics collected from some systems - all trending systems are examples of the time-series data.
In a few words, Tim series data are simply measurements or events that are tracked, monitored, collected or aggregated over a period of time. So everything that can be measured in time is an example of the time-series data. Such data you can query, plot, analyze in order to find correlations between different metrics.

___

There are definite benefits to using a database designed for your time series data, but two, in particular, pop up on the radar: 


## Scalability
A time-series database focuses on a higher number of writes with eventual consistency, even across distributed storage, and this specialty implies less worry for the users that care for their data. Additionally, time-series databases manage scalability by introducing efficiencies that are only possible once you treat time as a first-class citizen. These efficiencies end in performance improvements, including higher ingest rates, faster queries at scale, and better data compression.

## Usability
Developers are increasingly adopting time-series databases and using them for a spread of use cases because of TSDBs typical functions and operations like data retention policies, continuous queries, flexible time aggregations, and so on, and these features can provide a far better user experience and simplify your life.

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

