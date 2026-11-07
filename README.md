# Repolex Knowledge Graph of kivy/python-for-android

RDF knowledge graph data for [kivy/python-for-android](https://github.com/kivy/python-for-android), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/python-for-android
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c9a4b4f817847bd8505d972d1a0e6f965929a88
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c9a4b4f817847bd8505d972d1a0e6f965929a88
│           └── chunk-001.nq.gz
└── blob
    ├── 009a919b118f1b07aa795610c06469ad5a80a8a6.nq.gz
    ├── 0173e366d9042336da81f4d1499e6bcbb590627d.nq.gz
    ├── 01e3080f6cc455dbb147d10c7e735a8e1a39269a.nq.gz
    ├── 0257dbec314ce12b3d8354281d366db64331a448.nq.gz
    ├── 03ebcae77689d988f45e9fe008fd657cdd91b276.nq.gz
    ├── 043b56b01c1c409a01a7a2b8724a665bdfc996c6.nq.gz
    ├── 0450d789f3414eb4856bc676b590fb68cae34c8f.nq.gz
    ├── 04f56ac391f80e7c818a84dc5288a9acb871b756.nq.gz
    ├── 06f46c69cc67b55582322f5ee0490ee92389d767.nq.gz
    ├── 076efa9503dd23fdcb8b1354d5b1a63d5d1b539c.nq.gz
    ├── 07b71d4baa4dc70f33fe7c60a996e2c7e5796945.nq.gz
    ├── 087ab586ad198b895337edda3a8ebd762e32a3e0.nq.gz
    ├── 08cdf8d58a7e79b2f5c597affdcfe31b5caf1e0e.nq.gz
    ├── 0959479779773e52f3a2a24c9a7f6653271dfd71.nq.gz
    ├── 0967cfb5d042e3c2c62de22f18fb391e2df54c50.nq.gz
    ├── 09a3872b3e931eea3b8ef3b3b75d389b8c39c5aa.nq.gz
    ├── 09ac0efa74aeb79ee03f3d42037b279f332d14d1.nq.gz
    ├── 09b1804a836bd7002f36c3499a3e42584045ab34.nq.gz
    ├── 09fb3b212e4761ca6fef251ad6e7264398627661.nq.gz
    ├── 0a09dff97c7a40b71a24671f9d85a55cc4fc99ac.nq.gz
    ├── 0a0fbc72b4dbae14cd3382b0aae80347a47dd8d3.nq.gz
    ├── 0a299eb3cc0273ad1fc260cf0b4a2c35f5d373f5.nq.gz
    ├── 0a2be3e0329ba3b41851dfd24c633976a1d3b2ad.nq.gz
    ├── 0a32b7e614ccb58783d7fa89c15a36f4b5618b0c.nq.gz
    ├── 0a9310ad9738b0d3e33d8d9c99162b33f6cd7994.nq.gz
    ├── 0b261952314309c767706d1eed5d8fc05e1a53e6.nq.gz
    ├── 0b41be87f276847bde069c37c2f542fb599e8759.nq.gz
    ├── 0b880bc484d73e38f017b7b6d62221ba58f33925.nq.gz
    ├── 0bf40e17d4e378fae1047247d3b5a87a7d01af07.nq.gz
    ├── 0c47b29514274e7f50c57bc704ae822e2eb5f9bc.nq.gz
    ├── 0c77b9fde18ce42cc336dc9826cb112ba9fdadb0.nq.gz
    ├── 0db7bfd167513316be8e979907873c1bc6c8873c.nq.gz
    ├── 0dbffae246d512c2e33702bfaba1f337f7510a4c.nq.gz
    ├── 0dee5c8eb155039ef7e7cf2131b76e3fe5227c33.nq.gz
    ├── 0e0be2cf3a00e6390d532ba12dad17d2b16d3626.nq.gz
    ├── 0e119c5cc21e71de842f451aead08f7129a68391.nq.gz
    ├── 0ea10083c6ed4e81f5aa8416dadc9261c4f26154.nq.gz
    ├── 0f727ba455e06cefef93f035427d1cfb96765077.nq.gz
    ├── 0fa9bd9f52fd29531489790f6bf0f42104842333.nq.gz
    ├── 100c528dc3b3749948cac1d7e82fe682954aaa97.nq.gz
    ├── 10830bf26cd7bf79ffac5e10c040a92bedc0cf1c.nq.gz
    ├── 1086e00fcc440c865938fe17be905f8a8644d21c.nq.gz
    ├── 10b81f776bd2087c637d1995d6ee1e2d0266e1e5.nq.gz
    ├── 10feca475a37cfc4650fdd4381e8f263a8126ce3.nq.gz
    ├── 111cda0b853e635b1c2bbe43d23182d32badb4ad.nq.gz
    ├── 11446df95082d0a712e8f9961d1e12f28b739fbb.nq.gz
    ├── 11542b7abcc6bc59ee0d45f2829845f5f3a9c700.nq.gz
    ├── 1198ff3e9c6302243fd9c96a285373349cc0820b.nq.gz
    ├── 123c4b6eac5ba239a47457ce4671fa7e668a133b.nq.gz
    ├── 13348fcfde9cee84fa80e22f73f66ffbb44a8774.nq.gz
    ├── 134bf2991edf75a552d472020a28c6ef613fe3c5.nq.gz
    ├── 134ed9e33f129b706c14024dc8cc80018950d12b.nq.gz
    ├── 145622071271b2968f2754a7ae40f400457e695f.nq.gz
    ├── 14b4e0ed661a7d4a8b93b332478538baa784e748.nq.gz
    ├── 15598537ca58a8bf8192635da79925e522087597.nq.gz
    ├── 17fca683f1d121c0f9b342f2a1da512175ef5e1b.nq.gz
    ├── 1823b13223990d9fffdbd2b68e5533fd3f0359ec.nq.gz
    ├── 196a356d850bcfc42473c9997aa01f2a23520ee6.nq.gz
    ├── 1b306423120315343450f264e0a0351f10ce69d6.nq.gz
    ├── 1b33c55baabb587c669f562ae36f953de2481846.nq.gz
    ├── 1ba6a2601fdca900aabfe71139b12d992e37639a.nq.gz
    ├── 1bb58cb76df3347c1eb3cda24e482278f9a1666c.nq.gz
    ├── 1cdcb917947b287fcfb9a82526726d45dd201cfb.nq.gz
    ├── 1d6e65a161f0ffaab8bc4141d71381cb9fe5a95b.nq.gz
    ├── 1d946e7d42ec082b0e6a4ddf4f662cd2d170e9a3.nq.gz
    ├── 1e701341b312808d01482a14b6b6b63cfb29736c.nq.gz
    ├── 1fa91e9276574ae1e5a204d040d05f343b319d1e.nq.gz
    ├── 1faed7c59b0e6e09510b832ef6cc30da080db657.nq.gz
    ├── 220800d77d61702fcd1035687b951185c271fba1.nq.gz
    ├── 22866570b9816eb4935ec6486b873eb2b9d54996.nq.gz
    ├── 22b99b62ef26d8974876f554799ff4404d044428.nq.gz
    ├── 22f408949820c6d7015796c2fa169a922830bc2b.nq.gz
    ├── 22fec4cd57fa9bbe76d04a66482365e279ad5df6.nq.gz
    ├── 232939ba9fa15f6062a2c69494d622e62442cde9.nq.gz
    ├── 23f0b24077f498e0b768dfa2b9a33eae70a73b75.nq.gz
    ├── 2501af29f5a01a8deda2bfea42d8853fb4faa9f2.nq.gz
    ├── 250df058bd996c74e2d3c12419199a5fe24cc349.nq.gz
    ├── 25f8cbc04b37a81ca5166c70e55a6bc2e44759d2.nq.gz
    ├── 272c18f9e6cb72db6e7ce551d5cd4a8307e32f37.nq.gz
    ├── 27ae7d4ad4f840cfd1dea74e6ae8592001d839ef.nq.gz
    ├── 27e4cfee1bcdeec6f68a6d5b3de3e3bc6d5e00f9.nq.gz
    ├── 2971532fb13ccce23203e30f19a9796053141d29.nq.gz
    ├── 29d18faa24b01a0961febdbc549acede3d161a63.nq.gz
    ├── 2a0d2074ba89fb0dbc09fe88d537fbaedbf0255c.nq.gz
    ├── 2a58add7c117ad2c54ec8633ef082e9e0b631b8c.nq.gz
    ├── 2a72e68703b8964b2c2393ea25cf157cfce60434.nq.gz
    ├── 2b19cdf6d70c855f979cb848e8662449abe1afc6.nq.gz
    ├── 2b62c071dbbde09233506df47eb99e66c8aca37b.nq.gz
    ├── 2b7900a72f73cafe49232b8c7cd413183a9e0e21.nq.gz
    ├── 2c67c77be024ac6424f8292a213bd5ea30776420.nq.gz
    ├── 2ca47716b08df3ec37da354487c45282849d275d.nq.gz
    ├── 2d435620613a6fb96e9a42ceb8447b1264d16ab2.nq.gz
    ├── 2d4d7a893f53b9023dea3a35f16f1dd745bd0b35.nq.gz
    ├── 2de278ee001cc6cad7521fa8b943feab3c8281b0.nq.gz
    ├── 2e9474568befb34eeae3d07f52d63c69235f12d1.nq.gz
    ├── 2ee2d059c8e897a2a5a2d189dc672a8f65b06af8.nq.gz
    ├── 303a9530e1b4f116bcdbe688d82716c9fdf46f87.nq.gz
    ├── 308c525b7839b49ec668c8212c472b322083203b.nq.gz
    ├── 30a7af4bb901987c462b89936fa9a8c720e94ecb.nq.gz
    ├── 30b685e32bf52c6e97726095fc8337775554c8a8.nq.gz
    ├── 31422e89395982583c3671145bd1dc3082236dff.nq.gz
    ├── 3206603e8204bc1bc0dbc1e2cdf3841fcbc6f756.nq.gz
    ├── 3404c4fe62483329e48e05cbe42738b0360d454e.nq.gz
    ├── 343d344560702186d10a8e8519aa552cf6b4ef48.nq.gz
    ├── 34aec36dd25e7038f516aaefbd0d948821a5aa74.nq.gz
    ├── 34d56b6e01f4ec1ab5b186374c3cabaf0f8a72b0.nq.gz
    ├── 350d8b088942590ea66e55a9b4d0a374cea400cb.nq.gz
    ├── 357d74d5390acf267418390d6614443c484cd4a4.nq.gz
    ├── 36365cd03dd5bcef2613cfdd0867c806d9ba896c.nq.gz
    ├── 36c02e4b8673b3ced76cf5ee8ff3b79b88eceee0.nq.gz
    ├── 37f6c90f765d3b4bc4b71dfd99d4639a01de917e.nq.gz
    ├── 38564eb7ce92c9a2d0d24fc54e157e4bf607498b.nq.gz
    ├── 3908909e2d5bb88316a5feb33700c534a95101a3.nq.gz
    ├── 3930867ee0e547eee0e0441cce747f1d2ee2b7e2.nq.gz
    ├── 39411a740fb244523dcc63ec82b4b5554fe062ae.nq.gz
    ├── 398919d2432a408465c6e6e5e7e032d2640569cf.nq.gz
    ├── 39a68b7ee24de544cbfb3fbd9fca74c66d3fb666.nq.gz
    ├── 3b6ab683cb3f7e90b33cd7ba4993b90c786d131a.nq.gz
    ├── 3be02934bab97450728257db92d5a5f01b3a434e.nq.gz
    ├── 3cebc80c6c8ce08a49067d7df8aecf9037055a63.nq.gz
    ├── 3cf2437e32c461fc9dae8c2e2657c7b8c4968650.nq.gz
    ├── 3cf519571486fbb2c9f97453dcf208bd3bfed941.nq.gz
    ├── 3e65e73c32a31e6f54f02fb194936383953624eb.nq.gz
    ├── 3eb8871ff96d4bd8599b3bfd80375078f51eee24.nq.gz
    ├── 3f28649e179891c31c2577bc3914ad5b3cffed54.nq.gz
    ├── 400614d3bf36410b53eea4017a5696f99f4e919c.nq.gz
    ├── 404091ca75a3d80d173b4c7bb18716f73006697e.nq.gz
    ├── 40afd681ba018a81a6036f26f236c90ddaa3adab.nq.gz
    ├── 40bdea42dcfd26031d123d5d07794cbe11d783e6.nq.gz
    ├── 4161914b67373165facbda0b17d6d2032d254fe1.nq.gz
    ├── 41838651328687c074daf3ce8b63d72578838cfa.nq.gz
    ├── 41addc88d6596885dc9db70ba9761c85fec3e918.nq.gz
    ├── 41b06ee2583913008078a51d723f1e54524267f9.nq.gz
    ├── 421e4d927c4d9d49db82b806b1accf1d060bfd02.nq.gz
    ├── 4253ca7d335f0dc8c9bb3e393d9652c8bdc20fcd.nq.gz
    ├── 4265a0707782d5ffa38b7370f66a4e7c5e009379.nq.gz
    ├── 42d1da7064ae186f4ded7843f98751592415de65.nq.gz
    ├── 434be4e8ba94d5aa0759b2b2df9fd69823806de7.nq.gz
    ├── 448f174450ce28ce03127a499a3ebfe10623b350.nq.gz
    ├── 45ef3a9f5b737192e6000c16e5f6cd2727499997.nq.gz
    ├── 46048364ae1e8ad5ca5dac2f404677a264fcb4da.nq.gz
    ├── 4611e20eaa33afccc59dec5b40d2b1ea38132736.nq.gz
    ├── 46262472f345f2213ba5f61cafbd734a8d122652.nq.gz
    ├── 46bace12b73a7c9c8864aae0b700785ddf50e6a8.nq.gz
    ├── 471029e13ed1049af5f82b401a10eec85755a78b.nq.gz
    ├── 47511349377ebee3530fd2ee89f0976dc15e5f59.nq.gz
    ├── 48e266b3a0a3b4e7830c64da1cbc3e6ed164f0c5.nq.gz
    ├── 4910caf7fcb254bd3a8b14db069c629691348289.nq.gz
    ├── 492062b9840c8bd37d3a1aed24eaaaca1a90213a.nq.gz
    ├── 494270d2c7a8244bfa26192ceef0c6ad857dec34.nq.gz
    ├── 49c6a83d278e6dc7ed101b55a1fe3e8460fd3649.nq.gz
    ├── 49fe8c92dff6b75c8b783075ca275f4cb8ee3d2b.nq.gz
    ├── 4b342b1ed4977dca9751d2a947164a3508553239.nq.gz
    ├── 4b688be35b70df89c312fa0cbccc56fdc68be4ff.nq.gz
    ├── 4e26ca4d7e6a1c7256afebe2482ddebaf8a4cbb8.nq.gz
    ├── 4e9465603f554b974c06c2e2916cf6ae45dbfc2e.nq.gz
    ├── 4f68d6343bd8c5e540155471089dd41641bbda27.nq.gz
    ├── 50165765c0c18d12b67ae146476e8394f894cca1.nq.gz
    ├── 504a79cad93302a0efcb119ce1565885f506cb38.nq.gz
    ├── 5053e7d64389d3eaa35c6e807277fff9f83898f6.nq.gz
    ├── 50ebc2fb5ceeec72239f734f63423d4d262663c9.nq.gz
    ├── 512642afc34ef734dda7e3cc15019c40476b6bc7.nq.gz
    ├── 51f0d8a00140ddab444d9fb64b1847bf4a6528d0.nq.gz
    ├── 5216bf9a588138cfdc40b9f7b31d4c867f23f544.nq.gz
    ├── 524ed313fd8bf2bdf75ee5c571e14b9e05c1774d.nq.gz
    ├── 53a9403885e1de2324343c71a9ef923deb805dda.nq.gz
    ├── 5482da8477197218f6422d662464acd5ad64205a.nq.gz
    ├── 54d743ff18c464bdcb951320baacf7268bc94e5a.nq.gz
    ├── 54dfb646573697c03a6e8d8d0f5bd7780ebcb0d1.nq.gz
    ├── 55096a4aade989232b7138f4c7e91bcf8cb0e9b9.nq.gz
    ├── 553287d12a3373d654bb4842e87d55818efda465.nq.gz
    ├── 55b61d48b5dbc26b0cdd2d9b35be056886b71a98.nq.gz
    ├── 5636dffa7d1aaaf1db74c7ce5c985c76ca2b309d.nq.gz
    ├── 56b75d32dbc4200cac15b7a756bacd429c5c807b.nq.gz
    ├── 57860493e2919cf5fde5965d6d7dd898136520db.nq.gz
    ├── 591e977176ca6cdbbc83ab4be72b5175021edff2.nq.gz
    ├── 59265e99a7c429d11c0b3ce083caafb05a4578b1.nq.gz
    ├── 5942a03442058177d87227887214670045197341.nq.gz
    ├── 5965afa3542bbd05ec2845b4503c18ac9fc73e92.nq.gz
    ├── 59712ea8c831db460fe4e1555c06d3632d9e7bef.nq.gz
    ├── 59a00ba6fff07cec43a4100fdf22f3f679df2349.nq.gz
    ├── 5a05edf1f0ca74c24df11371394c642af7266cae.nq.gz
    ├── 5ac472b7e1899bc0fae1fce60d025eda6bf849bd.nq.gz
    ├── 5aec92606536fa21970c03c77c4ddab20e86e54c.nq.gz
    ├── 5babfbc114e884c0d09a1f69e2677f0a95429561.nq.gz
    ├── 5c84e6421b7ed0bc79a0b6a1e882601ef86bdd08.nq.gz
    ├── 5cd55d5096e681d74ee3217d2a55fd8f0515dd0e.nq.gz
    ├── 5ddc3c432f745f767bba851a83b5e089b983682e.nq.gz
    ├── 5e2a9a7243ff94cc91b9997063df9cfbf0ee67df.nq.gz
    ├── 5ea5e0cf3cf485b3cac192afd4d1bd61b0490115.nq.gz
    ├── 5f55723fd5ee92f9e4c4f00060686b9e39d74b45.nq.gz
    ├── 5fbc4cd36588f183c871b159a711cccbb6b134b4.nq.gz
    ├── 6006fb94c72def78c2c0695caaa339b854aa1696.nq.gz
    ├── 60188057a89c4ad58f65a381698b7f557d0a90e0.nq.gz
    ├── 60b18d7816c9ea5635f8c276851970e575b5f953.nq.gz
    ├── 60b34a8c46e627d5901473bf6f74fa866a5a4db1.nq.gz
    ├── 61381959014950d998b04d18dcc13ecffb3a5477.nq.gz
    └── 614b0df0ff52d4514627fed73794ac717bd8d4f4.nq.gz

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

[kivy/python-for-android](https://github.com/kivy/python-for-android)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
