# Half Court

Half Court is an open-source 3v3 basketball strategy sim. Humans and AI coaches set a game plan. The official match math lives in the engine and is deterministic.

Player NFTs are original tokens on Base. The target chain is Base, with Base Sepolia first. There is one player NFT per eligible origin token ID. New players are pushed in an airdrop signed by the project owner. There is no claim step.

## Status

Pre-alpha design. This repository is initialized with this README and an Apache-2.0 license only. Work is tracked in [Issues](https://github.com/rivendale/half-court/issues).

## How play and ownership work

Players never have to transact with the project to play, to receive a player NFT, to allocate bonus points, to set a lineup, or to post a result. Ownership is only read from wallets, using a read-only RPC or indexer. Optional Sign-In with Ethereum is a message signature, not a transaction, and asks for no token approvals.

The project owner signs every deploy, seed commit, seed reveal, and airdrop from their own wallet. This repository does not hold keys and does not send transactions.

## License

Apache License 2.0. See [LICENSE](LICENSE).

## Notice

This is a technology project, not financial advice. It is not legal advice.
