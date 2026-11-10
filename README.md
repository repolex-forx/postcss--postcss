# Repolex Knowledge Graph of postcss/postcss

RDF knowledge graph data for [postcss/postcss](https://github.com/postcss/postcss), parsed by [repolex](https://repolex.ai).

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
rlex download postcss/postcss
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4740f8a2c65949e18340a3a775a38a5717eafa0d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4740f8a2c65949e18340a3a775a38a5717eafa0d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a1037aa6096bb36ad20b26aeb6374bc4e2b4db.nq.gz
│   ├── 03d9ed1766f78a8472f7b2485a7cf0f40cb89525.nq.gz
│   ├── 06bde838507822e43a94709d43bcd76efe64862d.nq.gz
│   ├── 0934db2c873672be5795befa3fecafcd0ecd0658.nq.gz
│   ├── 0aaa2efe24e51b85941916c55917fc5fad81c9e6.nq.gz
│   ├── 0f6f9ea32b9e71fa295a7fbd4f73abca8dafe670.nq.gz
│   ├── 119624e8744e125e86959fe33a68e091c256eb0d.nq.gz
│   ├── 161dce90e1e20ab3ff653e6715efaecf574b8e34.nq.gz
│   ├── 16eabcb7ac27576cbe517fcd5d4de1be075ba4d3.nq.gz
│   ├── 1a1e46f1cc28d7dec54f503c30b6f4c54fa8fb5a.nq.gz
│   ├── 2155c55931a6160455e13ac99a46c9e21eb67e86.nq.gz
│   ├── 2537a11b8a05333af74f11979e70829671ebf04b.nq.gz
│   ├── 255d864099a363e2107cdc83bfb85bbeb5a2563b.nq.gz
│   ├── 25c1722ea0d7779c351091beba4848b402b573d3.nq.gz
│   ├── 293b4e99f054a812af1f6b0faa52179a24505b7f.nq.gz
│   ├── 2e046b40866cda95d05b42b90ccb09b3f44d0f5a.nq.gz
│   ├── 3030054ee6b1d1ab79f1da4af481b9c5114ddb0c.nq.gz
│   ├── 316e1cf462f076c803b4f5e023c4d81bdba308b9.nq.gz
│   ├── 34afb8a324ae769de1ecac1d5cbcbe3318d69daa.nq.gz
│   ├── 35075988c69c7316f5d64361fc65795e1e5e6c68.nq.gz
│   ├── 3754ebd67b18f5c2f123c55e780966bf88d26504.nq.gz
│   ├── 399198f06419304790d3e27b14500358f886f74a.nq.gz
│   ├── 3a0c5b85fd5c3a755bb07e7da3474a4633023f3a.nq.gz
│   ├── 3b8adcb71cf3ebbc929aa784e2548877d5b47a1a.nq.gz
│   ├── 3b9b7e9bb7fb7e1963cdabc5d77a62fe10e76948.nq.gz
│   ├── 3f4a7867d736efd6e7c74dc6bb29644e62aec19e.nq.gz
│   ├── 3ff06de0bcdc749d643209dea9ac8a9d5ccfb534.nq.gz
│   ├── 41bf40f9b9204aaa387c56ea34f18bc21ac66523.nq.gz
│   ├── 43211b46694f4f0d1109b09abe6dd2d612aa141a.nq.gz
│   ├── 43d920f4e91aedd28a360a5bbcf66dac23ee0ce9.nq.gz
│   ├── 44689917fc57d210b1a4dfad4187ac721c6eb16d.nq.gz
│   ├── 48a9516c7e355ba043ee238ed86c6ff1333c0131.nq.gz
│   ├── 4917509d4d6bae29683b33c8476abc2ca90d3ada.nq.gz
│   ├── 4e865fa6b04a9994fad13719b7b896456f54c350.nq.gz
│   ├── 4fa71796a447cf14b71a3cd5ed686712d43dbbce.nq.gz
│   ├── 55a30fa41434063d7c0e28f9d05a738a6d6316ec.nq.gz
│   ├── 586153354fc4e164ec076d6e2ceeb5587b504d23.nq.gz
│   ├── 599a614bf2b6a1e07faf74e8acae3e57273bc628.nq.gz
│   ├── 5fa8b76bd1452f857768b76dbb62c9d6504122b5.nq.gz
│   ├── 6196c9df19d6fc2c3bd0c3de7dc662dca5408048.nq.gz
│   ├── 64413e4ec16215327fc2ac07b1a3ab09b5b6e23e.nq.gz
│   ├── 64e57dbc9cdf8e7a6ed38cd7a590e44a58ae75a9.nq.gz
│   ├── 65a03aa961edbdb25aecc840bab6843f1e7ea6c0.nq.gz
│   ├── 67194dd9ca31ddd2015121d9cd797deb8e7101a7.nq.gz
│   ├── 6f4093b2103fd2a248617f8ecc6f6b533917596c.nq.gz
│   ├── 703e39998d64c5619b62804917e5ff714211c696.nq.gz
│   ├── 75eb003b156386e7517ae06cefe13caf8dee6976.nq.gz
│   ├── 81dc623b9999041c2aad0ad6948a854483086fe1.nq.gz
│   ├── 82131bf50dec70df1ee0431c7dd68d16ad101b52.nq.gz
│   ├── 8343f363cd7cbae7cee767c4148bec5ba515559c.nq.gz
│   ├── 8825951289b75c4acf65c0f012f7f75452991708.nq.gz
│   ├── 8874005aeda2019bd9fff9c52237ee60ccab37fe.nq.gz
│   ├── 8a8cdbb9c3871048677cca99c9d6224e2a0a355a.nq.gz
│   ├── 8d6d57bec9c3efc801c53240d9886b269b99cb6c.nq.gz
│   ├── 91de44399839b06bfc5ba85d7b38893b397484e7.nq.gz
│   ├── 9439f8b9dc67b5f5a010b44f989d395b60f6e826.nq.gz
│   ├── 9486447b029c6c9991ca1b62e5a5d57c611a7503.nq.gz
│   ├── 95b2fa2519d89b1df74e6768cbdeb3655f63fd68.nq.gz
│   ├── 98dccb073ff5c7f0aeba6d3397a9ebb6ab7f9815.nq.gz
│   ├── 9cecd44019f97a93238b7c7efc49d5cd8ea4d7a7.nq.gz
│   ├── 9f674c4c1313f65f686c5ad6cfa6a1b61236f14d.nq.gz
│   ├── a0a4a02d21969961f96c0b28211c91dee95eeb05.nq.gz
│   ├── a142c268d464bd4093653baea44ea7abb85e1496.nq.gz
│   ├── a2edcdad444703b1b269e889f9c9646fdf47c8d8.nq.gz
│   ├── a4666acfb67532af7717b4ac45d2c568d68073d5.nq.gz
│   ├── a70717e61c3ecd87ff20b3a3ab603fc921004ac7.nq.gz
│   ├── a9adb0bd134327c37db909970ddcbd83d31e2a38.nq.gz
│   ├── abaea53c2c9b790a4e2fcf15010ceffaa856afbd.nq.gz
│   ├── abb06e69a52a230f5e984e91bca32fa9c90bbfe7.nq.gz
│   ├── aee1cece98596245a97de4d542f80599ef2e3f90.nq.gz
│   ├── aef717dcf37ee53db24bfb38b4239860219811e8.nq.gz
│   ├── af69830f82105513174f30e349f4e4d45c2a7dbd.nq.gz
│   ├── b1f4d1e6254f988a28dda197b4ea0e8ba2257ab5.nq.gz
│   ├── b25f8125ecefd8cdc746e99f361c150e54ddac9b.nq.gz
│   ├── b3db4dca858434e7c5d69ff40acca8f24d9e0c64.nq.gz
│   ├── b4fad5c79a76de183f23aa58219120ec491bf44c.nq.gz
│   ├── b50cf1cfe2d8e7f9b106ebdf8997f036d7f7879a.nq.gz
│   ├── bc8547f3995b361d38b181361cc1596c54033a27.nq.gz
│   ├── bce5cf67092559ffaa97b0417a0207ee808e4ac9.nq.gz
│   ├── bd24aefaa11b106677ba51705cc4eb5f271c1008.nq.gz
│   ├── c1a9509b4cc7672c03a5e0ccae03a6d64cf9c15b.nq.gz
│   ├── c2314d53d097cd36006110afd82fe3d09701a7c5.nq.gz
│   ├── c3a5552bc0891e2e725e22e0f4633575f4bd8472.nq.gz
│   ├── c538c0d781b2277cd130e7e9fd9bb7774809728a.nq.gz
│   ├── c56650645caed3bb47cf7a39d18696ec47140ca3.nq.gz
│   ├── c5679674c5463bc49ab0778dfe35fad6987db9d7.nq.gz
│   ├── c6af4e8cabbf5abb1a98382dbd828105b83f5d35.nq.gz
│   ├── c6c8b3621938a4691225a870a59bf382af1883dd.nq.gz
│   ├── c796057122e511d7105b94706d890ab8a28757db.nq.gz
│   ├── ca2d26bf8444221e2c97eca099209bf4b085e6d8.nq.gz
│   ├── ca5da02e41b0b4c49fdd14e48f7e77b9854cff18.nq.gz
│   ├── cd0334fb238e11b89f8c054ffab2836ebc8cd63d.nq.gz
│   ├── cd3b65b6f167e3da9f7294aa0bd824d072b1daa3.nq.gz
│   ├── cfb106bc604cd475c1f8247dd6185b3198fc40a3.nq.gz
│   ├── db0cce05948dff2d957748eb6cb8d1cd884f5d31.nq.gz
│   ├── dc1fb8e364af5e7d423a31370663a96f3e35242d.nq.gz
│   ├── e163e178753e1b632a9a91e6cf56fa80220f6ea8.nq.gz
│   ├── e2d19065c6308fc58443580a2df0c53a98a35bde.nq.gz
│   ├── e3fa8295b5e47dc9e7e4084c8ed6e032cbf792da.nq.gz
│   ├── e5c07b7ae587d041f75b49f7180fab726684ccf4.nq.gz
│   ├── e93ce5baeec9cb20485c262aa9b23a7e0bf109da.nq.gz
│   ├── eaec8681f1b412534556620f2b0139045e3bfb51.nq.gz
│   ├── eca007d3853d3b30c394bd14b446e790f7ec6b2e.nq.gz
│   ├── ed5ab442f7eb5792da47bca8d5df42f4c8eae7d2.nq.gz
│   ├── ed906e510f8f2eb3e86e4a188e0e3dbdf4cf31f3.nq.gz
│   ├── f0becd7550f5bfade67685bef218a4c26029f085.nq.gz
│   ├── f764109b7a21c1527933d95bbfc2d5442834df40.nq.gz
│   ├── f8fc2930be24c366516edcd4497668fff40b5ef4.nq.gz
│   ├── fa9d284849af11b0e125430416f35a5738ce52dd.nq.gz
│   ├── fd0498110b0bbe12fc59ef44324104462dae32a7.nq.gz
│   ├── fddd982fe9c7198de58fd7d681a4a13871e5c7d6.nq.gz
│   └── ffe35b4390997ea1487104d6377630f9c8b5a197.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4740f8a2c65949e18340a3a775a38a5717eafa0d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 120 files
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

[postcss/postcss](https://github.com/postcss/postcss)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
