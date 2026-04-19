# Repolex Knowledge Graph of webpack/webpack-dev-server

RDF knowledge graph data for [webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server), parsed by [repolex](https://repolex.ai).

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
lexq download webpack/webpack-dev-server
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b550a702bd4246d1724513b70de0bfbe6604672f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b550a702bd4246d1724513b70de0bfbe6604672f.nq.gz
│   └── repolex
│       └── b550a702bd4246d1724513b70de0bfbe6604672f
│           └── chunk-001.nq.gz
└── blob
    ├── 018db0e5b38a6f59f6a8e274e1861374761b6a55.nq.gz
    ├── 02640b1a87509f0da0737c48bcafc242e111644c.nq.gz
    ├── 0303b0653fe1815ae6129cc3d932399648673283.nq.gz
    ├── 0379ec03acfbd6eb343da25bfad7c7ec80487525.nq.gz
    ├── 048032a34a354487ed216b032b6acc24b393b051.nq.gz
    ├── 058353d6689a9391fa67d8e0e145e158b0d4b62f.nq.gz
    ├── 05b314535beafb0519e6b97fed51b21d3e13a3e0.nq.gz
    ├── 07c1446444d89b7ad4f69918f08a5275be0fcb22.nq.gz
    ├── 07d29fb4b5e54eeb4f57e2bee230d2c1600fd62d.nq.gz
    ├── 0912669810efa388e09432588da0859d28da5576.nq.gz
    ├── 09656cd41839077acbebb3b61780f3dfa99d5b25.nq.gz
    ├── 09a8c2b001234a5f32cd992a7cd600367b6b432f.nq.gz
    ├── 0b158bad7a67d3ce05711a3a34d88e74c6273ca1.nq.gz
    ├── 0b550270a2dce883ea0aa014952f30ab6f79d2c9.nq.gz
    ├── 0b7dd7bc23620cb22997330d1d13a660b84caf1b.nq.gz
    ├── 0d6367ba1f3f3374fc85468dc38015df898ed7c5.nq.gz
    ├── 0dc1186bb05055ae8f89d381d9062caf7e568139.nq.gz
    ├── 0dd23f9c7c788de8d46258d4195ff1315aa731cd.nq.gz
    ├── 0de01e9834c5fde534c92cfa7e494b2b67360b7b.nq.gz
    ├── 0eb1ba82a5c5042abc474d40bdd712af129715ac.nq.gz
    ├── 0eef347cf92cc0f02ae028e0c91c7c05c94cbbe7.nq.gz
    ├── 0f719c909992a6d415e0799113d69d430ce11090.nq.gz
    ├── 0fb6a663b92bd75d6899b50c65e8670d7e767b69.nq.gz
    ├── 11659156e261ee0cc584634dde0a5436f8473f8f.nq.gz
    ├── 116ef47ad55434624fbc3b24ab96a3e65220bd70.nq.gz
    ├── 11ba05a2f3d09b4c9a342d46eff471a0e539ebd7.nq.gz
    ├── 12ad24762aff346afd02856c102f2a7bb6e0f22f.nq.gz
    ├── 130fdcd71565a10b7825fa172e8fff059ad43775.nq.gz
    ├── 1355ffb36996e5afd952851770d7a1928cca7d49.nq.gz
    ├── 142b64205da4f6f906530ea02ea727bb06f01bc5.nq.gz
    ├── 15667fe59ea56e9d32e4f9143b640fee14e9a5b8.nq.gz
    ├── 163a24f2652aae2550da8e5b2521bb5f307132d2.nq.gz
    ├── 1698d22ed846c43924d0cbdd8c8b36a25536ab0b.nq.gz
    ├── 18c9b29139c2e8499940abb8f74cbba56ab29ca7.nq.gz
    ├── 197b1478337f072b50b56e4f6438b825b8b0da65.nq.gz
    ├── 1992bb161041f30753ed37209239c6daf8f5420a.nq.gz
    ├── 1ae523febc67bf0066e1de4ebcf09a6f37ce9ed1.nq.gz
    ├── 1bc05cd64b40dad1165da9300048d9781dfd76e2.nq.gz
    ├── 1c3c271708fdac6fb8daced32e2f13f7413aad25.nq.gz
    ├── 1d99bb38ff07c7ebb4e04dc5445ff4d6173cd4d6.nq.gz
    ├── 1e2be08a9d4a1c56f2f500cb66b660539d17eda5.nq.gz
    ├── 1f76cb61724e8de25211bda48f16122cce9cdef1.nq.gz
    ├── 2042f88197a87ac70cd258d820ba56cbcdaf072d.nq.gz
    ├── 20a13bb93d0f3f82d9d1a35c884b1fbc1c0385eb.nq.gz
    ├── 20cb07cf7ae24f08513c6a03a5c3331f7040f1c6.nq.gz
    ├── 21062797012ad30a6744a19729b293d6b68f4152.nq.gz
    ├── 210f775f5cbe34a08e87bf476c9b7bba1bd02f1a.nq.gz
    ├── 215ab84a01d7bf2e8fb1f004acb0d2a775593d6b.nq.gz
    ├── 23bc4e348ae7bedfadc898f9d34456582bc875f4.nq.gz
    ├── 23bce93c456bc588c8bebbbb40bcbbe625fe32d0.nq.gz
    ├── 24147d0ba21555cc9c2cec0aa187cb0002fc72de.nq.gz
    ├── 25f2b95c76f744c81e658bbda99e18a05a73191f.nq.gz
    ├── 261d16e592c007c24c3e670144490c9a4f01ba40.nq.gz
    ├── 2640f84902922b45f3d0f713477feaf6ca4165c4.nq.gz
    ├── 267eb3545e5ad164a1e2cc06c4d731f664a8cfe8.nq.gz
    ├── 269e4cab418f3267378b96af33468e50b09ef7ad.nq.gz
    ├── 29046c9bc39cd81825894d15149fe32902227260.nq.gz
    ├── 2a83e8bbbf9a546a1bd2e9421d7773c5abf29d85.nq.gz
    ├── 2b8d1f2639ff0e944eb882ba8914ca3ea4d34729.nq.gz
    ├── 2cc8280721d1e0bcd9cfb004b4ee458063e441a3.nq.gz
    ├── 2d215c005fc948ff238c3918202ac05067312f93.nq.gz
    ├── 2d40a32b755d85011a24f15cd27b4e6174f01bad.nq.gz
    ├── 2db9dc995b2a38b6098ea7a2edec127b0051076c.nq.gz
    ├── 2ddbc8b93464d52e2873aa2ed93017370e97b7e6.nq.gz
    ├── 2ebcf25c98c62c838d5163a88ae17805940f7265.nq.gz
    ├── 2f64765a90c0991e6bab2b9ae7fb3eed6ef1739a.nq.gz
    ├── 2faa9805d10ede2135abb752e295c9bd8d5564bb.nq.gz
    ├── 2fd15a53ed591c97e04812df1a116f7028b6f6bc.nq.gz
    ├── 2fe136bcf68c1b4ed24096575a2627b9dad58851.nq.gz
    ├── 304c05f38d3cf71d5227edb47a8e0554547e2a1b.nq.gz
    ├── 306717f6a9d2272eb8e8988a6dc854b41df56470.nq.gz
    ├── 311d87c3337e85fe2ac2e222ac2ec821c4ae3369.nq.gz
    ├── 3141da7ce02802e79fd6bbab285176c2ef2781e8.nq.gz
    ├── 3170d8fa62fe5735b5ecc356fd08e7d7a3f2fe8a.nq.gz
    ├── 32638c333817e228c599fd2b39297e82b5d758f8.nq.gz
    ├── 32e1f9dcb3559d31c79f2f7d812f8f8f1b6f31ee.nq.gz
    ├── 32f9a5aaefcde38a58ea200f72c3a7cab36c63f2.nq.gz
    ├── 33350a7f822ad0ba2d974bcc69ce87525dfcd397.nq.gz
    ├── 335ca39648b28226e1846f64d3440aae814a82d7.nq.gz
    ├── 34550ba9a1b16a5ea275b8aa1bac83f7eb54a51a.nq.gz
    ├── 368e5606f4865427b438fbca8664e2c55a052c70.nq.gz
    ├── 36a811a933d154666a732606c30b0e35412cf66b.nq.gz
    ├── 37887d25359c563ae9040168a5647a33f9c71faf.nq.gz
    ├── 37bab961339ae96b58fa7bac8af228c5e10316e7.nq.gz
    ├── 3823fe2e1db1269a562789ef15291b070dd8c961.nq.gz
    ├── 3ab8776a4762e997665a084639b3a0192f0a4484.nq.gz
    ├── 3bfdb588d54bd847fe6bea4e8a35185941166715.nq.gz
    ├── 3c15ca173b938d5a4725c953fe6a6abafc255216.nq.gz
    ├── 3c915dbcb8e7b6839d1022ed67b1416464114a2a.nq.gz
    ├── 3cc4ed1dcbeb965294c789472864d3b24ca02314.nq.gz
    ├── 3da67069e02f5ee37b3f4b757ba801809aaaef3a.nq.gz
    ├── 3dfb585f6d8d584ab322d2ee1dc859ed5ecea0ea.nq.gz
    ├── 3dff1ef2ee5b4ebf0d463b9b977ff7378383bb4b.nq.gz
    ├── 3ef60579b1d3538665443f8bcc058d681052e806.nq.gz
    ├── 3f922d98c0d60edb024445287b8c850e517d9b07.nq.gz
    ├── 419046888f2d0f4d126e76fe2ea55636cd9e21fe.nq.gz
    ├── 41cfbc59280bf28fc89086ba1664b6f50c83941b.nq.gz
    ├── 425ac97c61c5055098bdeab8ffd805bc3b08d2fb.nq.gz
    ├── 42d116ecfe5cef72293a628bb804e6126e60ef81.nq.gz
    ├── 436119cd68387d02b5de7940abed9fd54502f173.nq.gz
    ├── 438cff8ada3e36d146d4b4ffe2777b6130e92d61.nq.gz
    ├── 43c47a418379ab0f5b82f6098bddc40070e9fea0.nq.gz
    ├── 4436292e8f440c0e14cf2086a5efcb7b787ee52b.nq.gz
    ├── 45946eaa25a5eb3baa261d1bf2a6ac8783defbc0.nq.gz
    ├── 45e917b284c8196483dbfc8c8cc9205907b3a4ca.nq.gz
    ├── 4631083de98b56da1afb079c98895c9af534a225.nq.gz
    ├── 4645e131de9b00367dd6ba1aca772c5ca31a1a81.nq.gz
    ├── 46d34de85f87f51941a734296828f9d8b149b502.nq.gz
    ├── 4740693e7976dd8d10b0ba4bc813ffc238bc42fb.nq.gz
    ├── 47dfba4c6251ddd387eb4e4afc1788aae4242d27.nq.gz
    ├── 4a7bc2be12ecf7031b1b3ad50740263f98bf40c8.nq.gz
    ├── 4add785dafe43f11202c6b7286b47c3b62401dd2.nq.gz
    ├── 4bb0db9e77b8c8c198db2866b079e900b2bc608f.nq.gz
    ├── 4bd07e7495dd446e79689091dbe600def13f172e.nq.gz
    ├── 4c29be511c91d3907ed190583570d409d416c502.nq.gz
    ├── 4c2e4b7f5e05276c906f4c5911af446947b6331d.nq.gz
    ├── 4c50ae6e5a51ee13084f702afec0ae8350b37160.nq.gz
    ├── 4d3db1e3f2390494a85759a3410b7a1a2f7870e5.nq.gz
    ├── 4d88c538a70a535e1187724242b2b7f0c98434e8.nq.gz
    ├── 4d9ffc4eaa2fc929910a9053bd03040567efc14e.nq.gz
    ├── 50e4530a237c88c4ca8fa7997eafc398231c5303.nq.gz
    ├── 51cf4a396b6fb7f18eaadb5ef205267bd61d5bcd.nq.gz
    ├── 52ac3be3ee2fce7a3d05e0d6d94237acf7e9613b.nq.gz
    ├── 53c0fb64a55fbe39eaf063d42d17a42f013841ea.nq.gz
    ├── 53e2b198e88466868e449503fe807cab1e51ab54.nq.gz
    ├── 5468355bd7a4989f6d70467889c554786defa99d.nq.gz
    ├── 548314d148f564668a22080223c46c310b425196.nq.gz
    ├── 54b9cbe19977a2b03801e5c71be13f4c7563689a.nq.gz
    ├── 54e2b462646257c0921231b545f2e5bbc4ae7e81.nq.gz
    ├── 550a73c229ae5407447a648982fbb8dd2fdcc19d.nq.gz
    ├── 555d475789b915ab7c3c1a91650bd3fcad796584.nq.gz
    ├── 564acff99e8ab9c4f78a8bf13555d96f978b56d2.nq.gz
    ├── 582e5318732c7c3aefc3682ea67536e47652dfcc.nq.gz
    ├── 5863c8e14acc186f81beb2853cad4efc107b96e0.nq.gz
    ├── 5940e9197cd3436f48b0d99d5f20e0c1be98bfb8.nq.gz
    ├── 59543c94135af4027582028eb1964f0abe4e9590.nq.gz
    ├── 5b4cc76e3472b62b64223d5a38687cd87986da09.nq.gz
    ├── 5b95533e568168ad44450ab29ca64bfc870856e9.nq.gz
    ├── 5e0aaeb46d04a086588805320539ae8f76cfc499.nq.gz
    ├── 5e59b2d444db7ba944f19d4542b5a824deb601f3.nq.gz
    ├── 5ece7ef13780b40f8906a8d1e37753e38454dae3.nq.gz
    ├── 5f2bc90aab6323ff07a66a770f10fb9c527b183b.nq.gz
    ├── 5f687b2927c39a3a25ab64c92483097a9218a2ac.nq.gz
    ├── 600607403040f7569c49f9f1b3603c8a99a6bf59.nq.gz
    ├── 60527ef0299fab4e5f327bd2191229991e327c15.nq.gz
    ├── 61fd73364e806b58bef974972f1eca4531da6dd7.nq.gz
    ├── 62011435d3669b2d41b9969dc34e3fc8d39a5fe1.nq.gz
    ├── 624dc8a648f0170b99bcb7578110853a3bf9b0eb.nq.gz
    ├── 6366f481c23684fa51800918ba7693966cbe14b5.nq.gz
    ├── 64284aa09e59817d4812adcff2197a48df483c53.nq.gz
    ├── 6439456ff2cc964f4bcdf009b1b1e47ad57c50eb.nq.gz
    ├── 656b58579a0f7e52badf25567b26da9ea299080c.nq.gz
    ├── 65cd2f21a94044a72f3cb08562b64d543344ba3f.nq.gz
    ├── 66bebdb43955fb56c4b837a014baa9540b6d2eb2.nq.gz
    ├── 66ccd5ec67903364cb928c5876479a7cb6f021f0.nq.gz
    ├── 677eb97671c1bab6782becd03f00ee16fdb85a98.nq.gz
    ├── 687d41d403d5d8d5f8822ad5962e685a6ed96d69.nq.gz
    ├── 68ad7bddf6e6812714972f4af9e7d7dd31ac5166.nq.gz
    ├── 69297e2b2bee04b05a5b5b9ffdc22dd5cd3a12d5.nq.gz
    ├── 69c627cdb0f4f5b8591131ab22f910c59ea7dd55.nq.gz
    ├── 6a574ef5c5ccddddfa7007d75c07aec1ae52b14a.nq.gz
    ├── 6aa74ce368ece2e4b4fa0fefe0aaf4570e591872.nq.gz
    ├── 6b525d885a020f29373b14e9b7dcdb3fa61c98c3.nq.gz
    ├── 6b6380e474c8bd096fb9033b4c3fba10711f8bf6.nq.gz
    ├── 6b9de75e769086231e86fa5c576aa1f094029879.nq.gz
    ├── 6bd40d9f70e3ecf98092799cc407aefbe815bc47.nq.gz
    ├── 6beb3163b853376bad375e266b3fd9ebf50d6b73.nq.gz
    ├── 6c600f15f363c40319e1579b8f9311afce1a424d.nq.gz
    ├── 6c880a4e7da66a86b2ebe46afbc642d4c9ccc957.nq.gz
    ├── 6d023305dbb36d3096005b7d6ae0322dbe7b13ef.nq.gz
    ├── 6db58361bb24dcf0db1e0150db598f0ec98dfb9a.nq.gz
    ├── 6df62b5fe12a943b2756fbed18508196f487601d.nq.gz
    ├── 6e3a7f753a73ca2f43e7725182f7f9e0a3596093.nq.gz
    ├── 6f3de30cb6a1046bcb0ef8c543ad64cb62064854.nq.gz
    ├── 6fc38f42e14d198974ec22f730850dc991645ffc.nq.gz
    ├── 70f3017b12946545cfc455c7296bfd947e134cdb.nq.gz
    ├── 71e82d230929400909b11af8ee8c763cf2c694d2.nq.gz
    ├── 7265ad5b12b3fa0a437c27ff24298d38fff631d0.nq.gz
    ├── 729e8274904c0f21279ad4aaaa9040d20193676c.nq.gz
    ├── 735b0e652f412fceafab558389e35ca6204b39c7.nq.gz
    ├── 73879d5323f9ae992cc437878135bac8da44b967.nq.gz
    ├── 739d9bd6383e8eae5baec1b2cefa8af2baa7f269.nq.gz
    ├── 74945cdeb66e9b7e7e5cec95f0cb6aff15476749.nq.gz
    ├── 74e736ae9aa8d8610aa50339424e379bb7ba9ca0.nq.gz
    ├── 74f65f722b4870710ce6b53264aea16cd6fcbdec.nq.gz
    ├── 74f9bc577fdeeac0b558f249132e055b081933f2.nq.gz
    ├── 7562d542064d72ef75ac5b02bbc5cbf9d4089125.nq.gz
    ├── 763a4be3535525522dc0897239a8b57a881d0c86.nq.gz
    ├── 767fb5b9801d73091d507a3e92c851ffef469eea.nq.gz
    ├── 76ff325ffabe4ee54d1520113151975e87306274.nq.gz
    ├── 77d1df223b7060ddf2c411c3d5f5d548f1a3b122.nq.gz
    ├── 77f80b74a73979500f9591184099a6584595c5fb.nq.gz
    ├── 789e304fbea35d211249378fc79ee4a504c3c9d3.nq.gz
    ├── 78d6bc2345e6ba270599dcb888e8655baff6fd24.nq.gz
    ├── 792be36f9c52f7f3ad6601141b3e6e474842ddcb.nq.gz
    ├── 79ed1603febafcc43a08c5857ae1d0cc98d5fdf2.nq.gz
    └── 7adb34b1e9b512c7b84c954c20612186a6a4182a.nq.gz

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

[webpack/webpack-dev-server](https://github.com/webpack/webpack-dev-server)

---
*Parsed on 2026-04-19 by [repolex](https://repolex.ai)*
