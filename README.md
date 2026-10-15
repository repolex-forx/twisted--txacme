# Repolex Knowledge Graph of twisted/txacme

RDF knowledge graph data for [twisted/txacme](https://github.com/twisted/txacme), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/txacme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ac18f92f6dde971a6b38f2ecfae44665815db583
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ac18f92f6dde971a6b38f2ecfae44665815db583
│           └── chunk-001.nq.gz
├── blob
│   ├── 0268996ed3b98b2c95607b0033b35a57aad44b59.nq.gz
│   ├── 076f46208b49872d0607c2261810904ae1973674.nq.gz
│   ├── 0a665d5508f8a3c088c7232bfc1ff23dd62b00e9.nq.gz
│   ├── 141ef4b3e9ae0047e82f9d0ce0a458e0fab8469e.nq.gz
│   ├── 2078d9709e46fd015f9cb22bd5bbe6fe8e0eac6e.nq.gz
│   ├── 2e063c5b52f12d0d1865654f5652c174e2503a83.nq.gz
│   ├── 34dff64261177cf085ffbe4f6b2361c044c41863.nq.gz
│   ├── 37c83c194ae709ea72437a75a3913617ac3fd875.nq.gz
│   ├── 3ad8af5b5c9f387074df58b084464ad57fbd24d9.nq.gz
│   ├── 3bd646016e0705573545282ae184809d91c71345.nq.gz
│   ├── 3d99bbe87caa24a10566b0d86156edb53be3b0ad.nq.gz
│   ├── 3e88c002e9a27bc2f66dc351a95a3ecae68e62dc.nq.gz
│   ├── 42891b95b8364b5bd9d77ac27c49aaeb786629c8.nq.gz
│   ├── 4350d52601e6fba77c19fbd9149363ea1d163bcc.nq.gz
│   ├── 46730eb45699bfffd719fd275067695e908fe0fd.nq.gz
│   ├── 4d3df0f668e1fcf9479dfd8cd32ef4d797b2886b.nq.gz
│   ├── 5443af02f6533da83e518969ec1c35a628c2717a.nq.gz
│   ├── 5a7efe6a2a50733f75cd1893633ce00270bb4357.nq.gz
│   ├── 6021505e9a7716ce9201404691c0d838d120f067.nq.gz
│   ├── 70f4046cab28b127c60c9f7f6b981cb24e5dd940.nq.gz
│   ├── 74f4e66884a4b8e791bb81ce324ac050fad29703.nq.gz
│   ├── 75ad74fdee7d7cf31a59888c760424801548184e.nq.gz
│   ├── 788bc654b1aec25c153418ed859136e990307954.nq.gz
│   ├── 7a7f319c0f1099c3e51cc123bd2d5117a4cf85cd.nq.gz
│   ├── 85d2266ae05c141b11d0863117f1397dd4f6d2ee.nq.gz
│   ├── 8e76fe5ccc1245c2da6e85cd22a52af037bfcb1e.nq.gz
│   ├── 8fd677e350755f0049584aae3b900f53d91015fa.nq.gz
│   ├── 9b03fc87c86028ae394086c60c4e96050d65c548.nq.gz
│   ├── a2b9e41093b7da26491bf8e31616770c4dcc0be9.nq.gz
│   ├── a2e77170462be8d2270fea376a24eb31ac1786fb.nq.gz
│   ├── abe1aa99bafa6156a03ddf4f0657b2e3765eb0a0.nq.gz
│   ├── b2e686e024988208621b9e9ac8114ce544e94bd6.nq.gz
│   ├── b60b9644e98399d7d445107b44f65d6ed4588c37.nq.gz
│   ├── b6db70d76f1a8dea8b664c81abe39f31681f10c8.nq.gz
│   ├── bb2fa4ecff49020c1b534c0bead8a85131bb49df.nq.gz
│   ├── c2a5e466082dad22e7e4c8bf0ed7501e348ec5ea.nq.gz
│   ├── c96ffbbad2e81c47c0608838e37735d22c83f7e5.nq.gz
│   ├── d0a293c33ee2c0f7c67066b4fc8b1443b11b1b67.nq.gz
│   ├── d340aa19cd3e11f568441a9a90308442576c5cdd.nq.gz
│   ├── d5d1c5c045e36ff140e6126cb5dbee395e89172e.nq.gz
│   ├── db304b9894d7b5374fbf9860f544fa4636454c7c.nq.gz
│   ├── dcdaa2f57572f5d401c21fe953d5949163885aba.nq.gz
│   ├── dd1ab0c2f3bdc6378b7588da8e6825c840e31377.nq.gz
│   ├── e0d300fc9b674bbf20d4df3ecf79d8247c462700.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e978bc13cbb3a9ff2946722d496b236785183ab6.nq.gz
│   ├── ecc03244b7f4514a11642149842ff7f2d0b44f65.nq.gz
│   ├── ecd8a1a8383301a04fed679d80e0770bddbb037e.nq.gz
│   ├── ef7e4721fa78d2346f543101add4a3f442b2c993.nq.gz
│   ├── f31d34bdf9c466e14ea09150f664d1f3a644d3dc.nq.gz
│   ├── f935021a8f8a7bd22f9d6703cafa5134bb6a57f8.nq.gz
│   ├── fdcc169061787fac10426711b0e9b533df048885.nq.gz
│   └── fe17e3ed0c3b10f02ff95e4aea9da6ed89efca68.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ac18f92f6dde971a6b38f2ecfae44665815db583.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[twisted/txacme](https://github.com/twisted/txacme)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
