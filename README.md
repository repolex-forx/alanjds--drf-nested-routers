# Repolex Knowledge Graph of alanjds/drf-nested-routers

RDF knowledge graph data for [alanjds/drf-nested-routers](https://github.com/alanjds/drf-nested-routers), parsed by [repolex](https://repolex.ai).

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
rlex download alanjds/drf-nested-routers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68e5bf56c9085adef100bbbf1838dfdabb4c5f2a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 68e5bf56c9085adef100bbbf1838dfdabb4c5f2a
│           └── chunk-001.nq.gz
├── blob
│   ├── 008c3a6d980387691872f3acc3db995f1790912e.nq.gz
│   ├── 00f86187c6f1f80c4e74102a179c4136fbe0d1da.nq.gz
│   ├── 0504abba3a1bc4d90296a66753d6d818b775f276.nq.gz
│   ├── 13ad157dd0efd3696cf9e78fdc2fdcf018c8d932.nq.gz
│   ├── 19899d3e86765ff2b001e552873fafa535f58c0b.nq.gz
│   ├── 2e3b6ee49161d8cd56079e236cf721c70bd942f7.nq.gz
│   ├── 4265e496d4563224e9ca870ff8624c2d742d1dfc.nq.gz
│   ├── 444edc537dbe519aa58980020b9a8f4693a58a7d.nq.gz
│   ├── 44eb6ff648c4dd058997706a2d29708bbc432ead.nq.gz
│   ├── 5ab20e5ab537ec0970bc89629a69e43953b27317.nq.gz
│   ├── 64da9ebcc2c90c118dce3585d677c63fab21e924.nq.gz
│   ├── 68263d9474e1f186415414126e875fda106f87db.nq.gz
│   ├── 6d12cc629f4d0dcba7f69507aee831d70dd9ebe3.nq.gz
│   ├── 76d1ab497ef1a20f458a2a62c3df57f068c79bce.nq.gz
│   ├── 78a12b6caa4ec101bfce326ab801940a856f6c6b.nq.gz
│   ├── 7ed348b5cc33f9fda271060dabebcc8dd4fbb0f5.nq.gz
│   ├── 81dc926a5794eb3bc966df6555c24d5f45422a85.nq.gz
│   ├── 8409ac58b9fc61c13a929a5d83fb908cd997aa7f.nq.gz
│   ├── 98747c4f6f01643b7e44c77c4c14ff27e05279eb.nq.gz
│   ├── a335fabe4786e252857bc14fad66f133f29775ac.nq.gz
│   ├── a823680f60f79940fff52eabc39acb1ef257db18.nq.gz
│   ├── ab14558fbf2183a59db2cf7fff141e3b22b55ad2.nq.gz
│   ├── abe17d101af4f12bf618c89b83c0e8944d04bcab.nq.gz
│   ├── ac7c1da340e096f2d3332a76801672bd809647cc.nq.gz
│   ├── ad2a22be08191aa99e75dea9ef5d0f6536939ff9.nq.gz
│   ├── b0e0068769966eb732d72ce93edcf4ccf2b6ca20.nq.gz
│   ├── b248b1ecfe9b9c5938d0e481c1b4500ea64b9a1c.nq.gz
│   ├── b249f08bad2460303cddb0be89bd57079f83e8cb.nq.gz
│   ├── bb0505797778f774c8e2baa79e78ac3502638571.nq.gz
│   ├── ce2bfc8854c319adc3d2359302fcf8c8e71b9799.nq.gz
│   ├── ceb067a1e537c2763eb19babb396aa10d207d9b2.nq.gz
│   ├── d375ee9e2f40b3fbe03019990d953015363e19c8.nq.gz
│   ├── dea4d1e06df98b1306798ddc5c76451bf8712523.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e746566b96348d09ee4c33a5b3cb88858001462b.nq.gz
│   ├── e7a4801510b6b6c63e65b3c61bd3894ac3a00a90.nq.gz
│   ├── ed4ff82867ddcb30be9d4cd196e561b029628564.nq.gz
│   ├── ed593e7e385fda4d56e8d422924ae0341c7d92e6.nq.gz
│   ├── ee730834bd7c9e2b590b94c4dd41a5858da25b62.nq.gz
│   ├── eecc90cd89f3a54b8a0196ec9f38c8020a1f062e.nq.gz
│   └── f130bfab84cfe371bfe112171ca4592482b3752e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 68e5bf56c9085adef100bbbf1838dfdabb4c5f2a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[alanjds/drf-nested-routers](https://github.com/alanjds/drf-nested-routers)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
