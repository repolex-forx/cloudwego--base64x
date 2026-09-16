# Repolex Knowledge Graph of cloudwego/base64x

RDF knowledge graph data for [cloudwego/base64x](https://github.com/cloudwego/base64x), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download cloudwego/base64x
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b1a66433e2aaf4e90a73578a914a25afff44c28c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b1a66433e2aaf4e90a73578a914a25afff44c28c.nq.gz
│   └── repolex
│       └── b1a66433e2aaf4e90a73578a914a25afff44c28c
│           └── chunk-001.nq.gz
├── blob
│   ├── 022984bda47753486d2d5f421b3b01802ddef9db.nq.gz
│   ├── 04473a8082635151872a4661e90ef9aa606cce2c.nq.gz
│   ├── 044a14f4e20e8ea15615ada457888a22c02dc1bf.nq.gz
│   ├── 06dd28ad194b9cc4b978cbddf391f8895db26fdd.nq.gz
│   ├── 083d864f7deea0e87610b817c9f06157aa7de5bc.nq.gz
│   ├── 1876fc045934ae6b85e54a3a8e721af44919e860.nq.gz
│   ├── 25ba9802dc1f1472fc5e6ef4ab5892e5128304a1.nq.gz
│   ├── 25ceb891887e6cfc36d549e33e45518e26b632a1.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26d3546f4c8edddc2464084323d4ac620620380d.nq.gz
│   ├── 2ce8624c10bcdf1a622c02fc6742868c299b16bd.nq.gz
│   ├── 373b8ac5d583c7c7e0ec3d76e17e12a8ad858d3a.nq.gz
│   ├── 3e097f977933f1f9cbb14ea05c21835d18432015.nq.gz
│   ├── 3f6e529101a6e59d2590b7c9fbce272b3c66c039.nq.gz
│   ├── 4513288e18282217fba53c4b28d04954066098e2.nq.gz
│   ├── 47b5bead831b0ed001e58df834da5357a81ac26c.nq.gz
│   ├── 49569e05e90b9aa8c9c691fb41dac0c910d1d2d6.nq.gz
│   ├── 4a3a7c98a22708ae2e2c2478909f6b149c9327c5.nq.gz
│   ├── 51f68fe2ba4f24331e31b983f2590f9320deb7d0.nq.gz
│   ├── 533e87253d290b4fb46afedcdbf4bf3aece93e5c.nq.gz
│   ├── 5b7ebebea925fba4d29d09fe85aaaa1eb1dd371d.nq.gz
│   ├── 5f4fe6d3faf32ed7b80557cf0b9aaed31836aac3.nq.gz
│   ├── 5fec4fb1aa5d83652658aaaaf1d67c23e2c675e5.nq.gz
│   ├── 644df37e05fb7656631f4bd1f870991d47ef6fca.nq.gz
│   ├── 66a27ec5ff940d3a9652d2948746ebac4c9d0188.nq.gz
│   ├── 71405b0bc0f619f7d5ea750a94237ae541ec2c96.nq.gz
│   ├── 720122e39d443804b764b70120a3b8b48d8af032.nq.gz
│   ├── 7271deb6c70c3b7b7a1982f98b024a3c79515eae.nq.gz
│   ├── 7554bbef174f8cb8665528fff073863acb629fbe.nq.gz
│   ├── 7583e5cd1eff09258ea058981c0a80c3f5099a96.nq.gz
│   ├── 84ffa40c051b9783cb95ecce558e885940b0df29.nq.gz
│   ├── 86d264230f2e2b7ee10585483314b8c273ea1712.nq.gz
│   ├── 877737d5629fd13fbb1dcd46f0bc775e0829e42b.nq.gz
│   ├── 8f65d8f654a8ab81c991d4ad0e218374a96aeab0.nq.gz
│   ├── 9b7368d1b27e22e9ec2f2753f90b1f0146e7fa2c.nq.gz
│   ├── 9db80ec92f0a4a8200b994513964d6d315a7bc4b.nq.gz
│   ├── 9e373215513ff2588e2175a89e35b41a05d59ca2.nq.gz
│   ├── a0793f485f6cd16a46e5ef09195d050fb75ca01f.nq.gz
│   ├── a07b093515ca984545c0e51c0a2a99188d6d97db.nq.gz
│   ├── a10629f7224e9a13c88236d6a945a4cad83a659d.nq.gz
│   ├── a168a826643cb5f6222dd97f353cc6b4fbcfe57f.nq.gz
│   ├── bbb8e1466d84e70a6811d2b8752742c4468ce8f9.nq.gz
│   ├── c4f489b10a01441471c139375281ac7c5c24a4b6.nq.gz
│   ├── c78f5041c756259df89dc285a2d26074c09be8af.nq.gz
│   ├── cef15eaa78a4c507364f9bdbf2c42bed910d16f0.nq.gz
│   ├── dd6ae111b30ca81def079a9b23ba877c5d47fee3.nq.gz
│   ├── e4f5de4f605a1f8ee1a77bb113e01a2afc78267c.nq.gz
│   ├── e5f7a8723ae99497496820e4c88a49b89bb2a693.nq.gz
│   ├── e60a59ec0c241a06c9cd05e01cfb05e574ddec49.nq.gz
│   ├── e68ff41d10b99dcb1ead1c8a91533d5b2c62d1e2.nq.gz
│   ├── e89c1bbc33e5cca751549b1771b9e6aef8f26065.nq.gz
│   ├── edecd8761ce3d39e4e2a397fed8a57f1c69450af.nq.gz
│   └── f0291e05976fa9bcefc6b644abd0e8218762e89b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b1a66433e2aaf4e90a73578a914a25afff44c28c.nq.gz
├── filetree
│   └── b1a66433e2aaf4e90a73578a914a25afff44c28c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 63 files
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

## Source repository

[cloudwego/base64x](https://github.com/cloudwego/base64x)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
