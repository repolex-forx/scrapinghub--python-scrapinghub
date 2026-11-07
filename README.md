# Repolex Knowledge Graph of scrapinghub/python-scrapinghub

RDF knowledge graph data for [scrapinghub/python-scrapinghub](https://github.com/scrapinghub/python-scrapinghub), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/python-scrapinghub
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c60ab4620f67f302a5685e30674fdf41c281af39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c60ab4620f67f302a5685e30674fdf41c281af39
│           └── chunk-001.nq.gz
└── blob
    ├── 03772bd481d44e6eef42b403a3eff3a4941ae9fe.nq.gz
    ├── 042a98af95f9fd23f12d6750fc9d74fd78580270.nq.gz
    ├── 0562b06790242ca052d3924400aed61cf19a8792.nq.gz
    ├── 060327218ea001b41a6d4ffdce228581b9432b7c.nq.gz
    ├── 063f53038635abd2be97d2ccf3be38e5e25bbc62.nq.gz
    ├── 0e6cc570b398e455461139f64069d1a800040d51.nq.gz
    ├── 0f0abe1e0e6e02c35ff41aa12a67c90803ad4c8b.nq.gz
    ├── 0f8f98e2ee9019506d131752d48280084ca52ee0.nq.gz
    ├── 100a09fb801c54e6eae6fe78aa6bf6d1c7185756.nq.gz
    ├── 103f178e13612cb33e26521d7e17ebcd7d568ffb.nq.gz
    ├── 11e53351f38efeed600557b09ebbb8a17f02803e.nq.gz
    ├── 13ed2f727264e33e13114dca9e1d1c8b99d06dfd.nq.gz
    ├── 148222b7b803e78aff3c12b9ad19b2bec18b5786.nq.gz
    ├── 151ee83b9141c7d338a24c965415cd93f7dd0517.nq.gz
    ├── 1572ddaf04966a11345a230029c839692774bf6a.nq.gz
    ├── 17798ca658192e1c3065e3015391fd94f64e1e5f.nq.gz
    ├── 1920f783ae3ccf3622747a47ca3cebe82340ca40.nq.gz
    ├── 1c200032ddfc2c42e28567afbff955cb2455f7b7.nq.gz
    ├── 1c7573cd54afc1db34a6fdff0d9d90e260f05e8d.nq.gz
    ├── 1cb7bf986be14b392b5d4eb237388a2b362682ad.nq.gz
    ├── 1d665801176e20989d63562a28612cb0f82cb5b2.nq.gz
    ├── 1db07d3dfde55775161d54509c6cc5cbb0d35671.nq.gz
    ├── 1e522d9ef239c29042878d7abaa7ec62fedb055d.nq.gz
    ├── 1f18cc199515a9d0a828deccb89b23f03d76f0a8.nq.gz
    ├── 1ff227ea3b283fc49e09a8db590139896f13140f.nq.gz
    ├── 2143c002f76aa1f15d8db5c4ae6671a169c625ee.nq.gz
    ├── 21a5762a0c7cfd9a130cd1d49c5f4329c98c7760.nq.gz
    ├── 24e4681d159e54e8199377fb8186e4687503184c.nq.gz
    ├── 2ba3d9042e846f1b459a92069ce7497eb82b02aa.nq.gz
    ├── 2d8241229535583dc970fbe252f6823c3547f80c.nq.gz
    ├── 2e8aa61ee71b3078148e530066f60a0bff3d9b8e.nq.gz
    ├── 2f1696b116468ef3ec9b2df09ed40e997c10f05f.nq.gz
    ├── 2f485f59938fef8dbd99e25575a5bfd03992df33.nq.gz
    ├── 2f98f42872a9e49e5e7d82c61d7d619877e8b639.nq.gz
    ├── 30789185ef8e6e7c347b2f010be275e98ab434f4.nq.gz
    ├── 3101cc8fc23245d01eb02f8ed49defcc45d2f570.nq.gz
    ├── 3141b0dae8291bdebd130cb36396d2c240a6c7e6.nq.gz
    ├── 315ea18409f97b318da962fe906949a9a0d81e4c.nq.gz
    ├── 31b4929cf62d07d089a8522ddf240f9370ea9141.nq.gz
    ├── 32698e12353e080a14c688bcae460896095911cb.nq.gz
    ├── 34004bfe1f2a2518bc2d75e49306f23f91e24170.nq.gz
    ├── 34c6878889d9cc59f8b95dd87516e3678d59fbe1.nq.gz
    ├── 368984c94c266f9b91454191b0294bb4332357a0.nq.gz
    ├── 37d914e6d3f841bcf2ca2f8898232aa0535bed6f.nq.gz
    ├── 38298a0bb85abbdf30b88f6cf141351d9850639a.nq.gz
    ├── 3a9b0fab227f1b52c504e3bad6cbcbd3e0464109.nq.gz
    ├── 3ab37e96b99adb4585b1a7c9cd09b241c57e072e.nq.gz
    ├── 3ad4f7a75e1a5dbb791245b7cde4720423c73cef.nq.gz
    ├── 3ad8f545873e583641b2be5fdba3749717a5ab59.nq.gz
    ├── 3ff2304642675f40d54fe9743e2635de53b31aa2.nq.gz
    ├── 40c4f53db2e44cb9729dc3a3c31953ffc2d7b2ab.nq.gz
    ├── 410ff77364343a4feb8330b2baba30a27d7dc2d4.nq.gz
    ├── 411979cac2649099cf7f730bf3fb4c5147c86c1a.nq.gz
    ├── 41e10362b4cb7d629fa755eac94ed129b00b4aa7.nq.gz
    ├── 435bee243527fbc6601ff7ac3ba08ef7be48c725.nq.gz
    ├── 43b34f8aa3525bc336a4f096c8601979c61184b1.nq.gz
    ├── 43b4966e6af6fe6bcb6f6ae330b996d9555a3b5a.nq.gz
    ├── 4473b748c6b3f0b8988aa982d810c809c5e6052f.nq.gz
    ├── 447cac896f87c7cc901c51e168cdd2210005785d.nq.gz
    ├── 462108832a702beac4c1a0ac44efd31f2c7be9e0.nq.gz
    ├── 4687931ac7b207f8b783a96fa07274be1664973b.nq.gz
    ├── 473ac6f3252ff6cff27edcfd56cca2365c0613d6.nq.gz
    ├── 4818b19ac08b1ab4a23d0f5ddbd768e2b057aecf.nq.gz
    ├── 487a1e4388bb51f7af7d0723f876e54bc69b63a7.nq.gz
    ├── 48ca283224ca699767c9e12f650c2b04a5c5aacd.nq.gz
    ├── 48fa35c37735b8e1342fbe4560fcbc0019225818.nq.gz
    ├── 4935d05ba49f56a479048f950d590b2b02d0a15d.nq.gz
    ├── 4c20bcfbdab76f948e2eb32c0e17dc416f4ee7f4.nq.gz
    ├── 4d849e4be45f33486ebe50cfe66bd66113235600.nq.gz
    ├── 4db52917211a9c3051d483214a559e986d71d581.nq.gz
    ├── 4dd2ef169f0bd0efe2d5c1c498f78423f8f0d843.nq.gz
    ├── 4f6c9438e406d3f1cbe5fee028db620b5bd5eaac.nq.gz
    ├── 528ad2136f5a152320a2962584d5169080368cae.nq.gz
    ├── 528de0fbe1577e6ca2fc975c92c06b236904ce23.nq.gz
    ├── 52cda91b0c669dd40fe06f8173419035f8492803.nq.gz
    ├── 544f2385d7fa2b73ecef09c176ee63cd719e1185.nq.gz
    ├── 54cd3110792b28aedf4dd438d17707286ded10d7.nq.gz
    ├── 550c99184658867e18bc2b938c5cbce4183c509b.nq.gz
    ├── 553f882d6edb5f5f32a2b76bba8d3e3449874b14.nq.gz
    ├── 5562fc95fc140aee061b3716f77ab6d21e357fea.nq.gz
    ├── 5593ec549d4891306d229288eb43231234b4ae59.nq.gz
    ├── 59ad94f24cb396c3e4e5929e51a9794fa5c60d33.nq.gz
    ├── 5b6781d5d43fbd4ec91778df61f709af9f983ac6.nq.gz
    ├── 5bd464b0f0305db09fe7a08148a099ce4c723ddc.nq.gz
    ├── 5bd9b394d4a8bfe877aa6dcdf38c283ec45377dc.nq.gz
    ├── 5cede667f10ddc5bac90d28f7b830db641dd37af.nq.gz
    ├── 5d09cc03ffe4e843d668573d735963fc6c4171d9.nq.gz
    ├── 5d61e6bf72a66d2a26928db0ab46684aaa3a7581.nq.gz
    ├── 5ddc4e1c5da962158df1264b713983fa7e45eccf.nq.gz
    ├── 5e7efacdfd3d7df0103d4565ce3e33d7df9edec0.nq.gz
    ├── 5ee28d27487d4aa88ca7001ee91dbb04e05e13c3.nq.gz
    ├── 5f06e1a92a9e72a47951995da6df8e88e3656363.nq.gz
    ├── 60aee845473021f7789fd99e365de6def432bb1e.nq.gz
    ├── 61a3b39599eb62d59575d686ac642c798e5e4e18.nq.gz
    ├── 62801605e159751fbf0a913ae4590a8571b9c2fa.nq.gz
    ├── 631fdb837c3c77cbfc4c5eed83a4353900cd8f83.nq.gz
    ├── 63d1b160952b9cd0638dfab76af72bf80055d7d3.nq.gz
    ├── 658c7985e587baec09b49cd7417d6a6901600b03.nq.gz
    ├── 65eb831e4643a0e79a22abd90ad0b461347f7f70.nq.gz
    ├── 65fec968e2d88f4aa017b18b3d683f2306340cce.nq.gz
    ├── 669a0dccfa56aaac3f328932f474f8d6bdad301b.nq.gz
    ├── 6b158f916940ea51dd0094a0d9a3c4cca47fe9df.nq.gz
    ├── 6ba431d832fce8b721f619a79ca314abda2912f0.nq.gz
    ├── 6c964759698c3cd4f22e10181ef7b8880f02c119.nq.gz
    ├── 6dcd1b958e52ce95930575557d31810966b8eaa2.nq.gz
    ├── 6ede3546fcea02d71c4c5ce120d725040f9d79a9.nq.gz
    ├── 6ee3c3cb8917d0ad6e5943b976a258cf9d8bfa67.nq.gz
    ├── 6f31eb8afa090aa074b949f63c203f9675ebd71b.nq.gz
    ├── 6f5ff7db81f8dfeba1801aafe36adff4d2b28909.nq.gz
    ├── 6f9a32ba41f01591499015e6b6ec55eea3db5125.nq.gz
    ├── 705678051a0e416b9b8665162a4583fd7d4810bc.nq.gz
    ├── 707a50cfe969824162ab6a6c270c937af42d567c.nq.gz
    ├── 715deee302e906dd123de7a4def95137f0ec32c4.nq.gz
    ├── 72d2a5567617e40a81cf1bf17acf02d7c62c4da5.nq.gz
    ├── 738df844cc50a50bbfa56bca289bd1e51369ad37.nq.gz
    ├── 73ae1958fbbc471f3791e153921c384507df55a2.nq.gz
    ├── 75c0c196c66c04af5481348b71d22c9782cf3a01.nq.gz
    ├── 75d0acbc9e2d564af313790d80cc1dcf63b81756.nq.gz
    ├── 77093c18d6164f20c3dc24e77fdb20b07cf11c45.nq.gz
    ├── 775d8fb8b648b56bf584f498c69439a20d1b8824.nq.gz
    ├── 795da1e925df9c0bbbf295fefc49573e956f2508.nq.gz
    ├── 79f68c33bfafe8b006d26a422536a1fd2cf2d942.nq.gz
    ├── 7a397bc24049ef920cb3aec8db12c3eaee72b2bd.nq.gz
    ├── 7b42bc5336fc5d628558408f5d56acf563398aee.nq.gz
    ├── 7c36d12af4f5012fe91ce0891e456bbcf6ed15e6.nq.gz
    ├── 7e517caa4c225e6d4bb80248b54c290dd46fd089.nq.gz
    ├── 813f4b27255f10b43286b2641f401ae30cc7b14c.nq.gz
    ├── 82917081f58725aa6cc4ff0d18dc7627e64d692e.nq.gz
    ├── 854d3f327b5690c5b750e4cef5e0b097c33ad70b.nq.gz
    ├── 87a8e9bc833997a1ce6aedd554f133f0fca4d173.nq.gz
    ├── 89fdc2c1c6e87b9a3897769a383651599b772e44.nq.gz
    ├── 8a2e253a1940611b258f949c70886b4d65cdb3b0.nq.gz
    ├── 8ac29f8ed3ee67d783906f08cb5ef1c54e886d10.nq.gz
    ├── 8b4ec85863599775472650d846bc4b9eabda21da.nq.gz
    ├── 8b98867bc614c9a8b631d9b17ee4ceee615293e8.nq.gz
    ├── 8bc412786fd3f6024350af44aad9dc869a54ea9e.nq.gz
    ├── 8bc64aebc3c347593b3c465a6b32732bbdd85d32.nq.gz
    ├── 8c78e4f9a62374f88383750bf120447eb6ab6134.nq.gz
    ├── 8cf2c836b934b706e51747fb8fa5fc8824c2578c.nq.gz
    ├── 8d253c0d1ba3f2a9cd816249b5671dbe61622e0a.nq.gz
    ├── 8ed506c0631b71372ae7658eb437bc71730507c3.nq.gz
    ├── 927193a61e43e527b97fdd8779be3d6fadae4264.nq.gz
    ├── 92c4f12c8272b2b32e365074da18edeb192feda1.nq.gz
    ├── 9472683f1ebaba9a745471f60cb2ea352ec51da3.nq.gz
    ├── 94851609d0fbd9cf274e27d84caf15d5d6d7bfa5.nq.gz
    ├── 956ee487121fcbda9068c004f0d93b0bc4fead00.nq.gz
    ├── 97be5fa7c573e5342fa0710b837b882719d9aa9f.nq.gz
    ├── 9853c9cc43f121992a97655b53ae16ef5d93db10.nq.gz
    ├── 985b50485e55ff9d2ab968b3cafe51cbf48336f6.nq.gz
    ├── 9ac2e3c938cfe1636b1d9a7e944bd4bc018998bb.nq.gz
    ├── 9cdc061bb1e869cb1c9ad6808809b0d6d849b676.nq.gz
    ├── 9da0e450c580fa33942fdf6e56c941eeb54460f9.nq.gz
    ├── 9f126027dbec6e470872ccc28af456f2ee3abe79.nq.gz
    ├── a05e2cbf8c8e4343a9f5423ed4ad65a1ff84e3af.nq.gz
    ├── a2e54433ecca2d309630c5c72a870e75dcbf0323.nq.gz
    ├── a320f4abd478cdd487839cc8a72be8a2d71eb832.nq.gz
    ├── a4f434d8381ac64ef7db97417bc5af228d45ac11.nq.gz
    ├── a5d1ec8e67ccdd917a9999ee03fabe4bfaf26118.nq.gz
    ├── a67f32667e9851406017b54b5139743fedcdfe8d.nq.gz
    ├── a9c55fee3968cb7ea33bad7b8be7ba147da907de.nq.gz
    ├── aa4bb62e90b3a0a6b567cec6c30be4734c3b4087.nq.gz
    ├── acacfdacf06ad28eae342b9d8ad229308710e3f8.nq.gz
    ├── ad9c7f46e7c7cf9259dca163c8b6ac5c01c5e30a.nq.gz
    ├── b002696a86521fb9fb6ea51e17a0b42f10390972.nq.gz
    ├── b110f596357f80270f1a59065251d8cf02a46b2d.nq.gz
    ├── b1b8e3b7332a512a18d1c8104d367c15e99571f6.nq.gz
    ├── b20cffb7a184ea221d24c6a816289199e70a8d5d.nq.gz
    ├── b29e454528f138a17c12026afdb1c958bb21766a.nq.gz
    ├── b34c8ebb1f96824ce62a94dc647a08181b16211c.nq.gz
    ├── b5d1777fb0af216cb9d360df1614d59d1043c431.nq.gz
    ├── b5ec68fe188f7d9f7faa0eae040ec1e7064b77ad.nq.gz
    ├── b93ef4f73e2a993083961b3fa971711c52226867.nq.gz
    ├── bad073b89483fdd12ac6425cff97c80f54a3058d.nq.gz
    ├── bae12a21c6ba9828b7e6c34a231f6b7560ef84f9.nq.gz
    ├── bb26c8c7eff50bb5f3877c3f21231a25eed07bf1.nq.gz
    ├── bbf446be5d0634632faa0afd1f44c78b45f30328.nq.gz
    ├── bdbc21523a461ca0bd6cfd7fb53f53cb48b43dbb.nq.gz
    ├── c0601cd63727d07a70a56b692341164b3ee75729.nq.gz
    ├── c11debd87ef833b692ec75ff91895a16e45bd5b1.nq.gz
    ├── c1240ce74712e1b0c1868efd24ba5b8aa5c74328.nq.gz
    ├── c207066fe4509c2df5f8221a6f77f3ee79cdfa01.nq.gz
    ├── c36396c65157de9ed63659084165b08945a7700c.nq.gz
    ├── c37c66ac0c68cc855066c3582cb98d0164d3865a.nq.gz
    ├── c40f05d610a6ac53a0c27fa4900a53b4251ccdae.nq.gz
    ├── c75c526cc4117d84aec16a01c2a91dcb5a002d5d.nq.gz
    ├── c8e38b614057b7e417c63fde44726a4143de9da0.nq.gz
    ├── c96da1e782e6ce694c2fa62e02531f17ecefc43e.nq.gz
    ├── ca99fe6cb4518e8e8918119421d4f1fe1e91854a.nq.gz
    ├── cb011905aac9f49d3ad1b0907787cccb08a6e151.nq.gz
    ├── cc3c1479323ad412cf4631e1d19646a2ff539fc4.nq.gz
    ├── ced24ead95f65a30110451249e0141bc2f5a2398.nq.gz
    ├── cf147c2eaa9e6d71ccaf98ead795b934d8939053.nq.gz
    ├── d0d5da916887662630113d71ae25361e12f4a62d.nq.gz
    ├── d0d69ac745f9b49f21a20f9e8340253c85460ca4.nq.gz
    ├── d1e06ea4520602684d68ea3a0824a30f69f4d514.nq.gz
    ├── d2a6478a1cfc7752dbbade9461a90da28d4df5df.nq.gz
    ├── d2f48337f9e40a7a1354c147e24fbffa760b5023.nq.gz
    └── d3889c1e00c439dfb42f50ace579a4927eee0edc.nq.gz

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

[scrapinghub/python-scrapinghub](https://github.com/scrapinghub/python-scrapinghub)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
