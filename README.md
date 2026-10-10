# Repolex Knowledge Graph of jazzband/django-fsm-log

RDF knowledge graph data for [jazzband/django-fsm-log](https://github.com/jazzband/django-fsm-log), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-fsm-log
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 27d6437d089a271c82497c2b8d751244edad090f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 27d6437d089a271c82497c2b8d751244edad090f
│           └── chunk-001.nq.gz
├── blob
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 1373fcb739cf4b771fce6bd297d26aa7f8e33232.nq.gz
│   ├── 144593a209a3cfc7b340e8994c5496a82de17691.nq.gz
│   ├── 144df7719e82ebe77e5ca90df6cacf93b36e3cf7.nq.gz
│   ├── 153be5e2f6f996741b53558d8bc7825ec091699c.nq.gz
│   ├── 1878b1024e5d2b4eb3ae9f0488af6a33d0430f05.nq.gz
│   ├── 21f9260ffc88f9d052219e0d72e58f7295ae41e4.nq.gz
│   ├── 2767027099aa78183598149a5dad47b833eff3a8.nq.gz
│   ├── 32d4d151daf8c53242e5af953cb294f7d3e38913.nq.gz
│   ├── 33f107a0560a8f3c485795e5907300da59d4f3f4.nq.gz
│   ├── 36f19b2c74d5056b307e2bbfa00e787145e2cf24.nq.gz
│   ├── 3ab2de0b04aefebe00c132a8149f31b3006c5a97.nq.gz
│   ├── 4e3ddd1a22ede87b5f74eba34ec198558f4978b0.nq.gz
│   ├── 5e32986335b1bba7f1fc1f2cee2046b8dfb82561.nq.gz
│   ├── 5e6527543e0b5461f987273f27577174f06f201b.nq.gz
│   ├── 648e36332add911a915cd13b99630eb74de35431.nq.gz
│   ├── 65a9660687640a9fc3a07717568a834cc6ceacae.nq.gz
│   ├── 725d54a2dc7f0767ec43c6cbd38caeb99463a08b.nq.gz
│   ├── 793598a397b155b83e11211783eab0d798ec5c91.nq.gz
│   ├── 7f34ed5cb1e4773964023dac8634b7445787528e.nq.gz
│   ├── 8b0f6c3427b57f5c17ca8cb94f179c3bd45cad13.nq.gz
│   ├── 933e877ad9e403269d386f864f3f6f88355ee67f.nq.gz
│   ├── 9341e13667a3dcd958bef2bf1de0e40cb13f0a82.nq.gz
│   ├── 9e240ace577a8cc0a3c4b224e1573a6c39b0bcaa.nq.gz
│   ├── 9fdc83d139986d0efbf0919fa68a255df6b7d31f.nq.gz
│   ├── a11baa6600b4f9dabe7f3f3b838b35ae49850e33.nq.gz
│   ├── a293ee11c1df97e30657208bd328458b489f5ce5.nq.gz
│   ├── aab0a5ae7886569c0ac5c057e3e82a796aab6d72.nq.gz
│   ├── aec8fd539423b9fdfb58a03001a485f7960ee102.nq.gz
│   ├── aed855749cf01ca1ebff0181589d4f31a3308555.nq.gz
│   ├── af9a5d81c4366b3a442918ef22f7db1e7c241008.nq.gz
│   ├── b0b3c25050c83e830ce3105714ea2e15a95856a0.nq.gz
│   ├── d395616574b0bbc0a59f458c6b43611ea2289e7e.nq.gz
│   ├── d3fd0573214e3ea298f15f7b5abdbfea5dc11c0f.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d89b4b3f6a85eae7a7a90dd9691921531a5d53.nq.gz
│   ├── e9991459385d801b23310bb97aad95affc0fd680.nq.gz
│   ├── ed0ca7f357acbaf8f86ea97309baab0f7ced8b18.nq.gz
│   ├── edc2b3729c0d9dfb45c8a592b03ec5a2da0d6701.nq.gz
│   └── fe4dfeb3e03adcc508a69cda64106485c5ef22fd.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 27d6437d089a271c82497c2b8d751244edad090f.nq.gz
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

[jazzband/django-fsm-log](https://github.com/jazzband/django-fsm-log)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
