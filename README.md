# Repolex Knowledge Graph of asottile/babi

RDF knowledge graph data for [asottile/babi](https://github.com/asottile/babi), parsed by [repolex](https://repolex.ai).

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
rlex download asottile/babi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── efcf4cb26a81f4beafa79fd8ce93456e627fb2fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── efcf4cb26a81f4beafa79fd8ce93456e627fb2fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 0239f0ceb09db903cccfca0d281934b416f86af6.nq.gz
│   ├── 056edef91822ed8416afdd6c131e6d5b73c32651.nq.gz
│   ├── 0612458bc73d739323f412e9f08cc7c5ea020883.nq.gz
│   ├── 0788f392ceac7ae8f19ee3dcb11fb05fca9cc8bd.nq.gz
│   ├── 08542d4b12581b2b1015464b6d8cdfd3dc2a52bb.nq.gz
│   ├── 0be41f7aeeead5f7e4554e0987c71b2346f4042b.nq.gz
│   ├── 0de2a76cb93bf305016495ea5f933ca7d5e5e757.nq.gz
│   ├── 10cef01bc8e9c3ad394cae9b3ce9159a29b327ed.nq.gz
│   ├── 10e38b6f50cc761f0c6da97637952e3f1e89d61f.nq.gz
│   ├── 1413fb9d3e2ed722ad67ef50711dfef7024c8e2d.nq.gz
│   ├── 1cea4b1b180523636ef372aee36eb5416498c0e1.nq.gz
│   ├── 1e466ddb8576be661b889d54ec99c4545433995a.nq.gz
│   ├── 1f79543dbe5e342d717b289a18ac890cf892f0bd.nq.gz
│   ├── 262dd1a700c36055f5497f7dfc1c23d7598f9962.nq.gz
│   ├── 277f32710b3c6887fe3da99c384e1a855b1c3fa6.nq.gz
│   ├── 28397e4c66fb8c30ae35ad20a745be67fdc547fe.nq.gz
│   ├── 2af35266728ec592575aeb0f3b914cb706e8fe06.nq.gz
│   ├── 2b4d9f36f276ab0cce2511ce70a4e3499f538358.nq.gz
│   ├── 300099c8921801b7b3c982df520b4e9901ebb57e.nq.gz
│   ├── 349a4599f72ac8b0a88962d353e4aec21e139924.nq.gz
│   ├── 3a72e5a9588db9b702a5c0677a23577b24b2318f.nq.gz
│   ├── 3d587b3242f300ad99ef9d2a72b6bad33898ccc6.nq.gz
│   ├── 3d93aefb2da505dba9c0114404cfaaeee5ad0d3f.nq.gz
│   ├── 3de2e1e39f62ec1dd6980c6365e64177ee0883a6.nq.gz
│   ├── 3e56ddf2c13478410b33d0fda8efe8b0fff35726.nq.gz
│   ├── 404e599f93618eb6538dd01acc53532d3c23dddc.nq.gz
│   ├── 413552d9bd471566bfe605dd9ab24f28d9d97a03.nq.gz
│   ├── 47105bffd90c70cff18d1a5ee563a951875332e4.nq.gz
│   ├── 4c666cfae64d436ea08ddf91ca86f20cbce8d4be.nq.gz
│   ├── 4ee14bed85189c1a294aba0265ce9258a190d61a.nq.gz
│   ├── 4ef4aef43365f3d5994f27b5f418db158b58393b.nq.gz
│   ├── 55dbdfb22eee7e1eecb011321bd3fc8a232deb58.nq.gz
│   ├── 56970d7a522bb5cf0e4f503cfdd8712249689385.nq.gz
│   ├── 5a4128de7f16972c216a66cf8d9b13716c1b6111.nq.gz
│   ├── 614b2ea8e0f30f47af12db8252aef0bc838f6a2b.nq.gz
│   ├── 655495b412448dbf50791440236d595a786f9b58.nq.gz
│   ├── 669b29326c1f55cc3f8c9b007b8b5c00ca905ddb.nq.gz
│   ├── 6a8bd123b8ff75ceee6ec6bbaaf2d31346e61713.nq.gz
│   ├── 7352d163e2713adf6366db772f216f6a4833e729.nq.gz
│   ├── 73d058fae0c63544d08973cb61639a223e3e66f0.nq.gz
│   ├── 74c1ce07c482e841f5583cc84c95c7fe95807842.nq.gz
│   ├── 75112f23d10fcf5870a560bc7acd57ca57e20457.nq.gz
│   ├── 770b7c9d5332eb13493825d7e42b432b2e4c916d.nq.gz
│   ├── 773f4558e3ca12a5f7d9293a459369bf24e20b4a.nq.gz
│   ├── 78e880c6594639be2726eed735797511a8490f31.nq.gz
│   ├── 7fa7781f55c9fce8c2019fc3122141c4467e566f.nq.gz
│   ├── 81de171ce451d4eee92a508f9bc9e1932d942c9c.nq.gz
│   ├── 83f2ac8c626c709b9363233f5d6d1fa89070d872.nq.gz
│   ├── 849299b9fc910775a11fc0036ffa60ec51f4037c.nq.gz
│   ├── 84df1978a49c530dec7c222b39f6cd130b4f66cb.nq.gz
│   ├── 87d9786abbdd8bce1b14db3e22c07f52407c5570.nq.gz
│   ├── 88edd1f531a9d65fa511ecce7d7bbd3f910a5499.nq.gz
│   ├── 89639ab79badc5a030e6f5be45b96f6a4415ebc4.nq.gz
│   ├── 8d9a99da63b6f3209a0f19b0bd1daa58d839bfb4.nq.gz
│   ├── 94ae6f0771dbc5dcb5bd693a4b8eed119f491a04.nq.gz
│   ├── 94d3d2dceeb5d573da019ccd03a1af9a5bf45f78.nq.gz
│   ├── 9519ed19de20b8f2d0d99b55527448bb0dac2cf3.nq.gz
│   ├── 969123f07bad2418932301df653a98183d88c6a5.nq.gz
│   ├── 985baf6c91237191e31d7e45030fc85c004c0ec3.nq.gz
│   ├── 9edcae49c05c892c3c6dd9a65c846fe0a9fd528b.nq.gz
│   ├── a3c9e8e339f3cdf46d4d0c68d179dd16cec8ac11.nq.gz
│   ├── a9ede916b1bcd9dc6d9ded6a0f18251478765564.nq.gz
│   ├── ae2c419f10699869f26e5bbed9c378e3b7674931.nq.gz
│   ├── b1447c3015af9511f2dee402ca4b5ad62adf5dce.nq.gz
│   ├── b36e7ada481e99bdce7f830b6b56f16d5b212219.nq.gz
│   ├── b8a36e2d64855884f3433d6a80915a0bf97e3184.nq.gz
│   ├── bb2200d6e4aa5f951681fdb970b380d1a5d822d5.nq.gz
│   ├── bcbe0f12917de26c02f95fa9bad0e26ffd511d0e.nq.gz
│   ├── be7f2314cdd984323d0469c50a0c48963446dc16.nq.gz
│   ├── bfabd6cef3b8a2593836a30dee3d2f407fbda289.nq.gz
│   ├── c1533a7328c794ea994ff33f7d938f59466b5592.nq.gz
│   ├── c1e6b22e6e4a975fecdad4a46f76615d8f1dbc63.nq.gz
│   ├── c3b2d7b3b6458df389f54a1218ac02e9460351d4.nq.gz
│   ├── c3c8fe2924b8c6c9adedce3b2c567666ecf3af2e.nq.gz
│   ├── c55e599452ac50c25327401a7357debc92a30838.nq.gz
│   ├── c602fc4baac53ea656e0f243a196e4b4d10fc9e1.nq.gz
│   ├── c744e112f45a534cdb1e14eeed24b10dd075a2ea.nq.gz
│   ├── ca837661b403b13a3bff709808a62401103e4736.nq.gz
│   ├── cd4569ada93c0dac5b26c9d18b2bfa374ecfb223.nq.gz
│   ├── d1898d740482ed6fa70fa1ecde625f1d79dec0a3.nq.gz
│   ├── d4c5ae74986ab75a424ddfb1653cc575251b09cf.nq.gz
│   ├── d50251241e7bac3d4dd3b9ad2aec7e9349179edd.nq.gz
│   ├── d549652072f99564d87db2da7f0ec21b4a8ef0dc.nq.gz
│   ├── d7981097f7999f8d0cfde9a9802048afa6b84d0a.nq.gz
│   ├── d7d76167537bc15861c88e922cac4b843c7b8394.nq.gz
│   ├── d8bdd3a8d07fae6d21f8094706db1d5901c6506f.nq.gz
│   ├── dc3e14a1f1f30fc2060d62aa237f7e30e3896367.nq.gz
│   ├── dd571df3407003cb4326869c5218ae04d8785621.nq.gz
│   ├── e1c61ec195203cc5ee19c984a2840f5b174ccaf9.nq.gz
│   ├── e229de433a0a11a311e68215a22104a62041bd2b.nq.gz
│   ├── e455d10009c5e91a8d4a81647ed31a2607fa5be6.nq.gz
│   ├── e5335ec866fd59d5c6cead2258bc2fbe30cbc727.nq.gz
│   ├── e535d4688bfafbaabe0649315b3dca5b1c2c5d24.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eba810ac052b3a9c1fab725f47c0aa6426a4c60b.nq.gz
│   ├── efd0d6539f24750b4cbeb55e6ae895f966249855.nq.gz
│   ├── f2399a135498ecc6bd2b3095c56bfe66a621bcce.nq.gz
│   ├── f34325635072c89d6db51a428d90e4fd7818df9f.nq.gz
│   ├── faea17d5cbee864be5e354098ce430bdfdf3d111.nq.gz
│   ├── fd1272d726747678727115c741197ae43dfd1d6b.nq.gz
│   └── ff5df83e1de97f3fbeab9349f7cc80755dc44bcb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── efcf4cb26a81f4beafa79fd8ce93456e627fb2fd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[asottile/babi](https://github.com/asottile/babi)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
