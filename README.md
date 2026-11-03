# Shelby

Musician building small tools that read things before you trust them.

Wallet requests, token approvals, master files, search results. Each tool shows what it checked, what it could not, and gives you a way to verify it yourself.

## Read before you sign

| Project | What it does | Try it |
| --- | --- | --- |
| [Read Before Sign](https://github.com/shelbygrayman/read-before-sign) | MCP server and CLI. Your AI agent explains any wallet request in plain English before you sign: unlimited approvals, Permit2, NFT operators, opaque signatures. | [Add to your agent](https://github.com/shelbygrayman/read-before-sign#use-it-with-an-mcp-client) |
| [Approval Lens](https://github.com/shelbygrayman/approval-lens) | Find every live token approval on a wallet with only a public RPC, and get the exact request to revoke it. | [Browser demo](https://shelbygrayman.github.io/approval-lens/) |
| [Calldata Lens](https://github.com/shelbygrayman/calldata-lens) | Decode common token calls offline with exact amounts and clear approval explanations. | [Browser demo](https://shelbygrayman.github.io/calldata-lens/) |
| [Typed Intent](https://github.com/shelbygrayman/typed-intent) | Inspect EIP-712 typed data offline with reproducible digests and ERC-2612 permit explanations. | [CLI](https://github.com/shelbygrayman/typed-intent#readme) |
| [EVM Wallet Lens](https://github.com/shelbygrayman/evm-wallet-lens) | Inspect native and ERC-20 balances across EVM networks without connecting a wallet. | [Browser demo](https://shelbygrayman.github.io/evm-wallet-lens/) |
| [RPC Crucible](https://github.com/shelbygrayman/rpc-crucible) | Compare pinned-block RPC responses, preserve failures, replay captured evidence. | [Validation guide](https://github.com/shelbygrayman/rpc-crucible/blob/main/BENCHMARKS.md) |

## For musicians

| Project | What it does | Try it |
| --- | --- | --- |
| [Loudness Lens](https://github.com/shelbygrayman/loudness-lens) | Check a master's loudness, true peak and loudness range in the browser, and see what Spotify, Apple Music and YouTube will do to it. Audio never leaves the tab. | [Browser demo](https://shelbygrayman.github.io/loudness-lens/) |

## Search you can check

| Project | What it does | Try it |
| --- | --- | --- |
| [Sourcekeep](https://github.com/shelbygrayman/sourcekeep) | Search text and Markdown locally, keep exact excerpts, export verifiable evidence. | [Browser demo](https://shelbygrayman.github.io/sourcekeep/) |
| [EvidenceBench](https://github.com/shelbygrayman/evidencebench) | Measure retrieval on external data and verify returned passage hashes and offsets. | [Protocol and results](https://github.com/shelbygrayman/evidencebench#first-measured-run) |

## How I build

- Reproducible commands, readable code, and automated regression checks.
- Raw benchmark results with the data, settings and limitations alongside them.
- Useful tools before broad claims. Passing tests does not mean zero bugs, and an intact excerpt does not establish truth.

Latest validation, **3 November 2026**: Read Before Sign, Approval Lens and Loudness Lens passed 64 tests, including a session with the official MCP TypeScript SDK client and the EBU Tech 3341 and 3342 loudness cases. Loudness Lens matches ffmpeg's ebur128 to 0.1 LU on every benchmark case. Calldata Lens (16 tests) and Typed Intent (9 tests) were re-run the same day.

Earlier snapshot, 25 October 2026: four projects passed 74 regression tests; EvidenceBench passed 10 more and evaluated all 300 BEIR SciFact test queries over 5,183 documents. Each repository records its own validation scope; these are dated snapshots, not uptime guarantees.

Currently exploring: giving AI agents a read-before-you-sign habit, honest metering for musicians, and private browser search.

[X / @tommyblinder_](https://x.com/tommyblinder_)
