<h1 align="center"> State-Sync Peer for Shentu. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
53e4af0f8edf9c457dd04ecd737dfcf246119cbf@94.16.123.116:26646
```
To add the peer, you can use the following instructions:
```
PEERS=53e4af0f8edf9c457dd04ecd737dfcf246119cbf@94.16.123.116:26646
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.shentu/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .shentu/config/config.toml
```
Add the peer YTWOFUND to the "persistent_peers" line.
