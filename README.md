# Repolex Knowledge Graph of litestar-org/litestar-email

RDF knowledge graph data for [litestar-org/litestar-email](https://github.com/litestar-org/litestar-email), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-email
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 270f3d370e07a7effe6aa93e58d4eea1f6e1bf1b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 270f3d370e07a7effe6aa93e58d4eea1f6e1bf1b
│           └── chunk-001.nq.gz
├── blob
│   ├── 001dd5f0565d51a7905afebf1caf64c3ddfabf01.nq.gz
│   ├── 0ecd7ae61885709ef509aec8eb7f2de4e418b9b2.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 13e1e497630bb083ccc94ec93a57162503bbdb51.nq.gz
│   ├── 1a0abd65e8e280841a0953a325d9e4160ed4cc45.nq.gz
│   ├── 1eda05378f44e0bae27c472c088e2f724ff18b1b.nq.gz
│   ├── 226da62398c18a74388a7feecf28074c3fd33609.nq.gz
│   ├── 298dff8b817b40914a3a164a4842416aaab30f1d.nq.gz
│   ├── 2a63eaf15cf73fb89189ee8212612efa03a37a7f.nq.gz
│   ├── 35a340b6565bfc92ef9d53ef01e30267f65d4ec2.nq.gz
│   ├── 414c7055ad09de6bf3f246c26d96682456c1a290.nq.gz
│   ├── 46ded0386ab7ef23bf21e116e12de4c9dac1aac3.nq.gz
│   ├── 525169197f9061256abd4def4b2aed1cc54506a5.nq.gz
│   ├── 54907b2d24fd2da731ad76c2eca76bbc00dcc14f.nq.gz
│   ├── 58a861748ee9fb9888c30db19c8687560785e161.nq.gz
│   ├── 5b55597a10cdcc2404a0cac595deb472f95aa6fc.nq.gz
│   ├── 5c297f5ab582081c36c64af7e5f1686db7f942ae.nq.gz
│   ├── 5c2dc9c32b931a6c9d6b80552137bd1cb7c508fc.nq.gz
│   ├── 5cc5380824ca2b3ef8c4dcf1df4e89d45887f1ab.nq.gz
│   ├── 5fa246e55978d335397715f64a42b7cbc00960f8.nq.gz
│   ├── 5fc7e707909dafde1680aeda92ddf1fe74f2aeb2.nq.gz
│   ├── 602760df0db91678817a27384dbed8eb683df954.nq.gz
│   ├── 60e134016397195f18085d5f5fd53f3f0231ce18.nq.gz
│   ├── 65ee4b1ea2c8dd506296cea251a77723f11c6365.nq.gz
│   ├── 689bff871a69eaa839c4dde6ef7de8e8a27ca1cf.nq.gz
│   ├── 6912e3bcfbb89dd7c85a06a7d9dc81a1e85258cd.nq.gz
│   ├── 6e1caffac76ba3441d13112588b4f27f173b1a77.nq.gz
│   ├── 6ef841e0239a9af9f9f7e8cdfe696aec6067e373.nq.gz
│   ├── 7360fa6761a3bfe0367fe3806b90ae33374243f5.nq.gz
│   ├── 7ac530eb9ddf12f270fb8250cfa9959c6b099ee2.nq.gz
│   ├── 7b28a3802cef1699b0dc688b216fa4fffa0ba1d3.nq.gz
│   ├── 7fad36f88673a902253b157c78c4e4dec171af01.nq.gz
│   ├── 8540464f237ffa3ce236221671abb778342f1492.nq.gz
│   ├── 8823733ba4e8c80e627c902bafa104455f3a0990.nq.gz
│   ├── 8c02a2890ad40247522b9dda47e8404cf36f59ec.nq.gz
│   ├── 8d161054a158e5ff9fd7deef805f53f2a59df7d3.nq.gz
│   ├── 8d34647ebaece1d7e9a96e1caee2834906d427a2.nq.gz
│   ├── 92de4dcc633b1b6ec7185fcfb74c271374ccdeb8.nq.gz
│   ├── 952d00db047f9be25bdbefe010f3a5d36e40beb3.nq.gz
│   ├── 9b897478ea07622a5cfa3753540865a4fc755f28.nq.gz
│   ├── 9f4b4afc8c3f06068fe47ae8a4e87891a9567558.nq.gz
│   ├── a410c9f604007bdb80713bb3be7f9fd37b11a400.nq.gz
│   ├── a42ae4bea3320f1f94e711a4bcac1c358d67d7a0.nq.gz
│   ├── a4b490081dd3c862e2a0b2990ea410e62561fcaf.nq.gz
│   ├── b51881f4072c4b2e68181a2db730625479c18b66.nq.gz
│   ├── b78545fe664a78b391d76eacc8b83d6db381408f.nq.gz
│   ├── bab960d928a582aa09fa9eb672d94092b8980254.nq.gz
│   ├── bbb6ae86a18e0267bb43791b865c8f8970dadb42.nq.gz
│   ├── c9e2df91e590d0e5fabf741ad15debc6a7184c12.nq.gz
│   ├── ca6dc4655a6f580940d7dcccdf5b83f85d7fb22e.nq.gz
│   ├── d5bad8e446ba6988a6cbe856b097477d40103134.nq.gz
│   ├── d6d79c3a5e16d9a2bdaaba010b2af9839708a551.nq.gz
│   ├── d7abf7459d52176994cd5ca201b8f748fd691c56.nq.gz
│   ├── d932c54fd5a31646ef8ffbc84faa2e2a324aaed6.nq.gz
│   ├── e0488f351811cf43ce66df9344d4dadc7cbb319e.nq.gz
│   ├── e2f44f5d280c0d6f666ff248e065bcba9327c826.nq.gz
│   ├── e3daaaaaff9e5672d901ce6e9cb1232971ee88f8.nq.gz
│   ├── e404eabfcf5059be08de9dc36a115da563e74e9a.nq.gz
│   ├── e6966939ff89ebfebb0f154850d5c03c469c270c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8cbdbec072e89b1e39fb3da290dd79c2174c6c9.nq.gz
│   ├── ec476f7904917cb782cc5a42d5f5fcc1810e0a42.nq.gz
│   ├── f06cf5dd96e117dffe4d02cd6aa01077186ffafa.nq.gz
│   ├── f1884a92e0a2c54b407306ece8cf3dc37dc8dd56.nq.gz
│   ├── f49dae74142d4460c0c27d77460489c3337382a2.nq.gz
│   ├── f813c25a6f2b032926a6d126e2f4a750ae2ccd2d.nq.gz
│   ├── f99601d28b6355e66f11544cdaefdd0709c5de0b.nq.gz
│   ├── fa190f746f8a5f150055581a2ae606b9569e53c8.nq.gz
│   └── fb918c62ac2dc2abef82d64f93aa1dbb75ecc642.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 270f3d370e07a7effe6aa93e58d4eea1f6e1bf1b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 77 files
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

[litestar-org/litestar-email](https://github.com/litestar-org/litestar-email)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
