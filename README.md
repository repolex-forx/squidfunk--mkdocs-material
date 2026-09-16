# Repolex Knowledge Graph of squidfunk/mkdocs-material

RDF knowledge graph data for [squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material), parsed by [repolex](https://repolex.ai).

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
lexq download squidfunk/mkdocs-material
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9580c28d2a8d8e7d088a203da4f98d2e31624c48
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9580c28d2a8d8e7d088a203da4f98d2e31624c48.nq.gz
│   └── repolex
│       └── 9580c28d2a8d8e7d088a203da4f98d2e31624c48
│           └── chunk-001.nq.gz
└── blob
    ├── 00028cd74c0b3e1e3aa483187410c0f3006becc8.nq.gz
    ├── 0006c63d7316027a17e6e0f240511410aad4fef1.nq.gz
    ├── 0008fc05856a7fffa987d63b79f465b20882cc63.nq.gz
    ├── 000fe4df2095d219c19a968a7680c29419becab3.nq.gz
    ├── 0010c5e5f346db75d4921a23f5685c4f1c57a5ba.nq.gz
    ├── 0011176adaaf7bb412e4ca80879245265324f83d.nq.gz
    ├── 001b251bb915ef404a5f0f10015492985b879975.nq.gz
    ├── 001b332d47257477c8b462439e9a85cf357a3344.nq.gz
    ├── 001e7b040e208751b4c9dffc76dcf29b5ebac323.nq.gz
    ├── 0022fbdb056c19e678bc34eb2d8cb8b093577a2c.nq.gz
    ├── 0024a6d10e311161accbdaee232d81e097c9c485.nq.gz
    ├── 0027ba76065dd6dc910c1a81b9269e3e19bbce87.nq.gz
    ├── 00283f94e9e3549277251d764325fcd2853a5c02.nq.gz
    ├── 002ccb2380097b6ac7a919e82427bf8372e70075.nq.gz
    ├── 0030de5f6801ed39bef04522b8ec184a4bb8553b.nq.gz
    ├── 003d297cc506b5a8019100b1e2d76353e0a020f1.nq.gz
    ├── 00419de3d3ee2546a8499742d898cb442532231f.nq.gz
    ├── 004488d8b00fbdee1e66f719d0a53ae0cad4fd19.nq.gz
    ├── 0044cc32b485d35d1efda8252e916d5a1fea49a7.nq.gz
    ├── 004b264cad7d0f334878d1c6f74d92f3682ad9aa.nq.gz
    ├── 004b2f331bde1f23379f2f5da435d14e02b9f806.nq.gz
    ├── 004bd325050a98fe9dcfc6ecb2a124c2c2648cab.nq.gz
    ├── 0050ad5d6da83c735e0f04033cb596fad60c5908.nq.gz
    ├── 0051209552c72054264cf3d768a9d3f2bd15a7bf.nq.gz
    ├── 00541082da106e0410cbe87f18b718eded6057ef.nq.gz
    ├── 005c8ecfe0cd312ff414c00f4d7309e655deebf6.nq.gz
    ├── 005ce57d3fabbc04414f07115af3d72fe2bebbeb.nq.gz
    ├── 00600b621f7eba58196784f01999563f508f76f2.nq.gz
    ├── 006688892042614ed936ba2be7a0ba87cc7da81f.nq.gz
    ├── 0066cb75ff67235abf28b2bf0d61e9e9eec9e1b8.nq.gz
    ├── 0067785c508aca51b976356df07aa53c47b211e9.nq.gz
    ├── 006921c82bae88de94be4d7ecbc57488283437c0.nq.gz
    ├── 006b93c793c3c336d5eb0d98afbb19e6862f79c4.nq.gz
    ├── 0071ad1f3462fa929fc8fe44221491607637c30f.nq.gz
    ├── 00751602c9cfd601f656457113b1cffb31048427.nq.gz
    ├── 00763166879c603bb74535e37564609aa3de3779.nq.gz
    ├── 0076ab496d1ad42e9789f3f5716e1a6828de24b3.nq.gz
    ├── 0079fd2d286cf5b0562b2d8c569078d527930045.nq.gz
    ├── 007af26dca2e0d9790becb362c616854dc74021c.nq.gz
    ├── 007be74e8566aec08ffe64007d0a5be6ed2400f8.nq.gz
    ├── 008258724fb3822606d06596f8086d22f87447f8.nq.gz
    ├── 008b5fdea67a1cdd8a31486a449f2ca5c26cea1f.nq.gz
    ├── 008e718ff7c1f8c4fceda5219ef7663b3cd36a2e.nq.gz
    ├── 008ed85c7b7395e05c46c7d1add17125f86272e1.nq.gz
    ├── 009191bd7c568597adc996dda24de571bbcfe82f.nq.gz
    ├── 009a5a51c85c0fdd80a9fbbc4453e28990f1f9aa.nq.gz
    ├── 009b9b3a0f2779f20711b864b16b9cd5e6b32f22.nq.gz
    ├── 00a37476631d32ee8896de693d6ac5a4bba04854.nq.gz
    ├── 00b58b9352fe90c72a21bc19807aa8f740c04bc1.nq.gz
    ├── 00be25496ecc9092311d2e8e5294d0554194c77e.nq.gz
    ├── 00c1b88edbf294b34cbafc33e0846040adea5482.nq.gz
    ├── 00c23bc2b076d18eeed67331e1bc5a09968eae23.nq.gz
    ├── 00c3dd9cef71fc22e1b7172e46bb59b54c5125c1.nq.gz
    ├── 00c64ef957e4c50c35afc4364cf4fd9b46891d4d.nq.gz
    ├── 00cd95c79f66785fe0efe9b17475d63e59a7be21.nq.gz
    ├── 00cdbd705d00c44b2e6901a1fc1b8ca05d818e5c.nq.gz
    ├── 00ce38c9823b724fead77f5a81fc2b57e4637e68.nq.gz
    ├── 00d0a24ffff343381bd915f17851f315efdf9a49.nq.gz
    ├── 00d47b7484e078f479c02afea9c048d75127ec94.nq.gz
    ├── 00debe8a6fd27f1225de255280b0035fead71b91.nq.gz
    ├── 00e78741fdacb25463376371a8cc67211f187918.nq.gz
    ├── 00ebc4956012515246607fe585845d3cf42ffea4.nq.gz
    ├── 00ec9f5091b5764bc738ba156f4f1b813224efa8.nq.gz
    ├── 00f3eb6535cdda68d40274f24bd113dfb5c7e6e5.nq.gz
    ├── 00f4058fce09100ac4d6d63e8ed8cc16c8b14ba0.nq.gz
    ├── 00f5297218be16af088f7eaa79effb4dbfc9c514.nq.gz
    ├── 00f61e3c9edf365d3cbcb64f04269e4fdbaeef82.nq.gz
    ├── 010379e3fa5f041378e2353be621a844183621db.nq.gz
    ├── 0105d0ab62e7d13af2e572585c1e8f4fae374fd3.nq.gz
    ├── 01101368122a674b0c200e5c719f57972f9297d6.nq.gz
    ├── 0110334009afaa9f8a9ec9986466f9b4ff42ae9d.nq.gz
    ├── 01133643a07218f0e869eed7105032da8af02ba0.nq.gz
    ├── 01196914d25ae9d39430ce22f0533de03ade21a5.nq.gz
    ├── 0119f586be29e14dce3ffedab97ddc3c30b7a9f8.nq.gz
    ├── 011da448041cafae5b729d30efab1c4aaff4afea.nq.gz
    ├── 01232a4c365f1a7a87420afeb9505812025288d8.nq.gz
    ├── 012442053c4931673a36e138fc4033eeb785a2b0.nq.gz
    ├── 0125fcfc5e0c7a55d7666928df7b111a203871c0.nq.gz
    ├── 012cc51f001cca4a7a300c1ed6337a1debcc6408.nq.gz
    ├── 0130020019e4509a9445d0fc604cfdf65d8224c6.nq.gz
    ├── 013aa54a2a8ea3e512eff37e34911ab2c3a30ca1.nq.gz
    ├── 013c81b5d0d7cefa281e50571796dbe14b51e613.nq.gz
    ├── 014247e9320c5f510db9d7f609906c34d6116289.nq.gz
    ├── 0145137b44ff07a058b3229d8c79699be5bb28fd.nq.gz
    ├── 014821f3ee15ffb0baa7edf343acee2662612f4e.nq.gz
    ├── 014934f7516c3db307b545feaf845d9def85b814.nq.gz
    ├── 01498c3699a45497c97a2aaeea115417aca2eb17.nq.gz
    ├── 0150018978e37496dd5cbbe1fc39f8c12915c8b8.nq.gz
    ├── 0154b6b1b93b9376c2197239ff3efa61c739e704.nq.gz
    ├── 0158c8ebe20fb159a329b8ab360801eb819ec078.nq.gz
    ├── 015bf288d9afdfb34915086889266c372939b9e5.nq.gz
    ├── 015e12060d60d9af499e85c6eeaf50484044c868.nq.gz
    ├── 0167f09b107d40bffa53b7416f0f96092725dc50.nq.gz
    ├── 016b2f0b5be5427ed0520056eb98bb96f4f43873.nq.gz
    ├── 0178200896be9656d3f74a5a6f6c99de29a5a888.nq.gz
    ├── 01798e59c29207d38911996366be4af974202d76.nq.gz
    ├── 018504f647de329ca85d3d4d22da3b671de5c3a9.nq.gz
    ├── 01870d49c96ac9a59a3df7485e833ad6ba878d9a.nq.gz
    ├── 0189ed9e39d787b740754df551e8c3a4f67f3b73.nq.gz
    ├── 018d273ed5a85d6f38b62983b8f2e91f72088021.nq.gz
    ├── 0190a5615aa1f3fa43fb52dc6ea51793ae428c46.nq.gz
    ├── 019128c1613a3d45cbf58a0c662c7d3deb5e7ed7.nq.gz
    ├── 01930a89361b75190b28fa33002c7cbafacf2640.nq.gz
    ├── 01940576fbf1a06b138445b332a19e359a16a27b.nq.gz
    ├── 019df4407cf1e5d6cf68841f4de39030f6042345.nq.gz
    ├── 01b18d0ef2880cbc1d09e268743dbaee7d8f0aea.nq.gz
    ├── 01b732cd562dbd91920dcae86448d3819e19f1f0.nq.gz
    ├── 01be39196ba98202d691e388ca928ae11b0e29c5.nq.gz
    ├── 01c2e2630cbcace57a71f7447299c76e5b4dfaf5.nq.gz
    ├── 01c4201fe150ba57bfb48ef574ea30b70565499a.nq.gz
    ├── 01d2e41832326f0be55450e033270247c94db122.nq.gz
    ├── 01d891809c238085595a407f1d240a148318b5de.nq.gz
    ├── 01ece2a8288d2ec9e56cb9a6282e4edd578269cc.nq.gz
    ├── 0208a7561bfe370ab9ad42e9f4a456ac9033bfdd.nq.gz
    ├── 020d441df49549d6c2480926a5174cf1a11c9bb5.nq.gz
    ├── 020e7f1dff0b7b9950fe8163b0ea580bbbd889ae.nq.gz
    ├── 020e891aabc1f9fa279667bd5da7a29aa11640a4.nq.gz
    ├── 020f268bb87d10abdc6f6e11a5b3b4566329c34a.nq.gz
    ├── 0211e5be8053c72d901806d38f0b733c69e8a394.nq.gz
    ├── 0213f0039defa074f5a96b4a8ce12678554dd08a.nq.gz
    ├── 0215338f3e31aaa9bdc3e6f1644cceaaea5f7fe8.nq.gz
    ├── 0217d61cbbd5a7a9d491513466e6f3c5153a289b.nq.gz
    ├── 0218dd512cd02af399b8a3ce54197aaa29ffe9a3.nq.gz
    ├── 021e6606bbb8f225439a76c7ed360dc3c965d5a6.nq.gz
    ├── 021f731d670386738a5087c1d452ff3a9129ee83.nq.gz
    ├── 02273017a6b41d71b95cc6c7c3d42f99213083ee.nq.gz
    ├── 023531c5c0187a601cfe953b30393d46fede99a0.nq.gz
    ├── 0241400b57e97c6bdec09a69d9775bfcb4c8304a.nq.gz
    ├── 0243b619279206dde1d13022e417b60ffe7357b1.nq.gz
    ├── 0249fa5cfebb4fccdaf8491bdd5d3d3a23baf18d.nq.gz
    ├── 024cbe84377f00c89f960bf833e8dd0e9d5266c1.nq.gz
    ├── 024f67ba736cc6651c3a8db0d34fef1d9f50450b.nq.gz
    ├── 0250bba7e32d288bf480e78217e0e26e619a7f26.nq.gz
    ├── 0253cf1ec055882d69373fb4c18428120cc34784.nq.gz
    ├── 0256c848a42e870648c1afb813d1e6fecbc21ffd.nq.gz
    ├── 025b457b372c95b6216282a2f66d00f406af1e5d.nq.gz
    ├── 025cf6731fde4183c1036d40eb83e6206aa62035.nq.gz
    ├── 0265f1a3bd8e706a465b04b1252522dc1ffe3778.nq.gz
    ├── 0265fc85c632d6b61ffcf0f5db77e12800eebf48.nq.gz
    ├── 02688e37a444b4638c80203d617dd7eebbd822dd.nq.gz
    ├── 0268e61eaaf3be78e4d7ea45165306263dfd2a1a.nq.gz
    ├── 02697cf9ecce29f1eee002ad17fcc258fcde1f2b.nq.gz
    ├── 026d34565b6e1c92b48a2cf794ba1dd76ce0e8d8.nq.gz
    ├── 0271ba1b0905ff154e94c7ce91d1494b1bbb7245.nq.gz
    ├── 0273f1d26b0fa4abb4e10a7d3a06285baba54d0a.nq.gz
    ├── 0277f0829221ca12d5a8bef8442ed5ec7eb55157.nq.gz
    ├── 028a59ed2f1115d95d70506a19413738edd04cd2.nq.gz
    ├── 028c2d42643cf1d6e00aaccf55ffae46f7ddbace.nq.gz
    ├── 028cce114fdd984c669354e06d85d9d07f3287f9.nq.gz
    ├── 028e2d50f7c5b78c791ee54a6a279e2f8e0e4438.nq.gz
    ├── 02a3138fb071f18b49fba95a7f431ec354d0e504.nq.gz
    ├── 02a343c2e483eec5ff628fe6fe417302cf330e83.nq.gz
    ├── 02a710198f434bec7ee616d21bd19754cdf48cf8.nq.gz
    ├── 02a9bcf8c56a8f6ef388bc5284027442ce4b80ab.nq.gz
    ├── 02ac3766f55c2a0bba81309ed3fd74925138ff7c.nq.gz
    ├── 02ac9832b872ca9550a5113c8300b6c23748deea.nq.gz
    ├── 02b063d7d7e35c5c707d3be61d1a6cd9ba951808.nq.gz
    ├── 02b37e18071c020c8d4a4a352363c41e539e7740.nq.gz
    ├── 02ba8edf89de2b5f9f06f8cd4f15bf5f9f498936.nq.gz
    ├── 02c09043147b87e983b624340386edb1e79bac5d.nq.gz
    ├── 02c52fd77650eb8f476dc58a4a19b44c1f826217.nq.gz
    ├── 02c5c9b70fcf1961ce9e9392025858c2258f64ee.nq.gz
    ├── 02da25954c320b553b0002702ea201110013ed14.nq.gz
    ├── 02dc4bdc632d9ddea4a2853663a9d5023371f0ae.nq.gz
    ├── 02e3899a0ba034dbc3c0e0bd650036c3ccd35ee5.nq.gz
    ├── 02e42e32e59d44405faf51dc5912fd062858ae1e.nq.gz
    ├── 02e4a43b7e0e91ae3f383896c0c63b8c56b4f538.nq.gz
    ├── 02e75ab79a542f8d6787028aa46caf7ffa35e3c2.nq.gz
    ├── 02e76c2a9fe4f82007283278bd6cf77d2ab1c6a0.nq.gz
    ├── 02ebf9c44fa6935e834f34fd293dd576fc1d3fa8.nq.gz
    ├── 02ed307c82be06dec2ac73e990a8b70d3dfa6d0f.nq.gz
    ├── 02f8a36a0bee789fd9569b161cc443b1d1d070d3.nq.gz
    ├── 02fae5f48fc49fce68d0f5d2ce499bb2d1a64622.nq.gz
    ├── 02ff248a4a0f5b9c9d8dc34d7b864df8bc3fb0c3.nq.gz
    ├── 0301d5e3afbf5b5d7cab7edcba1fc483ac3f5c3e.nq.gz
    ├── 0301dc851bc364cfae12c8b1779c01c9a0044bc1.nq.gz
    ├── 030330197e0ae685630e67abf5e625fd3eb1170b.nq.gz
    ├── 0309bfdf6f79c153f3d47bc9a30255f34e89589f.nq.gz
    ├── 03101fc134dd6812bb88ff3534a3dba20899d759.nq.gz
    ├── 03181a8cb8f651cc261bdf9148fd33e98512f4aa.nq.gz
    ├── 031c62714d9b84dc085000882fef86f5fc5e24bc.nq.gz
    ├── 0326fc380d38cda416a3f57d60c5fa3bd281096e.nq.gz
    ├── 033256f6864a078126c64dbdc09b58251ca16e29.nq.gz
    ├── 0338dd8b1a69be2f877f411fc2491b9f4daf3484.nq.gz
    ├── 03403c26a36a44bdc54c9bc4116d4f24595c894d.nq.gz
    ├── 03424542250108c215b64975bad676153d485e57.nq.gz
    ├── 034a660b4bdef518924d12cc08857c1d4c107df0.nq.gz
    ├── 034b0019108e637ae35b8a22dbbb08cad78a0a9f.nq.gz
    ├── 034c3363c56f13c35c4cffee10b6a51e53d1b0ad.nq.gz
    ├── 035fcaea433bc729a6fcc723c5b853c71ea76b66.nq.gz
    ├── 036a9cc897b21ff97e3af2cd3af6032e42186041.nq.gz
    ├── 036f3edda7a693806f1e23de71b90adcdb80f0da.nq.gz
    ├── 0371957d8b9a88ca8e3c1164a35f65cda91e8758.nq.gz
    ├── 03728c8a8a37dcb1f5d138e298e9b983b2b45b77.nq.gz
    ├── 037a328a57575b4ec43ff4a24d5c29586c4b1d3d.nq.gz
    ├── 037de14962b6cba9405a8a26f225029041b6d60a.nq.gz
    └── 038559799d1a8c817657d5f6470c0ced611f3ac4.nq.gz

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

[squidfunk/mkdocs-material](https://github.com/squidfunk/mkdocs-material)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
