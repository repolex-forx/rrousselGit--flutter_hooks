# Repolex Knowledge Graph of rrousselGit/flutter_hooks

RDF knowledge graph data for [rrousselGit/flutter_hooks](https://github.com/rrousselGit/flutter_hooks), parsed by [repolex](https://repolex.ai).

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
rlex download rrousselGit/flutter_hooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c47821832bdc45a04b61248d99725e9f45690b7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c47821832bdc45a04b61248d99725e9f45690b7
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ce362e7c26d2df2836d09aadf09a797e4b27f5.nq.gz
│   ├── 04d2024dbc01adaf62d5601b3381466487331d52.nq.gz
│   ├── 08df662c9c02b141c4de9ae6fcb2825e680aa4a8.nq.gz
│   ├── 0942c6b960b2d82c9213aef6f9c059d48d54904f.nq.gz
│   ├── 0accf1ab8a8b4351e04309498783109c254d9c16.nq.gz
│   ├── 0b9bf88dcf6339934c40bf73ca1abf5d4b259bd2.nq.gz
│   ├── 0f0bf428182630cdf2f64db537b35df1164940f1.nq.gz
│   ├── 112dd7e2be6da855dd03b2073a4536c2ede3218e.nq.gz
│   ├── 17e329519080e99ffe879ee695ea8ed06fa25368.nq.gz
│   ├── 18245f2c56e2285753fbe906720ba6401451a6eb.nq.gz
│   ├── 1ce2ebe68ccfda8bf97c68a3c98db10a4f5f4fc6.nq.gz
│   ├── 1d182cf64d9f9306f1a9dae1dd6b623097bbd7aa.nq.gz
│   ├── 1eb000df84e79a4ad4d615fd222d2afede756f75.nq.gz
│   ├── 20065d840e792fefc814f297fc27e89ac68d1b9c.nq.gz
│   ├── 20431916c7b98ed2931723b9e1835be0df788922.nq.gz
│   ├── 225568aeb5a73ea9f18aa0aae5fb9d670644cc47.nq.gz
│   ├── 26079874f1cdbaa83992c2b56b805a428b224ab1.nq.gz
│   ├── 260b868e4decbb0acbe29faf6afb1d395ceb00b9.nq.gz
│   ├── 291aff2fca4677981476740bf41a82c02ab7d683.nq.gz
│   ├── 2a063ad9ed465393c2a815e928bd3198eca8c4fe.nq.gz
│   ├── 2a3dcf8635f2b12e72af4e5bc912f6505281a552.nq.gz
│   ├── 2c71bf32cb4e184a2e71d5f30269335e3cf68b00.nq.gz
│   ├── 2f1e4bb3d2dc4c1c51333f35c5bc1fcd83bd95a6.nq.gz
│   ├── 2ff9bb0d510975efc1c20f497673a28a677aaa5e.nq.gz
│   ├── 30cff7403da04711c46979a06f6bf8eb10ee088a.nq.gz
│   ├── 332337ba344e92581a960cbbe9240fc9d5e99146.nq.gz
│   ├── 35cc10e5f8e69a773f08d79ca4cd94a4e6c1b3f4.nq.gz
│   ├── 39bd9ac1903537acd3f148dccf39b8adeea66901.nq.gz
│   ├── 39ce2edf69338fcffeca4d58634b2511540313aa.nq.gz
│   ├── 3c2be358089caebf14b571a0725a1765e278a488.nq.gz
│   ├── 3cc7adce5c817afeb00ccb11f99b4c2bd71e1390.nq.gz
│   ├── 422c85c2dd5ad1e40c927aff36d4b2c81ccad055.nq.gz
│   ├── 42e2ae1e7c2acdfa050a8b42f861a3ea952e8c83.nq.gz
│   ├── 43533b7cbaf0004277f433dd782bf91d110a49c7.nq.gz
│   ├── 460bc20bcbed6e300d85bcfa7de0dcc5591b09a0.nq.gz
│   ├── 497ae8c03d61dd73755a2e7aa63921ef77dd4623.nq.gz
│   ├── 497f98de41c38cfe9c8db3260b448d07761cc955.nq.gz
│   ├── 4fac1d8bf2688ceb033d8d4aeb838e3efeb66a05.nq.gz
│   ├── 536952386ffad0a048b20a36f2bab81ce86267b5.nq.gz
│   ├── 57863ce8766df8590de763f3cd65737ab9075a7a.nq.gz
│   ├── 5bcdc8e2e4f8a694a17e84f968090696a955aeb7.nq.gz
│   ├── 5cd7b254b0cd27a0277eb25a667272bfb252345a.nq.gz
│   ├── 5e4a954da6fade45d13bf1e494e616f2a2fe2392.nq.gz
│   ├── 5e8ba7d94956fbc52084bd8e1d2d23b5e436bac5.nq.gz
│   ├── 5f68465d71ead82454999d76d9c44b425262d379.nq.gz
│   ├── 61608efad6b357c0b3a6cfca4f2a07c1d8f1e033.nq.gz
│   ├── 621a339257da95fd428f7b25aa4d7a1405dd7b36.nq.gz
│   ├── 63c29411fd241c0b18caec66652fe43deddf8ac4.nq.gz
│   ├── 65c5ae355a29ebb0f9d5dcd05f6137b7750a8293.nq.gz
│   ├── 665aef49c3c7741c8164a2bad7b83152f67f2cb8.nq.gz
│   ├── 6b68671e8d5181fd30bad6f5ae4aac916016bce9.nq.gz
│   ├── 6bc80913c191eb132e11893383151de63971304d.nq.gz
│   ├── 6fbcde16ac65ded9f3c5d29360f740a511c02c21.nq.gz
│   ├── 6fd78482ffb625a8d53e415d1958e822673aa3cd.nq.gz
│   ├── 70ba0d90c04d545518270515685f3b2865666edb.nq.gz
│   ├── 73f59820bbb1ab66a050a9669ec3405fa932b596.nq.gz
│   ├── 755f82abfa181486243d894d1f21fe69db718190.nq.gz
│   ├── 75f6733ba268dad03f82617eb0b5a05b410dc696.nq.gz
│   ├── 7671a3a8373221115eaddeaf96f4f77751421a3f.nq.gz
│   ├── 7cd4a811120efa20f7933ea5a8a9190b652fcee8.nq.gz
│   ├── 801a8b7b7349306176352971b8b4a90d63223358.nq.gz
│   ├── 8118df91b31785677fbd3fc2f18d12ae7f9897b8.nq.gz
│   ├── 842691d4af485985f813d24c98ba9cdace4cd899.nq.gz
│   ├── 8510c736206c2222c27caee922086c3e9fc926f6.nq.gz
│   ├── 8e0c89474e74f3b77455995b9a5d8c5b30080a2a.nq.gz
│   ├── 8e1f84c459d3f64cd17ef7815621e7f6657ad259.nq.gz
│   ├── 8ffca397093cd7af7a3ee0fe7066391787475bb4.nq.gz
│   ├── 9541139501a40629fdc39d3e0c6934d179b6cfa1.nq.gz
│   ├── 96c5e83a78f0782a4ae033af52304a7995c98af9.nq.gz
│   ├── 98e015efd2e2f5599f67cbd948d4ae3c65a2cb5a.nq.gz
│   ├── 99b149915e66dca0a07e2837cf1991cdf3676b7a.nq.gz
│   ├── 9dea06d4094be27436a45798d0d8fb7a4b8611e4.nq.gz
│   ├── 9e122a93897a2023317c302921817abb27b08be7.nq.gz
│   ├── a4567049838e38b0c5ec0b87c95556ff41acca5b.nq.gz
│   ├── a56253598ab8d5d9992144fe339b4eb8b2a74058.nq.gz
│   ├── a5b77c3ae29ba642e0bd10de8c61cc4f5901be4a.nq.gz
│   ├── a6c42aa4f88d7089366015c0a3eeb2abfc28bc5e.nq.gz
│   ├── a70a1619019144c8de4aca2ec55352e00a5fda9f.nq.gz
│   ├── a804cdee24c003c0062456a62ad84474f579f30b.nq.gz
│   ├── acce0f5ef0fe8683c670f33e35c38a9bdb1a6061.nq.gz
│   ├── b08d0de91d605bedca94675abafffebe6fb7e60d.nq.gz
│   ├── b139d652962c28023ef2e5badb2b94f4f4795950.nq.gz
│   ├── b33e2e621736aafdf44edbe522a663fa6e0e7380.nq.gz
│   ├── b388f9015bd1b8e40dd44945d384bdf28feb41aa.nq.gz
│   ├── b424b10bcc1a1160821aedde52a97b8b2049fa2c.nq.gz
│   ├── b461ce3d194091b2ac1b6edff2b6a2e63baad99e.nq.gz
│   ├── b620e4b8e5b366884054f06ccca40f9089ab39f3.nq.gz
│   ├── b71bdc5979dff525dc4d6075b70b2cc27ccb9f67.nq.gz
│   ├── baf99fa0a2a4a1b4874f402cd45f317303fa6670.nq.gz
│   ├── bbe16734aa314475e4ab52ff14edae79d76029e7.nq.gz
│   ├── bc11bc861de15e64679548c0f432b85ff953a9ea.nq.gz
│   ├── bf209c687eca4b0ae676e2f45ed21f507eba06ed.nq.gz
│   ├── c577703d815a1d0d37fe1603eefe26b0947d137c.nq.gz
│   ├── c749c6db61f4ccd6e0fa1da2f0a6edf9730711e2.nq.gz
│   ├── c7746231ac819f7cf21f62580f09833f126aac64.nq.gz
│   ├── c8b8ef80d9b925b8afe16480e1f683a96b90d3cd.nq.gz
│   ├── ca240248a8616c1c34107cfec5de9f2c9b6ab489.nq.gz
│   ├── ca672863338e370892b8ae5d48543c667ef9514c.nq.gz
│   ├── caba344a113276f98affd1d4ef18e7ec2e3e90ab.nq.gz
│   ├── ccf1072818c13abdd0da7eabc0dceebea7872e7d.nq.gz
│   ├── cdeef1d58360ab6945f1a8f08991e2f879e611fa.nq.gz
│   ├── cf594815d2481660ac2476bab2a93935c0dc6e35.nq.gz
│   ├── d563d17df42013e22c746e68d6cd67e0568a89dc.nq.gz
│   ├── d5b69ec729809cbbd76df776436ed14074683d08.nq.gz
│   ├── d85365b28f8fbadb66f0d86e77218bc4342a2ae0.nq.gz
│   ├── d8b8abf13101da540b402003fcf1c257b6a8ab7d.nq.gz
│   ├── da9e22805bf838a0b54b73a684e15bb336906e18.nq.gz
│   ├── dbbf21674d073db55816ed654acaac2a71a7fa19.nq.gz
│   ├── dbc1d97530b0bada5d9f499207b59b42545b8f4c.nq.gz
│   ├── dcae6ad439d86c94d0171643ffa3290d0eace5bd.nq.gz
│   ├── deeb939255de03477e7de25147509950de58e07d.nq.gz
│   ├── e0edab3a0432cb510ce6a83482ebebcc7efac44f.nq.gz
│   ├── e2edc28171ed16686c00c433873947a87b61893a.nq.gz
│   ├── e5779122202774264c396726b13c725e476c433f.nq.gz
│   ├── e8f8310d9983f2e30fb4eee08b1e714a6e335e40.nq.gz
│   ├── e946d2a741aab8d5013b4f0fcfb95967395039ad.nq.gz
│   ├── ea0612ba6ffe35bb41a4ae9521a92fa9d13f83ec.nq.gz
│   ├── eab0ea2b1aa01320adbb4a6a218a639fff65a6c5.nq.gz
│   ├── eafde7ba3985637954eaa1eacdcc216547ff6a62.nq.gz
│   ├── eb950fc7f7cb85b5b527334e0c54acf268f55dfd.nq.gz
│   ├── ec2a9bab47ba152a77e6f6f059c4f0d3fea6692e.nq.gz
│   ├── ede731ebc12302c1245f37697f61da02c7ddd652.nq.gz
│   ├── ef41915bebc79dad8af4690b1466a5017de25a90.nq.gz
│   ├── efa910f75f4e6ee0fe989cfb23079dbb71bf3858.nq.gz
│   ├── f0365d6e866a0b1141f86efbb8e601fd94e33f1d.nq.gz
│   ├── f1c88358772d224315f8fb9d8367e071104ecbf7.nq.gz
│   ├── f4e07ffa0366908e879ad04eeb29bdca9392b6c7.nq.gz
│   ├── f5ec55207a57fcb1e823f3d4a22f8c561693de4f.nq.gz
│   ├── f7c5fba174f459d523ac67863d6193800591bf32.nq.gz
│   ├── f93ccd489029e406fab768fb2c2de491b8bb8380.nq.gz
│   ├── f98bebb5f344cc098e7656bdc58ca45acc419efc.nq.gz
│   ├── faa3c21ae8ebff7cfa9fb84468d35b3c602fa6fd.nq.gz
│   ├── fcadb77addd753b4257559b695f25f77642e3664.nq.gz
│   └── fe840054137e2ccda075344f21e728249a60a2fc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1c47821832bdc45a04b61248d99725e9f45690b7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 142 files
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

[rrousselGit/flutter_hooks](https://github.com/rrousselGit/flutter_hooks)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
