# Repolex Knowledge Graph of allenai/omnigent

RDF knowledge graph data for [allenai/omnigent](https://github.com/allenai/omnigent), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/omnigent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7dd85cfdd7ef9407b85127279b6540bef0423202
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   └── repolex
│       └── 7dd85cfdd7ef9407b85127279b6540bef0423202
│           └── chunk-001.nq.gz
└── blob
    ├── 00a20b1291e3c9d262cab6b2139cfc0f2cd166c4.nq.gz
    ├── 00c6bbb0e78d10ed6b16a7e3fbf15e417ca6e1bb.nq.gz
    ├── 029aa254977d34ac4a927fdef27afb6bec86de26.nq.gz
    ├── 06a2331fbd4c271ab6522dd209c4c854664f477c.nq.gz
    ├── 073ab64232c3111135c96d1d4e238175ae07606f.nq.gz
    ├── 075ee6a0bd8ee5518205de331fb2dbc215ed3397.nq.gz
    ├── 080b3555ade01d0f5e6d844b56269b1829b08e8e.nq.gz
    ├── 086c6ec028e297c20a70fffce2be88661d53ff6b.nq.gz
    ├── 08f62f0404e6bc31f09960c0a255146a02a0bf5a.nq.gz
    ├── 090af2172afd625ab6045191053d7e9bf6e320d5.nq.gz
    ├── 09676c2af6f98e736dc5358ec742b475002a58ea.nq.gz
    ├── 0a287355ac55281173a5d3dc9030bd8390741554.nq.gz
    ├── 0a8362da853ed3c3e0c58ee6b49e57e94d73a937.nq.gz
    ├── 0a9631a037afc264a3466baaab1333920753e170.nq.gz
    ├── 0ad0647cc05f79b2eb084fb1f6b31a8afa7c8d64.nq.gz
    ├── 0b7d3ca23e7aead05ae680962813ab1e8ef21864.nq.gz
    ├── 0c20e4b03ebc9cad9296262ac5a80d44baea4aa3.nq.gz
    ├── 0e03002a5e437c8d7d9eaf0ebf1fc1085b2577d7.nq.gz
    ├── 0f664b2cea4efc64f2e72677c5263b489375a0d7.nq.gz
    ├── 11a687bef875cea7314adc90fbb98656f83434b8.nq.gz
    ├── 11cc176baca3499ee3154db5d090acec42db7cc1.nq.gz
    ├── 1219080913a62cc5dda2942ebedb6028b029378c.nq.gz
    ├── 128c30c4333996494a1c1360664213145d016926.nq.gz
    ├── 134178231f17002cf349184d1516655566aff58c.nq.gz
    ├── 13e07650e21773150e363fe962ecc51da1c6ef3e.nq.gz
    ├── 14d1b63f537e04cc44894a39bef092c1cfa22ba5.nq.gz
    ├── 15730f32c17ea313f886414993e76d8846e31521.nq.gz
    ├── 1573e7d26179ef8ccb54cadefd891033aff55bc4.nq.gz
    ├── 165a045bc3e8320bed190cd411f6e494bd7aa58b.nq.gz
    ├── 173eca1234d1bf0d0c85a0d7dbebde84f96adc9d.nq.gz
    ├── 17a7a613a480013051ffb020125f4c13a8adfa1f.nq.gz
    ├── 17ba57f65ae96e8c69110aa90481c19593a47914.nq.gz
    ├── 17c0cbc935a2e2b23afb5de67fa53ee316e8c086.nq.gz
    ├── 18abfd3debe1e3518b9cb38a0402cb00ce17b978.nq.gz
    ├── 18bed75445b22b57b824d3055026e43f6e0c423a.nq.gz
    ├── 18c8d04222c74acd1a003344b626017b2cda8afd.nq.gz
    ├── 1a0d3cb25c85b54c10f7de482e08d727d8e8c246.nq.gz
    ├── 1a30b3c845e4fd2d9550589a4e140a4103192f49.nq.gz
    ├── 1b5f8b98cf6f144b16a486bf142cb7b80f31c963.nq.gz
    ├── 1cefa8e335f3d6d99f3dbab582ca493d2c00dd0b.nq.gz
    ├── 1d3ee72a0e6250748e577caafd75f5bb60546950.nq.gz
    ├── 1d425da413535ddaafbef50f9def6f70d89375a6.nq.gz
    ├── 1db7d1acaf556d51d6a627e7856c0456b00dfd73.nq.gz
    ├── 1ef193f507976d538f997c132214635e4489d49a.nq.gz
    ├── 1f8f4b850ef842f69cb537410702c508f5ad1005.nq.gz
    ├── 207a2044263b264d615c26d7c7a8f5e6106219b2.nq.gz
    ├── 210fd027de9b73da1d07d656cb76174734ec4c9d.nq.gz
    ├── 2128a48f38e7f0b4655fe3b340f53bbf77796d3d.nq.gz
    ├── 21dd5bbb8244f47023d36b5b702c1f2027241a25.nq.gz
    ├── 228e0ba553bbb96b812f6d249596fcd62bf3bfc5.nq.gz
    ├── 22c9bcc13cb2558d0fd6a00b744dd6d2502ac6c3.nq.gz
    ├── 22cf719a4f0173370929ccef2380cec13034055b.nq.gz
    ├── 24b0a4f26d3dac4fb79f4c8ffe02297fdfeb31d5.nq.gz
    ├── 24b1fe416f18e310f98593f43ab8d54f00a49112.nq.gz
    ├── 24f98132b020f43da5bbc5979cdec8c81fb3f063.nq.gz
    ├── 250389c557f2e585c3cfc1c3efc33b7c70517b3f.nq.gz
    ├── 25105a5188d91c24609dca7bd42d5ce90c99bcac.nq.gz
    ├── 251fb92905190fed5a96a6d6ad89c4bcea678f19.nq.gz
    ├── 25b47ec71cb4d699990035e8b264af6b5b6f3ed0.nq.gz
    ├── 25b4e961eddd2026ad5293fe6d14874852004fe7.nq.gz
    ├── 26b60b5c872e6296683ae30437647be809f16091.nq.gz
    ├── 26c81c7d1330f557c3a4c8ca5a661e18bbfb91e4.nq.gz
    ├── 2721500ff6774d7fcf46f591129d0db013bcc480.nq.gz
    ├── 27cc6df109236b56877e91bddfe4c81810696fab.nq.gz
    ├── 287fdcc68e18bccc44a490e2cd3f952c5fff6143.nq.gz
    ├── 2a4892009773c57e61cab0876a429ef83f7d4e0a.nq.gz
    ├── 2a985075677df7234316ad89677ae9a79904e565.nq.gz
    ├── 2abfcad76145b0edfa15f7cf895658c80b738974.nq.gz
    ├── 2afa55e4bb4dbd90b315ce11877a5e7230f5fbb9.nq.gz
    ├── 2b53d04797ce44bc34c085900cfdfecf4ef972d6.nq.gz
    ├── 2bb2d2ff2cb669f7b56a251592a3391cad0fe064.nq.gz
    ├── 2bf1fa5aa4519abe76b2e26595c330cd7032ebca.nq.gz
    ├── 2c8e9976dd7c4d498c9976c2728e43a2e9d55197.nq.gz
    ├── 2d2fe3ca00ed6f21544472d976e224515f4c58c2.nq.gz
    ├── 2dcd688ea4dba12133f0e2fa73dca01771a1a5a3.nq.gz
    ├── 2e7958211c36ac6883f79e5bf8351fcf670a2c8f.nq.gz
    ├── 2e7a92074e1a4d07c0ecb0e4f67adee2505fbac8.nq.gz
    ├── 2ee995e939e7efe9cf6ad8cde264a447e725776c.nq.gz
    ├── 2f48553f6fd9f6c7355a658bcba64cc4a4702b55.nq.gz
    ├── 2f50d32344d8999a36a3b13a96839eb2584ceab6.nq.gz
    ├── 2f78516a06067a781323ee727c75839a1766938b.nq.gz
    ├── 30685f4194038772966ef38d7819e1f099cb7dd4.nq.gz
    ├── 30d8a355a7268bd28516e07d0d39b5e986df6634.nq.gz
    ├── 3125a0c5a5ae09f818b7e8d00d07757e130177bc.nq.gz
    ├── 31401d2e6dfab7de20b82fea5ba87674bcf8c8fd.nq.gz
    ├── 31698131089f53929e8f0ce649c1409dda2f35bd.nq.gz
    ├── 316b98d163cd8e32d6c5545a69015488c4de190b.nq.gz
    ├── 31aeff7b019a610d33a49af66eda6267985bda5a.nq.gz
    ├── 32a29755994de74212044a217e2c3bc3207f44df.nq.gz
    ├── 32f740f0bf05f20d712e60482deb6c97f8d23a97.nq.gz
    ├── 3353c2e62b7ae3c944f07ea780c11fb0cb9ddf56.nq.gz
    ├── 34e8a2288361d15b9399cd6ea7ca3afee9e92d54.nq.gz
    ├── 355c310269694791a177784946e76c1d06557649.nq.gz
    ├── 35b4bc3fe81a03584ccbc49ac5f6526bdfe78781.nq.gz
    ├── 35b69b5302ddc6b822b52bfce627e15f9fe9f95b.nq.gz
    ├── 35de3f6b0b671fdfb8f216cc9e0129d37266c18c.nq.gz
    ├── 360e2177a58feda7a4d5fd0f0407ff42134dd282.nq.gz
    ├── 364d5cfcf6f693d324aac07b1052309ae2686bc2.nq.gz
    ├── 36acc08fad658d2a935df96b43881d3c48962f28.nq.gz
    ├── 378a45e93e6f40e78f0dfd257fac3c4f2366d1eb.nq.gz
    ├── 37f3a39012784ca1dc2c3c69adfb34279c7d044a.nq.gz
    ├── 381c1a6b0e23e33aeef063a3f9d0330479cea74c.nq.gz
    ├── 39ac6b3a94a5a2242b54df271549ae9b18cf63be.nq.gz
    ├── 3a8c165b5983d0cf6dbfb3f20c2a61b77b5a8ab1.nq.gz
    ├── 3ab0d0be11439dc9bccfd543f6cff51419c19431.nq.gz
    ├── 3b3b665629dcbb4a99a4b561c0cc1eb1ef6de195.nq.gz
    ├── 3b3fcd8e21b8a1350d03f08008b5588aee865592.nq.gz
    ├── 3d5f862546708647f884aeaef6f610801da1e0f3.nq.gz
    ├── 3e37742ebd7c9f536c66a7cbc45aa4eda33937db.nq.gz
    ├── 3f51c5b973b66c8d361e8812892ced34f9b0a213.nq.gz
    ├── 3f7be0b2acccdf3cc6af3b9d29895a438dff9e73.nq.gz
    ├── 3f7dc9f05ad96aaff706b249d5ee2b91840e7df1.nq.gz
    ├── 4090cea58b55e1545ed49332bce3935959da455c.nq.gz
    ├── 41e178349c0aa9c62a39d683792d07fdc9cc5483.nq.gz
    ├── 41e28716b24e48b092b9d197012c1bfd2cdc0607.nq.gz
    ├── 423e25c8e0cce4808c5f9292d88d0e9482297b0e.nq.gz
    ├── 444d633746ccfd92f4ab702f79e50c3d9828c19d.nq.gz
    ├── 447aae450e09d92e808510565b0b34b91a54d9bd.nq.gz
    ├── 44d43057bbe5e4c8395829e9496cc415e8d260f9.nq.gz
    ├── 4554f2dc94b2350a120f3db2e290f86d121d52de.nq.gz
    ├── 47845d82356cb606837c502ee5cef2ca0902af87.nq.gz
    ├── 47923997863e21375d7be9c219823a428493d70b.nq.gz
    ├── 47a03d3bef845d0299999b545c17addec9f7c002.nq.gz
    ├── 488572cccd040d7cfacc238303ad44c5996311b2.nq.gz
    ├── 48879dbe606fa89ea367e4fff925c9972a9e7001.nq.gz
    ├── 48925336260199594a8ca59dcf6e4dfad5d53b7b.nq.gz
    ├── 4a00c49890b88fc517e83e4d39d87e941d4d9f4c.nq.gz
    ├── 4a2f1d245917abb0bae95f6cf6a4d4d654a79862.nq.gz
    ├── 4a5560903c8729efac3eeab420f2a2255e393456.nq.gz
    ├── 4ab89d599be8bdbf8291238269c8079aab172cd2.nq.gz
    ├── 4b30f8305c880706270cdd1e77265b0e5e94f25f.nq.gz
    ├── 4d309dccfea1e5cbfbb334bf48b877d79ee150b6.nq.gz
    ├── 4d417b73f652985567c662206eef425602fef13e.nq.gz
    ├── 4d51a620e87834f37fd40d99be9472ea18eba785.nq.gz
    ├── 4dbe529f8a08ddba55eb8914b8ea70571a598451.nq.gz
    ├── 4dcde50c4e660b4038289116ddcd336e5d4646bd.nq.gz
    ├── 4deec12028a075aa4ebb080691d25851cbb64fff.nq.gz
    ├── 4e45822959d6454859f767aa6eb25a4fa5ff8d53.nq.gz
    ├── 4fded2aed6f43624b9f56a6b335fbd446e78af15.nq.gz
    ├── 50d18d3ab1a88c42b30d0809a727af913ff0da55.nq.gz
    ├── 51685b164f010c8019bbfe1f3336f82f0a9d5db8.nq.gz
    ├── 520f050c57b3e53ffe957c8579e7fadf01c30fc1.nq.gz
    ├── 52f8bf854b85e92dffc49261397dcca2f5cdbcde.nq.gz
    ├── 549f0571e0b1878d03dec4acb45176c3d066ff3e.nq.gz
    ├── 54cd2ba081782bbc49fc493c6bdef2e230d9f5cf.nq.gz
    ├── 5554d71d7a4a0ede54abd30035218089955a0fac.nq.gz
    ├── 55bebcca02a016424981b181682f4020cc96fdf9.nq.gz
    ├── 55e50d57e2341561b592f5a83cf146e44c31c53b.nq.gz
    ├── 5656af789b2b18acfece342457baa86011b5862a.nq.gz
    ├── 56968a017e55bf830cf5997f0490e03c66cdd789.nq.gz
    ├── 56c0d5735f8d7f9007e5313f63a18bee3144d90c.nq.gz
    ├── 57009059e3642badc26bfa9502d4026206e62211.nq.gz
    ├── 5736f0d3b9e58fae922ee593c8570d2895f61717.nq.gz
    ├── 57ab21ac9962a84506e7547cdac106d3c1c91c2b.nq.gz
    ├── 5854b308e0f08b967abf82ab231bb2192151a725.nq.gz
    ├── 5876ce8245f0910bdf7ad25502008e070c30a895.nq.gz
    ├── 59747377a75dd6bbf032123147cf23a99e405be8.nq.gz
    ├── 5987829dc27e1c4b6bd29bf2e88be2eca0295ba9.nq.gz
    ├── 59ed41cc372746f9fce39a0777a8190f7a5d1649.nq.gz
    ├── 5a7d014c0b913ad3fba9d79f67a164f4ed6ba027.nq.gz
    ├── 5aedf7fc3481c97f71d35c61bda3ca0b4d7ed606.nq.gz
    ├── 5b1655e44faa76b546fa21c6ce77a1f5c6d07ec6.nq.gz
    ├── 5b8ed041ac0071240dc8b48b655ec589957edf83.nq.gz
    ├── 5cf1492742f5ca86dcffe218e2a720b8f7d8192a.nq.gz
    ├── 5d030bdeb4e445a4978bdd98c0e2e302c7c05ca1.nq.gz
    ├── 5db0fd8f03559583bea5e46d88a34330bdcb6e0a.nq.gz
    ├── 5e3387e1c8a53c89950da80a87f575c0f0123e59.nq.gz
    ├── 603c0dabdd6f7bdecae6e3d810949b46786ff402.nq.gz
    ├── 604dc55f6ab5ce5c2aa856cd83539b68d884fbd1.nq.gz
    ├── 60ce739e5c4d3b1758b34f79669eb6670288dc6f.nq.gz
    ├── 61334fc2408f1dd549ece9b3adf9a7959d0c4ae8.nq.gz
    ├── 61d08e0d69b0a6b20f51475bd4451265a51ba70c.nq.gz
    ├── 628f51fabc2aba99a6bd08911bad1a9709cc2704.nq.gz
    ├── 6396b3c80d9f1ac95d09b867dce3eab09c7b63a3.nq.gz
    ├── 63f0ff11ad2088e174cc8deca6cdf3a008e4bea9.nq.gz
    ├── 6435e30c5c860f6d1adce5c821a7f440ba3668b5.nq.gz
    ├── 64574c7d608448798115e5c6af479ee67311ecde.nq.gz
    ├── 6549a5e1a8e0a84a5fbbb36be9030003dd25f18d.nq.gz
    ├── 65c37f55cebf8c359d12cd1902943c71ddad08ab.nq.gz
    ├── 65cd77207473de4adc6334eeafcbef9534cdf84e.nq.gz
    ├── 6630ef0a040b0cb6addcb947237489c37cab2207.nq.gz
    ├── 6755327de5b4a924fb0950233cedfd008cbbffce.nq.gz
    ├── 67aad4f315d5cf747027bc9385941533503a3f39.nq.gz
    ├── 67d30cb6c55ef7f88035cf265648c7b15f104cb9.nq.gz
    ├── 682d70d187db7f912b43ca75e15765025d19206e.nq.gz
    ├── 6843f6277cdb140e3e6a55d9a268ede38a52849e.nq.gz
    ├── 685db71b7d2eb504e884ebfbc64ccf18b348c6ad.nq.gz
    ├── 69a868b55ea79945eadc4f809164e7a63006ade2.nq.gz
    ├── 6b2663a3f5558646159468e832441cda6a9d4696.nq.gz
    ├── 6b653fd8a12bb7b0a0b1eb99f3134acafd15cadb.nq.gz
    ├── 6c1b6d664907c1139eed098d5769a174344be700.nq.gz
    ├── 6c4cdf9aebfd9a98acdd5d8cd9aedb93ed1eb713.nq.gz
    ├── 6d508cbe8d08be4932eac472c56bf03a77eb4991.nq.gz
    ├── 6dcfb057434448548cae819288732ff8ba810b7a.nq.gz
    ├── 6e570729fe8b00fafcb957e42e91102364c51cce.nq.gz
    ├── 6e76fc932af8eb4b9b1f191fd5179c78cb979357.nq.gz
    └── 6f9dd7bd1728c828ca305404435a3b27b65cb55a.nq.gz

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

[allenai/omnigent](https://github.com/allenai/omnigent)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
