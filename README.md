# Repolex Knowledge Graph of block/ln-invoice

RDF knowledge graph data for [block/ln-invoice](https://github.com/block/ln-invoice), parsed by [repolex](https://repolex.ai).

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
rlex download block/ln-invoice
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a9b2468b2c0969855ad3a9aa4d26981102b6a99
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1a9b2468b2c0969855ad3a9aa4d26981102b6a99.nq.gz
│   └── repolex
│       └── 1a9b2468b2c0969855ad3a9aa4d26981102b6a99
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a91af21fd9f0c3d0daca9510799e79592b5fb64.nq.gz
│   ├── 10452cd43ba45cd1227c6e02a2fd0748062eb223.nq.gz
│   ├── 12096b5429b6d0020f982478a6b374cd2bdab054.nq.gz
│   ├── 14ef14e49f04976b575f4a984d235defbe9e3741.nq.gz
│   ├── 16cf3a0daed753634c0b201afc0b2c27d1e4d395.nq.gz
│   ├── 17927dce225f1eccb055c308c1373213a10da301.nq.gz
│   ├── 1fc0b340c35c6cebbd677d7d9d782461c2f25929.nq.gz
│   ├── 20cfe59082d80a5626254945399ee775a25dd48d.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2c1f94a074774dacc3e1cc7cd02c9e19f1d3abf9.nq.gz
│   ├── 3760a6a9ee1c109638e9098eba5b5ea844d61ea6.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 40b138d67db6034197dfb3d71e89661fef29c46a.nq.gz
│   ├── 46f763d46a36334a00e4c5d8bd43226f19ecb864.nq.gz
│   ├── 4c41e8df87d1c333325aacc3d46d1b0529e72ee3.nq.gz
│   ├── 54dc6705c5894641dc912f6e4f608fb0ccbebb3a.nq.gz
│   ├── 581a4f5978403e84bccaf1b79f674470fbfcc07b.nq.gz
│   ├── 5bdc8529660d9fc85161e001a4a3808bc4c66ef5.nq.gz
│   ├── 670a7578994ee1f4dfb366a9299b1d5c00b903b2.nq.gz
│   ├── 7272ff7a8580e4e901832a016318f05ae0d8bd62.nq.gz
│   ├── 79e5ee62572ac260b5164c7cf68c6595fe07737b.nq.gz
│   ├── 7b298039bcc5ab7afb476b92b1bf3970c4d36733.nq.gz
│   ├── 7fef769248e85eab6c828b9f2f7b802296cddadc.nq.gz
│   ├── 927902b355dc3f16bb1dbee5800e4b23adeeece8.nq.gz
│   ├── 9a08009bacccbe18bc769abfbfd7ceabf3e05a0c.nq.gz
│   ├── 9b353494b9affa9873676a82eda20a00e53df08f.nq.gz
│   ├── a4a00765f5ce361f2316e6b21aafa4035b6f9f73.nq.gz
│   ├── a553bee03ba2486a7edb59281d35aec1fc0df3eb.nq.gz
│   ├── a8aacfc9dc697287a41dd17938de54438383f546.nq.gz
│   ├── abae0b663fc774d6c1e33b8dd35b588467df5fe5.nq.gz
│   ├── b2704cae2aaa0b8d79d2c787c18161a2fea96eaa.nq.gz
│   ├── b453732bd8350e49d6978de0da967805d5c5cc0c.nq.gz
│   ├── bd13c859ba57eb398bd853c1e09b38c6159f9d41.nq.gz
│   ├── cb7e599d61a53f5384f9d9ae5293b7d94a8d28b0.nq.gz
│   ├── d349b6addb873951ca664dfff63747fb59f60cda.nq.gz
│   ├── dbfa7d9acfe1728cd09a1d544b2b5026a945a226.nq.gz
│   ├── e2720671ae9d57792cc4fd01df6de9b20f35da5e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── f2278332e28c51dc2fefc258881c1afb8f87fde0.nq.gz
│   └── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1a9b2468b2c0969855ad3a9aa4d26981102b6a99.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 50 files
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

[block/ln-invoice](https://github.com/block/ln-invoice)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
