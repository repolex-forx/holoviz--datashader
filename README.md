# Repolex Knowledge Graph of holoviz/datashader

RDF knowledge graph data for [holoviz/datashader](https://github.com/holoviz/datashader), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/datashader
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 385fb0b976356459d59deac8c1b23d14eee15dc2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 385fb0b976356459d59deac8c1b23d14eee15dc2
│           └── chunk-001.nq.gz
└── blob
    ├── 0089fb11868b3c48af0afb38abb3c39ccb1ae773.nq.gz
    ├── 015fe3654e4eac4b9cdff3ef17bf7e8affcb3e51.nq.gz
    ├── 0266078ebedff135f474cd931291ed33abd7594b.nq.gz
    ├── 031a8dd95de81c54c40c8016a04dfc0cb94b4c66.nq.gz
    ├── 04ee644aaad7660bdba10552faddbc4705d2cdaf.nq.gz
    ├── 067be40a58134425c1ca752cd9d35b993f399763.nq.gz
    ├── 070931df6ad70885b24adf862b2db859ac38e172.nq.gz
    ├── 07ce31e16e608c6b94921751caa0e974cecaf45a.nq.gz
    ├── 0a767168c77e849243d6c2999dd6fb806575dbf1.nq.gz
    ├── 0a83d30db01c3bc4b03756ca75224d6c942cd57d.nq.gz
    ├── 0b8149a0f312ca9d6199e72cb9d026a24cdf732e.nq.gz
    ├── 0c0bb01d18e6863c7ec3d973956dda2449dae2bd.nq.gz
    ├── 0cdbf92c0fb49177ae80577d938151126bfc598d.nq.gz
    ├── 0d22d1364bb52a6d99a77957481c8f5fcb97ccdf.nq.gz
    ├── 0fdc5faa6ccaa44aece23067854da7f054ada63a.nq.gz
    ├── 111a177afc1d57badb5bcfb81a844d64ffc937e4.nq.gz
    ├── 11bbca768a6291b999262e17c30997ce007865dc.nq.gz
    ├── 13897e62da926412775699ec1d1c73b74ccd941b.nq.gz
    ├── 162f95ab626e82d3adaef1eb488a3028d785a0d6.nq.gz
    ├── 176fb36e0554d9b29e794af76ae7324c5772aab2.nq.gz
    ├── 183e365e217b105d6d3cedd4763d3b4af5c6826f.nq.gz
    ├── 1a24ae6eea55545a54ad9268baa376fe75dc0e55.nq.gz
    ├── 1ac1f6044a89a367df333f5b2ed39156d67138f7.nq.gz
    ├── 1afc095d5d10104cbfa8b1c98c99dd4cc1d9d8d9.nq.gz
    ├── 1b37880e8867ecf5e12907e53e21c2e628b9d793.nq.gz
    ├── 1b8ae724f966baea5e0ce429e8cdedd67658205e.nq.gz
    ├── 1c055fbdf765ab6385f4e25b66e5fda29cb93e71.nq.gz
    ├── 1c84e950a20a7a58b1fb4b2bb57d0f7946608dd2.nq.gz
    ├── 1d1a9a3bc59b643fc8aea66fe9b5c725e0cf7a70.nq.gz
    ├── 1d8a3ec3a35fc1c8da0f6612c9ec80c916ec4ae9.nq.gz
    ├── 1e3af72d077015cc2e4b36a229c620b45d3cff66.nq.gz
    ├── 203e210893194914690180f5a5198b405c2d56de.nq.gz
    ├── 20c392c181508906e13dd7e5834781e43440927c.nq.gz
    ├── 20f85161205a37863af48d49380b4f3c69d18ba2.nq.gz
    ├── 23b085c0340a6311062c9f4f6c27f155a969a0b3.nq.gz
    ├── 23c73d3607b71440132ec5e7aac1f729640739a6.nq.gz
    ├── 25394f69a3ee8cbd4e57b3b4a0417d81df40ee66.nq.gz
    ├── 26308830a3766bd1d8cbde569ad4f2e7bae18cfc.nq.gz
    ├── 2662b1ba51f9a52361ae2257ce5e725785c65e87.nq.gz
    ├── 270378955c5a627453cf83124af930fbc78e8278.nq.gz
    ├── 286ac76b7e94f58db484851685ab1bc35c661e56.nq.gz
    ├── 28ffddbdd89e0ee42ee64f7abcc6b8079e1131bc.nq.gz
    ├── 2908fd78f575d58ed2f89e59faed3d344dbc6ccb.nq.gz
    ├── 2a2249dc1da6135ec1de9d30e38275042e52acf2.nq.gz
    ├── 2a7607c6438bfc45cd9d2f854da97ae25dd27f94.nq.gz
    ├── 2b571f699b4340622b46cf57d2dc9942c172975a.nq.gz
    ├── 2d0cc01bc55c061827b889847a6ce90bc81d5517.nq.gz
    ├── 2d8bd545367ab70f6f1afa7eff0235e60c59869c.nq.gz
    ├── 2f608e2a6c467252e09ed076cb575ab481e3fd5a.nq.gz
    ├── 2f7236e0d24600afa8f037b671d6d96da2d21dcf.nq.gz
    ├── 304e00b6ea8e12e3ebe4202c7ed09e27c31db659.nq.gz
    ├── 3128e18b5c28c525aabf29dd681648d71a6002a7.nq.gz
    ├── 32a6282ac8269d217163a423a7e3ae082bce38e5.nq.gz
    ├── 32cfdd93712011b46c0730dbe4ab4756cb992f7f.nq.gz
    ├── 350a3d53dff5c077bbce0b21eb5b2591869752af.nq.gz
    ├── 361b0e140d47544702870ba47afb3cdadb12fe08.nq.gz
    ├── 36df85d6847f842374e98ccb6adfba672f254393.nq.gz
    ├── 382c2a6fa4f997383b75e60cb75fabf719c1755e.nq.gz
    ├── 39136bd05e7d1c51b4fbe9e58e8fe3710a3a96cb.nq.gz
    ├── 393891380ed4d69d801c8724421355a26cef12fa.nq.gz
    ├── 39b62393998cca77f110f92c42acac4e9534b7c0.nq.gz
    ├── 3addc12e702926649c6c2008f3b82dd2c6ce2074.nq.gz
    ├── 3c4e8b15c665694cb6bfd79bbeb721d750ed14a6.nq.gz
    ├── 3d75eca6fa3477fc6d681267efb1e6e2f08a5bec.nq.gz
    ├── 3dfd2b9c421414c96d5935e29f8b35bacf8bac3f.nq.gz
    ├── 3f33a944b0740c474d7cf21acd94f774e7c50225.nq.gz
    ├── 3facd5d82dfc33e345afc9eac9c46db9fe52d7d7.nq.gz
    ├── 42cd2769ef2e8c94ec59f3fc1753080d2743ce0c.nq.gz
    ├── 440888440c47d08382f4e6628d7079dac0f173b3.nq.gz
    ├── 45477e3c86cca51d4206d41caa33913b71e9f0d0.nq.gz
    ├── 45596c5944dd299e96b30f06f99349e6960970a0.nq.gz
    ├── 4612932417301f7716a596a221160c9425076e3e.nq.gz
    ├── 4930d02fcc9a6c9d62b9aa1bcd62c118b80a1177.nq.gz
    ├── 49bb0e589f7b153dfe72b8b54f9f17394f1e7c18.nq.gz
    ├── 4b38eaf9205aa517b64dcb43890cf8f0816142fc.nq.gz
    ├── 4b8e6dc859710f0f39c61c5c13bf04b5cd4e645f.nq.gz
    ├── 4c90edcd0d490aea5392ae28c5576568a044851d.nq.gz
    ├── 4d102d0cb6b9ad9a1d9695c0b76448837b83a364.nq.gz
    ├── 4dd0b88b4651f891b0c508978a722b0d9c11e617.nq.gz
    ├── 4ec800e88a7affa5c5f3696aca51dd2370949932.nq.gz
    ├── 4ecb21971ebc7a8d30c1f756e441e22ebe187306.nq.gz
    ├── 5364f6907051ab577509cadf5f00392ba516a7ac.nq.gz
    ├── 56eb434e9ac89fbf0070c8b2cb13080147d8e003.nq.gz
    ├── 5703b3746fc7f0bc1f768a2079e19f8f94f0c403.nq.gz
    ├── 5760a160b5022dd44292adb3dbb6e55f309fe2c1.nq.gz
    ├── 583c04993895c7f148cd8c272ac6ecbc8dce5db2.nq.gz
    ├── 58d130b7cc435b0e29a7ee187f87c2d68bad900c.nq.gz
    ├── 592c905095f761ddd2016843aebefc09fce40589.nq.gz
    ├── 5a6df4e428de2934aa7050783b0f6feae22b858c.nq.gz
    ├── 5b498b69695928646c8983a9c96b43d8ce6ee313.nq.gz
    ├── 5c9a52b950460f7dc5e7cea9a8b0195e5698951f.nq.gz
    ├── 5ffdcdcc1599eb9f5a64886c491db1704babc5c0.nq.gz
    ├── 609b66770579d35ec0b77eaa34f841569dfe01f0.nq.gz
    ├── 6158c8cbe3cdb8c4d5b674fbe4cce94a5e0262d5.nq.gz
    ├── 638888c9dce56a0197a30635f9af8f077d6af0ee.nq.gz
    ├── 63b8cc01309eb8b66833089c27919d2691e9f562.nq.gz
    ├── 6427520340bbbfa8ace598de6e06ee02404f79f8.nq.gz
    ├── 6532f6cde62ef1646ce45a2791075dc7012fb70b.nq.gz
    ├── 667c38e136c4e898c2e6424a9d57f9fc1abb44c1.nq.gz
    ├── 66ed847510abdbca656354db4bfc23eb73f34e33.nq.gz
    ├── 68515888bc6df59abd0e7184e57727f8928687a4.nq.gz
    ├── 6898e4b508464f144e021077802bbeb7ba7f0945.nq.gz
    ├── 6b15b51d296a56cdd438eebff1cb999ae31d6d27.nq.gz
    ├── 6b332a7062f5bbcc187a754e4f357ce2d71a6646.nq.gz
    ├── 6be4c5b3a0b0c5be54a077f048d45427dea5b6f6.nq.gz
    ├── 6c6ceff708ee600aa427b51e11ea730121de2296.nq.gz
    ├── 6da0b6126971542cae83643d2211712869761bf9.nq.gz
    ├── 6daedfc8d29597ad76de0651a1ce28c28209e3ce.nq.gz
    ├── 6ea11cd0ad7574a96bc3c0676b0210718107813b.nq.gz
    ├── 70e5c2c3a26abf00066c3caef552cfa7459a2de4.nq.gz
    ├── 7372923c9aa376daeabeaeda0aeaef16650efe15.nq.gz
    ├── 73ba05b26b54ecb3ba974de19d13850458813192.nq.gz
    ├── 74c375bd10f11284a8038a2ce41a36a951516b70.nq.gz
    ├── 74f4177a31cd3f1b250d0efc196cf3b652de8f50.nq.gz
    ├── 775e31629eb93fcf604e1ce112ffbaeaf1b59e3c.nq.gz
    ├── 778113a4d9aec391525cc72316b2cf8bf36c8b9c.nq.gz
    ├── 7ac4af6ddbe57a272ba080faa700b35a63bdd62d.nq.gz
    ├── 7c14af468559e219c1c54f081bfd8c42acfc5483.nq.gz
    ├── 7ca86ac72d1e709adf6f8dfc47d9256944bb3ff9.nq.gz
    ├── 7e8f4f87e2f0b716a6716b419ea1f06581fa011b.nq.gz
    ├── 7f0d115cc5268b5f51f1348ae706d1105d1115d3.nq.gz
    ├── 7fe0b75f0eb8357189456034b701d4fa24556ef0.nq.gz
    ├── 8032160533c8acbbacd225714d8d64914b132679.nq.gz
    ├── 8135d3f846f5e174fdfc7d6127a2e04e27ae64da.nq.gz
    ├── 81998e949464659460d6b9c5aef048b316eb6b17.nq.gz
    ├── 81a2deb300e252d6af7db008d803f001b49c8d59.nq.gz
    ├── 81d4b7196184f31c86efcdaff5834b725d71446b.nq.gz
    ├── 840be2e9289050953e1c586f4367d047fc33bcc2.nq.gz
    ├── 85e256c45c6a3411e60e859342c04cf113ee0032.nq.gz
    ├── 870600b65bbc49c2fcc38040c3dabc61ac882158.nq.gz
    ├── 88a009c62b4813a9af46dbc96a1c1d6e8a3942b3.nq.gz
    ├── 8a294a5d72fecdef9a6420a7d47f72db8333972c.nq.gz
    ├── 8b5d7efa690e840022c85e43d24974583a038ea7.nq.gz
    ├── 8b9504419544a4ace6d16ba77e44786505845516.nq.gz
    ├── 8dd5100511ae9132ea76d7d173e802c9b8d2579a.nq.gz
    ├── 8debd2d20757303973d1242b8f2aee75be733b55.nq.gz
    ├── 8f233248bc2a6b97913858a0abe7e0a3ff5f3eed.nq.gz
    ├── 8f6ed05e047035f429b502b6e47f23e61ae05e0f.nq.gz
    ├── 9036c34a1f9a7ca4e47c36d07247d4a1e1fd0291.nq.gz
    ├── 9059bae0a5bdb8235eaf41cf0a2a35f63f69668c.nq.gz
    ├── 917d23027d3e0f7a79b0e410214fe96cce776aec.nq.gz
    ├── 92564d2052b591e8a69727db4457b648a72834a0.nq.gz
    ├── 93a745a2c6fcb359f91361f43430e4b60526552e.nq.gz
    ├── 93ec7f033563a6d9697e35e068727834f410d354.nq.gz
    ├── 94d04a3649429fc7deed50e921f2246a8532f4ab.nq.gz
    ├── 94d30a47af805097d9d67a0431851b493cb065ee.nq.gz
    ├── 958cdaa7a2ca1e78ccf5f1ff05c492503f1b84d6.nq.gz
    ├── 95d825e4d116dce327409063d89246ee5e30db55.nq.gz
    ├── 980835159aa5e869837c7280f67f1b43cef3976b.nq.gz
    ├── 980f1ebc74eb591ed6d668bddc9b889b861ee67c.nq.gz
    ├── 9886d2f0e4d2985d28da470933feb2691693f5ee.nq.gz
    ├── 9d3aba3c0b052f788e7951f3bfb058f9fc17bf8f.nq.gz
    ├── 9d619ee2cc20e2a1410047420e22ddeacb543af8.nq.gz
    ├── 9e527477dc669b6973ae1f915ff1a49b5423e726.nq.gz
    ├── 9f5562e934abaf7169048e39b61f0c5357d4381b.nq.gz
    ├── a08f55af2e2340bc1c07588e47fc1bd01d540a1e.nq.gz
    ├── a1141d55c60b51e6b34c1adfc48f3d812633ea41.nq.gz
    ├── a1c9b3218603244b17d408d4586fdd048499cd1b.nq.gz
    ├── a1cbe5d0735c04138a2f5418fde246200ff048a5.nq.gz
    ├── a3b901f632e395c3dc39ac171bc88c754874b305.nq.gz
    ├── a60867246ce63109e6cae78a0c50f1aca01c98eb.nq.gz
    ├── a77fb3aa80a9a10e4a081f87a38cb43b488806bb.nq.gz
    ├── a8568aa0939400bc79b2b69bba52cc09cb7f2b7e.nq.gz
    ├── a98677e9474ddb0d27ad0f5a7d0ff372f8eb25dd.nq.gz
    ├── add6dd7a3c49c373d50cd41b5a923808fed09d93.nq.gz
    ├── ae7cc3aeba885e92ca7450d3c8e805330e725c00.nq.gz
    ├── b0732923d01f4606230c0776851a21da8c4b4b15.nq.gz
    ├── b0ec985bad489b2e3eabfe3a9df3e8637ebf75e5.nq.gz
    ├── b1806c7c882755772863af39853c3d914d69f439.nq.gz
    ├── b2656aa2d0a6b4170e720e7e278400ed0416982e.nq.gz
    ├── b29ac5d26ab8b7dd7fa8fc1085393f14156a9ed0.nq.gz
    ├── b507237cbadce5e63f67c2f14a10049b29381431.nq.gz
    ├── b6f2747498b426a42975a1ec5757882fb556bc84.nq.gz
    ├── b6f832d3541f56382d2149aa0b57b88c6e895a22.nq.gz
    ├── b8c688a007387127e427e9a2f583009188131364.nq.gz
    ├── b8faa8d0d228cb3e0bb07b8bf1647968fbf7d385.nq.gz
    ├── baa97f71a7b3332decf47a7e4509799bacaf2b4b.nq.gz
    ├── bacc45d7e34dea4a9f5150cf0cdfe85d69ff7779.nq.gz
    ├── bb146f502596c5974390e3fc93e952a2183cb3cf.nq.gz
    ├── bbf1ad790689ceeb649d6d4f0f8dfa7f30a3acfe.nq.gz
    ├── bde76107a29110b1d4bfd4dffba16f446868a63d.nq.gz
    ├── bf2ab6b879477cbc25a028e5eda77cfc5bccfa55.nq.gz
    ├── bf53e06771f7f9fdb4e259661b4c3e116f4efde6.nq.gz
    ├── bfb23d2d9d40fe33a16f65e064561e13a4b42f03.nq.gz
    ├── c0d3fd53c278e27a6c8efe5ca64f066104012b5f.nq.gz
    ├── c1130e7072c1a78fb4edb849ec0dc21a24cebdd2.nq.gz
    ├── c1d8d47aa86abfb3228fb53debf9381647486e6a.nq.gz
    ├── c1e5f7d6371128d0e10bcfc246c71055d1daf234.nq.gz
    ├── c67f55f7afea8508d973215c9d80aeb19bd96c31.nq.gz
    ├── c6dc3baed71f1b62efee2012048fe0300d42bc34.nq.gz
    ├── c8f572e0fc3562c3f92232efd120aea55983ad49.nq.gz
    ├── cae0371ba789aea56759639ec1163159a7f9c96a.nq.gz
    ├── cae4c144acdc9fde9bebe38279bcb6082588ad28.nq.gz
    ├── cb17da6c5935fc725c2e33696d45caac8263d658.nq.gz
    ├── cb2620cfefbc66050333b0f4cc72ae5894be8c22.nq.gz
    ├── cb7a8f249e5341876f9670237b93158fed85ccd6.nq.gz
    ├── cc1921f24526f581335580337949d957f3a3d16c.nq.gz
    └── ccea8c1319f6415c910be7cd14f60c296d496a4a.nq.gz

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

[holoviz/datashader](https://github.com/holoviz/datashader)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
