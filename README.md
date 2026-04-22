# Repolex Knowledge Graph of apple/embedding-atlas

RDF knowledge graph data for [apple/embedding-atlas](https://github.com/apple/embedding-atlas), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download apple/embedding-atlas
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5938e875890b49a432648426db4e97ba977f0b67
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5938e875890b49a432648426db4e97ba977f0b67.nq.gz
│   └── repolex
│       └── 5938e875890b49a432648426db4e97ba977f0b67
│           └── chunk-001.nq.gz
└── blob
    ├── 020d63ce14f5f6dc8ceb06bb717dcad796c481ce.nq.gz
    ├── 0347172ae8b7247a185657cafc5ac6d007629f7b.nq.gz
    ├── 049ae6ffe688d16bfbc9fa752a51a7e438c2604a.nq.gz
    ├── 063a5ed94f902fddfb6104cca6ec693085fd5e00.nq.gz
    ├── 06dcb71f878102f4160c2f9953f7ba05c8adca4b.nq.gz
    ├── 080e1ceb72bc608dbb25c57f0c9355ed07dceeef.nq.gz
    ├── 083ba314ee0072cbb2bb2ba7234484f4dab20787.nq.gz
    ├── 08467b14ac182c4b52250dde793e385cf72ba6b8.nq.gz
    ├── 091325f03252456a53fa75d6ee8b05cd0228117b.nq.gz
    ├── 0993c174116ba56246aa30559ab2a79838d128d6.nq.gz
    ├── 0b68ce12103fbb7d7ac9d5d8132291da002c556e.nq.gz
    ├── 0b6be6e16e43ecef8497c91c58556649e71ad760.nq.gz
    ├── 0bab4bfebb7262ec55915ac298e28202ea4166a9.nq.gz
    ├── 0bebb1c35930838609cb029746e1feadcdf1e096.nq.gz
    ├── 0bf0d6b6d58a958ca3d3394af85e8abb3c1f9b74.nq.gz
    ├── 0c1f5cb989411b4b931f8bca8ff76fbcf22cd3d5.nq.gz
    ├── 0d5afbe90c60f8efcae6724e7a21a00d34e1dbb6.nq.gz
    ├── 0d64527b3219aece3e84358fbee9059c5ac79de6.nq.gz
    ├── 0d9a3d4bee0c9db4aedb45bd817ed2b50c8ee51a.nq.gz
    ├── 0dfa959aaeefe3a5ef3ed0ac6f66d2f4115a87d1.nq.gz
    ├── 0f31ee855f92a9c04670ba51f2403d8fa47b947e.nq.gz
    ├── 0f55380f92c9c1ec914531d1daf9f10084016897.nq.gz
    ├── 116351ee193391c8cf338e4c6b55c905699351f2.nq.gz
    ├── 11dfb458fe88ad59b7eb450638a250ca830dd22a.nq.gz
    ├── 1293cc67be3753952c462d422d6db9979da93757.nq.gz
    ├── 12f3279dd6c0dc61c2f2e66db6c7b963c87409f6.nq.gz
    ├── 13185008b6a7fb31a809e9a280c6df9e0a8d6cf7.nq.gz
    ├── 13187396d3fe67b65415d84f2b8151da68d90065.nq.gz
    ├── 1349789e0841a8c450b9ad72806ab388de05bed8.nq.gz
    ├── 1360275edfe90a764efe49090fe8d157f6f17b5d.nq.gz
    ├── 1440953b3380808387f49325f510ea6087b75aaf.nq.gz
    ├── 14be50000763dfdb084e258b7844659d5ed12fab.nq.gz
    ├── 1595cf456e3e34b73f1126d80508a8b4b6d3040f.nq.gz
    ├── 15e40e8ef36dac2504bcd4f2381f81f86a32a7e0.nq.gz
    ├── 16325148433d134ad5142d9f9106bcdb8bcaac95.nq.gz
    ├── 166959906692a5a3ef65458f748b07a2bcf26779.nq.gz
    ├── 16bd9ec9498eac521585eafcb9cab9603d7128e5.nq.gz
    ├── 16fe0f9e0729c8918a40c2aefc89a9aa0aca9311.nq.gz
    ├── 178550d5d3decfeed8a8ba2128f2c69c9a3180b8.nq.gz
    ├── 1a1bb497e607afa570c1167d39aa3f658dc84204.nq.gz
    ├── 1afe20ed1d5c3df77f0a9f37d41d938b848ff744.nq.gz
    ├── 1b2c67ba315236ab0ad40d8dff16dd5394332d94.nq.gz
    ├── 1b371b06c9fa1fa89a500b09b7bea80c2bb8a028.nq.gz
    ├── 1c31085b90ebaf81c67471059aef84cbfe03858f.nq.gz
    ├── 1c331d845176e2f8d7b855cc8b6841daabb8bc7d.nq.gz
    ├── 1c59eea05150f6c37b52e37ddff6b84793351e9d.nq.gz
    ├── 1cba04c1683545fdf65b36715532bcf2ca0b82cd.nq.gz
    ├── 1d456dd7848e41dc2db5b1f46b62a6996717a89c.nq.gz
    ├── 1db3632a22b1875ea05099f059ffe52ea319858b.nq.gz
    ├── 1f6319cf2df2fbe96461be5a734a41fc2f3f1d9b.nq.gz
    ├── 1f6f9f3d72a679cfe7af36ae417b5776c39064e7.nq.gz
    ├── 1f8022d4df2c9967abf5a031e1af42f61813b88c.nq.gz
    ├── 1fbd0edb16db49b6e37562d3bfd0648116378481.nq.gz
    ├── 20a86a6e6fefcc8f1027943d4a715a8644252a9b.nq.gz
    ├── 20f7854eef8b624ee7eeff91ff1022a62359aa75.nq.gz
    ├── 21c09151ec882e9a46d62bb5ed283617c237d28f.nq.gz
    ├── 2260bb089ee0a4f7c65031f3241378e087fe4ca3.nq.gz
    ├── 23105fa0db1e3520047359a8eda05a6b2ea68709.nq.gz
    ├── 23ba432c6e3a9d04e32c05b556e76efb50618831.nq.gz
    ├── 25246e67353b9f9aedf9e245d54f7e2b74fa666c.nq.gz
    ├── 2574057b86249c11f45c9a132c643d664b91d366.nq.gz
    ├── 2585c0fef36e6dd58956be787fbe4487572ba39c.nq.gz
    ├── 25dd5727f2687fdf8a351a1dbc7e53944e66101a.nq.gz
    ├── 270b10fccb84b841bd388d9b00db1fdde530f278.nq.gz
    ├── 27d9e545681ccc0ba1c7b59fa97247894ccf5c79.nq.gz
    ├── 27e7c13b46191cba958024590c648742c29bbfc2.nq.gz
    ├── 28026899a7d40b9dc68c0caf151149dd89aea919.nq.gz
    ├── 28b17e1272b3a7382c3f0d8e102cb3a47a2f70c0.nq.gz
    ├── 292d6cc6f7b79fd5044c44b907087e70fae8c8a9.nq.gz
    ├── 29308aa10a46f2d4cd6d7ba7d1dbe8b040579897.nq.gz
    ├── 29775af6f9edd2b9e1e7e61149eff8dc7656cfce.nq.gz
    ├── 29af739a3aa695b490f9360ebdd6e4607fe7d930.nq.gz
    ├── 2a8cca5da3530f43ee4e925ccbe29e5a7827d1e1.nq.gz
    ├── 2b36d130e078a855ca5054b9500914883d2f6b6e.nq.gz
    ├── 2b7e27b9de012a169f8fb485374a30a10735fd8b.nq.gz
    ├── 2c622591a4fd8993be1a2aa172cfcc6c783fa6cf.nq.gz
    ├── 2c8cabfd62491b119cd8cea5184ddccf0582980e.nq.gz
    ├── 2c986a51acdd2690749a70ee801a5a8dd110d4a8.nq.gz
    ├── 2cdc5e77e1533b97c9fa6b2e9b87a03763c91154.nq.gz
    ├── 2d359296fa4d88be39c43201456de8caaaa45a30.nq.gz
    ├── 2d976f79c2fef9e04d10ad6f05960127869b295b.nq.gz
    ├── 2e087fa347a17381a25838980f9dc479f4173f3f.nq.gz
    ├── 2e08cff4b567f192ef7811b97105b89b27805a3f.nq.gz
    ├── 2e95f4c91188e5776c277fac3e5c07fa286b7a09.nq.gz
    ├── 2ecf72b4bae72cc2a944725a7746b252c44f6c17.nq.gz
    ├── 3077d4bb6f1fca9031c442c309bf98a0b7f1800b.nq.gz
    ├── 30cd5f42c8b60ff512ee0030daae8c1589e65fd4.nq.gz
    ├── 3274f43a3a647d2cdc6beff76c626d5176c6de76.nq.gz
    ├── 32c8a2c61208f1e9826e24823175c63035e33a11.nq.gz
    ├── 331fd07db9e934833b3c941b76d7d22e49fbd682.nq.gz
    ├── 33b7f2d9372d9c7ffbb5199a8203d2809f7279a5.nq.gz
    ├── 345a7b886f673fb11c225dc61a8d5fbed1c41d76.nq.gz
    ├── 3544aa14d60a2d8e02350759b012ec34dcaf5e69.nq.gz
    ├── 354cbeac31d06ea57bc898d1f5fc0f2212e85031.nq.gz
    ├── 35a783752d05511e633c9e65c3432d8e3b4171c3.nq.gz
    ├── 35f602de13615d2978be3c13a80421380c4f5cf0.nq.gz
    ├── 360f0be30bc7d286266a90e672082ea5aa554c06.nq.gz
    ├── 363830c0f65dd9b581a70630527a9a80b7ea6a36.nq.gz
    ├── 367e6d9759c809c1993c51f216fa6e518cad1893.nq.gz
    ├── 36840ef8e9f6f456d919cc02b079c1e5bdf01819.nq.gz
    ├── 368e7320f02ab1942a4e05c1a02f93a80eb55881.nq.gz
    ├── 36dbb1b52b8f21e298bd2a838d5a3e940db9cf27.nq.gz
    ├── 36e0ea06972ee7f08e211ec292de53fe32432f1c.nq.gz
    ├── 375245ed482b95fdc523b8e586b45f338b827721.nq.gz
    ├── 376b71cb4fe3faeecb2e08b8d0b1cc8b50fc36b1.nq.gz
    ├── 37a94b395980265910f653f21da05fb00542f8c9.nq.gz
    ├── 38460fb376536f8d96e3ac1d2fde8f146f045c48.nq.gz
    ├── 384937ab5a9a01956151d1bf1a9604bfbc1ac20f.nq.gz
    ├── 3864d3b1abfe8dc61370dde625b75f6209dd1812.nq.gz
    ├── 386a97766a0424390727f8f22ca6fa88887a6168.nq.gz
    ├── 389ce6f5517f930bbb53dacff8438a8ece49f6b4.nq.gz
    ├── 395fc1314c1d459b13d23f6ade9e8cd998844166.nq.gz
    ├── 398e3f13f154be8ed572a00e4082a7f483ae8175.nq.gz
    ├── 39c92f22657c0c956457f5986beff0842dbf5188.nq.gz
    ├── 39db88696569bb6656c3dab838fae6a520aa4fc7.nq.gz
    ├── 3a0bc7d15b6cca2c47b4b89a75116e0e1182b343.nq.gz
    ├── 3ac6b36bc60ebdb38f0ac41f36782b3e792864a2.nq.gz
    ├── 3b221d092c7ad71b63382305c2338e0ebb405fd2.nq.gz
    ├── 3b3ebc6657d7fa9558ebb2bbb7e16b1351894727.nq.gz
    ├── 3b42af0c85de2a673a3881419c74c40d2e62d8d5.nq.gz
    ├── 3cd35519c7cdaa3a451da192a04e4efb0cb1ce42.nq.gz
    ├── 3dadaabd16cba9e133a67b667f4e0796871bdbaa.nq.gz
    ├── 3dbb695be46551e4ac24964d14fbe0e421182ded.nq.gz
    ├── 3e855b6500481dc9c7d6c377a92aa30b1f87e2fb.nq.gz
    ├── 3eda4bc823df7cc4d2d5daa5498c5978e4f01e69.nq.gz
    ├── 3f0fe729ccf3761dea03c045052b6e7618ca3fcf.nq.gz
    ├── 3f783c0d8b71790196da3b374c0e804cbb5d5c92.nq.gz
    ├── 3fe485f853a7ea121b1cc71ae7a8f390ad9ca825.nq.gz
    ├── 400ba30d277c6073201dc4a2d298cd0395c0312c.nq.gz
    ├── 4060229d30e31b47b4d8d81a147565094e0deebf.nq.gz
    ├── 417051ccf2da9a6d72068f29adc3c8e0bf2e9add.nq.gz
    ├── 41ac22be5b746cd098a38b5be556812cad02d5db.nq.gz
    ├── 42676a977cb75261bc894c47e7df837dcbcff94b.nq.gz
    ├── 42ddfaddf3e256af03cfbbca92f6003a684eb9a2.nq.gz
    ├── 4424a8c7f52093420cdd7046634af9fad97bcfec.nq.gz
    ├── 44a235f86b742048d7e83b33c61c03670104bd5f.nq.gz
    ├── 45160fef6dcfaef482b1f31a5e00511405266350.nq.gz
    ├── 45202d36084f6eb7c8983966845dabb0285e66d2.nq.gz
    ├── 453b38e7a392096167c58a713a38678e273c4daa.nq.gz
    ├── 4591a85930ddaf48e2097ffcdb30886f884ced01.nq.gz
    ├── 4889e3a6d43b08011be879ff4ade0f7d693bc77b.nq.gz
    ├── 4a677c87911487c9d8a8ec3e0c2c5287eff148df.nq.gz
    ├── 4c7672c0095b3fa9ecd652cf0b89e9ce7d0107c7.nq.gz
    ├── 4c76a243065e449d9cd97a77bdbba6b00c7acc53.nq.gz
    ├── 4d1be416d2311c3179b46f43020aba5325d2aa2f.nq.gz
    ├── 4ddeecdbc5a187f920d54ba86bdd8d8ea31b1242.nq.gz
    ├── 4fc107bafbcd8dffe656de2ad1cca40a7cbd9adb.nq.gz
    ├── 5084fe8dd4e76e3f035b05e8f94758750dd3e593.nq.gz
    ├── 5340e77d6bad9dd6fef4a78d8ebaf1804e68e4f8.nq.gz
    ├── 546e8dedcded6aea0cc9a78f566ccb0b6d89ce11.nq.gz
    ├── 548d5af837a9867411a3774ceb8b306d180658db.nq.gz
    ├── 554a71c2a7c69820f9f13dac3926848df015cd3d.nq.gz
    ├── 55568eec944e40d174e68071417137b727c791fa.nq.gz
    ├── 55ccb3ad62529f3dd54b8902ed3d058d3bbf08fe.nq.gz
    ├── 568c2100681229197fe855617ed5c7596b8255fe.nq.gz
    ├── 56f691571c25bf8d723db7499c59aa379f9d6caa.nq.gz
    ├── 575a56973123e9f0788207a77474a05c0b503cde.nq.gz
    ├── 57fc71eaee0d2bd4bee95dc910d4fa2385d9249a.nq.gz
    ├── 58ac87b8adb5d96206a3bd479ef50f3854d86626.nq.gz
    ├── 598715df9fd8db488b08bef645a0f4426d93872e.nq.gz
    ├── 59ff75ef1d6314a756ce4fe9fe150296d6a2be89.nq.gz
    ├── 5b2c4a2f430eb413fe14f3f2a76ac4461d29ac1f.nq.gz
    ├── 5b6919c51f077741d5f9bebb10a1701ad0b52850.nq.gz
    ├── 5b6f2d8dd027f5c0a20734f46fd7c1d45f439697.nq.gz
    ├── 5b8e1056bbfe29fa243556afd75257f605159bbe.nq.gz
    ├── 5bc6014aa06ee7f743e3dc301c190bb2de43f382.nq.gz
    ├── 5bd38ca993ef29c09f8dc515daeab9e63c490d2c.nq.gz
    ├── 5c114c6ba57cbc13fd13d90731a69beee49f3a16.nq.gz
    ├── 5c3a3be979d5bba396b586009d01d1c685469075.nq.gz
    ├── 5c68de4fec4f42cf562f0739133b2098774c5a0d.nq.gz
    ├── 5cc284fcf4db4989f7262ec2a659640382458e6b.nq.gz
    ├── 5e1bd0e556ee9e72f7e5fb01cf0b774aa548385b.nq.gz
    ├── 5e9248669747c00dbee1f5531a92008368d68d08.nq.gz
    ├── 5f1b707948ff028a9c2328071a250d0fbb954ea4.nq.gz
    ├── 5f271bafee8915cfc1d4444ef286a10d92242d0e.nq.gz
    ├── 5fe025dfe5da420ef7e2973b41a2db074d2e6b88.nq.gz
    ├── 61775b5ac8aecff8e9c7223fd920c2113a456ec1.nq.gz
    ├── 61aedeff4a7ec682b3ca7183c56b00ee48764570.nq.gz
    ├── 61ed06748e05d0b0d67441a3dd35a0929d8bdd87.nq.gz
    ├── 62cd14c42947a4f26c8bdf1aad711a69c9b0c284.nq.gz
    ├── 6304a936af2fdc0fd26bc95cd965254f451d81eb.nq.gz
    ├── 63ae2ad912cd963412df30466b17c2c5d36989a3.nq.gz
    ├── 642511ec5b5a0db04f621ca8d9b71ed43d81edfe.nq.gz
    ├── 6437bfde85820fb7bbd53950cd776e56aa52d059.nq.gz
    ├── 6484c4a77289489ae7d387bcd901feb9d7308c31.nq.gz
    ├── 65f311a2a207453ecbe9888b0e179ad6d3e1a57b.nq.gz
    ├── 662b6a2c3df34aab8b3cfe8449817bca23325aae.nq.gz
    ├── 66a77b3ba14430e5b5dba9690bb6e26e77adcbab.nq.gz
    ├── 680939e147c52aecd5c9b3568d10162e25de0ad6.nq.gz
    ├── 68af356c5870284ce1903dc2cb89665f9f9f2f09.nq.gz
    ├── 6972b242a492927c5803c81df9207456e8c9d754.nq.gz
    ├── 69745a16ac38ee3b61ec6f75734351545bcc0304.nq.gz
    ├── 6aba96e0a7a2b376571e50646af0264264be2060.nq.gz
    ├── 6aeeff5570fdfa1d28d42ba7ed1cf1dbd6217906.nq.gz
    ├── 6c036d27254aabc999ef85cc4af8c537442bff3f.nq.gz
    ├── 6cbf3196862cabe5477c2c1f9818e670173a6467.nq.gz
    └── 6d33093e916741bf14427d9eeae5c20b7fc3e6eb.nq.gz

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

## Source repository

[apple/embedding-atlas](https://github.com/apple/embedding-atlas)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
