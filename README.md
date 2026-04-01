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
│   │   ├── 3f7346ec9c37b0df39e996663bba21be6a7e6813.nq.gz
│   │   ├── 3fedfacd59affcda9fcbb1125a3b7e057000b7c1.nq.gz
│   │   ├── 83be65b09d3b8f764b65f81c9339b6b5c813a1ff.nq.gz
│   │   ├── aeec48706fccd4892ba023593075aa549bc558f2.nq.gz
│   │   └── f0d368279d902bd4ea0053f08cc1a61b0606ab2e.nq.gz
│   ├── lsp
│   │   ├── 08aa0aadff27ee1e413f609c939e683855e28033.nq.gz
│   │   ├── 090bd032c061d3b63232629fdb469285ae20ffc8.nq.gz
│   │   ├── 2cbca767c1fa84d45aba4776797faabd9a6bb4bd.nq.gz
│   │   ├── 367d98abe22e201da8968bc167271c7aafce4cb7.nq.gz
│   │   ├── 38164ce047a4f15f8f0a3b39cbfbfea861cc1b9d.nq.gz
│   │   ├── 3f7346ec9c37b0df39e996663bba21be6a7e6813.nq.gz
│   │   ├── 3fedfacd59affcda9fcbb1125a3b7e057000b7c1.nq.gz
│   │   ├── 83be65b09d3b8f764b65f81c9339b6b5c813a1ff.nq.gz
│   │   ├── aeec48706fccd4892ba023593075aa549bc558f2.nq.gz
│   │   └── f0d368279d902bd4ea0053f08cc1a61b0606ab2e.nq.gz
│   └── repolex
│       ├── 08aa0aadff27ee1e413f609c939e683855e28033.nq.gz
│       ├── 090bd032c061d3b63232629fdb469285ae20ffc8.nq.gz
│       ├── 2cbca767c1fa84d45aba4776797faabd9a6bb4bd.nq.gz
│       ├── 367d98abe22e201da8968bc167271c7aafce4cb7.nq.gz
│       ├── 38164ce047a4f15f8f0a3b39cbfbfea861cc1b9d.nq.gz
│       ├── 3f7346ec9c37b0df39e996663bba21be6a7e6813.nq.gz
│       ├── 3fedfacd59affcda9fcbb1125a3b7e057000b7c1.nq.gz
│       ├── 83be65b09d3b8f764b65f81c9339b6b5c813a1ff.nq.gz
│       ├── aeec48706fccd4892ba023593075aa549bc558f2.nq.gz
│       └── f0d368279d902bd4ea0053f08cc1a61b0606ab2e.nq.gz
└── blob
    ├── 000aa11efb95d43c642b920a557d7de02b6afc9a.nq.gz
    ├── 000aaa724eebc44384ba9210f99e2025a60384d6.nq.gz
    ├── 0013946589ed63750f9a276895c12d2fb5ef4d19.nq.gz
    ├── 00144e2e29305891fe691349433e2dff31808e25.nq.gz
    ├── 001bc642f81565688495840eb216e71ffba98e5a.nq.gz
    ├── 001ca4142b8683bbb99e9ab89e87d461a5cb6cfa.nq.gz
    ├── 001d0482acaa335e2acfdcab3f344382517e3490.nq.gz
    ├── 0020c057e3b1eb1d13aab7dfa9667ac552a32325.nq.gz
    ├── 0022b4007d40f9fd8fa4783fdda41aa24b9b968d.nq.gz
    ├── 0027be49454c300391749030f782de3de787256c.nq.gz
    ├── 002eb3faa45c0138c2c6fa2c161d3896e2670648.nq.gz
    ├── 0036a1f17a996a9128c031d53e755239caad6017.nq.gz
    ├── 0036fcaf40f8e27e42e17e21bcaa173320b6a323.nq.gz
    ├── 0038fec6bb4509cec4b7edab51b7c1e2c2831b76.nq.gz
    ├── 003b84e48c78abad45080d8702c593bc04d8a306.nq.gz
    ├── 0046342813042590d33c58b72f133362379f8387.nq.gz
    ├── 0046a62f6e23a018bd96bf2276bde6b694177a13.nq.gz
    ├── 004aed812e19c81e6ba64cf64a1a81409ca88884.nq.gz
    ├── 00518fa03819b6c60ca506c69aea54ba00bed607.nq.gz
    ├── 00546a0e61723623d912a2e5177d07d8ff5db6ec.nq.gz
    ├── 0057b989434d3906e8b3e01118559e0c465cba73.nq.gz
    ├── 005f64f942e2699862afebef26575764d64c182d.nq.gz
    ├── 006032325ce4c7c49f320d16a7826eda29f0f874.nq.gz
    ├── 00639140bb01dd93da488d1cd42954fd5f51c7b5.nq.gz
    ├── 006558549bec89c0b3d622578ce10f4565338da5.nq.gz
    ├── 0068619c70c5bcccc6fbaa02c9974923d558b485.nq.gz
    ├── 007248681a9bb4095a3747c92c9cdd5062f16cff.nq.gz
    ├── 0075c6568b951560f7b07c7809d67b58fe6504ad.nq.gz
    ├── 0079fbc2d798c289d9801b66007400fc4f2a97b7.nq.gz
    ├── 007f4fad5d508bffd36fa04b5421cf74b3647029.nq.gz
    ├── 00807ece85030a87c0a38821d4574431dc1d7957.nq.gz
    ├── 008200b18c5bd01e25fd18feb0cd774cdff7bde1.nq.gz
    ├── 008cce48be55779626fd9781704ca5295a3b74ae.nq.gz
    ├── 00901ba07438afba428302d5d4b8709ea70af084.nq.gz
    ├── 00969b1410fd9347f3abac248f8fcb6e446712fc.nq.gz
    ├── 0098057a9a8ad374113280da09f3b69ce27721d7.nq.gz
    ├── 009d5a62cb18e91a0cd7acd3ed94b564880e417f.nq.gz
    ├── 009d83dafecbc38ad723b51d7391fbcc23f11461.nq.gz
    ├── 00a6042a9e1f31714469a8fa4e339f6358c6d239.nq.gz
    ├── 00a91d139fecc945168642595912fe1c8e282252.nq.gz
    ├── 00a9a1a94b94f402168924a4e5a57d44421ba497.nq.gz
    ├── 00ab9844a42050317fe09ff272d499e874615e65.nq.gz
    ├── 00ae7c6b659c4234f7fad37cdaea463790e8fe77.nq.gz
    ├── 00b013af94ae2c85334ee63c9905f794784ab82a.nq.gz
    ├── 00b20568e272bfe6a7e2144d61cd7449b6d75381.nq.gz
    ├── 00b31613e878417f62aedd8bade173de812d5392.nq.gz
    ├── 00b3f7131a2eecd3229f83b54b620fd2b503257d.nq.gz
    ├── 00b41efa9d50fe1aedfce8407c44ed6c3650536b.nq.gz
    ├── 00b71aba450fd09b68404ccb6600068279e7afe8.nq.gz
    ├── 00b9834f4f7b400b51ce03802832d3b2c6b44740.nq.gz
    ├── 00baba787bb08456f320e8ee5fe45f619d532301.nq.gz
    ├── 00c0ce29208eb570c842a5dafb736587d94c006b.nq.gz
    ├── 00c3c2411adb9f1028e8a75688d447e812fdb172.nq.gz
    ├── 00c4f42743c3296ef79b89e04fefbb564800efef.nq.gz
    ├── 00cd556e2145916483e993132b87e25007eeac67.nq.gz
    ├── 00cdd55b766b901591acc11c879d2449f960d820.nq.gz
    ├── 00cf3088b0e5e2b47eeeb7512355998b9ca3819f.nq.gz
    ├── 00d0e1293ff066a1260b7d262c4c339fdab32996.nq.gz
    ├── 00d13d2a92b9420f1ee209f1b049e4ae0b62d36a.nq.gz
    ├── 00d6534465c0355c14382bce9e3e53ce0a111b49.nq.gz
    ├── 00d6aa4ddcc8e82553d40797f3fd6a3a98533568.nq.gz
    ├── 00e1af057fcbf5752a1b8dce0e80f8a252b99757.nq.gz
    ├── 00e7c0135893445cfd0d530801d8dc67c67ac497.nq.gz
    ├── 00e97f7d4d9d2a892ff27b7f04e9e5c117a71c44.nq.gz
    ├── 00f8ba2da3f6ddb1aeb1da2358676f2724eee33f.nq.gz
    ├── 00fa79b85f97002201fa972555ed333bdac99468.nq.gz
    ├── 00fdf24af7a66a8b00353521c9d13d85103f6f98.nq.gz
    ├── 00fe5d33f2c2ee2d7629ee4e0ac3638bb73fbf6c.nq.gz
    ├── 01016c1f57c7a80376faf13c94479a3a6c2adaf2.nq.gz
    ├── 01025b4bffa1ee059248602ed53b9ea887d626cd.nq.gz
    ├── 0105f3ccb85232d4c8b21ad7710ac20dd3847bbf.nq.gz
    ├── 01077d782d7f138788daa19aa1c06f9de91bb3f7.nq.gz
    ├── 0109961e1ad316fb46142545ce236f62a94f7429.nq.gz
    ├── 0110c66a5432b4051f770cff88da8ee4bde38811.nq.gz
    ├── 011c3bd63f4eff00d49cd597a17c50a9818021f6.nq.gz
    ├── 011cef594b364f6b6a0b463d576d532dbdfd6c6a.nq.gz
    ├── 011d3633c27d8a4b405d59b928aafcdfd16c0421.nq.gz
    ├── 011ee61951765d51316cb5f58ccf53c864531b7c.nq.gz
    ├── 0121fbe931caa59e6b4228fa664ada82b07c0e29.nq.gz
    ├── 0123ae854574dd10cc2313c9190ac8f4faf9e85a.nq.gz
    ├── 0127ed20d545245c1ef294e03e93ec57e1a5fdc3.nq.gz
    ├── 01296f2f1b9b79ad2eb9334afc732e46a6b2b5eb.nq.gz
    ├── 012c2baf9e5aa283507838d7fcc8916b61fb8127.nq.gz
    ├── 012dccae0d85bfe38bd2422e011b4bb8ba24dcf8.nq.gz
    ├── 0134dac4794bd7f7d1a903bb2ce2262553c1d17e.nq.gz
    ├── 0138cead6e30e2a88e77331d859ab5ecc96ca5cb.nq.gz
    ├── 013bd35e1ec4a60535a9fd7c0dd8d18750045130.nq.gz
    ├── 0141c60922c75c8b8c1d64436b3748797c738ef0.nq.gz
    ├── 014a1ed17a674e185ca13aeb32b9ac82e7befadf.nq.gz
    ├── 014a9711dd246d443ca98bbc602c5d9ab3ae7665.nq.gz
    ├── 014aa8c4fdcf2aa637930a37182a0daa5e6ed817.nq.gz
    ├── 014d77585d85a672326ffbcc7d02a09e10fb1108.nq.gz
    ├── 0152a9b1f078be7d77b26d9d1a02320df941a5e6.nq.gz
    ├── 016548752b70509063908c4b6d0f6f3646f2c206.nq.gz
    ├── 0165eb66b07d85c990acb1cfcab3252cd2536853.nq.gz
    ├── 016898d925e121d76af70d4dc5737ccff089c8d9.nq.gz
    ├── 0172e546a7ca3991bcf85b6aedabd28dc6206ba1.nq.gz
    ├── 017423ffb754ed4c31edc66151e1b411f168217a.nq.gz
    ├── 01874dbbe2fb5da3bdcb8607f5257861bb978f84.nq.gz
    ├── 0193245834691c9a2b4e2e2ac489ffede433df30.nq.gz
    ├── 0199eed57dd7b63a9fed2cd08cafe4c5a60fdf84.nq.gz
    ├── 01a2291e2f90a94a0c8c92ba556fd593ec042f2b.nq.gz
    ├── 01a38b189c219817f54b2516d0acb962ecb6dba7.nq.gz
    ├── 01aaa6539d18e469bf1aace6906e4022f13e71ac.nq.gz
    ├── 01ab6cdc34aee9873b7787ce8791c8104b7b7ef4.nq.gz
    ├── 01ac986fddebd4cce26679290596a9c48df673db.nq.gz
    ├── 01b072f6f82bdd06bf32873edd66a3b957acc84b.nq.gz
    ├── 01b5cc71f325dc6b401353ca4d7ee1c767206080.nq.gz
    ├── 01ba893432a537b03be84030b46c1c72a1491b7e.nq.gz
    ├── 01c094b13b41aa3946d14a08a7905ff908679f68.nq.gz
    ├── 01c176d72d1e265df0854c01b217b96cbc7bd2a0.nq.gz
    ├── 01c28d56f98146b818825052f9b08ace9f157b5c.nq.gz
    ├── 01cd966c084b50bfaa5b190b5550bf181418028e.nq.gz
    ├── 01d6823bb6b52c2f53b6393bd751f16f72d3864a.nq.gz
    ├── 01db40aac3ef5311441290a4487341b7e49169aa.nq.gz
    ├── 01e09ab77d853c6bc551d92ce954ddc8324607a1.nq.gz
    ├── 01e56ecf58e986fa0d02ca9f7f46399eba20d11a.nq.gz
    ├── 01e80e76fb26529744653912630380c39d49639b.nq.gz
    ├── 01eccd43e64e98325734c6f62c5dde00aeaead3a.nq.gz
    ├── 01f28fe97ffce8b55eb262e53f75821ba18569dc.nq.gz
    ├── 01f67048266e885907ed76af413668f6317f76ff.nq.gz
    ├── 01f8c96cfd5713c491094ae9e4888cb93d1b6fd1.nq.gz
    ├── 02060565ee8cf6e4eb0c065fb54ea552728e517a.nq.gz
    ├── 0208847fb58ad31d30425d565bf3991d7aec41d4.nq.gz
    ├── 020c10f3d7113f8c67835996b3fa4ae8426504fe.nq.gz
    ├── 020f83202354a1329cdecb92bf94960be357dab2.nq.gz
    ├── 020faf1765d736fe1d5d1de2aa97b5f6bbf07c09.nq.gz
    ├── 0215de8f0b5188dd0252e20d27d411ebc77aca49.nq.gz
    ├── 0217c7fae6a2089130cd9d365755bad328caf152.nq.gz
    ├── 021f00e6c5d5367670416f791ca67c754a1dce99.nq.gz
    ├── 021f7d8f65b35c6ae78ce72367849b066639ef4d.nq.gz
    ├── 022e295419f8bf43230dd59cf1ccc11c513c2510.nq.gz
    ├── 022ea58a6d53b01044cef11fbfac6acdcf982337.nq.gz
    ├── 023163fd56b611343307e6292215504d6092755e.nq.gz
    ├── 023337e9af5bb75d0ae666debb433e56bb86538b.nq.gz
    ├── 0239b2908db7e8744d717930efe4d6896db63f11.nq.gz
    ├── 0239cb15fa21862df91a3c62aad5fa59bb83ad95.nq.gz
    ├── 0239fa25fab78b24d5eb804ae4ec8b28b2d90c0c.nq.gz
    ├── 023fb7c42f6fc8ba47e460945a6507b9cbdf8b37.nq.gz
    ├── 0241f13214bb3035ddced33ba19c10245c1327ca.nq.gz
    ├── 024cc3bdda2667950487ea71b8252907eabf92de.nq.gz
    ├── 024d22b1521f877d159a79142d890e9fb5e6c240.nq.gz
    ├── 024e931d3a786688534b8062755ed02a12cfd720.nq.gz
    ├── 02544f1d71ba8e819118ec1ca89150c6d6414af6.nq.gz
    ├── 0256131b8f230363fab1d37a6481b78d1063f5ad.nq.gz
    ├── 025c2a8f7dbbd12248bf9989669780a96c4b8528.nq.gz
    ├── 025f32d8e0529a8524567906db2e044a1c0890a9.nq.gz
    ├── 0261b1cb251ef4e275578452c6a7e96638538362.nq.gz
    ├── 02799a5a23b1229114f0d62dab06ec14b8848001.nq.gz
    ├── 02848726182c7a7b19402ffe70b1ad6878bf06bd.nq.gz
    ├── 028649846e7425db28315208f75046fa29c0927f.nq.gz
    ├── 028c8d9d95bc07bb0a7903ff42197b1a9231f5e6.nq.gz
    ├── 029877f159a835ff6800485a1748898433f30f56.nq.gz
    ├── 029e2e9475896c009d8d1e1f6721ad9b0fcd4fc2.nq.gz
    ├── 029f4bd6ad2aa521fa309eaf44edeb2480731501.nq.gz
    ├── 02a8a793192f985edcb96c7a73898d24396baa82.nq.gz
    ├── 02ad1242e7775281ca1cd9819b06b7b0ebd15287.nq.gz
    ├── 02b3e297ca41c52789eb65e6613265e940cad4d1.nq.gz
    ├── 02b500221da0ed70bf390c547f79559058c59f67.nq.gz
    ├── 02b7462664e82f2e16cf343e48c4e10272e5f899.nq.gz
    ├── 02c7d2f7505bc2d3e59fec5f98591acd229c04a5.nq.gz
    ├── 02d5fef070d0873e6bd4293577bc8b6fda88de0b.nq.gz
    ├── 02f099658ab5495926ccb0dbcd1927d467cf642c.nq.gz
    ├── 02f47a2f67e63e6bcb935c26e40df770023eb212.nq.gz
    ├── 02f9275454b8d614613a5bd899a95db85afb31c1.nq.gz
    ├── 02fbe346d7cb3b55bc294eb291726aaf1169cde3.nq.gz
    ├── 03058c5d21caef83962efec619466fb8394c619c.nq.gz
    ├── 030da49b4392ac02eb33affa12821b47e9bf766d.nq.gz
    ├── 030fa8049f0ce03f772dce65c43f1dd7a1774b11.nq.gz
    └── 0311788a62f6de2b20f7c2d9134996a960a85bba.nq.gz

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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
