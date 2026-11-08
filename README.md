# Repolex Knowledge Graph of canonical/tmate-ssh-server-operator

RDF knowledge graph data for [canonical/tmate-ssh-server-operator](https://github.com/canonical/tmate-ssh-server-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/tmate-ssh-server-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7fedfcfbf13c06316fac8a6e0016c2d2f10bc9fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7fedfcfbf13c06316fac8a6e0016c2d2f10bc9fd
│           └── chunk-001.nq.gz
├── blob
│   ├── 01c7479311e9015cc4e0a1ed5606c02ee303f985.nq.gz
│   ├── 02361050a74f8c7508cc12ed3d26ae641a0352af.nq.gz
│   ├── 025002aae5995ffc6f250b4db7f311ec4ceefe8e.nq.gz
│   ├── 05f5ccb87fc754ec7316005b86737957039b509b.nq.gz
│   ├── 06ebde17ff7af1bb961aa27219ca1193fdc892d1.nq.gz
│   ├── 073ccfceb10f2f5102059fff3aa22166c88f668d.nq.gz
│   ├── 0d402e5e794c5753e310af29a1d3f882f10d011f.nq.gz
│   ├── 0ff43cda993107c14b34611adb1aaa08d4d8d327.nq.gz
│   ├── 12a0bb9f64e1e26be9f49a0853c74e288248cb9f.nq.gz
│   ├── 16f83ec615d7ba02215eb3556fee59b02c770688.nq.gz
│   ├── 213ec01d15a4e63159e610b387073bf3c6028137.nq.gz
│   ├── 2203e18761eb2420c67677346485e097a2f107f5.nq.gz
│   ├── 2513df62bb49ef025f4d626d8c9a8df9b7cc366f.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
│   ├── 2a95889654b5168fda2e4e0238aeb327b70ad796.nq.gz
│   ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
│   ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
│   ├── 3571b4f63a192181ab533ac98fb7e33140f28994.nq.gz
│   ├── 39c04edbff1522fab2469d0929f7a750855f321e.nq.gz
│   ├── 3a781086230b2d1249d692d70afc0672e943eaf3.nq.gz
│   ├── 3d0925f9a8d4601d003e1ae4911a08a7cb2ed3a4.nq.gz
│   ├── 3f110d596d2b571555863363a2179a37ebb86fef.nq.gz
│   ├── 3fed885d525aa423ab9ffeed0b4704e0f313e686.nq.gz
│   ├── 42e74a0a35c0a815733ddc1615c7ca72de374387.nq.gz
│   ├── 4f13f0380d610d4f0d7d0f6868fefe56d5f1841a.nq.gz
│   ├── 4fa4b40ee1d6c551cf66ed3f022768063b4e1bd2.nq.gz
│   ├── 544f89c2a7cedb6f808cccc62f564d45f6987ac7.nq.gz
│   ├── 55373d51d04d2593c9e4887d769b29fbf39055ac.nq.gz
│   ├── 56a6051ca2b02b04ef92d5150c9ef600403cb1de.nq.gz
│   ├── 5a0d6ad2b091429c48b9b21fdc0748ae01616c8f.nq.gz
│   ├── 5fbb2168629fd4fd8989799af701b25f4e7c1762.nq.gz
│   ├── 622d8a7fde576ef243306990a61385fe6cefd002.nq.gz
│   ├── 637cc0a8ee40c32c3b29a760116dd03fbe01bc5c.nq.gz
│   ├── 656bc395df198d998a43c0e65146e2484af70919.nq.gz
│   ├── 662a8018db20e6a12dc7911b65025de56c0fdaa2.nq.gz
│   ├── 6755a2c7dfa59d01577c8cc557cd7536e5ae0689.nq.gz
│   ├── 684441b6e944258c046aab3ef9bec2cdf1e8eff0.nq.gz
│   ├── 6dc9552caf44205f712d0b75d4d7ae95bb9d419d.nq.gz
│   ├── 72b9786142f406d724ee06c3dceeb05d70c9a702.nq.gz
│   ├── 7518fc90bf78b2b347b694f695c6e1ed120d523c.nq.gz
│   ├── 75346220221836c2a0a95476bf1aefacff61373b.nq.gz
│   ├── 764cc0e5911fec873bbd62bfb124e012bff48522.nq.gz
│   ├── 7749e2bcb09a0cf213b0cad8ed3a96a36985667b.nq.gz
│   ├── 799154697c924d3f28612bba321ece22ce279f7b.nq.gz
│   ├── 7ce903c7f5a1d64eb3d42ede87b62f211b1ecea2.nq.gz
│   ├── 7dce1d59720fabf0a3becf8107e355a0b79a466c.nq.gz
│   ├── 7f582241348273eeb6c5598723c182bc9d4b515f.nq.gz
│   ├── 827d418fb9944f31c5cee1aa1772218d06f630db.nq.gz
│   ├── 82dc1f3ebdc39093585ef1d90c1263909c0b4155.nq.gz
│   ├── 8302bc1369c62739a9268b17b757a9936af31d30.nq.gz
│   ├── 85e07a5f31f6b4b701888d2a58ac666010fbbcac.nq.gz
│   ├── 90ad887fed8a0510005ed42b9c91fdcc1d85f64c.nq.gz
│   ├── 9182f16656759414829996cfc30fe2acb784d949.nq.gz
│   ├── 99bee505c547925c59a2c99252505e552dab6d97.nq.gz
│   ├── 9cf6067068286d0dbdfeacf441d021811ab9fab1.nq.gz
│   ├── 9d2d153310b71568099ce5510a3f7e48c0fcb679.nq.gz
│   ├── a1153a86f5036f03c4d69e06e63810a677e8be55.nq.gz
│   ├── a4e9f05d79ab725ed6968db663a6944f57edc1f3.nq.gz
│   ├── a6d61f7636e32b75ec6b6990b0c34a4858e36cad.nq.gz
│   ├── ac8054a4be1ebaff13f10d9f62c69e99fc89d7ae.nq.gz
│   ├── b39b4cadd0ba0791db23f8a112b0764d405fefb1.nq.gz
│   ├── b3a516179c343ecd3a2df798519031e09d91b88c.nq.gz
│   ├── b3e7008da3729d5fd681fc6fe38f0a21e82e4f2b.nq.gz
│   ├── b4703853405c6f0b56ed76226acf79242125cd84.nq.gz
│   ├── b7f78fbe33918cfd0d3f9327ffcc5a63cbcf3ffb.nq.gz
│   ├── b845a37f5520e5747ea34a81bfc3669bf7b62266.nq.gz
│   ├── b95ca9c0878d400d1e250f81482e4e145fd3aa39.nq.gz
│   ├── bc320fda872e17e2afd53432387d1f00712d53be.nq.gz
│   ├── bedc69955895532758aa306f530cb5ec2e49a10e.nq.gz
│   ├── c944c190514c1cc0e8b5b8bb0a2fb3d7fe564370.nq.gz
│   ├── c94c5387058101d180c3d185875039a30281d09e.nq.gz
│   ├── c9a0100e367d3ae327a476b47218d153e1843e0d.nq.gz
│   ├── cb48cfb19751b3281a46a46dc22c6eb86dcea528.nq.gz
│   ├── d11b47bfd867ed2cac61048fb7af061887a1bc6e.nq.gz
│   ├── d4ce0edc306a6de77c165ec95a2d5ccc3ec58b0b.nq.gz
│   ├── d664a2d4d60a0973deef5a813648f329a2abcf76.nq.gz
│   ├── d8a47d52837ce23e1f92ebbc6b85543278abc0b0.nq.gz
│   ├── df462db15aee2c3a2b224de5495ff55fff4d0c53.nq.gz
│   ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
│   ├── e74cb0e8670d68ea532266f10163f480b88427cc.nq.gz
│   ├── e8d3d774b20f002b351f48f1da9144d74c5b37a1.nq.gz
│   ├── ea9e6f5820ed32edc7a296832fbcb736a6e43104.nq.gz
│   ├── ebfb77b347949be9dbef1af2aa43642dec677ac1.nq.gz
│   ├── ede1d9989429a91dbe52365f87a1a39a5d50f722.nq.gz
│   ├── f002523f3f8adba85bc9c0ced6b4684271137352.nq.gz
│   ├── f1b79f590b5d39662376b37ddd11f3b8a86139f2.nq.gz
│   ├── f55165852a059c152540beb18231ee0cb151ab60.nq.gz
│   ├── fb3ce0afe75d79b77a4027c41198cd840a2558c2.nq.gz
│   ├── fb46081ca5070b8d905da9191cae901f2583445c.nq.gz
│   ├── fc25b9e7bc71f893553f7a3f63ffcfa41463ca73.nq.gz
│   ├── fcba45d66618fc12fcab01c9710a0acbf93007f2.nq.gz
│   ├── fd0dd5fa45cbb308bf837c2f5f20283b97d1fc69.nq.gz
│   ├── fe3518b0772aaeea4b156d5d8453f58c15b3ab96.nq.gz
│   └── fe6468e8d0a1957aba024423c38b9eac57f996f6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7fedfcfbf13c06316fac8a6e0016c2d2f10bc9fd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 103 files
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

[canonical/tmate-ssh-server-operator](https://github.com/canonical/tmate-ssh-server-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
