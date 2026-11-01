# Quarkus architecture visualiser screenshots

Screenshots of the Dev UI architecture visualiser prototype for
[quarkusio/quarkus#57878](https://github.com/quarkusio/quarkus/issues/57878).

The prototype is on the branch
[SiteNetSoft/quarkus:dev-ui-architecture-visualiser](https://github.com/SiteNetSoft/quarkus/tree/dev-ui-architecture-visualiser).
The application is a small shop: REST, Hibernate ORM with Panache, a REST client, Kafka and the scheduler.

- `L1-context.png`: system context
- `L2-container.png`: containers
- `L3-component.png`: components
- `L3-component-selected.png`: components, with `OrderService` selected
- `L4-code.png`: code of `OrderService`

Each file also has a dark mode version (`-dark.png`).

Trace replay, from the branch
[SiteNetSoft/quarkus:dev-ui-architecture-trace-replay](https://github.com/SiteNetSoft/quarkus/tree/dev-ui-architecture-trace-replay):

- `R0-list.png`: the list of traces
- `R2-mid.png`: replay of `POST /orders`, at the call to the payment service
- `R4-consumer-mid.png`: replay of a Kafka message on the `shipments` topic
