# Repolex Knowledge Graph of pytest-dev/pytest-order

RDF knowledge graph data for [pytest-dev/pytest-order](https://github.com/pytest-dev/pytest-order), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-order
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3730f4f168c2bfa0bc0788b0aa9402da985bd2cf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3730f4f168c2bfa0bc0788b0aa9402da985bd2cf
│           └── chunk-001.nq.gz
├── blob
│   ├── 01f5badb69f33f01242a42735ef4c528ba9f63fc.nq.gz
│   ├── 023c71e3ff5426355454374a48bb82ca5f4df323.nq.gz
│   ├── 02f4c7ff8137daaad69aa1f22f0f07f2083be510.nq.gz
│   ├── 063d1ec7450d691976c013b933cee833cf629d67.nq.gz
│   ├── 077103baf1555dd663bf3009ed74e0ca35470f0c.nq.gz
│   ├── 0cf27ac34e1e1e50b34cd48e1bf065efb8c9eed9.nq.gz
│   ├── 109051808e10b4d4b17096265224a548e61ea5e0.nq.gz
│   ├── 13054f4ffb17b92b146d49746c3af7ba2582e07e.nq.gz
│   ├── 1b796ec75a402ee50ec08522070ea1e3a80847c9.nq.gz
│   ├── 1f05a85763a4c791a6babe8aaaf1613567dedff5.nq.gz
│   ├── 229fe70f33ec5002aa5fd201a09a254789b33691.nq.gz
│   ├── 2b6a2771b96bf8b940b96c5f0e4ef0bc202c1f59.nq.gz
│   ├── 2f62a21e029626e34901bff89cd73baaccfcab40.nq.gz
│   ├── 3210e687288513f6c8676e89c1061ec1fc4b045e.nq.gz
│   ├── 3413617608cfd3dd783e24da37796b6a771aad48.nq.gz
│   ├── 34b2f2d988f037b997e3b8bbdf03cf415553fdb8.nq.gz
│   ├── 374aae997bbbc445c1011b11d932a09655db58b3.nq.gz
│   ├── 3e8bbab300c767b22cce9426a098b18de9a5ef42.nq.gz
│   ├── 444506558548afa6a994623f3a857f823f692a12.nq.gz
│   ├── 468d33f92f659808b38ab989ee4005559e629df3.nq.gz
│   ├── 4b3cfe6b4240cd1d6cac0e68772daf145ed73e49.nq.gz
│   ├── 4bf0bd2fa613a77ce3b4c7acf22fb292f74379fb.nq.gz
│   ├── 57bb166dff9c05449fe243855b12d56a7dfd842a.nq.gz
│   ├── 5a3b62617c801f2c77e7ccbe16366b1099e7f585.nq.gz
│   ├── 61ca60df82633670daa4616fa9b4e0275b1f6b5f.nq.gz
│   ├── 62d7b838ca83c4b8bc13e0b95d376c91680508ee.nq.gz
│   ├── 630b99db1693679b6a9f9ef7c19e33505c013a0e.nq.gz
│   ├── 6816cb0b0250cd63941c99e66032cc3fa82a18c2.nq.gz
│   ├── 75563fd87159f344548a8ff3ff17012af2a336cd.nq.gz
│   ├── 7c5325a88998aa261a34aed50db69b9994b44df4.nq.gz
│   ├── 7d78282f18d43e8c71a66debede2b9113fcc70da.nq.gz
│   ├── 7e57807aa9de152572bb252bcf4c4656306493b5.nq.gz
│   ├── 7f24f5c28571fc3b27e807690b10987eaa5cfa19.nq.gz
│   ├── 810e88098ef7b284eb065ac488f05d720fdd70cf.nq.gz
│   ├── 82c538809cec95aa9c011c305fa29b99f8199b01.nq.gz
│   ├── 8348df197d121825bc5b81028ebd5d413b8f1ea9.nq.gz
│   ├── 8384d22aa55ae153eb85111b7c1d5aa0e3bd556c.nq.gz
│   ├── 858ad8f63fa73561a5f0fb8cb4a93481e7137d72.nq.gz
│   ├── 85981bc5005981159e7bfe95c7287da522b63b5c.nq.gz
│   ├── 873981bfc8d2a6676b82163b30447d3a9c0a997c.nq.gz
│   ├── 889ac04ae4728af2f1fa9cfb464e8582ac8532d2.nq.gz
│   ├── 8f7326dd969e173df4cea43555928e4f2b49184f.nq.gz
│   ├── 9067d2b53ea6c56cb64836adac243ee250d741b9.nq.gz
│   ├── 94a47f2a65a561cc29819ea510ea36ca7a98a6b2.nq.gz
│   ├── 97e976a424b249234188a132e6887039dfc7dce8.nq.gz
│   ├── 98253b2ab6384a16dab29e113aaf6330286dfa77.nq.gz
│   ├── 98d7931665daa5f1c8c8ef0fab6529c1695e0f18.nq.gz
│   ├── 9ee3ee3a838dfdbb2b1f34c477b0948f0ccb9f79.nq.gz
│   ├── a1ac89cc1fdbc5aff813e0dcc36b0777882c2f80.nq.gz
│   ├── a2f5aa4fbd0a96b1ab271788e85efb7c378ea59b.nq.gz
│   ├── a31f75e20c833ac587d22a210d600810382d831c.nq.gz
│   ├── a37e666f2f37695429f9e2c8522fb32c7ed78e62.nq.gz
│   ├── a3a05e3b8887d5aab636c47c181e30190cef09d5.nq.gz
│   ├── a3a88a1f02f88c42602ec024f27ea4e662775930.nq.gz
│   ├── a68f5330c089847e696e9a4b15d074248cf26bb5.nq.gz
│   ├── a6aa45b09febc7be03be9973bc2aafecee5a8bfa.nq.gz
│   ├── ac57b3b1c6ca058491ba0a8b8d0c00c9e9e90f5e.nq.gz
│   ├── ad503c9d232d25651b5577cc4377655bd3b9a0f5.nq.gz
│   ├── ae93dfdf43235f3e5870f76c91108fb165f0a5a1.nq.gz
│   ├── af013674bc7951315cf0db7c17a76aa5907380e6.nq.gz
│   ├── afba8424ad0c3ef013c1d1f0e89a751bb8dbd4d9.nq.gz
│   ├── b14a898af05073c0de670c90e557d8fa9d527aa1.nq.gz
│   ├── b6c03004b23fbefb28fb3c8ccba4a2747b51898a.nq.gz
│   ├── bc07bdb19cffdc24241ed04bf8bd97bbf418b63d.nq.gz
│   ├── bdf1bed695d24b46839e09cd888dc50bb3aba492.nq.gz
│   ├── c388c967b7e0a101311060d9f39ea2637ba2efa6.nq.gz
│   ├── c3d3a6c34bd32c382b91b17b30e8d2b1d93d563e.nq.gz
│   ├── c57b3fb6e580b5b24ab6cd693fa461d8013ed114.nq.gz
│   ├── c7ed7046bc4c75074a798bf496ac0c55b9b63e8b.nq.gz
│   ├── c87b160b2f14e716775aaa5a9c26714fa2bbf6fd.nq.gz
│   ├── c8d109142f67e50307657982d425fc3c01b7b736.nq.gz
│   ├── ca552fa5df532bcfcf22b375b1658d124394b2a0.nq.gz
│   ├── cf33d60fbd60b8a6248ff2d892423a9199a2c6e1.nq.gz
│   ├── d0b93d65405f46392ef515097a9bdde83d9c4107.nq.gz
│   ├── de09a5e54dccffe9ba553b71ab10e21923c003fe.nq.gz
│   ├── df0fa65d16cc86a62455159dec786f1400e0d41e.nq.gz
│   ├── e24685efd6a81597d0f7b05cbed2a106f1ca412c.nq.gz
│   ├── e4ba9c06f1444417c9c0dad4459436baf1caf8ad.nq.gz
│   ├── e5903e0b83dc737c6590aed92cc76b85b8613929.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e74e7317b2b51d6f5ae1a80f845900d07ce34e5d.nq.gz
│   ├── e789236b6482969c21fa852f9fdd0e90fb734654.nq.gz
│   ├── eca7b57b198f2a3816b529b546cad831e4e43bc4.nq.gz
│   ├── f0e784b5808fa93a300aa79cca345de9532030e1.nq.gz
│   ├── f17c8ccd8bd4a9686ea2952ce922a6658392b472.nq.gz
│   ├── f1c009417fd00ac453c3f45a61a9b87816cbba68.nq.gz
│   ├── f68a22501deb6dac35e36cfa84d78a2c6bcef79a.nq.gz
│   ├── f72a44e9f1fe5b68ae7a9a68f637c8ae43057cf1.nq.gz
│   ├── f7c3d3e29497300760e9c021945db122edc19546.nq.gz
│   ├── fb61e9bc6d36f92ee518195cf87206b170a0f85b.nq.gz
│   └── fbfa5e8916bd33748135db6c537966b24a2b8e40.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3730f4f168c2bfa0bc0788b0aa9402da985bd2cf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 99 files
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

[pytest-dev/pytest-order](https://github.com/pytest-dev/pytest-order)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
