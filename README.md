# Repolex Knowledge Graph of pyusb/pyusb

RDF knowledge graph data for [pyusb/pyusb](https://github.com/pyusb/pyusb), parsed by [repolex](https://repolex.ai).

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
rlex download pyusb/pyusb
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3241c0e6a7debafd7597925e8403d9d3ea02ed93
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3241c0e6a7debafd7597925e8403d9d3ea02ed93
│           └── chunk-001.nq.gz
├── blob
│   ├── 01b9166d323f7d23048cfcd12b04a85d85bfa03e.nq.gz
│   ├── 030e79bf5f5491a22520fc44b1ebc99f9b2e3233.nq.gz
│   ├── 07867f52d682f614f3b0d5602e97216ca8e9878e.nq.gz
│   ├── 10d05a0e955f56f16ae44cd9849e30160119c145.nq.gz
│   ├── 16cf9f1f3bcf725af0885201afbd4c3d7245d6ec.nq.gz
│   ├── 1eb12b61d6707eb44d04fbeaa94c35f59532f6e0.nq.gz
│   ├── 28bbf481936321c4df4238c93643ada5e5adbf7e.nq.gz
│   ├── 303be7562ee61d16e6b422610e6260816f7340bb.nq.gz
│   ├── 31e2e5e868e1c1b8189b969cfcf7641f807500bf.nq.gz
│   ├── 3ac930745b6bb1c54524b4578d22eb5123ae896d.nq.gz
│   ├── 45d1d276bdd009206b1db9f83c8adc71d38ade85.nq.gz
│   ├── 461a7963fa59992c4c10fbebe39b60c06e6ffd2b.nq.gz
│   ├── 48647f2da87588eba5b673091d09c3d0c408b749.nq.gz
│   ├── 4bdd1216d46b7b65bb8aafc495c100d91b2cacdb.nq.gz
│   ├── 568560cc229399a287bb54c3665690bfe991a692.nq.gz
│   ├── 6181a85949d06036251e33a960dea1697dcab0d2.nq.gz
│   ├── 68695de0e13db6d9cb82746fd3349530ada4dde1.nq.gz
│   ├── 6e27202379926977f23e86bc11e8db5017cadc42.nq.gz
│   ├── 7849d842d8b045d429592334c05eda59129e6eac.nq.gz
│   ├── 79744052b3b50a5a6346800c6a78a891efa72bc5.nq.gz
│   ├── 7edceeeac7a5b2595a8095e49b6df95a92a4963d.nq.gz
│   ├── 7fde00abf6b54878f09f2170cc4926c6d47eeecf.nq.gz
│   ├── 8080ebd3d81895dfca2d47d3f42c712c5947eba7.nq.gz
│   ├── 883861988ab7065dd81c9e2424693fdb219388dd.nq.gz
│   ├── 8e727c1974de8ca162f85fd99488beb5cb542956.nq.gz
│   ├── 95c022f3896d8d9d41df336550ad8e27074325d7.nq.gz
│   ├── 9734b1f5835fd6b42ab55ba28fac0e0ad0abb43e.nq.gz
│   ├── 993b5fcf14faa9358b2e36c275e7dfeb8021b37d.nq.gz
│   ├── a19341f63adb1ccd3b09e6ffba9732f93e58c56f.nq.gz
│   ├── a9d03e8bc185ccf4f636aaac092e2fa42a0b4e2d.nq.gz
│   ├── b46f78f62e971bb991ec1b205ebf0d10097edf8e.nq.gz
│   ├── b65dc51d2da43d96b6c1e6e8882a6464b16aed48.nq.gz
│   ├── b87e4d94a4fb6506503384ce3789e82ac26701f0.nq.gz
│   ├── b9c123e3508448791bbb77c690786450144051fa.nq.gz
│   ├── bb963a18a3e09f363c9ddb0ceab68b73158b535f.nq.gz
│   ├── bd285a6621b473196e03063e45f0d2ea1e3c7f85.nq.gz
│   ├── ce6586b310f6b456523832f5792c55e3a438010b.nq.gz
│   ├── db7cc4618dcd1c1910f0d0f99a16feb27885ed4b.nq.gz
│   ├── f0a15521bd53b9b5aef00b7e3a19feecc837b77d.nq.gz
│   ├── f4949a51d71b740dfb876737becc66191888db86.nq.gz
│   ├── f4da5acd4555a4874cad3adda044d2b4547dde4a.nq.gz
│   ├── f83eca5543538851cf326f34373411df0f87593d.nq.gz
│   └── ff21b1ba41e180d2e22fae42b4e4ca60984284e3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3241c0e6a7debafd7597925e8403d9d3ea02ed93.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[pyusb/pyusb](https://github.com/pyusb/pyusb)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
