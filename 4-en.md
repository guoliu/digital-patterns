# Replaceable middlemen

In any decentralized networks, we still rely on servers that act as middlemen, to keep our data online and to listen to incoming messages. The reliance of the network, and the level of ownership it provides its users, are therefore determined by how easy it is to replace such middlemen.

# Example

- In p2p networks such as BitTorrent and IPFS, the bootstrap nodes that provide initial entry points to the network can be easily replaced, and the machines that serve content (seeding or pinning) are also easily replaceable by both content consumer and publisher.
- In Nostr, each user can use multiple [relay servers](https://nostr.com/relays). Clients verify the digital signature of users and depend very little on the guarantee of the relay servers, making them easily replaceable.
- One limitation of ActivityPub, especially in the implementation of Mastodon, is that user identity is tied to a particular instance where the users' data is also stored. Although it is possible to migrate to a different instance, this obstacle weakens censorship resistance and limits data ownership on ActivityPub.
