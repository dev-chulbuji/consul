# consul

- consul use `Gossip protocol` to manage membership & broadcast message to cluster
- `consul members` cmd runs against the Consul client
	- Consul client gets its information via `Gossip protocol`
- if u want to get strongly consistent view of the world, query to Consul server via `HTTP API` or use the `DNS interface` to discover the nodes

