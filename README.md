# Repolex Knowledge Graph of dask/dask-image

RDF knowledge graph data for [dask/dask-image](https://github.com/dask/dask-image), parsed by [repolex](https://repolex.ai).

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
rlex download dask/dask-image
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e1a0358386403cefc8f1fbc68f5c37adde114587
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e1a0358386403cefc8f1fbc68f5c37adde114587
│           └── chunk-001.nq.gz
├── blob
│   ├── 01544d483b1f688e59f475e046c465498d8f561b.nq.gz
│   ├── 024d0856f0490cb6d6309a7843444d4ff276fedd.nq.gz
│   ├── 02575cef27828666d3fa748cd996081c938db20d.nq.gz
│   ├── 0b53d355ddacf01e170731507b8cbda0f01e77f9.nq.gz
│   ├── 0b90e7e58a45a3f8b02b2f3df48ac87f6628bad7.nq.gz
│   ├── 0e16e982cc58a3aa3b52c3fd2f884b822aed24a7.nq.gz
│   ├── 127312317b29a03bbeb97b975eba385e5f70aafc.nq.gz
│   ├── 18bb73410316cf07a8636edadf48489b1e084f41.nq.gz
│   ├── 19972bf2551a77286d6dfcc94eaf9037a3cbbf3d.nq.gz
│   ├── 1bc3dae8b68fe32dbddcca1ffdeee94b74b65bb8.nq.gz
│   ├── 1e2339324c7642650059daf4cce6fa18fe65d6b3.nq.gz
│   ├── 1f6393ee1426b4fab6fadf1df798d22b5898ef2d.nq.gz
│   ├── 21fcf5cfed2020ed176aa3027f4c328452b1719a.nq.gz
│   ├── 24a1a8e101a2c4dbf88a9810be674b70da7c9a5b.nq.gz
│   ├── 24c12482874b03ddee6bbead2500dcfbee520fc6.nq.gz
│   ├── 250649964bbc36f4bec2942f69238aa6f7c02c1a.nq.gz
│   ├── 25aa7b3d1929402f3d517b527784edaae9feb8b9.nq.gz
│   ├── 25f2714bf74537daf8e22eaa5f8290a13f8a6f60.nq.gz
│   ├── 2baa622f81cd248d4d33a23b8d0488bda89473e4.nq.gz
│   ├── 317b641da87712851e4304d07a8a4d30b97a61bb.nq.gz
│   ├── 39132ead7d305e7b1d87aadb93680357355f39c6.nq.gz
│   ├── 3b298c1e2b5e3967759a0045a7071b18cb3d1215.nq.gz
│   ├── 3cb2b97e6dc5bd402a86bc74456d4d63e64315de.nq.gz
│   ├── 3fd871258c01ae8dadc5fab3b1616bb714a903d5.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 455a576a6b9c4454b23315430cbdf4e6d1ad896c.nq.gz
│   ├── 46709071b77455ce8accb4cc5ce3d44e7f14af71.nq.gz
│   ├── 49d9041ae87d1a45a760d35fb90a27ee17f78d10.nq.gz
│   ├── 504f5fcd1bbb16caeeb7b907d7657d3400deb156.nq.gz
│   ├── 5089ee6b0e8b81719a45b7df20397517b54d118a.nq.gz
│   ├── 50aee3cc398a9e96314d2f792e708f5a89e0b55b.nq.gz
│   ├── 52ae617a602380bb52b6e08c3d0252551b6b87bc.nq.gz
│   ├── 585a1c87ef4aaaa1cb9eab9cbfd65ac03fb137a7.nq.gz
│   ├── 5c6af93242923e40751ee4fbc81baff1ff4ad2cc.nq.gz
│   ├── 5f191b34e273fa4da6632699a5f30853ecec5ca6.nq.gz
│   ├── 69b3ee2f945487301d315d79dc9e02b833252c1c.nq.gz
│   ├── 6a6a60450faf2f49dbad4f7eb8e8f1e14eee317f.nq.gz
│   ├── 6b4b52fd0f94ee8a83b1fcdd5fe4d1ec391bba0f.nq.gz
│   ├── 6f13b451893e31f9ed1dd3967261d68dd69d2f8c.nq.gz
│   ├── 6f4151ef4c4e9d1e51d1a99cde951b33e18956ff.nq.gz
│   ├── 75a225532fbab9045b6c27d15ac4688ae1960d07.nq.gz
│   ├── 7959f8e2fc98a48936c79d597dbe7489d7e741a6.nq.gz
│   ├── 79959f806107b930b022cd982dc98cf663a167c5.nq.gz
│   ├── 7c4f5edb5dce3188dea2d33c1648cb63ee4fd192.nq.gz
│   ├── 7fbdec303d23cb70a25ddbe766d19ce984a56052.nq.gz
│   ├── 81960c5c6ab1a09c5926a6e1bf77a1a8ba15c04d.nq.gz
│   ├── 894ad877a1285ab79a9962bfc820c7699c1f41f6.nq.gz
│   ├── 90b240c6e436cc144e542e212196186cdc6b3eed.nq.gz
│   ├── 962eed978d3df26516c799cb4abf172ff7cc8b37.nq.gz
│   ├── 96bdc9a0710a6dc5845f18e1c7e9c478c64ff86a.nq.gz
│   ├── 99090148e69765f957786c50f177baf7b902ba47.nq.gz
│   ├── 9b9a6cf7581030f4a7038893353ed113df3caf52.nq.gz
│   ├── 9f684c51aed778a8e62a2c69dee8c26648982e7b.nq.gz
│   ├── a0297aae5b0e11420b0f7f4b9cab7be6edf24bcd.nq.gz
│   ├── a3dd6eb43ef84b4cfaf21c9f8a4f37f20f539336.nq.gz
│   ├── a5952c3e3d61d32887885546924216a02067b0bb.nq.gz
│   ├── a5ca4ec221f8dc46dc81715c7f080929c8bb3029.nq.gz
│   ├── a6247c1e1225ae4a70ae01f89031008ece0c663a.nq.gz
│   ├── a6f558792f5f617923fa232dc9b61394160f4de7.nq.gz
│   ├── ac9bd6f45fd0d98e783af8a4b8e9f69dec20c01f.nq.gz
│   ├── acf375d5bf9d8944d0a31973cd627a46c54e872f.nq.gz
│   ├── b0daba8ed7aa8326186b7a0b7fa258177c975dbe.nq.gz
│   ├── b5aebb23c7a0c0490116ebd32c148781944fa5d0.nq.gz
│   ├── b7827b74a4a5109a3f72898f51b02c61a66777b6.nq.gz
│   ├── b9348b9ab3f5253ec18ddbea74804e3a2aa463a3.nq.gz
│   ├── b9f1f0cd3682148de327221376076218f764550c.nq.gz
│   ├── bb7811708d659cbbedbd2522937a17fb697e9386.nq.gz
│   ├── bcb5b70fc7dc68a199a8939ac3105656387d2de2.nq.gz
│   ├── bcc780b3581a8e2462337843900a65f0d9ad4e23.nq.gz
│   ├── be98c0d1547af4fd6e100ebc4606f460fe281727.nq.gz
│   ├── c7b977eb89beb8236300606998f3dc7e17e66d7a.nq.gz
│   ├── ca15b4731b5a9a8679db2f8aa38276fda88f301d.nq.gz
│   ├── cad07bc233f1e6722e393487c0d48505f35cd48c.nq.gz
│   ├── cd8e5dd36c6f752286aea05d7deccbfd528bc868.nq.gz
│   ├── d0c5e5b8ca81803bb9cd560d10d35cbf8c92e998.nq.gz
│   ├── d268fc44cac7cb6998885b7ea0e4d1aeb7028c8e.nq.gz
│   ├── d4a2c4405ec2e962c521a13af91bf5f7098a62a8.nq.gz
│   ├── d89231025a0d7d706664c3fa10ba8f22d034abfa.nq.gz
│   ├── da6deb55d06eb14156be3830bddbfaf3b51a001e.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e4a0b1e75974f0184419180b90b693a3beeade80.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e68abc5196435dd439831b5a5f8584ddc4091005.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7165bb5dd77cfc60996e556986735ae32a8ac31.nq.gz
│   ├── e90963c9408ccca07bf7bc7ae098635ecd753ba8.nq.gz
│   ├── ebcd251ea355c92c9bbccc3240cf5045e76d94c3.nq.gz
│   ├── f03a5448f9ef7119da85e773cb81afaefd1ae6c7.nq.gz
│   ├── f3102103b48a88c9594b44cde788dcc603d54b53.nq.gz
│   ├── f5300c95039b8e8c652bdf71d32cee76b2874a4f.nq.gz
│   ├── f614889d5aecbe744a6d21ea184064b73d4d9f4c.nq.gz
│   ├── f8a0d841b92fef1b1ce6955e87ef7d173e45b9c4.nq.gz
│   ├── fb65181c50e1d5cb4c8043254d3d875e1cb95e8f.nq.gz
│   ├── ff060011a86ce20f37b2d8d0efa3e7a920b3ca6b.nq.gz
│   └── ff50aa13aec722c66f3de21651e83590e237061e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e1a0358386403cefc8f1fbc68f5c37adde114587.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[dask/dask-image](https://github.com/dask/dask-image)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
