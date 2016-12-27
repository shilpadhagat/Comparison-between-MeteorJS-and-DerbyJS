# Comparison between Meteor JS and Derby JS

|`Features`|`Meteor JS`|`Derby JS`|
|------------------|-----------|-----------|
|`Databases`| Meteor supports MongoDB natively. Although future databse support is possible with FalthomDB and MySQL. Meteor supports Redis.io is also supported in beta.  | Derby supports MongoDB as well as Redis  |
|`Server side rendering`|  |   |
|`Front-End Stack`| Meteor uses three user interfaces libraries,React,Angular and it's own library Blaze. |   |
|`Underlying protocol`| Meteor uses Distributed Data Protocol (DDP) to communicate between the client and the server. It is a protocol based on JSON and maily helps in handling Remote procedure calls and managing the data.  |   |
|`Template`|   |    |
|`Latency Comparison`| Meteor comes with built-in latency compensation feature. The user actions ate instanly reflected and hence there is no need to wait for the server result. Latency compensation works only if you are doing write operations to a data store supported by Meteor (supports MongoDB and Redis). |    |
|`Browser Dependency`|     |    |
|`Performance Evaluation`|     |    |
