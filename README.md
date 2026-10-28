# Repolex Knowledge Graph of PennyLaneAI/pennylane-orquestra

RDF knowledge graph data for [PennyLaneAI/pennylane-orquestra](https://github.com/PennyLaneAI/pennylane-orquestra), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download PennyLaneAI/pennylane-orquestra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a3d204bdfaa80e8bb278505a09d9d3855b192b1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6a3d204bdfaa80e8bb278505a09d9d3855b192b1
│           └── chunk-001.nq.gz
├── blob
│   ├── 08a3c1ed776295e0d5ff8ee12886890fb4c61c0d.nq.gz
│   ├── 0a892ab2df26d6187332689c32f135aac8fbb2a1.nq.gz
│   ├── 0ea45f9eb0fbef165dc16878d5a80fe74f8d5c6d.nq.gz
│   ├── 10bd335a4522daf891e05f12f05910ad58a69d91.nq.gz
│   ├── 1361bcc3d27eec80bd9fa99db0d26fd9d10f93e8.nq.gz
│   ├── 13698f0835fbb4ec40782ad7c18d3766ffc8459c.nq.gz
│   ├── 13ca714ab6d29593ff3cd814d1e1c93f6605b5bc.nq.gz
│   ├── 1685aa7799b6392bc1411307eb244a71d9ba35a7.nq.gz
│   ├── 1ebd7685f5d6ecc33fdcb7d5c502330d30b4f463.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 283e8226c32768989d4a2573368b964c0fc41293.nq.gz
│   ├── 2acaea2a4e4ccc780c7a484ebb4e2f1e7989ccbf.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 30e7cc503d2504482498cbb4c4811f81528e2301.nq.gz
│   ├── 3ac200d50fb5a7982a90ad176c507ddec1ffeae1.nq.gz
│   ├── 45e731c3d9e6a6254a11ab91b2a5d9d85b8266a8.nq.gz
│   ├── 47b08347a45787d27184c92c6b1ff995f409b20a.nq.gz
│   ├── 48b34502316a0504475f76060c853d08d1a9b53e.nq.gz
│   ├── 493755029e9942e734f9b430cc2bdd9c6dfbc149.nq.gz
│   ├── 4a8db3096af2ea1286032c46124bf9a57e85c7f1.nq.gz
│   ├── 5aaaedb336ee2a532f590132e39bd7d8505f53cb.nq.gz
│   ├── 5b535439c0f275b14690a7f4e5c5b59a33866727.nq.gz
│   ├── 6057cc3e968683d0b50e1e4592fc7cad5d590bf1.nq.gz
│   ├── 61e2fd85046e8c5ccb25b7cc6d406086a59bcada.nq.gz
│   ├── 6f9e005b8c172b734d433f5eb753ec45a8206de5.nq.gz
│   ├── 71d9551f321a5532392e2eec33f609df448979a4.nq.gz
│   ├── 734dc40efffbdeae9dd2e9f1856ec4d32812535f.nq.gz
│   ├── 761eaf49f6825ecaffb300c93a0cdad1f464e394.nq.gz
│   ├── 765ff50980f277b59f57117fa084c72ba39c46bb.nq.gz
│   ├── 7b0ba1e9562961f3bd8163b0532b87efa9ae735c.nq.gz
│   ├── 85b9011f7573b2df1eb0f7de09bac10b57ee5c4c.nq.gz
│   ├── 88ac4e4b877cb6622894aeb38a141e6fe1f1690a.nq.gz
│   ├── 941f4f561f8ddb1fc1d5e0a6d139f247b6aa9153.nq.gz
│   ├── 946381b812a3e96cf28fefeedf6c440ffc57f659.nq.gz
│   ├── 9eb590ec6865bae76036d34f67dc66bbe531aa09.nq.gz
│   ├── a1be2ef8c61f0b5853d8ec1cb84af71f98cec093.nq.gz
│   ├── a95015b9257619688ac9e25de3342616ffa7dc19.nq.gz
│   ├── aa19efecc6af9804aaae9f03253c8c61681638fb.nq.gz
│   ├── adce1a285c3b209d566df8505c7166382c5e8eb4.nq.gz
│   ├── b3dbe8137a59a76a36290819217d7d08bb6edc0d.nq.gz
│   ├── b69348d97da3e161718a410312935f4746b6cb54.nq.gz
│   ├── b72240f9968a177ab4b226268c4b248fec555a40.nq.gz
│   ├── be6796221961e20fc2dae07ffff69d3d3a0f7183.nq.gz
│   ├── c1abf5ce880a2cf740a44abc033326098d8524f3.nq.gz
│   ├── c93f99273f4021a99e2179750d5d39852a6e33d7.nq.gz
│   ├── c94daf3bce26000c3bab406eb63d56e74751aba7.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── d0f491b283ae410535315592a0efd6bd2afe9425.nq.gz
│   ├── d8466c93cec3f733563f493ec244df7aea8bcf9d.nq.gz
│   ├── d962c547dc6bd13b11e68421a1f6d177d31ba1ef.nq.gz
│   ├── d9a259015802350bb2e9b9ea963b8b95cc1d61f8.nq.gz
│   ├── d9d9fb92e65be93d98da6e7538c6c16f44d0c7ca.nq.gz
│   ├── da55fc50ab854a236ac9c71a7bb395aa9db8f2c9.nq.gz
│   ├── e7ad9aaf525a7595def3d8a6230a1d2efee9efad.nq.gz
│   ├── eaacdf3086ad51085b5e7a0dbaa927a1e33d1355.nq.gz
│   ├── f67bec815653a41d9d6bb7cda75b00f728640fe0.nq.gz
│   └── f9f79bdf9d4895ba76bcaef7a7d59d1ac1f0b67a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6a3d204bdfaa80e8bb278505a09d9d3855b192b1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 65 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[PennyLaneAI/pennylane-orquestra](https://github.com/PennyLaneAI/pennylane-orquestra)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
