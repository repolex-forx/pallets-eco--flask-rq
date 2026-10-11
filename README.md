# Repolex Knowledge Graph of pallets-eco/flask-rq

RDF knowledge graph data for [pallets-eco/flask-rq](https://github.com/pallets-eco/flask-rq), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-rq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4331cfce676f93aab2251c60d9133fcdea7d4072
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4331cfce676f93aab2251c60d9133fcdea7d4072
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b66b214493f7815f70a52dba82b147b06e8077d.nq.gz
│   ├── 0f433a047c73565c67a1eb48cb93c3879215e9a4.nq.gz
│   ├── 13369dcadf9cdafbe7b3661832d69ddfeed7c880.nq.gz
│   ├── 280865fece3a7b43f92f3deec8e8614c73b24062.nq.gz
│   ├── 2b9f62c85b3dfc96e251f30f788d90fda1adb9f6.nq.gz
│   ├── 2ff985a67af35fdfd1076354b771c425867cdab4.nq.gz
│   ├── 31a196c5f922adffe62310c10ff6e7e070df0e7f.nq.gz
│   ├── 339b4f366860ccb091bbf017a050ea6fd41f5374.nq.gz
│   ├── 35e705c5abf566a1ae72137eeb3fab13e89629b3.nq.gz
│   ├── 35f1d66a04f47cfab98109e84591467edb60640e.nq.gz
│   ├── 37a351a8d268df4bed43907694b572cea0ba7413.nq.gz
│   ├── 386cde9f109690b1f4dda531a61ab0b61159e9c7.nq.gz
│   ├── 3be5e94541c78b3126c917dcb6448b8bf9142fdb.nq.gz
│   ├── 3bfc3af1a559121e731a5fb50b4a95da372495f1.nq.gz
│   ├── 3f597c48f3d62f8dffa81aa506cb889881241437.nq.gz
│   ├── 3f859396885d8fe46244aa11674200181314cd76.nq.gz
│   ├── 50866ff9b1721ee8cd27f85c68a28786b8e40f91.nq.gz
│   ├── 5149e064dce29fbb0fd92773a95ee676196971d9.nq.gz
│   ├── 52295a4720f78fc0533bfa65535e62a039114934.nq.gz
│   ├── 5f522c22204b689033f69e581c007bc1e1d73774.nq.gz
│   ├── 6a41ddae72bfd27c245c810b7a3cd6645e1957cb.nq.gz
│   ├── 6c4b08337309fda9ae5030ac7e116d64bdbbfff2.nq.gz
│   ├── 6d6ddd4124df290621ea63916abb92830b984e9c.nq.gz
│   ├── 73384d0a3187edb2d0c34bc01fa1bab7afda507d.nq.gz
│   ├── 76088e8a42c780e788f1cb6a27609de98e1305cf.nq.gz
│   ├── 7c7e3acb125b5e0e0fae25903cd070338d032670.nq.gz
│   ├── 7eaaf1332b75999703bd1c4102a7df2b1ec66970.nq.gz
│   ├── 7f86190bd7c44e9d3931227dc31d0068353216f3.nq.gz
│   ├── 81f6d7d95565c31b8c1306cd9de5aa0c35f927b9.nq.gz
│   ├── 8441e5a64f3bdd680c9d67e8b44c9f176d2a351b.nq.gz
│   ├── 8711b0e178d9dc64ca3d6b0ffb16f32bf9ad8bdc.nq.gz
│   ├── 8b9bc2c9fe6a96cd4cc7b0111e13e9562017cc4d.nq.gz
│   ├── 8c9c4d3a804ac8cf52967c9fcc65878fde46c580.nq.gz
│   ├── 912870b06c94ecdff44f7a7941abca9f5202ab7d.nq.gz
│   ├── 9dc352ef09cce6eebd40ef331d43907c68777b72.nq.gz
│   ├── 9e4cde4877fe2422ce1181098e3b5f086668f933.nq.gz
│   ├── a9b49c25ead21e098f0a39f5ac3b0dbbe9b50bbc.nq.gz
│   ├── ac444bc489a21e6dc7c0b45c9b4528580bb1f105.nq.gz
│   ├── acbd83f90b38e208b211fc7e62366556e9565dd8.nq.gz
│   ├── b594d7121b572af9387356939913bee3b9ef067e.nq.gz
│   ├── ba5ee1fa618e2a8df0ca918fa5e7d099784cfdb0.nq.gz
│   ├── be0c637f90edf631bc3b91dfb4ea5d33f57228b6.nq.gz
│   ├── c283d4c1b54fd399256d704e699fd4d69b007e14.nq.gz
│   ├── cf86ad2a00df7660f0702f33b157b051ccbfb732.nq.gz
│   ├── e0baa4d6296e565a8a50a5a13ac8603879ee0651.nq.gz
│   ├── e3c1e63697857281cf0478100b8e8975623265fc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── fbe82e0e30a669ef4ff5815f73169dd9ea567303.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4331cfce676f93aab2251c60d9133fcdea7d4072.nq.gz
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

[pallets-eco/flask-rq](https://github.com/pallets-eco/flask-rq)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
