# Repolex Knowledge Graph of microsoft/DeepSpeed

RDF knowledge graph data for [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed), parsed by [repolex](https://repolex.ai).

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
rlex download microsoft/DeepSpeed
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 036230e4f97c728204f89b1f8214addc9465b5c5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 036230e4f97c728204f89b1f8214addc9465b5c5
│           └── chunk-001.nq.gz
└── blob
    ├── 003b6c4d50542d80fc4b406eb8cd5c01ec8215a6.nq.gz
    ├── 01f3f4e96571786972c6f24bf15464f0ec9da613.nq.gz
    ├── 0282847d735cb8180fdc45f96f7f25e89bab611d.nq.gz
    ├── 0301ff7770426994fc76cf3e6087586287c96c0f.nq.gz
    ├── 0352b8f6a7e21abcfab218c846e9dc68dad3f343.nq.gz
    ├── 04a6347bec5980810aaa7888b99a2187cff591f8.nq.gz
    ├── 04d653544ccd46379217c08c57179afd922b13b3.nq.gz
    ├── 050f21c3bf3a471d3695770be1d7eab4e2c6ae16.nq.gz
    ├── 053ad5da77460974cbc34361dcd887c5ea2851d8.nq.gz
    ├── 05463c75138ca5e9517788849b2818b515a4c18f.nq.gz
    ├── 0632f92db51b3897f01993c2514320a63fe2b3d4.nq.gz
    ├── 0655b0ce26a3ed1ffb16c330bcc964add185ad5f.nq.gz
    ├── 078d8f46fb394cbebe901ce487888a02a252cd8d.nq.gz
    ├── 07b26ca3129968f8d78810df5187dd92c3c166c9.nq.gz
    ├── 085c0b1b2b9a50680498281f3a13dedb6079c80a.nq.gz
    ├── 08db7d2f8afaf4008b6b74f22f8372ac8998f9f6.nq.gz
    ├── 09bebbbac8f3349fbc9ddbd416c9a447344464a7.nq.gz
    ├── 0aaea236268691618ecd2c16008c6f1dd35f8b40.nq.gz
    ├── 0b2ce8c2b56f79f9b7932625f826c6295e6633fb.nq.gz
    ├── 0c8438aea40d4ffd588a496844d692c9a17faaa6.nq.gz
    ├── 0ced1ecf207e80157e30fcb9f0b1893597d899be.nq.gz
    ├── 0d9e9e6de9b85b6ca48f61344a6e1533bb89abcb.nq.gz
    ├── 0ed2f43a61348d8bdf19552543bdefed54c06a47.nq.gz
    ├── 0ff7c34dc589af824e29ed1db4f5cac32731a3df.nq.gz
    ├── 10a80018a9bff367299706695a90dd47461f129d.nq.gz
    ├── 10fb638347bcd9132abc365ba8f488551ea7cb01.nq.gz
    ├── 114fbb9d3ad61970bd31e97f4168b9b07ab9c1d7.nq.gz
    ├── 11603fcc576c4576eaad71817479f942e9e61c21.nq.gz
    ├── 1168d2a749cefb772f492dfcff69ccf727c28acf.nq.gz
    ├── 116cedf926676bcb32e6684ed3f3206392e443e9.nq.gz
    ├── 117adfba22c08e28ec2f757270c0937a1893526f.nq.gz
    ├── 12b014d909880da286ea76b264a72ee15d05d2a7.nq.gz
    ├── 131708132c3e040765b75605d6610a911641763a.nq.gz
    ├── 13e79bacce4a3ffb88b8634a90af3912c2110110.nq.gz
    ├── 14abdd1d9d632d265be8364301a3757dbe536581.nq.gz
    ├── 14c300d0bc9f4da71f5aa559b5cfc47480e56a10.nq.gz
    ├── 150c880afbcaa19e240060810a8aa61714df95ed.nq.gz
    ├── 166fbcb03272af075b4709b7dfb82160ccc8e04b.nq.gz
    ├── 16c0611c9105faab4362081344e5964f8b45010a.nq.gz
    ├── 17b2ffbb9d29247535d888d054d7a92f0c3079d5.nq.gz
    ├── 17b6479ed8c53711a4b0c5fd7e23bee44ff9e142.nq.gz
    ├── 17def1fa021fb1ce8c23b9c30ca5c27c40d67488.nq.gz
    ├── 1897afd1fea248f497acf3fb6ba049baa1ca56c3.nq.gz
    ├── 18be3c84337019898932d3d65c6f847844a11715.nq.gz
    ├── 18c43c75e0c5af0a4744f74c93a367e15a68d2a8.nq.gz
    ├── 19405123e79ac23c98565fbfaee20c19d12bee7f.nq.gz
    ├── 1ab7e5f0b7a2455ad3e60bb12a9d262900340e45.nq.gz
    ├── 1ae13599d4e8d430859ee0e79b91d69ec144e026.nq.gz
    ├── 1b500a9a0b5a25b17696bffcbcc5fa1ffd582de4.nq.gz
    ├── 1bbd21dd5e329527241e57e7ee6da18170639d54.nq.gz
    ├── 1c291bcf7a99f66bc574bd1b3d23f1f418d2f24e.nq.gz
    ├── 1cb62d0d17d55d70980eba1a0a17a77cc89e733c.nq.gz
    ├── 1dd3a3172d41aefe79839f85293382484ceebe88.nq.gz
    ├── 1e6021d36e987f78c8253010097e65aa808fe34e.nq.gz
    ├── 1f803bba10c90d3fac15ef9540f9ca24c69f716a.nq.gz
    ├── 1fc99199f8d63c199c523582df5c6a377f2341c1.nq.gz
    ├── 1feefa9ee5885e71661b67f4160bbf85396ef966.nq.gz
    ├── 2058791dba4aed540f8ac2ff702e9a4efb7a99bb.nq.gz
    ├── 208299fb8c50f73468d293b6fa5dca71649d62e7.nq.gz
    ├── 2094448d534d6d1c237f42e062e6dd050df8d87e.nq.gz
    ├── 20b7bf12a917865a753d9db41851562edc8cb337.nq.gz
    ├── 20f37538274ccda7ab68ceb7e82c87675120b7e7.nq.gz
    ├── 210f21b7c4d67a4f4e3b5720efde5c2f5c1db9e1.nq.gz
    ├── 249742298da6c94484bcfa9f0b9f72641e8ec1f2.nq.gz
    ├── 24f710d224949a5b7684742b7ff7cf96eb007122.nq.gz
    ├── 2556d0264efd728e63a5ef1d2c65e20357a665b5.nq.gz
    ├── 263a30be27c5ca0faa1de732151b5f67bdba4d05.nq.gz
    ├── 266f8e922a2cbfae924ec2a12aa0f5f8c7916dbf.nq.gz
    ├── 2689d8d4bb1cbf5d34c500a21118c700c230b470.nq.gz
    ├── 271b88e272197ace88e55d3eba454fe152562754.nq.gz
    ├── 27220e3714664a13984f46cf16efa5189e4785fe.nq.gz
    ├── 291d4cb2cb2d310e4eb4a2ad447d820c591bb183.nq.gz
    ├── 293f56af2a15d2bd39385590c02edc1295c5e0c2.nq.gz
    ├── 2aa7c3054df2f25d33ced3a18631615d616522fe.nq.gz
    ├── 2aef0d48475f76a5b181512f0dda301e2696b5fd.nq.gz
    ├── 2cb1aa889291d63dc93bba27494c42e11aa9139f.nq.gz
    ├── 2d2468329fa5d8684314334dd17c6d4965ae8d55.nq.gz
    ├── 2d9ca634a6a0b49a65efa2f6602dbc092a038463.nq.gz
    ├── 2f6e7b7464859c2f9c7b13e409575063214c3b0e.nq.gz
    ├── 2feb57afa6ba7224d327da1f4f14944afbe93493.nq.gz
    ├── 31347636b50c40fc74f0c477e848a9cddbab0c92.nq.gz
    ├── 3137c08d3db4f7802c274119a26dc31a1c13fba2.nq.gz
    ├── 318ac9447efc5857b88c483eb6883e349e0231bd.nq.gz
    ├── 3195eb788ae10f680313948e9d61023e5b4d8822.nq.gz
    ├── 325bfb4f7e181d8b718748fd5ebf2f4f1ca3af64.nq.gz
    ├── 3266a425b102f9105e0d2deac57bb1a353a4d201.nq.gz
    ├── 3347da182c50893b8644c3ff030ccd12a6cc4a51.nq.gz
    ├── 339dccffdbeec0b065e3ee4cc99916b51ed900e7.nq.gz
    ├── 3429e69b47de32cd14346b8fd4ad1c7d0ac460c3.nq.gz
    ├── 3485024ee5371702c47df0ce8bc2f1a58005d86a.nq.gz
    ├── 3760ccab852a5ceec65fa6693070a84fec284d8a.nq.gz
    ├── 384e2f0b26a0e5f0aaa94367a437b2557946fec1.nq.gz
    ├── 38790238fcd2123afcbf8c4dd41416f53b85b6ad.nq.gz
    ├── 38b0e7f3d582535958efd33c3b5be1a8be44a3e6.nq.gz
    ├── 38b4d1dab341f67e165a10a477faa39bbc7f54e6.nq.gz
    ├── 3907fc3e3a4bf8619c7b70413e71089e8f40f460.nq.gz
    ├── 392e0ce9218d7f6aec5d8e4f6092f6922c09af62.nq.gz
    ├── 39e8a8420bdeac84298404049958499d7be53c34.nq.gz
    ├── 3ab107e75a9147f30176f9e3f6bc575898d8e572.nq.gz
    ├── 3b4966eb822b245990a6523fd93e6727e277730c.nq.gz
    ├── 3c0762c810766ebc7bc832e737d7e773216475b9.nq.gz
    ├── 3c2aa5cb5eb4553010bede7c777268757bd897d4.nq.gz
    ├── 3cb74f4c49d25a9520ad3ef00343bb66ae79345a.nq.gz
    ├── 3e3a42855f448e0afba0a98e15dea5a4291ffa15.nq.gz
    ├── 3f7a44cfb34d5cfc5a4a288bdcc650216707a38d.nq.gz
    ├── 3fa53f31d4204bda235942bb4e948505c0b48393.nq.gz
    ├── 3faa07f23908175bb3a5d7699204e496d53967ee.nq.gz
    ├── 404084cb6c3c1537dedb47c9649d91bee5417f5e.nq.gz
    ├── 40926b776cf2f0bd3c46f44c6eda2ed3ec6bfce5.nq.gz
    ├── 40a9c9a7d5b3af172c02bb67df493a33b5accfde.nq.gz
    ├── 40d3265c7a638396ca5c12282f7da56fa63c925b.nq.gz
    ├── 4153a2a3636fa536c0884df636c77263441c5cf7.nq.gz
    ├── 41fbce58e1ddf28516a49ba93c603e06df93fa1f.nq.gz
    ├── 424c527abd5664267d70fdd9c1654f07c337fee0.nq.gz
    ├── 436712590c44c29348c00fe81618dc3a822008c6.nq.gz
    ├── 436d7f8805d5c4df552d239a5a64b620bd57eea9.nq.gz
    ├── 43d82d724ed2416e15d768fcd9f04c64bb50daa1.nq.gz
    ├── 443f12046b27474fc5a202c0163a709b524dd681.nq.gz
    ├── 44b8e67bd6b950ad072443b7969c82aed90267f6.nq.gz
    ├── 44e3b0e2990c1e6dcb6fab270d0a452ef2970245.nq.gz
    ├── 466ce049d34d58eeb93c03387b00e0e444396ee5.nq.gz
    ├── 4675e2041d84f00c7b9a5755e961d4e7b2673b00.nq.gz
    ├── 47f170e64eeb792044875112a30c8cbe80974cab.nq.gz
    ├── 48179265553150824855140750da3fc6e41503ef.nq.gz
    ├── 499473b4ced81ba5ae5a447e32e03a2971b63c8f.nq.gz
    ├── 49f5f9c60f105bc598fb2484fa55ffc92638a5af.nq.gz
    ├── 4a3d8c8f8dbf5f545699055a3ae017d22d917b56.nq.gz
    ├── 4ad48dbc8c39b535c6c2e30b47ec331250d7d3d0.nq.gz
    ├── 4af5a579ca1bb253b044c36c44b72e8cc0caf931.nq.gz
    ├── 4b00bb78dbce6f5da7c8e9d9e3d1969cab2b0872.nq.gz
    ├── 4b081a8e61bde9304c8f1bee920bb8729f1c6aef.nq.gz
    ├── 4b1b392e933adc42a1f1b18ba54c272d7f8c1903.nq.gz
    ├── 4b9c1692686328580b05771536b455fb87106424.nq.gz
    ├── 4d9dc5445043229ede5ef7c9c2daf7f7521d7bd0.nq.gz
    ├── 4daccf7d7c8d4db06bd65243bd83a5f1fd50df2e.nq.gz
    ├── 4dbd1d4773385db8e40a9e2f0ac8d6ebf2433c7a.nq.gz
    ├── 4ea27a802570ae472a325ee6af180208d80574a4.nq.gz
    ├── 4ec0a1bbce3fd3197a264d8da5da9d3f36cb8c4e.nq.gz
    ├── 5037021ec466aa84fc5c881cffd49833f949f173.nq.gz
    ├── 518bcbd8e4390ae44cd2a6aa26f0f36756239103.nq.gz
    ├── 519781246289e12766b1c96feddad1c4c74ae323.nq.gz
    ├── 528e40b106c6cf14cfda42d430e84fc6bf69a892.nq.gz
    ├── 529b5eb916c090040b03d4ae17f7956bd4ee18a0.nq.gz
    ├── 52a44e7a23491a0846c54fcde2613d52b80451f2.nq.gz
    ├── 52f89e182ce10f339c4709347a7617848c0f12b1.nq.gz
    ├── 53f859e9cc87bde8f16760a4c23394ea1207af0c.nq.gz
    ├── 5458a855abf45c3870c2208663dd5f49fb4fb22b.nq.gz
    ├── 5490e38bbf3ed169896d7c47e4df1a60090b8891.nq.gz
    ├── 54af7150fb36f9eb8bd6a295648d8a11da8d8373.nq.gz
    ├── 54c33885d26f23140503a45df806b1421ac6c2af.nq.gz
    ├── 5505714219bbe3d67d20bb0f68547e44f9c100ea.nq.gz
    ├── 55d773a0d69cfd6ac10a358464e6ecdd3fe04261.nq.gz
    ├── 5674c0ff047ae9556b6272e7f4208eba6f7ec5ea.nq.gz
    ├── 57fbfe38c45d4b6d54ac1ef4b07a6da17f732b91.nq.gz
    ├── 583736fb8bbc0ebcd07a63452ce029b002d6d937.nq.gz
    ├── 58bde9d78e684b0ef9b97d02777e1329e881f269.nq.gz
    ├── 58be0990b944854dac045383403ca14460ab4c04.nq.gz
    ├── 5957ad771974010e98c7d57b7743f1c64da14ef6.nq.gz
    ├── 59597f63d12348b179908bd70d74f1e12696f326.nq.gz
    ├── 5a330562b39c6960db5b660f12824733238f0536.nq.gz
    ├── 5ac01c1932d48b2d0e35aba1a82ace8d6b11663b.nq.gz
    ├── 5b1771fabc22f6ad13161231900a737bba733e68.nq.gz
    ├── 5bd0bacb32072a5b90804d27b1e639bb94519c40.nq.gz
    ├── 5bd8e728caf1b1ea3b82a855791adede9f478740.nq.gz
    ├── 5bd9badbcb4fa06091a8c01b0b0d386153a24589.nq.gz
    ├── 5c68f1dade7493b9edabfd32efbb02561f5bc1be.nq.gz
    ├── 5c6cf05d3e7a2d47c2d0dfb7ac25653024bcf8b4.nq.gz
    ├── 5d84e9be855af3d3bf38631565264bb7a4621d5e.nq.gz
    ├── 5de4cb8767a6380b7717d337e118c735b26b65e6.nq.gz
    ├── 5dfd63ccdc32ac1d98d4f3e2dfb429ef367a45b7.nq.gz
    ├── 5e7a6fc4e834dfa0d28bdd52e1e04cc7a8bb204f.nq.gz
    ├── 5e7bdb970a9d6432653cea76c371be03443fb617.nq.gz
    ├── 5eac4c2909997dab6aa68fe865e3c15d16a6a18d.nq.gz
    ├── 5f0c98d569ac066410392fe87943ed586060f0c6.nq.gz
    ├── 5f21aa5c224a1dd12c5ecf51656daf0f84303896.nq.gz
    ├── 5f300b19a8da0493a79425579c18f070d32b0bb2.nq.gz
    ├── 5f3f0ee507e53bb0ad7a0f8fc3fcd25982c177f7.nq.gz
    ├── 5fa0c8a079f0953da4abb906cc19eae9bb515dcb.nq.gz
    ├── 6286294ad60291e1db6de6f0e10d76c162991903.nq.gz
    ├── 629047dbb057384ac8f0d7fa5d557e0c070cd830.nq.gz
    ├── 62ad309664b8b2a6599f384cb683d036e525d3fa.nq.gz
    ├── 62bc9d056ade4aaf256a5eec48f42e61edbd80aa.nq.gz
    ├── 62ebf73919e9157cb150050e2da7da8defe4fe9c.nq.gz
    ├── 63421bc1c622822f3975680bdbbcffe66b261c4d.nq.gz
    ├── 63ad33d41c5bfbf05806fc0f5a2b761a00034722.nq.gz
    ├── 645faae47eb1badb276de3093a88218648b0e0c8.nq.gz
    ├── 667f1982d30d295498b952f0a681af29796a1521.nq.gz
    ├── 66f64079531ad5fbad00fd5ac44a95cf2cc6262f.nq.gz
    ├── 66ff5b51ad2d832c024d90c04d0f818b3d106a11.nq.gz
    ├── 675815dd5d57f970ef5314ff0305e65749341ae5.nq.gz
    ├── 676d0ebdc42f80f49301b18408b22b95515dacb1.nq.gz
    ├── 6777788ab885a618544ced9ed9448e08c5159751.nq.gz
    ├── 68037b4251131747479ce93d6ac5df5a8af0b028.nq.gz
    ├── 681fd634764c45a76b98a2a49248fd2875569389.nq.gz
    ├── 68865cdb6b8c9b2f08065944d0e769e0746a153b.nq.gz
    ├── 68b7bbe514eea6d7714a6f8b6135ebd622a1b7f9.nq.gz
    ├── 699cad2f1c3f99858bf242a86b9d6cd1b221e50c.nq.gz
    └── 69b90e848ee558395eb6d0a1840bab35c3eb4508.nq.gz

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

[microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
