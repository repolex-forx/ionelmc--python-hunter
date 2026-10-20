# Repolex Knowledge Graph of ionelmc/python-hunter

RDF knowledge graph data for [ionelmc/python-hunter](https://github.com/ionelmc/python-hunter), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/python-hunter
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b29fb483a14db7cedbb68d354ffd6188c0415c68
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b29fb483a14db7cedbb68d354ffd6188c0415c68
│           └── chunk-001.nq.gz
├── blob
│   ├── 009a913cde5985359d40200f00c0efcc2baf5582.nq.gz
│   ├── 03e05a2da26238a8fbf3316aeba0ab216ad06abb.nq.gz
│   ├── 0b8944ade1ad6b44cdeccf66ccb3513634b3531c.nq.gz
│   ├── 13c8f1572321dafbd600f5beefdf1272c03f09b9.nq.gz
│   ├── 1ec15597e09461ca77748877aee500f53292fb66.nq.gz
│   ├── 1fd8bdc680722830264a5da13f280d13a9f32035.nq.gz
│   ├── 20ebe5771e240246833ec33c3ad477dc0cb08167.nq.gz
│   ├── 28b332dd653eaa00a9992bfad7ee0e8772e5c3e7.nq.gz
│   ├── 2b22cdabbc2678d47dd3015337f79fd42eede512.nq.gz
│   ├── 2c70b41297f3e346e03342b32cfaf94e18c42810.nq.gz
│   ├── 2d81bbce476dbb9e2fddcd3ba0fdae8dd3d9c5b6.nq.gz
│   ├── 2def86d6f9f4a3c2e4ac9213c7cd97758dc43735.nq.gz
│   ├── 2dfdee8fda6f56161efdbd7e072d367620cb578e.nq.gz
│   ├── 2e311072dddc0b5e60f34a574c6faede07cda2ea.nq.gz
│   ├── 2fe9e11267e66d761a35491fe245bc97dfa581b8.nq.gz
│   ├── 359505cc2c7484c30d54989934f83a30cc095b56.nq.gz
│   ├── 3a20dfb85558a19ecb289bc048cd441d36b99821.nq.gz
│   ├── 3e365e3a79b4abe54e3831ecb71690140648b834.nq.gz
│   ├── 3e4c1b03d8b4e493bcb742fad546977c2585cda3.nq.gz
│   ├── 42f04ff5eb99e9f18652315602197d0ab1a2d064.nq.gz
│   ├── 4509e99718d9229209c209229db573491b786d93.nq.gz
│   ├── 48334525d8176552ba4b4e77999c6ef20d85b0f2.nq.gz
│   ├── 49e8e60cb8dc2bf2f306fb82b89635cf656859f1.nq.gz
│   ├── 4b0497bd1ac0cedea43b9ec696521973c1c80676.nq.gz
│   ├── 52bf885a93fcedc3975672a67d9cb51a9c37be7e.nq.gz
│   ├── 561731b986ddcfc25f401c828fa3db7827911da7.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 56c3ad1afff70b861b2e87dc7d634737586673af.nq.gz
│   ├── 586c7367de1cff5d362be309c0a4014b0905edb1.nq.gz
│   ├── 6657c46d55187637217f40129823d93ed3d37497.nq.gz
│   ├── 69c94b64049e6580c7ea461969616e2d1d194396.nq.gz
│   ├── 6e91c39e0a3ee9d59661d0ec5dfe779a767a391b.nq.gz
│   ├── 6f308659d465495e7c4d98d71b3ae5933c08e8e0.nq.gz
│   ├── 70cf2af817bfb524bbeca8d83b0fe4cc17993f95.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 73d6224593f8e5d41d9090151832d4863944ea48.nq.gz
│   ├── 76e28695ba3577434769d3aa7457d1e5038ee159.nq.gz
│   ├── 8000ab4c58b6aa6db6c9a80162684bd273a5ef61.nq.gz
│   ├── 81d6aeb55ed9998f79d2ba402ae08490c4c53b45.nq.gz
│   ├── 8616a59615a4a6e75db5d00127622a21e4e75125.nq.gz
│   ├── 8a39a5a4ab85c094a9c812a28d40cd37b5d41799.nq.gz
│   ├── 8bf9ad3328829a8dbe04d522b150d9b9622e9649.nq.gz
│   ├── 8f8054d37b6daa5aacc507f0e5907b86d0de3d6f.nq.gz
│   ├── 93f67988ebffc316258cf7199cec819f4415c685.nq.gz
│   ├── 944a9ae54da15f1dc7a1a0ece5de2d9325c9c57b.nq.gz
│   ├── 95bcd7919b0a28fb8072e001942c69db01e0557b.nq.gz
│   ├── 982f6576291a6e60ef551c08a0aff6c530dcce75.nq.gz
│   ├── 99332762e7fa86bedee781f2af762a114077ebea.nq.gz
│   ├── 9a0be3fe1faf46d1b74a4d849cbdd8a58dc364a0.nq.gz
│   ├── 9c1450c933ec8f6bbb11b97a000b958b8ac302d8.nq.gz
│   ├── 9f0bdc4a80647ac08f014672017dabc069dc477e.nq.gz
│   ├── 9fb2c23dcb549fbfc8ce784255b25ef8b0a027c8.nq.gz
│   ├── a3057c0a11ae919f133b05f893a69f00fb9db548.nq.gz
│   ├── a8796d46a3dfea12d32dfe6247ea236a2f068bb4.nq.gz
│   ├── a9a2ce8b0d083d5874e10d8453b2fd4b1c354673.nq.gz
│   ├── af49513494c1082c13b0802817c0c8970201cfe4.nq.gz
│   ├── b2d74f55071a721acf6a633c114850fa28ebd126.nq.gz
│   ├── b58764baf2436fe994bdd2d3373799cf683fcf77.nq.gz
│   ├── b7279ab42220d59992e68c36925ac5d17754d93b.nq.gz
│   ├── c03e307ab39cd6807b9bc0d8f404e716707c2533.nq.gz
│   ├── c1a280731498687c7c31c989352de02af0ada697.nq.gz
│   ├── c774d659b9917c1b27db5a6246e7df157ae5b89f.nq.gz
│   ├── c8a7ce7677dc4e6b20f14adddf6cdb9aafec8dab.nq.gz
│   ├── cd99c9688f0cfa251a0755deb383c16094706554.nq.gz
│   ├── cf8dde02506d7431eea121812ee518d575e8b96d.nq.gz
│   ├── da6a44f2d2954f76a837978a36584b041c31cfb8.nq.gz
│   ├── de4f3dfed57df39a3f4f4149ca6ba76677947371.nq.gz
│   ├── dea7b0cdadf7d11fe2cd3dd48081d172f289faef.nq.gz
│   ├── dfa6e0e2c88264f122209ca88da90adedbf1ecd4.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e25d0d58d75829419222ca5cf9d01ad3e2266730.nq.gz
│   ├── e37a7bff169e2afa28f81bece0fbaad70a49910a.nq.gz
│   ├── e4c2ac7f0076045e66e12235aa846fe561197f0e.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── ec67ced1d7a4a58227c7241cb3d3352e3c28aa1d.nq.gz
│   ├── eccab3317ba411e480cf2a886df580a98dcf7de2.nq.gz
│   ├── ed07b5de2aa89146caa60fa17a4e72930fba4436.nq.gz
│   ├── ee69e2c52b5c07c8c75aeabe78341dc093a708b6.nq.gz
│   ├── f400a13802ce588842889f2096a3cb9aaefe83a5.nq.gz
│   ├── f5efe0d5d0df931c02be8ae8f2a09f19597bb566.nq.gz
│   ├── f8b646583d3cd0de8d625d7508160e1d55bcb36f.nq.gz
│   ├── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
│   ├── f97c9a0340dc2fe5bb24be6234e8944593b89358.nq.gz
│   ├── fa4b8a104e0cb58bef5b498aa4eb6b8d33b8b39c.nq.gz
│   └── fe120a2cac2255b8ea1258c6f1886728f3a83514.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b29fb483a14db7cedbb68d354ffd6188c0415c68.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 93 files
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

[ionelmc/python-hunter](https://github.com/ionelmc/python-hunter)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
