# Fabriq Documentation

Fabriq is a Solana liquidity platform for pool discovery, market analytics, and LP position management.

- [Read the Fabriq docs](https://docs.fabriq.trade/)
- [Open Fabriq](https://fabriq.trade/trending)

## Preview docs changes

Run the following from this repository with Bun installed.

```sh
bunx mint@4.2.1125 dev
```

The docs navigation is defined in `docs.json`. Run `bunx mint@4.2.1125 validate` and `bunx mint@4.2.1125 broken-links` before publishing changes.

The developer guides and OpenAPI specification come from `apps/docs` in the Fabriq monorepo. This import uses revision `1881f28`. Keep developer guide links under `/developers` when syncing updates.
