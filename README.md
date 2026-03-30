# Repolex Knowledge Graph of apache/logging-log4j2

RDF knowledge graph data for [apache/logging-log4j2](https://github.com/apache/logging-log4j2), parsed by [repolex](https://repolex.ai).

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
lexq download apache/logging-log4j2
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
└── blob
    ├── 0013946589ed63750f9a276895c12d2fb5ef4d19.nq.gz
    ├── 001ca4142b8683bbb99e9ab89e87d461a5cb6cfa.nq.gz
    ├── 001d0482acaa335e2acfdcab3f344382517e3490.nq.gz
    ├── 0027be49454c300391749030f782de3de787256c.nq.gz
    ├── 0038fec6bb4509cec4b7edab51b7c1e2c2831b76.nq.gz
    ├── 0046342813042590d33c58b72f133362379f8387.nq.gz
    ├── 004aed812e19c81e6ba64cf64a1a81409ca88884.nq.gz
    ├── 00518fa03819b6c60ca506c69aea54ba00bed607.nq.gz
    ├── 00546a0e61723623d912a2e5177d07d8ff5db6ec.nq.gz
    ├── 006032325ce4c7c49f320d16a7826eda29f0f874.nq.gz
    ├── 00639140bb01dd93da488d1cd42954fd5f51c7b5.nq.gz
    ├── 0068619c70c5bcccc6fbaa02c9974923d558b485.nq.gz
    ├── 008200b18c5bd01e25fd18feb0cd774cdff7bde1.nq.gz
    ├── 00901ba07438afba428302d5d4b8709ea70af084.nq.gz
    ├── 00969b1410fd9347f3abac248f8fcb6e446712fc.nq.gz
    ├── 009d83dafecbc38ad723b51d7391fbcc23f11461.nq.gz
    ├── 00a9a1a94b94f402168924a4e5a57d44421ba497.nq.gz
    ├── 00b013af94ae2c85334ee63c9905f794784ab82a.nq.gz
    ├── 00b20568e272bfe6a7e2144d61cd7449b6d75381.nq.gz
    ├── 00b3f7131a2eecd3229f83b54b620fd2b503257d.nq.gz
    ├── 00b71aba450fd09b68404ccb6600068279e7afe8.nq.gz
    ├── 00b9834f4f7b400b51ce03802832d3b2c6b44740.nq.gz
    ├── 00c0ce29208eb570c842a5dafb736587d94c006b.nq.gz
    ├── 00c4f42743c3296ef79b89e04fefbb564800efef.nq.gz
    ├── 00cdd55b766b901591acc11c879d2449f960d820.nq.gz
    ├── 00d0e1293ff066a1260b7d262c4c339fdab32996.nq.gz
    ├── 00d13d2a92b9420f1ee209f1b049e4ae0b62d36a.nq.gz
    ├── 00d6534465c0355c14382bce9e3e53ce0a111b49.nq.gz
    ├── 00e1af057fcbf5752a1b8dce0e80f8a252b99757.nq.gz
    ├── 00e7c0135893445cfd0d530801d8dc67c67ac497.nq.gz
    ├── 00f8ba2da3f6ddb1aeb1da2358676f2724eee33f.nq.gz
    ├── 00fa79b85f97002201fa972555ed333bdac99468.nq.gz
    ├── 01077d782d7f138788daa19aa1c06f9de91bb3f7.nq.gz
    ├── 0110c66a5432b4051f770cff88da8ee4bde38811.nq.gz
    ├── 011cef594b364f6b6a0b463d576d532dbdfd6c6a.nq.gz
    ├── 011ee61951765d51316cb5f58ccf53c864531b7c.nq.gz
    ├── 0121fbe931caa59e6b4228fa664ada82b07c0e29.nq.gz
    ├── 0127ed20d545245c1ef294e03e93ec57e1a5fdc3.nq.gz
    ├── 01296f2f1b9b79ad2eb9334afc732e46a6b2b5eb.nq.gz
    ├── 0141c60922c75c8b8c1d64436b3748797c738ef0.nq.gz
    ├── 014aa8c4fdcf2aa637930a37182a0daa5e6ed817.nq.gz
    ├── 014d77585d85a672326ffbcc7d02a09e10fb1108.nq.gz
    ├── 016548752b70509063908c4b6d0f6f3646f2c206.nq.gz
    ├── 0165eb66b07d85c990acb1cfcab3252cd2536853.nq.gz
    ├── 016898d925e121d76af70d4dc5737ccff089c8d9.nq.gz
    ├── 01874dbbe2fb5da3bdcb8607f5257861bb978f84.nq.gz
    ├── 0193245834691c9a2b4e2e2ac489ffede433df30.nq.gz
    ├── 0199eed57dd7b63a9fed2cd08cafe4c5a60fdf84.nq.gz
    ├── 01a2291e2f90a94a0c8c92ba556fd593ec042f2b.nq.gz
    ├── 01aaa6539d18e469bf1aace6906e4022f13e71ac.nq.gz
    ├── 01ab6cdc34aee9873b7787ce8791c8104b7b7ef4.nq.gz
    ├── 01ac986fddebd4cce26679290596a9c48df673db.nq.gz
    ├── 01ba893432a537b03be84030b46c1c72a1491b7e.nq.gz
    ├── 01c094b13b41aa3946d14a08a7905ff908679f68.nq.gz
    ├── 01cd966c084b50bfaa5b190b5550bf181418028e.nq.gz
    ├── 01db40aac3ef5311441290a4487341b7e49169aa.nq.gz
    ├── 01e09ab77d853c6bc551d92ce954ddc8324607a1.nq.gz
    ├── 01e56ecf58e986fa0d02ca9f7f46399eba20d11a.nq.gz
    ├── 01eccd43e64e98325734c6f62c5dde00aeaead3a.nq.gz
    ├── 01f67048266e885907ed76af413668f6317f76ff.nq.gz
    ├── 01f8c96cfd5713c491094ae9e4888cb93d1b6fd1.nq.gz
    ├── 02060565ee8cf6e4eb0c065fb54ea552728e517a.nq.gz
    ├── 020c10f3d7113f8c67835996b3fa4ae8426504fe.nq.gz
    ├── 0217c7fae6a2089130cd9d365755bad328caf152.nq.gz
    ├── 023337e9af5bb75d0ae666debb433e56bb86538b.nq.gz
    ├── 0239b2908db7e8744d717930efe4d6896db63f11.nq.gz
    ├── 0241f13214bb3035ddced33ba19c10245c1327ca.nq.gz
    ├── 024cc3bdda2667950487ea71b8252907eabf92de.nq.gz
    ├── 024d22b1521f877d159a79142d890e9fb5e6c240.nq.gz
    ├── 024e931d3a786688534b8062755ed02a12cfd720.nq.gz
    ├── 02544f1d71ba8e819118ec1ca89150c6d6414af6.nq.gz
    ├── 0256131b8f230363fab1d37a6481b78d1063f5ad.nq.gz
    ├── 02848726182c7a7b19402ffe70b1ad6878bf06bd.nq.gz
    ├── 028c8d9d95bc07bb0a7903ff42197b1a9231f5e6.nq.gz
    ├── 029e2e9475896c009d8d1e1f6721ad9b0fcd4fc2.nq.gz
    ├── 029f4bd6ad2aa521fa309eaf44edeb2480731501.nq.gz
    ├── 02ad1242e7775281ca1cd9819b06b7b0ebd15287.nq.gz
    ├── 02b500221da0ed70bf390c547f79559058c59f67.nq.gz
    ├── 02b7462664e82f2e16cf343e48c4e10272e5f899.nq.gz
    ├── 02c7d2f7505bc2d3e59fec5f98591acd229c04a5.nq.gz
    ├── 02d5fef070d0873e6bd4293577bc8b6fda88de0b.nq.gz
    ├── 02f099658ab5495926ccb0dbcd1927d467cf642c.nq.gz
    ├── 02f9275454b8d614613a5bd899a95db85afb31c1.nq.gz
    ├── 03058c5d21caef83962efec619466fb8394c619c.nq.gz
    ├── 0311788a62f6de2b20f7c2d9134996a960a85bba.nq.gz
    ├── 03118ad68a4096eff44bd049cabdb5bd33215e9a.nq.gz
    ├── 031f714d232912701e48ef037523c45e45edb710.nq.gz
    ├── 0321e204542fa63346715c3ad91d2d36b048a503.nq.gz
    ├── 03224bbec7245384ab6af27f6558437861ffdcf5.nq.gz
    ├── 03272e5cf1fc0b3d2aaafc3e33c1d214080826a5.nq.gz
    ├── 033b2a1177ef25e920b095bafecd15bd8156b1b7.nq.gz
    ├── 035e2dd18d0786b39a6ca667f16d2305127f308e.nq.gz
    ├── 0365d0cd087326aa83c780c917d28d3b00aea839.nq.gz
    ├── 03663c2879b80ef5c1f475e272278f61bf7be027.nq.gz
    ├── 037ae80e3503d16637f2edf66e35f1defb95a604.nq.gz
    ├── 037c26da4aa94d882cd8060f1dedccb566d9b025.nq.gz
    ├── 037e9f46744caf43c33fccd449c2d01ceae67b86.nq.gz
    ├── 038972e88411f34898a00118087c3ab5f5bbc25f.nq.gz
    ├── 038f721e3a33a85c7447608c593330653e8fb33d.nq.gz
    ├── 03aca2ebbead64713e8853d02ad5ec1cad4f1fa0.nq.gz
    ├── 03c205bf988675fe04a93e1ea2dc145916c36f86.nq.gz
    ├── 03d5d13cfa9bec6660567511c075ac00b91677f2.nq.gz
    ├── 03e446ea68f15897afc68802498dd258fbaa844f.nq.gz
    ├── 03e7c9970c083119b06310777c09abcae8b2b4c1.nq.gz
    ├── 03e96f05baf3e56114c18814485666273adf1a18.nq.gz
    ├── 03f185eb88f073dd8e9b55374143bb2f0c576458.nq.gz
    ├── 03f5046feb19010f86eae2d4fd2c5348706f96af.nq.gz
    ├── 03f8653c56c754f17680c14cdbfde4de3d76298e.nq.gz
    ├── 03f994c68b8904b2824f6dbadd2107f44092e083.nq.gz
    ├── 04005eec737fdff63184d8f63030df60ad7b0e17.nq.gz
    ├── 04016d53f34c8f22ed687b45f12e2daf5a3a2e2a.nq.gz
    ├── 040e2d0897f648377de2abacf7f17afe4764e4ff.nq.gz
    ├── 04200100967ac489d4c116dda826551ee5859a10.nq.gz
    ├── 042c9958b18572d0654e32788292e2004f1b6733.nq.gz
    ├── 042ca7e14271224239fab280225bd6d5f46cc19e.nq.gz
    ├── 044688dac2ae588114cb4fa2391baf1ed2cb615c.nq.gz
    ├── 044a8cac7c78074ccdf63368ae927486d614ebc5.nq.gz
    ├── 04511b75386952cecbf3687e062b12678213c7cb.nq.gz
    ├── 045a182cb1a10acabd1404d28d1f29ff0d3328a3.nq.gz
    ├── 045aaa8dac48e9278d6f9f63fb2e7fc176b05ba9.nq.gz
    ├── 04608772e66ce56dddb386af8ac2310eda3925df.nq.gz
    ├── 04667ffd191820ee98eef2317b5c2b4e16349783.nq.gz
    ├── 046d017fd35c7fcfd75e4ea837e7f1bf8578367b.nq.gz
    ├── 046d29524b43df7617d224c7987326e5e01f9ec0.nq.gz
    ├── 047ad4a95fca11dd969baec36e8186ab4d740cc1.nq.gz
    ├── 048801128d811597fec858b4d269a04fc620aa04.nq.gz
    ├── 048b0a9f62393929bf7de390154858c09e307a02.nq.gz
    ├── 0493b0fde2974330224fb75b1b5053751164943b.nq.gz
    ├── 0494b9cfebdc1ebbc9fab6cade56f32b6d85c6c6.nq.gz
    ├── 049630ffb63b9abf69afe08d1629caaa3c74fd9d.nq.gz
    ├── 049a12df4b7ecc1473761c1b14f7b986ab3b8956.nq.gz
    ├── 04a45551e033af9331d2f79e337760097576fb89.nq.gz
    ├── 04ca49d4db923b3cf13d21377e1f0592118bc6f9.nq.gz
    ├── 04d71b7ee5add284d67c2b3b8dadfe3f42393978.nq.gz
    ├── 04da984f657273cce9a4a6304c93a81e31514cbf.nq.gz
    ├── 04df756f0294833a17ba5d595dc8c8b7bedee4fc.nq.gz
    ├── 04fd3ec1103fc7fd9446580d779aa0ef54d56992.nq.gz
    ├── 052d48f36ae15c164fcd8ab6635fcb0cc10f2836.nq.gz
    ├── 052dcc8c027086a43497f9a1287df20349f7a825.nq.gz
    ├── 053af0078f6c02357e696e8d25006c570149fab3.nq.gz
    ├── 05489e65b1b4158369fd18ddbcd8b32ba42d274e.nq.gz
    ├── 0559608f467a19089ed835f68cb51323e90d0e9b.nq.gz
    ├── 0561c952ed8c21220caa450549647a6d63c8ea71.nq.gz
    ├── 0564601b31569deba111b2907c18ae201be92a86.nq.gz
    ├── 056e1f4a681b29822b2189a5a2d2198401119d94.nq.gz
    ├── 057eb86d9e789636608c85471520b9705379e877.nq.gz
    ├── 05852b93c5bf0b7a60fedd46a76a82bc42b41108.nq.gz
    ├── 0595e9cec05d5f6c5eac69c49d35e42639f0cd7e.nq.gz
    ├── 059d46163ca36ba1be66e990f9f2f31af1f251b8.nq.gz
    ├── 059f069e605afe74bee5fa530baa14763ebcfe15.nq.gz
    ├── 05a56cc99a841d8b5d96787980f7659cf9449ffa.nq.gz
    ├── 05a57462af7f8bbd12be579f3d9382a332d25d6b.nq.gz
    ├── 05a7b195ed9dc0301322b6a887b37a69736e77aa.nq.gz
    ├── 05b767936f991b6643e93c8b325ea0033515950c.nq.gz
    ├── 05be0c4c27cde79e32d762d82fe41de41ed0ef39.nq.gz
    ├── 05ccbfae981e81db003735e33fd18f230b314b8c.nq.gz
    ├── 05d98d13a73b130db5c855ee86d6bd4d2ec911c2.nq.gz
    ├── 05dd3175c1c6c2997226d5ffc0f04370b52b9b5d.nq.gz
    ├── 05ddfee21ac3597b93a8ba8c0e35a1a68c712e80.nq.gz
    ├── 0605842a7e1c5fd9c71ac0f97faad788e5b73652.nq.gz
    ├── 0636213ae69597b6da9624a01175586545ca0281.nq.gz
    ├── 064040ef37d551bf71e94d2dd96155990aafb6b5.nq.gz
    ├── 064a7695a960ec53c3863015cd525dd65182859c.nq.gz
    ├── 0650530a13a743eb7a9d02fc947098010b8690d8.nq.gz
    ├── 0652f4a9105f046ac10a417ed718fc80ffc41508.nq.gz
    ├── 065ab3a7ca226009e7ba8beed5fb3800b893c3b7.nq.gz
    ├── 06655ced4007425dcea19369df916cb65aa89cc7.nq.gz
    ├── 06705c53da7818075ffb6969998d3070586cf56a.nq.gz
    ├── 0674de4fa0cef975b509a3d6c1ce834c6ba17534.nq.gz
    ├── 0679424cc63c325d20d5379fad44b9ecaa570964.nq.gz
    ├── 068538538313dd9ac8b7733c012307bfde2d70ae.nq.gz
    ├── 06873c97b8322a993b98ac8bc1645e801931f4d2.nq.gz
    ├── 0694f75a60c043fe03020b4e238e0b15e960d4fd.nq.gz
    ├── 0698962d20214d782e155d712db56975b2c9066b.nq.gz
    ├── 06b2dd8035dadd3fff783b6b3a03f4b85e198ea3.nq.gz
    ├── 06b8890153f72884a60dabd8f4b328a0c01c0927.nq.gz
    ├── 06cc8dc2723c677e3653e0e59541a2a24562ed2d.nq.gz
    ├── 06deed51ba275744f8e7abced381c29b0a52db0b.nq.gz
    ├── 06e137ca51cb4ae6a50d84f8d640ad63d16b17ef.nq.gz
    ├── 06ebded62a1357b6ee8a1e08d557575937bed250.nq.gz
    ├── 071991d5f9630bf15c89ef543879bdaaf740909e.nq.gz
    ├── 0723ec69cefa2c7633c122c5aa958186ff536237.nq.gz
    ├── 072aaeb13cba6728b33cb5787725cca73311d8a9.nq.gz
    ├── 073bc3bc0cd33d89416eda1cbbaebca55eab00b3.nq.gz
    ├── 07400f8662fb41ff387fd26769b0340330fbf454.nq.gz
    ├── 07596383109ab3fefa67638b01fda8733766b3a3.nq.gz
    ├── 075e2a96ef171f2ff1b703da3b0d7e16388f4e4a.nq.gz
    ├── 07608bb0c1a2a3153254eb3aed4844127d21f6fd.nq.gz
    ├── 0775cdea2f0a59035cf8c2a9ff783fef5be044fc.nq.gz
    ├── 077b015befcd52681ce703eff3cb5ab44dbf94b1.nq.gz
    ├── 07866f0294cf12ea7fbfceba6f15219f91c60e46.nq.gz
    ├── 0792ee4ca3cc0b217a9737175c652c0d8251f673.nq.gz
    ├── 079663cc98ba9527a9e9e1d349f925a83df96056.nq.gz
    ├── 0799eeb2bbb5a6f36f1513e0ddfdbd8bd22a9d87.nq.gz
    ├── 07c9ae6d1b309acfb99c16837c3c88a1e41b25fc.nq.gz
    ├── 07cbb72858a1da3a0df558b206cc6beb6c3d4194.nq.gz
    ├── 07ea820443f639300753cccdf8262a5e3be0e2e3.nq.gz
    ├── 07ffb0ae1fcbf564b480c09cede943f061023600.nq.gz
    ├── 081afe24cab93863a4dd91b75c56b3d80655cbe0.nq.gz
    └── 081e9e7cd71d5c8b1147e93835ad5271f66c25c2.nq.gz

2 directories, 200 files
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

[apache/logging-log4j2](https://github.com/apache/logging-log4j2)

---
*Parsed on 2026-03-30 by [repolex](https://repolex.ai)*
