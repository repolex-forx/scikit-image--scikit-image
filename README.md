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
│   │   └── b700edc8005e4ee9e74fc83259f09e8df3213f15
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b700edc8005e4ee9e74fc83259f09e8df3213f15
│           └── chunk-001.nq.gz
└── blob
    ├── 0043ca0826218dccd9beaaa704facc443eae3071.nq.gz
    ├── 00bf7a4652f420ff7f59fafa7cbe4a65b2c1cbd4.nq.gz
    ├── 017f1ff6382a5a651ae83e937de484aed04b8ace.nq.gz
    ├── 01a8b726606eb04d9d359933ce976096215904a1.nq.gz
    ├── 02074625ab71f6c68d34f02273bcb9412be0a41e.nq.gz
    ├── 03070c0edbb9422995824912d76f75aa6fd5eb51.nq.gz
    ├── 03f13d4cc2189ad7cdda415f5de45d99771aec39.nq.gz
    ├── 03f496405230890b660eb9f2666af6c390d662a8.nq.gz
    ├── 0433d3fc7c421917c63cd6d7849786b67c248496.nq.gz
    ├── 04a13dd18cd48a8d9c46a33fcbe75c90fcce918b.nq.gz
    ├── 05026e3f2e98adcb7d2ef2a4718bd3c647175da9.nq.gz
    ├── 05fa2f40c0b642b796ed254ff927919db29eed55.nq.gz
    ├── 069974de16de6e0ad92dee1a693bdbd704e4d3d2.nq.gz
    ├── 06e01ed7c24bcf8aa32f70085905641039513ae2.nq.gz
    ├── 079a45d87cc8aefda8f5b07a53a7eb654e52ecc9.nq.gz
    ├── 0849ad2fa8f84fb72b0546b3d0963d37030533b8.nq.gz
    ├── 08699c314daf0df76637ee2573b621c91722aae7.nq.gz
    ├── 0871aba41e98619d67ac124145a5a86c7c4fcece.nq.gz
    ├── 08859faac23c76080c0d6dbbb7dacf7e5adad558.nq.gz
    ├── 08d904ffdeae11d1f216df07d1342b7e0af04743.nq.gz
    ├── 090d2139017be57800c46bf526198df72640b829.nq.gz
    ├── 097feea41bf7bc66474b401a68278371b99c607f.nq.gz
    ├── 0ab2357dd9b24da46461bfc6311d3a32f1bbae3b.nq.gz
    ├── 0b2786071c55dddebc8d2ebd54debd7102017f2f.nq.gz
    ├── 0c53d7aea21a0ccdc6af2f5d0464a5154c1bca51.nq.gz
    ├── 0ca7a8b5f2c2082056d8c648a9fe45068e6737df.nq.gz
    ├── 0df756cb8c29ce8bc1a1ee4230c1ae4d72fafed6.nq.gz
    ├── 0e0e2d979a28ca313718b6e0a64af6697d387490.nq.gz
    ├── 0e56b4573e1c0e452c24419c8db2af7b0b320602.nq.gz
    ├── 0e75d395bd4e7e155e11dd87ee9137297aaf1282.nq.gz
    ├── 0ea6126c7dff9565c105cb3eb36408b8f9de38e1.nq.gz
    ├── 0fe0796c927c377f382e4c67116738315e459a91.nq.gz
    ├── 106bc39aa6598a7990ad1285d14e6ccba38be9dd.nq.gz
    ├── 10af8a189ad40a75f0cb17fa6de82a813a6584d9.nq.gz
    ├── 10e1962a5bda6efdb9e5d9cba380aecb8f439710.nq.gz
    ├── 11bb8140594261069f318623950704d8a075f9be.nq.gz
    ├── 12bca25e9c5fca90f9c57b2bfced616312be3c06.nq.gz
    ├── 12bddf3969b8de2848355c7a4e4b52d691e0f689.nq.gz
    ├── 13c8e7421d0898c0da6029dc1e31c2362176eb4c.nq.gz
    ├── 13f01e9c222bce4980db3739d60c6b3086ba32e9.nq.gz
    ├── 15a64db2819387474cda53e0f2489e0cf5041d2a.nq.gz
    ├── 16bff6be404dfcabbb8bb3fbdfb3d5e8495efab6.nq.gz
    ├── 17af64ebaac3055b76500930e913c4464a236595.nq.gz
    ├── 19365d56aa64a410e662d868a9e0b9d409a6ae81.nq.gz
    ├── 19c16b7c62aafac3f0cd0fa78eb4743e030759e0.nq.gz
    ├── 19c40a4e3f522ef239a9b23cbd06631d408659e6.nq.gz
    ├── 19d44484ecc2f74d6ee5fad42aa615ce927c7319.nq.gz
    ├── 1b8c187cb5d6ac8b08dfe163dcf19f785366aeb2.nq.gz
    ├── 1bb7a577732c91ee6aa31de8f81045b5622126b2.nq.gz
    ├── 1c3b7b607dd2fbb7de49d60c60bb5cffb05389e5.nq.gz
    ├── 1c4b6e33cffa8945aefff542b31b5f70196d2269.nq.gz
    ├── 1cded6a4f11c3affa9696fc9c0c560d2a47c4562.nq.gz
    ├── 1dae6fe4359631c0014f0c33581556b10a6d4edc.nq.gz
    ├── 1ddb849c5a5a63fd6c40211a4f98dd11aa4a4bbd.nq.gz
    ├── 1e21f93b14c62d16411786bf95af569ffae38ffc.nq.gz
    ├── 1f989a74ca6d85d35c554512f11807d81ae9369d.nq.gz
    ├── 20067eecff821f7d70fef2f5ffb2b9c306aeacbf.nq.gz
    ├── 20f4dcfffd4ae0e2d00146c283b7dabbf635bcff.nq.gz
    ├── 20ff86542a9948d2c4e6b9d47007af2ef96de3c6.nq.gz
    ├── 21efac8b868adca059131d74c5619569aa1339dc.nq.gz
    ├── 22401032f57529a2c86e2438ac181cb597e34187.nq.gz
    ├── 23046105029b96ee8b418b9cc83815761ada31ce.nq.gz
    ├── 2378cdb14decb6b98ccd725da7a4a8edd5120077.nq.gz
    ├── 23ef2b095fe681f567ccbdc6337571720c8357a5.nq.gz
    ├── 268639c33cd931f5724fff021ac772fb3ed6f227.nq.gz
    ├── 268cb719f58b9c60381e6b13013d8ce7cae92dc8.nq.gz
    ├── 26edbe29ea2bc82c4a6ec4b355df065e508d42d5.nq.gz
    ├── 2770a71e68b4871d656dd3f861ae623658693830.nq.gz
    ├── 2777d8f618ffbd6bb478157bd61f4a7d655db251.nq.gz
    ├── 27828b843e465c49ed9793154f461f5d25a8e197.nq.gz
    ├── 27a3fb0b8c4f70d382b603882762f1261d5fd67c.nq.gz
    ├── 27eba35b68d010acef5631cf74714a521db45afc.nq.gz
    ├── 27f72205c298760d973867e7f386749ecf851efa.nq.gz
    ├── 29076a0bca4d4f9368da6dad10cdc67cbc77cb0b.nq.gz
    ├── 2933c48462db42b4eaa34a3832337fac75c9321c.nq.gz
    ├── 2a45e1e8a9df61df6a5d366605f813346815504c.nq.gz
    ├── 2c8780c64f11fdff73d0aa8ac2e96ecaafedcd66.nq.gz
    ├── 2d13b028214aec23acf6bf746ff890f9a77329c4.nq.gz
    ├── 2d26b6f89f8e0339843ec6f1b8c9f4396ddfd4f9.nq.gz
    ├── 2d946a571fd33c343950ba7e7aa1e740accf0384.nq.gz
    ├── 2d96064221d6dbe1a87c16c477c42ea1257caf07.nq.gz
    ├── 2da4cfdb06964e09ef9688afbb2e711ce8cbf969.nq.gz
    ├── 2e0a6d6d392f281c06e4b9dec419909077292628.nq.gz
    ├── 2eb4120986d7085308b685168381d8fefab2ed78.nq.gz
    ├── 2efbe8985974baca5353871934de3829fb636aea.nq.gz
    ├── 2f168b8f3737613c0948e2955aac0c9222905c54.nq.gz
    ├── 3019b2ea1637a7c0af2fca63fd6877350a883cbb.nq.gz
    ├── 305bbf7cc35c78fb3e806351e716fa3cfa859f84.nq.gz
    ├── 30cd06b5d9306fb122e18ed809a2660ff9cbe8f4.nq.gz
    ├── 31071a0cca418afed6ad725bdd0bcc11e3df9c8d.nq.gz
    ├── 31bf61ecbf293a282acf73720086513535c0b100.nq.gz
    ├── 3363caf1712f0049c15449a10a7a8708b13b8ced.nq.gz
    ├── 34402aa5796ea89bb99a35c726d92a1be87a1fa5.nq.gz
    ├── 34f819ecf803743d2288f161fce0cf54bb655a65.nq.gz
    ├── 3597d8778be5be0dd7924c243839789b26907a05.nq.gz
    ├── 366cc49df8cd56ee2a1b8040d676cd02a890d480.nq.gz
    ├── 3715b353477035e0c9dbc85ca2c6c7e9d066fb6f.nq.gz
    ├── 372ae218af8e229889e5ce1080bd7b2952d63894.nq.gz
    ├── 37572559ffc8b89e3ce19f5691e09a552f3d8a81.nq.gz
    ├── 3762c04b82cfda479e605ef2f0a5798730dfbcd5.nq.gz
    ├── 37869d245d3958a0d800db66d40791ba47ecbbf0.nq.gz
    ├── 37c63ff457254ad00fc3eb164d2c911f42f5cc34.nq.gz
    ├── 3839b233d1cc4673fb0d09d099489ef8bc3617ab.nq.gz
    ├── 3944a54ac2682222f1fa27268a1049e8d738760b.nq.gz
    ├── 396f64b2870daf97731ca7d2893e0578fb748cd6.nq.gz
    ├── 399036ae296af775c89461588d417ab4ca950129.nq.gz
    ├── 39c00bcdbad825acf082455f356b1579868ce033.nq.gz
    ├── 39cd74749de42c53306a08d800d47ac93d8e1716.nq.gz
    ├── 3c2b0e1f7069920f56cbe68c30eb93adab6517a0.nq.gz
    ├── 3c8978cbe8f1001226c7db2b377da48dcc43be9f.nq.gz
    ├── 3cbb1be407192bea7a92d42521aee93a84dbdfef.nq.gz
    ├── 3ce39e8f00ae9b380858dc9d87bc2ac73718807c.nq.gz
    ├── 3d0ad5b8d741a2c99816822511f7e5924b36e093.nq.gz
    ├── 3d7cf00148b6d7ec92bbc226134f4d110f993ea9.nq.gz
    ├── 3ecddc81be0cfe5d9a28b58f1d85477217e8c242.nq.gz
    ├── 3f86389cee3c1f3091ffb1a96c65446847941458.nq.gz
    ├── 40bcca5bcfb735ef09f90021ac5c73d0fe9136a4.nq.gz
    ├── 41ab7b58ce91e33d88a494021ad2ce1e4a7ef521.nq.gz
    ├── 41c72e6410f92b5e31a78cd98957cf4f53091952.nq.gz
    ├── 42e5a8dd1c2acff065c15b138253df4b1a94e3b6.nq.gz
    ├── 433d80824a4382f3ffd484c2f7fa19ca15583ce2.nq.gz
    ├── 435b0c140574ceca3e5a03b56c75427ef692134b.nq.gz
    ├── 43806db59a3b7f933b264f35f73b204bdea495e9.nq.gz
    ├── 452ad177929b54d0f4c48e8ad791edd9d81d4c89.nq.gz
    ├── 4599899f7adfa5869b666508a8d48e923425e890.nq.gz
    ├── 45baa6adbb9740d39a9bcb23c0adf254fb9035ed.nq.gz
    ├── 45d6ef21e0a88162e58b739a84cb8f6cef2e951a.nq.gz
    ├── 45e2baf9dd368ad7406665e25c008698a8822e52.nq.gz
    ├── 46e17c7620ca9e7a1a1342da7de667eca2c9060f.nq.gz
    ├── 47aaf1fc5e695728215e5151893c718d0f0471d1.nq.gz
    ├── 488b4ddcfda964be8d13734a7c6c5586b35c25d4.nq.gz
    ├── 4912fb3efaafdabd4cb878e09ac4e2b3dd7d6a63.nq.gz
    ├── 492839713f2084c6bc38bab9b09343f417c5b5ce.nq.gz
    ├── 496071a26815e9318e862d2308b747e7b8d34e1d.nq.gz
    ├── 49a585cc8c2902dc830ca52e15d8312fa8d182ae.nq.gz
    ├── 4a6d848c460bd99c8ed2c03395e0ab2f7f77ffb5.nq.gz
    ├── 4a928f82c267c5deaf7097f0606c56dd4bd4786f.nq.gz
    ├── 4aaba8ebe4a1861e2f92e2da58bda394d54423e7.nq.gz
    ├── 4ac9c0ae704ae50a63e8d508ca2e0664cdfd154e.nq.gz
    ├── 4b9badc3a7558b29a604af9b59818f194102306d.nq.gz
    ├── 4bbeed6ad875156251347cf81091aa4621a2ec82.nq.gz
    ├── 4be2510a295aa3f1147d7f822725c8327c9fb6e0.nq.gz
    ├── 4c1fdef233602db3178135a99884c9315d8e1d08.nq.gz
    ├── 4cb6f1a146eec4604381d9f78b29e42ff389cb19.nq.gz
    ├── 4cda645414a4777cba0bc158beddd6162952d757.nq.gz
    ├── 4d2630330093b8d6531adcf7ff7fb6cd19fa3362.nq.gz
    ├── 4d51c390280c8a2b1b05b769160334ec713d0e55.nq.gz
    ├── 4dd8d7ebb1a338cfe72f41af953c74e4e9ac1879.nq.gz
    ├── 4ded8f5b80d931ade1742ced7d1bf4912dbf8f0d.nq.gz
    ├── 4e141e47d270a297f49026d83356426d2b3a7ff7.nq.gz
    ├── 4e2fe03372a868e8eedffd4a89b1f1d2129d7f5e.nq.gz
    ├── 4e8159ed923f08b39e3efbe342fb916ea888be20.nq.gz
    ├── 4f3ca50df9fb34fc0faccba1b169181fab6c3dbd.nq.gz
    ├── 4f5878af4812cc5f65564820549c05024416f160.nq.gz
    ├── 4f6ff130f033e23cbe1fffe96e45ca0dafcfb0f0.nq.gz
    ├── 4fcef6d0dd1faa3578a529e072869dbf02431e6d.nq.gz
    ├── 4fd986d850e98864bc5ba1a3ae62803549d47296.nq.gz
    ├── 50740f0b91c959dfe928a91e232f4956fa517bbc.nq.gz
    ├── 50c1b81aea1d565d78741387b5279bbed0ba4ce8.nq.gz
    ├── 51071fda603608a852f24838db165a390a0c808e.nq.gz
    ├── 519a4c1ccb685519dc174dcf909d73f4b56afeb9.nq.gz
    ├── 522bbad19a7c02aed8ebd27f13a7642ca772a61b.nq.gz
    ├── 53726294acb2501148e83601b6b2ac7e0a6cbdb8.nq.gz
    ├── 53839175afeb6688a2b0d94897a374aebbbadaac.nq.gz
    ├── 542bd67e319850d75221929abc905d6da3934baf.nq.gz
    ├── 54b54e7218aff7692732b4b8c5494c5d62c82224.nq.gz
    ├── 54d1d1b424b969bdd0f28aa806e2ff45ce9b4b1f.nq.gz
    ├── 551ad023176328ba5faf710769c036be64bf3cfa.nq.gz
    ├── 5582d999e90ecd56805004550b19f0de04a33012.nq.gz
    ├── 5584a1f6215fcbe6528d2a900eaaa4ca202f403e.nq.gz
    ├── 55c14eebc8b74633242a5769a61e075bb5e0fd22.nq.gz
    ├── 55ce72bfa72aa9c2c98043df45bed0da47c6f763.nq.gz
    ├── 566bc1105ba4f214ccec74a210bb9880a1115202.nq.gz
    ├── 575828638cbfcfe6c218fc19642b0dd684238b0f.nq.gz
    ├── 577683d9b73e72ebc2926ccb61ded58760833c3f.nq.gz
    ├── 5869c6e0fc470fd4a29d50fe5c914b84f40ec282.nq.gz
    ├── 591d64e1cc9e695218e9451f7fb9d92ab6cf3530.nq.gz
    ├── 59b37d41e90c94a609bb931bc834c6d02ac1615a.nq.gz
    ├── 59c388d8f2b46b3be14d1fa8aebc1549f037034f.nq.gz
    ├── 59c8701659c760d182dc65fd68cb25244675e9e0.nq.gz
    ├── 5a0edba5ceed6a954f97a6e7c5c10f18198f3083.nq.gz
    ├── 5a2e6a903a83c771b3ec624748ed6796a3a1dadd.nq.gz
    ├── 5a9e3091bb1ae3b27b5a1906d2d466c5ff6a2458.nq.gz
    ├── 5ad626dc3c82fab9357e015c4eedc32b29b62310.nq.gz
    ├── 5b4e18f93916ff9c3ba7a6ce115ed83adfbd5165.nq.gz
    ├── 5b5013bcf298777529c789418bb6ab3ee85325ad.nq.gz
    ├── 5b794a3d3b0f2a34fd7f7292729c81091b8b8db8.nq.gz
    ├── 5b89192a0f9836ffd1dde34f176a88cd9cc65ab0.nq.gz
    ├── 5c39465fa80f70b0c76a935cfd03678c9beeb64d.nq.gz
    ├── 5c591c7e4e7e070efbc54119dc72b0e07285e5b2.nq.gz
    ├── 5c86bdcded85f6e717bf96d632d42867aacf10ec.nq.gz
    ├── 5d3acedb6cbce1243990f589d660dc7d1b4561fe.nq.gz
    ├── 5da6496363e1e9c42dc0f3719a8d10a47f55e0d1.nq.gz
    ├── 5e325fa9c811f8b5fe464f2de21ab5f5f8d383b9.nq.gz
    ├── 5e6e9db1808d7021073c0cba9f6adbc81ab3ad98.nq.gz
    ├── 5ea8f5bad8689f83230e00b93f52f1a9ce0282a4.nq.gz
    ├── 5fe0a4cb754e525a5b7a79fa0845edec436541d7.nq.gz
    └── 60bef2a15662680b8b71728fad5198cd7e1abed9.nq.gz

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

[scikit-image/scikit-image](https://github.com/scikit-image/scikit-image)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
