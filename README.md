# Repolex Knowledge Graph of explosion/curated-transformers

RDF knowledge graph data for [explosion/curated-transformers](https://github.com/explosion/curated-transformers), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/curated-transformers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e7e7e9dacf5e9013c9d1ed16e7233232369147b4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e7e7e9dacf5e9013c9d1ed16e7233232369147b4
│           └── chunk-001.nq.gz
└── blob
    ├── 039a50a1708d67f6347bff230d26256387adbe28.nq.gz
    ├── 0624a6d31f17ff738b0ba004fd0eded81e7437bf.nq.gz
    ├── 09010896523748c8e7e3b136e75968dfe65a9c37.nq.gz
    ├── 0ba9d73b2744d4ac99ab53721130980261caf178.nq.gz
    ├── 0e23a0cd02e0f5151c050a381ce7c2d6b5b98966.nq.gz
    ├── 0e6b3cf3627910ca586ea7cf267f0bae338461e5.nq.gz
    ├── 0e6e389805cba22cca61ebbd3a2ef42e8875bc78.nq.gz
    ├── 11b60ffe201d4f15a41107fdd63ed4b9da6d17ba.nq.gz
    ├── 11e943ed98a27037c5b5a3bc880b59ffa0f1710e.nq.gz
    ├── 12702c41ce05d28a32d1b9c04698e8b9ebd9f781.nq.gz
    ├── 1289ac1d35276afd164833194c817c481ee70a6b.nq.gz
    ├── 12f4afd09f4b79badbe20dab41d8ba5cc3adcb33.nq.gz
    ├── 16082891bcaed38772cc3957dbea9c74210040db.nq.gz
    ├── 174c2551d59dbc7d56595ddd34d37232aa8111cc.nq.gz
    ├── 1880074f6ef04594e2262b4c6b15eafdb79b1b7f.nq.gz
    ├── 1a0ef08806a8bd5d1e35662c8e33a9ad3a9b15de.nq.gz
    ├── 1a4e22ff425e6992449b627b7088038b00cc5dfd.nq.gz
    ├── 1bb2cc53876d6b8c31b48f1631b3b5863ca2900a.nq.gz
    ├── 1c5e24e4ba0e7bf729730e20e4fecf6a618e4bc7.nq.gz
    ├── 1dde3e1a4ad3862158d34fc7d5e22ed6c71b527a.nq.gz
    ├── 1e2692425fd5b7519174f3127b041106f0fc70c0.nq.gz
    ├── 1f2fa74ea150632488ba90531236a20a86d5783d.nq.gz
    ├── 1f5a9429655e70cf97608e9f8e80252cf2ae9508.nq.gz
    ├── 2130d4bfbb83f7b90c0f3e52ccf8a9a97ea7ebbd.nq.gz
    ├── 217971286dfd213eb28ee029a7c221446e1d81dc.nq.gz
    ├── 21bfa21cb5382d6379ab04e82a56c5ffaaf062fc.nq.gz
    ├── 2351a14d07d9e0c03c0e283ea8de7ba6e1985517.nq.gz
    ├── 237c1eeb194e7c2ee2b00b9c87a4c6749dc8eb68.nq.gz
    ├── 25335a669096c98d355741413f991199be552f20.nq.gz
    ├── 289782ac93accb4d46c5c05e00918efcb3183d2c.nq.gz
    ├── 28a1021a62feb8f84a36cdd1272bfb8a1fc1ee62.nq.gz
    ├── 29aaf1480af2addf7eb84936e15dc7848efe384d.nq.gz
    ├── 2a0452bdac68e30ec3d2408ff64443fdf67b0f67.nq.gz
    ├── 2a6b7487daa85ae817fbab6bcad6aad0dc527550.nq.gz
    ├── 2b31e83e5a16bfd7b4cf6fc4ba5f5d8b9a1beed0.nq.gz
    ├── 2d1695d3a60264e234835388f0cc178afeabc32b.nq.gz
    ├── 2d4d90033db5535ace67fdde8e18ec3421573cb9.nq.gz
    ├── 2efd7dff6182b90d54c55944ddedc21d92020e66.nq.gz
    ├── 2f35f7af8ddee4ea069914ab1a8bd07c145b8d71.nq.gz
    ├── 30e35c759922896d7c1f199ddf100b38e7229268.nq.gz
    ├── 31415d21b3212fb22b4c5d2984a56e53ac0b0a97.nq.gz
    ├── 3163ea2ea31269bfdf94e0d6d9cbf1329db28835.nq.gz
    ├── 31b305c48426803a989d9a4637d0a5e1198a2ec4.nq.gz
    ├── 32d1010bdd23cf7a9526a43c7a7ae65f17debf95.nq.gz
    ├── 343b5417ecc47d5de2e3905a88765c0e9a0228f8.nq.gz
    ├── 393c4b2f2e28aaa9b369315d2342dfe636133f55.nq.gz
    ├── 3a08f1988503c685c8fd69d3571c3ba63931a92d.nq.gz
    ├── 3be07d3fb67b4c953259f7354e7653807414e9ba.nq.gz
    ├── 3c730278d560389da19363d12c7dca8804cf8f42.nq.gz
    ├── 3fa3545db5d8a1b2798d20ad4649c36eeab62aca.nq.gz
    ├── 409299f92bc385ee6e9cee720484a8a06fda0728.nq.gz
    ├── 40a7cbb533f8858de5bb3ea55c7b6ca8aebbcd70.nq.gz
    ├── 424af81bc4522b145870017fe0595086abfe1f66.nq.gz
    ├── 43b9915325814efa67ee22361f1dfdb3aec3779e.nq.gz
    ├── 445aa7b6b207b800770110c7d8a89f2e867c1deb.nq.gz
    ├── 4612d862e90ced28574e42e02ff1ae6dabc47d9d.nq.gz
    ├── 462f950beb0dcd16c041b86490368ef93e20fcd6.nq.gz
    ├── 46b9ea1a1fdd39731841c5d87122071cb2c2a0ef.nq.gz
    ├── 4867a77eced27b04f3af89ec944cb508d21dc0a7.nq.gz
    ├── 48c56a7ae10be77751f290d14f22aac0ff940ab7.nq.gz
    ├── 494eb0b83ff4cc7f12a258ce70a452488164a2fd.nq.gz
    ├── 4a02e9306f8c97126d5a9e473614366d9ce91b28.nq.gz
    ├── 4a4d727a03138040a739ba459445862cc7fcd836.nq.gz
    ├── 4bece367034204a7037dea9e8836fb8d18f3e701.nq.gz
    ├── 4d4b944a0d00d72a0cdcde076c81e079546a4939.nq.gz
    ├── 4d68e39d12e2d3c103e994de692ae01f4a85f714.nq.gz
    ├── 53409e2fc7e1ba521806b7e771b29dc8cbd0a4c2.nq.gz
    ├── 53493587d61a811f4cf25d17c3516cdbb77c171f.nq.gz
    ├── 53d3ff7626f997d347b7f0c906b6ec4d0a766eb0.nq.gz
    ├── 545dd99cff09a240b02450e180b1d8f81e91bd13.nq.gz
    ├── 5469d2d64a5656b37bd3c494df3773501aeff6a1.nq.gz
    ├── 54d635fa6a103d395fb3d8a6022073e010454618.nq.gz
    ├── 55ca4867b70e530dad1f4a13d8c118fdac89201b.nq.gz
    ├── 5615996df33e5932c65055f681dfa270ceddaf88.nq.gz
    ├── 56aacd38c07780b9eeac3d55cfca266ed1c74a01.nq.gz
    ├── 5884955a979acbdae1e78d4c2936bff32e60191f.nq.gz
    ├── 59206551a6e442d34708934d793cdf3432c212dc.nq.gz
    ├── 5aa2b2866e6899afbe6984c8efacb26830238c67.nq.gz
    ├── 5bb7a1e9ea57517e7e02923f6d4bb8b51ce169b0.nq.gz
    ├── 5ce938ed0352dfc40949868608f64b78fa7e6d57.nq.gz
    ├── 5cf60f067a9f3e1318184a968b1f6c471f62aaae.nq.gz
    ├── 5d9b11a0380091e9cf1eb13b289813d4a93eea9b.nq.gz
    ├── 5f83888ecc757ca6f0885dfb543275c5c7d5c462.nq.gz
    ├── 5fc7345d90a4f6ff829f96e4a8365fb603a3651c.nq.gz
    ├── 61ffe20ba8fc2783fce8851833fd9b3d1952c1bb.nq.gz
    ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
    ├── 6310aba2072442c1e68ff01f131d95ecf2308f26.nq.gz
    ├── 6649ebafcaa3ebea959474af92757ef40e343c2c.nq.gz
    ├── 6653d0d5e8465185000407d8926657c837a74efd.nq.gz
    ├── 68dfee6227e0d33ae51f6d49d89f30122e3b851e.nq.gz
    ├── 697bc1e305f8add4c88849c9cfee8dce3c9332b2.nq.gz
    ├── 6b677152cc154b6102016aef141ede6c3fb016ac.nq.gz
    ├── 6b79991009364cc46b2b41d5d792971f9fad487f.nq.gz
    ├── 6b811c15b166d7ae5966dcb7027e06fd63ee3b8b.nq.gz
    ├── 6bc21f14378728655fbb955db06d19cc746d23ee.nq.gz
    ├── 6c08a23985b79336229c2aa1f008b09d60598c54.nq.gz
    ├── 6d869c47777861016d8d0a6036af625690d88f48.nq.gz
    ├── 711e19a4dbe487700f0d23d464b71d8bebd82438.nq.gz
    ├── 714843de61940f877e3642d7cfcc7427d34ce47c.nq.gz
    ├── 715447e32886f8b6aba52726d2dc9fc54f4458c8.nq.gz
    ├── 7716ef677072347627d0c792c63064c9133751b8.nq.gz
    ├── 78ca008c96f1b320a14a171717836915709a2f95.nq.gz
    ├── 79838376021581756e8c759880ecf1d7309b6b16.nq.gz
    ├── 79c100a11920b5fac6de9b740b0f29f0f305e50a.nq.gz
    ├── 7a0721914d860f93207fa87db8edf6034617adac.nq.gz
    ├── 7b1d0cd323c8c15101ab2f5d8e9397569428db1b.nq.gz
    ├── 7ca35ec98a43a2d7d446079a190d376d886ed705.nq.gz
    ├── 7edc84e6d8c5f3a42790af0f148408a2bf49e299.nq.gz
    ├── 80485bd20cf47cca8eb84efd75cd3583151f4d45.nq.gz
    ├── 80826f05518b0b8cba464a35c18b6ac02cc217a4.nq.gz
    ├── 80fd48f75891813518faf09b926b5fbed9b0c5c2.nq.gz
    ├── 82170f4efeedf29c0a942cc743f76e806a14106b.nq.gz
    ├── 82221d0f128197b58afe7c346446a65d2f4a5df1.nq.gz
    ├── 847e036056f497de96dc50fedfa8c67e6363062b.nq.gz
    ├── 853caccf1e376fac58a9ee6f49188d9b4f0e680d.nq.gz
    ├── 85637defe5e3074de3c226319c55d0f306cacccf.nq.gz
    ├── 85f32c7ac7eb76043a986f28b8059f04727d4ef1.nq.gz
    ├── 865e97f9e03476156d958c0a0358b4734543fc37.nq.gz
    ├── 889c692734010ee848d187c82860ae099e071c36.nq.gz
    ├── 8a1f18ff9f58734d4d8e6aa8dcf30671b793a274.nq.gz
    ├── 8c619369b0f12a9391bdebce8c7a53628d3f26d3.nq.gz
    ├── 8c7d06513c4daa3da46e03bf301b86597b3719a6.nq.gz
    ├── 8e08b06f4a206304c68cb8b9c350dcd3dd4ac68f.nq.gz
    ├── 8e741110818bdf1803b09d8d97c18f6a0c4812ea.nq.gz
    ├── 8f6f033657283af4c93b6e492bded9604865dbc5.nq.gz
    ├── 90098936395c6027a01b45293dadc47e0760ac15.nq.gz
    ├── 90fb9d0864ae0b5c5c65a4a91e9f9d4ed12f8591.nq.gz
    ├── 91ea2104897bc3fd5bbb23683f6f46e2cbd1847c.nq.gz
    ├── 9467e16bba0f516a60fc88156bf8d30f793bbe0d.nq.gz
    ├── 954a6c2a61bbc55b4e10e2ea208e55496e58944e.nq.gz
    ├── 954e5b4915c5a8546ceb6d40455bf2f0b5393b1e.nq.gz
    ├── 95e61d7c1c8e3e3a8d9df92858e769753259b108.nq.gz
    ├── 95fc6fcb8a207164698018351a187947933e290e.nq.gz
    ├── 98c759e696f64cab0542db8f6180a225472a891c.nq.gz
    ├── 9b57de3f1953096cc8fc3e0d12e80b895c689c9e.nq.gz
    ├── 9c05cd3aa3a9604653d63498328f7c98775571f7.nq.gz
    ├── 9c406323575718caf810ba61e1a6d76384fe59dd.nq.gz
    ├── 9c8ca4ee32158bf35a7a260b0e9de29efcadd2d7.nq.gz
    ├── 9cefc30b65e06740554dd1bf5c71de8eec2e47f9.nq.gz
    ├── 9ed7ebf1c1eba4da3a812f2324aec82d1a0eb029.nq.gz
    ├── 9f3ef97020496cae3e69e8af9d1affe1d9d2f477.nq.gz
    ├── a0e1f5e158f16ae839d1278ab52962a7e0e32327.nq.gz
    ├── a16a9b9e09c8805069ae7cf16c062ecc22362f94.nq.gz
    ├── a5c921ddcc29d6ea267d80802bcd2cab1d6c11bc.nq.gz
    ├── a7faf911e72ee74c1fb659da871ccc224199ae56.nq.gz
    ├── ab837f14d19f0b68776126e8d693f0e8198601da.nq.gz
    ├── ac297b49e3ab41d36c8e3a6f275bf68db31c40b3.nq.gz
    ├── b2a621307a9b1f4bffeb1fefad3e667924c8e0fe.nq.gz
    ├── b32fc1a9ec5f6223bceff7481a98ca1c4051af27.nq.gz
    ├── b6859dce258392e925d665d7a6aeca87fd098866.nq.gz
    ├── b854ca6dd87e3a3a5fdb9a9356b6f7d132129162.nq.gz
    ├── b8b1897699ca23314cb9aeaa6b26a1a84379da63.nq.gz
    ├── b9f18cde7fcf3b150a0eac4eb15bec6ef82a0d02.nq.gz
    ├── bbca368c2b555bde6486fe8b5d746f3aa1fabe60.nq.gz
    ├── c1b81cada2fe5a9dcdb99e87f4496915c024f2a1.nq.gz
    ├── c35cc3236b6f4ca04a112dfc9615549ca787cbc3.nq.gz
    ├── c37fc74fda792cdfe939adaa94fd70e16bdee5a3.nq.gz
    ├── c674fc8085ea1bb8c40a4a1cb2fdef444203d17c.nq.gz
    ├── c69c24ade2cd5d507d251797ddf55e05898053d3.nq.gz
    ├── c741b1a10fd90e9cc3a6832cbba091ab43cc3316.nq.gz
    ├── c7bbd927456e9b02ef66685719776cb4e9bc2717.nq.gz
    ├── cd9ef27ae419891161034569e56319d106ec1e05.nq.gz
    ├── cf2e55f809b64962c3e6175785b9a8a7855837bb.nq.gz
    ├── d00bf3d88d26b5aebe92916a227034e877d2b483.nq.gz
    ├── d115c54da46cb2c18614dff050a72501b2dcd1d4.nq.gz
    ├── d22aa9eb42bae3d2d675a5aab6f5051efe56205a.nq.gz
    ├── d2d5c183ac382a0978b5a7f6655fd5495fd7c139.nq.gz
    ├── d576626974f44c3e9079dabd6335ae4a892f32f7.nq.gz
    ├── d62bab1f38338ddfb10e73bc003ad33af51dae36.nq.gz
    ├── d72c9f60c8c0c18e0954a470acc0ffc6f66164fb.nq.gz
    ├── d86c13999c3bf884efb42efc9c4939bb9057081a.nq.gz
    ├── d8c16583b1b91b9ae170f747b4739a877f592db1.nq.gz
    ├── da19c64e64966cb992501cee195df37eadabbe65.nq.gz
    ├── db8f7decdf2df3de17d2f8e5425ab25beb98d90e.nq.gz
    ├── dd4c2347461527460b9949391f3ac9440639ad9c.nq.gz
    ├── dd6e9f79273b1afb9073125143e51cfe2ae0becb.nq.gz
    ├── de5e2dc383ebe76fd8240405133bcdbe3b1e145d.nq.gz
    ├── e0c70b3936993c8814463e0ecb7208832dfc1042.nq.gz
    ├── e29642bb477bb96d6656e45db0158f6d21ef7682.nq.gz
    ├── e6515aea349586849de038b43cbbab61b90c6c45.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e8536caf60bb9fded3146b6139ff94dfecd1cb4b.nq.gz
    ├── e8e0b848fa20b0ae24d3b7a0c9d305af23b4e30a.nq.gz
    ├── e99e5739eee5653a586809b7ff5b785a430ae745.nq.gz
    ├── eab006b33dfeb46deb0e2e9f85e6dedb63ce6ec5.nq.gz
    ├── ed506b96017efafdbddaf5f0bb196de850871d37.nq.gz
    ├── ee0a12ecba7e29cc458500409352f5546c4999f6.nq.gz
    ├── ee428b529885d9b16f5fb9a3797bc884a6bbc8c0.nq.gz
    ├── ee83fd5e3b03b6922c4c081d0a251768dbe0f2a8.nq.gz
    ├── ef0d8be17dba4776cb4d432df76b6fb188a744a1.nq.gz
    ├── ef2458a3ebebe682276713ab5c8d9da84ac28b65.nq.gz
    ├── f25e5576e32baee1ed029471150e4cca61f3b063.nq.gz
    ├── f29b3bf0535cac7c09aa38c6a626289951b22303.nq.gz
    ├── f29d862686d53e3bdf2186e5192465aa24759552.nq.gz
    ├── f5c1994d956f81cb16ec237fa5da253dc7458da5.nq.gz
    ├── f72f458dfadd139e3a401b83dc2a27968d67859e.nq.gz
    ├── f8418a5e42f757070195c7c80e2512ecb4ea22af.nq.gz
    └── f95076699cc14444c336553b805fc59c6093ca89.nq.gz

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

[explosion/curated-transformers](https://github.com/explosion/curated-transformers)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
