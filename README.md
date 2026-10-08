# Repolex Knowledge Graph of modelcontextprotocol/conformance

RDF knowledge graph data for [modelcontextprotocol/conformance](https://github.com/modelcontextprotocol/conformance), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/conformance
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c37eec888e1c6ff140af79987a40008548b7cc5f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c37eec888e1c6ff140af79987a40008548b7cc5f.nq.gz
│   └── repolex
│       └── c37eec888e1c6ff140af79987a40008548b7cc5f
│           └── chunk-001.nq.gz
└── blob
    ├── 00bf4ab2bcad8106ebc6238fdc3be4dd410b6053.nq.gz
    ├── 0128203b3abe611fc734c25f591d25e887930e60.nq.gz
    ├── 0227d3f84cecdc8ed089d5c5fba1db7739444470.nq.gz
    ├── 022fa4ddd2c0be4219cd946dbd23730a53063f56.nq.gz
    ├── 055076da993584a70d6e3cdc3d825aa3f506a166.nq.gz
    ├── 056d3b388d84449870191d5390764668f5c07756.nq.gz
    ├── 057355d88318c59d14a744eef8367584f4d66b14.nq.gz
    ├── 062efd729d3c2426d314e006c24c1af6dd33f384.nq.gz
    ├── 06fc311cfb9fc331862b8be1ef42060c53cd49f5.nq.gz
    ├── 077917b23fdf7225535d2ce3d4ea90420f749929.nq.gz
    ├── 08aaa8279e4a5ab516e6d506433aec75a41a0840.nq.gz
    ├── 09f8b5bafef9bc4d746ab33f5ecb0b57d3426419.nq.gz
    ├── 0a1cab8a7b707edd042f4c93c40222c76e053d69.nq.gz
    ├── 0a80b7f727db35375c7e1cd29897d8f1bbeaf7b5.nq.gz
    ├── 0c395c4fd8f200f0bc336751277619a1648c87d3.nq.gz
    ├── 0d7575db1cfad0f12f0f336aa0839dd37b553a7f.nq.gz
    ├── 0df081ee2979a1f09a9cf6f44dae5c3a0252fecc.nq.gz
    ├── 0e6559ca9cd248420ef83b9500ac0e96629a9bf7.nq.gz
    ├── 0f372f494dac14bfb72a170f5274b749b0e25d4f.nq.gz
    ├── 110485f68da17d54cb4b9119add86ca958af3a94.nq.gz
    ├── 11b8f0538c5a194d270537b70c19b6db52260bf6.nq.gz
    ├── 13f3ba04fe981f150668e145a013e43eb33b1466.nq.gz
    ├── 143a7ed1932e0dfd63204b6310f140180e55f34d.nq.gz
    ├── 14e94328500c51d4eeee9de8d2073a3b221d3bd3.nq.gz
    ├── 1518595885c0e4ca32ed2f4ccea5e362a50ccffb.nq.gz
    ├── 15d0ad5833a63a5ce7796c06f6c9fb16d17aff0b.nq.gz
    ├── 162f93aae4000fc0c4f91c85f26a7612a5f1de6a.nq.gz
    ├── 191cf221f3c3931706c0e9742af3f4f61b5e692a.nq.gz
    ├── 1cdbed0996010d0fcb205a844516546baeab36ec.nq.gz
    ├── 1da07c8f04ebace7e846dc572a7c38f3bd30f1e0.nq.gz
    ├── 1e0fc3c6ac6835cbc09606da082833084910364d.nq.gz
    ├── 1e307b8deda83f91823cf146c4796418b2f327c3.nq.gz
    ├── 1e4b37c52d242fd1c42c4773c2cf57494d87601f.nq.gz
    ├── 1fd768de9db46f64b81f422310fef4cec87259a1.nq.gz
    ├── 20ad4373d1210f0054b8047eff7e5fd81b8358e4.nq.gz
    ├── 20ed8ee9937bd7ae19f6aa1a4595754ea22877ea.nq.gz
    ├── 21e80ec408d0514dc96d1f116d42f688d12a048f.nq.gz
    ├── 21ed5ae12bbee7f85f109f46d3a1d12dd7f94f93.nq.gz
    ├── 2214ff16be5a2d0b9858895f3604e0de8e195e53.nq.gz
    ├── 227546b295fc76dd30071ae3572ae7c114fe9dcd.nq.gz
    ├── 227c6c45752be1480278c4b0b00e8e227c50e1eb.nq.gz
    ├── 232367f2e28d8628834c438b5b66e1522e395cf6.nq.gz
    ├── 23daebeb8a8397aac86fe9637fe9efcdf4dc0478.nq.gz
    ├── 2416d1babb4f9313146078fa9d0d7f851bd8d0ca.nq.gz
    ├── 25fad1536d6626316e706288d7610e06b99506e3.nq.gz
    ├── 26101cec3720074717f67091174dfed03dd347c2.nq.gz
    ├── 280fe791535f5355821956c50b4db6de4eae2fac.nq.gz
    ├── 283419180c7c5365396f93dc61a0ff50d4517733.nq.gz
    ├── 2a0bcda064a69860b5fb67eac518be75679c505b.nq.gz
    ├── 2a836f1c032be5a427880964d5141cb0d3e63acf.nq.gz
    ├── 2b6bcd5ba24043acf270dacc0a3bf20dab87ad5f.nq.gz
    ├── 2bd5692eaf0b526e5a2d0a69af452c8fac3144f3.nq.gz
    ├── 2de317b06810fe84909940b8401c61da1f832cf1.nq.gz
    ├── 2f6ac6458301c54b09ad804042f35911cacc8f5a.nq.gz
    ├── 2f90da3431109a01142c04a8e5088a356a8a46ba.nq.gz
    ├── 308351dba4a19ce65c1a3f75979259febc0ac85e.nq.gz
    ├── 30da62415bdbc767b63ac830ab1263d6c5d49d01.nq.gz
    ├── 319510578ab224a3b840bb5cb05bb29f76588cfd.nq.gz
    ├── 327cb4cd6029b310881d61e60d1b61a3ead0e63a.nq.gz
    ├── 3361f28348f4883698c960eb9b01349b58668ec6.nq.gz
    ├── 33f44be46a0a13fd00c12b2e8ca0f0917d10f874.nq.gz
    ├── 3401c11a8794aeefba1ecb954b74a23b26d2b3f2.nq.gz
    ├── 35f1991d9d56892be9f05b5843ae9f7de2af4af8.nq.gz
    ├── 3728bd8976aef8e05aac7ae2f51ff81e39e0d001.nq.gz
    ├── 382b0db837b3395ce67a0ba07013f7797ce300f9.nq.gz
    ├── 38890ac891286acefd48db6d226fe49a61df6a57.nq.gz
    ├── 38a1beec312e090b7631320629102db15ca48692.nq.gz
    ├── 3b1ff5c3953b763cc3fb2e10982810e288305448.nq.gz
    ├── 3cee1e12c13c61f5f4849205a439eb158a592df8.nq.gz
    ├── 3d06c86a521c570847d7486e5ea6213c40599384.nq.gz
    ├── 3efe71ed2004bf2b9b5796eb7b07a41e78b02ac4.nq.gz
    ├── 416265ee236dfb9089ec7f86adab42615c1da23c.nq.gz
    ├── 41c84ae80bf8402cb2c40c5f03fc4e86b2ac6df8.nq.gz
    ├── 430406d13bef46a83c6f020c2f19afb9b7811a9a.nq.gz
    ├── 4356d425a29e7392ad665127cd18ded78acba14e.nq.gz
    ├── 43ecca64e5a503a0ac3f5f307c7633f43777dd8c.nq.gz
    ├── 45cbc0975397429861cb44c888068b5b2de4465f.nq.gz
    ├── 46268aa224361e7a481928e980367dd13a40f013.nq.gz
    ├── 46271843bf5bdb890e96bbac3c590c98b2bd949d.nq.gz
    ├── 46679005e8d733911b7811b9fc96185ce602364e.nq.gz
    ├── 476a448eead87910aa79e4a96e3c140659619853.nq.gz
    ├── 47952c644f63d4818d3f035e26fee3d648e73ab2.nq.gz
    ├── 48f9170aaa72102952dfd1ba341bf5b74f5704f4.nq.gz
    ├── 4a5c1a508ffaf114c06a2cba6c6ca27fff932669.nq.gz
    ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
    ├── 4ad06b8f800492be2ea5450d3adc4d793bbb3f5e.nq.gz
    ├── 4ba6ca3e564c4d8953eeb657d3152773861530b6.nq.gz
    ├── 4db0bd9c07612de7fc53f0d55af609962373d036.nq.gz
    ├── 4f65f323a999ef8654f6d6734524cb4357ade406.nq.gz
    ├── 5016a2667aab522f00f1d68e452a8c956ab4e110.nq.gz
    ├── 509df1d84e6ce440e213b630e00216d31a0e9876.nq.gz
    ├── 50b7efcf931b43803c6282683abc7132913a973b.nq.gz
    ├── 523f4ec0e71c4ecc74b72fb5d34a07909570f1c1.nq.gz
    ├── 53c28fdcc673d5ee1b78052e90db94945ceb8639.nq.gz
    ├── 54673b00a566417fd603a06e14d87bf71a7a0cd6.nq.gz
    ├── 57cf7c4d7dd6ae52fed0ec4e0a6845fda24dbe43.nq.gz
    ├── 5adaf8e05bdde4e3b2e29c730372d32f60552540.nq.gz
    ├── 5b9d96682e802d0edfa05e21cf23a6df1682dd6b.nq.gz
    ├── 5dffd3d722f0de629b32fed36e517bdeb04b03fa.nq.gz
    ├── 5e72f51c6bfb8108ec250a5f83765ec3b72ddf3e.nq.gz
    ├── 5ebc8687198c12d277921304f159192574298bce.nq.gz
    ├── 5ebd8220e52a3999fca13542e66ead28d6dc7337.nq.gz
    ├── 5f0251106255378efeded4ddfd54b587166ed385.nq.gz
    ├── 5f3ebfb14661d4869f8b7cf9015259b56c90dab8.nq.gz
    ├── 6022a704393a6a882deae07f476c8e98cdab93a2.nq.gz
    ├── 618dc0c5f2d88e168741468b8c1b5c7fcfd1aba6.nq.gz
    ├── 638171ab218729de04fba4b3f95de77bd742c93e.nq.gz
    ├── 64ad4ba9e5f054259095ba38860164926296a930.nq.gz
    ├── 65382fab2260fabf27d750ec29b7d8ff7995fab8.nq.gz
    ├── 654ea292fdd1819d7e1d559cda44be3e6982e700.nq.gz
    ├── 6612196e9b123c5128944fb9406ddc7ec359c4ac.nq.gz
    ├── 674f2e9ca9bc8f99c05948e4adc6aa8ae7fc5499.nq.gz
    ├── 6751dedd49df54861b6ec8ab48e1e2536210aaf5.nq.gz
    ├── 68b3eebc48bd706495f686d5d935d0969411ef29.nq.gz
    ├── 6a3dc81fd3c52cd916aa22c396a5e2fc0312d8f7.nq.gz
    ├── 6ba2091e400c3493e210dc6463f93f3eb9f76bb3.nq.gz
    ├── 6c7c989e6994ce30e2eed0bbebe7f774926bbc9d.nq.gz
    ├── 6ccd0bff0b11e3b1250959713238a2ec35846813.nq.gz
    ├── 6d308d64a4a0b974fa52dbd1245f4cfe734201fc.nq.gz
    ├── 6da0f596f66b5ce6391ccb9450646f4cf084e61d.nq.gz
    ├── 6ddd4ea8244cc22bd44571262d368729f7a56d89.nq.gz
    ├── 6fc77936788869c73e551641ed41bdebb0e16393.nq.gz
    ├── 721365e691766ecaa4fb7ccf9b4ed7a95b3de572.nq.gz
    ├── 72cf602137a451e766dd643f07d2a6096395ae1c.nq.gz
    ├── 73684a19c7d0004fc13445c0f3e59df159eb5b94.nq.gz
    ├── 746cf9ce1b6db523cc6aea55552e26b30b36f098.nq.gz
    ├── 74e9be3fb9dbbac2a99f2895ea11991670bcd8ad.nq.gz
    ├── 76fd7e514794aa95d59c35b60edcf0c971bbcad8.nq.gz
    ├── 7758c469fa00b83a51e0f48d2f0cbd30f39bcbf9.nq.gz
    ├── 775dc991791e6008f662544e70f76f9d47be32ac.nq.gz
    ├── 77eccca5b21427ff7a2d51a53dd79ea42aea3fd2.nq.gz
    ├── 78a2c7baafd5b4e79b51266639e54ff4990a7a3b.nq.gz
    ├── 78bb55b8c229e2ed4d959ce0a31a683d1619b959.nq.gz
    ├── 794369676d8589bb6529ec183fb83fa2ccb8193d.nq.gz
    ├── 7a197c64a8722455423c70dc80d21bc7369c9b89.nq.gz
    ├── 7a6e8bf6d0cbc0adada7dfceb86e2c6a21e11c71.nq.gz
    ├── 7bbfa3c4cbc9ae83ba3ea54b14ae20ec32f754e6.nq.gz
    ├── 7c8470e605f92e66bf32a9cc7938011cbde00721.nq.gz
    ├── 7daec39bf3b41ee0d7fe2fed0003715ca0fc773e.nq.gz
    ├── 7e4ff545dd7829a06db072c9e3c27afa0a4430bc.nq.gz
    ├── 7e5f45177a7294a37f4e4a839f53791cd865961f.nq.gz
    ├── 7f69283012f407c005548ea4d4dcc100fac67a48.nq.gz
    ├── 7fb3886258fd937ce1e99236f4ff6bf0a9609844.nq.gz
    ├── 7fce40a958d3573e826922e0fb37f2ddaf2059df.nq.gz
    ├── 818351679dd6b5a84ed51de5108a3d3063990b45.nq.gz
    ├── 82a28b5eed373780507f8810db11a61ae8938bcc.nq.gz
    ├── 83c11ce9ce9b81011d96d672fbac9388b2971e84.nq.gz
    ├── 842950e325fad5585d65684aae08a0d08b675a2e.nq.gz
    ├── 843590d0b66bb3d8bcb98ded7cf04250b22aea88.nq.gz
    ├── 8445f1b4a44b4711c64fb6405e5baceb339d9fe3.nq.gz
    ├── 85101b226e0d337d1cc4bf8c905eb518392056aa.nq.gz
    ├── 85773e23d748d1eca07bc3e95917d1ece6d4b164.nq.gz
    ├── 86bbcc5293d11d8f797d1ede24d41c6bb9f23390.nq.gz
    ├── 871ad73b6416fa6464d2a948efeef66dbed1853e.nq.gz
    ├── 8926538bb2eb4ba31beee2402a511e3b30845fe3.nq.gz
    ├── 89b110685f8673325ad8492355dd32da9a27d180.nq.gz
    ├── 8b16ba5aae8bbec07123b69697e09750e9ff5876.nq.gz
    ├── 8c16ca29c191e994b548318d52986e28228d59bd.nq.gz
    ├── 8ce464ac18b32b20c62038fc57517f5a880cb7c3.nq.gz
    ├── 8d20cf7a4de3fefa2e7279270ab3103499c2ba33.nq.gz
    ├── 8d98c92d314dcec18bb5617e12ef3465dc09f489.nq.gz
    ├── 8edc0221724cefe55656282428db349354149902.nq.gz
    ├── 90e20bfbf00e0675e7f3b8ee748e2d58e4f412b9.nq.gz
    ├── 91bd24ca909806a1ee7d091d5d0ae97a64447be6.nq.gz
    ├── 91dae452e24075a51a9f03ab2da523bc3167e62c.nq.gz
    ├── 920b1750c256574e6f90d8ae213a50c8a23059d5.nq.gz
    ├── 92295519f12becc830b17a5e207392bee9ab77a1.nq.gz
    ├── 92767e90e03c919b81a5fff2dca448db3dc6ace0.nq.gz
    ├── 92fe4124b765c0bf0f4f982b5d8aba1d0b280df6.nq.gz
    ├── 946044fa65277e1a4f8e285a83169434ea174393.nq.gz
    ├── 9467456234d9b19b7b65138f3e9d0c9942399711.nq.gz
    ├── 95686c28a4aff85b0bbb2d56477b144fe94c57ed.nq.gz
    ├── 967f5d8a5357949acd9630dd9a364fb3be9e06cc.nq.gz
    ├── 969f4a444b15ccc8dd6a972c5ff2b0524e8ad419.nq.gz
    ├── 97439df3983a0bb7ad21f878fb51d043cab68dc4.nq.gz
    ├── 980c0305f80f512477e6bfd2d72943d3e39f1c23.nq.gz
    ├── 990662207ebd75fefdbcfaa2693dc2aadf9e45cc.nq.gz
    ├── 9a197e14ed041f2c4bd7b37dd58e4f30e1dde632.nq.gz
    ├── 9bfd0b536695e049f954647184b724eef914a79a.nq.gz
    ├── 9cc8d5b5a71280f7e3695af3767a9c3709d91966.nq.gz
    ├── 9d2e662a2676124cfafcf893af4f263f0041554f.nq.gz
    ├── 9fbe9db3134c114e75dada4fbbf9267e537c5f42.nq.gz
    ├── a0921150362622b1562400300397042924df2529.nq.gz
    ├── a1e3f26799d06421eea7e2334e6d279233c6d090.nq.gz
    ├── a2b37b7a0b9d82a905f6ddac484ccc0be087888f.nq.gz
    ├── a354d8386713eede7f946efe023e50bc522c71df.nq.gz
    ├── a39a86ca7ce63649c302320221fa6b029df345e9.nq.gz
    ├── a4891c9d74e46fcca07f7422567324a382ed08b4.nq.gz
    ├── a511114df96891e17e74e4b589b42a9b876140f3.nq.gz
    ├── a5cc157ae64d564ddcb317ad88e56439043095c8.nq.gz
    ├── a5d41a0b8b74aef5b6790551adc433133b53cba3.nq.gz
    ├── a71925d9b53e23b8fb11ff6bf05e6b2bd432193a.nq.gz
    ├── a799ad05399696f224fe8c33dc256a7ec67b01f4.nq.gz
    ├── a7a10894910c72a0d1bf336ee621b1a049a7dabd.nq.gz
    ├── a7fa1b9080a07fdca6c2d6bfecc5ea0f007eef0a.nq.gz
    ├── a845a8f4ad8a27b183c039c0e06e0a968cfdc918.nq.gz
    └── aa50a3a6962945b07d764d3557acd6036fda4339.nq.gz

8 directories, 200 files
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

[modelcontextprotocol/conformance](https://github.com/modelcontextprotocol/conformance)

---
*Parsed on 2026-10-08 by [repolex](https://repolex.ai)*
