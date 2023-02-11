# Sandbags Dev Testnet

## Links

* [Join Relay Network Dev-testnet](https://docs.sandbags.io/join-relay-network-dev-testnet/setup)
* [Stats Dashboard](https://core.dev-testnet.sandbags.io)

## Core Service

core service api url(configuration for `center.apiUrl`): https://core.dev-testnet.sandbags.io

## Scheduler

| test content | date | node version | core version | description |
| --- | --- | --- | --- | --- |
| core service | 2022-12-15 ~ 2022-12-17 | 0.1.0 | 1.0.0 | connection, logging, daemon |
| p2p network | 2022-12-18 ~ 2022-12-30 | 0.1.2 | 1.0.0 | DHT, data sync |
| node basic | 2023-01-08 ~ 2023-01-31 | 0.1.7 | 1.0.13 | version control |
| scanner & processor | 2023-01-08 ~ 2023-01-31 | 0.1.7 | 1.0.14 | data sync, error process |
| global access | 2022-12-31 ~ 2023-01-07 | 0.1.4 | 1.0.24 | (NOTE: the network may not be available at this stage) |
| global access II | 2023-01-08 ~ 2023-02-06 | - | 1.0.27 | distributed core service, data centers |
| global access III | 2023-02-07 ~ 2023-02-11 | - | 1.0.29 | horizontal scaling, data center sisaster switchover |
| bot |  |  |  | version control, data sync, conflict handling |
| utils | 2023-01-08 ~ | - | 1.0.15 | task management |
| global access IV | | | cross region file system |
