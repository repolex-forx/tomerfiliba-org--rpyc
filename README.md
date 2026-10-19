# Repolex Knowledge Graph of tomerfiliba-org/rpyc

RDF knowledge graph data for [tomerfiliba-org/rpyc](https://github.com/tomerfiliba-org/rpyc), parsed by [repolex](https://repolex.ai).

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
rlex download tomerfiliba-org/rpyc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 08ad26b5e80cb1d6f1e1ef8ca2013e1b7ff293fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 08ad26b5e80cb1d6f1e1ef8ca2013e1b7ff293fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0228d642cb86f05bf0df37f71700700ec38d2999.nq.gz
│   ├── 080beefc95222041f30461edbf73b0684a29bc3b.nq.gz
│   ├── 0d0040a34be4549c408978cf48dc18a99595a6f3.nq.gz
│   ├── 0dcd3fadefe592e1f9fc6245cdd0e5e001043e0a.nq.gz
│   ├── 0e2b5fdc7dcdba592a1a869eb6abf4e1c510def6.nq.gz
│   ├── 102d1d37410323f60f16b5a09ab38935a11739c4.nq.gz
│   ├── 11cbde403a9427fe32ad65c07d778918399455d8.nq.gz
│   ├── 11ceb6dcddf95aa6043e02a591d557eaa755a301.nq.gz
│   ├── 13ccd5577496bd6f7835aa85e9a3330e7c85e600.nq.gz
│   ├── 1522c353ed145596ca763f3629fd813aa897a33c.nq.gz
│   ├── 176cfa8089953397620f98d9840b8ea1adaf0955.nq.gz
│   ├── 18d12ceee76aedb91f8e0e45b18f6a6fd7f7ff93.nq.gz
│   ├── 1985c913c83269e02ad4437bdda6c3e3d8b22a26.nq.gz
│   ├── 1c7c48733a2f76de3b855450ac2392803fe4e5c7.nq.gz
│   ├── 2082062db711512665e853f7b54512f1f839170a.nq.gz
│   ├── 2141909a98e6e38419a842d6a103f665f0d15e8e.nq.gz
│   ├── 230e340bc23a0c232a99dae07a3474100c2d37b7.nq.gz
│   ├── 23bb91d7d8bfa72a52c372d03cc205f57a638212.nq.gz
│   ├── 244c53454b99855674f0baa61f8f7aefe43360c5.nq.gz
│   ├── 296527bd76fb0892dd62f54becc39100b3b18e47.nq.gz
│   ├── 29ce707d658fdd01c4ef8ac1802707e973c483b8.nq.gz
│   ├── 2a0c0f9f365de2beea99b8fc8e80663561a9d9e2.nq.gz
│   ├── 2b50676aaf6721f5c2ef335d60f621652e1e59c4.nq.gz
│   ├── 300186bfaf5cb07187f56145b5e5b3ccc6f8f10b.nq.gz
│   ├── 30edc1233740040bed18eee3d879073ecb61ee42.nq.gz
│   ├── 319599e3724d0eb8133f62bf66105c747d0d276a.nq.gz
│   ├── 338b424c21f8d8c9164b98cdaad704dffa4ccfdc.nq.gz
│   ├── 33a8717961a62677a425c9616f732e5f1b814e12.nq.gz
│   ├── 35d9b421e3b8be834593fd4c78b76b84dc439284.nq.gz
│   ├── 37526ec6293219bbadbeccf44d804c8d52662fd8.nq.gz
│   ├── 38dd4d6a65e2bab52fba27b7657772eaf17f4cc7.nq.gz
│   ├── 39ede808e2c2f78c5e979ed9d7186d8032751f9a.nq.gz
│   ├── 3bf9bade865f92f7ad043146fc28767c1776b9c6.nq.gz
│   ├── 40a2b73b4c80dcae564a21af12fabd584dc98d7e.nq.gz
│   ├── 412735e285db8cbcebe0befe59e0a3768df105dc.nq.gz
│   ├── 44309bdf47e15253dfd569daaf2029e4805f8a2c.nq.gz
│   ├── 44dccd546494c65ec91d33134b45fe78e03b64e4.nq.gz
│   ├── 467795b20dfe06f75282550ef5ea68c950c58af2.nq.gz
│   ├── 4aa99c10248dae7af8ef06930953888c5e4d5241.nq.gz
│   ├── 4b3e4adf21b5872c0c6f79e7b3f69c867b579d17.nq.gz
│   ├── 4b5cd4ec880ad98472471214cc2c5b4398afee42.nq.gz
│   ├── 4bb2bbe4b056999d63279b344a16ffeae2413fe1.nq.gz
│   ├── 4e9380926306129ca7a99f0e01cc4d9741fc8ede.nq.gz
│   ├── 4f66377d14c5266724ecbe92e1019570a63166c5.nq.gz
│   ├── 4f97bcc809b35715a270aa43d2f8cdd57fd9ba9a.nq.gz
│   ├── 53511854e9e4dd38fbd1184536b429868af713b2.nq.gz
│   ├── 538d5c1c85b69af929b958eed9f9cfc843624bc1.nq.gz
│   ├── 55c38d49c79f58839f7f7500f4987d908064bc4e.nq.gz
│   ├── 58303545e82fd384513353c9c132569045ff761d.nq.gz
│   ├── 59354aacbdf29a54647954c1848aa6811ac1385c.nq.gz
│   ├── 5b2450ff08206fb282d838935b86ae1c294e1a89.nq.gz
│   ├── 5b779bce55d9015fd33f417d6f1e3795d2bcc95d.nq.gz
│   ├── 5b7de24645ca886df12a18db40ccb454757522bb.nq.gz
│   ├── 5b84bd5bfae8a94142562f3f371d8f2f4437df06.nq.gz
│   ├── 5cad7e563697b3bb39b69b17caf4df0635d61d1e.nq.gz
│   ├── 5de0aedccb6e21242fee449f496fb3a681cc4c4e.nq.gz
│   ├── 5f41444dcbac946490131d26da7eaf2ac2babca4.nq.gz
│   ├── 63a71b796b85d9f4985f44b6d98e6e297a19e8bb.nq.gz
│   ├── 64335c614567e7873d409d7307031253408963d7.nq.gz
│   ├── 6664d82da5855b04a7bc37af50b00e364a81c333.nq.gz
│   ├── 67ac2de86f1359c7bdfe5732cb309d467fcc59de.nq.gz
│   ├── 67ade2592f63adf7c98fcb547ac31a5e3707875a.nq.gz
│   ├── 6a91deab5ebebc740f16114c20231e34fab79417.nq.gz
│   ├── 6b71b220848fcd3a12b4098b603c4202d1a4ebdc.nq.gz
│   ├── 6bb4b735b3bad212576bd65a8886b9e42d3015a5.nq.gz
│   ├── 6c494f4a965b322c8c6d6834fe3027ebd4ce5a00.nq.gz
│   ├── 6da9895c39f4397759c15563f9f5781acb84640b.nq.gz
│   ├── 6ec9067903416e096ed54dce40bf42a4fdaa7d19.nq.gz
│   ├── 72ff4389078b1a766c45843234f74bf6f3bdb8db.nq.gz
│   ├── 7373affc3838139f000fb51c17c5c9b5865f0dbc.nq.gz
│   ├── 74a3c89ca5fb6d864e4935d7d95ab182d2559ba9.nq.gz
│   ├── 753521165cdfb16a0c278c86f4e2eccb99b19ee2.nq.gz
│   ├── 7535c9ec4e42fa4028363e30b6fc61a1e7ce0beb.nq.gz
│   ├── 75a9e68049531db223f6896ea2165604ca9aeb58.nq.gz
│   ├── 75f38757185a9ec6a4258cc1d2d8bcf6c4d2a820.nq.gz
│   ├── 772bad3b6763b225f55d6b01ddf5d0ef165897dc.nq.gz
│   ├── 78b24afc565b033bc15cc8197791f618a2790f1f.nq.gz
│   ├── 7a2a76defaa5a82fd80829c68a4b29c4114dba10.nq.gz
│   ├── 7a7adb72dbb8c06f1243bb568d0c3a666f80a188.nq.gz
│   ├── 7aa8868416601c58a5919b783af98a9d152bc17d.nq.gz
│   ├── 7c6c5baebb2be91b6841f8c73c7fc4810af20eac.nq.gz
│   ├── 7ce36b52a3870f815c47d50fb9384135870a2fe0.nq.gz
│   ├── 7e03d5462bb1e83508a2325fd1cee2aaf1c7f13e.nq.gz
│   ├── 7e82fc78b6c2ff1c989601e4f9d872b94aec435f.nq.gz
│   ├── 7eaa7fd37b1c61ceec9a63adfd985b0dfba45e24.nq.gz
│   ├── 7fb14688e8222497c1dc249fcf71cfe8bbb646fc.nq.gz
│   ├── 7fdbd55024153fa4251490210ebcad2811b71c71.nq.gz
│   ├── 802e4577cb39b7d2c721e06fb11700aeec303c55.nq.gz
│   ├── 813b59ea49140dd2b72d6cc79b04f14d6ded40cd.nq.gz
│   ├── 816626a6777ddd7f6795db7dbc424dd2940bbe3e.nq.gz
│   ├── 81ff4156a74c64e79fc3ef4d03e5b08b50fd49ba.nq.gz
│   ├── 82133027c9eb6dd3ff20c82704ecf25650e474f5.nq.gz
│   ├── 822116aadbdff336d2b9496f3f1d20f789f1e043.nq.gz
│   ├── 824a61592237f9ea491dc005f5aeb8f233d93528.nq.gz
│   ├── 847594e2d9367f479a6ca1cf28d06368b3f17eae.nq.gz
│   ├── 870fb16e00c708dd59ecf9ece18bfaf6aaef31c3.nq.gz
│   ├── 88826caae3597fe6b2b0c18f556f8d092f72dc55.nq.gz
│   ├── 8ca39972c3a7a1b334ada4cdfa899e754ef7628b.nq.gz
│   ├── 8d188f49e7a5f1e1ab9ee3764a1be70f24b71a03.nq.gz
│   ├── 8e48e71aa4dbd063686c36804eed17252687f929.nq.gz
│   ├── 8eb1a599b2a58cb403da01ab8de28af233fc71d3.nq.gz
│   ├── 8fb32afdc2d0bb190e376422a2c2c706b65743c2.nq.gz
│   ├── 9139c62d55497c3b59bc7c9cb870ff9bad5b0358.nq.gz
│   ├── 91f66afbb086776e323c4d17099e96fef5d3e7c4.nq.gz
│   ├── 924b0e626da7bb7807ed110c2a3cdaa5bc28fa19.nq.gz
│   ├── 9285ebe24e558d25e3bcc7782748b33f15c1c6d0.nq.gz
│   ├── 93faca5efc02affef38a74481b90816dfa39d55e.nq.gz
│   ├── 943fa38743fceaa05c19b60c7807a1a994e6d323.nq.gz
│   ├── 94eb356cdf516f904c725e9048fb2c7c27d09eac.nq.gz
│   ├── 96212fe2686cc592962c4818a63849d0af53c7e4.nq.gz
│   ├── 9717775bbd429bf3966dbb969af79bf9d9da3676.nq.gz
│   ├── 9821c5062546fd09276a7dcaf36b2f130971aa78.nq.gz
│   ├── 98b930a82fb2a275eb54104818f6477b542df91a.nq.gz
│   ├── 9b669dc63aa016dcbb67dc720851016ea36c8e49.nq.gz
│   ├── 9b7fa4a46b80745d7bec867e8528906d9951c51b.nq.gz
│   ├── 9bd11c044219d48d592a45da70c044ff9beb5529.nq.gz
│   ├── 9cbd84b5c6ff4ac6f917fa44e69bd85888d5b847.nq.gz
│   ├── 9e8d8789e2c0d679258ac3d7500e7999febf31dc.nq.gz
│   ├── 9f0106c26f83e1b7a183939c435e42036b533c9c.nq.gz
│   ├── a003a76ab07e861ab55bb6d1e80ebb2e6d93f3f0.nq.gz
│   ├── a01215042641e8df7bd382c999c25691e96db06c.nq.gz
│   ├── a384eaca026df7d8f2f8eb9e2f0ac8614510ce21.nq.gz
│   ├── a485625d427fe22dc5597483e2581751cc127516.nq.gz
│   ├── a540756a6055616c40922f8b201740fbb45fc2d2.nq.gz
│   ├── a60e9fc999ef2a5eec5c4d18086384d65d96a9e3.nq.gz
│   ├── a72cf5ad0774c27702088f791bdc13d049534afb.nq.gz
│   ├── a866a0799cfccfdd67cfa362745cfd8f2e84786e.nq.gz
│   ├── a9e6fb44c8e75923c614a1d7cd7d3966f0db8ecd.nq.gz
│   ├── ab5a927e6a12118219f2e92555e23e4109190718.nq.gz
│   ├── ace4d3ef61ae5edad5569592f3b716e184587580.nq.gz
│   ├── acfb624b375782818ff5c331dc9d4d1183e8c4e5.nq.gz
│   ├── ad86f42c3dc292e8f8407ca2b875c3f203ba1ac1.nq.gz
│   ├── ae0ea6828041034d912baddee20823a9c40d6962.nq.gz
│   ├── af9e1ba7b0a34d2830d227bc2852bbb1319635af.nq.gz
│   ├── b0929ab1cbfc20146af117abf440eed685346320.nq.gz
│   ├── b197b0ad679bf3db9e754fe5c448341b9af0eee8.nq.gz
│   ├── b2860493253697635bfca3198f18a89ac958fb18.nq.gz
│   ├── b4135b999eca0455321ed463fa8989bbd822ce2c.nq.gz
│   ├── b4db127b59d21e84a0aa883fd725f2cdfa3b5ca2.nq.gz
│   ├── b50c2cd61076765702aee02408a288da8d25b097.nq.gz
│   ├── b70b6b2e0b9643f381f0902ab1012f88d8aedcd6.nq.gz
│   ├── b8ff23da2c4b26b8aea1388be42bb9f9b59c23eb.nq.gz
│   ├── baea7d6027dff2a784ff04e090a74af94565de11.nq.gz
│   ├── bfe8953e3b77f14a08c3451c34043ba7f0d3dec7.nq.gz
│   ├── c2cf32c3c86e06b542566933fc93c14263246c7c.nq.gz
│   ├── c3757426c9040117d03fe46e31b86928223fd6d2.nq.gz
│   ├── c47bba3ba2495fa85b64fa3e610ea4c3b2eb3275.nq.gz
│   ├── c553274697f58780b20eed5d92e59f0d784b1c18.nq.gz
│   ├── ca858d6ada7d303dff094ca253501e8172c0b4e7.nq.gz
│   ├── cf3e5dd59fcaa70a9c4dea6b197438e1424e2607.nq.gz
│   ├── cf7b5bc1db836b2b1d4a95676e308db7498a6761.nq.gz
│   ├── d29f899f0901ee65ce3533149c6cbeb1b3a3f9db.nq.gz
│   ├── d3d0dd1add04e779e1d2649ab9feee48e7fca688.nq.gz
│   ├── d581c372a9e3a907ea493811eade512629f6b7e8.nq.gz
│   ├── d5ee26bfc8d2b796914798c4b4fe6f710a46fb42.nq.gz
│   ├── d686252a8c67899bc275f171cb43f3a4afec3eaa.nq.gz
│   ├── d77dac7511427398843a562b2c13d1155646fc7f.nq.gz
│   ├── d8dc6ccaa914a2bc7fc3635d0c5fa08a81080e8b.nq.gz
│   ├── d9555f02c1af9a6934539a1b53ac6c9a849db2b7.nq.gz
│   ├── da2ec90205975fa69c9a64c09d07ede3ab762928.nq.gz
│   ├── deb02bde118c6fcb16df59459f75fe1bc6288fcf.nq.gz
│   ├── e19060ff1c1f2e8b69b525a9800682a7864f99d0.nq.gz
│   ├── e219c6ff8f7a4885e9681b01754491970d393d15.nq.gz
│   ├── e2cd3aa31c7143eb3de8d863b0c6ecc36c28e9d2.nq.gz
│   ├── e33b637e606b83902e941da3b385b20efc7f4830.nq.gz
│   ├── e3b2be98348c7bbaa8ebf15740416047d47c5469.nq.gz
│   ├── e58deb6c87dde3496bfe42f74bdd24aedd998998.nq.gz
│   ├── e5fba3aa8304a4ed992c807f8d3a0b363c549de4.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e736119ee8bcbe018d38f561a59d2b4036d84a4b.nq.gz
│   ├── e81a3d84a472a564f11529d3a369657ae42c085f.nq.gz
│   ├── e9ecf0e346bda147ce56bd7b606eeba270f41343.nq.gz
│   ├── ecadce2d87cc207392997c49e2fe8166ea522c9d.nq.gz
│   ├── eccc4993d8f467568f587034aa361c9386d1b3fb.nq.gz
│   ├── eeb63e269df1a5e6c25c4bd374e411df2403aadb.nq.gz
│   ├── efc9605cf52f1e0a480003dddc759c3d7e7933d2.nq.gz
│   ├── f24f2dcb9c41b7828a211454ab984fb09376c9a6.nq.gz
│   ├── f493166949e8fd5b814b713634431e720504ef83.nq.gz
│   ├── f49b9633434b87e24b6d61a96b0c9b2818aa87ed.nq.gz
│   ├── f71d5c6b362bea0510ce4bc7e03df89e7e33d5a1.nq.gz
│   ├── f739f2aaa011a73f1b08e46423bfc9af6caaeb6b.nq.gz
│   ├── f817d818c497578861975c2e0a4835a423349680.nq.gz
│   ├── fa63412178db93ef9789e847bcb1c51cc50268f6.nq.gz
│   └── fe607abee28fb0005311c3cbad57a26ae0d9e1d4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 08ad26b5e80cb1d6f1e1ef8ca2013e1b7ff293fb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 192 files
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

[tomerfiliba-org/rpyc](https://github.com/tomerfiliba-org/rpyc)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
