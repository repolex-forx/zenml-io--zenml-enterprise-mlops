# Repolex Knowledge Graph of zenml-io/zenml-enterprise-mlops

RDF knowledge graph data for [zenml-io/zenml-enterprise-mlops](https://github.com/zenml-io/zenml-enterprise-mlops), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/zenml-enterprise-mlops
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6c13ccf00b655a8b9f7d0465c7651a98d461b250
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6c13ccf00b655a8b9f7d0465c7651a98d461b250
│           └── chunk-001.nq.gz
├── blob
│   ├── 00cf4901321f2374bceebe4a851eedb90ab4e702.nq.gz
│   ├── 00d9381def396aa58e1240444ebc1463a08fb9a9.nq.gz
│   ├── 04307cc92fbe4ad2587ff897930b16bfca8f34e1.nq.gz
│   ├── 0abed1e9964b95179bd28d1fc05caefbd2efe227.nq.gz
│   ├── 11e1fa65756bb55c853aa4da801273f41c3d36a7.nq.gz
│   ├── 1214208085aecbbc6a110fc5774ae7c07f73c603.nq.gz
│   ├── 13fd73ee8c9c48fd3610d3ea1b2199bc28f15f65.nq.gz
│   ├── 14fe923f92f9eb1f0bc99ccbaafbaa907541e18e.nq.gz
│   ├── 20800a8af2c5bd3e919b933b6d96989dbd1761c5.nq.gz
│   ├── 20a90af5868e6bc5e7e57fbf39cd8c02d89306f6.nq.gz
│   ├── 20ecd9dc9ac269003874127579a350ebeb44b0d5.nq.gz
│   ├── 21b484e9abb3b732cde2f97d302cc3aebbe68b7e.nq.gz
│   ├── 2209c0239ada90d5d2ebf29cea7c5445e0ec17e8.nq.gz
│   ├── 253c69f0101f4f8493cf2190b5d1666541cbb942.nq.gz
│   ├── 25841026402ed20a990a152c9f7cbb5c4ca2cd5c.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 2d69ddddf3038e7ec10e1d052c069bbd1bc3821d.nq.gz
│   ├── 2e43c9adda20476c8e19ab9c1f3f06b4938ee92a.nq.gz
│   ├── 337b228583a928af064aaec2596362cbefea7b30.nq.gz
│   ├── 33c7eb0bc4a80bbac3406e91bef84c1a54ae14fb.nq.gz
│   ├── 3b6679021f913bb63cd1067182e9f69ac01766f8.nq.gz
│   ├── 3bab4c9711a8315767f41b30182fa43c105dca84.nq.gz
│   ├── 40d672b4311967c4dd3aff1c6bcd0f8ee1ca0d0f.nq.gz
│   ├── 43d6915da621ce373d774f0e8e9a3aa56f0918ce.nq.gz
│   ├── 4458f8a75969b8fd9c652c8d0319d1d4c9fe897e.nq.gz
│   ├── 4b5cedaf56144f22616f94017d807457a4e7dba3.nq.gz
│   ├── 55fac0e9b5d07042de1e34ace42e4d33fddf2648.nq.gz
│   ├── 582e496aa0209ccae786105a7dec0c4fa9ff818f.nq.gz
│   ├── 5a173a0d921faf279a8d210ec1d7a67cca4ae195.nq.gz
│   ├── 5bd327d09beb44b65f28cb3cd77ecf007195670e.nq.gz
│   ├── 5dc02084c49ced619ce188e1c74067632717e55b.nq.gz
│   ├── 5dc8612f37401d70bdc5c766f48e262205206128.nq.gz
│   ├── 5de884c68689bd5f725a86c26028850b37264f13.nq.gz
│   ├── 5f185b8b0b73f1ef635d45925f35d3901bde984a.nq.gz
│   ├── 5f3c284742b7a148f205733a9759b1d4b6b9b9d2.nq.gz
│   ├── 624edb17599a853adf814606733daa6a6f1a15c6.nq.gz
│   ├── 6307066062d57b1bd72bca9713966119a9551f48.nq.gz
│   ├── 6493deda1ebf40476a8fac80c06f29b28cf114f0.nq.gz
│   ├── 663b43fd5a547978fc41757849851e02b86b1619.nq.gz
│   ├── 684b64c5c7928543b80687daf39e5011dde196fd.nq.gz
│   ├── 6a923bc56e58526ff7e18bc3eee44839c0e69b1d.nq.gz
│   ├── 6dc8b50a4f143af650cb298b7b8c9b149545ec4c.nq.gz
│   ├── 6e16b868e959011433a6835db421d42e7bbae758.nq.gz
│   ├── 6e92aa8a72aac803df04006a5de3fe8c5120b975.nq.gz
│   ├── 6f8c34a5c8d3048de93e1238383a4c5cebc3dad6.nq.gz
│   ├── 71e228d6e61850dea98ab8057c929a0b5a8c51b3.nq.gz
│   ├── 721b25b9f89f8c251463eecc3891dcaff0dcf63b.nq.gz
│   ├── 733ab4bbb64ed96befde3bf5e255127a8ab5826a.nq.gz
│   ├── 75ad82f48376373728d22c576c0ed454cf7fbdb8.nq.gz
│   ├── 803e4041db48a6b036e778af28dbfab2b50b9d74.nq.gz
│   ├── 80555989aa4ba89d50b9d2a7a5edddb4f05c1ea1.nq.gz
│   ├── 81afea4d827dbdc178ba635231d4f6afc206f9f3.nq.gz
│   ├── 81f13867695e01b47e765e5a3fc6423a82ab08cf.nq.gz
│   ├── 8a9c718dd08eeafcd739da9a2f424ba5957cd0a0.nq.gz
│   ├── 8b19ff93166a3d35da188226fbf20693353394e9.nq.gz
│   ├── 8f80fffe211a8b5914a144a64c909e2e899369e5.nq.gz
│   ├── 955c758407bb2f3ffa12b86990c89fe0a570defd.nq.gz
│   ├── 95cb235d14efa632080a5aefb4d768b00c51e014.nq.gz
│   ├── 9673d7f341d276bb3b14879907c021bba9ee1016.nq.gz
│   ├── 96dd67025b020b7b83b61da21bc440ad45dd92aa.nq.gz
│   ├── 984d80fefb5b6e3b55d92c5820b6b39c651f23be.nq.gz
│   ├── 9bf8c2f5e8b6c7fa91bdb103fee41fa23e65cb9b.nq.gz
│   ├── 9c6c6b5f6e7547c11481278cc321c04f67e1d667.nq.gz
│   ├── 9e02f9b0b754f6d456efb744708658f308b509a5.nq.gz
│   ├── 9fd39103b37fc57343aa49a121ca1c3b7ed038bb.nq.gz
│   ├── a03a9f9a54f2c79448c9a63a2abfd8db22b51fbf.nq.gz
│   ├── a2279c29e0d3d5dab7b69c013b6ea600aaa2e383.nq.gz
│   ├── a24d3efc585e089039474fd0a85203045385571c.nq.gz
│   ├── a29da461fbd573c0b473aa92af95ac46f80969e0.nq.gz
│   ├── a4e2dfdd348682bde81a07389978fa98e33ec632.nq.gz
│   ├── aa6971d4dc48ed32e9932f91b464fc344974c1d1.nq.gz
│   ├── ab2e233c6eb6d90899663c03ed3cef52dc4cc9b3.nq.gz
│   ├── ab8aee7d5ccc7f01d42cc472ea4bff16a3441535.nq.gz
│   ├── ab97fa8242bfb3f233f19b26f5ac9567f6b0fde5.nq.gz
│   ├── ad7f319050e1c6804d112bb77363b46dd7b24ecb.nq.gz
│   ├── af2408e0993f541dc7c9d5ce45526cb9cca2f74f.nq.gz
│   ├── b60b5ee76a7e0be46fa7080059040eac4332252f.nq.gz
│   ├── b6db6cedf91e31f8d891144b18b6b55130f22e66.nq.gz
│   ├── b9fd2dae2edf98a10677f21a5c65037886f0c264.nq.gz
│   ├── bb31ddaa5586895cbb38df568bbe2f9dcb5643fc.nq.gz
│   ├── bb57cec69f2c0a120063e6c841ed41a562d08fe3.nq.gz
│   ├── bc64b809c282a101f27673ca4a2124fc14ca284e.nq.gz
│   ├── bc6b6bc5fea0fdf256b425a8fbee55705decd9a6.nq.gz
│   ├── be8503b1a0f8f1f8eae73a02f2d100ef9bcab8d7.nq.gz
│   ├── c5100cf9707ddc8b4edf1dc284ef380078278ef6.nq.gz
│   ├── c5bdd22fa72271105261568a547219622548ef6c.nq.gz
│   ├── c93f82ecc9fda7f4acbb29da74f4c6347fe81bfd.nq.gz
│   ├── cbed07b710f3f0243965fc877c69199208628a8d.nq.gz
│   ├── cd7f63cabdc1386c8e1b0379d4b89f94f9675877.nq.gz
│   ├── d4e73b0a6aa481b63186e6abe32a3f56fa0b76f4.nq.gz
│   ├── d7055a4ddcbbbf45d1db87fdd94c577a395bbab1.nq.gz
│   ├── d8041e906fdfda54ea206606538873cd2dd2dd41.nq.gz
│   ├── dc75067e72ebbf35045a27dd8930c69c77e247df.nq.gz
│   ├── e2ffe39d8b83ff8d386296e538e170304dba3c1c.nq.gz
│   ├── e40cabfe9e5647cb4cc85792f0a2405289dfd0b0.nq.gz
│   ├── e42915e421305069802ed3972b24d7a4bbec0737.nq.gz
│   ├── e4bc2cf4daa4fbdca5d4d0bafe02651e8dad4d70.nq.gz
│   ├── e54e96b1f94a20d179381e1e38feb3fdd6e45cc1.nq.gz
│   ├── ebc290b9726649e5dd469292cb02e2b99d99029a.nq.gz
│   ├── edc574f3aed73bfa3274beeb4b98d4175af793d6.nq.gz
│   ├── eeedffcef08dd55e9075106bd2f893c5fddd0b60.nq.gz
│   ├── ef44cb970830f99476597ba0d7f6cb0dac5320b5.nq.gz
│   ├── efabc09736af19d60346bfbf18846ebc7bbd7e0b.nq.gz
│   ├── f3610bccc1983fc13d3d014a66e3b2336b16ddef.nq.gz
│   ├── f627843192c1c10fad56304f24a9009046f7d254.nq.gz
│   ├── f98a75dc6987e509e2ef48189435278513e0e9b7.nq.gz
│   ├── f9e459689f325703e360772dc33466d58190e4dd.nq.gz
│   ├── fb3965dece5e998b17ab9c9864d123421fe8d238.nq.gz
│   ├── fbc8cfea3ca8261a28d2213ce31bedf8ff50868c.nq.gz
│   └── fe1464b303a1d7131161a710b0410934ef30b78f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6c13ccf00b655a8b9f7d0465c7651a98d461b250.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 118 files
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

[zenml-io/zenml-enterprise-mlops](https://github.com/zenml-io/zenml-enterprise-mlops)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
