# Repolex Knowledge Graph of ansible-collections/community.fortios

RDF knowledge graph data for [ansible-collections/community.fortios](https://github.com/ansible-collections/community.fortios), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.fortios
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 472b28853c930071004c3d7bbf1dc8c48bdc66c3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 472b28853c930071004c3d7bbf1dc8c48bdc66c3
│           └── chunk-001.nq.gz
├── blob
│   ├── 04877ff5d4439523eef13c855b76690576185aa5.nq.gz
│   ├── 07a69557521d7ec2087d39d281ff85de74bad190.nq.gz
│   ├── 08e382b875a719a73a07e78ac82e731d21d819ac.nq.gz
│   ├── 0972cd2e8e58d51f20c6b0d23d8f89154c7ac076.nq.gz
│   ├── 0a0e43d157b72a8548c26f73bfd7e7929ad4dfc1.nq.gz
│   ├── 0a0fa7bd2f29d00ce8fdc81ba9279e226846f7c7.nq.gz
│   ├── 0af21b25cd635ab2fd7a159bc4eae54fc17db8f0.nq.gz
│   ├── 0c9bdcdcc0ad296d2fb7cdd0eb46382b29f125e9.nq.gz
│   ├── 0d3a3005d35361aec4ac3f4df0fd3e1110382323.nq.gz
│   ├── 10b21a4c55e48eda7166a90490d34565402fcb9d.nq.gz
│   ├── 15e63a29f90ece64aba0577c627bf2d610ce7562.nq.gz
│   ├── 15e8977fa90bbde388cf5d20740e1d9f26eb03b5.nq.gz
│   ├── 18a675dee6a331a92f8ac653f226d311fc7fd3c5.nq.gz
│   ├── 1b3ce8d134ce6dee1a002a8a874aee781ed519d6.nq.gz
│   ├── 1ceb7dbb363a5d6303bfe93711efd50adce263ec.nq.gz
│   ├── 1e9a0f7d759f6ed667d5657d24dcec96c6fd594c.nq.gz
│   ├── 2ee3c9fa9b21eade729afb639808ce15cfbbf6b2.nq.gz
│   ├── 315ee7cff55842a719a5f9c3bebf7dba749e7398.nq.gz
│   ├── 31b71288a712679c4fbc3fffa5a2dab5e456700d.nq.gz
│   ├── 36ee27096886c2851de1bb03fa176aff3e0f3b42.nq.gz
│   ├── 399fc4c8d2794b4705d0ca8da898ed77427ff208.nq.gz
│   ├── 3ece0f22284469f03e06315c20b29dde311941c3.nq.gz
│   ├── 4878075234da1b62680af9080094dfc7e9b6ffd8.nq.gz
│   ├── 4a289a0fbe880bdefaf0dd3b72699b4aaae9256a.nq.gz
│   ├── 4b5f8996c1a7f2e22bc38d2d4aee9ec1106b3d75.nq.gz
│   ├── 4c65abf5b4e8a3dcd8807f6aaa7fab7a453c91e1.nq.gz
│   ├── 50cd95cc652504912aac5caf15779bcc888df5e9.nq.gz
│   ├── 56bdd9a4aa6378ccc1a9af7996baf0dbd0d6217d.nq.gz
│   ├── 57edff901ebb64f40b0a1408b98185ac29638914.nq.gz
│   ├── 5c8fadde82f81b000da191f7799c12a0cc3d1d66.nq.gz
│   ├── 61579327c79866304bc5b86fa9ce0716034e96e5.nq.gz
│   ├── 6620275cc01af1f37d17a8fcd093d127ec1c6773.nq.gz
│   ├── 66d2bcd2ffcaef619cbdb880d4f66b86656bcff6.nq.gz
│   ├── 68f0962b7250f8f157eec841b1e74f69def9eba8.nq.gz
│   ├── 6d7f4040171ccb0b6574653f7de21ddae083bd11.nq.gz
│   ├── 6e429fd2401b8aeaafc644abadff9852a7e67eea.nq.gz
│   ├── 723c29b11c3493ad7a7ca08b7de106e05cc07102.nq.gz
│   ├── 74e85e30c44c423ea100f2ddf2ec2a753242030c.nq.gz
│   ├── 767573e22be70e423ecf6f1e3c2347505b6062ed.nq.gz
│   ├── 7b65393fddb73779a4699e64e9b284cf144eafc4.nq.gz
│   ├── 88375cf16a1f0c469fb847c0515330ce9060f5f7.nq.gz
│   ├── 8f0c6045f20b7ba3c4c4f58f081214552e7a60ba.nq.gz
│   ├── 91b6532afc12a857f93d5c9e559764c52a58b4bf.nq.gz
│   ├── 96325db1ba04a2b0d67f5cf16765efe4ec50aeec.nq.gz
│   ├── 97d4a3f00ff20bc74070c90d9368ed2699163da4.nq.gz
│   ├── 98f08ad6a8474fbcc3e338436bae46663d4aa4ae.nq.gz
│   ├── 9c8c0ad60fa30dcb59db9e5451e0c555bd74416e.nq.gz
│   ├── a0b39ab16b2d68f63c5cde8055619931ce4f705b.nq.gz
│   ├── a13c654e5b0f6aa66e3740823e462096ae5bbeb6.nq.gz
│   ├── a3a0353c8a738d22d5bd93f4eef8456e6864004e.nq.gz
│   ├── a5470b68048554209764231a282ef5c2819fdd28.nq.gz
│   ├── aabd298596fe1fd9b4d53ef1002152c5ad671c72.nq.gz
│   ├── ac5e918a898cf1d9dc886c3559a00ddbd2008b66.nq.gz
│   ├── adba2e4957f13a0ac9c6f02b69b703a78242d934.nq.gz
│   ├── b0540e97003f1ca21284af447f8fcb187e5fba0e.nq.gz
│   ├── b45c6e01ac56188d76a404916001235530d95f73.nq.gz
│   ├── b51e3fadfab686b09d96f5dedbb4f0fc4cd791b5.nq.gz
│   ├── bca775ccfa0da1f4104f51f3e4dccbae51eef439.nq.gz
│   ├── c060c00d21723308546b9b257f509b3417f8b0f9.nq.gz
│   ├── c718869432c99209ee702cfbf107619cfcecd707.nq.gz
│   ├── c834414aa8540a6b4fc3cfed7f2d8f5ccb15bfe7.nq.gz
│   ├── c8dbfc7750f65feea0580571f2d0a10557f39451.nq.gz
│   ├── d84606cce9bfb0cc9d2192f34ae7ff530579ca77.nq.gz
│   ├── da499cbe4766d3c71ff56d66e3986e786883b02e.nq.gz
│   ├── e24f11463caadfa112130c6b91fd67a7ec31f611.nq.gz
│   ├── e36dad95f07279316573d4e2c8c0a8f15eaeb3d0.nq.gz
│   ├── e6157ff4b46de28bea534c065f1d7679cced8046.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec804d278dd0e7a099f440a84579edf8a6c59eef.nq.gz
│   ├── f0b0fd9c8544cccbf5454db1753345017d69d325.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f36e90908074bf67ae4d9e55040b7e1192b63d3e.nq.gz
│   ├── f3e0d5aec3dd156db1acae11c1af8620d678156c.nq.gz
│   ├── f6bc82b71022f09b2e257ddff85c2411cde3c573.nq.gz
│   ├── f6e2785b264766669be43f211ab230ed7f7ace77.nq.gz
│   ├── f89f1c98b01dde7903f935bb2a240b811b6b26c1.nq.gz
│   ├── fb8a3597f41795b30d9366fa3df14ebf2e5146a3.nq.gz
│   └── fc1eac658435adf948120c92387dc7672c66c4ed.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 472b28853c930071004c3d7bbf1dc8c48bdc66c3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[ansible-collections/community.fortios](https://github.com/ansible-collections/community.fortios)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
