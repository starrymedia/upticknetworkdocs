# Table of contents

* [Reference](README.md)
  * [Introduction](intro/README.md)
    * [High-level Overview](intro/overview.md)
    * [Architecture](intro/architecture.md)
    * [Clients](intro/clients.md)
    * [Use Cases](intro/use\_cases.md)
    * [resources](intro/resources.md)
  * [quickstart](quickstart/README.md)
    * [Installation](quickstart/installation.md)
    * [uptickd](quickstart/binary.md)
    * [Deterministic Builds](quickstart/reproducible-builds.md)
    * [Run a Node](quickstart/run\_node.md)
    * [Interacting with the Node](quickstart/interact\_node.md)
    * [Cosmovisor](quickstart/cosmovisor.md)
  * [Basics](basics/README.md)
    * [Chain ID](basics/chain\_id.md)
    * [Accounts](basics/accounts.md)
    * [Transaction Lifecycle](basics/transactions.md)
    * [Gas and Fees](basics/gas.md)
    * [Tokens](basics/tokens.md)
  * [Core Concepts](core/README.md)
    * [Encoding](core/encoding.md)
    * [Pending State](core/pending\_state.md)
* [Guides](guides/README.md)
  * [Localnet](guides/localnet/README.md)
    * [Single Node](guides/localnet/single\_node.md)
    * [Multi Node](guides/localnet/multi\_node.md)
    * [Testnet command](guides/localnet/testnet\_cmd.md)
  * [keys-wallets](guides/keys-wallets/README.md)
    * [keyring](guides/keys-wallets/keyring.md)
    * [MetaMask](guides/keys-wallets/metamask.md)
    * [Multisig](guides/keys-wallets/multisig.md)
    * [Keplr](guides/keys-wallets/keplr.md)
  * [Ethereum Tooling](guides/tools/README.md)
    * [Remix: Deploying a Smart Contract](guides/tools/remix.md)
    * [Hardhat: Deploying a Smart Contract](guides/tools/hardhat.md)
    * [Truffle: Deploying a Smart Contract](guides/tools/truffle.md)
  * [Validators](guides/validators/README.md)
    * [Overview](guides/validators/overview.md)
    * [Run a Validator](guides/validators/setup.md)
    * [Validator Security](guides/validators/security.md)
    * [Validator Security Checklist](guides/validators/checklist.md)
    * [Validator FAQ](guides/validators/faq.md)
    * [Disk Usage Optimization](guides/validators/disk\_optimization.md)
  * [Key Management System](guides/kms/README.md)
    * [Tendermint KMS](guides/kms/kms.md)
  * [State Sync](guides/statesync/statesync.md)
  * [Page Test](guides/page-test/README.md)
    * [testLayer2](guides/page-test/testlayer2.md)
* [api](api/README.md)
  * [JSON-RPC Server](api/json-rpc/README.md)
    * [JSON-RPC Server](api/json-rpc/server.md)
    * [Running the Server](api/json-rpc/running\_server.md)
    * [Namespaces](api/json-rpc/namespaces.md)
    * [JSON-RPC Methods](api/json-rpc/endpoints.md)
    * [events](api/json-rpc/events.md)
  * [sdk](api/sdk.md)
  * [Protobuf Documentation](api/proto-docs.md)
* [MAINNET](mainnet/README.md)
  * [Joining a Mainnet](mainnet/join.md)
  * [Block Explorers](mainnet/explorer.md)
* [TESTNET](testnet/README.md)
  * [Joining a Testnet](testnet/join.md)
  * [Testnet Faucet](testnet/faucet.md)
  * [Block Explorers](testnet/explorer.md)
  * [Deploy Node on Cloud](testnet/cloud\_providers.md)
* [Specifications](specifications/README.md)
  * [Modules](specifications/modules/README.md)
    * [\[Collection\]](<specifications/modules/collection/README (1).md>)
      * [Collection Overview](specifications/modules/collection/README.md)
      * [Messages](specifications/modules/collection/02\_messages.md)
      * [Events](specifications/modules/collection/03\_events.md)
      * [Future Improvements](specifications/modules/collection/04\_future\_improvements.md)
    * [ERC20 Overview](specifications/modules/erc20/README.md)
      * [Concepts](specifications/modules/erc20/01\_concepts.md)
      * [State](specifications/modules/erc20/02\_state.md)
      * [State Transitions](specifications/modules/erc20/03\_state\_transitions.md)
      * [Transactions](specifications/modules/erc20/04\_transactions.md)
      * [Hooks](specifications/modules/erc20/05\_hooks.md)
      * [Events](specifications/modules/erc20/06\_events.md)
      * [Parameters](specifications/modules/erc20/07\_parameters.md)
      * [Clients](specifications/modules/erc20/08\_clients.md)
* [Resources](resources/README.md)
  * [Uptick API Reference](https://pkg.go.dev/github.com/UptickNetwork/uptick)
  * [Ethermint Library API Reference](https://pkg.go.dev/github.com/tharsis/ethermint)
  * [JSON-RPC Reference](api/json-rpc/endpoints.md)
