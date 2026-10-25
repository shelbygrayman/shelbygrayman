# Shelby

Artist & musician building open-source Web3 tools and private browser AI.

I like small tools that explain what they do, keep their limits visible, and give other people a way to check the results.

## Built to inspect, verify and reproduce

| Project | What it does | Try it |
| --- | --- | --- |
| [Sourcekeep](https://github.com/shelbygrayman/sourcekeep) | Search text and Markdown locally, keep exact excerpts, export verifiable evidence. | [Browser demo](https://shelbygrayman.github.io/sourcekeep/) |
| [EVM Wallet Lens](https://github.com/shelbygrayman/evm-wallet-lens) | Inspect native and ERC-20 balances across EVM networks without connecting a wallet. | [Browser demo](https://shelbygrayman.github.io/evm-wallet-lens/) |
| [Calldata Lens](https://github.com/shelbygrayman/calldata-lens) | Decode common token calls offline with exact amounts and clear approval explanations. | [Browser demo](https://shelbygrayman.github.io/calldata-lens/) |
| [RPC Crucible](https://github.com/shelbygrayman/rpc-crucible) | Compare pinned-block RPC responses, preserve failures, replay captured evidence. | [Validation guide](https://github.com/shelbygrayman/rpc-crucible/blob/main/BENCHMARKS.md) |
| [EvidenceBench](https://github.com/shelbygrayman/evidencebench) | Measure retrieval on external data and verify returned passage hashes and offsets. | [Protocol and results](https://github.com/shelbygrayman/evidencebench#first-measured-run) |

## How I build

- Reproducible commands, readable code, and automated regression checks.
- Raw benchmark results with the data, settings and limitations alongside them.
- Useful tools before broad claims. Passing tests does not mean zero bugs, and an intact excerpt does not establish truth.

Latest validation, **25 October 2026**: the four existing projects passed 74 regression tests. EvidenceBench passed 10 additional tests and evaluated all 300 BEIR SciFact test queries over 5,183 documents. Each repository records its own validation scope; this is a dated snapshot, not a permanent uptime guarantee.

Currently exploring: better retrieval evaluation, private browser search, and evidence that others can reproduce.

[X / @tommyblinder_](https://x.com/tommyblinder_)
