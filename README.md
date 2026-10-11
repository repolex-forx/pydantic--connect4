# Repolex Knowledge Graph of pydantic/connect4

RDF knowledge graph data for [pydantic/connect4](https://github.com/pydantic/connect4), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/connect4
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 339a8902e67e78d315760d5d7f52ad2c5f3087b8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 339a8902e67e78d315760d5d7f52ad2c5f3087b8
│           └── chunk-001.nq.gz
├── blob
│   ├── 008be983ac265343344f3eff4e265e46cf054b12.nq.gz
│   ├── 00a1b1abfc9c0b04a2fb375322f90d8eb3a10e2b.nq.gz
│   ├── 01f7ef913e4c48e1911afb429141296801d8acc2.nq.gz
│   ├── 046dca3aa690c5ca3490b88a703932de9621e46a.nq.gz
│   ├── 079f7b573567f30a008f9b992922f0cfe8b30cf8.nq.gz
│   ├── 08b4c02735d2fa8c92b6e514028559b3de2d9257.nq.gz
│   ├── 0c6e2ac6f13e460f54ab519c8548e005f8ae8b75.nq.gz
│   ├── 0e22ec82a01af393547695e6f02d4ce04ac1f858.nq.gz
│   ├── 0e68246a44a4153b21432bc3a0d86f8f22fc1592.nq.gz
│   ├── 18bad822ec00f3d22a69bef38cfcd51be579d063.nq.gz
│   ├── 1c19d620b555640d6e917fc7e45839a94e47c62a.nq.gz
│   ├── 27649c54efe07ebcedca52817e606e0a832476c8.nq.gz
│   ├── 2cd30648c109fdaf015d32d2a308d4c10c71fda0.nq.gz
│   ├── 2f2e68a7400437e185211f319730138cc9731e7d.nq.gz
│   ├── 337a3d7a1d62d57acfcfc73c6e5483a9a7401bf1.nq.gz
│   ├── 3f25d2f3bc5473702dd7874c8715b915cf082ca1.nq.gz
│   ├── 3fcf991a8068c442c49d9a371d72d8b0d93cc5ec.nq.gz
│   ├── 3ffa44ca1f43775dc572b7462506511e49d51b0e.nq.gz
│   ├── 42de47069a7a66c4b207e5f9f6765266a667a00d.nq.gz
│   ├── 44f5c484ff6b9089fb4166ece3f6c5aeaad41378.nq.gz
│   ├── 452e20abcdb324b6694de469aca3cb16bf7e2946.nq.gz
│   ├── 466a3f4dbbd2c9920a3e998cc288be495a6649a1.nq.gz
│   ├── 47a22e8db1191051f47fdb15524bbcd4365651ac.nq.gz
│   ├── 4990b62bb418a13a40322ee063baca8c6ae9a96d.nq.gz
│   ├── 4a2c71578b56f21ad3dc5705e6a09a52eea10286.nq.gz
│   ├── 4ac0f9bf75c27a1901cdc9a814c2eafb07ee6297.nq.gz
│   ├── 4ac69eb4bc4ca2ec7f92aff3d6bcdfa1bdba5156.nq.gz
│   ├── 51494da27551c71962bc2b7c72dfdb97b207fbbf.nq.gz
│   ├── 5601df0bb2ac99cc7c0ec3563bfb44d4504c382d.nq.gz
│   ├── 58029a1913aa2655dd50d3597e4acd1e54c9ca36.nq.gz
│   ├── 5b1e36058814f700ac0836c3c83354fec2ad67d6.nq.gz
│   ├── 5be8556e38c58eaa276071d0d0e2dd339ad15cd6.nq.gz
│   ├── 5c04108eca0b2947b7b2df36146cfce7d66297b2.nq.gz
│   ├── 5ee4b6d5acded376ef60a2372052325dae501168.nq.gz
│   ├── 5fc2108c3054fea83367e6742d8cabbc1f361fcd.nq.gz
│   ├── 6ae73ad331810793c86b4fa769b40d030e4cdae6.nq.gz
│   ├── 6f4050aabcd5d74b65adc8309a27d060f00bdf3b.nq.gz
│   ├── 76fb65d3db3516ab3410db401b12ce56d11ea920.nq.gz
│   ├── 79ad019948018cca252456297e4071c1cb235660.nq.gz
│   ├── 7dd3bb9ad39765004fbf3d6804cdbcbf35236273.nq.gz
│   ├── 8b7c0839dc23aeee7badd31ecab1dbaf015ec803.nq.gz
│   ├── 8c7e6b48855a8ba7e3209c95db303f52da233805.nq.gz
│   ├── 96b16238b948f87c5b78ee49e46a440f1a81887f.nq.gz
│   ├── 9fc7c790b30b781c55b90886b09e161d5d387079.nq.gz
│   ├── aad9de3f04c92422104f6d14c9ca7b5e56913f25.nq.gz
│   ├── af8919e6647e44f86565c81238c71526530c19ca.nq.gz
│   ├── b8f74451bf41fdc3b204458e496ba77a6c209a26.nq.gz
│   ├── baf6b0aa85995763cbd5bb32956bb580a3ff5379.nq.gz
│   ├── bedb7378dd6f6af3af27ee274161a97cafc0f329.nq.gz
│   ├── c85f6a9ae54d5495a5ee9cfcceda2218f3995bb5.nq.gz
│   ├── cebe91f6e3b80da3abafb3f7e194cc852f626059.nq.gz
│   ├── cf518834c363ccbdd4be19f215686a747e4f160d.nq.gz
│   ├── d3ee959f504fd3a3fd600e8659a0d6fc17a1f9cb.nq.gz
│   ├── d73032d47c2e3f1de1f16887e35c2e398abb6ab4.nq.gz
│   ├── d94c504c74da55b17923a9057ddaefb5bc039f56.nq.gz
│   ├── da4d7458263d77eaf0f9f29ebd6399d8d98b3d4e.nq.gz
│   ├── df7fbb9299a2450c04c43edb4acb80718f8f72ee.nq.gz
│   ├── e21ab4ef8fbd1d3c609cccc4822e1fcb4bf64023.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8ee0106c498aba4dfdcf4ee258b5b773015da57.nq.gz
│   ├── e9baae9a8688f71080e9236a7efd727a7fefd8c5.nq.gz
│   ├── ec27518da965de8df9bfd383f99853b5ba6b8c1f.nq.gz
│   ├── eef3e1a88b9fe9a5666b84f9798980a16fce815b.nq.gz
│   ├── f0556f7bd8fa8c52729f9be1374164cf66e8114b.nq.gz
│   ├── f30c09f00a3568b23514f19f00191eb23e2181a9.nq.gz
│   └── ff12abe07980a50b2f5215f5913dc0f8b7ae2bd8.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 339a8902e67e78d315760d5d7f52ad2c5f3087b8.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 73 files
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

[pydantic/connect4](https://github.com/pydantic/connect4)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
