# Repolex Knowledge Graph of dtolnay/syn

RDF knowledge graph data for [dtolnay/syn](https://github.com/dtolnay/syn), parsed by [repolex](https://repolex.ai).

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
lexq download dtolnay/syn
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7bcb37cdb3399977658c8b52d2441d37e42e48f2
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7bcb37cdb3399977658c8b52d2441d37e42e48f2.nq.gz
│   └── repolex
│       └── 7bcb37cdb3399977658c8b52d2441d37e42e48f2
│           └── chunk-001.nq.gz
├── blob
│   ├── 032a374291b38597b2495297bca7f9dea741a5ef.nq.gz
│   ├── 06066ccab163834700c0381c0eabc7d13fbcd5a2.nq.gz
│   ├── 07409932677bbaef44da8ea6a377cac0dfd7c710.nq.gz
│   ├── 0dcaa94bb27a922180cd695a12fbd920dced61d8.nq.gz
│   ├── 0f18552af0c49a886bd011e35d38e3b73d13cf22.nq.gz
│   ├── 0f92701dca3a91a5df74fbb1d93979598d8a731c.nq.gz
│   ├── 101c1b1c906d2f48c307bf1bbbd31fb693ce4ff2.nq.gz
│   ├── 10df0ad56c2ad69d7a5e0b1a579773c53d4f34a2.nq.gz
│   ├── 11a82adaadb0e75deb85d3e73a09e627a773f812.nq.gz
│   ├── 11ac24d7c9aa86933cfa2a8093975717602befab.nq.gz
│   ├── 148701ea444bb9acab842941032f99d379b03114.nq.gz
│   ├── 14ea96c7717221f068aafe68b92b4a28b14c8313.nq.gz
│   ├── 15107801cfee02ae790d5e06c4cd6b4cc3ee1e93.nq.gz
│   ├── 1b473858cd1b286f3aa4c025443890f472d940b5.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 20ab75e4215c10d1e75df512ba8c5d16ab81d222.nq.gz
│   ├── 20d1f397740cb8af6648fc04cc390fb15ca89967.nq.gz
│   ├── 212e22398d5ae6015ecc61215a54da1002c6ec07.nq.gz
│   ├── 240d10db939f9aa871c3787667f4e408297fc271.nq.gz
│   ├── 272e2d26e9abaec9fbcd5d2933d1aeac8d9627fc.nq.gz
│   ├── 277093dc938654ee6384f3e085ad247f75eb6934.nq.gz
│   ├── 2840f91af030f6ed5d45549896d655a0be5ad17a.nq.gz
│   ├── 28ceee8b56d55444909a4a90a59e0d931509e00d.nq.gz
│   ├── 294ed7e4da878fa45a3b924ae0638330f02ec327.nq.gz
│   ├── 29fd43589d427a055b4befb8a6d81b208ad1fb55.nq.gz
│   ├── 2b2c31e984c919a8e9719866f6988c2cca2db174.nq.gz
│   ├── 2b753ea60102f52991af47a1865bd1f557b36cb8.nq.gz
│   ├── 2d2a6c5382d53b0c9931bc2b06122462cc02d47d.nq.gz
│   ├── 2ebd9ef12265e4946926206f82f3f13c72de9f17.nq.gz
│   ├── 3112db7566a328520dee1aecb727da5c680a2db1.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 3652f4413aa20d5f7dfde6e5c5af179534bf95fb.nq.gz
│   ├── 37c84d80255dd4d27be6dd7fe9b90554ba1e8082.nq.gz
│   ├── 38551445b26d66e5e14ce4dbe6efafa30eb3267f.nq.gz
│   ├── 3b55ddfdd59d0381ba340f44a92e17fa0b0755a0.nq.gz
│   ├── 3e96b2ed944fdf51d6767a69b241724f6795947d.nq.gz
│   ├── 46fc0247b396dd7a66b331b5051e84519e46e7a1.nq.gz
│   ├── 48540e1b39f9d1e309904f43f00a3e1aad484eca.nq.gz
│   ├── 4950eecb60aa4fe79f94b91031c860b60af7d237.nq.gz
│   ├── 4bc31dc394135fc1aa166b499d5f346bc0abfc2d.nq.gz
│   ├── 4e1f9caf38e0c1822153880f463357b3caf73aa2.nq.gz
│   ├── 506b42cd7284a1acad45f1e142d060c18fd1cf13.nq.gz
│   ├── 508af526c1ec7e6c50686042ef2b5a8ad30e7b82.nq.gz
│   ├── 56667b6a241cdc2e5ca4cba7d092d3396606a35c.nq.gz
│   ├── 573b88fb16671f360447763581bcc9a17360560b.nq.gz
│   ├── 575d9faa1273ad81d244e19eef5932d3ef56d399.nq.gz
│   ├── 58955c7ff1965f642d1c63f7e032d38be56def23.nq.gz
│   ├── 58ae526a995c66903e5322ab9bc105e0a760a70c.nq.gz
│   ├── 5ba15722b7bcc5ce04c71acffeb64283b8a52d49.nq.gz
│   ├── 5c7fcddc8da9a6cdf72abfb71d575da8ee907316.nq.gz
│   ├── 5e2d7a71f25d2d269029c19ffb66b9c89440cd3d.nq.gz
│   ├── 5f29220114781a07441e8a8afb85d37606183d71.nq.gz
│   ├── 5fa2e59e14be63e545989e32071f5f609ac7ffa5.nq.gz
│   ├── 5fd5da3c99f8bac0eb6ccbfc552c9634792dcb0e.nq.gz
│   ├── 600870bab58a4349ef6dcfa23d042657495dbfc0.nq.gz
│   ├── 6167488c9c5500b750b94c6ea57ef80720d3be1f.nq.gz
│   ├── 61bc8dea1cec9864287fe3d357d72a780dde4e06.nq.gz
│   ├── 63a89acc3170c2905d21b654582d573eac0fdfd9.nq.gz
│   ├── 6588182c4fd66c43982ad1ec20e4f94539bb6118.nq.gz
│   ├── 66e4dbee746612f0acc71ef8ab0b67b0ce39c7f6.nq.gz
│   ├── 6ba25af38fa7b3360c2c72e78125fda393ef3df9.nq.gz
│   ├── 6d2c3092d54838f9c441804500a5df3680f68c10.nq.gz
│   ├── 6d5edbd559ab116398b672850762f84e7031a632.nq.gz
│   ├── 6ef45aa97eb88f4a8ea383a5e4d8afb2fc9e06f7.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 75217e1b5735df8fd34858f6a7641873d1f7e567.nq.gz
│   ├── 7545c6692612c209a58a8a6b7dc45f069718be56.nq.gz
│   ├── 790e2792adb3a77d6608f8229c80aa1181deed18.nq.gz
│   ├── 7a7319025ba99b2bf6c84e0061c6461e106f6cfb.nq.gz
│   ├── 7ab2b795d5d3500c7a1b0acac8e1bc4f0bd04fb9.nq.gz
│   ├── 7c9a93715985b9fd4cb457776c362bcc859d2777.nq.gz
│   ├── 7e7e0315ad52009ecc13fb13bf1ecb9bcc9df5f9.nq.gz
│   ├── 7f107c64dcae4c920e18bc8a9d472666f575f964.nq.gz
│   ├── 7f410166914574b2e854b48d1681a5624c87a8d8.nq.gz
│   ├── 7f9e515d26963e3d5518584ecb7222a8e6ddc6c9.nq.gz
│   ├── 81c485e6b28fc72f2b210582262772e40127b040.nq.gz
│   ├── 82accac78ecec3ef0ec9fa624fa2d8cdffd24e26.nq.gz
│   ├── 847552ad8787c6f310a7045d099482bb8c36784c.nq.gz
│   ├── 8836030664b8b7155fc34c4b83367e5c19a3e4ed.nq.gz
│   ├── 8af199ad2c480b5a461e622900e95bb25eb31c15.nq.gz
│   ├── 8cbb83bf8e79fd53f660a10d0dcc69d971542a64.nq.gz
│   ├── 8d4439308e8a47b16f4ddf01bd01dd52a93e808e.nq.gz
│   ├── 8d63a4111b364e8a510f02620c6ab1d9fa1b9db8.nq.gz
│   ├── 90880ddc0eb06b4bf6dfbb4c7037e3fea262045f.nq.gz
│   ├── 91b98460ccd5b55fc5910127e8fb2d7bc087485b.nq.gz
│   ├── 922534fe911b2f3554b5534108b5e7c680c4f45d.nq.gz
│   ├── 923fe19d19620c37d56bd321b14009a44819ea53.nq.gz
│   ├── 92dbc96699c0470d23b799b55d78dc55b7ffac37.nq.gz
│   ├── 9332b11c4ff5d41b653b4585cb4bdec5e2eace61.nq.gz
│   ├── 98194101fdac0da3372e105d754cc877c6fe2c97.nq.gz
│   ├── 98d2aebc9d303e5c93c5ab7dd00405774baf89d9.nq.gz
│   ├── 98d3051cdd25c76a947f1dd7aaee9ae6595d05ee.nq.gz
│   ├── 9ae472ea6699740f96c42e7ca9bb86d359fdeaab.nq.gz
│   ├── 9c9a957f71c27fd507165dceb0439dd1f6e2957d.nq.gz
│   ├── 9e10b4c9bbd556d92549a2ba55dcec25ba792068.nq.gz
│   ├── 9e26bd9ac04bfa7fc6b54652b1cdf64057e0bc48.nq.gz
│   ├── a1a670d9edeea1659ae390ca842691df0bd77a1c.nq.gz
│   ├── a3a0416cb097313180c4f9e0a63809594911ba07.nq.gz
│   ├── a3f6acd4a067cfc93054629d1092117357ad721f.nq.gz
│   ├── a4cdfd92cb1e00dabea9bc8c3f4dc9f2688ba00d.nq.gz
│   ├── a50b5069a68b929f87e6f806550584775b633b3c.nq.gz
│   ├── a650fc85346c251c69df036fa51131f8ba44a093.nq.gz
│   ├── a77b3cd3e8ff57a8dc0d28b68886ed9db736dd53.nq.gz
│   ├── aae7371e592792b783d05a954738365f840f638d.nq.gz
│   ├── ab2c4266fd102b62d4aab4c5b478555cc721a1f2.nq.gz
│   ├── ac188e6834fd8da4131f699f287f904cc106106b.nq.gz
│   ├── b1246093a0d4404d5e7b626d9bdd36efe88507cc.nq.gz
│   ├── b30d694eed7e9800fdbb031b6982e8a7d5ef0786.nq.gz
│   ├── b466c7e7217e09cf84a966d2c217f79795e7ee13.nq.gz
│   ├── b61b56189dbdaa8627a7f37c874b5002c3f0d149.nq.gz
│   ├── b6e95a2bbc0d0a549040f7800ecd12b1898d4ed1.nq.gz
│   ├── b71421f47a35ac27d563bd81e28bc32163bb45aa.nq.gz
│   ├── b95e4c351c4d434e34d56e5770d934401b1c4c07.nq.gz
│   ├── b99521d0f7f48a96de44d926bff1a05ae957d88e.nq.gz
│   ├── bc2a66f0c9d586862f620f9ee0670837c77f49a4.nq.gz
│   ├── bd1c104d9bf18734ed27ee335a0c21eb36370058.nq.gz
│   ├── be2b698422da91d6238cbf58a6d21d333732334c.nq.gz
│   ├── be966caa41b13af55be91b4392a7be9961a8de5e.nq.gz
│   ├── beeb66017d46734563182d25e74e5bbb623b6399.nq.gz
│   ├── bf0784d1c463b4d9dd1ec43216e9732e53161fab.nq.gz
│   ├── c05a0c61d1d083eb89779f36f212749763b608fd.nq.gz
│   ├── c0d37b791d6beb9bacb87800e6447e58a0e1f02b.nq.gz
│   ├── c19adb843c86d7f3c9980ac6a490d4d53cf71830.nq.gz
│   ├── c404ae1ab194f40d2e15c50bb744ac4fb365b2f4.nq.gz
│   ├── c4f64af907ae8592bc4e7b57356110384bf655f9.nq.gz
│   ├── c671b25596daeb6d28fac49b660bccc4afadbfdd.nq.gz
│   ├── c7aee3285bb29a2e919f29cbda23c8077dfc67ff.nq.gz
│   ├── cb2e87da4cb3d8e893d8f0932385f609efabacca.nq.gz
│   ├── cc4f632c981a97148202b1d76ad7832107d07fb3.nq.gz
│   ├── cd258fcde120a9bac0645c7e6d70bf3e3f4735fa.nq.gz
│   ├── cf15574b51029948c56d6e09bc5a281aed45ab64.nq.gz
│   ├── cfaea94a7eaaf4bd2eb4addc6d32895b8dddf6a6.nq.gz
│   ├── cfe9de12eacee6f706778edd7c9a7dc5d59e8d9e.nq.gz
│   ├── d0cdf8eda600e89fdcd139680d5084c9fa1d676f.nq.gz
│   ├── d1dc0caaab8f690678013c2ecdfa36d2ce75f861.nq.gz
│   ├── d225f7f41568cb378cd0be5388179c7a66f6a2ff.nq.gz
│   ├── d32298b79321428ca593f1dfbad094a1e6985db7.nq.gz
│   ├── d3972d88117e19f59d9f68fdb4485a7b1f9ffdef.nq.gz
│   ├── d438a43ad9bc50f7d8683a188c1b4f5423d06ca4.nq.gz
│   ├── d633830545d01dd6a6d8c2f047ab23f30fa041ee.nq.gz
│   ├── d67cef6bc8a6720682c9c24cbf4d8b4977aeb0fe.nq.gz
│   ├── d9440ab39429fc777344a5dbdb491a2090bce811.nq.gz
│   ├── da2c10b8498f6597186cbd2bdb29c680be3e85b3.nq.gz
│   ├── dbb1bcb4fff966f7cc833e8fccc77a86aee87c2c.nq.gz
│   ├── dc804742d12db08ebcbaf300418624993b559fc8.nq.gz
│   ├── dddad3f694089df69c3521361956a571e468e54f.nq.gz
│   ├── df46bd253a3ac8c1697af76aac7c1e3302368cfa.nq.gz
│   ├── e21373cf96d84cb78a8125997edc4e4f2cafdc64.nq.gz
│   ├── e78955990d8e7b7f9a5cecf3e84778a57fb02769.nq.gz
│   ├── ead830f811656a6199edad03262ef6348697083d.nq.gz
│   ├── eb2779479aaac57e8a1ca8a0557beecf1554f027.nq.gz
│   ├── eb29bce2e8ca80a48c6268aa5b78b7315e5e4fea.nq.gz
│   ├── eb675465f022b70c655386c116383b739dd39403.nq.gz
│   ├── eca67f6adaa6bd0a8438b070087a589ebb8ec3cf.nq.gz
│   ├── ed82ae1502b4b65642ba4e06fff6a7ba07af2ce0.nq.gz
│   ├── eeaa39835409c1232641d76f4a2c30881df91cc4.nq.gz
│   ├── eeeadd1e91592cb52ccc459315f9c8eaa5e802b4.nq.gz
│   ├── f0660aedd7dff9b613453c23e9c20eb432d1ae74.nq.gz
│   ├── f2367b44165dafc986ae180573669254886fc484.nq.gz
│   ├── f6b61f3971cec2acd3f3f67bb0293ef958651207.nq.gz
│   ├── f756578b93a985f441643db8a419b3549b43e841.nq.gz
│   ├── f778928bc99341f8b9be94ebb07909a0dd8b7ec8.nq.gz
│   ├── fdd69d6a3b19947e15e36b2ff74ebb0ea42abc4e.nq.gz
│   ├── ff3147c0561804cf986d8a27503faecf91cc4691.nq.gz
│   └── ffa1da08a8f3c726c20fc953bccdac99a10671ec.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7bcb37cdb3399977658c8b52d2441d37e42e48f2.nq.gz
├── filetree
│   └── 7bcb37cdb3399977658c8b52d2441d37e42e48f2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 175 files
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

[dtolnay/syn](https://github.com/dtolnay/syn)

---
*Parsed on 2026-09-07 by [repolex](https://repolex.ai)*
