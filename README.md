# Repolex Knowledge Graph of agronholm/cbor2

RDF knowledge graph data for [agronholm/cbor2](https://github.com/agronholm/cbor2), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/cbor2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6dc0c6b426c7407c5197fc2dc226c9dd0f27ef33
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6dc0c6b426c7407c5197fc2dc226c9dd0f27ef33
│           └── chunk-001.nq.gz
├── blob
│   ├── 086445d83b82f52f90496dfee3516adedcfbd382.nq.gz
│   ├── 1a635396c8c01dfb74654b3b7457eddb38dd5217.nq.gz
│   ├── 1c1317a4b6390494f89c4030f8bea26649a8081b.nq.gz
│   ├── 1e1c560c74cbc359354d5ec0a1e048d13d1a63ac.nq.gz
│   ├── 2677cead9e4d36b1b1546051b8b603cecc81a1f3.nq.gz
│   ├── 2f1ec11e600e7f5ddc81136726f58761b0d4a5f7.nq.gz
│   ├── 320eb4daa5602cb1d9948998ee996c3fed4dfad4.nq.gz
│   ├── 350151e2219e13b449330eff7cce75033b0da96e.nq.gz
│   ├── 35b5890e6ee3667a4fc76536cf89a5cbdad75c13.nq.gz
│   ├── 379237f0cf917ed027d82d37dd8f835a1c345e69.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3db1f2f8683dab3cf570d437b66fdbd4801381b2.nq.gz
│   ├── 3ff735f0b3796b9ea01c2b0c86587107f6857714.nq.gz
│   ├── 45a2f73673edab66a13ab5de206142341e996f10.nq.gz
│   ├── 541051b033418ac6672c96017e46990572c7f522.nq.gz
│   ├── 565288aa55228425a199bc51e47db77ab186417e.nq.gz
│   ├── 5e9bd2976a4870715352ed7b0be72f0a8fabcd5c.nq.gz
│   ├── 684bf837ae5c79c1ae46a2f4e76bc9bb31f5558f.nq.gz
│   ├── 71e96e74530751754abc2346855e6f3c998f7982.nq.gz
│   ├── 776cbb96a5618a8e1b57b2c0b5960cb2116d8fca.nq.gz
│   ├── 821e7fcf1e37bbaef851c76d2e056007e9078496.nq.gz
│   ├── 85522f29b5063a872522977dade81352abc2739a.nq.gz
│   ├── 91efd49751a0c6be85aa5e3d1d915816a642e54d.nq.gz
│   ├── 9cbd9c95e846c73d25b42a2224688f3b407c3860.nq.gz
│   ├── a64c427e125b0b2f9089a1da94f10d3ec50b4aff.nq.gz
│   ├── a9e99cf3487aa5ae358cb877fe24f32c1112141e.nq.gz
│   ├── ad7745ade1fa1cce2dc3104ac59ec83e7024e3c4.nq.gz
│   ├── af25916c55bca95f24088160f183d2761ee46163.nq.gz
│   ├── b319a8faa813506e32f6f09bcd1bdc3d06a9afb2.nq.gz
│   ├── b6e6829e7cb0e3636807855738daad951e1b0044.nq.gz
│   ├── bcdd503ab16140c2620b19e0e141ff4257d4604a.nq.gz
│   ├── bd51dd40a9303011e6ac8006e192e917528d5313.nq.gz
│   ├── befb1dbfd719e234af5cb1d8443fbba2f6746baf.nq.gz
│   ├── bf9a8c0ad42fb78cb20be5a9444b4ee6998549a4.nq.gz
│   ├── c4e5600cf2be88e33f5c7854d18037958adf67e4.nq.gz
│   ├── c6147df57cd0475e297c21370b76a9cca4ee63e2.nq.gz
│   ├── d5d6c455c965bfbace22aed58cec108c67c4f4d0.nq.gz
│   ├── ddef82027d394b9d4984149848212caa45cbf5c1.nq.gz
│   ├── e09bf6e409abe719dd8e5fa42e6bedb5c0c391c5.nq.gz
│   ├── e22a7840ff8dad6c109d82821dc933a7d44f266c.nq.gz
│   ├── e55e860488c03be6c661b1908d8872c75d12f11d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee4415dcc3b785218cba2b874cd2ee3123b9bb3a.nq.gz
│   ├── f1780c434a12df1000dcbd628f4c4648a1bdfefc.nq.gz
│   ├── f1d0daed6c4c765fa8aa054bd12b98cfe1129469.nq.gz
│   ├── f5dfb84671a67928882f33290ed90c04726deb34.nq.gz
│   ├── f813697fb2e4f1a815863b6429b407e048aa4287.nq.gz
│   └── f9e00affc9b248f81d95aa1a400c03bbcba233e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6dc0c6b426c7407c5197fc2dc226c9dd0f27ef33.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[agronholm/cbor2](https://github.com/agronholm/cbor2)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
