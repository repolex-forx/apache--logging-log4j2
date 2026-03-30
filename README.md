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
├── aggregate
│   ├── ast
│   │   ├── 08aa0aadff27ee1e413f609c939e683855e28033.nq.gz
│   │   ├── 090bd032c061d3b63232629fdb469285ae20ffc8.nq.gz
│   │   ├── 2cbca767c1fa84d45aba4776797faabd9a6bb4bd.nq.gz
│   │   ├── 367d98abe22e201da8968bc167271c7aafce4cb7.nq.gz
│   │   ├── 38164ce047a4f15f8f0a3b39cbfbfea861cc1b9d.nq.gz
│   │   ├── 3fedfacd59affcda9fcbb1125a3b7e057000b7c1.nq.gz
│   │   ├── 83be65b09d3b8f764b65f81c9339b6b5c813a1ff.nq.gz
│   │   └── aeec48706fccd4892ba023593075aa549bc558f2.nq.gz
│   ├── lsp
│   │   ├── 08aa0aadff27ee1e413f609c939e683855e28033.nq.gz
│   │   ├── 090bd032c061d3b63232629fdb469285ae20ffc8.nq.gz
│   │   ├── 2cbca767c1fa84d45aba4776797faabd9a6bb4bd.nq.gz
│   │   ├── 367d98abe22e201da8968bc167271c7aafce4cb7.nq.gz
│   │   ├── 38164ce047a4f15f8f0a3b39cbfbfea861cc1b9d.nq.gz
│   │   ├── 3fedfacd59affcda9fcbb1125a3b7e057000b7c1.nq.gz
│   │   ├── 83be65b09d3b8f764b65f81c9339b6b5c813a1ff.nq.gz
│   │   └── aeec48706fccd4892ba023593075aa549bc558f2.nq.gz
│   └── repolex
│       ├── 08aa0aadff27ee1e413f609c939e683855e28033.nq.gz
│       ├── 090bd032c061d3b63232629fdb469285ae20ffc8.nq.gz
│       ├── 2cbca767c1fa84d45aba4776797faabd9a6bb4bd.nq.gz
│       ├── 367d98abe22e201da8968bc167271c7aafce4cb7.nq.gz
│       ├── 38164ce047a4f15f8f0a3b39cbfbfea861cc1b9d.nq.gz
│       ├── 3fedfacd59affcda9fcbb1125a3b7e057000b7c1.nq.gz
│       ├── 83be65b09d3b8f764b65f81c9339b6b5c813a1ff.nq.gz
│       └── aeec48706fccd4892ba023593075aa549bc558f2.nq.gz
└── blob
    ├── 0013946589ed63750f9a276895c12d2fb5ef4d19.nq.gz
    ├── 00144e2e29305891fe691349433e2dff31808e25.nq.gz
    ├── 001ca4142b8683bbb99e9ab89e87d461a5cb6cfa.nq.gz
    ├── 001d0482acaa335e2acfdcab3f344382517e3490.nq.gz
    ├── 0027be49454c300391749030f782de3de787256c.nq.gz
    ├── 002eb3faa45c0138c2c6fa2c161d3896e2670648.nq.gz
    ├── 0036a1f17a996a9128c031d53e755239caad6017.nq.gz
    ├── 0036fcaf40f8e27e42e17e21bcaa173320b6a323.nq.gz
    ├── 0038fec6bb4509cec4b7edab51b7c1e2c2831b76.nq.gz
    ├── 0046342813042590d33c58b72f133362379f8387.nq.gz
    ├── 004aed812e19c81e6ba64cf64a1a81409ca88884.nq.gz
    ├── 00518fa03819b6c60ca506c69aea54ba00bed607.nq.gz
    ├── 00546a0e61723623d912a2e5177d07d8ff5db6ec.nq.gz
    ├── 005f64f942e2699862afebef26575764d64c182d.nq.gz
    ├── 006032325ce4c7c49f320d16a7826eda29f0f874.nq.gz
    ├── 00639140bb01dd93da488d1cd42954fd5f51c7b5.nq.gz
    ├── 0068619c70c5bcccc6fbaa02c9974923d558b485.nq.gz
    ├── 0075c6568b951560f7b07c7809d67b58fe6504ad.nq.gz
    ├── 007f4fad5d508bffd36fa04b5421cf74b3647029.nq.gz
    ├── 008200b18c5bd01e25fd18feb0cd774cdff7bde1.nq.gz
    ├── 008cce48be55779626fd9781704ca5295a3b74ae.nq.gz
    ├── 00901ba07438afba428302d5d4b8709ea70af084.nq.gz
    ├── 00969b1410fd9347f3abac248f8fcb6e446712fc.nq.gz
    ├── 009d83dafecbc38ad723b51d7391fbcc23f11461.nq.gz
    ├── 00a9a1a94b94f402168924a4e5a57d44421ba497.nq.gz
    ├── 00ab9844a42050317fe09ff272d499e874615e65.nq.gz
    ├── 00b013af94ae2c85334ee63c9905f794784ab82a.nq.gz
    ├── 00b20568e272bfe6a7e2144d61cd7449b6d75381.nq.gz
    ├── 00b31613e878417f62aedd8bade173de812d5392.nq.gz
    ├── 00b3f7131a2eecd3229f83b54b620fd2b503257d.nq.gz
    ├── 00b41efa9d50fe1aedfce8407c44ed6c3650536b.nq.gz
    ├── 00b71aba450fd09b68404ccb6600068279e7afe8.nq.gz
    ├── 00b9834f4f7b400b51ce03802832d3b2c6b44740.nq.gz
    ├── 00c0ce29208eb570c842a5dafb736587d94c006b.nq.gz
    ├── 00c3c2411adb9f1028e8a75688d447e812fdb172.nq.gz
    ├── 00c4f42743c3296ef79b89e04fefbb564800efef.nq.gz
    ├── 00cdd55b766b901591acc11c879d2449f960d820.nq.gz
    ├── 00d0e1293ff066a1260b7d262c4c339fdab32996.nq.gz
    ├── 00d13d2a92b9420f1ee209f1b049e4ae0b62d36a.nq.gz
    ├── 00d6534465c0355c14382bce9e3e53ce0a111b49.nq.gz
    ├── 00d6aa4ddcc8e82553d40797f3fd6a3a98533568.nq.gz
    ├── 00e1af057fcbf5752a1b8dce0e80f8a252b99757.nq.gz
    ├── 00e7c0135893445cfd0d530801d8dc67c67ac497.nq.gz
    ├── 00f8ba2da3f6ddb1aeb1da2358676f2724eee33f.nq.gz
    ├── 00fa79b85f97002201fa972555ed333bdac99468.nq.gz
    ├── 00fdf24af7a66a8b00353521c9d13d85103f6f98.nq.gz
    ├── 01077d782d7f138788daa19aa1c06f9de91bb3f7.nq.gz
    ├── 0109961e1ad316fb46142545ce236f62a94f7429.nq.gz
    ├── 0110c66a5432b4051f770cff88da8ee4bde38811.nq.gz
    ├── 011c3bd63f4eff00d49cd597a17c50a9818021f6.nq.gz
    ├── 011cef594b364f6b6a0b463d576d532dbdfd6c6a.nq.gz
    ├── 011d3633c27d8a4b405d59b928aafcdfd16c0421.nq.gz
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
    ├── 0172e546a7ca3991bcf85b6aedabd28dc6206ba1.nq.gz
    ├── 01874dbbe2fb5da3bdcb8607f5257861bb978f84.nq.gz
    ├── 0193245834691c9a2b4e2e2ac489ffede433df30.nq.gz
    ├── 0199eed57dd7b63a9fed2cd08cafe4c5a60fdf84.nq.gz
    ├── 01a2291e2f90a94a0c8c92ba556fd593ec042f2b.nq.gz
    ├── 01aaa6539d18e469bf1aace6906e4022f13e71ac.nq.gz
    ├── 01ab6cdc34aee9873b7787ce8791c8104b7b7ef4.nq.gz
    ├── 01ac986fddebd4cce26679290596a9c48df673db.nq.gz
    ├── 01ba893432a537b03be84030b46c1c72a1491b7e.nq.gz
    ├── 01c094b13b41aa3946d14a08a7905ff908679f68.nq.gz
    ├── 01c28d56f98146b818825052f9b08ace9f157b5c.nq.gz
    ├── 01cd966c084b50bfaa5b190b5550bf181418028e.nq.gz
    ├── 01db40aac3ef5311441290a4487341b7e49169aa.nq.gz
    ├── 01e09ab77d853c6bc551d92ce954ddc8324607a1.nq.gz
    ├── 01e56ecf58e986fa0d02ca9f7f46399eba20d11a.nq.gz
    ├── 01e80e76fb26529744653912630380c39d49639b.nq.gz
    ├── 01eccd43e64e98325734c6f62c5dde00aeaead3a.nq.gz
    ├── 01f28fe97ffce8b55eb262e53f75821ba18569dc.nq.gz
    ├── 01f67048266e885907ed76af413668f6317f76ff.nq.gz
    ├── 01f8c96cfd5713c491094ae9e4888cb93d1b6fd1.nq.gz
    ├── 02060565ee8cf6e4eb0c065fb54ea552728e517a.nq.gz
    ├── 020c10f3d7113f8c67835996b3fa4ae8426504fe.nq.gz
    ├── 0217c7fae6a2089130cd9d365755bad328caf152.nq.gz
    ├── 021f00e6c5d5367670416f791ca67c754a1dce99.nq.gz
    ├── 023163fd56b611343307e6292215504d6092755e.nq.gz
    ├── 023337e9af5bb75d0ae666debb433e56bb86538b.nq.gz
    ├── 0239b2908db7e8744d717930efe4d6896db63f11.nq.gz
    ├── 0239cb15fa21862df91a3c62aad5fa59bb83ad95.nq.gz
    ├── 023fb7c42f6fc8ba47e460945a6507b9cbdf8b37.nq.gz
    ├── 0241f13214bb3035ddced33ba19c10245c1327ca.nq.gz
    ├── 024cc3bdda2667950487ea71b8252907eabf92de.nq.gz
    ├── 024d22b1521f877d159a79142d890e9fb5e6c240.nq.gz
    ├── 024e931d3a786688534b8062755ed02a12cfd720.nq.gz
    ├── 02544f1d71ba8e819118ec1ca89150c6d6414af6.nq.gz
    ├── 0256131b8f230363fab1d37a6481b78d1063f5ad.nq.gz
    ├── 025c2a8f7dbbd12248bf9989669780a96c4b8528.nq.gz
    ├── 025f32d8e0529a8524567906db2e044a1c0890a9.nq.gz
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
    ├── 030da49b4392ac02eb33affa12821b47e9bf766d.nq.gz
    ├── 0311788a62f6de2b20f7c2d9134996a960a85bba.nq.gz
    ├── 03118ad68a4096eff44bd049cabdb5bd33215e9a.nq.gz
    ├── 031a3bad2741f27fd08ff0f36dcd93715ae6a732.nq.gz
    ├── 031f5fb4af1465d0ce881868b527c8b3425d6dd1.nq.gz
    ├── 031f714d232912701e48ef037523c45e45edb710.nq.gz
    ├── 0321e204542fa63346715c3ad91d2d36b048a503.nq.gz
    ├── 03224bbec7245384ab6af27f6558437861ffdcf5.nq.gz
    ├── 03272e5cf1fc0b3d2aaafc3e33c1d214080826a5.nq.gz
    ├── 032f34fa8df07a43a9b526dfb6c1cb588395719d.nq.gz
    ├── 033b2a1177ef25e920b095bafecd15bd8156b1b7.nq.gz
    ├── 035a73f6a0461d23a56d58cb5b2b1bcda621d830.nq.gz
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
    ├── 03e180e920fbb8afcd615923023be7d75cf61ce9.nq.gz
    ├── 03e446ea68f15897afc68802498dd258fbaa844f.nq.gz
    ├── 03e7c9970c083119b06310777c09abcae8b2b4c1.nq.gz
    ├── 03e96f05baf3e56114c18814485666273adf1a18.nq.gz
    ├── 03eff035ac92abf8e9f1b52b0faaef6c7c3d4b97.nq.gz
    ├── 03f185eb88f073dd8e9b55374143bb2f0c576458.nq.gz
    ├── 03f5046feb19010f86eae2d4fd2c5348706f96af.nq.gz
    ├── 03f8653c56c754f17680c14cdbfde4de3d76298e.nq.gz
    ├── 03f994c68b8904b2824f6dbadd2107f44092e083.nq.gz
    ├── 04005eec737fdff63184d8f63030df60ad7b0e17.nq.gz
    ├── 04016d53f34c8f22ed687b45f12e2daf5a3a2e2a.nq.gz
    ├── 0403f49389b7e11ef2ed93dda2fc7981c43ff5f9.nq.gz
    ├── 0405ce060eeed1c758ee3350a15fdc2f9c0bb5bf.nq.gz
    ├── 040ae6ac27b1544cda8d67c8672137c7b873e50f.nq.gz
    ├── 040e2d0897f648377de2abacf7f17afe4764e4ff.nq.gz
    ├── 04200100967ac489d4c116dda826551ee5859a10.nq.gz
    ├── 042ae00bf0aeb6bf86c35e1d4cf0cd3a1abc355f.nq.gz
    ├── 042c9958b18572d0654e32788292e2004f1b6733.nq.gz
    ├── 042ca7e14271224239fab280225bd6d5f46cc19e.nq.gz
    ├── 044688dac2ae588114cb4fa2391baf1ed2cb615c.nq.gz
    ├── 044a621e5326ed409365f7c02c817b265191cc54.nq.gz
    ├── 044a8cac7c78074ccdf63368ae927486d614ebc5.nq.gz
    ├── 044f3edd7fb49732b337d1643ee2ae86760b5f50.nq.gz
    ├── 04511b75386952cecbf3687e062b12678213c7cb.nq.gz
    ├── 045a182cb1a10acabd1404d28d1f29ff0d3328a3.nq.gz
    ├── 045aaa8dac48e9278d6f9f63fb2e7fc176b05ba9.nq.gz
    ├── 04608772e66ce56dddb386af8ac2310eda3925df.nq.gz
    ├── 046106f7490438fcf92266a837ab037579645b28.nq.gz
    ├── 04667ffd191820ee98eef2317b5c2b4e16349783.nq.gz
    ├── 046d017fd35c7fcfd75e4ea837e7f1bf8578367b.nq.gz
    ├── 046d29524b43df7617d224c7987326e5e01f9ec0.nq.gz
    ├── 047ad4a95fca11dd969baec36e8186ab4d740cc1.nq.gz
    ├── 047edb1806c8ac6d107bbff73d5ee9c7267f8848.nq.gz
    ├── 048801128d811597fec858b4d269a04fc620aa04.nq.gz
    ├── 048b0a9f62393929bf7de390154858c09e307a02.nq.gz
    ├── 0493b0fde2974330224fb75b1b5053751164943b.nq.gz
    ├── 0494b9cfebdc1ebbc9fab6cade56f32b6d85c6c6.nq.gz
    ├── 049630ffb63b9abf69afe08d1629caaa3c74fd9d.nq.gz
    ├── 049a12df4b7ecc1473761c1b14f7b986ab3b8956.nq.gz
    ├── 04a45551e033af9331d2f79e337760097576fb89.nq.gz
    ├── 04ca49d4db923b3cf13d21377e1f0592118bc6f9.nq.gz
    └── 04d71b7ee5add284d67c2b3b8dadfe3f42393978.nq.gz

6 directories, 200 files
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
