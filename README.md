# Repolex Knowledge Graph of tailwindlabs/prettier-plugin-tailwindcss

RDF knowledge graph data for [tailwindlabs/prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss), parsed by [repolex](https://repolex.ai).

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
lexq download tailwindlabs/prettier-plugin-tailwindcss
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 28beb4e008b913414562addec4abb8ab261f3828
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 28beb4e008b913414562addec4abb8ab261f3828.nq.gz
│   └── repolex
│       └── 28beb4e008b913414562addec4abb8ab261f3828
│           └── chunk-001.nq.gz
├── blob
│   ├── 0862924f6a8d45bce5f750192f66a44212595ee2.nq.gz
│   ├── 088e5d8e128711e6db4ad079de0ea8ce63a48757.nq.gz
│   ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
│   ├── 0c0c9c078a3f753d97a70f2bfe111e3229e5009b.nq.gz
│   ├── 12cf8d57ada75a88ae0baebcfc1ac3ad52d677af.nq.gz
│   ├── 1a60a4a5ddbdc3d1245c50b9faf6aba8fe440c53.nq.gz
│   ├── 1baa73cc89e952bb5dafcb221d24096facb7f594.nq.gz
│   ├── 1bf51d8d3718ad3468b11846b1242ebd3087e3f1.nq.gz
│   ├── 1c33ae8bcc9171cc995d9bec793612cddd7d784c.nq.gz
│   ├── 1d19184330b47a715f917ba16a2726e72f2fd88f.nq.gz
│   ├── 1e3ec5ab9ada34ccae1e599ca38eccd83695b0c6.nq.gz
│   ├── 1ecdf24f3f53cc1380fdf437b6116261a67f1f0a.nq.gz
│   ├── 1fb3b3764f9a8eab721c8f2c5b43c5398a5b1a7e.nq.gz
│   ├── 23fa79d90885b7c86f304ce77d6082ed54dae274.nq.gz
│   ├── 28ba80dbe82b556f0154a91d512d83ef6fea9aa5.nq.gz
│   ├── 2f86256f55e25909558d1afffe3af5e3755dbed6.nq.gz
│   ├── 30b6946f293a42bb810b5d411d3ded6167458f7d.nq.gz
│   ├── 31d97482d68fc22861ec7effe36d4ff8554fa6dc.nq.gz
│   ├── 336bae08c7c064959f1241399af77fb34c384b51.nq.gz
│   ├── 369d50aff8a4d48d235467a63e8ee168492ebe42.nq.gz
│   ├── 3703eb8562e735df5d7dc328a0e037f23698a6b0.nq.gz
│   ├── 3c09d578ddba4d17ecbb7b18f05824799c220ca6.nq.gz
│   ├── 40b89a945d81d58da006d1db57a20a0cb4e770aa.nq.gz
│   ├── 4147daa7f5099599be4b2b39bbc87c681c61ee39.nq.gz
│   ├── 43f4abffca1d37297a0732e2f3369ea455bb89e0.nq.gz
│   ├── 46164850a0673fda3453c5e98effb6dd5da9a40a.nq.gz
│   ├── 4a200fa9e0878c46f8c7218051951a4062bd3fd1.nq.gz
│   ├── 4d234adc7db309ea2ee96e8106eaffd4ab2b089a.nq.gz
│   ├── 51345d89c68bbeb57ed8bb206128e0f5e71bbb53.nq.gz
│   ├── 5bbefffbabee392d1855491b84dc0a716b6a3bf2.nq.gz
│   ├── 5c00bb1be3cfa74faf4a9348a745fa3daf69160d.nq.gz
│   ├── 5c3a44f199d2d50b7817b0fa7bd61bc5b6c4eb61.nq.gz
│   ├── 5f316a9b03b179766a7d44521133e36749544d60.nq.gz
│   ├── 606018602db4ad74d22d7c92c7e82a87a983c24b.nq.gz
│   ├── 60fc8e613fa398f8a8291d6c5fb45dc3b51f4cb5.nq.gz
│   ├── 6309bec564bdfd2252458772eae09122d4cc3a6d.nq.gz
│   ├── 63212967aee04c09f8be8e746bb56f3705bd61eb.nq.gz
│   ├── 6328c84b37a663fbd2a05698de4a74cfca242cd1.nq.gz
│   ├── 634f357ba9ce8f2318325d6ae69b6e7c61818b20.nq.gz
│   ├── 6456ce73a28ca202d044c223fca6f0fdda27761d.nq.gz
│   ├── 64bae51e61c5ece3d53ad0a97b5de4625cc0a7b7.nq.gz
│   ├── 6d29d2ba426eb35f999b59233e17c94bbc055f32.nq.gz
│   ├── 6f2a4470d3e9e3d3263d5d54eb3d0aa4a90f1343.nq.gz
│   ├── 713e1bb18cd6c74acbcb78c8ee46bdb4f229b20e.nq.gz
│   ├── 74ba9675ec1144deac25f48d14a0fb3bba02663f.nq.gz
│   ├── 79387c607a4c55a9133d3f2931af7674cb4ac4f7.nq.gz
│   ├── 796e265faebdd73b0ae89c455cbe138ca47bb55c.nq.gz
│   ├── 7a2bc386ec63e5c5097eeae20e6f3e8b3ba29feb.nq.gz
│   ├── 7c77ab91ac294ab33fce9af56683b2c9e827dc82.nq.gz
│   ├── 7f6673005227f6f4f77f3d08bad3d4ca0e4770f1.nq.gz
│   ├── 803df1e1ed2ca11ef5f5f597f5f82d915eb16373.nq.gz
│   ├── 848c851b1773eec383b31d4d7b712ef1fbdd3cf2.nq.gz
│   ├── 8fb8c517f6ccf77873a2cdae7c2d5c5883fa637e.nq.gz
│   ├── 9098a40647133e7d6990594d10f2ff1b8ae50c49.nq.gz
│   ├── 9591397afc6cf7993c573f83bdaaf9ad44d5cc4d.nq.gz
│   ├── 95cd1b7c867155bae47c92ebe9d3b3e928935fe3.nq.gz
│   ├── 9d2eec31d6fae78ed6780df6f847a4383638aa23.nq.gz
│   ├── 9db12a9037c7393ecea195c186ec79eed43270b6.nq.gz
│   ├── 9ecd6e82fa30481c8eefb501ac5fd1244bbc7467.nq.gz
│   ├── 9fc0088c08d4f902e34c6fed6d72bfadb0d7e654.nq.gz
│   ├── a428ba515c90d570e3fe0b613a1f35cc376a5244.nq.gz
│   ├── a4517c33923bcbf2bf87c737546dd9730bc555ef.nq.gz
│   ├── a72622939d671380060a70beee23bcbcf7029803.nq.gz
│   ├── a99a8e30b9ee6fbacbd0b736467d3682de23149c.nq.gz
│   ├── ac52a795a95dc294d3a69a8cb99d5696ed1e425f.nq.gz
│   ├── af1fa29e9525f0ab23c2db576b5ecbf6be3ee46b.nq.gz
│   ├── b479cc0e3c3ecc8f2d62763676b2b0d583472032.nq.gz
│   ├── b69507aedce729e7931bb3ed67720d4f3e5f8d6f.nq.gz
│   ├── b7db3dfb0c8d97f242e7a3611dd8fe24c220b721.nq.gz
│   ├── bab476a8530d86ea1e7b0c0e5ff2d6090cf892b6.nq.gz
│   ├── bbd3ef9880917cb1c623b472f5a9d71511a7bfb4.nq.gz
│   ├── bd07d4e1bc26979c14a11a72824f88d59b8f0498.nq.gz
│   ├── bda93684372ac564dd87d29a295924b6670b6797.nq.gz
│   ├── bf5be4a9a648434d8145eb0412d0c13995459204.nq.gz
│   ├── c27b91e10d02ae7236874aa7519fb103acbbab6a.nq.gz
│   ├── c57e6140144f0021c987665c64fc6413e6014ec3.nq.gz
│   ├── cc1254773f618f5dca821245d25c60e7c8dba22f.nq.gz
│   ├── cd0cd3c63de7c6c918b4e8728a2303859d0ed7c2.nq.gz
│   ├── cdefec88c6032641f977730a6ec0d413d82e0fbb.nq.gz
│   ├── ce1b3b2301cd021c45862a855820a35a358572af.nq.gz
│   ├── cea4f739116db9b157c23996474653a34f79f402.nq.gz
│   ├── d94857a4d28bfb10fff7e03e6206a7deeabd35bf.nq.gz
│   ├── dd17b16317cf556f956f44036fbc8085ce7bda15.nq.gz
│   ├── ddadc952a74ed80054e270111d1e4276c88a089c.nq.gz
│   ├── de2102e6f09eb30149389a9087c6635d3bed6417.nq.gz
│   ├── e0802d777f7ad8ded54da2889007c340ba3cd05e.nq.gz
│   ├── e106914d06ccf0840ba23e3c6517812463b04abf.nq.gz
│   ├── e810a394dbe506b1087f7d238bb28fa5e0016af5.nq.gz
│   ├── e8319ca0d457275d1a50889f0a63455447a9a432.nq.gz
│   ├── ec44ef36fcb739bbce32b94b505a992c6511cf25.nq.gz
│   ├── f053ebf7976e3726d11f3c03fade2170903889a5.nq.gz
│   ├── f11ad33ccd3bf39bfc58f686da50e36ecab57974.nq.gz
│   ├── f3ba30b31a474eefeab6f26ebec470d276cbe4b0.nq.gz
│   ├── f4a30c0adc1b5d43ef5c590e9358b67bbbf1c769.nq.gz
│   ├── f69a18af311108bf79bc4b02c091532a4413b1a4.nq.gz
│   ├── f70026f748577f618ef629b4e7430b23f69d552f.nq.gz
│   ├── fd0174ccdf9a148ee3878067ce4fa7fb180971f1.nq.gz
│   └── ffc643a18c8cc5f9944fdaa8582b63e2fa8f78fe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 28beb4e008b913414562addec4abb8ab261f3828.nq.gz
├── filetree
│   └── 28beb4e008b913414562addec4abb8ab261f3828.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 108 files
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

[tailwindlabs/prettier-plugin-tailwindcss](https://github.com/tailwindlabs/prettier-plugin-tailwindcss)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
