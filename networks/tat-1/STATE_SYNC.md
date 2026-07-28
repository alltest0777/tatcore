# TatCoin State Sync

## Enable State Sync

Edit:

```text
~/.tatcore/config/config.toml
```

Find:

```toml
[state-sync]
```

Configure:

```toml
enable = true

rpc_servers = "http://84.8.220.64:26657,http://84.8.220.64:26657"

trust_height = 107672

trust_hash = "4DAFE8F92A2DFF935D4B1A6B79F79AE2208AC8F2D15AF1FC440638C9EEB69FDB"

trust_period = "168h0m0s"
```

## Reset Node

```bash
tatcoind tendermint unsafe-reset-all --home ~/.tatcore
```

## Start Node

```bash
sudo systemctl restart tatcoind
```

## Notes

The values of `trust_height` and `trust_hash` become outdated over time.

Before joining the network, obtain fresh values from a trusted TatCoin RPC endpoint.

Future versions of the TatCoin documentation will provide an automated script to retrieve these values.
