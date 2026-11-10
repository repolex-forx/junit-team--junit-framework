# Repolex Knowledge Graph of junit-team/junit-framework

RDF knowledge graph data for [junit-team/junit-framework](https://github.com/junit-team/junit-framework), parsed by [repolex](https://repolex.ai).

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
rlex download junit-team/junit-framework
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 12f007f531867169baefe4483b7d7e5dd15acc77
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 12f007f531867169baefe4483b7d7e5dd15acc77
│           └── chunk-001.nq.gz
└── blob
    ├── 021c28c3f47bc88e77cb8e68adc68bba3a399993.nq.gz
    ├── 02545cdd512ab148052385e8f346caac23992fea.nq.gz
    ├── 02d69812a83f4bacaf8b0d9201edcbfe252aa4c7.nq.gz
    ├── 03825a46b808e87a5a8fcddc1fa6cb8e525d7b45.nq.gz
    ├── 03b1601f40a62927b00278f2280f58c00fa6f7c3.nq.gz
    ├── 0475270319489e00dff0b4700d1ab09f1172469a.nq.gz
    ├── 05150d0a10fc75b53582eee76b0ba6da527cb9fc.nq.gz
    ├── 055648b7f56159f2a27f9b7d47503fe870f8e103.nq.gz
    ├── 061026fa3d5835b7df6cbb2ab379edfa3fe905c8.nq.gz
    ├── 06123735a545b952b8f00e194ed953b53114c339.nq.gz
    ├── 0624868ad2b0e9fa61fd08a5a807ca1fda454d53.nq.gz
    ├── 0658a8bc856554f2b094d38363f6c6a991612dab.nq.gz
    ├── 06c09c805d8f348b6bc30d2f883e6675bd3da9a5.nq.gz
    ├── 07526960466f0009a0e53e234a924cf3bf03dd31.nq.gz
    ├── 086629ca2bc6dbf86b2e54521c0b753c8cf13194.nq.gz
    ├── 08c2ae188b69881d56f90a4a446acc409f78cf32.nq.gz
    ├── 0955a5f23faef8fe8f6654deb821e6967fd0123e.nq.gz
    ├── 0aac34938980b72d91171d0625677795403773ff.nq.gz
    ├── 0b855e5d5b17fb6ea39f36fdde4d8d6326ad16b0.nq.gz
    ├── 0bc2f0e0bf7baf8be8099bca8f1c78af2473b495.nq.gz
    ├── 0c0f0ab1bb4c5ee0d6344ba4c565e8767c87d156.nq.gz
    ├── 0c4b142e9a768208a9935f9553d927695a55e851.nq.gz
    ├── 0c5032304342bc9727dc3bbc777918ccec5ca576.nq.gz
    ├── 0c53371592a4c2d6665b2038cfc69c3bace90c34.nq.gz
    ├── 0d3ac3d36b60392a160f93b0fd0af196c9ed4d88.nq.gz
    ├── 0d72d10018f20d458c502ed6e3069b09eaac4a09.nq.gz
    ├── 0d8e7789d62106b8fea0a94f4580427010012378.nq.gz
    ├── 0d8fd5fedb294beb938d9c59fe19d4ba02085cd3.nq.gz
    ├── 0db3b13a83b1c6dd98bcee5e811bf9ad79002788.nq.gz
    ├── 0de37d968dd8440b34c27b4b2d803a57027be7e3.nq.gz
    ├── 0fd064684dedc15c58965c222788f88cdb49723f.nq.gz
    ├── 10a403d32c9c52414006a8cae88608ce98cf16e5.nq.gz
    ├── 10b0f0232260670f805df26b246512b7fbe0c461.nq.gz
    ├── 10dc6ea4d8c57e058d62ae0a4ab697841422fa8f.nq.gz
    ├── 11046d1c0d1f3e472c52f64616c1059f9be214e0.nq.gz
    ├── 1111f9ceb381f965c8abc5aa53c997ab612c9e26.nq.gz
    ├── 115a760f864bb5a1c2be5aba70d6b41e93b7410e.nq.gz
    ├── 13a4976d82f5bee5a432b656a3bb2e6413129cf3.nq.gz
    ├── 1463496f599782b152091ba9896fbb7095e2b709.nq.gz
    ├── 151ef99b166d31278548ecf6995fef7a5c0e854a.nq.gz
    ├── 1641033da355937053a00d55b0f7c07ee4772e69.nq.gz
    ├── 16cd47c4643731d3ad0722bb5e2cd3bcba5eb06f.nq.gz
    ├── 16e67172e81e49fb730d193540a3a34074d7c157.nq.gz
    ├── 170360744b1cb86fd241aca335ff1e74774c69e2.nq.gz
    ├── 18daa47de66d5b1d61df99c55c5c45614e3ab258.nq.gz
    ├── 196aedc0c93414aa3c1afa6c3cd9b592e0b12636.nq.gz
    ├── 1aec8dfa48dfff6ca1913fe92084a360bb5ff659.nq.gz
    ├── 1c6e7334ecca42ecfbafb675f5fa32a7469115e9.nq.gz
    ├── 1c866e401c7819a8f729de32c82a89a5ce2b4e5c.nq.gz
    ├── 1cbc2d28cb78437f607cea66e40a8852b44990e3.nq.gz
    ├── 1d23e10e72b68f7d7173f5d62050df39a21654e6.nq.gz
    ├── 1d3516ce41687a39c04df064cd4c92d9c8baef5b.nq.gz
    ├── 1de2a846e3d6610c8231ab01e1f41822722164b0.nq.gz
    ├── 1e7da4d9bd486905549efb0a72111c8e6e84b2a6.nq.gz
    ├── 1ebf42f5bdeb3aad4a1bb241780252386fe0b70d.nq.gz
    ├── 2092f07a42afa8a0214ffb5b5168772f9bf7cbc1.nq.gz
    ├── 20f904a8b8de27c4e4040a8a212338f7968e8f8a.nq.gz
    ├── 2124b949908ab5db27284e9c3c43a281a4809406.nq.gz
    ├── 22c199ef47dded687f7c95fbe4aafecf438f518c.nq.gz
    ├── 24338dbc89fca37ac2a2b6c41e131bf178bfc80b.nq.gz
    ├── 2491ee2892736ccb4c5789be459334e5a469529c.nq.gz
    ├── 2647486c74d37f7aa541825fabcb19062653a7ce.nq.gz
    ├── 2687526603ff7ab206e0d93de5b1881ca4470483.nq.gz
    ├── 278f1abfe27ab66526e4f645fd2e2fe94996e143.nq.gz
    ├── 286d05a8999f62505b2f920564030920abf93a0e.nq.gz
    ├── 28bfabf903d43132d3d676cbef58e35d1602738d.nq.gz
    ├── 28daa01422191145c09693eb53f422001e5d2815.nq.gz
    ├── 28fcf1fe8cf65e3fe11a39977e2c6acba90fba57.nq.gz
    ├── 292919be700f3773a40fa70336d7fe64004e1b54.nq.gz
    ├── 2931993a8b896ef85beb1d6b24b4dcc4f34e3282.nq.gz
    ├── 29c294c753194448c49ade3e095863bdd15eb361.nq.gz
    ├── 2a5284fc83baa231b749bdcf70afd5cee6647890.nq.gz
    ├── 2cb3d8b551f02d0736e8cc7cf32939829121ec61.nq.gz
    ├── 2d0f96153ed59d05cfd7c096441d1913e69d4e16.nq.gz
    ├── 2e698f263c87104771ec069cafe82f82c9f211f1.nq.gz
    ├── 2e7f7d18975f6f5fea6d33c84c11f214229a6fb7.nq.gz
    ├── 2edd995c01ddef2c7a05e7d2588a70797458e9c4.nq.gz
    ├── 2f03fe1f2adc5df0d3f4f1a07fc2798934d0cf1b.nq.gz
    ├── 3035ba252ee6aa5241f4732eebd8ba0d5a413bd1.nq.gz
    ├── 30533491790a818f5dd6c8f301cdccfae310892f.nq.gz
    ├── 309466b9e50d6a9afc7b2fbe104944a0c6e172a1.nq.gz
    ├── 30a86d5208a5b4e0567dd42d69c4cec35d589d4c.nq.gz
    ├── 30c333c09088e10962ba11ee161247c6792e4348.nq.gz
    ├── 30ded20daf5bb86e1c7741d59e8fe4ecd524836f.nq.gz
    ├── 312f05c44fb4c4e03ddf46bbb00e6491f09fc62e.nq.gz
    ├── 3290e40c17c1ebbc75b23031b841234227b766ee.nq.gz
    ├── 32ae852a567a2139710d6632ee8a1e1f15e9e0da.nq.gz
    ├── 349119adf6f36513159486486e04d40544cab08f.nq.gz
    ├── 35b16471a06fc42cbc904da929debc1dab05c80c.nq.gz
    ├── 36505d8cb5200a25fda07da21a24849a6f8801f6.nq.gz
    ├── 3774734bf57ac91fefda61a99dc2437679ced487.nq.gz
    ├── 37c7ee9965ff1dd4653d50befc1af258979957da.nq.gz
    ├── 382e5d54271ed75964ca151124a6c8e011ed2ccb.nq.gz
    ├── 38bc62edbb7953addd681151bd6a55ae285993c9.nq.gz
    ├── 38c58ab9c7ac5c08a9261a4aa94c40fb74ff8cbe.nq.gz
    ├── 39c3fb15ec71262dd78dcc40981e11b9edacdbd9.nq.gz
    ├── 3ba41c3cf3e9f322943b13d90bd488bc9ff0f2d0.nq.gz
    ├── 3bf1bbf781a740f8f89ec0e36a8db14a7550ff4e.nq.gz
    ├── 3c262e04895a2e8670750765ed78d4b814798fb6.nq.gz
    ├── 3c3f8c8a74040f8c2e5e025e3b6ca191a670ba44.nq.gz
    ├── 3d609d0bbcb91f07661696d0265ba9b480e5855c.nq.gz
    ├── 3d7bfa80f32474ef9bce4e09f6d16a9967eab7ff.nq.gz
    ├── 3dba24faa5de50d086e5204972a77af5cfc5f2d6.nq.gz
    ├── 3e16c0e9c951ec3ad4f1b80488f48680f9aa87ec.nq.gz
    ├── 3e3a110aa0bcfc2c699b0d7b0262e1f792a417de.nq.gz
    ├── 3e6309ca4adfcd452280aeb3f687b0baf2b311cd.nq.gz
    ├── 3e86676e8fc088690549bc1a9157ce3712a7610a.nq.gz
    ├── 3ee1ada0bc0c39f846cedeb30e97285c78103897.nq.gz
    ├── 3f4a0f94a3ff52a2919ef014deedf31381a6c4c0.nq.gz
    ├── 3f5f102f346208e1ee196494550f05ec162ef36f.nq.gz
    ├── 3f661c200d6031f9622e7987969643e3cf2894c0.nq.gz
    ├── 3f8177ae5d6ce3239c69ee3f83a8eaa7c2364364.nq.gz
    ├── 402a62451836dfa37aabe06ef03d0b8f5e09b620.nq.gz
    ├── 40ab146721101191e471ee47c265fb2a50d49c97.nq.gz
    ├── 40bcd60434c8a7692c5ec204e378d3607d737ee9.nq.gz
    ├── 41090f92f7ae5185f5208c02b3d42276d6891b22.nq.gz
    ├── 4246070ced7135fd498ddb7a22824a576a686e18.nq.gz
    ├── 43d48f59750324979cae7c2327c1c39e082564f6.nq.gz
    ├── 445297166ef4ee935aeb21883e62b78c58ee4b28.nq.gz
    ├── 44e933a9e106fc0f6b7969ff8a8271d64fdbf3c3.nq.gz
    ├── 44f65f8490cf057dd99090aac0236d11193f39a9.nq.gz
    ├── 4576e17eb87106528f2e81d5d08ed65867333731.nq.gz
    ├── 45a3e7cb5a412081725d18383c7349cf4887cf87.nq.gz
    ├── 45dd45c35639e526983326f1eb2a5541c8b100b6.nq.gz
    ├── 46b9a6c079c7c1cee40dc303aedc0af4448f9cc0.nq.gz
    ├── 478cbb03525019aa1b34e00a9f7b0398f056500d.nq.gz
    ├── 47f6c0bb39925ae1167c2b72fcbce2cb44890e93.nq.gz
    ├── 481e8ac34ed5192546269051836536da0b2223c4.nq.gz
    ├── 48861cde61efeb0c050d1787294accec386e8a51.nq.gz
    ├── 49b411910a458f9246356fea7f6e087b2798b213.nq.gz
    ├── 49ced897e708eb8faed45f8f67989589c0545011.nq.gz
    ├── 4ba5550e706c6a4d62084f0d148c49bcc77d55a6.nq.gz
    ├── 4baf0f43043e10dedc8353556a85f658b6e84439.nq.gz
    ├── 4c299873a6303ce2d0eb753a0c220bcac921f0c8.nq.gz
    ├── 4c394e95274d624c9ea2ff623920e410b2e727d6.nq.gz
    ├── 4ccae0dda49e1cd8982713e7b4fe50f937e1638d.nq.gz
    ├── 4ce58e9d83fb136d2de72941e7306dd676712c05.nq.gz
    ├── 4d60ffa7a9cee31fc3030032e262048caaea9786.nq.gz
    ├── 4db62b007f6a052b0e6858fbbb6aab76f5303523.nq.gz
    ├── 4dc7657a9837cebc9ea0e1c3b770a13ed880dcb3.nq.gz
    ├── 4e73a4260e0e36f132f79f00bbd3747b3916c1e4.nq.gz
    ├── 4e8a13dd02f043c5f41e23329dd4fb58856abd99.nq.gz
    ├── 4e9ed117c3bf322784d0ec9560dace1bb86082e1.nq.gz
    ├── 4eebe57e64fedc3daccf626ca11d8ff881766b38.nq.gz
    ├── 4f0463e6dc87220e4b6682e63b21b11020b327a1.nq.gz
    ├── 4f1cffe0e31faf53268a5a4302837d3703a9366c.nq.gz
    ├── 4f83cfc0a897cee8ff872d90dbe0a81fdfd19224.nq.gz
    ├── 4f8c376ebeda32f077a0a5d729ec0136462a0718.nq.gz
    ├── 503ba1cc02a3c1778a6815f9f945105b0717afd5.nq.gz
    ├── 504bf91c93d7a58e16d80cb610fb5021acc39be6.nq.gz
    ├── 504db8625079f985da6ae553fb4ef50ac5aeab44.nq.gz
    ├── 50e3bf79603d19bcd2322fe1ab0326dfec0fe212.nq.gz
    ├── 5130f5881be36f026d5b4e82a8c386f28b2d296a.nq.gz
    ├── 513459b4b4145ebfb8df7f79803ae954d285a1cd.nq.gz
    ├── 519082b351f6ae4733a89a82339cb22b2681eec6.nq.gz
    ├── 51c4f8e9e9c4cfbc7491e6d94268c30f346e66a7.nq.gz
    ├── 51e2971d82dc648869b51d4df8a996d0007b3d1f.nq.gz
    ├── 525d01108a118f07c74c57b51cbde3abceec0739.nq.gz
    ├── 5304d20c11bf95e672918b0c0b8b95738c7baf35.nq.gz
    ├── 541f725a403130038e37910eac996a17aa1dc48c.nq.gz
    ├── 545aa617da23f76ebda40426ea0410fd4701de36.nq.gz
    ├── 54722adc307e732b64c67be25e2157275cbb9657.nq.gz
    ├── 550ed4b88b7e000de8d496352797f1f2ee69fb23.nq.gz
    ├── 554d1a6313f6ddf7ed1d86f1b5f25a70139905c1.nq.gz
    ├── 556a843de13c07fe8b36987e6f04df4efacd2212.nq.gz
    ├── 55e076ab93e303061a8610cbddee6c38e3e3e4b0.nq.gz
    ├── 562cf28574410fb4eb05aa86d9b09aaff8a74985.nq.gz
    ├── 563587048f6e27e8933ecbf38a50504f8ed7e541.nq.gz
    ├── 56537c2b1bedf8103b6a49972d697c8422d8e5a5.nq.gz
    ├── 569e8a24e2dccef84a2a26a7ff0c9619b4ebf7ef.nq.gz
    ├── 56cb0619d7747577fa74821cf7236c5fd4d5202a.nq.gz
    ├── 5832d4fc4620a6db845bb33eb82db64169ac90c0.nq.gz
    ├── 58684243141c6ecfd8feab55c9f936f8d8d2fed5.nq.gz
    ├── 586c90d2029c7a031ffdf426dc37e25508b4e5f1.nq.gz
    ├── 58c3d7c72cacb9efbec8a734e571ba6bd3597512.nq.gz
    ├── 58c89596bc4343f058a262babf4d8d0b1811cff6.nq.gz
    ├── 58e1d7d0fd43cccdd69b895086800a057535c15f.nq.gz
    ├── 5a048e2a859bb1903706a73dd2f4c429bae250c5.nq.gz
    ├── 5a2f6b07e6d307b32ee0e8afc5439986d2bed205.nq.gz
    ├── 5ac5c7f2cb75cfe3c2ae3a0fb6a9ca2db7a37967.nq.gz
    ├── 5b960b93599ebe8049f5b822ca4dd878d1b9a790.nq.gz
    ├── 5bf478dc8de6d95149aaa4c6f3361ea6b6ea0382.nq.gz
    ├── 5cf9f51af8ea25f9ea7baa1c1874944b6ee68d50.nq.gz
    ├── 5dec4b7ffafa8e12931216f5ad5622ff78a6f334.nq.gz
    ├── 5e03f890a13cc927b225e4e0379e4c198afce6f9.nq.gz
    ├── 5e143f2244a7a5abbf715d0e2469e7468639c172.nq.gz
    ├── 5e7f6f2a07f59254cbb6f149c96ddb5d58da1936.nq.gz
    ├── 5eacd273442e5013c2bbf2a6b279c1c28a138ff8.nq.gz
    ├── 5ee9860811facb46605aa0eb259e6144999d5cf3.nq.gz
    ├── 5f40e317838b49b573ce08e3da9f8d86261cf939.nq.gz
    ├── 5f8388ba5ec42a0caa2bd5cb97838ef82fa9bd8a.nq.gz
    ├── 60deea1624021fc63779a3b7a77dcd1e0c82b578.nq.gz
    ├── 632e616a34ee410b6703bfd54d9102c202a799f6.nq.gz
    ├── 635dd409ff37098eb119db10a2cbe2e8c9f904dd.nq.gz
    ├── 63cdda9026ca4dc99e778a95dc19a10353e3425c.nq.gz
    ├── 65768295d304f7053f264a427160e124a6d8f55f.nq.gz
    ├── 658abbda044ebdbfed05bf3e89bf440418239125.nq.gz
    └── 65eddb565fd1abef79216a8d2fb216cdde1b9c77.nq.gz

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

[junit-team/junit-framework](https://github.com/junit-team/junit-framework)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
