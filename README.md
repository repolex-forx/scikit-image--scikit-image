# Repolex Knowledge Graph of scikit-image/scikit-image

RDF knowledge graph data for [scikit-image/scikit-image](https://github.com/scikit-image/scikit-image), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-image/scikit-image
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── b700edc8005e4ee9e74fc83259f09e8df3213f15
│   │   │   └── chunk-001.nq.gz
│   │   └── ee0a7a3ebd9ac8c2602f40e55bc015a3c8a81ae8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ee0a7a3ebd9ac8c2602f40e55bc015a3c8a81ae8.nq.gz
│   └── repolex
│       ├── b700edc8005e4ee9e74fc83259f09e8df3213f15
│       │   └── chunk-001.nq.gz
│       └── ee0a7a3ebd9ac8c2602f40e55bc015a3c8a81ae8
│           └── chunk-001.nq.gz
└── blob
    ├── 001d5a3929099d48949fdbfff765093431520ba7.nq.gz
    ├── 0043ca0826218dccd9beaaa704facc443eae3071.nq.gz
    ├── 00751b37f4a2009064606b11c91f0b047de4819b.nq.gz
    ├── 009d4d63bd0489fbaa8003975621de5ad9d561b5.nq.gz
    ├── 00bf7a4652f420ff7f59fafa7cbe4a65b2c1cbd4.nq.gz
    ├── 00c0b7cad3353292b77ea53d2eb80b36708f0189.nq.gz
    ├── 017d268bc4b9f07cc9bb82318e9f0bee961871cd.nq.gz
    ├── 017f1ff6382a5a651ae83e937de484aed04b8ace.nq.gz
    ├── 01a8b726606eb04d9d359933ce976096215904a1.nq.gz
    ├── 02074625ab71f6c68d34f02273bcb9412be0a41e.nq.gz
    ├── 02132e75050fad74775862e866ac353ae69858e2.nq.gz
    ├── 02d5cc833f7b40e31d4d68d9ef2ee8bce37bdfbd.nq.gz
    ├── 02f15171dd2099350e5c126ad592b7f42c242d9c.nq.gz
    ├── 03070c0edbb9422995824912d76f75aa6fd5eb51.nq.gz
    ├── 031816f24dd549629a17ca55a4d6318c1b687921.nq.gz
    ├── 03f13d4cc2189ad7cdda415f5de45d99771aec39.nq.gz
    ├── 03f496405230890b660eb9f2666af6c390d662a8.nq.gz
    ├── 0433d3fc7c421917c63cd6d7849786b67c248496.nq.gz
    ├── 04a13dd18cd48a8d9c46a33fcbe75c90fcce918b.nq.gz
    ├── 04d5a1484ae518f9eb0d65a266c9f2760de3b6c6.nq.gz
    ├── 04e6d69a3384eb70ef19836efb401f7dbe2e4f77.nq.gz
    ├── 05026e3f2e98adcb7d2ef2a4718bd3c647175da9.nq.gz
    ├── 05bafe09a281aac18c062ad4350deb8dcfc307f8.nq.gz
    ├── 05fa2f40c0b642b796ed254ff927919db29eed55.nq.gz
    ├── 069974de16de6e0ad92dee1a693bdbd704e4d3d2.nq.gz
    ├── 06b631b6a736cf4c3d77241624cc3cf7ba01c8f0.nq.gz
    ├── 06defe96f96b48d0dea6c66b4974e4f3ef1daedc.nq.gz
    ├── 06e01ed7c24bcf8aa32f70085905641039513ae2.nq.gz
    ├── 0734c601ca0e28d059cbd5f5466385d84ec5b53e.nq.gz
    ├── 075018723c4ed44090d41b898c6fb25dcf0098ca.nq.gz
    ├── 079a45d87cc8aefda8f5b07a53a7eb654e52ecc9.nq.gz
    ├── 0849ad2fa8f84fb72b0546b3d0963d37030533b8.nq.gz
    ├── 0850774be961158956fa1ad855e2e457f07e7101.nq.gz
    ├── 085c715572f31d77d2142185f590f1ac5f888c04.nq.gz
    ├── 085c77c28ff3003797ad0655a528aa08f93b3f1c.nq.gz
    ├── 08699c314daf0df76637ee2573b621c91722aae7.nq.gz
    ├── 086e15d0218e6a485a69de4aebba563c85b673d7.nq.gz
    ├── 0871aba41e98619d67ac124145a5a86c7c4fcece.nq.gz
    ├── 087e26efae100e4da562ff4b7d1fa256835d3725.nq.gz
    ├── 08859faac23c76080c0d6dbbb7dacf7e5adad558.nq.gz
    ├── 08ad2f7ebc583503fdb1a2d88ae94f2479860f29.nq.gz
    ├── 08c9a66d454b8a5996bd77beb79988523b56af9a.nq.gz
    ├── 08d904ffdeae11d1f216df07d1342b7e0af04743.nq.gz
    ├── 090d2139017be57800c46bf526198df72640b829.nq.gz
    ├── 0938ecc850c1c37b85ddbefaf10df8553a61947c.nq.gz
    ├── 0970658fa2be010a4654759373fc5a11757878b8.nq.gz
    ├── 097feea41bf7bc66474b401a68278371b99c607f.nq.gz
    ├── 09eec1061ad5a33281575e00125bf338bb621b61.nq.gz
    ├── 0a28fac4adfa53092db2dde29c928eb5be08da70.nq.gz
    ├── 0a801a2618d2c340c22b89a523555614ea7fe8f3.nq.gz
    ├── 0aa116d0deb5e1d2d0f73f2681efafe6a6928f6b.nq.gz
    ├── 0aad2685ac034a1f1fe29a47411973b997913d88.nq.gz
    ├── 0ab2357dd9b24da46461bfc6311d3a32f1bbae3b.nq.gz
    ├── 0b2786071c55dddebc8d2ebd54debd7102017f2f.nq.gz
    ├── 0b2d9f78c8d1f139bddc1a8cd9dc511280d3a903.nq.gz
    ├── 0b7188b153474f31fafd72800c5485cfae48b63b.nq.gz
    ├── 0b8c30aff89b1572bb836c13e1f2ec0c2ccd27c8.nq.gz
    ├── 0c4042dc1a0a045809ec0b5a5d87af22b62fc978.nq.gz
    ├── 0c53d7aea21a0ccdc6af2f5d0464a5154c1bca51.nq.gz
    ├── 0ca7a8b5f2c2082056d8c648a9fe45068e6737df.nq.gz
    ├── 0d5cb003a1b1ae81a54989a915bab1bbff97b0b2.nq.gz
    ├── 0df756cb8c29ce8bc1a1ee4230c1ae4d72fafed6.nq.gz
    ├── 0e0e2d979a28ca313718b6e0a64af6697d387490.nq.gz
    ├── 0e4f0663ba8ff642149140f70c6a5600ac0c6d08.nq.gz
    ├── 0e56b4573e1c0e452c24419c8db2af7b0b320602.nq.gz
    ├── 0e75d395bd4e7e155e11dd87ee9137297aaf1282.nq.gz
    ├── 0ea6126c7dff9565c105cb3eb36408b8f9de38e1.nq.gz
    ├── 0ebf2f90f0aaa9587e487098baea538cdf4217e1.nq.gz
    ├── 0ec62b94d1235f370ff5e2a9eeb2afe8c7676c3c.nq.gz
    ├── 0ec64ade775bc8f4e3677a55c397b5e958e468c6.nq.gz
    ├── 0fafa934c4e2b163bb98e599280f0c640c53081c.nq.gz
    ├── 0fc8176d242edf8163a1436adcd4afcef5d97802.nq.gz
    ├── 0fe0796c927c377f382e4c67116738315e459a91.nq.gz
    ├── 106bc39aa6598a7990ad1285d14e6ccba38be9dd.nq.gz
    ├── 10a4888bcc1a193fce288ab5555fda49064c2471.nq.gz
    ├── 10af8a189ad40a75f0cb17fa6de82a813a6584d9.nq.gz
    ├── 10e1962a5bda6efdb9e5d9cba380aecb8f439710.nq.gz
    ├── 110d8e8d2144925a548d468a7717d702b5824fe5.nq.gz
    ├── 114f9da7b8926ec2c19d5414e80150dbd5d795a5.nq.gz
    ├── 118ae0f61a17fae2668c36a27afdd19361d09c77.nq.gz
    ├── 11bb8140594261069f318623950704d8a075f9be.nq.gz
    ├── 1267e0a550a382a6f049fd9d36ab72eba6010292.nq.gz
    ├── 127c652f477fd734e7a54b0142f6220844ebac7b.nq.gz
    ├── 129cefe8e6aa2d723cb98e2d31ec57eea87b0acd.nq.gz
    ├── 12af9a44283f6121cb8c3967e005e8a64689d221.nq.gz
    ├── 12bca25e9c5fca90f9c57b2bfced616312be3c06.nq.gz
    ├── 12bddf3969b8de2848355c7a4e4b52d691e0f689.nq.gz
    ├── 136ddabcd335aacd504b2e1acd981c71d6990177.nq.gz
    ├── 13bf47ef0cb035abbe51a077b162cb5e69930ad1.nq.gz
    ├── 13c8e7421d0898c0da6029dc1e31c2362176eb4c.nq.gz
    ├── 13f01e9c222bce4980db3739d60c6b3086ba32e9.nq.gz
    ├── 13f78ee5b07a33ba29784500e89f07ea5cb60ff2.nq.gz
    ├── 140344104141d7dc1e74676dd8eb84e7a426d47a.nq.gz
    ├── 143c6103c4846aee3d873b7a5855fbd9dc0f6ea5.nq.gz
    ├── 14ab8f93501e44b246c1c75d2bca75c1daaa507e.nq.gz
    ├── 153dfedbc808a39fa2de747f275235d4708eaa25.nq.gz
    ├── 15a64db2819387474cda53e0f2489e0cf5041d2a.nq.gz
    ├── 15bccd5c73770f2a2f4f077425a22ddcea619867.nq.gz
    ├── 163e806ed95b4d2637b49649ac92b2eb3434ff6f.nq.gz
    ├── 1669097b022040f8211840a3bedabf03ed1da0b8.nq.gz
    ├── 16b458c6d93b5ccaf136cfda6335951d4891ea36.nq.gz
    ├── 16bff6be404dfcabbb8bb3fbdfb3d5e8495efab6.nq.gz
    ├── 172667e3f355007f417297757678c2096a90050d.nq.gz
    ├── 17729967caf38bd68eecf688623a4fe1f40a23a9.nq.gz
    ├── 17af64ebaac3055b76500930e913c4464a236595.nq.gz
    ├── 17b84e3eb183b42f40b2503b52e56b2d8d88d95a.nq.gz
    ├── 17cd75cd3a8fc440b2fbdc53a1ce297b4bb78600.nq.gz
    ├── 1872c252ef089296a7d52641f8ae514aecbd364c.nq.gz
    ├── 188f42b492f04b99970275752298e9cadaf269a8.nq.gz
    ├── 1908af0f5bdeed43cf871e08cbba648b1ba10e1d.nq.gz
    ├── 190c1e2f35f9b3090dd42d28e7ff8c3ccd709e8b.nq.gz
    ├── 19365d56aa64a410e662d868a9e0b9d409a6ae81.nq.gz
    ├── 193b77dc67e611b23e3d5c33ab30bad19fa527e9.nq.gz
    ├── 195cb27a0de3bc154cde833ebc89a66cd545d720.nq.gz
    ├── 19c16b7c62aafac3f0cd0fa78eb4743e030759e0.nq.gz
    ├── 19c40a4e3f522ef239a9b23cbd06631d408659e6.nq.gz
    ├── 19d44484ecc2f74d6ee5fad42aa615ce927c7319.nq.gz
    ├── 1a1e3a75c77283c36e002b18319d5bb9005658e8.nq.gz
    ├── 1a9740a21cf32d3b3e838f4303c292dbde2b2440.nq.gz
    ├── 1af216bc58cf57f380cd6e4d5eaab43083324643.nq.gz
    ├── 1b0e9d32eb8f952a64d50c5fe6a0a15124cd9598.nq.gz
    ├── 1b3fac699afb4fb6ec01f6e387a47dcf24e866ad.nq.gz
    ├── 1b795b9909ad485000402d09b88d0302f8a95fea.nq.gz
    ├── 1b8c187cb5d6ac8b08dfe163dcf19f785366aeb2.nq.gz
    ├── 1ba06a39220fa25e9d8708d56d8209e6837d2dfc.nq.gz
    ├── 1bb7a577732c91ee6aa31de8f81045b5622126b2.nq.gz
    ├── 1c3b7b607dd2fbb7de49d60c60bb5cffb05389e5.nq.gz
    ├── 1c4738da76799ede65fca139a38327a14bb97bf4.nq.gz
    ├── 1c475d91a6a84cf20ffbc2f22f095563de56511a.nq.gz
    ├── 1c4b6e33cffa8945aefff542b31b5f70196d2269.nq.gz
    ├── 1c86cae18a7b6bc387fe8eb3e0ff5068ff184ea9.nq.gz
    ├── 1cded6a4f11c3affa9696fc9c0c560d2a47c4562.nq.gz
    ├── 1d50dcdec2c0c466a29db381d71c33a44450ba4f.nq.gz
    ├── 1d734cfbd1b1bc2e166873df93792f50cdce6576.nq.gz
    ├── 1d9935c3b85172307b5da032504404a0d36dfe20.nq.gz
    ├── 1dae6fe4359631c0014f0c33581556b10a6d4edc.nq.gz
    ├── 1db9fc58d5149a70f1957f9dcb3f572c6e0b0d9a.nq.gz
    ├── 1ddb849c5a5a63fd6c40211a4f98dd11aa4a4bbd.nq.gz
    ├── 1de5a31d48ef0af2b5a79f7ec07ed93a1fd0482d.nq.gz
    ├── 1e21f93b14c62d16411786bf95af569ffae38ffc.nq.gz
    ├── 1e96130c3f2e925a92dcf2862307eca5fbcbc8ba.nq.gz
    ├── 1e99edadb80c7b1b389f582ee7a9c84c87cd14df.nq.gz
    ├── 1ef368552e9c96e9cae3654857e8ee8557b6b9e0.nq.gz
    ├── 1f43ea8409de7370583f5b1ee4385c43a954a20b.nq.gz
    ├── 1f63bf41e50ece485442f0188f9f4ab832d1549f.nq.gz
    ├── 1f989a74ca6d85d35c554512f11807d81ae9369d.nq.gz
    ├── 20067eecff821f7d70fef2f5ffb2b9c306aeacbf.nq.gz
    ├── 200aca450147045b9a015c67db182c5542756484.nq.gz
    ├── 206361a3d4684361f0de401afa4b9c211cff5e94.nq.gz
    ├── 2089702cc21f957cca0a70d787ab536147a3e232.nq.gz
    ├── 20b488a4ab6b2c4aaf77c433129518eeed15add0.nq.gz
    ├── 20e6543aa0a239f5604aeef58f8bd4cd7761860a.nq.gz
    ├── 20f4dcfffd4ae0e2d00146c283b7dabbf635bcff.nq.gz
    ├── 20fee27fc6e7f5f7fc0cf12e8705aaffa8275911.nq.gz
    ├── 20ff86542a9948d2c4e6b9d47007af2ef96de3c6.nq.gz
    ├── 2145ed17b664246b2a2867e205488b24f659e971.nq.gz
    ├── 21efac8b868adca059131d74c5619569aa1339dc.nq.gz
    ├── 22401032f57529a2c86e2438ac181cb597e34187.nq.gz
    ├── 226a9dac4504b66b95976acb7a39853ac905fb3c.nq.gz
    ├── 228c4dfddc2a3acfde981c864a262a727483b123.nq.gz
    ├── 22aa389c58d8cc4cd65710ed630df88cb9e28b3c.nq.gz
    ├── 23046105029b96ee8b418b9cc83815761ada31ce.nq.gz
    ├── 234a62cd1dba13dc98895608396e401eb0ac8609.nq.gz
    ├── 236f09f7bfe4d6a6a67ab0f7c6ae81db7007e697.nq.gz
    ├── 2378cdb14decb6b98ccd725da7a4a8edd5120077.nq.gz
    ├── 238390c9985788cc999374dbb067f139d0b8985d.nq.gz
    ├── 23aa1cea463226d06ab91f9ef602032bbcf8eead.nq.gz
    ├── 23b7ea2c1472766c9e9e2c6edc1d6c1bec99d140.nq.gz
    ├── 23ef2b095fe681f567ccbdc6337571720c8357a5.nq.gz
    ├── 246689553d94f33c36f141ebdf143d1bd0bdaf32.nq.gz
    ├── 2498efe7cdb2f77682df26a53eed8e007a25317b.nq.gz
    ├── 24f9b5e68d4400def13982b2292a1d692bd7bb55.nq.gz
    ├── 24fc06a694a9c3e9b8cabc554aa2661074e8cfb1.nq.gz
    ├── 250635322ea46a1c39d1be984f0fd704b6e86ebd.nq.gz
    ├── 2524505f4fad91c16147c021a426afadb0414ad6.nq.gz
    ├── 2572d63feaea9886256e650485ef5a4aa329d89d.nq.gz
    ├── 25893aecd8841a2eb82673cdefc4ebc62903a357.nq.gz
    ├── 25d4bfe2c16253cf653c214b3b960499a6bd9e81.nq.gz
    ├── 2654f5eeecd1a0156eddedebb0623a01e2f07772.nq.gz
    ├── 265f8a5fde1206d89a20a2a4f70248cdc136f53d.nq.gz
    ├── 268639c33cd931f5724fff021ac772fb3ed6f227.nq.gz
    ├── 268cb719f58b9c60381e6b13013d8ce7cae92dc8.nq.gz
    ├── 26edbe29ea2bc82c4a6ec4b355df065e508d42d5.nq.gz
    ├── 2770a71e68b4871d656dd3f861ae623658693830.nq.gz
    ├── 2777d8f618ffbd6bb478157bd61f4a7d655db251.nq.gz
    ├── 27828b843e465c49ed9793154f461f5d25a8e197.nq.gz
    ├── 27a3fb0b8c4f70d382b603882762f1261d5fd67c.nq.gz
    ├── 27eba35b68d010acef5631cf74714a521db45afc.nq.gz
    ├── 27f72205c298760d973867e7f386749ecf851efa.nq.gz
    ├── 284f021a27d927b0871fc598ca777f8887ff6495.nq.gz
    ├── 2855224d2c4d56368bf3171f662ff962ecf99255.nq.gz
    ├── 285c2ebae4348a5e0c9e78c4e7a6f519da4a25ec.nq.gz
    ├── 29076a0bca4d4f9368da6dad10cdc67cbc77cb0b.nq.gz
    ├── 2933c48462db42b4eaa34a3832337fac75c9321c.nq.gz
    └── 293671fa26f3551c515fe229c5e18dae2a503344.nq.gz

10 directories, 200 files
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

[scikit-image/scikit-image](https://github.com/scikit-image/scikit-image)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
