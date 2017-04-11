# Shigoto
GenStage based worker queue with multiple backing store adapters

# Todos

## Worker

- [ ] Shigoto.Producer (Sourced from the store adapter)
- [ ] Shigoto.Consumer (ConsumerSupervisor)
- [ ] Shigoto.Processor (Task based)

## Adapters

- [ ] Erlang's :queue module with wrapper
- [ ] Redis
- [ ] Google Pub/Sub
- [ ] AWS SQS

## Configurables

- [ ] Queue peeking latency
- [ ] Queue popping latency
- [ ] Adapter Configs
- [ ] Maximum Demand (Affects number of active processors at any single point of time)
- [ ] Minumum Demand (Minimum availability before requesting for job)
