# Repolex Knowledge Graph of deepset-ai/evolve-within-bounds

RDF knowledge graph data for [deepset-ai/evolve-within-bounds](https://github.com/deepset-ai/evolve-within-bounds), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/evolve-within-bounds
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a7c23ac5e6e686afad65497af7b0d19547f94b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a7c23ac5e6e686afad65497af7b0d19547f94b7
│           └── chunk-001.nq.gz
└── blob
    ├── 0029a7dfb0a294c50081e85a6abc8f4319f64c36.nq.gz
    ├── 004ca9a0d871a595029b5cb08b1bebc17be3a128.nq.gz
    ├── 005a07c983ce787917ccd8fef641c9649a29eb86.nq.gz
    ├── 01f0dbbcfa2c5f6c5f8159cf15a74a67e5325f43.nq.gz
    ├── 02fafbb462affa44121a7187cfcdfd829cb502db.nq.gz
    ├── 03034a9881ccad863a7dff10d1c072a864bf82f0.nq.gz
    ├── 04991c9bf39b0391c3874b50940a89cfdc91ae4c.nq.gz
    ├── 04b13af9e67d183fb2b0804e2a232a92b5679f5e.nq.gz
    ├── 04f3f874410659a4a9c41bd438c7a482c1ae73f2.nq.gz
    ├── 05103e9460633889b5cc2849dddb48b6e03ee133.nq.gz
    ├── 05174f9bcda525c5a42d89fee6c6e99df6a0b670.nq.gz
    ├── 0569a9e19b0fe7ebdbfaa5d42150e4f6e7f795db.nq.gz
    ├── 056db2d29e6061bd449d7b0392c385e48bc13f9d.nq.gz
    ├── 05b9ffd857feaf4ccf0329319d36deaf629dcd2a.nq.gz
    ├── 06634ae726974b66471016bd23360933036e9aca.nq.gz
    ├── 06c95b4a5b7be3af2aed4cd2cbb59918e604af87.nq.gz
    ├── 08482fc9c9967f4788faa01265b9e9564d3c0bad.nq.gz
    ├── 087145bd4fa032881f1db4766701b1653b65bde0.nq.gz
    ├── 087aa0788f2f5744545b7f3323f87f76926e3a2e.nq.gz
    ├── 089a5da172c6204c4abcedb838874bba2279be4e.nq.gz
    ├── 08f08c08bc4c16e4d68b434d52743d724c0066fa.nq.gz
    ├── 0a89166b7b27cc9290a806260ac3e02f6cc15d8e.nq.gz
    ├── 0a91010146c12acd312673df0f953fe7dc332b5c.nq.gz
    ├── 0b33ec3c68caea7bcf645fb20a641dab5c5c004f.nq.gz
    ├── 0b7923c3adc1533f117251dc4249099ef3dd8115.nq.gz
    ├── 0bc596f11ca3255727e8216483af4edb8e7a0467.nq.gz
    ├── 0c567ca7f0af9451b12e6269a06c4732abe8ee7d.nq.gz
    ├── 0c93d063bccb44c7ca79d3e8b7e4e4c1de38e12d.nq.gz
    ├── 0c96e57b337c2d09fc2990b48e2711c482da2504.nq.gz
    ├── 0d60ac81ce124153c3bc3cd6563344e4165030d0.nq.gz
    ├── 0d67b9f759b014d94bcc66971627ab3c6e5fef37.nq.gz
    ├── 0dbbbdae44b36bb2d5c25c205efc8f0a76f4860a.nq.gz
    ├── 0e7412d6f7fa57726e92521b2f8031b723ce12aa.nq.gz
    ├── 0e95f7b00ec3006699501357ed051ab1453b07f2.nq.gz
    ├── 0ebae72bdebe79f06bd33cbd2f36b5e74cc2b2bc.nq.gz
    ├── 0ebdba6f0a3ee9db0a5d058c36984ac0ad011cd5.nq.gz
    ├── 0ef83fb35a9afba13745e2ed7c9c72fe3968a7c0.nq.gz
    ├── 0f25326680505f968748efba4fe6c7ca08ca9981.nq.gz
    ├── 0f6169b94698b84196e712295450d2118bcf8f19.nq.gz
    ├── 0f81f1cab9477f0e1d481a84bee26931f667859e.nq.gz
    ├── 0f9ba6094847d8197eca574af6b0484f91048f79.nq.gz
    ├── 0fc50380207156c5904645ea54a81955a515f11c.nq.gz
    ├── 104e56762c88e75ff71071f13f7852843d547ec1.nq.gz
    ├── 11585b0444aa77e3423b3111ac33351eeac9df17.nq.gz
    ├── 119c871e693cd7cec147e13f2d0785ad43822f19.nq.gz
    ├── 124423b8aabd5b617ab95c118a50ee5c720b858a.nq.gz
    ├── 125a9523ba1cca70d982eb2f5d12db80bf3e7de6.nq.gz
    ├── 13e1cbfd8d500dd12af54ef22fbd9ceedd366f46.nq.gz
    ├── 13ec1bef307f2b468a9deb53758a63427405c95e.nq.gz
    ├── 14e74f96b5590b04a2c38bf3ec9d50bae5cd9b29.nq.gz
    ├── 14f31b25d60af45405fa46e6582b500ea7f50a48.nq.gz
    ├── 155e8c474b7609d37d84b4780eb3ba6a9898fd27.nq.gz
    ├── 16086d3f74cc43e16786fb9a24ff43ae5b98615f.nq.gz
    ├── 163ffbd1c5fa4a72c68e497f326979ef6f42a2d6.nq.gz
    ├── 1648da666598d8229d5bd35f48cf1401889fca64.nq.gz
    ├── 169afb10eeb27703da25c3a0b19635b5c1087781.nq.gz
    ├── 1811ae0dc4ea71cf3d387284623540ebbc5c284e.nq.gz
    ├── 18501c54c6167bd47c0728888f78cd9f6299eaa3.nq.gz
    ├── 1872f673d795b4b21a477a9b2b9b8716580b17ad.nq.gz
    ├── 18ebee7e0f38a19edf3e38f132bffb67d624c2d3.nq.gz
    ├── 19c9d2d83a2359856a39add313543878259e03a0.nq.gz
    ├── 19f7e901837ad03d496d06896b58d422a5e375ce.nq.gz
    ├── 1a386d655d41c56cd999d19e3e4edda73bcaad0e.nq.gz
    ├── 1a3d3a0c79b5f52d2544cd2c4402858a76e39c6b.nq.gz
    ├── 1ad2069cdc7ee598e00631e7afdbe5963abf1f85.nq.gz
    ├── 1b3f6e4b9fadfa4acc5ef6b48b29e707c34cc411.nq.gz
    ├── 1ca12d86512d4c22d595ef029c3c91706f385c7a.nq.gz
    ├── 1d33fcf87e4b1459f6b1f6f0fbec07d0cd0df3f9.nq.gz
    ├── 1f9ee2fa70ca28eac1912750e38537bd97299416.nq.gz
    ├── 202b7d9f95633e9ca412cb8a67571cd6fce93b52.nq.gz
    ├── 20ede0a0f805858a8ea6cd055a973dff32beae4f.nq.gz
    ├── 2103bc84fbf30f6d1c5a732a02c37c68aa569935.nq.gz
    ├── 21d5dbc146abb8c56958d6f189c7a92c90c844ef.nq.gz
    ├── 233d2278d0c9e9f3936c1fecf7eea5d3d5586d22.nq.gz
    ├── 23403748969a96ef92dc899845067a6d14f96480.nq.gz
    ├── 235308d65303c2b57409dd21aa795d97aaaafc3d.nq.gz
    ├── 23897860d9ca3c13dabef536c8b6c090943a8f51.nq.gz
    ├── 23a437557ddab13342db66e77a4f423a54443e55.nq.gz
    ├── 248bf0c06cac41617155d7f435aeea1696842427.nq.gz
    ├── 24b65013985b4f970b4788b04db26f82f7e104a6.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 268f63add12ed7453bc3828fb092a9b9db71b439.nq.gz
    ├── 28350d1f38d396ee6e20106ecd28cffb23198a4a.nq.gz
    ├── 287515e84f8ffbece297bab628abe264bf010b85.nq.gz
    ├── 28a0e2d999ee4ae5ff8f45ec286d4bb57a42afa2.nq.gz
    ├── 292e7748d7f1abb21541f99aef56c95da8db9105.nq.gz
    ├── 294a9fa431b50817b932ced1240dbd97cfd3a065.nq.gz
    ├── 2985cc16248bfa0e55550bc98338a24f5e8cb7b5.nq.gz
    ├── 29c984ef7b092a99bfc47d216a3b2e31336c2cc2.nq.gz
    ├── 29e35d90a835f63a62e1cf680a4ed67268d8ac3e.nq.gz
    ├── 2a916adc7695076d83ac2f68669905064832220b.nq.gz
    ├── 2aaaffb2eb4783e26758e8b5db991dc6c4d01d64.nq.gz
    ├── 2ac8c6fd9d63de35efb47ce864ae2a8168d5c3b8.nq.gz
    ├── 2ae7a1b32a928f7d9591b94b05ee8c4ee8481791.nq.gz
    ├── 2af6e4ee13f93df23b896eb6d2649d032aff61c4.nq.gz
    ├── 2c1f6a4ecc4e4fc55e9973b3fafb6af945f4db75.nq.gz
    ├── 2cd3b585c21743949252ca9f65526e0fcbcf7b61.nq.gz
    ├── 2ea4dc7899d6b1677e91fd673aea4fb66bb6e7da.nq.gz
    ├── 2f621a42fcb149d652ac2135f3a95075c1ac3e66.nq.gz
    ├── 2fbbeffb843137984e12d05a67fbe952a8e68eaf.nq.gz
    ├── 2fe5a1f70776db4482d5218b9ad41e7cf565c07e.nq.gz
    ├── 317dd9494bde62dc2cd1e90f6f397fa6cbc0f294.nq.gz
    ├── 31a245ece37bddf34952f22e075060cd58e28c78.nq.gz
    ├── 31d14a6d5b8336ffd62ba5e696cd410d8cb9eb34.nq.gz
    ├── 31ff63cdb3b87549faf6bf3e9490c4d0329878d3.nq.gz
    ├── 32f5880875b54e883c2034e4edefa4b046ee81c3.nq.gz
    ├── 334c75b92a402a44b6a83fe68da5162c661a8fb7.nq.gz
    ├── 33d6444e5880870734fee64a68f146a138fa3e4b.nq.gz
    ├── 33db485907f00bcf8acab9be3a87222adfcf5de7.nq.gz
    ├── 3444dcfa2c5ad0caef82e47a263ea73af29327e3.nq.gz
    ├── 3497f18e32e470cda3af330c2d7e3a1f6b934935.nq.gz
    ├── 35bdb5dfec2655df55f66cde1dbe4369f5440c82.nq.gz
    ├── 35cfe593bb45d57968b98dd8f38de82ac017838d.nq.gz
    ├── 36144b43d0c07feffae51db38a07ed1f9179eda1.nq.gz
    ├── 377c3b783fc1ec08c8c18b4296623cbe355a3b59.nq.gz
    ├── 37d62087ae84e81e677d62cee4a02744fca6accc.nq.gz
    ├── 37f4df736df96ee0478abfb0750b18f61dc928cf.nq.gz
    ├── 3872ff29b1d911a5ffd9d069d0f30482cbf43f02.nq.gz
    ├── 388b0f925192b07d851199b9824e1debf76e8377.nq.gz
    ├── 38a288550deca37caf65a0d4c4016ccec0c486ee.nq.gz
    ├── 39ccfd72074db0f8aeaa846ac5277466d564b7b5.nq.gz
    ├── 39cdb9079396021301ac39ab769a804b69b207eb.nq.gz
    ├── 3a43779fa05cff075b0315ec6a6ed8a5e01aa51b.nq.gz
    ├── 3afb11deb5fd965fe44013ce20ce785eebda0d42.nq.gz
    ├── 3b593321d4c9fee807238883ba704baa4d24a902.nq.gz
    ├── 3b632f95f9faf5590fd753ee1e091db8634a781e.nq.gz
    ├── 3b68929a288e000f84553e254f11755666504da3.nq.gz
    ├── 3b6cd753bcf8a07481222c1ceb300d487264f1e5.nq.gz
    ├── 3be5509a391f3641986ce2fd7d4ecaea69fd1aba.nq.gz
    ├── 3bee13792560cf29a7b67ec087dee71c573ded0c.nq.gz
    ├── 3caed9f41153ccda491474a310b3e88abd0bb307.nq.gz
    ├── 3ce6790135d63c944a5c12fc16b56353d5da4071.nq.gz
    ├── 3d9c06dd5ebe1134c9017d7861c36c7172b22a75.nq.gz
    ├── 3e1e2bde443130033d3863a4aca77c9f2ae33adc.nq.gz
    ├── 3e518769bc335a05df667fc2b1a0a4512b83a7ee.nq.gz
    ├── 414660296f589914491a77be0b98180815e22ce5.nq.gz
    ├── 43ad20898bdc5a805cc0857c03f9956b0b082f2c.nq.gz
    ├── 449de3a474ac7d8c7fd4d19124f3467e7d37a9c6.nq.gz
    ├── 44dcd204d96784b7cde67e130387d558db5ff062.nq.gz
    ├── 453ff8c006719983b435bf1d7d5a5f5b8f40ee47.nq.gz
    ├── 4590b64bcb9b45da10e1aed2bffd25478d1cf9ab.nq.gz
    ├── 45b08e0f19c324ef5933f9ecf01090773d06ab72.nq.gz
    ├── 45b6bb64642fde0b17f40be3d2e408d7ae335345.nq.gz
    ├── 45d6b8a26e7312332e5c59b0dd5c4908405a36c4.nq.gz
    ├── 45f03c522da955b755cdd428a15982fbab94fa5f.nq.gz
    ├── 46e08b4fa1bfd6fd9ec0fabb0ca5d356c633b75a.nq.gz
    ├── 4760633d5e07c2f459bc1ba391127953c072108d.nq.gz
    ├── 47e67a21fa173647e33eb0ca65cc65df19a44669.nq.gz
    ├── 482ec9494d4f196e8d4c8ce6d3c0aaf1cb341eed.nq.gz
    ├── 487e2f30bbda218c897d8c70d66bbb0a5997ea08.nq.gz
    ├── 488516d4cf78fc331156d25a46864f05930f0078.nq.gz
    ├── 48fbcc7bd1ba87f210f82dbc4610a7858a7f22ca.nq.gz
    ├── 49625d555766421beccb0e5f2a9b0d81d8afbf59.nq.gz
    ├── 4a39dca54d47c7419c68570d76b2b0671bd693b8.nq.gz
    ├── 4b6447324176e87f7061073dd1c696a5ab34922f.nq.gz
    ├── 4b6fe012210b1f88c64585d95b000e0352f5781c.nq.gz
    ├── 4cdf1ad3eefca1cc93dbb6b26d887f5bc9380cc3.nq.gz
    ├── 4e21102d409e823d282abe14936e371f8da77f07.nq.gz
    ├── 4e4c3783e659f07239191076156481389673ddb1.nq.gz
    ├── 4ea2e5187c8fa40f76cd31a129287769881f74c8.nq.gz
    ├── 5104ec81c8e7163b948e872cd87603abc521502d.nq.gz
    ├── 51c0d77785312f10a4ec9cd060c842c48c618b22.nq.gz
    ├── 52122de64f61344f75fd3b62cb4982264ca2b244.nq.gz
    ├── 5253da0cea7604534e19628a1be5808ae1c8e13b.nq.gz
    ├── 5263480f8f631487f654c7b4c6b84cfbf0bf11a3.nq.gz
    ├── 5328d69fddc1d654b58a3e710d2fe05d0dbb463a.nq.gz
    ├── 54a71a7f45f1391aa7d21768b94966535e0afc2f.nq.gz
    ├── 5532433eae12c106d496c7850e13687abd2e3120.nq.gz
    ├── 5579cce38f84aba12d85da4cbd8f7812a0aa12ca.nq.gz
    ├── 55892cd5e38e10ce8dcd539a161369313afe4587.nq.gz
    ├── 55ac4226183a9d2f529ed86142b61a6d0ba7750c.nq.gz
    ├── 56ae3255d2350d009b8de404b9ffbd8607f3ccf7.nq.gz
    ├── 56aeb9e380b41516932c002e08524342af370b33.nq.gz
    ├── 57cf84126d3113c333596b5ebd6706ce730c215f.nq.gz
    ├── 58369070c3a4c5b47ba508d61e0a67f535de4404.nq.gz
    ├── 585d6d14486a4a6a46b8d0ff05f06c7b1f7e4900.nq.gz
    ├── 58d44efde72865f79b010e3587065fc148103f81.nq.gz
    ├── 58f5b224c0cc849439ce9ee065b8ea9025269ae5.nq.gz
    ├── 59397e01181fd73b7bd19d20e12af583e9ff1071.nq.gz
    ├── 59ed20695d9de618b7b63cf207b92a0d0b83b3b3.nq.gz
    ├── 5a3ed9aba2fe986290671f064fee3dab4a9ec1e4.nq.gz
    ├── 5a8d3e72ad7ffb62af3b146e1b1f54ab5813a212.nq.gz
    ├── 5c36757924624d21b7e0dba1bd1937939f6c3a73.nq.gz
    ├── 5cb086548f37d9d93d97221d5ec6d17a0dc2cb9b.nq.gz
    ├── 5d03945aaaad74d34719c7f579ef7bcc229263fa.nq.gz
    ├── 5e7cf351b053d355b41d33ea365c5487437dbed1.nq.gz
    ├── 5ea281b62f5cdd4d6f93e2f158965ca6642dd28e.nq.gz
    ├── 5fdb3a232e1c87c67819edbdd7e6b19ed2ecabbc.nq.gz
    ├── 619603cc39bfdd32ed68a0a8cff9879b349aad91.nq.gz
    ├── 61beea57689c7fe7124a7c5a16ab597366b05c3f.nq.gz
    ├── 61da6b8705c92ed982d5bc50e9b3ffdab3317d37.nq.gz
    ├── 626341c28d4c2a391ca5e22b1b2331207547f32e.nq.gz
    ├── 62d739b47cee4e49abb1675ed03f4223062cf2e7.nq.gz
    ├── 63381ac0734f94b0b783ee17e684b34efd6acf97.nq.gz
    ├── 633a844a1a27a3720b39e62e4a974e595d5a7361.nq.gz
    ├── 637b0c0c4a386606020e23f3efb27b14c70cc979.nq.gz
    ├── 6386be71bec2f4b1f65617af8938377907643f6a.nq.gz
    └── 645244b94378311da60ec82626ce574da43a5044.nq.gz

7 directories, 200 files
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

[deepset-ai/evolve-within-bounds](https://github.com/deepset-ai/evolve-within-bounds)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
