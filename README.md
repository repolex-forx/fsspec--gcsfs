# Repolex Knowledge Graph of fsspec/gcsfs

RDF knowledge graph data for [fsspec/gcsfs](https://github.com/fsspec/gcsfs), parsed by [repolex](https://repolex.ai).

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
rlex download fsspec/gcsfs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 905240e42e1dc3069ea58852feec19fd682c1685
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 905240e42e1dc3069ea58852feec19fd682c1685
│           └── chunk-001.nq.gz
└── blob
    ├── 014053b7fc9d2be065d533d031818c8fcb114e11.nq.gz
    ├── 01df7ef40ee69b9c765b8cd49bf52141fba2a70f.nq.gz
    ├── 02b2ca83d579cc1b63f862a8fe7200c30c0d4f7e.nq.gz
    ├── 02de9c6054f7765468584b41506825095dd4ff6b.nq.gz
    ├── 038d34bdb5466025bc5973dd4deae4eeda95d5a4.nq.gz
    ├── 048c969e1f3a8f276f08ad1de552ab4540998b89.nq.gz
    ├── 05560cf3da16a84abc50f069d631fc1aeb6b2159.nq.gz
    ├── 05afe78556591fc7afa41465e7a35b9773ab2ed4.nq.gz
    ├── 05b895c87a6edb314c19da6b7898d631d5ebeb68.nq.gz
    ├── 06798904383f691cd196a49e60d652699c328ec8.nq.gz
    ├── 072972afaad86a82b9266ac34ba2e8aa25f8181a.nq.gz
    ├── 075adcf38c84dece61bbf8ae36d51776c9012f49.nq.gz
    ├── 077c309a62ecaf16b986aeda2d38f3b2048c3992.nq.gz
    ├── 08483ac70be7a5b2cd9ef8ca59fa1b501ee640c5.nq.gz
    ├── 0913dccf8331c3d20ea8791f7a3cfa551afa8042.nq.gz
    ├── 0952887921f75c29e3ab21f535b9b005b752b51c.nq.gz
    ├── 0a3cef4458d105f786513980faf58f361ac30634.nq.gz
    ├── 0b36e51180033761ba9ffe7b5d63cfb19ff0f6af.nq.gz
    ├── 0c6590ea0fcb794f3e8c0cbd849335b5994d4909.nq.gz
    ├── 0cebb2ccd67a22a70d7ecd4d643177bdf9370dab.nq.gz
    ├── 0dcda97f3a639b72dbdac0b2d69bacf341b0058d.nq.gz
    ├── 0eebeca50417ecec6062d77a95167def0ba04688.nq.gz
    ├── 1052a5e4bac4d959cefe315fb7228fb7a1e05d0a.nq.gz
    ├── 145ed73e6c0f7a9fb44564a9cab3c9f1d185be09.nq.gz
    ├── 15b99b9e7d01441c3c8354cf3db282838de25e6d.nq.gz
    ├── 15f08a86a7288b10dc5ecb9ba9a30fc5178f3992.nq.gz
    ├── 16fffc59dc4381614b90acd9bc2875116bc9774d.nq.gz
    ├── 17029eea8309ce033a5e5a07b289941d8b91a034.nq.gz
    ├── 19079fc533b6d2bc80f8c4cb9ac705e3a0c159eb.nq.gz
    ├── 198d53618823d21f5798276620e8f7a1794bee96.nq.gz
    ├── 1a571887d01b9fa6d5bb443cdfa0ac08e0454fa7.nq.gz
    ├── 1b43b3e2ebf3b5c2d93c812f1647ccde16ee5ec7.nq.gz
    ├── 1c17fb9ff281b01f0b6cfed23109e33dddd75bb9.nq.gz
    ├── 1cbdb8832e8d6ee9dfcdeae38c5c569e576ec13f.nq.gz
    ├── 1d3a42db32d1bb4b2b93793912c8b82117d0e3e3.nq.gz
    ├── 1dc426235c4a36b9132b789c303ce3586ecd7153.nq.gz
    ├── 1dd13c98be41129f1d07d58c7d466600ce0114c8.nq.gz
    ├── 20114662c51b1a1a50dd307bf0a7cbc5ca733eaf.nq.gz
    ├── 204acb6c83ff3f16cf601982c8d3f7da4af89482.nq.gz
    ├── 20a54a4f5a484c2ac831c4caf4469997fdeb6673.nq.gz
    ├── 20d138e480d6e50e4e5da20ef52ce2645f5760e2.nq.gz
    ├── 21a0187b965feaf3d6e3f57afb0da7b6bafd9ba5.nq.gz
    ├── 21e966dba7fdb98d0006c6f07bd7a49bb5c8b814.nq.gz
    ├── 220eefe5dbc79b05dffd1246922aaa5ef5ded2f2.nq.gz
    ├── 225dda159532bee948dbfaeac28b2b03839f1daa.nq.gz
    ├── 22739831b909e62cf7b7209a6a9bc30cda81c804.nq.gz
    ├── 241b9e957c09c1639d883447f70aba86dcfc2444.nq.gz
    ├── 24d4726e7e7939b57298118e4f0ef3e3cc6c219c.nq.gz
    ├── 24fb67eab6774cffde5a88735dc28ef309c50e6e.nq.gz
    ├── 2593399d00b97d9070562f981164cfa168d9b895.nq.gz
    ├── 26ee02dfd6817e15bbfe28b1600f3635b2d084e2.nq.gz
    ├── 2715f46c84b21b0afab97f3e2cbd82c8b2ea793e.nq.gz
    ├── 2748f7744ee5840b9370d39433b99499fac96741.nq.gz
    ├── 27dd540c7604c9994617db94809192a39a41886b.nq.gz
    ├── 283ed1a6040dd1abd1fad2591a9dc54fd92f4374.nq.gz
    ├── 2a81b69e404cd53cd76ac525045502d701d60a10.nq.gz
    ├── 2b7a4ea8baf8046982535d144e6d6415be749aa5.nq.gz
    ├── 2b8931df18755ce3bac86c60f585f3e40b9e3b8a.nq.gz
    ├── 2d1077cc687fb13fb72a74413cff437ed360b1dd.nq.gz
    ├── 2d6128a36275337d8015604eb9cc076ce2c91828.nq.gz
    ├── 2dc62d5317b736b3063af17662733fbf9cb405eb.nq.gz
    ├── 302587fd6ebe9a58a8edae52636901699b62ed51.nq.gz
    ├── 30af20de36cada8519d3aed33cc44ea564283626.nq.gz
    ├── 30c52cab881cecedceefa9278234b4c9e9f57118.nq.gz
    ├── 31137873c46ab4015be891437431affb13c5b984.nq.gz
    ├── 318602d841c5c7478ea7ca7ebad8a1bf06aa4425.nq.gz
    ├── 31a0a2a5c8989596b5c87d0611c00adf852892c2.nq.gz
    ├── 31d3a8e0ecbcf2583e67d9862c25e5497822251b.nq.gz
    ├── 325f645608618bd4049a65de190eae353c58a602.nq.gz
    ├── 32d078165e74c72fae4cf678c32787f91c3a50db.nq.gz
    ├── 33b1da8eea4673ee3933d4f45a0f2ee5e37ec6af.nq.gz
    ├── 340bf92ac86ea6413b8e0a72c4d60b0142d0ad8d.nq.gz
    ├── 34780c28731f808179cc4ae3fae4407a0ccf9f2d.nq.gz
    ├── 353e59446e999f93c869c5cf5bb30ee17d5b0723.nq.gz
    ├── 367b79428ecf98bdfd03c261311b93e5ab01e1af.nq.gz
    ├── 367fb81eaf5615a2273c3635cfa5091484b92dad.nq.gz
    ├── 37e953e35d74443cbc25246e82c5346a423aa563.nq.gz
    ├── 3875d97ff7d1b44b65463d39c0be3fd6a56d456a.nq.gz
    ├── 38b973567e4b6ec5d445d7c2541dc33c936df014.nq.gz
    ├── 3ac832c60f49cc7ded1d0ad349f85f186319be22.nq.gz
    ├── 3afac64b6c4c84c479df7fe667d36c46063f9038.nq.gz
    ├── 3b360abd1e53a0645f244d02d690a237a6d8bc72.nq.gz
    ├── 3c30f036645a34ff0c401b9aaf1126dde5311dbd.nq.gz
    ├── 3c7f60218ab6e58a588cfb7b17bbc1129c1a2bd6.nq.gz
    ├── 3cf9ec8ead0b4c2648388d21ea7e24de3160a45c.nq.gz
    ├── 3df8ae11893322b14e66ac387d127615f0b4b35e.nq.gz
    ├── 3e970dfae80f294a5351df699afaa8d99c94bac7.nq.gz
    ├── 3fac5e6e93f2316c0369e8a78cc0bc5e9d354e8b.nq.gz
    ├── 3fb2da56ea4c7946b3e212f98157e79e41a90f58.nq.gz
    ├── 3fcc94cbff1bdb18f9f65e38a8c757edfc183a0c.nq.gz
    ├── 3ff2c95c34e51c60ab3c0c724b414a157bb8d3fa.nq.gz
    ├── 406451e3bb0723df5c9654c2b0b9caf02b0909b5.nq.gz
    ├── 41005c3887e4f2f9c292d6a8214efac425676f53.nq.gz
    ├── 416488cad697c1cada84b700393f0ffaeb66d3b1.nq.gz
    ├── 43f36037a63c659549da1a17a71fd2cebc8c9aee.nq.gz
    ├── 444fd58b695039dfd9e5d995eb7c01985eaf8028.nq.gz
    ├── 456db982dbba0e6e6449f0d0ef73236a48e3a473.nq.gz
    ├── 457289d42e2179f3c977f39d0d827253c5ea8ba7.nq.gz
    ├── 46e2325892f22905e28fb6a0315978320cab498f.nq.gz
    ├── 4830cd929e79adc8da8bc6de6e7f9168c987b7ae.nq.gz
    ├── 48e825447a176eaf3dd403e94f857774718f276d.nq.gz
    ├── 4940a4edc24a57c031444d896dae071835165b3c.nq.gz
    ├── 4964d94ae39a3461dfc0164cc9b138ef671484a5.nq.gz
    ├── 49b474cf8aa67dc1108cabe0bd1179d3805da8f7.nq.gz
    ├── 49e66e025b2da3fe0d66c4843be686a3c6cfd682.nq.gz
    ├── 4a795f609188258004375cf0ac8c24e4a1c0313d.nq.gz
    ├── 4bb77678a58558b808acdbd6ccc2b5b5a047f091.nq.gz
    ├── 4c5bdb747f97b55d4ebf61a738c0038325f13f59.nq.gz
    ├── 4cc6f54512828e78c63857b059972497f43c5b58.nq.gz
    ├── 4ccc618df378cf1eca30b1984d83c32cd21c818d.nq.gz
    ├── 4e122824d3ad16dd6a726abe10f28730cfa5ee7f.nq.gz
    ├── 4e8cb1919f28a16f11a085778fa6cb34f6779686.nq.gz
    ├── 4f4639da776de0da109a6c518e5a2e28ec7879fb.nq.gz
    ├── 51c243bf9a14144cc9469daa0d0e8803f639c173.nq.gz
    ├── 51d40096abc7e6f7256b788e43dc9c3397931073.nq.gz
    ├── 5275328f0f9ebdee0547854bfcbd30b16b4db04d.nq.gz
    ├── 54199b7524f1e9209469c5923873332e25fb8a55.nq.gz
    ├── 5544f0c8feca8903505039d7bf46b3f040729cd3.nq.gz
    ├── 55c720f2670bd93d300d81289986b4f4ccbc9317.nq.gz
    ├── 5601ab11a9aca0df7f0a75c695dc1391759d7ed7.nq.gz
    ├── 56207d317e0e266ebed130b1f53bbdf49b81e599.nq.gz
    ├── 56a4856fc3b60c35940bf28084bbe8249b519ff5.nq.gz
    ├── 56c61bcbbaee46648fbd1017d9694468b83b342d.nq.gz
    ├── 5706985411877cef692406b0011a0bf688cb5ae8.nq.gz
    ├── 57329debf900e51989efe4aaf5a7aef97f9cd872.nq.gz
    ├── 582cc39a9c836e12314e491cd0d5a9b41ab276d3.nq.gz
    ├── 584485a7b0ea6ad8295438c3fb164820a43fb3bb.nq.gz
    ├── 5878013908b302a00bf7d2808bf31751f62da2f5.nq.gz
    ├── 596a6105ce84b39b05b432b6a2686f6d6b86b5e5.nq.gz
    ├── 59ee27fb06cbaad71adebf61782c18d08935f354.nq.gz
    ├── 5afcc09c7bdfdc727cf9f245a908531a05b90334.nq.gz
    ├── 5bfe251f58b3073cfd3551555a053839293b527e.nq.gz
    ├── 5c39df903b9277739d7e6462cf17f5ac3f5f6e4e.nq.gz
    ├── 5de46a491c2fd1cdccf195cde729c87187f7f0cd.nq.gz
    ├── 5f9c297748ebda2d08c10fc67ee06ae6bb76ec35.nq.gz
    ├── 6230f434f0bfb1d8a596d1e8eeb04b5877773f72.nq.gz
    ├── 6256de5accefad377bb3dac2b6badf47e4396653.nq.gz
    ├── 6302f88108dc4ebedde26c72774721fdff93d08a.nq.gz
    ├── 6440457a0533709866653a9575cb2e56689c20be.nq.gz
    ├── 668fe078b1ba720065e9b7b659a946cc530cfd4c.nq.gz
    ├── 669968fd4fbdcb3d25c40931092b32d4dbb7a49e.nq.gz
    ├── 6728ddca851410207629b55dfb5f01066f3d6f6a.nq.gz
    ├── 67793fe8d545c49e7f882dd8dc8a33de02983e7b.nq.gz
    ├── 68ca285c1d936089d90fb9314b713f91fd70e423.nq.gz
    ├── 691142002c7602d3ee78cac244901804cc3685e2.nq.gz
    ├── 69170e8e76d8286c862aec23834b4d8ad82be93c.nq.gz
    ├── 6978d2115479fcc2cb4487d36a06ab7c51376376.nq.gz
    ├── 6aa865c19ab7425f7cde0ee7935e1e8ca23c311a.nq.gz
    ├── 6badcad3065434373f091adca913d26b089786f0.nq.gz
    ├── 6c35880ec549c54b51ee49541cdb4e0315121211.nq.gz
    ├── 6c551017491bb729ad655febdb91990dd7623902.nq.gz
    ├── 6c6c1b130170566469e90f4e08fdbb03dba8adfc.nq.gz
    ├── 6c7808ffd4073313c57e2cc037359f08e7c857ca.nq.gz
    ├── 6d42db00945603ebd382a5e6ec47d001a0fd8f0f.nq.gz
    ├── 6df7dfa988f4990c0e193ec3bb56d409223f09bd.nq.gz
    ├── 6e2b2d97d595525d37fa4e03acc6ae1e54234aa6.nq.gz
    ├── 6fb556975d96ee664cecfe9cacb732b0411ddc93.nq.gz
    ├── 6fc7e6432f27d6592721d2e0aaf5a9206f6bebf6.nq.gz
    ├── 7138420c6e6c7fc25983487893d7bd0d5051206a.nq.gz
    ├── 714252bda9be26291ddf7a12d0e59d1188e5437e.nq.gz
    ├── 7231d70be64399572bdc860ac0ac412c2b095516.nq.gz
    ├── 739c8baa08d829bc1c81dbf72e68b0fc57ffd5cc.nq.gz
    ├── 74a4cb6df903c431d9aee82653b4c6cd9e5e85a4.nq.gz
    ├── 74e6f7cdbf56dae9a6e52464bb61628861d0c6e7.nq.gz
    ├── 7527f4086093bae598d31e2ad49f63d2673bc8e8.nq.gz
    ├── 754688c56cb5a44e84f822d913c943daef83ee2e.nq.gz
    ├── 75fcb6327e984d9b4dfe148e1810bfc458f276c5.nq.gz
    ├── 7638e47447c702a938e5807318fc2399d54b13bd.nq.gz
    ├── 76736294ef0758274abbf6440d4c10a43841cba3.nq.gz
    ├── 7768a885478acd7fea23dcb9339004bc76103dbf.nq.gz
    ├── 77a983e2fa5669a4a92b3c0cbe7be0995e5743ee.nq.gz
    ├── 77f8d94d5818206946fc7de3c46b76adc28202a4.nq.gz
    ├── 7830d797596ae9eefcded34ffbfb72e80cafb7f9.nq.gz
    ├── 7898018f0e78d9b8a11f355f706f2f46d0e1b116.nq.gz
    ├── 78d9736799ed6aef612ff0d90d67e735cfd5b84c.nq.gz
    ├── 794854853d13642b70deef06af0412bf26a8a31d.nq.gz
    ├── 796dad477e870a4405311aeaed72d775e593c148.nq.gz
    ├── 7993d01f0c62f2f05a82c9318b1ac1fa30de49e5.nq.gz
    ├── 7baf699afb6b89a98a80e7ffa103ccb7570e35f4.nq.gz
    ├── 7e51f6ef1ca25fe4891ca377e8ad7c0381447802.nq.gz
    ├── 7e5a763fdd38d1e566d532ca21616811e1f4ff01.nq.gz
    ├── 7e6c6b219c8a29af82a288f1503cd41e3f00e2c7.nq.gz
    ├── 7eec916213b805f493bb395498d12b4b64b513fb.nq.gz
    ├── 7f6f976b81945f35800757b185121a8ec0a15644.nq.gz
    ├── 7ff32f65ca001fb2c0ac57276c5febfa053849f2.nq.gz
    ├── 80650cce7e00ffdde77d70fedf47ac7cc2a64a99.nq.gz
    ├── 81226d8c555c7587d1521a4c4761a9caf727bb46.nq.gz
    ├── 814fb5f454db66fcd19776fbafede8facb7544bb.nq.gz
    ├── 82d841f2d5b11a9e20e27e69067ada946edf613a.nq.gz
    ├── 8370598ef88f8fc22e9409774888b358efbf21dd.nq.gz
    ├── 8566f171949f6e0b7722ff441b0542941870fba7.nq.gz
    ├── 86438c0256b2f922abf41dbf5bb8735be35e9f44.nq.gz
    ├── 86b527f751afc5fd6d0b3a0b69bc6d1a89677dff.nq.gz
    ├── 880c953cba36ab63cc7b67405198d16c91c3695f.nq.gz
    ├── 88d3489891b12d0acae80b88f65b96cebd318c76.nq.gz
    ├── 892a2d833eb7734ffce33f134cd10a8f160baaa5.nq.gz
    ├── 898b385c4190d2b618fbcffdf8a7650e21ed1127.nq.gz
    └── 89b12ad07e97e857f4952a8ee2696c2d31176cb8.nq.gz

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

[fsspec/gcsfs](https://github.com/fsspec/gcsfs)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
