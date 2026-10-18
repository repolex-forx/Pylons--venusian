# Repolex Knowledge Graph of Pylons/venusian

RDF knowledge graph data for [Pylons/venusian](https://github.com/Pylons/venusian), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/venusian
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d036c00afa4e8c3077ab53a22290ac19fed652b2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d036c00afa4e8c3077ab53a22290ac19fed652b2
│           └── chunk-001.nq.gz
├── blob
│   ├── 0245b1ab090db9d96187486835d6ec125f788b26.nq.gz
│   ├── 027198cca34997d39663c8c6d67f8df710a90de4.nq.gz
│   ├── 0508787af2d86343f6f832fbf68fdb5568b6218a.nq.gz
│   ├── 136821837d908e053faccbf7ad9c9f54640a7016.nq.gz
│   ├── 13a8fa5f88cf431f11a3b558cf8f83f287405030.nq.gz
│   ├── 17fa9686af34d0a66e7c9006fcf8eb6df2ae6f7c.nq.gz
│   ├── 1ad0fe4505580919cb3b333138918b73655cdf45.nq.gz
│   ├── 29e778258ad4fe162e8f269419cb3fb2f4841e76.nq.gz
│   ├── 30cf48b6dcf4d46e32713d4fe46ca64b08e15a65.nq.gz
│   ├── 36b95f818ac57b092c444a82c72b416f7005b211.nq.gz
│   ├── 36e6082f67d5ebf7fff5245d8b72db4a880ff178.nq.gz
│   ├── 3946ef8d37a5770894ff43e3dbdb5d8ab4e587fd.nq.gz
│   ├── 3ac64fe4c28161474e56102654d3a664eca7e7e4.nq.gz
│   ├── 415cb4fa691b4713e7f9e5a795f4427aca4ee550.nq.gz
│   ├── 47225033f6187d7bf4719f6a73ef8431646906b1.nq.gz
│   ├── 4ffcae43ca90963c2858f7443fa1358eb2ba7180.nq.gz
│   ├── 5737055179c779b424f85fe92776d847c5e82905.nq.gz
│   ├── 5bb534f795ae0f566ba9f57c31944d8c6f45284c.nq.gz
│   ├── 5ced96e3b5d11a635acdcf19c4919fb3d70bdf9f.nq.gz
│   ├── 5fd08cece57e41a45d4ee3a0ef70685d2c37a9fd.nq.gz
│   ├── 6a126965f43979361ac7810cdb2fa589841f127c.nq.gz
│   ├── 6e565c528d85429b63f6ea89723778ffa7ce085a.nq.gz
│   ├── 71ed6bf243dc339147bf90a5a37de430064091d3.nq.gz
│   ├── 77247adff461847d2b67978880b20aa1de496e70.nq.gz
│   ├── 7e1cc119367ae6cf5084fb90c4701079902fca54.nq.gz
│   ├── 83d34ae14970de0639a32468d902bc0aa429cc1e.nq.gz
│   ├── 8a576d663b240e76405e61e675bb804cb905be34.nq.gz
│   ├── 9c188dd48bb86f5e1be6acb53eb11fae7094b5ae.nq.gz
│   ├── a2ecd73a0a91caf1cfe1ae3c128b715c2c91ef04.nq.gz
│   ├── a533f4d2a0b109d1762307a99d89d367ed44f903.nq.gz
│   ├── a857693af62ea1e820ec5704fed33a2f831523c9.nq.gz
│   ├── b58a39dd3a5ae09755e2f72410b770cf76b272b8.nq.gz
│   ├── b9bd50a065e0dd4b2a5657fe8bdb789d05b57dd6.nq.gz
│   ├── bb062c159634c8189dbcd4424b80cb44285ffc76.nq.gz
│   ├── bd8889a5d70e7b1202f0e4051741c98e7f098941.nq.gz
│   ├── be71724ca9ec08c688266cb9d7f7189704248307.nq.gz
│   ├── bf21bc24b3125148831554884be4658cfa750c89.nq.gz
│   ├── bfbeb561d7cc69829f3a40be079b27396afa9d1d.nq.gz
│   ├── c2373a0af0b055a1c3c93fc407999a13f275eb09.nq.gz
│   ├── c51def15246d11a512a92ab210829a58f3df4aa3.nq.gz
│   ├── d09b0d5b12c8d9524253ffab5a69b0ed1915bee4.nq.gz
│   ├── d2a5a8da7ffde7bc6136ed13dc8780f2feb82adb.nq.gz
│   ├── d759cb2f58c3dea0eb319a6ba6bee0d55e0f04d2.nq.gz
│   ├── d7d2043d6418a4bc658934b27a3bf929235b02e7.nq.gz
│   ├── dd2abcb60d9cdf79dc1aece333c2d255fc37cc6e.nq.gz
│   ├── de7ba42bc06bc4e38ee2bc66baa777125598f984.nq.gz
│   ├── e1f8cb491907d6ccfa2c841ed65cd728ce3a78f8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e920a07677b18e14f446890a1c20d7f9d4bd29c8.nq.gz
│   ├── ed6d01e682668db2c66cd69dca3dee9930121a93.nq.gz
│   ├── ef715a73c55575989ee414eddc23f53ae46005b8.nq.gz
│   └── fab813f9ca50daf665e64ba41cf2a3fe4d13869b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d036c00afa4e8c3077ab53a22290ac19fed652b2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 60 files
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

[Pylons/venusian](https://github.com/Pylons/venusian)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
