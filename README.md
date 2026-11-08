# Repolex Knowledge Graph of canonical/cn.ubuntu.com

RDF knowledge graph data for [canonical/cn.ubuntu.com](https://github.com/canonical/cn.ubuntu.com), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/cn.ubuntu.com
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fa84caa790d26f60c3b8da739611ccd2f473bc00
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fa84caa790d26f60c3b8da739611ccd2f473bc00
│           └── chunk-001.nq.gz
└── blob
    ├── 0016ad172d74f28710b25d0ccb56707051206bfc.nq.gz
    ├── 0107fa78aacb1d254abe4e810a73408882b7b362.nq.gz
    ├── 015404f449f45c2f91a9e869764b842822e699a9.nq.gz
    ├── 016c159d0c96c0639d7bc9838f0d25befea26616.nq.gz
    ├── 017c8fa441835484367a62ff7756d3549820b92b.nq.gz
    ├── 01aa3941d0812692f82cce69009c0e5628bf39a8.nq.gz
    ├── 01cc3d8bdc036a045b3d04a6f5cf21bb44aea679.nq.gz
    ├── 01eda9e0ff0a47347556c28b3bcf1ba68d6c99b5.nq.gz
    ├── 01f0e489d657517837a4f130d14d40292e52d02c.nq.gz
    ├── 0209977682eaa3359d03c305d6e6dfe40fbb772d.nq.gz
    ├── 03a0bcb909a467abd35b89aa8415e9e57a77a982.nq.gz
    ├── 045247f5748c721982e0b971a4b44aa8a92d7115.nq.gz
    ├── 047480b68e6ad88bab36f2f5146e10085f1f0787.nq.gz
    ├── 055004358db386cf39835b259b7a78f6a023abbf.nq.gz
    ├── 05799fd9cd7b56cd745ebbc09c2a808fd43d4876.nq.gz
    ├── 067057e45600d75d6748e5b4633ad31ab16494a2.nq.gz
    ├── 068c0d89eee49df9fa60c6d6626cc7c3149e9c4e.nq.gz
    ├── 075e7c989e7d069810118a91188039569fdcffa2.nq.gz
    ├── 08489a8edc1ce39e2f543310ebd07a4e8320920c.nq.gz
    ├── 08a01d7d33bd49f17a834563895ad62fe80e24f8.nq.gz
    ├── 08ece1f30bb3cb44fee99cf8f0fe21b8756966b0.nq.gz
    ├── 08f849fe748e4add9aef1e6c81c8559dfd6df4e0.nq.gz
    ├── 09547db9d66e44db94e6075bed29b4a67a6e9d21.nq.gz
    ├── 09d6efab02753cf4871e9aaa112674162465fcef.nq.gz
    ├── 0b6aaa08154f454e3d16e08d09c5ce7d7f8724ce.nq.gz
    ├── 0bb9a615e258a9679555064bde1c3045a0e42968.nq.gz
    ├── 0bea4c4158653e8ab7034d13752eb4a2b3fbbad8.nq.gz
    ├── 0c0763a9e6961579c9044cb002699bb8b132ca24.nq.gz
    ├── 0d30cfb02a18a8a0fbfecd57afae264fdd02527c.nq.gz
    ├── 0d5aa323425a3271c9fc6aa58ca8f8e3da5728bb.nq.gz
    ├── 0d60a42189fe4db14b7395ab53fd9415f5ecb51f.nq.gz
    ├── 0e39dd95fd22f78778db26afa1424107ab7a9c8d.nq.gz
    ├── 0e51d1b6290584044e24fd75944c48b6dfd942de.nq.gz
    ├── 0e60bde9a6a8476cf90c1c4d8180aee5d5607261.nq.gz
    ├── 0f60f885fcbc6b142b1bc8eebd03b34ea32e5a30.nq.gz
    ├── 0febacb4602dace1d7278a42023acc80f7518973.nq.gz
    ├── 0ffd2e2c417be1121f8e790bc4d4f43a3fefcecc.nq.gz
    ├── 105cf3f119fa496bb61fa547700a83ad56a0e89c.nq.gz
    ├── 10b11a2f235b299058092bf36fd03bcec84afdd5.nq.gz
    ├── 10f55f3bdf53187781a111f78b999dd91a9944ca.nq.gz
    ├── 11998fbb1335a903c8bd256fc67e84887ff27f63.nq.gz
    ├── 119c878dab54a7b6a8cc407e17d69c2dd8654d86.nq.gz
    ├── 126f90b11b227bfdb342eb63639f2b784c1f528c.nq.gz
    ├── 12f2e3c3e596b00c10c38b883272069f7d06ebb2.nq.gz
    ├── 13b051abf31eeb6edbaaec03737b265350919f75.nq.gz
    ├── 15206cfcecf097b5869cb82ec047829e82e74529.nq.gz
    ├── 1522c6824607645690a56becb35f6c957735ceca.nq.gz
    ├── 154d7b2b4975285ea254dd2a697a1952c09008e4.nq.gz
    ├── 15612d7960dddc2bddee4121de536c59f42d35fb.nq.gz
    ├── 15989603d6610b1c35a4476079088accadafd106.nq.gz
    ├── 159e2e39b6aa052bf42757e36197fcedaa546c2b.nq.gz
    ├── 15b6a0c54e18c08f323950755f9542685ff70428.nq.gz
    ├── 160dcc7922f61d183a2fb5e2de5cd92efb8f4afa.nq.gz
    ├── 167fdc7890e90bbcb9b17757c08b566af09a40a1.nq.gz
    ├── 16dcd86134f8fd69acc6952b5c95b8c47f443608.nq.gz
    ├── 170a219a7d5198817c3ccbca226a22fb96712218.nq.gz
    ├── 178e93e77b6c25be7fc6810ed1f80b7f08d8fe19.nq.gz
    ├── 17da17938ebd8a86c48a5248895979dbfaec827d.nq.gz
    ├── 18c5ac8a6ee3386980ee3fe162aefcb4fcc94ad8.nq.gz
    ├── 19be8ce04b9bccfe8d825459c2af9af141465ab1.nq.gz
    ├── 19fd7854e0ba1a69706c705c9fbdfa78e702b3a3.nq.gz
    ├── 1a62a6916c2091fc5288fab83746a7c987b51daf.nq.gz
    ├── 1af5f93751ab68e4c11edcecee6503d5609c46b0.nq.gz
    ├── 1b81ab82c696ea050ed181fcd5e9250c71014228.nq.gz
    ├── 1bf4738078af2605312f7115ac047436038ee107.nq.gz
    ├── 1c45f93208523231a0b4995238ab647cac68f46d.nq.gz
    ├── 1c71f6070341be2415618ac5fafcf3c3b2a34e32.nq.gz
    ├── 1ce18b63cacea807e4368fc8d3143278a3be323c.nq.gz
    ├── 1d6026b20f639d7d9637872a8c89fd927a5d4a2f.nq.gz
    ├── 1e181e1bbde123d82605caed1d3a8731f35d444e.nq.gz
    ├── 1e204c31e3490af2ab26874ad868feb6b74720df.nq.gz
    ├── 1ebd055010533de13cf1276516955cd43ef336a7.nq.gz
    ├── 1ef3430ba5c76c7fad6fb019cf1867dd3eabe3b4.nq.gz
    ├── 1f29aec4f106f503bb6e556e5a0fbc7e00c2cddb.nq.gz
    ├── 1f3ce56e44f87e0cd1d12b623fd3fdd70bddb835.nq.gz
    ├── 1faae9f1e849a6a9ad9d5f1563e22271de8faf4a.nq.gz
    ├── 210d33df059c80d38c04984f87aecf141c2c6b05.nq.gz
    ├── 220f572990287d0aefaa056ff8fd0fc72e1d5f0e.nq.gz
    ├── 2216467c6ae66c334f0e698e255641cc3168b7bd.nq.gz
    ├── 23831f22b29ff2f83b766502cd59d42ce6c31a58.nq.gz
    ├── 23c248dadef53241e98c659e235a72fce41c3907.nq.gz
    ├── 23c38a409a04afd0e6f48677fc2c46941aafb34a.nq.gz
    ├── 23e20ee9edfd0cfe486eacdd1d54c4b53ed9b7c7.nq.gz
    ├── 23f0f5b6ac7220e4b697da6eac88d93843e9bb57.nq.gz
    ├── 243b984d9ae39145e55edc31f7ab63cf755d21b9.nq.gz
    ├── 25470cca9c4cf2ca82f7f8bd52bda61a0616e404.nq.gz
    ├── 25c94aaa54f5a8d95f8943479704337b76a59098.nq.gz
    ├── 2694f20e8284b74e019c9bf76246ec3493bccd2f.nq.gz
    ├── 26da997e85a3f5e13d8e625d7be5817fa2dbc18e.nq.gz
    ├── 26e7da2abf6f256cad179142abccaceaee59be9d.nq.gz
    ├── 273631b03dd23f924cba6506b62dadcd0e20a62d.nq.gz
    ├── 274d8fabbc67ce99269208f1b1b0cc8fb8e4c0a5.nq.gz
    ├── 275b37652e146dd903426e06997d7436443628a6.nq.gz
    ├── 27efa407b43f1e2ee21aefd1a679c40a4ce09bd6.nq.gz
    ├── 288c6ea4d08b4405a03f4047d0424e4340460b02.nq.gz
    ├── 2924f4642d1ff9960c296778f9f50132579127be.nq.gz
    ├── 29984ec41c233879ad2cfc8d4cc12cf18589d27c.nq.gz
    ├── 29d780cc9ccda675231955279619c72909b80bea.nq.gz
    ├── 29ee07b59a248c553c71aae88d9a60cf4554da7b.nq.gz
    ├── 2a3eb7f5676028b4c35a2037284e64f73aa01fd5.nq.gz
    ├── 2a5a7f5baab48b9686e30cc201a11312aeb3fc84.nq.gz
    ├── 2b2ad32af1a2abf9b081d18341fd8ebd026097e5.nq.gz
    ├── 2c00be8eda6cdd570042163259ce6a71ded2e484.nq.gz
    ├── 2c7554f60bdce6314198b95b0aeaa18c59556ddf.nq.gz
    ├── 2cc123ef55972a7471a9941c1d62e4fd9072b784.nq.gz
    ├── 2cf656da75745712c0eaaed15c90605d70d34c28.nq.gz
    ├── 2d2f3622fc392f599f54bf816f079b4ff9c67b94.nq.gz
    ├── 2d495f4642f79c156e4b3d407037f7f2c6804c8e.nq.gz
    ├── 2d49eee5c40accd2d77cbc2276be67ab00cb9645.nq.gz
    ├── 2e138538624790b96b68ee3bcb16b1e98f0bafe1.nq.gz
    ├── 2e2ca9a16313276b7fa2fb5e64b5366087fab7de.nq.gz
    ├── 2e58d5055fb2d7a5a9f13f2b3a3d89a855b5b5c9.nq.gz
    ├── 2e6d80eeee0e77fc5aa511b5ada23fad6ff5cc90.nq.gz
    ├── 2f20c83d8956ee89ec53202ad653db1d832b9565.nq.gz
    ├── 2f90e4c662c3682900bf8141bbd54f45ad8b4493.nq.gz
    ├── 2fd5dbdbe5c753f6ab594981a520e443f15e6195.nq.gz
    ├── 30b6245475f1a916b81f9a99b3b6297424278ece.nq.gz
    ├── 333ba444aee82d07ddd8c4ad8cef0f9894c3e5fa.nq.gz
    ├── 336add7ec062fa06a877cc3f221cffa0cd1ca124.nq.gz
    ├── 33c8a11ef35db6ca9f30c3c3a9699c342490d3d1.nq.gz
    ├── 3431183b050a66d054b168093908b4a0b038b31d.nq.gz
    ├── 35193554c9de310c3d7f2018882d1c6a64895384.nq.gz
    ├── 35645617856a6fe3d27e8aa9791adb9545796fac.nq.gz
    ├── 3650c1372bc219ee939160922979bad2082c9750.nq.gz
    ├── 369897147a890b6b2ec29697a8f764099267853e.nq.gz
    ├── 36a02333aed59703a9439613847ec19de232d44c.nq.gz
    ├── 374ec9076a16f1ca1dd294e37c75d28bf825ba12.nq.gz
    ├── 37c4fe4edac3b7efca871908fc9b197bbb07999f.nq.gz
    ├── 3a13ed4d400a5d9e9b6e90e225c830eebed4a8b5.nq.gz
    ├── 3a9c6c46605d740b6dc11f063626fd1f3c485286.nq.gz
    ├── 3ac70a14ebaf50486045a290a0ebe803ae09966a.nq.gz
    ├── 3ad376c41475e8a741c461bfa801bf31f6dbab6e.nq.gz
    ├── 3b064345b74475ccea5df5a65229589814f6625c.nq.gz
    ├── 3b30ccf21a65b48c728b722b8b5d608f88e5e908.nq.gz
    ├── 3baf7e9f115575ed5e57b5033a7cf76eb1a5dad4.nq.gz
    ├── 3ccd9c3eda4d4f2fe53360be6fb27e6050a1420d.nq.gz
    ├── 3d8394bb995abbc774d0e6e9ae574c486b828350.nq.gz
    ├── 3ddd580fc2f1c81dd0b53a875abb5f5e31d77e26.nq.gz
    ├── 3e7b050f6989e7fb273f34936f78a4a04db6df0e.nq.gz
    ├── 3e7ef688b7b228c99225c22e9d92c57d5bd2be27.nq.gz
    ├── 3e8ff1b2972a66a4e8bfb978492072eaf575d3de.nq.gz
    ├── 3f26e7c7adc1bd0f1059c8a31cd03aa3cefc6bac.nq.gz
    ├── 3f53104899ae5ecafa0a4320b592f6c41e3c4df2.nq.gz
    ├── 405cfeaf8abfd52e2a3d7db0786f2d1d28fc3d6b.nq.gz
    ├── 4113d0b78383b3b4c8aeda15038efc7cf3c27ce6.nq.gz
    ├── 41cfecb217f85ec9e6a4ea9ffefe3e7cfbea09ec.nq.gz
    ├── 421b4c86792648ddd3b8c72aeabd3942e143c681.nq.gz
    ├── 4260985382af6d2ff45be92fcde134b431d4a646.nq.gz
    ├── 431bad34a6b7e38b7bdc4aacdad015740fe67985.nq.gz
    ├── 438e6786f31f3289bb53c6be00ef52cfd5457171.nq.gz
    ├── 4446c7a1dcf71b77ff7ac74d4bfe6c7a543394ce.nq.gz
    ├── 45198df5321549f95fbe5e4556413a0a6f51438e.nq.gz
    ├── 45c7a53aa88cf54d847c7924f8f54f6fb1ff20ab.nq.gz
    ├── 45cf1b3cc67e0b54116471dbb80335c562a0d34e.nq.gz
    ├── 464292fa75f69cb05888ba10b809b423f8a0ebba.nq.gz
    ├── 4653ea29fabf363208617da6acd33d2d6949f8d7.nq.gz
    ├── 4723daf19ac3872798ef71c1425312d35364398d.nq.gz
    ├── 480c2d700cfabc03d7f79e7f9e289f6673308a8d.nq.gz
    ├── 488f6137692652f4ce90d682d5a7360794c3a69d.nq.gz
    ├── 49345eb6b470bc4d2bc6d1728dd30eacdb7ca80b.nq.gz
    ├── 4969c31af7c959dd8f27410ac29df6fdcf7503f4.nq.gz
    ├── 4a130ba0d67e94cc5dcadd72909f6428591cf07b.nq.gz
    ├── 4b2988980daf220b9c1decd9cad3245a093ca641.nq.gz
    ├── 4bb50251f80029c577c7bed139e69f023732b7e7.nq.gz
    ├── 4c269618ec75b37e5bd526497541b14d2cdbd108.nq.gz
    ├── 4db29946c1791210d4ad36bb1b04bb3ba8316a17.nq.gz
    ├── 4dbf3c77ce5687b81f53a6361517fa0eba6dbc2e.nq.gz
    ├── 4e7b1555d33f02fa40cee3f3138d10c970bc8a10.nq.gz
    ├── 4e7ec5c58b87d71c92d1bf3f872e82b5bd9f1ee8.nq.gz
    ├── 4e9597517271f8d107d168c336ce3d3936842103.nq.gz
    ├── 4f3ce95bd0683838dfdd536baa8e9db9df5e882f.nq.gz
    ├── 4fcfceff545784f3bc12d9ac87b555014c3dc1a7.nq.gz
    ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
    ├── 50468eeb56de823077cd6d79cb9f07a8d7629597.nq.gz
    ├── 51807a5b2a7577a3213240ca2cd1dfc6c1c58ebb.nq.gz
    ├── 51ae0d91ea8f2ed97f3259b575eaf82e4a8e7be0.nq.gz
    ├── 528dfc3bb157cb530260b77d9976405fe7063f26.nq.gz
    ├── 5500b87383a1a3038e7805fc9b0929d793070743.nq.gz
    ├── 5532cc4b11ea4107e07cf99d2554324f6ca58f4a.nq.gz
    ├── 55856c1c891007cb369ae70e122e8ecd4b519e4c.nq.gz
    ├── 579277d0a9fd4c09a25272699667ca40c18f6b97.nq.gz
    ├── 57c1f36c6b91b4dd41b8f9160d6d9dc8215036ca.nq.gz
    ├── 57ff50fd3d84c2cc670cff290385bb2759c01ce4.nq.gz
    ├── 582548f9e20b05cf71a4383222728dec1b7a2f38.nq.gz
    ├── 5985ec52129f49af2e1a953b6ba34f2fe27c6af5.nq.gz
    ├── 59f96930fca27fef172c95c9e00239cd41b62831.nq.gz
    ├── 5a1791aae5fe8e8a34073d43dd58b85118640989.nq.gz
    ├── 5a5a3ac434c5b48b5f0ea8800ef5a2492a09c5a8.nq.gz
    ├── 5a9bb281b8b9faa334aaec1b23e1f8d49197217a.nq.gz
    ├── 5a9c6a0b14b88c4c9f892f589f72cad03287778f.nq.gz
    ├── 5a9d8611ccdab8fadf5447b1f4a5d3a63eb4e60d.nq.gz
    ├── 5ba12279a06b6faec7f87c40aecd44324b6f8aaf.nq.gz
    ├── 5bb61ef00710aab18c62635d3cb67b013e64d777.nq.gz
    ├── 5c018185a3b7395067d901ec2abe7879ec3582ea.nq.gz
    ├── 5c03bc1ab8bfe4431ca9f22927c4c219520b9698.nq.gz
    ├── 5c26650182f7e3ab057c718fbc499b588ba73efd.nq.gz
    ├── 5d93a3d1f8c6afce386bef1a9dd92881957ec94b.nq.gz
    └── 5f146a5660d379e37124cfb329fad8086b37c0c5.nq.gz

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

[canonical/cn.ubuntu.com](https://github.com/canonical/cn.ubuntu.com)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
