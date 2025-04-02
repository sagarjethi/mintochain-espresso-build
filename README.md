# 🚀 MintoChain — Fully Functional Rollup with Espresso Confirmations

MintoChain is a fully deployed rollup leveraging Espresso Confirmations for enhanced decentralization and fast finality. We’re live on both the Decaf Testnet and Arbitrum Sepolia, demonstrating cross-environment resilience and scalability.

This deployment showcases MintoChain’s flexibility — whether for specialized verticals or cutting-edge rollup architecture experimentation. By integrating Espresso’s decentralized sequencing, MintoChain ensures robust and trust-minimized confirmations.
## Local Dev

```
$ docker compose up
```

If you see this error:
```
error acting as staker                   
err="error advancing stake from node 2 (hash 0xee288c5dcc61206e6868fa7a01da6abaabe22d6c849718a47eb361857b7e8dd8): error generating node action: block validation is still pending"
```
This error is expected when running a newly deployed rollup with no recent activity. It occurs because there are no new nodes to stake on or no new batches have been posted. Simply let the system continue running.
