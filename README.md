# Shelby

I build developer tools that make compatibility failures and hidden assumptions easier to inspect. Musician, open source builder, and a believer in evidence you can rerun.

## Start here: MCP Client Lab

[Replay a captured MCP catalog](https://github.com/shelbygrayman/mcp-client-lab) through pinned SDK clients, runtime restrictions and validators. Find whether discovery fails or captured output is rejected. No model API key or running server required.

Requires Node 22+, npm and Git:

```sh
npm exec --yes --package=git+https://github.com/shelbygrayman/mcp-client-lab.git#v0.2.0 -- mcp-client-lab demo
```

**Latest local verification, 11 November 2026:** eight regression tests passed; 312/312 outcomes matched fixed expectations across thirteen synthetic fixtures. Expected rejections are included. This is synthetic replay, not production-client certification.

[Release](https://github.com/shelbygrayman/mcp-client-lab/releases/tag/v0.2.0) · [Raw evidence and limits](https://github.com/shelbygrayman/mcp-client-lab/blob/main/BENCHMARKS.md) · [Use your own capture](https://github.com/shelbygrayman/mcp-client-lab#check-your-own-catalog-and-captured-results) · [CI example](https://github.com/shelbygrayman/mcp-client-lab/blob/main/examples/consumer-ci.yml)

Want to contribute? Start with a [small, verifiable task](https://github.com/shelbygrayman/mcp-client-lab/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22), or bring a minimal synthetic capture with exact versions and a repeatable failure.

## More tools

| Project | Useful for | Try it |
| --- | --- | --- |
| [Read Before Sign](https://github.com/shelbygrayman/read-before-sign) | Explaining wallet signing requests through an offline MCP server and CLI | [Agent setup](https://github.com/shelbygrayman/read-before-sign#use-it-with-an-mcp-client) |
| [Typed Intent](https://github.com/shelbygrayman/typed-intent) | Inspecting EIP-712 data with reproducible digest comparisons | [CLI and evidence](https://github.com/shelbygrayman/typed-intent#readme) |
| [Approval Lens](https://github.com/shelbygrayman/approval-lens) | Inspecting live token approvals using a public RPC | [Browser demo](https://shelbygrayman.github.io/approval-lens/) |
| [Sourcekeep](https://github.com/shelbygrayman/sourcekeep) | Searching local documents and exporting verifiable excerpts | [Browser demo](https://shelbygrayman.github.io/sourcekeep/) |
| [Loudness Lens](https://github.com/shelbygrayman/loudness-lens) | Measuring audio loudness privately in the browser | [Browser demo](https://shelbygrayman.github.io/loudness-lens/) |

[All repositories](https://github.com/shelbygrayman?tab=repositories) include the retrieval benchmark, calldata decoder, wallet viewer and RPC comparison work.

Each repository records its own commands, measurement date and limitations. Passing tests establishes only the behavior those tests cover.

[X / @tommyblinder_](https://x.com/tommyblinder_)
