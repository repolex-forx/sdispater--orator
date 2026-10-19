# Repolex Knowledge Graph of sdispater/orator

RDF knowledge graph data for [sdispater/orator](https://github.com/sdispater/orator), parsed by [repolex](https://repolex.ai).

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
rlex download sdispater/orator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── db8744967e1c91a80079ecef70c7db805871dd3d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── db8744967e1c91a80079ecef70c7db805871dd3d
│           └── chunk-001.nq.gz
└── blob
    ├── 006205e3cc3ccbf4dc04b3e991905bd68462fea2.nq.gz
    ├── 0316577d2998000c7e443e6483f160cff460cd5c.nq.gz
    ├── 03c037a0d9a0542404852f2a1324e4008e538099.nq.gz
    ├── 05b1e53a5f435c19ccc723b37ecac9b75a760783.nq.gz
    ├── 06287e1f4baec7ddc22d2e3b0dcab38d624db017.nq.gz
    ├── 062e0c5f5c26964c5babb097fcd149f4a4867dc2.nq.gz
    ├── 089e35d7a5368998b0adc572d1c80d5f2f3f0b7f.nq.gz
    ├── 0e8efb2e8cfc4593efb39de782a0e30fb80afb3f.nq.gz
    ├── 0ffbfcdab18bebc1421557da84c31d7855a982da.nq.gz
    ├── 116929d835f7ed0347da3807ba828174474239da.nq.gz
    ├── 1450ea6ebd7bcc4ef2d5cb904b1711e1487e8811.nq.gz
    ├── 16a1e0ea9d208f63cd4c92e4d2bd2ebee6d0d4d3.nq.gz
    ├── 1814afa8eb7327832cd489be13d8fc7b2ce0cb43.nq.gz
    ├── 18658674bea22df82517bc4a85af7fc228f70ea9.nq.gz
    ├── 19bd7f796b014ef2e682c2ada91686168228e295.nq.gz
    ├── 1b54f44ae2530c01ba9e35eb35d5ca266af1c9ec.nq.gz
    ├── 1d783033b7462346373b7e7882255384362d9cc8.nq.gz
    ├── 1f73e4d55cc24c863d5307cfd4860670bb783c2b.nq.gz
    ├── 20fb48a0ede9c4a4c98e2d5de3556c4cff24410f.nq.gz
    ├── 217e21f0718ef5fc03e487108717b700fcb16204.nq.gz
    ├── 220e9924e33c08637579f4eaa4e8f1820b8cfd3c.nq.gz
    ├── 220ee06743a183f68ba2e336be255cff7cf2fab4.nq.gz
    ├── 22be9f5b5559ebdae0667b15c74907e4c81dad01.nq.gz
    ├── 24dec942a56f709aeeb9a88dbfdc5489c6d61e33.nq.gz
    ├── 24f7cb77c0450cc65bf9a11a47921c177be720d7.nq.gz
    ├── 25b038e22556b14a3097354296b92300bcf8f931.nq.gz
    ├── 26c1c5e3f097fba0e1ba3ca78ba6f3eb3fc4db15.nq.gz
    ├── 26c890c47600777b38ba297725732fdd29cc7b12.nq.gz
    ├── 288f1ed39a271ddac097b46203586591b863e367.nq.gz
    ├── 2949c00eca9eedf3dc0c04b645cf586593a0a6e7.nq.gz
    ├── 29b41c02c781c266a0c48705160e32e867d8674b.nq.gz
    ├── 29c5627840c168aad464e0016d6f5c9885d3ab6f.nq.gz
    ├── 2a114400053456127f527de3df080309760f43f6.nq.gz
    ├── 2b165f55b7fe19a144764c75ee2c738bc4b9cff1.nq.gz
    ├── 2b789d65a894e9a6fe7000ed4045c29ccbbb2a54.nq.gz
    ├── 2c9a2f9f2302f9a3ebb7aac67407a1458752d2f8.nq.gz
    ├── 2dbb669089c090c13ac1a5f83c1d291e01d80abf.nq.gz
    ├── 2eae9ac253c11c2a66abd0d2d8dd799f9024d479.nq.gz
    ├── 2fe4a21311e0f8da8feff1c15c62bf8f107e5cd0.nq.gz
    ├── 30fd7f64537e6d4cfba91fc3f39ee78039697627.nq.gz
    ├── 323f1e74ce8f2bbe1fd04872f1d1cf5d443d6ed0.nq.gz
    ├── 325817728ede29abed99a5a4b1d7985976203920.nq.gz
    ├── 3680b31ee9cfd00daaea5522c67eeee04dc3734a.nq.gz
    ├── 376cda08faf611578793e0edc1a7829dce357dec.nq.gz
    ├── 381b97f6acf69ce1fd1e8da7ce9245635caf9e85.nq.gz
    ├── 390896c01bbc14c86c341a0dc08e496eba162e6a.nq.gz
    ├── 3a7d5596fd1edee72574511100c1502684c50552.nq.gz
    ├── 3b0f04f775baa0d403e39d92c9c1620fee82df4b.nq.gz
    ├── 3bf1d6b01f1f20ae8f04108e576aae3d89629f16.nq.gz
    ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
    ├── 4169466bc7faa2806c67efd882ee630896379a27.nq.gz
    ├── 442eb25d9d9ffb97b32acb68c9893581ae158536.nq.gz
    ├── 44f0d1ba40fef0b8a5177eb1b63639682e464a5d.nq.gz
    ├── 454f39ca70634005486c366ac0d72ca363b61f23.nq.gz
    ├── 468b1bdab48a9e4136a52a32efd4c6fd1c165454.nq.gz
    ├── 469b59890334950fa186707c4992aaba1fa414b7.nq.gz
    ├── 4708507544cc87bab479ce2236f42adea092ee09.nq.gz
    ├── 48d62239d4c92e367afb573b0d6521b39243cd51.nq.gz
    ├── 497a793b3b6c58eb5438df32a88103ea3cd2dbe3.nq.gz
    ├── 49ee29e9cc8f060e7448bcffd87c577eb378f621.nq.gz
    ├── 4a69058a88f75df817b98e562b420da2f6596354.nq.gz
    ├── 4a8a676fa05e8dce39dc7f5ddc5251a1707a99aa.nq.gz
    ├── 4ad0da67f0687767b92b3b473d0af69efdd42c44.nq.gz
    ├── 4ae07f4d52c94bccffda38ff0728f3292323b9c7.nq.gz
    ├── 4c889528c3736c6e753fda174cdc5a1e80c5628b.nq.gz
    ├── 4da03b2311ca24b0a1c8144bf6bdac01d6497f8f.nq.gz
    ├── 4e33c917ce75b14fd69fa352b6820e140e3a628a.nq.gz
    ├── 4f7b4e62822b4d1f6dc1c58c74ac4f2607fa92ae.nq.gz
    ├── 52987bbd54a28594482ed1d4d153cbc98153fc68.nq.gz
    ├── 55978eec802f36a989b0300fb470cc3f50740464.nq.gz
    ├── 55e6b94501356fdefb532d1ef5ceb40b67a92b4e.nq.gz
    ├── 560914da4cfa197ab1baba928d61d21eff5003f1.nq.gz
    ├── 57558a7e6e3758d443466d12540962672ac36e84.nq.gz
    ├── 57949e15aad424a7bd19217459dd74551950962a.nq.gz
    ├── 59ce0b3bb401e31895a60f2b30d81aeab7c52bcb.nq.gz
    ├── 5bb2e6c8f068507b2dca1fcbaaaa1a73f6ae8bed.nq.gz
    ├── 5cbdbb05e914b73debf0149cd513da1f82da2bf4.nq.gz
    ├── 60916adb85e5a1935d8eca2c421d7919df4fb8cd.nq.gz
    ├── 609ce5281da929eacde9ea04c9fc39850465061a.nq.gz
    ├── 61907978d68d85fe661c918b696364040982c322.nq.gz
    ├── 61909456e8ee98f9bf724a7c6c44ada747a1c3a1.nq.gz
    ├── 62d95e5b92f69c250f59d21274b5f6a9ee4bb95a.nq.gz
    ├── 657141e84e5965e5af95bc2b215851fef4e06f90.nq.gz
    ├── 6a0d8270c90ca894e334e8d5fefb14100eab6b5c.nq.gz
    ├── 6a1c8f6b49bd88bec2c509b580eb863860e79f45.nq.gz
    ├── 6b806bba4a28a5fcc8b73e59726260e9ab2caec3.nq.gz
    ├── 6bb7f3b5e5d50b87a314a0b3a6108867631d2ae8.nq.gz
    ├── 6c7faca6fc23d5f55dbea627e8f6c0b80f50b13f.nq.gz
    ├── 6e627294b457e3a95dfbfc1a31ed2667641819d9.nq.gz
    ├── 6e8aaa6c57e47e54e144624f5b3c3b37a2b78618.nq.gz
    ├── 6e9c6556ff399e8c210939e1b4c4e38c24584f1a.nq.gz
    ├── 701df228d97e9bf3f2b10c5634107daff2f7bd3d.nq.gz
    ├── 711de337f366dde15d8b647c25df5215e246539a.nq.gz
    ├── 7188eddf64ef53d4e0d7aa76e072f0e0c5331073.nq.gz
    ├── 71c759fd8b17baf647f47c5565ec64058271cdf4.nq.gz
    ├── 72a7441eacbc8e49b276d3330fa5d61fbdec8598.nq.gz
    ├── 72ac873b6822aa576c3a950345e6cdd0b9aa3b91.nq.gz
    ├── 742cceec5a9ea09ee0c4a69d2f1ba672205a5993.nq.gz
    ├── 7560c480e67c916168dfbb3228567bf4472e6db8.nq.gz
    ├── 75a763ff4ce8f2b21fbc4cf376f2ff1845ba80d0.nq.gz
    ├── 75b600d5c9a38404e42cc6d25418dac0dd1c9bc0.nq.gz
    ├── 7a311b73a057d5ca22e85db58119cc49e2155269.nq.gz
    ├── 7d92bbd3936147effaeadf4cd09bc61fd6be5c4d.nq.gz
    ├── 7dfded18cd7790e8f9c04984c3876f830f7bc76f.nq.gz
    ├── 7e356e37be913646b3cbd9d9ec98ba13b7da4c74.nq.gz
    ├── 80321c76e76adbe7910d641ec212c4fc2cfa6c4a.nq.gz
    ├── 844dc1057d171dc2dbec30e1094184a7c18bcc42.nq.gz
    ├── 858493d78f9b29c12eeba49ed415d0e7346a205d.nq.gz
    ├── 85f8fd8f6988e8cbd90fa3beb8bfeb9c3b549d26.nq.gz
    ├── 870ef8fe97bbe82104b6776b30d6154013d15938.nq.gz
    ├── 884fbfa9be9d3982f75ad2767c058c2cbca34351.nq.gz
    ├── 8918769bae6ee0af78ee16898cb4d46d6f7b3ca8.nq.gz
    ├── 895670ca86b113c492858a0c47bee0a96da73e50.nq.gz
    ├── 909c59934545426b307e28a3bf8b378bf009627f.nq.gz
    ├── 90dc8d2ad37a9336e4b3fcabe50d8693a75db2fe.nq.gz
    ├── 911e6f647ed361f7769bb580e2bc9c04c953337a.nq.gz
    ├── 91b0c400ec5f9f6bb4caa673ce9df66527996b27.nq.gz
    ├── 93ac7bd911ccca29fea06c7a8f593925094a4158.nq.gz
    ├── 94af46c0d867b858ee2310ce2793c212bfff172a.nq.gz
    ├── 960cd07a6cede52d9125e176724ea6d25f070b2a.nq.gz
    ├── 9814a69dfe59d051f640da26bfec23b6d7f7babd.nq.gz
    ├── 98780c31225c20fd88511ae4fdf71756090bb28c.nq.gz
    ├── 9de77bbadc5ac4b40fabaabd9a9dab81d794d3e2.nq.gz
    ├── 9e0ce6c145b1769cea979772072bff90ca23d65b.nq.gz
    ├── 9e4fb4665d42b867e035fb8f01576cf6d8876045.nq.gz
    ├── 9eaefe1f7c98624219d2c4ef3e4c5e55fd17870b.nq.gz
    ├── 9f1435f140beea9b9f2f18d4740ecec6b1b6fb49.nq.gz
    ├── a38a6a903044d8db593c88d846cf9faf34790cfa.nq.gz
    ├── a404c291150d754ceffd296b89652af8f537c0fa.nq.gz
    ├── a59a7f33161aa6886b2b44534efed66fa6a586a6.nq.gz
    ├── a5b88bb19a476a12a0e63e872c0811ca8f401e0a.nq.gz
    ├── a5bf69f745f296716c6b697865b7ce560f200a2a.nq.gz
    ├── a5ed7cf05f190e4c22faee0bddeb247b90e561a1.nq.gz
    ├── a6d5cc1f53c28888519f273c55a25bd266026e78.nq.gz
    ├── ae958d67384909ec32ff2376c54c38caa679b29c.nq.gz
    ├── af00ee38d2c275968f0f54620e3453010a1fb791.nq.gz
    ├── af4c6d60968024efb0a99160667ac5073d9a9873.nq.gz
    ├── afffd0e93015a19393d9f066545ffd37b9ae6238.nq.gz
    ├── b0f7d30dc68fc27a118749281f77b13e904aa752.nq.gz
    ├── b233d0e36c3c3a45b9d8bc4972651649a2cf9241.nq.gz
    ├── b2e76af042109cfd0394596497b271692aff4fea.nq.gz
    ├── b421b46effc6ed039a71ca7845425ef1766af54c.nq.gz
    ├── b5698859a5baeb76946a6b964396b2e2b461cff8.nq.gz
    ├── b72269eb8a4baeb76a75a656681aa500b7e9477f.nq.gz
    ├── b8724bb25c647712b5bcba9bc8ddf134773fdff6.nq.gz
    ├── b8738698919e1bcb924b1c93b6d06d67e3e0b3b6.nq.gz
    ├── b916d5532ee7d9cae97291cd8ac73f9fb7ff1868.nq.gz
    ├── b961797832d4c08c9a24cf6b4ee63c8e694c5c9d.nq.gz
    ├── ba7ec414ff70c3ab5b6eb9b5a261873b8e8afd22.nq.gz
    ├── bafa14087e642d64613c5ea3f4e4d1b9bfd3cc70.nq.gz
    ├── c067e646d125f8a1bf3d2533c22ad001ccd39556.nq.gz
    ├── c17db2007eb49a69c4818d0e6c0f7de39ca32ad1.nq.gz
    ├── c4572bc302e8b666e0266be1e3ca7cfefeb44236.nq.gz
    ├── c4ad62e5fedb440c637326b4ec45afc53f43c8d6.nq.gz
    ├── c62c3d2d7886470aefaf01320104d71676922d07.nq.gz
    ├── c82fbdc43315f20dec5973542beecd85521deb24.nq.gz
    ├── c9a910ed4b6a7b559e7b06653ccee71a28bec209.nq.gz
    ├── c9eebdf3271ee88afcef6cff617b922ca0a80178.nq.gz
    ├── cbe12b32b50adbd23e3aa402c733732419a8c270.nq.gz
    ├── cd3e7c6299d628d18a6658a60307586922d6eb6e.nq.gz
    ├── d06a45d5cf8c7d40f6b5e56cf6050daa9dd2e8dc.nq.gz
    ├── d0dc388ad56e3da49a695d8bed719e28c982c3c0.nq.gz
    ├── d1e1b7f8efd4f88afbe12d39872e84409bd85ed6.nq.gz
    ├── d28987f4721f9a99e5c5be012cdefac76cf5f52d.nq.gz
    ├── d32aadd64c531f113352139600fcd0ed51a4d580.nq.gz
    ├── d58494010d8a05c6b81497911f5a7099cd1eda16.nq.gz
    ├── d6b2a19e0759a1c42ea580869544ec2ecaa0af23.nq.gz
    ├── d72a5bd6f4c9f9cd81ebc6d53e980ab907880543.nq.gz
    ├── d7ff78698abb9d3e019c2004943eee3eaa19d00b.nq.gz
    ├── d81abaabef9d9ba68e0efd5c7715bc3a6619c8dc.nq.gz
    ├── dc012fd5c1042fefff59873a5063c05650adce79.nq.gz
    ├── dcfba3f80bffc3fbd3342cf1252ae0c949a89e71.nq.gz
    ├── dd9e19cdd272df41fb2d00a8b319ce4e6c578bb8.nq.gz
    ├── de945367e490503815fa4ef194abd816a18e7ce5.nq.gz
    ├── df9d913b8d62a9aed4de62c3f485ed9825422a9d.nq.gz
    ├── e1086f8b3ec1462d658c53c26246821cec14dbf8.nq.gz
    ├── e1bf70b19dabf6bb9662a516bc303a9212077690.nq.gz
    ├── e2724a3dea78ddb615b31eb4a1d5713501677525.nq.gz
    ├── e304d755c7980165d8a45ce49316920bade73502.nq.gz
    ├── e5a70c3f9dc7ff47a410524a651e6b1f7ea6ba8e.nq.gz
    ├── e5c929c0b52fe1d71d9083dcd500028475031a1f.nq.gz
    ├── e632504672b5157f7b6d2355f85aaf8c99c69b33.nq.gz
    ├── e95c29ec8881ae1234ccee4c6d953b03437022f0.nq.gz
    ├── e9f6b2fb1f12f5c94f9f33041374f434793f601d.nq.gz
    ├── eb422f6828961b3d651b4f9924c6444f0e0f3f30.nq.gz
    ├── ef3a858833f84fb9e2d1779ad219868e348bcf67.nq.gz
    ├── ef7d8a13137d301cf00065297e9d04c19768329f.nq.gz
    ├── f0249ba414ef75bad066383f8c136a9329eae720.nq.gz
    ├── f10638fdc65c7fe40acc41e7465ee3a64a150f35.nq.gz
    ├── f2bd623dcdae58e82111fec2ef98b2635ef7f31f.nq.gz
    ├── f3c2be0a082dedad2cb547e726cc951b29dbabdd.nq.gz
    ├── f4c1c8861d2184214e72f737d2398c211daf514f.nq.gz
    ├── f5e62887d65316b14e7068b859768cd0a5283a3c.nq.gz
    ├── f639cfa665505f8045a57dccd39219a185c0ce48.nq.gz
    ├── fac1814b1c16da23a003129e1c1866f9c9727023.nq.gz
    ├── fae90f8497ffeb7b0c9bb3ae63345f73eeecf2b7.nq.gz
    ├── fbdad4b4aea6e4aee098c3941efff986b67a39e0.nq.gz
    └── fc37731f836f1218f1780102991c72c4d0e31c7f.nq.gz

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

[sdispater/orator](https://github.com/sdispater/orator)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
