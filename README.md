# Repolex Knowledge Graph of Cysharp/MemoryPack

RDF knowledge graph data for [Cysharp/MemoryPack](https://github.com/Cysharp/MemoryPack), parsed by [repolex](https://repolex.ai).

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
rlex download Cysharp/MemoryPack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eed91b29770697319d9635e246e79bff769d97c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eed91b29770697319d9635e246e79bff769d97c2
│           └── chunk-001.nq.gz
└── blob
    ├── 002cfab543311ec8f502647f85de73d7e9cc91bc.nq.gz
    ├── 009306070a81c2db13112c4e7d5e5daa01b46f61.nq.gz
    ├── 010ff2f8d523fac5979a0e4d186e71c90ae89179.nq.gz
    ├── 03f4b3c0b2971c5e4011af6172d9e8b4af8f3b84.nq.gz
    ├── 04302c842790ae51b86cf34e8e4566ea46d10056.nq.gz
    ├── 056b45549f7389c7e2b46e6a991d08499a857820.nq.gz
    ├── 05e7fd91fe1cc49457f2b6ec829d0fd6ba20b9cb.nq.gz
    ├── 0770c35cd50fbaa01380b6421b18f6b4390daf26.nq.gz
    ├── 07898e78e08290b8e8a4aec5595a5b650ef057ec.nq.gz
    ├── 0806cd142de7f54b72875b2a5251ffb022eda775.nq.gz
    ├── 08098367e5b62020330f2cfea8b49ef8cd4626ae.nq.gz
    ├── 081ec08fb5c31eed45604b9d263fa7c5b7795481.nq.gz
    ├── 082f864308481381395b40a66a4da57bba9a48ba.nq.gz
    ├── 08862ceaa71be4bef81b8aa54cabb06a27a37428.nq.gz
    ├── 08c8cc167d75e76ec0cc75c5bf8505a7625061c4.nq.gz
    ├── 08eec05844ba0ad22596ef2192ab8a5940bd395f.nq.gz
    ├── 08f4a3ae4c861fcce6761055284726fd8ec5389b.nq.gz
    ├── 0991681d56bc921dd112aa3c71b5ba588b6689d1.nq.gz
    ├── 09f7bda7a34b12f46a4bdd508e77f308d5316ac3.nq.gz
    ├── 0a1dd9e70af5485ee2e2d285ee3233227d69214a.nq.gz
    ├── 0a929c18ce5c6261c1dfa5f7535ec9eecd285038.nq.gz
    ├── 0ad9fd395a92dced82335b545adfec9b66048212.nq.gz
    ├── 0aef04e2f8e27b4c8df0e5951b4a020b701aabf2.nq.gz
    ├── 0bce09d9859c5eabdd8d64934b2a31ccedc376d0.nq.gz
    ├── 0c3c9ab54cc0ec1cd33fbcd6cdf2bb7445da6e5d.nq.gz
    ├── 0ce82e91c281bad92628ff757b2e7a253b9337d2.nq.gz
    ├── 0e7491d8ff35ff3a22e83069146a1a3fa127d5b7.nq.gz
    ├── 1095f9f252ff9dfe8b6bb884c37933d35bbefce1.nq.gz
    ├── 12674b08b24c28c6e71d95c595e19c0e8a3b4224.nq.gz
    ├── 127de9f60456ac5f905dfa38a865fef7d88ac976.nq.gz
    ├── 139e7bc16c012f0af094f6516c1b3f7e3cae0a69.nq.gz
    ├── 13c11bb1364e72b7363319b9fe5e2fac093670d3.nq.gz
    ├── 155d6071d421b3694e4c825c2957a1280aef8ce0.nq.gz
    ├── 1607b298106afe755c06a80e3673a041544078d8.nq.gz
    ├── 161929181a0de62374f8503146bea8fecc721cea.nq.gz
    ├── 170ed91715edeb49fd2159eb9713bfb61ae0eec5.nq.gz
    ├── 17b0634b553d0b92fc9ff63b16938e72c355d11d.nq.gz
    ├── 180be3ea5bcf32c23eba6789d7cb41b6a4ea168b.nq.gz
    ├── 187048eb120f6725e46bb4a414a37e3951f0ebf6.nq.gz
    ├── 191da0adc86d5e8c8f6ed70009ff3d6d260b079d.nq.gz
    ├── 1923ca01e6c4980b7f9af401d3c602fc97321d92.nq.gz
    ├── 19763acd5422ee9b48a9f4a2ff137ffdf5dd0122.nq.gz
    ├── 1b9e91bcad425809e8dbdb573ced18b992387b40.nq.gz
    ├── 1c5be0a8f1b6438a9b73326266fe616a7919749e.nq.gz
    ├── 1c86d5f5ebabcf7c9be0377df47ec9d194779d22.nq.gz
    ├── 1c87fbd1dd6e72eadf19a17fd0578fe16c5e7487.nq.gz
    ├── 1c92a7840ec11895c76785f65d949a3d20d53355.nq.gz
    ├── 1cea682d43dfe1fdf2fb92f922f4abd559e2b017.nq.gz
    ├── 1e294a8c5ce8620f94e9a0ffcc2cd5db0170b261.nq.gz
    ├── 1eae6fe0924a56608af10c54b61f4e2839c4381c.nq.gz
    ├── 1fced998a9a8a31e2db043cdd6bc2188d0584340.nq.gz
    ├── 1fe4ad69094159efc6508e5e5b8630be119c479f.nq.gz
    ├── 2052e6d6b84e9afb93d44621057cfebb91095262.nq.gz
    ├── 2059fdcda7f1b88b9595192dcca5dee7b8662803.nq.gz
    ├── 20811d4d89f2973de6ff1d37ba6bac42f3fa8bbf.nq.gz
    ├── 219eb3e1d46b8f7f556296f8cb8b27ad22b9fb0f.nq.gz
    ├── 2238698fe7a12ae5e312ef0e38c855452e0e575e.nq.gz
    ├── 22868baa7983ecd63e2d6ad6f89c97058b004b15.nq.gz
    ├── 22a88ab24554d0fcc64b6fe5cf95836a9bf27fb5.nq.gz
    ├── 22af7e4f673a30a0b8c7b5c10e97b5d512cc7c31.nq.gz
    ├── 22f2f97c427879f3e5c03acf9aef6a33c4fbae70.nq.gz
    ├── 233382a48a920c77e9d7150e8255222efd3392ae.nq.gz
    ├── 23c8ac281e0f3f366ac885580717cb0877e8cb2d.nq.gz
    ├── 2442fde1bd6e8386ed48d76f4405d11f91a147cd.nq.gz
    ├── 24b2e2f7b1cf69a59ab649e429fe95884b4ef9c5.nq.gz
    ├── 2501c74af340ec2fa477c00b393ddb294135b901.nq.gz
    ├── 25786b296955e9997a11908a87708bcbf6089995.nq.gz
    ├── 25a37ec9b7b487c123df2ca7ca0aeeaa2b6e45c3.nq.gz
    ├── 25b07ef8ad3f5b25253e4e44c2bf80936cc26fbe.nq.gz
    ├── 25eb42dcc5abf51e4172b01394a45edca0746570.nq.gz
    ├── 26051501181296036d8986e6e4d2c278a20ce0f7.nq.gz
    ├── 264094a0e72fca903966e44c922f2f9e0a904ced.nq.gz
    ├── 265ea2b24063d1741d6ccad44d8183fc6ce3290f.nq.gz
    ├── 27287fec5f4e4b712cbdd5b3a6383cbfd900b940.nq.gz
    ├── 2753ef2e94ab008a716c10ceda87153eb4219ef7.nq.gz
    ├── 27e986949529fc2aedaae5d4e2bec5606c4056b9.nq.gz
    ├── 28bf50a9c28185580e76c168a6eb242297b17d60.nq.gz
    ├── 290ad4b95427fececbd9a662db479461637be4ea.nq.gz
    ├── 290ff419f5d3260430b37b5c1ebaa37de4cc9aac.nq.gz
    ├── 29b988abc78d483b22bae5b95a737394a11c05ea.nq.gz
    ├── 2a015f966a69f29ae7ad9536a621550dd06064cf.nq.gz
    ├── 2a24e39bc5ffb2c419e88f2f0973c109494b5ec4.nq.gz
    ├── 2ab92428abb6bb1beaa74d6bebf3b6b73203012b.nq.gz
    ├── 2b61c72fab026ad8be56e6ecb509d45bfdd78b19.nq.gz
    ├── 2bf8b3f721204cce4c818204036169e0024ea997.nq.gz
    ├── 2c07005ef40c93fcf592c7c5447870ba649b98a0.nq.gz
    ├── 2c13cb8253a68b4f698b629be9f1e88a6f73614e.nq.gz
    ├── 2c7270f945c271702cdb65364abe2e60e4cab9be.nq.gz
    ├── 2d970c6be7b13358bf681a5171118e044f51b912.nq.gz
    ├── 2da0c97c3fe65bdf4d4489faca6e76aa32c39daa.nq.gz
    ├── 313cbe3e169b5dd7242c0d3fb6f1d8748060ff64.nq.gz
    ├── 317c98c84fbcbd93032db71e3741cd2b4886e205.nq.gz
    ├── 32af017399908c153b7aebde29612b8464ecc76f.nq.gz
    ├── 32f42112b517dbe7289a4b3135daeaa3391bd8d5.nq.gz
    ├── 33f5c3b2633f4c2ea0380cf718da3b9b9ffdf435.nq.gz
    ├── 34c04bbd766f9f49214e4e494affefccf62574f9.nq.gz
    ├── 36383ba04be6c58895abf6a71f9f5d2b859494a3.nq.gz
    ├── 36f41a7b53bdd8d250174436480c07f1cd064360.nq.gz
    ├── 3701324cf12cdea660927d91b93c23fcf8fe792d.nq.gz
    ├── 382845ece67cbd3fcaec31f082912d31fb789d51.nq.gz
    ├── 38b724d823c88b21482fccd0989586d4cbbd3bc5.nq.gz
    ├── 3a348998fc3b6d3696a1f1696fc9c74f31346750.nq.gz
    ├── 3a582dff3a42104c34ce7b2c16fa6cc7c7a621ff.nq.gz
    ├── 3c339b5fb84ec31312036d3b19e07e1b423bfd2f.nq.gz
    ├── 3caa1c58cdf916196124bbbbbcada5baa2b1f15e.nq.gz
    ├── 3ce3eb6950758b6eef76cefe6151744d18f9d1bc.nq.gz
    ├── 3cfa5f90c4b354a316377dbb20fa0f047000d0b8.nq.gz
    ├── 3d74798bbc2662398a9d6d717705ad93fa65686f.nq.gz
    ├── 3d9680485471448bfdcd7b129b16d2c22eb27026.nq.gz
    ├── 3de88b04d9810fef8bcf19c902e8863756d29ca2.nq.gz
    ├── 3fe28dcf249c40d93c35feaaf2b3dc69150bfc27.nq.gz
    ├── 402b3857ce5aa40711ed75a18a716d0dff422da2.nq.gz
    ├── 4142b77546798764daca14a5f5d199961a43696a.nq.gz
    ├── 424ed8c600d5efdf893523b94906bfee74ab8f32.nq.gz
    ├── 4299afe1a2a21a91132491d3dbb22f4f80821518.nq.gz
    ├── 42c83164b1410481bd6a5bc72f51d9d18f8df4b2.nq.gz
    ├── 42d9130a1319eb26b7e747a72f181a1300f1199d.nq.gz
    ├── 4304125db54cefdf2694fe84d9ff893aad7c3122.nq.gz
    ├── 430a001fbb667ee439f1af51b86ec5ad2398e3c0.nq.gz
    ├── 44289cd9b8aca68845c574b84438a68a1bff0d7a.nq.gz
    ├── 44829726772b7b00489599360803391c41bfc93d.nq.gz
    ├── 4495391356eb952287b2c1296424e5bffadfd09d.nq.gz
    ├── 44b7e494aa8c915c82f8afa27c37c4aeecdfdcde.nq.gz
    ├── 45510443cd492b25b293e3bf1f9f8517e983d878.nq.gz
    ├── 460150c8ae411d9ce3fdea2a940e438e42d99ab1.nq.gz
    ├── 463d3e89f892a8c4b94a11ce3bc22091bdb11303.nq.gz
    ├── 467eb75f42604eda3fa0c3f172b8da8a1d2f4598.nq.gz
    ├── 4690ee7e4d9db8ee04de477b18d7cfadbf77c030.nq.gz
    ├── 46ba96612ec31c6cb9534149ef06e73d1d284b81.nq.gz
    ├── 46f38e16ee8dcb4cbdb872f12128bbc1232b1a21.nq.gz
    ├── 48034578c615d51a85af127b393c61c54c2be1cd.nq.gz
    ├── 482590c196f7a82116679f58176b9d1aff21d7f9.nq.gz
    ├── 484835faf5d6a275f9355cecc63cf2c2918499c7.nq.gz
    ├── 491a80a97880de93aa893f6974c5f76891d2de73.nq.gz
    ├── 496164eac6073f9086b89fe9f03a1b3771c85c8b.nq.gz
    ├── 499692dc9a033b30947f4e5dc91586d86f3a4c2c.nq.gz
    ├── 4a6e9e783ccf9e72d55eac02ded2ec6e92ccd9fb.nq.gz
    ├── 4b0737cbc3784e51abaf9d0768f4749c51f4c94b.nq.gz
    ├── 4b6ac675ea6156f7c7fb1eab886cbb0ee47e3357.nq.gz
    ├── 4b871ed5d9c7de5cac32ce6541fcebb2a6b3038b.nq.gz
    ├── 4c24f97b888a6683833cb239e5b9a99136dcd92c.nq.gz
    ├── 4c2603b6c532e79ff905f63653724e3a484d17a7.nq.gz
    ├── 4cf5ad503ca41bf8e933b025183b34ba8186fa99.nq.gz
    ├── 4d456040f603fb51c76ff0032c6b9d018c400399.nq.gz
    ├── 4df7b31ebdb02ea17fa07150ae60a57d2e90622c.nq.gz
    ├── 4e0032a15da5b38c01e2090fe2653e78192f4fd2.nq.gz
    ├── 4f48a29ee6abb61d86ef4a0129f8993685706fc5.nq.gz
    ├── 4f745dedae03f675dc6f6d21147f4f47732cb84d.nq.gz
    ├── 50a77087e303f974bb62d3b01c0c8036f7c1ebde.nq.gz
    ├── 518fdbbb3836e0b94d00b57d1abd52cbe6c20a6c.nq.gz
    ├── 5192502baec5c779d373805b2690018274c178dc.nq.gz
    ├── 521460795b3465b929a777578d658abe509878d7.nq.gz
    ├── 525396c585af4c86ece9248bb6dfad5e39279c93.nq.gz
    ├── 52fc4e2caa5bda23a5f07f7abc0a1823a612aa7e.nq.gz
    ├── 53092eeeff69da15ca050f6bb571bc74a11704ff.nq.gz
    ├── 533bb5133395f29d94e8e5606ee22eb2fbf5a188.nq.gz
    ├── 5420ee4c939b53c16709b60da4c097e8d6a57e87.nq.gz
    ├── 543090533d6257ccc338c1aced2b7c1ea4bab5e9.nq.gz
    ├── 5543bd965c4a05753c3a3aeb96900b406ceedc3c.nq.gz
    ├── 558a017e1f50b2db73414a1abad3c033922774f8.nq.gz
    ├── 558f035bd00a6f02d354dbb8aa43ff6885ac7882.nq.gz
    ├── 55a231b0566fc676d91e6473ee82ecb1094a18ad.nq.gz
    ├── 55dae4dd43e364329aaa176f331325d076af7bcd.nq.gz
    ├── 5705e6597df9e66e9d2d4ebc8457c6c9a13f5bf5.nq.gz
    ├── 57258c666d14f9258498c644e893bdafb39cad0d.nq.gz
    ├── 57481e1ca16972f4c02b304883f713b6f57020c8.nq.gz
    ├── 591e57bf403be4fa44f5a93d4190c385c535592f.nq.gz
    ├── 599bdf2c721396853b5afae210081dc776985f65.nq.gz
    ├── 5a16d80a9aa78592ddc961b1d48b549024a3dbbf.nq.gz
    ├── 5aa2b2cf6674f55e26f0d2650265f5af37c2a326.nq.gz
    ├── 5b5facecace9276319b6e497953ab0429de65b61.nq.gz
    ├── 5bd81430b94298cda516811773f6ad5dfca40799.nq.gz
    ├── 5c57369237d42f3c5dbea8cebf30941cda21bdea.nq.gz
    ├── 5ccbe41552965b6b33f0787958940ca2fd3ff35b.nq.gz
    ├── 5dc6a831d9f2a11f08ed96571e0f602e3c3908b5.nq.gz
    ├── 5e226f9f2ba2ce5f020dbb756b4c02ebc8e1062f.nq.gz
    ├── 5e232dedfae3411d0af80785d2eac5f855a86662.nq.gz
    ├── 5ebbe71619131ff3e65f8271a23497c8fc596aee.nq.gz
    ├── 5ed449cf946366f227d9521b29ac18f79bf3d305.nq.gz
    ├── 5f282702bb03ef11d7184d19c80927b47f919764.nq.gz
    ├── 609d2b0f7593fc123c8a61ff3dd4730d88964db8.nq.gz
    ├── 622f74e0842d23730644440919bb594fe44791e4.nq.gz
    ├── 627362c97cdd42ed62108ca41cfddfcbd0bc1954.nq.gz
    ├── 62b61536d790172d14bebec5cf77e440f72e868b.nq.gz
    ├── 631f1ec3f92a6d944aca47e7ad526cbb641e3525.nq.gz
    ├── 6325523ea84f2d016caf902ddc23596f34519044.nq.gz
    ├── 63cc1d9e8ac2d53aa7cbd37289e76b2e38b70dde.nq.gz
    ├── 63e859b476eff5055e0e557aaa151ca8223fbeef.nq.gz
    ├── 63f3fa85a3de4f98c5540e6b6c158af8b2cd6d99.nq.gz
    ├── 64496e0b333568d2846fc3f48b07bf057037f400.nq.gz
    ├── 644b09ece86383c3890b550cee918f70fa61fe0c.nq.gz
    ├── 650946eb5b070c907fb718a7e0aff90da4586338.nq.gz
    ├── 65913682df90941883c596844f7ab49c406d6d30.nq.gz
    ├── 65e23c069b8e014015c54f515a1a1d723d8b5de6.nq.gz
    ├── 666124095548c8ad57ce1a31ad52709a69c129c8.nq.gz
    ├── 670b814d3331910aaa9674e73027a89bc4722c8c.nq.gz
    ├── 67989da8464acf3275ced10f98a7ca2619934548.nq.gz
    └── 67a7a617646e5afa33444fb114bb013b6bd7e076.nq.gz

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

[Cysharp/MemoryPack](https://github.com/Cysharp/MemoryPack)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
