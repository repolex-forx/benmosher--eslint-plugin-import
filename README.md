# Repolex Knowledge Graph of benmosher/eslint-plugin-import

RDF knowledge graph data for [benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download benmosher/eslint-plugin-import
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 01c9eb04331d2efa8d63f2d7f4bfec3bc44c94f3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 01c9eb04331d2efa8d63f2d7f4bfec3bc44c94f3.nq.gz
│   └── repolex
│       └── 01c9eb04331d2efa8d63f2d7f4bfec3bc44c94f3
│           └── chunk-001.nq.gz
└── blob
    ├── 002bd8cb66b2ce137aabb30854b9126c30fc4f2a.nq.gz
    ├── 00c93fcba1b105b7cd19fb6f797ae6ff0f5c8066.nq.gz
    ├── 01ff4f36f2c503f473b44b2f5074f0d1583a2218.nq.gz
    ├── 043b375628fff40390d733e44889be15d33f0717.nq.gz
    ├── 043d6994241b31fda7e37731703675b56c2ec1e6.nq.gz
    ├── 04ac20265bad32a321ad974a9cfb691e6f6d816a.nq.gz
    ├── 04d6de0577a07f8bf981cdf7ef2fd0e26aee1ed8.nq.gz
    ├── 057711e9bf3244bfae861c7d0a0828b9cd0be341.nq.gz
    ├── 05860cde1e0fde2f3bfefcab8ea42261e4518820.nq.gz
    ├── 05ed0a52109e589641b0e452308a884b9435421d.nq.gz
    ├── 066e52a6f7622988da1791d66f293e505e75989d.nq.gz
    ├── 06cd8afce7d0a3418b39287bb75d5208ab37e0a8.nq.gz
    ├── 06d938e40b08605a2a0673318cb6792316f1527c.nq.gz
    ├── 06dc48a9dcc2dda715a7bbc52c5b3cbfce6058a4.nq.gz
    ├── 076e59fd761ed81ac35c236e48924ef80659a91b.nq.gz
    ├── 08371931f2a6c76fa9b0996db4af8e0aa22c305b.nq.gz
    ├── 08674714227bfbf5e954aa79d6d966b5dbe517c4.nq.gz
    ├── 0894d29f28bb8284af8ce872473c31d6d22fdc97.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 096df7728190cdc897252697733d5f304cde7647.nq.gz
    ├── 09a6328118945eb95e2700b04d7dde9fed99557c.nq.gz
    ├── 0a0e128dc0591ac2d489924c82eb08f74f542136.nq.gz
    ├── 0a5fb6e237f9ea78fd70534639a30cf2f68be705.nq.gz
    ├── 0be6eb2fd6625c11013ef58aabbc6af40dbed065.nq.gz
    ├── 0c632c24767df8e45ba548eaf703a8243d571bbd.nq.gz
    ├── 0cffc87d1994b9fe3ae13679fc897c970b944e22.nq.gz
    ├── 0dad14e067c986f58bb6117947af4af927c5a6d0.nq.gz
    ├── 0db9b05f499d84d09750017647aeed996d788cc6.nq.gz
    ├── 0dbd8cb86c179834548c440d079abc222e09a470.nq.gz
    ├── 0dc5fc09546b48bf944d041ce56af981643e746f.nq.gz
    ├── 0de787c33cb52be21451ccc8f67b513aa3d12a95.nq.gz
    ├── 0e4a12c68ab0a0c09cd108afa0da207ef63862d8.nq.gz
    ├── 0ef28872fdbd01b312a6a30968bff5f62c934627.nq.gz
    ├── 0f0af7d06b02090a8d31d090c9a76b500f8109b8.nq.gz
    ├── 0fe78c5218340589bc34a89122f1914d720e7ccc.nq.gz
    ├── 103f2fd6fe6427b92f4c2cc67e5fc965e6f88560.nq.gz
    ├── 1084360870c9774162f15a30bc8f6c9a9407d4fc.nq.gz
    ├── 1091770f7f0d086cac1684da379b866766534f1d.nq.gz
    ├── 10a17c3b1952e8c368af9a8d52f9383008aa0205.nq.gz
    ├── 10eab3796ccec7f6458671d1ef8c333b72bf4c87.nq.gz
    ├── 11bc1f52a4b06733a958c13162fac6421d9da99a.nq.gz
    ├── 124b1745d205e79175ca89ed44b82f0c0b188064.nq.gz
    ├── 127c29a0cca94138b39843b8c34e688a1053f232.nq.gz
    ├── 12a7650082ec97200ad448c70e40a5f9d56afa9c.nq.gz
    ├── 12f790ecb5e805d79d3457efe4b854f475fb2457.nq.gz
    ├── 13135e3925bee5691bf968948c9101d1d41ffa16.nq.gz
    ├── 134f23bbce3626733029216288d1debc0e473da7.nq.gz
    ├── 139457ff606b2dcb46424d6d9af3ca88adb35fbd.nq.gz
    ├── 13ea63ad739de4b68dc574e8c46934b6b69d67bc.nq.gz
    ├── 14006c5dc62b61909d1a3c57ba662a154c6694fc.nq.gz
    ├── 1432652658de1a825a512864ed555eeaba222b76.nq.gz
    ├── 15c67470ef12f88907e464e7e7bea31cb58a8772.nq.gz
    ├── 1605a22035ca3f1f5d19cb18e4050b62582cb8be.nq.gz
    ├── 1679224189c017f8c84cec0f2815f8877aff8d66.nq.gz
    ├── 170b10e1a13f42af1218e4c880ae4bd2be8d7207.nq.gz
    ├── 17406f1bbdbcace05eba46c1aa5d7e203086a920.nq.gz
    ├── 18a1e415e56220fa5122428a4ef8eb8874756576.nq.gz
    ├── 19082862fc93def5ae7b665826026cdbfe85198e.nq.gz
    ├── 194bb8fc882c4c4b43a87a25ced40481f82edefb.nq.gz
    ├── 1a177f58199cfac30f4338b2ae938ed523efd10a.nq.gz
    ├── 1a3a112f58374ac1643793b6b2b440cfeb8584a7.nq.gz
    ├── 1a5baff5a9a760e4a9b0c129429fbe80462836a5.nq.gz
    ├── 1ae8e1a51a44c240445c6af77330c72b5fdf2c87.nq.gz
    ├── 1ba6fba79b2a2a654278475d1f9d4c65a2656eb2.nq.gz
    ├── 1bb4b63fafeb72ce462fdfa31e7eed734f0bbfc3.nq.gz
    ├── 1c572264959f2a3c87e3ec1c6434ff1b55719669.nq.gz
    ├── 1d0fe1bd5e3443982f55926ded20edb443faeb60.nq.gz
    ├── 1da867deffdd82639bc6920a4140cb156c00add9.nq.gz
    ├── 1de6d020c8aa666b9b9d5ea77139e4c3b6908350.nq.gz
    ├── 1df57a23aa8a18b47a2c32083f97bdec69598c1e.nq.gz
    ├── 1e79f8339c2e8385e66676039735c4e70dec2e68.nq.gz
    ├── 1ecbca64d3241bc699c34449c5a52929ab34c973.nq.gz
    ├── 1ed0e31df572fe7c6b5d50f388845b67659b1409.nq.gz
    ├── 202103085ce76c654eae0528cbd05a6c47304560.nq.gz
    ├── 20306c1829324dfa741a8b5fee39052e51759c2a.nq.gz
    ├── 20fe1e5af443d5d13df9d5d451a5854e53e0ea58.nq.gz
    ├── 211fd972f6e40f2227e1abf91a3ac9b9bc114c10.nq.gz
    ├── 218c3cff7c0b4354bbe9e6644e8534bd946dbf76.nq.gz
    ├── 21c1a7c6441a07054f4cc694c6cb9e1b50a7a964.nq.gz
    ├── 21ed524a9f8483170da34fdedde9d484fd4a571e.nq.gz
    ├── 22c4bf965b223215ed029ac64089e3048d56d472.nq.gz
    ├── 2491fad3ebfd1b0b6b067eac6842a669eff62ffb.nq.gz
    ├── 24c76849ddc5c7d9d5edc2b7023c2b8cbe085bfe.nq.gz
    ├── 24d5504a71c269e4181fcee3f67cae62333900a3.nq.gz
    ├── 2528e5207608a90e51c471d82dc7907d22b1d284.nq.gz
    ├── 259feb4cd98e41921a0748135b11d8034e9a0fa1.nq.gz
    ├── 261989a75c0f4934c5f998bd33b42235c389ac01.nq.gz
    ├── 26f3534d7bb9cc0e223b6e8ce37caf650e55d41d.nq.gz
    ├── 278e4c472508174038a32a9dade911fe051a792e.nq.gz
    ├── 27dec2033dbca1581f0d89ca4b09790f414fdac2.nq.gz
    ├── 2917b03f51a7bd240f650bfa1cb75c81a597b514.nq.gz
    ├── 291b1c058a57e282be5cd34c93a2f45888ccf84e.nq.gz
    ├── 292055fcdc20b5f225f42cd883c2dc6ed5e71590.nq.gz
    ├── 293bb8ae60b7150c3f617977b0f07fdbe60a6b07.nq.gz
    ├── 29c16f15d166fae4f52413402c490c19d548d16b.nq.gz
    ├── 2a2d45185001caa863db8d3129a49f5ae7f8ec17.nq.gz
    ├── 2a31d57e1924c26179edc79955043a7ff4fa196b.nq.gz
    ├── 2ad4822f7c4af14414e1195c7a04c3d093efd5dc.nq.gz
    ├── 2aeef64758d20a3d3d3fffd454eba27a36e7b309.nq.gz
    ├── 2bc5e42242f3aa5519d46a714c848018713ead80.nq.gz
    ├── 2bef94ec2b997226fbf4bba0555050ee6cc0329a.nq.gz
    ├── 2c63c0851048d8f7bff41ecf0f8cee05f52fd120.nq.gz
    ├── 2d36b837ed001a39426ac08a73d8ce91208a03d3.nq.gz
    ├── 2d4eab380f442d11921517183dc5e853609d8abf.nq.gz
    ├── 2d7500a680c1f9443467d451f9a5dfce8c229063.nq.gz
    ├── 2d8dd35269e7ac19431a76fe36020f92ffefe237.nq.gz
    ├── 2e1bc608c6bc79b25fb29b30314d83a11ca9cec6.nq.gz
    ├── 2e7984cb95a1989ba9b1516437e46c768e6c355b.nq.gz
    ├── 2e9a7c1c293ee8abc264b364d0ec940f09d7fc87.nq.gz
    ├── 2f98042715ab97ef1c420552b4bc4e228365eb45.nq.gz
    ├── 2fc07cd9a335443969050bfd880b3ae9fa669195.nq.gz
    ├── 2fd502539c3b47fa20933c88737e35b14287432e.nq.gz
    ├── 3113adc1ab250257f3a9187ade76aefe735001cc.nq.gz
    ├── 3163544b95fe3361214e2b9cd5b89200aba55725.nq.gz
    ├── 3211c085a7416bcc9c93f114d16ed5610c881da7.nq.gz
    ├── 3212781363bac9093e9d3d2239e234cd09f178ca.nq.gz
    ├── 32dd3db4eac9458890823a2170432a03c62a5736.nq.gz
    ├── 32e200f1defcbdcc3d2d13f0800fd42ae2e2d058.nq.gz
    ├── 338501511c29199ec114db241459a1fb2cc9384c.nq.gz
    ├── 33b77da597a1d1dfe99f4dc8e2be2bd2cfdae06b.nq.gz
    ├── 33cf714e0dd462fc4ee1f6fa14846fc3539e2c48.nq.gz
    ├── 349372067bd3b3e6b3ac73eb0fa45ca62f553c10.nq.gz
    ├── 34f5a6e8205ca539a87d4a2ee5de6bcbed01500d.nq.gz
    ├── 3516f09b9c797fc9c57a6902cf6f4eadf1e6aedc.nq.gz
    ├── 357d890b9d83c1ee0ec47fa78d40a9b49bc19f12.nq.gz
    ├── 35f46e66c292b4aba911092bf2579c7b6e876f5d.nq.gz
    ├── 365f02b6e0fe01c7f904e4f435ea2a756a262c9b.nq.gz
    ├── 366f3ebb6ecce906d1f31ed55c1b75bc064743d9.nq.gz
    ├── 36a3183866ce2095915189c2b2e1bdf7618a1043.nq.gz
    ├── 36bf5c313c58fb0660ffe9aebbe30e6612af8765.nq.gz
    ├── 370f47579dd256ff1cdfaffd828a109805547b19.nq.gz
    ├── 376b783ce17a14b2e630b58b108b134194b59aa9.nq.gz
    ├── 377a10d20c1d0ca318eead0a293c6b376e771d0d.nq.gz
    ├── 37b3009f0ce7c3b02652535cad9d117be9fe26e2.nq.gz
    ├── 37dd47636111c7b4cdf78a4cbd867068195a1920.nq.gz
    ├── 38a4c888bd425092563740cd7670e18506a0ba62.nq.gz
    ├── 38a9ed7345aa1fe95efec941523170c4cb0bd183.nq.gz
    ├── 3a80819f882edbac0a863bb5614e41a6122a2e9d.nq.gz
    ├── 3b7feb34657fb4014962495cd1e224d5547a3822.nq.gz
    ├── 3c44db68d0f803ca16d331c23ad0c7e035fce503.nq.gz
    ├── 3c47cd8c159a95164252b1c794fed2b559f1d7af.nq.gz
    ├── 3de28a65d59f2fa16f91c7ade18b30ceecc57136.nq.gz
    ├── 3ec93603af1123d6ff1d4d2934673cdd7bc9681f.nq.gz
    ├── 3f38d78a5a999adf11f90733c47858a66d19bbff.nq.gz
    ├── 3f680bcb02348eebacc154e0789f0798725d7b8d.nq.gz
    ├── 400f7a30171c6bcc9263feb2d7f3950f91a705e5.nq.gz
    ├── 4138a88f4b972ebe184c0719804e69c7770ac666.nq.gz
    ├── 41d98e4e1f4b3f61e179b58347ab2d8373bf2d17.nq.gz
    ├── 41dc6c8e89104d9a4668c1480271e783150dff97.nq.gz
    ├── 41f8e8f02cf28989fd5c5895b0729bcbae6b9c51.nq.gz
    ├── 42419123f0f349f8a68a0379470aad8de3e5fbeb.nq.gz
    ├── 4282cf80b9b79c072435f27055c8ceaa00d33f9f.nq.gz
    ├── 42a9f556aa1eeb68e11df495cca8d207762c9259.nq.gz
    ├── 433b55140d8493bb8f80f4c3befc7b1704af8ff9.nq.gz
    ├── 43791f0316ee2afa2cbc7f9a581bd45d46cf7cff.nq.gz
    ├── 43fe0a91b81fbb2c89e30c53ba10b7c0af960918.nq.gz
    ├── 44d2b2cc3896442e53e122a00665c3a2c08d5f1f.nq.gz
    ├── 44f8dc65849da42c3d08d0199c23c6b4e18cf617.nq.gz
    ├── 45dd01e12f375251fbc984066ddca5c94493e9df.nq.gz
    ├── 4640c7f8d8c018b31c550a39328f44ad3c4eb889.nq.gz
    ├── 46b6da280afa5929cc07ee5699460ecbec684282.nq.gz
    ├── 4746d74005d6408b2f30ec61ddaf7e96cc6433c6.nq.gz
    ├── 4828eb575c2135c2cc8adbd03b49a5678df63b81.nq.gz
    ├── 488e9061824f527bede66c3bace56126d094f071.nq.gz
    ├── 48b2e14ad01409eb18528f0351268737c573e13c.nq.gz
    ├── 48fb9532bda8cbbd7429a35b344e7793ad80ec6f.nq.gz
    ├── 49446b2603b083e7a6a53b6adc0d954a17b33f8c.nq.gz
    ├── 4a465eb39dc953d625229c25865a27b31783de9b.nq.gz
    ├── 4a52b823e1cf6a6f46b9b61370d8491f46c7b629.nq.gz
    ├── 4a6bb623d784110e511243d2e664f97c1fa7ecf3.nq.gz
    ├── 4a877cb1f8e63842242562653c2a87227068f84f.nq.gz
    ├── 4b1355aaed68acaebdbaffada94d62d1f80a5290.nq.gz
    ├── 4ba52ba2c8df6758685c8f65f490306b5c44eb76.nq.gz
    ├── 4bece8a9bb45fdf65da8a1358d35e549e6e19131.nq.gz
    ├── 4d9754cbc28ef54ee93d4587136e34d9654edb85.nq.gz
    ├── 4dc9c8c5d90b45cc324d4cba9e92db932ee52bd4.nq.gz
    ├── 4ed17d9dd3da4069efb40494b748ac5b8bc42841.nq.gz
    ├── 4f5d82969032f76d0fb86b547eb65a7c61177b79.nq.gz
    ├── 4f68b517e63d91ee0bf2f1045ad0191e5f59368f.nq.gz
    ├── 4f6947e8148c45dc063180a4f9f4896912603207.nq.gz
    ├── 4fbf13a727bf54f59d9f3de61bf5b8ea3d286bff.nq.gz
    ├── 50559aaab08aca1379fd91c74a90cb72e158e390.nq.gz
    ├── 51a76c129033afcb82a6d1ce6490d75aa19c5a1d.nq.gz
    ├── 52b71db861bfd3c44ba07449e1b48dcf3aec8b1e.nq.gz
    ├── 53953b33e9cb4ab10f0ea995f351fb31d7146222.nq.gz
    ├── 53a8ed162fcdad40c58d6b093909bcb3f63e0024.nq.gz
    ├── 53cc33821f49d3ebb7e047c04a3ad3b20c79c047.nq.gz
    ├── 54915edd32806c0a522ba4f32460b4f0a933150e.nq.gz
    ├── 54a8a39cf33250d3450f4743b9302dc756977e71.nq.gz
    ├── 566eb7c7d42fb7d02a02fbda2bebee7529cae028.nq.gz
    ├── 56e947e94bde0e7f2cc76d477669c803393119a7.nq.gz
    ├── 5738f8c5240b79c84ad5b5f24900c47815df4f14.nq.gz
    ├── 579dbb0444a0eb2e91f3e30c729a9502ad05e629.nq.gz
    ├── 58183af12f5c31eea211bb50564e207fa1942fbc.nq.gz
    ├── 581f02502e3707d3385f83c13ada040de8113e18.nq.gz
    ├── 586d5e74511f5f5543a30ca77b017d1ba3cc8163.nq.gz
    └── 587dbd928088bf377fa3fb3f338e899ddbaf3c14.nq.gz

8 directories, 200 files
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

## Source repository

[benmosher/eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
