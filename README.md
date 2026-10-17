# Repolex Knowledge Graph of spacetelescope/poppy

RDF knowledge graph data for [spacetelescope/poppy](https://github.com/spacetelescope/poppy), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/poppy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5e76d377bd27cce0e43268db4a1bcc61c29316b9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5e76d377bd27cce0e43268db4a1bcc61c29316b9
│           └── chunk-001.nq.gz
├── blob
│   ├── 00d34896d97f510238b2f8d4c17b7d47f972aec6.nq.gz
│   ├── 08186f13ac4eeab8d6e4d71fb23d3f2d7cf0fe35.nq.gz
│   ├── 085e752f828673cae94b8cb11fe4f89afea55a57.nq.gz
│   ├── 08efe6e184a60708e8081cc36b2a8019f1f8d622.nq.gz
│   ├── 0aa32b71a2c1772619377e4f524e449f62a03c8a.nq.gz
│   ├── 0ad148be6c1f21b18f5f4f816327ffdfff1992f0.nq.gz
│   ├── 0ae9eef012ef61c0916dcf0e9ce5e02cf731936e.nq.gz
│   ├── 0b3164f410c41e4dec35f30fcbd43970649da7db.nq.gz
│   ├── 0c5bd7b5faa9035ddfb515b7224d81635234612c.nq.gz
│   ├── 12215c1fa73a86f3b88587f4beaf0b807db72876.nq.gz
│   ├── 14019a81294d4c0b31be0c91bb51d9131904e7e8.nq.gz
│   ├── 14d3c81d70b66ce03856ac6a6eac74793ffd5009.nq.gz
│   ├── 15666abd5c1685e2f94f32c581c7988d3c122e4c.nq.gz
│   ├── 1884dfac4c5f9525147a1d15a92ff1d1e9ed5026.nq.gz
│   ├── 188b6fd0175b3b6361ea91b9992a23396a28f9f7.nq.gz
│   ├── 1bc73716889891174c4ba464a4b7989ea755bd92.nq.gz
│   ├── 1c6f3d43011e2ab49a8bacd96a7104ab5440b719.nq.gz
│   ├── 1cd322690975e951bba4829a8efaf2f2acaccb4a.nq.gz
│   ├── 208e653a597d810e05162aff7e7270b4c106cf15.nq.gz
│   ├── 22ed47fd7e33a4b9f0f11c56e3c0ff697b5c1ce5.nq.gz
│   ├── 230c35f1cee2e79120cc4f1c4b7339110f992c19.nq.gz
│   ├── 2519d52b3659829116a189031a4605ca6fca9bb1.nq.gz
│   ├── 263aafec3af365041ff64ff382f892b1631620cc.nq.gz
│   ├── 26b64cfe0f82cd145fecf98684cb6083d57fcada.nq.gz
│   ├── 281fe8a71b55a90441d515026d20e9e0dc9a8910.nq.gz
│   ├── 286b2c898e60fe66cd010c4e0abdf9723fdd5a55.nq.gz
│   ├── 295781fa86f499796d3f1ba1173ce80c1cf91c06.nq.gz
│   ├── 2c027bd299e9ec3c0d9e7e4f92bb1056703161ab.nq.gz
│   ├── 2c23eaf3d7d71999eff588071865e3fd59e4218b.nq.gz
│   ├── 2d34419e30c00dfb654e69a1f5ad7cf396576073.nq.gz
│   ├── 3134382709d13f72352f78420f4ff19512209f3b.nq.gz
│   ├── 3267cbcebb83e106ee3e6d8d447a5499064180c5.nq.gz
│   ├── 36939dc3bf444ee2eb17b0141425c7026fb9de64.nq.gz
│   ├── 37c871472c9e7983c8861271613eeb3b31527801.nq.gz
│   ├── 382642de3c2c5d4b6000846d4d5cf8c135ee6600.nq.gz
│   ├── 392d15f119c92a9874d73c1fce964d44290a5de3.nq.gz
│   ├── 3b39e8da6948ce074a4f956767b20f413eb26ad3.nq.gz
│   ├── 3c3d00a9dcd31ead0c27e210bd149cc5eed5881f.nq.gz
│   ├── 3fddc0c298269c87307af60c94cb6a47c5910332.nq.gz
│   ├── 40a0e8fd4a61e7fdca6a339d93cba5c9029141cb.nq.gz
│   ├── 4143955650a8bce158bd829667ccb8479881effd.nq.gz
│   ├── 432267972c8fd559ad75cf869713e3dea797a684.nq.gz
│   ├── 45f1af2d3f604dc332b4fe374395675d0c9e5b7e.nq.gz
│   ├── 47d4621dec492470d506fdb319423fe5145e5930.nq.gz
│   ├── 4982040fc88bd2e9b6600c0d063c73811e6f068c.nq.gz
│   ├── 49bf993596549a5031a9e200403ad972b241bb2a.nq.gz
│   ├── 4ecd4a85815150d757dff2725cb9e612d2cec8a4.nq.gz
│   ├── 50ace8bc8ac53bc442012952ed4d39b6d9d4657c.nq.gz
│   ├── 52432de93336023f868afbdaeba1884e22aabf17.nq.gz
│   ├── 56fada548d53440f394c4e5ffc99203f16ce8c35.nq.gz
│   ├── 621caf6181213abe80c29caf0f416c5acec66360.nq.gz
│   ├── 6415cdfcdf50ae19a398dbc2f4ff59dcdddb63c3.nq.gz
│   ├── 6457129b3ca11ee708471f9fc467f686b99f9460.nq.gz
│   ├── 6540e7f4e303dd4af93cb8873df30ea188e969e4.nq.gz
│   ├── 6a3705cd15c5f7d20298187f4cca172a8c90eb2d.nq.gz
│   ├── 6ae9d38039eec1247873c4c2b56d331ae2639f2a.nq.gz
│   ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
│   ├── 6b9dc09f09d8d372fe5b605edb732daa71a46fb2.nq.gz
│   ├── 6d8e417823e00d9493a19ca8d6ffc5e90157ba85.nq.gz
│   ├── 6da0bcaba0d64fa19c4dfc8b9f7d24068964ce3c.nq.gz
│   ├── 70a4579c5d368dfb3a31380df24755fb4ebdbc9d.nq.gz
│   ├── 73b77b02ed16103d6647e4213a1b4cdc048308e5.nq.gz
│   ├── 7498140872e5b6902b01bee50881b35bc5f5da02.nq.gz
│   ├── 7589d4bff10b00a050e031d2b304ff245dd510d7.nq.gz
│   ├── 773d7ce091d3e6ce21e6b490364b2e4789ccd0e1.nq.gz
│   ├── 775851fcfc8c8a89e9ed537e8b056681d2a56120.nq.gz
│   ├── 776d0479e86a29dae13bf785a880c54710cec42f.nq.gz
│   ├── 79bc90b69b3d1ed0cead4da4a9b9a13ffe35e467.nq.gz
│   ├── 79f254ea51752f18878ccf6657e3e83e2d0cf327.nq.gz
│   ├── 7a6f17422582e30104ab5e1e82f2bb85758a6d1b.nq.gz
│   ├── 7ac323b0b5eb529880272af88d0dd01e374df294.nq.gz
│   ├── 7b79c8bd555c791c03abdb74cd4cd3e841f2d91e.nq.gz
│   ├── 7e95291e3af77010b8bbf46d0acfb3306addecb8.nq.gz
│   ├── 80f6f042182268925938f6d32a25906a35b56056.nq.gz
│   ├── 8425f72d752d7e18026bbbebe18334c66afca789.nq.gz
│   ├── 85ea98ccdcdfb9e41da14cf6a6ea0daf0d961a79.nq.gz
│   ├── 879702da9bc03f5afe97e7695a5778cf628c5d39.nq.gz
│   ├── 8840939c99697d8817f1616e6ac3d2a12d29ef57.nq.gz
│   ├── 8bcf29bec7857f4f3565a70e0798645727a37c7c.nq.gz
│   ├── 8cd9560d835672b037a42f818763b1697aba67e7.nq.gz
│   ├── 8d59d50693403c16daa475d0bbe7c732d31c8eee.nq.gz
│   ├── 8e6872ef39cfbbc6fa483a206fec72964f8f27d3.nq.gz
│   ├── 8fc1f5af25952b123b2bf8d2124bc88289556a70.nq.gz
│   ├── 909902bf5ea667482906d9eca49fb14f26db400f.nq.gz
│   ├── 91dae1512483138e7354de498fb70a78e622bf91.nq.gz
│   ├── 93d79811de51fb602f22d487f9f3fe37e6135259.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 9484a1efe4a4ce4a7e2a7fe17b810dfece0216ea.nq.gz
│   ├── 989ccfc75b97304262f1d225f68018754a8243c0.nq.gz
│   ├── 98d31eea3295dd91751cbb96c9d0c63dc209899f.nq.gz
│   ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
│   ├── 9ccbb518f0e8d6e85601de79da6d125039c9236a.nq.gz
│   ├── 9fad22a63d278acbf2823ccb8481cee7aa8845c8.nq.gz
│   ├── 9ff4aa9ff4e3c09fbd0187abc39fc09c1b155ff5.nq.gz
│   ├── a13f23bfda7a935ce4edf02035ee584b6f6282f8.nq.gz
│   ├── a35b3a25487798945ecd3c9da9fcf9540609621a.nq.gz
│   ├── a49d8c6ca278f54c85ef106cf6352c8050d22e02.nq.gz
│   ├── a71eacc881db778a436751babac1a738083ebafb.nq.gz
│   ├── ab058ecf382c3c201267d5dc3581bd8d43259ecf.nq.gz
│   ├── b0c842de8b0aaf679440e8ef5e37243ee4dc1f25.nq.gz
│   ├── b3d31496149ebd74a72f4958de59560d5d20012f.nq.gz
│   ├── b4839cc9d7a473ce18c6260b8f3bacb1936a1756.nq.gz
│   ├── b9591266eaa8d385abf4f26e2a4c7ec8363562fa.nq.gz
│   ├── bf9f69f1aa39c7147bd7535272df08009ad5c066.nq.gz
│   ├── c11699446190437951248f8a899af17abfba2657.nq.gz
│   ├── c2bca3af116dc3c3f50313c7f5620c74ff255837.nq.gz
│   ├── c3a70d86ca36a5494303019bcd7f02630e339d2e.nq.gz
│   ├── c466602f26a2db11fa899f4b0aa191998be454d6.nq.gz
│   ├── c50ac93dfcd73ea6e13b7f1051357e8ff9e44292.nq.gz
│   ├── c861b5890c5c2e73dde344beafa92b750eb5aa88.nq.gz
│   ├── ca06bcd7c049e03c44f32f444250eac815664999.nq.gz
│   ├── cc2ea34b78d4ac44438bb3b4a40f06f664f59e84.nq.gz
│   ├── ccaa1c550cf24d730c2df13be48e7daf17b2e4c3.nq.gz
│   ├── d02a879a662007f0efc45734f0b91a1144f6664f.nq.gz
│   ├── d178f0d166c5d769e4df18421f1803e3a7deb6ab.nq.gz
│   ├── d680e8440fd535947daf7432838421aa9317bbd6.nq.gz
│   ├── d849874adb036be42fb50eda0d7f13fa4447ac11.nq.gz
│   ├── da4c66e575104352b03d49d12146d09fa579bc4c.nq.gz
│   ├── dd00dfd0370795d688843e998e8f359281e7ed44.nq.gz
│   ├── de044d0bcd1f809655f5654f0814b2f86e605622.nq.gz
│   ├── dfaf1fc92d126eea448909924036640193a6018a.nq.gz
│   ├── e17272d3a74234f7eb8dae80a7d500e96b2b7fbf.nq.gz
│   ├── e205e307fd6d1ff7ed1a65642e8b90e9b04390ae.nq.gz
│   ├── e6cba06f4ec20fc4649a74b1352764603d11fe0b.nq.gz
│   ├── eae48f5be3d23246872af8e14d76a3c99b553c30.nq.gz
│   ├── eb143c91a3c471193219493f52e6d8401f74b510.nq.gz
│   ├── eb626f3e30281915042afe7594e871676b339e0a.nq.gz
│   ├── ebfc6acccab0d10ba8aed9bbd07cb38b0305c113.nq.gz
│   ├── ec4ecb108504ca91f4e1055759dde7fe0ed3ec80.nq.gz
│   ├── ecf5d62fcef2b89e9e6a8e7b16021b1b774db90e.nq.gz
│   ├── eeb50185f83f69ead4f3a09a5133f26ab4f514a9.nq.gz
│   ├── ef2c49d69ef70322a756bd01485a51cbbfd16256.nq.gz
│   ├── eff0c4c4c0c4aa7289237a5c799e09b4fd31806b.nq.gz
│   ├── f21ccbab1fd2dfc1c062e193eae5b80af9600f76.nq.gz
│   ├── f27e5b1054efb75ce76742ee8c95ff528932000b.nq.gz
│   ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
│   ├── f7c6358db96c430d79ebe23dc2a4bb6e76932e6e.nq.gz
│   ├── fa2c30ce2094d547b3242c4bcd3636809f3fdc29.nq.gz
│   ├── fb7b6b67753b8612cce159dcce8a23d9fcf0ae2e.nq.gz
│   └── fc3d93099fdfc3bfb09fb4cb9e26610a918fd874.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5e76d377bd27cce0e43268db4a1bcc61c29316b9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 148 files
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

[spacetelescope/poppy](https://github.com/spacetelescope/poppy)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
