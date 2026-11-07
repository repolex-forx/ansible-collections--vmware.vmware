# Repolex Knowledge Graph of ansible-collections/vmware.vmware

RDF knowledge graph data for [ansible-collections/vmware.vmware](https://github.com/ansible-collections/vmware.vmware), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/vmware.vmware
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96594d9e364cd177781cc3cff0d0a135ccd437bc
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 96594d9e364cd177781cc3cff0d0a135ccd437bc
│           └── chunk-001.nq.gz
└── blob
    ├── 00e3d5718e424197d9f403a4214a7c0bc4f73881.nq.gz
    ├── 013a3f49050fa7a45bbd10e966d4b4ad23d46d0f.nq.gz
    ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
    ├── 01c5fcb658b3752efd3d40c57d1d5bb1b69684db.nq.gz
    ├── 04014ca8a48c573b905914c38f2498a0279579b4.nq.gz
    ├── 04a86191dbd6381c57f96c686ed3994f6c604eb6.nq.gz
    ├── 05012468b5930a91b1e3f7de4d1d8176ed9d4157.nq.gz
    ├── 0520a2fa08a5267679ddaf39b45fbbd9873ca02a.nq.gz
    ├── 06c93122487bcad4f33212aa39228ed46e4a1006.nq.gz
    ├── 08513ba6bcd2d4753488b09c9bcf08b0c63b2a8a.nq.gz
    ├── 085ac46b4e4df5afbdf8fa4eb01e00f2eefc03f2.nq.gz
    ├── 0a20ac76c8e9386cc8dbe5a841ec550b2c97820a.nq.gz
    ├── 0aec8625e832a761403f81dd6cae45f6b5617aca.nq.gz
    ├── 0b53fd22f87bbce45edff77849c56461d2624ebb.nq.gz
    ├── 0bddc03989ee09f31876f3314b4694aacb24d530.nq.gz
    ├── 0bf11d05422358d2b07bded1ada5cba7aeb7a80c.nq.gz
    ├── 0cfbbfc244da6f4749782cd00753778da21d5794.nq.gz
    ├── 0d8af73364a7f9f577a9e52640d42246dda45db2.nq.gz
    ├── 0e0464b5ed3169b8269a8fd3b327373edee74201.nq.gz
    ├── 11973e8d997dc88cc0a96c839e8d4158986ac687.nq.gz
    ├── 140877db1b86e54b461c8955cb7435d6d9a6241c.nq.gz
    ├── 147b9be5ad668b9daf919f13b6564941e80c32aa.nq.gz
    ├── 151c619e95d9aec6456cccd5add0ae45eb0534f4.nq.gz
    ├── 15ff3eb21f407ce6a4abf0ef1dfeb94c90e797ba.nq.gz
    ├── 180957ec9141ea5f4683b9be4da3998ada95b3ed.nq.gz
    ├── 187cd87ce5825fe64ff909a5db274fdfb233b33e.nq.gz
    ├── 18d0b8a4efeb5c1daf4334a01fd0549faaab8073.nq.gz
    ├── 18d514eb9b9d3af3030f8a2b83e25bdb3d7e855d.nq.gz
    ├── 1931401db0a22a28e60208890824f45f8856350e.nq.gz
    ├── 19758d619b874401d06651c290043adef74581c5.nq.gz
    ├── 19d859b50dcc3927e36aa921f6d3e86cf6641a73.nq.gz
    ├── 1a31d669b311cd9717a5376426ecc9efc4d06b0a.nq.gz
    ├── 1bd41392790a8cca9c3e77e5f78a085416c2dce5.nq.gz
    ├── 1d4ad12e0289cd0ef669981c640fe6c14bff1be2.nq.gz
    ├── 1d5aa24112cefadfebd91f52871bb282e9461098.nq.gz
    ├── 1dac83e755916803dfe5330c1cd90797157bbb34.nq.gz
    ├── 1dd8e8c3914287f0d9fe578f7bdc276eeab7aaa2.nq.gz
    ├── 1e56c8d84872a6d11d5f87b89a978461ea429cc8.nq.gz
    ├── 1e793d9e12423cf8242ed8e1ecd71142b47faa05.nq.gz
    ├── 1ead10507b098df4a3061088a4766bf3c92670c6.nq.gz
    ├── 1ecfb94bfa828d10ef9a10599aca58e5e9054b39.nq.gz
    ├── 1f1817c0382917fbfb72c459542a31599e6a6ba2.nq.gz
    ├── 1f2ca00d6cf40cde824a30730b235e4e281a8e17.nq.gz
    ├── 1f6837d3e54c955ca6777953deaaa5cbabfd3f24.nq.gz
    ├── 2012a7ce83c195e052c420f3934dd3d0ea659910.nq.gz
    ├── 201836a005a833ff8faf31886d9029be0b130aed.nq.gz
    ├── 20472d8bf2a3e7abe0583b3dba0dc5d6c8215a95.nq.gz
    ├── 205071f5a88f56cbcb8c3d882bb0eb21924be719.nq.gz
    ├── 209d35e51c997454d114ac6a89a1f231ee3a0494.nq.gz
    ├── 20ddbdeb86db255c563f7bb4bac11f6681a8f75c.nq.gz
    ├── 211b425322e8f9c5484354e860dda2388bd290ec.nq.gz
    ├── 21409e06c05800b508cacb8109382beafe404b46.nq.gz
    ├── 214d390518f2ba4820e18239279dd4fe4ccbf91e.nq.gz
    ├── 219154c3d12a530487f8f0e880a70bdea3db7684.nq.gz
    ├── 226d6d264fe7e39eb0c9d074531132aa2b2b624e.nq.gz
    ├── 250e47e3c9d0cca9c596df0dc96d8ff9c9aee672.nq.gz
    ├── 25a7379fcdf551e9d1333dd6e405f96a86b84d6c.nq.gz
    ├── 263fb011c9232c2af37d3188d25a66f74a0706d2.nq.gz
    ├── 27e2eb87e9404f1adf8cefe11c6704a259da4523.nq.gz
    ├── 2830b711c80ddff1554b0079fb0d8ad033669e02.nq.gz
    ├── 28e3687649499708faabfa5174215ed9522329c7.nq.gz
    ├── 2916733d415b72ae69da7507c2e6ca803cc0089d.nq.gz
    ├── 2985dfdc7a13381f97f98bceebe0ebbbf18ab623.nq.gz
    ├── 2a2075addb61d0766221d96d5c17971abb5c9d71.nq.gz
    ├── 2adc8b5b268bbf021afef9883bcc8ff58037a686.nq.gz
    ├── 2ae29fc06addea9b6f274677227d7b5b52339f12.nq.gz
    ├── 2c6aadc80e1b7b5cafd28d724e996705a5ad54d0.nq.gz
    ├── 2c97536d4d4a9c700a1301cb3795e912576748cc.nq.gz
    ├── 2e1ee6089765e19c97e30420d1a523dd8a4a03d1.nq.gz
    ├── 2f26f2c662917953480ad336028e7910dad880a7.nq.gz
    ├── 301410f02ed4e2119fbc2a6b38b098dc0909f43c.nq.gz
    ├── 301b7774b757a142371b119964971d01ea9dae62.nq.gz
    ├── 3036676eb4d875919b809f3aada608861788a1f5.nq.gz
    ├── 3053a52f0a25401236ddcea9f4e3c0f4ca2af7e5.nq.gz
    ├── 30614e39bf590b18775c849055cbc80a88125426.nq.gz
    ├── 30b9037437e9cc14e54f54e155fdbcabaa8df375.nq.gz
    ├── 319718ddc51b4d780df8cdd3bbee62805217aeeb.nq.gz
    ├── 32ac7c162650d9bba9cdbf6ff0e55a23df084bad.nq.gz
    ├── 345e20a1272a0e04bf201b3aec0f0a648cdcf6e5.nq.gz
    ├── 34e9acdd71196f853cecf5aec55e7b975bce60ef.nq.gz
    ├── 3768de3eb6617409042690cfcf9896eae0e16b3a.nq.gz
    ├── 37c13800cf0581f8b3ae5e7e8acaf8a35ac194dd.nq.gz
    ├── 37fb3081048f18d68a7f69cc8a9be2d2d41aa4ad.nq.gz
    ├── 389c3884ee5fe1689c578c118faf75c03b1f3269.nq.gz
    ├── 39eb1da0a47e4f529e0ebfb77f1577656b5f1edc.nq.gz
    ├── 3ac9a6e9cf1a8b85d2420e28d4f5c89514a9096f.nq.gz
    ├── 3acba864b18b2310dbc3ffdcb8694cb07ec9dc63.nq.gz
    ├── 3b4ce3f144d6fa11d1524ba86d084245a83a99f3.nq.gz
    ├── 3d9399332835d95556a70922cef8ce8303203346.nq.gz
    ├── 3eb819ff359f7e82a0d5e6897b64207d9aa6e3e4.nq.gz
    ├── 3f4b17ccd25d95c301983fd6ffd284cac7dd9514.nq.gz
    ├── 3fa098006ca06592ae9bee37fbd4173f09a2940e.nq.gz
    ├── 40e186e502de65f09032996580ed512ec78b96b2.nq.gz
    ├── 4228afdfdbde066ed467c1d63fd054c0207524a4.nq.gz
    ├── 425a5164cd3f80cdef1a128fe860e287fcd7571e.nq.gz
    ├── 443847706279665691fdb07773d9e45dda3b7393.nq.gz
    ├── 44d1f25bb01fcd127bb7657f18db9ed4316cb80b.nq.gz
    ├── 45c2b5c103aa19e9f9cf264f9b71b5ccc3eb4df9.nq.gz
    ├── 4614cc9906e38c1236baf25ff30cbb57e9ad112e.nq.gz
    ├── 463765421132676e2110dcb416cf934a97276c2a.nq.gz
    ├── 464007f82e80b6c61bf5f9daacb78facad9d7f7a.nq.gz
    ├── 475cfb46418efbfe9402400e207c7109685a3a69.nq.gz
    ├── 4849bfbb98cebb3fde4c5c4adeed9e6c454be057.nq.gz
    ├── 484ffea933fde9e5ce0dc80fbd553587ee0cd047.nq.gz
    ├── 490cb77e5994ea5a2ae4b3552a4642afbeb36d09.nq.gz
    ├── 490fc0e56ce461e27248b99a5dad25dc069bf95f.nq.gz
    ├── 4969a52717e9e109150c19e7e6012a4e83367eb6.nq.gz
    ├── 49d2b35b0a8b2cbcfc7d5047a7792d79afd4c730.nq.gz
    ├── 4a24e5ac41c7446355b1c834a90aef368e32b042.nq.gz
    ├── 4a85aa567cc34ba874e32496fc7b68795ace50ee.nq.gz
    ├── 4abfa75a2d110e648c3567b7afe9f7d1f6d961a2.nq.gz
    ├── 4c0052e3e169097533703bdddda73d657ad1cdfd.nq.gz
    ├── 4c1fbfa0846d7a62595a4dbced3301301a638c89.nq.gz
    ├── 4c345d7308c4c9ae4535425ee7c6cf92a34e8f82.nq.gz
    ├── 4c50ab7ce0bb42f6b1abc6aa5777f62c8a097eeb.nq.gz
    ├── 4d8c1d5aa100afea204e7c588da401e02f460ad3.nq.gz
    ├── 4e29ce3fac2456ebd08689018325fe5f224466cd.nq.gz
    ├── 4f4bce02cfd50004563a57caca0ef42c01ba8093.nq.gz
    ├── 4f6584aa656b289ce51ebfb272564f83ea51e7f5.nq.gz
    ├── 502f32cf390e4e06bb6baa368bd7f428f94aef88.nq.gz
    ├── 505a9d2e41714759a0ca9ec3089fbe5c780a3ad3.nq.gz
    ├── 51ce85af9e789584b5493d6c833d46fc9b67c71c.nq.gz
    ├── 544de1638d1df21eb86f37f44579a5ff726894fe.nq.gz
    ├── 545064784dc159aed77d5fde0993fee645747648.nq.gz
    ├── 54adeb65c8276870795b1dd22f6cbb94ed13485d.nq.gz
    ├── 55ba80e8cc5ff28f1d32a797cb92a0a59a3a9568.nq.gz
    ├── 55dc17183de586abeeac3a42dd28847d4a15327f.nq.gz
    ├── 56f9ef4fd3ed6572faa9e8694dbb9d956c6f5270.nq.gz
    ├── 57c4bef46a948ab1d3aa397932a5c57961390fc6.nq.gz
    ├── 580dc17b11a2c297afaa2db7d6da4129f41a5b26.nq.gz
    ├── 588c17e34490a3dace2ea13162c35c49ee899549.nq.gz
    ├── 5941485748c717422bde6cfadb2ccd19a6266647.nq.gz
    ├── 59ad7dc207366760a5d79a1d1fe0cbb5d75715e6.nq.gz
    ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
    ├── 5c9a61a72880f3eade962cad2aa84d551ebc2eb0.nq.gz
    ├── 5ccfc3c56c0b65c3c1d32a045eda13c61a3a9426.nq.gz
    ├── 5da4b7c6b945dab15a8cab39d4549763d0d6ac63.nq.gz
    ├── 5e4c4e39616522f6281f960e866aec0199ff9856.nq.gz
    ├── 5ee02cb934386ca8409fc6ef7599283c23376a2c.nq.gz
    ├── 5fbb9affdb028b819ff167956bcf060f18b6e3d3.nq.gz
    ├── 60f26e7ce402ea3b56fc73febecea6cd9d8046e3.nq.gz
    ├── 61fd3d0671afecf521d743dd9a2e76b0eeb7233c.nq.gz
    ├── 62f8019c3d4d0dfaf21dd5d706cddca3692f7eed.nq.gz
    ├── 64c39a593388f50985c712c74df88006da373128.nq.gz
    ├── 64d3efcd5146990ea6ea5d0b14f4a143187e1177.nq.gz
    ├── 64f4630cf045423c63f2457657b43fa7f46ed85e.nq.gz
    ├── 654cd5f597ecbdbc12e98929dfb84b4030357633.nq.gz
    ├── 65b3c3a22f207ebfa22d7ae3d0dec0a0cc2774d8.nq.gz
    ├── 65b4e1491a0595d576caab11d0399e8fb5da16e2.nq.gz
    ├── 660a1c1dfac19637dc257fc9d23a9e8512e5a161.nq.gz
    ├── 6685c21921af2030919c3cae5c1d94871ffc13b8.nq.gz
    ├── 6692aff19dfdbdfe80cdc02f2eb8a5e318761297.nq.gz
    ├── 67a66d4cd7a8747869c3e4fd5157240a97413542.nq.gz
    ├── 6a31cf3f3440d6ddd30f95aaa45afbdff226eec2.nq.gz
    ├── 6b56f7f4452ff8d0f9b918932bac72a4fbb3699e.nq.gz
    ├── 6bb1a999e1bcde8f568a2672b9f2410759e7a135.nq.gz
    ├── 6c1c36346ee77f8b088425842378457ed98dbdb6.nq.gz
    ├── 6dd128e06ebfff3382f6064451f0fc3254038fc3.nq.gz
    ├── 6e272bf64765be1a7b62d4b94c37cd6a9f1f0d51.nq.gz
    ├── 6e5abd87db8fb9973801b2135568f41082788895.nq.gz
    ├── 6f111193e4948bbe3e85c4c9f5045592dda45159.nq.gz
    ├── 6fe2c30a38c565e2aa4511a6cdb32d76589de070.nq.gz
    ├── 6ff94636a398f53a01ee49ea1859a9f38d7fa5d0.nq.gz
    ├── 70ce24b65b5c32786eb8d014100ae08d86d54486.nq.gz
    ├── 70eb090d1801ea7af88e393c53187c5a12964195.nq.gz
    ├── 7105006dcf796c56e41a4568f179711ac636c6cf.nq.gz
    ├── 715fef76351dbd00140401dbc01157f7bbdf20e1.nq.gz
    ├── 720bf6f98474139943b07d79cf33e089069de2c7.nq.gz
    ├── 728b35a520849e1d839a75eecb639de15bd56c28.nq.gz
    ├── 7326055248d19bd4b833dbdf75397637c5ac08e5.nq.gz
    ├── 734538b9d06770df0d7229eb8737170374b28ae1.nq.gz
    ├── 7379d264b2dedb9c58b37a153f5ffc23b9b1697b.nq.gz
    ├── 73f43ebfb6bcca7d5bb6fc76e07ad97717540dd1.nq.gz
    ├── 7421ddc5720346c3ba3ce7bb6bbca1265eb9f70b.nq.gz
    ├── 744c4ebade194742fd25c30d28099aad7080d447.nq.gz
    ├── 7474372b482f73c5270f442f2e89093ae81c7f08.nq.gz
    ├── 7548e9def859eb2437727c53284bcdc830f9e8f2.nq.gz
    ├── 7612a85a4ef2d459df15e003f42921cb38e7309b.nq.gz
    ├── 76aa8d901ff0d862b01e36875ff17de158ed7104.nq.gz
    ├── 786cebdb3e69d2840bd7041816ec0983b60f1fe5.nq.gz
    ├── 78f0e6530c39301e25b1116eece59864c4a17ecc.nq.gz
    ├── 78fcb8aad0f28adf0e928aa8012bbc561c37150b.nq.gz
    ├── 79950d7ec523600d64cef0e4e6d7d93e214b502c.nq.gz
    ├── 79b9780347bd10430eb84757bdbaed7ce6e33e09.nq.gz
    ├── 7a68b11da8b136187d66cb2bed84c89208189324.nq.gz
    ├── 7acfea6cab6b10577ce2184fb73b2f96dbd5fd57.nq.gz
    ├── 7af67891361a622d742541196bda5146202e8f1b.nq.gz
    ├── 7b0496f4c2d8e734c8df9d20a8b06c8c93e6645c.nq.gz
    ├── 7b563601d41e94e23bebd9c18cca98cc00fd9378.nq.gz
    ├── 7c39b8118c7f1a8896443aea6a9ba4f826e781c4.nq.gz
    ├── 7c5ba97f9a31f8d8db8200df579d360230dee5ec.nq.gz
    ├── 7e152bb666251908fe8e922fc71fc2f436f16662.nq.gz
    ├── 7e28f67f156082f7d6037ae94e4f6a0cd1f394c8.nq.gz
    ├── 7e610aa1695d196ba41b524ca3c549db5cb08ad1.nq.gz
    ├── 7f9a17c3316d3bed49fb65e68ddd57e11e5a2e3b.nq.gz
    ├── 7fda627936ecd08f88ca068c87f87d92b4a0ec66.nq.gz
    ├── 801c4a42084a82e4d527746959ceab15ad1628a1.nq.gz
    └── 807ab0c56603bcdd418acebd5e6120df2de30946.nq.gz

7 directories, 200 files
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

[ansible-collections/vmware.vmware](https://github.com/ansible-collections/vmware.vmware)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
