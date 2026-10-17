# Repolex Knowledge Graph of Nixtla/mlforecast

RDF knowledge graph data for [Nixtla/mlforecast](https://github.com/Nixtla/mlforecast), parsed by [repolex](https://repolex.ai).

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
rlex download Nixtla/mlforecast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e3f057376ac3d9140069f44b3937107dc3cc4ff4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e3f057376ac3d9140069f44b3937107dc3cc4ff4
│           └── chunk-001.nq.gz
└── blob
    ├── 0082d147acc70a2b1d81718d08793eda95221be0.nq.gz
    ├── 01f50f9103cb97673f062bb9df6ebf50ee68dc71.nq.gz
    ├── 026b30ee2951ac8ec3270467e5c82a9a1581b5a6.nq.gz
    ├── 02aeb16888a0fe76f7e2348d49a8b49346f9ecb3.nq.gz
    ├── 02eb01eb7b9a0e45d0e53647ceabe7df00bb91cf.nq.gz
    ├── 05946a017a773d73effc08593146709ea6f8406b.nq.gz
    ├── 05eadbfbc145b4f3db9c7defe9d2a4dca8c8074d.nq.gz
    ├── 09464e3dfb1c9ca32d3c9a0cdf9901b0660d3198.nq.gz
    ├── 0a138b26e55d444674ed5a17bba75e1fac08858e.nq.gz
    ├── 0c0ced01112dce20bb38f59a882af37e5b891e42.nq.gz
    ├── 0d2d7cf3624f9537f8b4a820426cdfecfc2fab69.nq.gz
    ├── 0fd06912909e30e6692a5ab18a0451bc86cc97ed.nq.gz
    ├── 1015b687b0515fcdefc78951ea779eb0392d6b9a.nq.gz
    ├── 1132945ecc9cf5c64eb9b85e6c43b307a0476f0d.nq.gz
    ├── 120e9b0ce52891a817e27dd0217d24f54c9bb45d.nq.gz
    ├── 1222b9b9b4db4f4b7712c322c9d97088477478d7.nq.gz
    ├── 12e22b0b52efa1a129630bcd55a36a7f81a40049.nq.gz
    ├── 150e08f1eaf1ce526bf3002862ecb6c05cdd37b1.nq.gz
    ├── 1544c4576de4b2779a26aaaf322a5dad00c01aa2.nq.gz
    ├── 17dbdce4afd9f919aa33928cda1b5c39c8f7fd1e.nq.gz
    ├── 1880aeb7df332f195e59abedb7db4d2b1887c7df.nq.gz
    ├── 1a7b9cc9791371db2f612edb9933b569b7230c5d.nq.gz
    ├── 1d8f4452e566c818bd9bf8819688cb0258418f60.nq.gz
    ├── 1dd19a44c6b16dfd83162680048d1efc10fd33a0.nq.gz
    ├── 2203e14a3f0c5583b873369e453042e755c93261.nq.gz
    ├── 263804344b70d7beb10e5a2351b80a998cf98d35.nq.gz
    ├── 265518a507df20ed99750e55c7ff7a55e4d5c783.nq.gz
    ├── 2657bf31e41a3b33af579d7e2c7eaf405302692a.nq.gz
    ├── 277cccb6121393f7aed14e23370e81cdb82a0164.nq.gz
    ├── 28f6d8d060fb4e82fee6bde3d6c051322969c2e6.nq.gz
    ├── 2969e3a0a9ccc2fdfb034f368d6e1cc7a2d24e69.nq.gz
    ├── 2a89a69d84908141bc823c0ced4e5317f4219498.nq.gz
    ├── 2afe548ff713a960af5156123a22b82bfdb95811.nq.gz
    ├── 2e416d8db413f337a58bc8618367973289261baf.nq.gz
    ├── 2f4cde6dd4a9103ab8b5315af9935a4d2b76829a.nq.gz
    ├── 2fbf954d1a73e6e0ae36005845d2e9777789626a.nq.gz
    ├── 30f63ca6c326e0c5188eb21233262e12d8aa592f.nq.gz
    ├── 3128f0e430a8a2a4c020f4eced192c35a64c7da6.nq.gz
    ├── 32903322cca859ceb91163a39cf31da17958667b.nq.gz
    ├── 34a4012708307db239eeac312dba0e734280c812.nq.gz
    ├── 380619a4fc35557b1b78e23131cb0dad085de2ab.nq.gz
    ├── 38d6f5bdbabf8a8ba9751581db622342dc485611.nq.gz
    ├── 3944b68e83dead57cb9c6603066bdbf566016599.nq.gz
    ├── 3a4452264a9e7ad23dd694fa2df485ec17891104.nq.gz
    ├── 3a4e2b004a45442b9428da8bc026217da9ac6fef.nq.gz
    ├── 3caa1a7f11e64a653bcb793660de450da780b092.nq.gz
    ├── 3dd47007a4ab5aad55083acf90a6404a76b567f6.nq.gz
    ├── 3de46d91d66d8dd64d81d3f5553d69724677238c.nq.gz
    ├── 3e05181594e3d8b2d83df61545f218b92c27650b.nq.gz
    ├── 4011f0361a0615477af746a4eb2f589bfa683e89.nq.gz
    ├── 408e7b5a52a65c74da5330133140dbd3e993ae62.nq.gz
    ├── 40edf8bf93d03fac249c1624eb1bcc0f6beebc70.nq.gz
    ├── 41c11173c710c4e971c2521da415105374484ee2.nq.gz
    ├── 439f20af9b933f0e8d1861d46f3dbf250a2c06aa.nq.gz
    ├── 43b92438b42c68a8b48b6d0581ae43c88efb7f76.nq.gz
    ├── 449e9b1bc18c82fdf85dad9b3898cf76b4ee561d.nq.gz
    ├── 46f155d2c5a7253245539c00c32eb91597f89414.nq.gz
    ├── 489d709ae4d0939aeeaa1de44c90e62cd8018fbf.nq.gz
    ├── 48b30e375c9c9039ab4069f88e90ad71151613a5.nq.gz
    ├── 4a9684db576e0e8f920ea02b6dcd45e6603a9776.nq.gz
    ├── 4b6218c76e1bbbb7d4e4bd027da7ff3d8a04c6c9.nq.gz
    ├── 503df6b3fa53e72dd0f856d02e6a9d551621a7e1.nq.gz
    ├── 505ef9677bdcf7978f7cb5d45ed4599dee432c3c.nq.gz
    ├── 50707b50f8d9e1bde70fe77eed85a0f5bb63a843.nq.gz
    ├── 5274dd035a7261bb715f9f88767e7c65ea56882b.nq.gz
    ├── 527b420f50a191d9c75f4fe25af8a4add10bca31.nq.gz
    ├── 56149acfdc0b07d57bdd0b6abd07075002daa24a.nq.gz
    ├── 5681d9b9566d5448c1be6ebced4304a3c314efb8.nq.gz
    ├── 568774335f22458df3735f43312884b07660ae94.nq.gz
    ├── 57d7078e8a94a5b815496688558de0e74b36a978.nq.gz
    ├── 5879a6a3544184814027954cbf7ef11a2ec964f2.nq.gz
    ├── 5882dd0c64f830bb82cf08f61b8348ccfb0779d5.nq.gz
    ├── 58f777f7af332f581f59bd64645948305b3eb749.nq.gz
    ├── 5ac65c2fd7721554c9803380100cb5e248c191f8.nq.gz
    ├── 5b6142dda292ea9bf95e2941b0af4a2acfc520ec.nq.gz
    ├── 5c0e7ced193cb35aee60cbadc3e022a1da0fd8cc.nq.gz
    ├── 5f7e68a63137d7a5d93b0546b028e5b0b7d9693a.nq.gz
    ├── 60176bead501c06972937fb686b30cf18ffbdfe2.nq.gz
    ├── 606f9ff48d1e0aa2fd4dabb04d6d77949399bd58.nq.gz
    ├── 608ef36ad35aac228a351e83c218dd1609667346.nq.gz
    ├── 60e80d79269cb9d523c5799a6dc113807f22b612.nq.gz
    ├── 616da6ea4cb84e05fc273ebcfdeabb3bee379286.nq.gz
    ├── 6815c39e3931213990cbea78d15015867d27a1be.nq.gz
    ├── 69c80f53638c6ea16273f288b05f5e61f38b6f25.nq.gz
    ├── 6db0104ddc67133f782812b4e72fe29c5cf2f7b4.nq.gz
    ├── 6ed3cec1c5a0f9830252c8c299f399a6814036a8.nq.gz
    ├── 700de2f36519df70fc20cf815c997ca151c794c7.nq.gz
    ├── 71415a60d079eaedc27e13019a4b4ba87a6a0bef.nq.gz
    ├── 719db12e686c5312fde5f86038b641bfe04f43ed.nq.gz
    ├── 71b7a57346da3d270e3de85c7bd285b81109d0b1.nq.gz
    ├── 7404181df2222101a3971d74c105ae4ac0e923a7.nq.gz
    ├── 756f91cd95ce0b351b3fefda24e8799c3e42fdcc.nq.gz
    ├── 773ad90c7eeca030650b6aec6ee9064f53d94b90.nq.gz
    ├── 78e6b4d49e5e43537fa5c4bc93391e63798f65f2.nq.gz
    ├── 78f1d73977bc4f76f655719fb6cd578288cec6fb.nq.gz
    ├── 79fb37678b449739036ed525eb33468d12160fa6.nq.gz
    ├── 7afdcb5a6aa6d4f355c1a564b0f0afdbd37a56ec.nq.gz
    ├── 7cc8aa7a49310c3f0b4e02fa92abe84bec51690e.nq.gz
    ├── 7e8972e07041e8ef5e7f56bdbcf29f6ea56d37c1.nq.gz
    ├── 832987c965c8a67a297c009f82877cae18ba43b3.nq.gz
    ├── 836b8620c286208d906e31cac5f71ad4d531c82e.nq.gz
    ├── 8471f9baea9e9b7d6507d3a9d5f54d8b14dc5e76.nq.gz
    ├── 85311b1ba38896b0381d5cd6dd486d7ee901920d.nq.gz
    ├── 8869e790b3893734c630e32abf9640b5e2d62d7f.nq.gz
    ├── 88cc40d73aebf839404be7c62ab95f76ced1c22b.nq.gz
    ├── 8a8e91dc208203bff7fa09d5a050c721b43093b8.nq.gz
    ├── 8b46c302fdb06327172dcd4334aa2b079e00744d.nq.gz
    ├── 8b5b0ec0612585448831190fc005293e8a5efbf9.nq.gz
    ├── 8e7dda1e97f8bebb879002196319c9954d0bc7b4.nq.gz
    ├── 8f658fa094f928302ab16eeca81f9c3b23f710e9.nq.gz
    ├── 90446f28c57c8582e9f6ffaf5e736ead96c4537d.nq.gz
    ├── 918e9fca11d666087fd0bd7a9705151d310ffd73.nq.gz
    ├── 928299c5302ffbe072efd81928fa691188f42b86.nq.gz
    ├── 92fab3cb8d2bd3c061a333e1cf875552f4190437.nq.gz
    ├── 945aea349f909894ff90a6dc0f69c20718c722a6.nq.gz
    ├── 952b1b8f75813d24b7fd876556dac0fe1ec8a0d5.nq.gz
    ├── 956e6dd09a42d7562b6f530026c84db077bc3a49.nq.gz
    ├── 96939d27c9848551f4118110ad588607a4e6fb91.nq.gz
    ├── 9973580b427ff0a90c22150df25772b83fefb5df.nq.gz
    ├── 9aee9c39d76429fecd6014545065075e1b27d757.nq.gz
    ├── 9b1c5ae1fc16170d74aebe4c415aa9a1a9554ca4.nq.gz
    ├── 9c6c09abdc2bf41bbe18f35be3e7c9f165ba38d0.nq.gz
    ├── 9dabf71d50980af486472edd622e7ade7f1a7b99.nq.gz
    ├── 9e155f871a0de14a7e42be0648984d3b3fdb9793.nq.gz
    ├── 9eb1ca58f87a95d2eb45d73e916c764d184b1615.nq.gz
    ├── 9ff43443fca38c01f2ca3e50cb128c43c1ea51ff.nq.gz
    ├── a07abf81173130251efa5950e07b986334260d1d.nq.gz
    ├── a188878b181de963f9b3fdd11cd0ce2558580da8.nq.gz
    ├── a1ae3df4df09663ff27a356795c89189456844a4.nq.gz
    ├── a5c91d4ef49128d3a02597a9bb317c8ba498d985.nq.gz
    ├── a76be888939030e6d991ad308aa9e6e18e1c4b41.nq.gz
    ├── a8b3c619c88731255fcbb189724d2e202431bece.nq.gz
    ├── aaf605463920cf97dcd374fdf87afd31d86ad7bb.nq.gz
    ├── ab05e8321f5f6a6f979f3ad7ea6c478338e33b8d.nq.gz
    ├── ad8b6b2cdc7d337752fa70a464390fe44aefe42d.nq.gz
    ├── ae45e22c03e012dac68614d5d5f79b2d2fb07088.nq.gz
    ├── afdb33555674abe6b2ed1cb2d3e7124efd3a755e.nq.gz
    ├── b2530437b3eab28b7af8f26efe462ff2b01d5a2a.nq.gz
    ├── b386cc110b4561a6ee1824cddfd34844c03669ab.nq.gz
    ├── b63f593582f734452e80ecdb89af63d5dd02c46f.nq.gz
    ├── b6f108276c8f8fd4f9f68cca86d29af74be880b2.nq.gz
    ├── b8a090157a7a4e9566cb78bd548324234bdf03b8.nq.gz
    ├── ba822c0a248cf9940c49eeed2ceb53e536194df7.nq.gz
    ├── bce02f595b80983a6d2f4dd890cdb1e916f32424.nq.gz
    ├── bd831cd3a14cf2c4199bf211c2e9858879b71dff.nq.gz
    ├── bdcedb7dbc75064d11bc95bd1e0996d7191acd0c.nq.gz
    ├── be6999c1e53fd34bfa4892c410b54eee12d6a26a.nq.gz
    ├── c02c201ba18c73d61a5008951fa545a2a8a6bf4c.nq.gz
    ├── c1621efc2a9d380e110789d99315d12fc9823b88.nq.gz
    ├── c19329036d6102f4139d4d43675dcd7967228c3b.nq.gz
    ├── c19616814c7239a1e1718276a6ff2b2483d2e05e.nq.gz
    ├── c238ca8d9ac1b7e6b29bf2ba713a8773699aaafe.nq.gz
    ├── c2540541d41e1d222ac7ea00955a0c81fc96338e.nq.gz
    ├── c27e054fbd58c02018844fae8488eaf60b5dcf1e.nq.gz
    ├── c29ff25cdd1431feb53b438cae6fb2880ba7f96c.nq.gz
    ├── c33f4df6cacd1a3b4fcb20d4cd0995c44188cce9.nq.gz
    ├── c433315d54d47ccdd2299503dd206f8fffbd5549.nq.gz
    ├── c586666540f216efe00867e9a3f0c8f1eae4fb41.nq.gz
    ├── c5ae03b802913d57b391ec75e856a6d17306c03b.nq.gz
    ├── c5b1a4704b3490140e7165edfbba3702cbebb1f5.nq.gz
    ├── c77b05d0edf9704e9ca6a9f2a24234e38fcd16be.nq.gz
    ├── c86a70d2fb481cc197b11a01ea48d93390371b7c.nq.gz
    ├── cba84bf648ec30bbf4b7ec4ccb92ab028482855a.nq.gz
    ├── cbad4479246624d918a0ccd20bcc1446dd67be70.nq.gz
    ├── cbb890a295e774646109d00d3d701afdba877c87.nq.gz
    ├── cc62c6dd65920fc2bf9f6b469657f62cfc6a082f.nq.gz
    ├── cd760bc79772a136bfca0b7b88fc46331996a1a6.nq.gz
    ├── ce7edd0d0c0ebfbdc7143242f9183ae8b66cf232.nq.gz
    ├── d033fb43c8e692421a32ea30fbf68ba8dc240ec8.nq.gz
    ├── d03f35ce46f1638723e15a34f9ad6394dcb8b26e.nq.gz
    ├── d0924c3b873634f3ecf62b0731493c73f91ae9d2.nq.gz
    ├── d2fd359b180dda289f5f0eb0e0a6e8d435ca47fd.nq.gz
    ├── d302e79c17c2540e08508f88b757fdefadd66afe.nq.gz
    ├── d35d9ded5456d574fd33453da66084b0634d0810.nq.gz
    ├── d4abc83d04823b52ebaed877b26ce8ff5e385c08.nq.gz
    ├── d5b6271e55aa61bf7b37c4a7ee619e3561768a31.nq.gz
    ├── d65964cdf237717a3363a3612705d3818e82e22a.nq.gz
    ├── d807c0e32319f2209defe5a5fa8c9f4655bafca7.nq.gz
    ├── d8d848516667800076e97eddbaa64c3573fb0f3e.nq.gz
    ├── d948da342e1e20609963af5c7522322df3656108.nq.gz
    ├── d96bd8584b7c97d0399cc6c5d6b20223bebd3959.nq.gz
    ├── d9e0d95f866e7a5f7fec4f972fcbe38c2c65cda2.nq.gz
    ├── dc35d5b4417449b156ba8eccb7310045ec95832f.nq.gz
    ├── dc7f904d886e44745c5a3584b1ddf2bac455f464.nq.gz
    ├── dda1a877e264ac57ee54acb902d167a4c043a9c7.nq.gz
    ├── de72ad929c30933b167b3461b5738c1fa37bfee8.nq.gz
    ├── e0266cac632b8f10d95cc48704efb14d2532d0b1.nq.gz
    ├── e248f6f3d3d92600fe318634e429e4941df190ed.nq.gz
    ├── e3bd826a5e38ea08793c4f1ba0db83567fed267d.nq.gz
    ├── e498573ad28b30520b36f76614416aac006b12a6.nq.gz
    ├── e4bbf1135b09a6fb4be4b7524c9cd8fa08061aa8.nq.gz
    ├── e5751208716d6c08e937c5f407d1d18d33291567.nq.gz
    ├── e5f33342874295f851fa548fd3811f054487bfd8.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e819bd851143d05a250041d1219828bbf8df9550.nq.gz
    ├── e8f25c7286495bb51706aa5cc12dfafe9ce69b48.nq.gz
    ├── e90b6412cfbed0e5d195aca4ae49f4cb187cb5c1.nq.gz
    └── ebdd9d3e047c10b120006a14f2ee6e6a528893a6.nq.gz

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

[Nixtla/mlforecast](https://github.com/Nixtla/mlforecast)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
