# Repolex Knowledge Graph of samuelcolvin/python-devtools

RDF knowledge graph data for [samuelcolvin/python-devtools](https://github.com/samuelcolvin/python-devtools), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/python-devtools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5022f1f6f1c55d871b1db208c9c1b2ab0df488fe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5022f1f6f1c55d871b1db208c9c1b2ab0df488fe
│           └── chunk-001.nq.gz
├── blob
│   ├── 0be9736f3b0ea918facf1f34db5332bb0c739176.nq.gz
│   ├── 0ea43a0282c44b7daa620fc9431b66175372a5a2.nq.gz
│   ├── 1057313f325b04531dd7a9db3b45a629a444c315.nq.gz
│   ├── 2098507532939c0c7777c7a9c35cc6136a500cc8.nq.gz
│   ├── 28a9ecf3190eb9e2997b046a3914c6cec5b99b57.nq.gz
│   ├── 298dc584b4d1a8e9a0e6fc1292fc630f95ff7231.nq.gz
│   ├── 299cee81466abc36e10426e289a1f885d2d7056d.nq.gz
│   ├── 2a62df2c4d0398b9db977934faa0155850c1ec50.nq.gz
│   ├── 2a967654b8c656cab53cebacbf6309d2ae5f290d.nq.gz
│   ├── 3dd96144fc91dbd0db16e0ef894afc2ec8de7425.nq.gz
│   ├── 3e6af7557ace667488f0085f2a493d6e31cd623f.nq.gz
│   ├── 3efce3e746c1a53caade1c0daab52b7ca878d22f.nq.gz
│   ├── 41aa444c2d309d68bb024146cba7271182f3181c.nq.gz
│   ├── 455963f41782c79a8b56535770d474fc3decb00c.nq.gz
│   ├── 51b877c461ed431e3f761bf4635c12801aa554ad.nq.gz
│   ├── 552e5d3b2b9c83274b18e9b6f48f02209ab0a4cf.nq.gz
│   ├── 55f1d55ace1afae0419f07481b2cf53ea3ad1b59.nq.gz
│   ├── 5f40bf129de4d2fd2603069b714d80ccedf83b0f.nq.gz
│   ├── 6a3232abcd2d0aa48719f4d4a416a7c9bb98888d.nq.gz
│   ├── 7763972d2b1165d8b3079f51f773776bd35ffa90.nq.gz
│   ├── 80ccc7e0acd300ff77ee544e410f8544efda828f.nq.gz
│   ├── 822ea44841fc45b2aaee3ac18f47d4e3a746faa0.nq.gz
│   ├── 89b5ad495f38a28975c481ce325072b9732ab77b.nq.gz
│   ├── 89cda24f36d76aeb6c9e39889d11c9ed903dd2fb.nq.gz
│   ├── 9d8b8f1ccbeb4a325798f9bae66299c28045a1c0.nq.gz
│   ├── a1ceba79ccba894ee480eec2a2347232304bc241.nq.gz
│   ├── a3b409923f37fd157a85449950b48a5d1d25ebe4.nq.gz
│   ├── a4ba93b15f7dda1a11fccb66418ac12e1cdbda13.nq.gz
│   ├── a5fa2f5d87d73a3c7a881723e25d33c64f561913.nq.gz
│   ├── a89e9caf95ff614625ee076253034f93c41365e7.nq.gz
│   ├── b08876368b53d8b853f8c62776a043cfad3be425.nq.gz
│   ├── b2d5b9f088756599bd096cb6ac4b0ddbf8bde7e1.nq.gz
│   ├── b607d1901971e1a9df04dd24153127fc9a64d619.nq.gz
│   ├── b6bc7b1697fb5e2d314f63a4d041f47a1d37fd8d.nq.gz
│   ├── bd6c1fcbe82b63c86a0ef4eaeeabe03920d79142.nq.gz
│   ├── bdd9b15521a6e7860883f7d5fea2ed29e1c0422e.nq.gz
│   ├── c45bc6aa0db7a65b6666808315d72e9e00bb130b.nq.gz
│   ├── c660d287fbeaeb26530d12f23219801e1271313a.nq.gz
│   ├── c6e6fb8dd75610a9997e3600456f67beaa7e7f9d.nq.gz
│   ├── caf159bcc65447b5c5857aa3c0ec0ca5e71f106b.nq.gz
│   ├── d09112013a87c165ddf09530716343e90b7813f9.nq.gz
│   ├── d254c635c17a92500137894970982c5fae39c5c9.nq.gz
│   ├── d385c38fb37fd12e4ebabd944b9b45124235f81f.nq.gz
│   ├── d3b327da3161500fdc1c998a2e93fadd430f1184.nq.gz
│   ├── d688645de866eee0e9aa94e066b906dcf17e7abc.nq.gz
│   ├── d7c56814a85d63e1ba82ffecd4b034a075a48d50.nq.gz
│   ├── ddf0bda2a61afa5f9ebb6183de0ae56a446023ae.nq.gz
│   ├── e131174cb3b0e35ef1c23d99905a53ba8a9f6e5b.nq.gz
│   ├── e31a2d114c61cdfa4890c5aacb76dcc44ccb0508.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eed9469f9c3b99ab2cac1be3ba051208ed4dc00d.nq.gz
│   ├── f47311a5d3167554b0920a79e1521bb345aa52e8.nq.gz
│   └── f80efd34f78da88d1597103258f5c9b338dc3668.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5022f1f6f1c55d871b1db208c9c1b2ab0df488fe.nq.gz
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

[samuelcolvin/python-devtools](https://github.com/samuelcolvin/python-devtools)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
