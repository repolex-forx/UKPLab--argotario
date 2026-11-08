# Repolex Knowledge Graph of UKPLab/argotario

RDF knowledge graph data for [UKPLab/argotario](https://github.com/UKPLab/argotario), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/argotario
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8f4bbf08db1c3e0ef2f836176b4ec52bf72891b2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8f4bbf08db1c3e0ef2f836176b4ec52bf72891b2
│           └── chunk-001.nq.gz
└── blob
    ├── 00736d8326b6ae45d604bf0957c60da816ae6022.nq.gz
    ├── 00eaf5831a761434ab14ac2d20976fcf8e552759.nq.gz
    ├── 01062274b6bf6befe92359c6c622f383a13961c7.nq.gz
    ├── 0111d85b3be41cc4b2ae5c67d21768a0b5c56310.nq.gz
    ├── 0141bfd8099a6fc11a6612321ff9e1efd541440e.nq.gz
    ├── 01dacb769894d86bbb71147dc529c2df8a8caf45.nq.gz
    ├── 01ef340566546cfd7bba2f8e75190809d9b1055d.nq.gz
    ├── 034ca2cc6b70f971a476d77110931dddab756a5f.nq.gz
    ├── 03610d27eefc077607223a8df5f3dcb1887c1df1.nq.gz
    ├── 046d22f9c883cd75a36f4bd4e6fb506b5530640d.nq.gz
    ├── 054d94e5307987af3d8b6f3f423ba909d1544c90.nq.gz
    ├── 05800ff26bdde8b56f1f80b1553c987cfbaa65e0.nq.gz
    ├── 0653b978c0fb4c28e00ee682a97642a5cac2be64.nq.gz
    ├── 0715e01ad8d5dd12173e42f6c1bf6245ba096d73.nq.gz
    ├── 07321dc73dbfba0b660d2b3034e9f40a10f9963b.nq.gz
    ├── 07661bb6f8d7f7d9cbbbadf23ce2aaa7cefde75b.nq.gz
    ├── 07ae7e0c67422d131c5fbd3e1a91c95946adce6c.nq.gz
    ├── 07d26c2cb91f72144f6bc2e19c539cfcf101dffc.nq.gz
    ├── 07dfa85cc81abc3d0153110265b4f7537d58e07b.nq.gz
    ├── 080df3bae3b2c6b2f597517fd808c7ddf4f667a2.nq.gz
    ├── 098c78fd35a8ed64aad4d6d5add95d78cb569357.nq.gz
    ├── 09bee2ad545ec85544ae79045ee37f2e0cce51c6.nq.gz
    ├── 0a7b5f829bf95130415104ab9db82958116e2afb.nq.gz
    ├── 0b4ee37c188bc8abb361e89e3d378a9e4c96909f.nq.gz
    ├── 0bf122d1424b6ee3d4f504fdd37a7537a5ceff3c.nq.gz
    ├── 0c64511829216a18d9dd65cfa39447f1ddf5fb34.nq.gz
    ├── 0c91a255be6570c0608d7582d31e33b10bb71f5c.nq.gz
    ├── 0d7724932633670237cba8265b2dc08e8dfc8aeb.nq.gz
    ├── 12361431cb2f387d0bf444c6f764e0e991bd65a5.nq.gz
    ├── 124e21184b167793210f8048ec4c32e4e729bea0.nq.gz
    ├── 128f8e4efe6577013ba61ba3251e3369029ca4a3.nq.gz
    ├── 130484537ea9a5de477a6072647e6bf61f97801a.nq.gz
    ├── 13511ad86b41b0bdcd682097462370104b2592b1.nq.gz
    ├── 135916004abe54ab1aeebfbdfefeddca536f18de.nq.gz
    ├── 13b55928da70a38ac834f729e3a9971ce272d1ed.nq.gz
    ├── 140ca8a4f992cf875d3a75fc73bb5d30af386eb9.nq.gz
    ├── 157a9a3f02bf917fd47a63c7ec3aafd2f62a1897.nq.gz
    ├── 1587b991b8736830ca7eda91dd7155d07dfcb66f.nq.gz
    ├── 15d50af6a1c4dabe9602035d32c55c0d56e993a1.nq.gz
    ├── 1653281767d3f044e4d644f067cef676054e01b9.nq.gz
    ├── 16859fdb7e2169446b3b4d14ca81883e966c936e.nq.gz
    ├── 16fa3fa675a51ffb6ce5da839d791133f6693a87.nq.gz
    ├── 179bd483c4d6c6ddef888a0745a9ae21d24c59ce.nq.gz
    ├── 17a46829ff02262fcbd4c415617b1903e9fcfc98.nq.gz
    ├── 19771488d6b632c7e627d005439a025f5b739f75.nq.gz
    ├── 1996fb29d68034b8fbeaee879bf926a8129872d9.nq.gz
    ├── 199e3c45f9b437e3956d020e955f0eabfb9f5a16.nq.gz
    ├── 1a96029dc632373e72d25a7126c1199ad2531cc1.nq.gz
    ├── 1aaeba4110fb7ee9e1f749d194da6ddab2dae556.nq.gz
    ├── 1bbecc77502394824c4fd48c8f1bb02e9a3e2407.nq.gz
    ├── 1bef2f8382e285e551f8c94e4fe90b61a9f041b9.nq.gz
    ├── 1ca1cd4bf732d46d5c6fb5f4694aff548b3c0fd1.nq.gz
    ├── 1cc33ab77cc3c859edd1869d28529cb73d7c999a.nq.gz
    ├── 1cf58ed398b351dc40add1b3bad5fe795b0e76b4.nq.gz
    ├── 1e0205d5bac9d2b6e5f0589f14ae4713fd42f62f.nq.gz
    ├── 1ea45906161ea2c12ce6e048442d5e35a488e570.nq.gz
    ├── 1f14090583769cc36d94c66b20b37f50c1cfb1bf.nq.gz
    ├── 1f17ad325c33602edf7bdcbdc5bc0dd7b26d959e.nq.gz
    ├── 20a258da3e7305d4b8ee64456d5f8f8a2ca97f90.nq.gz
    ├── 218ecce1751b27bc0ff21a6fa80dad23e34fed1a.nq.gz
    ├── 21b3bf6340c243b25257f5730500f78a40c66f9c.nq.gz
    ├── 22344f08f08c567b0ae2d3aef4df64f98fdcd618.nq.gz
    ├── 22be5dbadf6c5d11be0343bcbb818a639590a564.nq.gz
    ├── 2385562a7139568f77ca3b87dfc1faaf136bd27d.nq.gz
    ├── 241fb5507fbb51b4d7a313e4511e49a272407622.nq.gz
    ├── 24ddd8c34f760371f978a226924e50debb95df04.nq.gz
    ├── 25d0159b88390bef686a2b40d9201af9e8cf2675.nq.gz
    ├── 26b2e39a1a681b464c5e3a4682efba7b7fc811e3.nq.gz
    ├── 2754a6a3bb6d3becc78fecfdb2f5c7a855d579fc.nq.gz
    ├── 27a9ed04bd8085b6734f23565253da0fd18a7625.nq.gz
    ├── 27d49a2b7e7c5c9a3057c2fe19dcb9451999ca04.nq.gz
    ├── 28c9a2bad6ad384eeb334b0376453ed026a931b4.nq.gz
    ├── 29b5af638c2c8cc993f346f49f549bbb4f2a06fa.nq.gz
    ├── 29eb21e35f79fef7ebae7d8a2f44e67984ee4d6b.nq.gz
    ├── 2a578357f9dea21aa8334887a3deb7ace49818e7.nq.gz
    ├── 2b22937622a4b1c0adf26f6cc120cde0fa74071c.nq.gz
    ├── 2ccf17f3fb3252aaa66cf31f5fd524ae19e7a052.nq.gz
    ├── 2cf2b9f566e388dfd438c95701df5aee6279104a.nq.gz
    ├── 2e661ccaa8ef9f9eae611ea78c2f432abb4d17a1.nq.gz
    ├── 2ee92f851d59e2e0163bf9b6593268860aa18bd6.nq.gz
    ├── 2f03f7c409618b185026f952972ee07e76637272.nq.gz
    ├── 2f318ca743d0c6776ad634e4563b8dcac593c34e.nq.gz
    ├── 2f477077fd94094e3039fce9657717f01220401b.nq.gz
    ├── 2f68876c6a2bc863c00ca29d1e8841e10cfbf778.nq.gz
    ├── 2fadf062809f8b6ace30b4ced57f0a5b7a9d8c8b.nq.gz
    ├── 3020b23b6d9583608ccab5292430636dcec8634b.nq.gz
    ├── 30fca2583e051a430d74fbd1df167ffe77f4dfce.nq.gz
    ├── 31630f4e158b00e84436ebc4a816ff60c32a2fc1.nq.gz
    ├── 3217d78b2ff51a1e366d2575536c9981702a0c04.nq.gz
    ├── 329e504d69def9e3cc2b0e98836ce15d73297854.nq.gz
    ├── 32b5aad02653dff2e6aacce869acb66a648471f9.nq.gz
    ├── 331c545b8cb07a97ee63cb4f1256d1dba5557a82.nq.gz
    ├── 338addd7859275f35f1e898815ca026af47fb55a.nq.gz
    ├── 33d9b64df24a61181897d6c26669424ef7d12bc3.nq.gz
    ├── 33ff0318d6f4ca55474f91d8dba19ef67837c65f.nq.gz
    ├── 3421e38a1e1f198540b8367f1e3574feaba25f1d.nq.gz
    ├── 34930ba04025b4163020a3ca7d81ec28bb355b90.nq.gz
    ├── 36a7f81c0ae38e4633f821042666bd44576bafa2.nq.gz
    ├── 36af2094a9b68be224e7c2f4dd5ee6b81e9d69da.nq.gz
    ├── 372e864f057e9e5f87e0f12e5cd83a9a9518bd18.nq.gz
    ├── 37cf101f9a8b1dc822b63cdebecd7191e20d38c5.nq.gz
    ├── 380cc5b34d028262e34ad15eeeb43ab80af18412.nq.gz
    ├── 38e9b5c3b7fe1cf41fb59197bacd50c3131f0492.nq.gz
    ├── 3a1540c52e45ba976435a220dc583d45e45280cb.nq.gz
    ├── 3a2f1311473921edd60bebfee0c059a864ad0766.nq.gz
    ├── 3a9dcd2a49da6a9224ae1c1c750114d32665e9f4.nq.gz
    ├── 3b4091bf00d6474dd5ee8c1bb75843a9b4e8f690.nq.gz
    ├── 3b44b79bb5e851f18f6571d6eb3471e33820a9ad.nq.gz
    ├── 3c67906cdc138eff8c6f0a09108fe10dd5107666.nq.gz
    ├── 3c8803a77c554c15e91b154e0497dc7841750179.nq.gz
    ├── 3f6e41c8805ad7431d5ea4a486b286ef063c8ff8.nq.gz
    ├── 3fb7ae607b577aa5a0ff000383d22b6070716404.nq.gz
    ├── 405915783a6316e0a1c0cc7f3f5bbcbadad78836.nq.gz
    ├── 4062f5f0ff506ef4e513495595bef19b7133c4dd.nq.gz
    ├── 40dabbc446c1868166ca6bbfb7cbda01c0127ca9.nq.gz
    ├── 40f631b7b2e7b099f2117c25618e19bf3651c7cb.nq.gz
    ├── 42018a5f790e4ca2a4f709cf582f7aeec7159f4d.nq.gz
    ├── 4240e9cb86eaa2becd4ef67c5076ab70fec7879d.nq.gz
    ├── 4278df8c2cca3e898207d48b74c1cf91bafb1f83.nq.gz
    ├── 42a34ea2619f30b7b14b7d485faadb2ab2390c18.nq.gz
    ├── 42d5807a83af90abe418537b2b85dad0bc206631.nq.gz
    ├── 43857564dba83c825c550eb2b168dfaef7c81b89.nq.gz
    ├── 43b8fd680519600ae489e8a1d8f29b753a8945ce.nq.gz
    ├── 440fd9d4057f87503c98033e4ba99f55a516d3f3.nq.gz
    ├── 44b3c09444daaf918102cbabcc8f642bf6baff3d.nq.gz
    ├── 44c72cf6a51734f9a09b23c216cf9345a0a89642.nq.gz
    ├── 453cbb6fa08dae94c1095ce70f4e5f96b83a4b58.nq.gz
    ├── 45a3d780d95a052de3ae732963fffcaea399e34d.nq.gz
    ├── 45fba49da56f579df14617335867459c508af7f9.nq.gz
    ├── 4709ceb5471e7fce20262f43cc0844a7b852e8b3.nq.gz
    ├── 47365a300110db23c24d8471b4412cff3299335e.nq.gz
    ├── 477edd2cfcb343b340e27d22956e09266a725de4.nq.gz
    ├── 4869ed6f95d4cfc69c98ad2f81cfa80e5149dbbe.nq.gz
    ├── 48a2a5bbf3e22c2ab0799f0582f9c6307c90bcea.nq.gz
    ├── 48b3074837aee7e2a9abd044b45277ff98c25a9e.nq.gz
    ├── 48f40046d11596513fae6d16832667931a5c3991.nq.gz
    ├── 49e706aab51624ba1d3d872e42cd6e6945745f47.nq.gz
    ├── 49fc8f367404798ee10aac4f1f2a5b38498fe625.nq.gz
    ├── 4a39573b9263bb866227cb3ffb0e066f31763f9c.nq.gz
    ├── 4a3adab4d5421be2ee8cc14ff2df5fc8d6fc1228.nq.gz
    ├── 4a3edde92285a3a4912bbc0d5a810e6340d508d0.nq.gz
    ├── 4ad2df42755874f331733cfab5ad0931d5baf0a1.nq.gz
    ├── 4b4683cc084944fc9d153084645da69a79a9059a.nq.gz
    ├── 4b5d091a1f04e49593244b7c9e49caaebacb8ed6.nq.gz
    ├── 4bf6517854e8f4748ecd65b3490ddf1498be1f51.nq.gz
    ├── 4cd0458b93ac966fc82b179dce297941e8dd5b03.nq.gz
    ├── 4cee31418b3084991a8bd0af152d26da1b7332ab.nq.gz
    ├── 4cf6b802a58c8b6571691ae45ddd4d4d202b6425.nq.gz
    ├── 4cf8a666e64d997f1160175b2fac7511134c8d29.nq.gz
    ├── 4d7fcdd5e2fa9a43bdcac15f1439aae5936ca7ff.nq.gz
    ├── 4d882803fc4bfd0665a8a70a2485001b26a37e55.nq.gz
    ├── 4d9d527dd117428fdcee1c4a1f81e5a41a68eb08.nq.gz
    ├── 4dbf359c7a80d81ddfaca7f3a5fbd3b25726f3cb.nq.gz
    ├── 4df97babceb70beec4023af6840de0c56185bd72.nq.gz
    ├── 4f103aee6ffceafc639108773b7258d0c2a1b7f3.nq.gz
    ├── 4fd48dff5e567b7ab18292e67a3685fad6c20aeb.nq.gz
    ├── 50a6fb943e04fafa09e11dc147ccee71ea6bf701.nq.gz
    ├── 51f0da24da023cc2c4b9413c35ae4df374c2fa77.nq.gz
    ├── 52345898a20b5823329ef6f6458d19ad8fccf68d.nq.gz
    ├── 53f0ee818c4e1a492e02f370ef292caf681ba09a.nq.gz
    ├── 53ff44f2aef1e38f95e8305752f57b681d0f6a45.nq.gz
    ├── 540f13cdba90365d7c4028c3c2958ad26ece1637.nq.gz
    ├── 5439747bb893d27664b8f18f4317764f56c65ffd.nq.gz
    ├── 55c5d5e07fc2745b7f5f884d7d362ddd1911c6f2.nq.gz
    ├── 562c97bf898f1acbf96530e0cdfedb28808b98c4.nq.gz
    ├── 5637ae2ee5195798bb87e03e4bbf7005344f4e7c.nq.gz
    ├── 5698fde6c90e0998c632eafc3d934e2d1f2e88b6.nq.gz
    ├── 56e00d6c951be895f4e2f5c103888f4ccc06091b.nq.gz
    ├── 5762c7468dc1a1998d9d8d602e7ab5e5cada0c50.nq.gz
    ├── 57b7075ea77972022b29567068b1263b8065fb03.nq.gz
    ├── 57ef479ac2af04188cbb43507a2a5bcbce4bc272.nq.gz
    ├── 5813d91b275690813ad1c27f34ade03bf2867510.nq.gz
    ├── 585e76e2290c09bac9e17522095038e1400fc3ff.nq.gz
    ├── 58bfd88e7a1dfc21a79d05da5f8a5cba81920db2.nq.gz
    ├── 58e9e1aabbfe128134fcc95ce32200c0228ae6c5.nq.gz
    ├── 59b418110d79bedae65e32c97245a5344bdf711c.nq.gz
    ├── 59bb742bc631716bf0855babe3ff0eb37299e670.nq.gz
    ├── 5a052bcda4ebaa8480da994e2b33d39289d574eb.nq.gz
    ├── 5a4be2b7a988ccd5352b98457324881c5d4de5c4.nq.gz
    ├── 5a9adec118620de7ae3fd595972954b012bd49ad.nq.gz
    ├── 5acf8127a2a09c4e07fbc97ecc64ff1b2adb8343.nq.gz
    ├── 5af16c8d871e6bdbbaaa87182ae3863e74394b42.nq.gz
    ├── 5d291f7a368aac947b1b142aaa3830c3a5e15cd8.nq.gz
    ├── 5d30ef74d7bc7a1b2461b3ecef8e6b95bb585ecc.nq.gz
    ├── 5d334cbc5e6b914ad2a1aa1c5a15b7c1fa8de0d0.nq.gz
    ├── 5e053339552fcfbe061bef25bf3825424d093af1.nq.gz
    ├── 5f0500e06f6303903eb9f546091db276bd808610.nq.gz
    ├── 5f4b83be418329cb9210d47144b672913fa3c769.nq.gz
    ├── 5f95320f1f7dfcf7e43312899103dbc17e6c1b60.nq.gz
    ├── 5ff58adab8255c8b1a44da1d8938713cf6311f9c.nq.gz
    ├── 60294d33a76ac4ca0ee3bad0426a587e9f3f9dcc.nq.gz
    ├── 6076ef09ee7fe65c182736c2e6dd99cfeb245d2e.nq.gz
    ├── 61110122c339d4f91e977a552d659d56171abaeb.nq.gz
    ├── 6143f5b5ace6f2d2bfa2c0514c9e0df0bf89432d.nq.gz
    ├── 614f6b4e442e7e83622ab28833d24ac92ffd3979.nq.gz
    ├── 61577029688d4060dce77adb2800a96e01fcce33.nq.gz
    ├── 61d2bfca2a6fe535fd12c84366881f6f42c5b1f2.nq.gz
    └── 62a0c739f87a798e4e4a1aec65b386d62c063b12.nq.gz

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

[UKPLab/argotario](https://github.com/UKPLab/argotario)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
