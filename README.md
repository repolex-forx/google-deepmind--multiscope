# Repolex Knowledge Graph of google-deepmind/multiscope

RDF knowledge graph data for [google-deepmind/multiscope](https://github.com/google-deepmind/multiscope), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/multiscope
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ea9bc9025cfb1531ebca9d11f53afe8e3b0b1028
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ea9bc9025cfb1531ebca9d11f53afe8e3b0b1028
│           └── chunk-001.nq.gz
└── blob
    ├── 0181d6b156e3815fdd1361090b6c480b2406056c.nq.gz
    ├── 01af0482511d734d549a70b64a2838bd196e47b4.nq.gz
    ├── 01be76bf5ab47049b836b7d963e1cadf56e29fed.nq.gz
    ├── 0366309fe29a6f7685dd390ce7639e479046e012.nq.gz
    ├── 04f392256b5088b4ed53cb34537ce979e8e0a451.nq.gz
    ├── 0517d972cae5bebab5d4215e72780cfeb25cf296.nq.gz
    ├── 053753e2d0c5a9cf2051d9c46a0102af9923c051.nq.gz
    ├── 0555afbef787057e6bb73eaa3cec5a8a6003f087.nq.gz
    ├── 076b558727c6486e69ff1e4bd4e6fcdf3d0df138.nq.gz
    ├── 07c5604821c53837987ee9d030f7bdc0e6ebdf97.nq.gz
    ├── 0af05bd8cdf9238a0d56c70d96c62f5aa8261280.nq.gz
    ├── 0c00412da6200deaa366193d6f8d6d677583c0f0.nq.gz
    ├── 0c1fe37dee6315783b968e21538a961065974dae.nq.gz
    ├── 0dbc65ad039d6b1cb61a51280f290b5afc00dfee.nq.gz
    ├── 0e9eb102c4f140319b6b3225a3940e31bd698bb4.nq.gz
    ├── 0ee95bc3090da0fdc4f9baeaab385e6d6ee3da99.nq.gz
    ├── 0fbe7f39683b0e0c874afc25dd2881baec698f0f.nq.gz
    ├── 103350546296a1d72b78157be2d2d19a3db84a90.nq.gz
    ├── 110ae294ec9cfc6b6adec91477597b3ffa6beea2.nq.gz
    ├── 1224c90f9dcf5017cd6cedd8786e3a762c514f13.nq.gz
    ├── 127186296f8d95e313a330f645b585d77fdc6d07.nq.gz
    ├── 12f1e8956b592eb1a0daffead3e7e21734bf57a0.nq.gz
    ├── 133709f56a8924b076c3224c272d782fc06ac38d.nq.gz
    ├── 13d40c16351fa3fae0b55af585d4e20f4133cda0.nq.gz
    ├── 1643a66f86447e87d8bf51cfc529a7e4c63b935e.nq.gz
    ├── 164d1067f1dc94cc4a33aed7948b66f2a55d19de.nq.gz
    ├── 171d8b260fab0c0d30a243325d6f8dfcf7588f06.nq.gz
    ├── 1855c422d0a1c77443f710e1ccc64302bac97ff5.nq.gz
    ├── 197583a98d3a77c8d9e6d5c94fafb63c26da939d.nq.gz
    ├── 198c92416ae4fa00efa4c5c6eeb2546a41d9d034.nq.gz
    ├── 19c22afbde75b60e0ccc88778d5058394d0bc24b.nq.gz
    ├── 19d90974ac380f3477868ce5bf44dc93ba2dc785.nq.gz
    ├── 1a07e21ded16d98925fa9488e04f8608d864cdb6.nq.gz
    ├── 1a7831fbcf724c7fb2d3a4f4ac4d24c89b20d19c.nq.gz
    ├── 1a92dd96d355342041ad63750e0baa3925a1000e.nq.gz
    ├── 1b2a8f4a4208759471436e07f658c417970620f2.nq.gz
    ├── 1c8b3d550b5fd0f8e3cbad8b7394b20749d40aef.nq.gz
    ├── 1de73e3c3f7cf6ae01ddeb944686eb2f26e1050e.nq.gz
    ├── 1e10a0dc1f02fd0cf5787d6f186bacb07e25f690.nq.gz
    ├── 215fdf82b2648b83e597b9388d8718fec31d6092.nq.gz
    ├── 223d435dde67eee6e02839ba6e3f8b96dbfa54ed.nq.gz
    ├── 2264ef1b4c8640bf754dd26d3097cd4f562509c4.nq.gz
    ├── 2292a411132515dc2b7ba301517b138538756aa5.nq.gz
    ├── 2483802ffa7796fd8d0026626ee2aff3af34b78f.nq.gz
    ├── 262cb8de3e844b67ded568d8045c14405a95c434.nq.gz
    ├── 26ba0b404fb37437b0f721b2f3a5c1d7c4795f49.nq.gz
    ├── 2852a727cc85a865674efdbe551ca2ec46889265.nq.gz
    ├── 28da0849476e6a91d785cfa6c473dacd04ae2622.nq.gz
    ├── 2a1111e0bcab2e0be38d4bf127821603e8d7a191.nq.gz
    ├── 2a8ea24716de575037c502394d62081cb7cfa0f6.nq.gz
    ├── 2ab5f0b47ed1e0bbf38d383790fb7bcc03c78541.nq.gz
    ├── 2b0753c1d42a6f2eae8e135af1a5d5352ac91375.nq.gz
    ├── 2bf2baa9e37c5bed62ed2f54a38c1888cebb84a1.nq.gz
    ├── 2cdb5bec6900b660d811306524a39bde8149b5fb.nq.gz
    ├── 2e3969e9192ef2c44ddd939622445d262bb102f7.nq.gz
    ├── 2fbd3997daaf9118e1f6165cf016e63a3df4726d.nq.gz
    ├── 30e7cf0273b0a30d96fc05516860f1b69944dc5a.nq.gz
    ├── 311ef6b104098dcfb32056093e64dcd409839203.nq.gz
    ├── 321547e9120748171a41ec70e6bbd12a15ae2b5e.nq.gz
    ├── 326e280825ba3b33845f4c4fd70bc7a11b88b0b1.nq.gz
    ├── 326f5deaae63e43cff680585f5cc10621c511b53.nq.gz
    ├── 32bf17b711baddb6d3e457a84a47d509d9b9fa07.nq.gz
    ├── 3370ee0a32a39cedf64c2b6de6f83b9a04d824dc.nq.gz
    ├── 3403fc5f1809eda83b6bdf5ab9ba3d5b1f94b518.nq.gz
    ├── 350d258452975cff712cadc1a9c4cebb06559b24.nq.gz
    ├── 35373791da4553cc2cab81324d4c8ee52c50bdf9.nq.gz
    ├── 372e24c6d434ff0d523b20aa7f70d1d1a1e1c2c7.nq.gz
    ├── 374f3d476e44cdd8b927ae71194d6c8fd199a782.nq.gz
    ├── 377b459f9290d866aef561504ed5393b97023bf2.nq.gz
    ├── 398ce05303d93ce90f9a95ac06dc95497d999f63.nq.gz
    ├── 39a0b2fa9952da211d5f695b7688beddce624a06.nq.gz
    ├── 39e3f229e742d563d4c843ebdd9126984cf4037b.nq.gz
    ├── 3a072a9197f089812ce6e14cff850bf37ed55809.nq.gz
    ├── 3a368d318618b77af3d69085dd9fa97aab3f4431.nq.gz
    ├── 3b060af6acd47928389538f97a0d4641f8d38809.nq.gz
    ├── 3bf4888ee083f307bc77a67716e60b06e4a180dd.nq.gz
    ├── 3c67eb9b93055afc01f483ff56228e4ea8ddd47d.nq.gz
    ├── 3cad0feb9d0cb9325a1892498ed685f8eff05ffa.nq.gz
    ├── 3cafd1983401dae4bf560e1481f3806da4c0372a.nq.gz
    ├── 3cb81e8cccbcceaaa0c200f7d6d0c617dc99992c.nq.gz
    ├── 3d722075e6e4602ee66ffd69b9fbef09debf2f8f.nq.gz
    ├── 400c40d9bc6b5f12e1e221c5da90e6eb7f7f09a2.nq.gz
    ├── 41123c8d5e23e5fdb36912dcbb97fd43bec78014.nq.gz
    ├── 4363f1dc65050c39bfa63fb619e43d226fae4c51.nq.gz
    ├── 43665cd222a6ae9306bfdb37f24e9b5e66038dac.nq.gz
    ├── 442a6f8d87e9db4935b0fcf1fe63db26ce7aa413.nq.gz
    ├── 4461dc64ce9b0a90957916f2cadec6ecae973e14.nq.gz
    ├── 4489b586bcd11a217dc28faf8ca19cc326b17fda.nq.gz
    ├── 44950e9e729c38a314f7eace5953e30b4bb51a18.nq.gz
    ├── 449a43d4ca00be365f19b3fb2c0ec130fd70cc17.nq.gz
    ├── 45a018f649117820e5772dc32dc88fff361f6f39.nq.gz
    ├── 466754c577163e93e75172cdbf486967b2b10c6e.nq.gz
    ├── 484577775eff52ef2a974a36d566b981cc5a0322.nq.gz
    ├── 48fc73d1c0a9ee558d592be61d08319a0e6b70ba.nq.gz
    ├── 4a56c09e146b9bd75e5c120b7964233584165d7c.nq.gz
    ├── 4bccf73171e72ac773ec17d9520f5ab468efc73f.nq.gz
    ├── 4c903c78852a97d9720b88ea9440a3fa92a5afe6.nq.gz
    ├── 4dd56b98b2bf4cc43e0c7e4f905eda9a373ab3cb.nq.gz
    ├── 4e60b623c245819df46f0010efa260d9a622c1bc.nq.gz
    ├── 4fbbb6e4c36d684cdc89a8550b258e6ac2888382.nq.gz
    ├── 4fd07acb2eddf1e172d2796f79baa15f81548648.nq.gz
    ├── 4fd3a8614297f41ad753e60434281deb7f55bfa6.nq.gz
    ├── 5049c356074873ade778fbafb042a4fad7a4b26c.nq.gz
    ├── 5052bddf8142730c08b2f581d61ac4d64bbdddfc.nq.gz
    ├── 51334d3f734a1a6c8182adf985b52452a033ebc1.nq.gz
    ├── 51cd17e418f5bdc42a8862362bb69fd910908372.nq.gz
    ├── 52421d4e0f4dfc55d0661bb6463e1ba9ff0fd101.nq.gz
    ├── 52d0812544fee333be9399ee05a8b3028178e70b.nq.gz
    ├── 53448255fdf596d94f9d28334db27ff79b51e6f5.nq.gz
    ├── 53c984294f828e9e3eeb0a6ce7c5bb53c70c9a7c.nq.gz
    ├── 5430783e1210cce6ac5bf6a2a6a12ef038a2f51b.nq.gz
    ├── 54f49d3222e4c6daaeefc0b76fa866a55aec125a.nq.gz
    ├── 5516e1b442cb1e81e592919f6dc0aff2529dac8a.nq.gz
    ├── 56cc4843d62003821990a04d5b861a8539f2e95e.nq.gz
    ├── 57330319edcb4e2e9c591ef0826522252643aac2.nq.gz
    ├── 5834cfec9cf319eb1ae81f427531573ec7ee7480.nq.gz
    ├── 58735baf9e5ae808ff225b47a7bc83d69ae1cbd7.nq.gz
    ├── 58afcf0587381d25edb51e5a2e7d5d5aff7ce9c2.nq.gz
    ├── 596216a15ec77b3dca37fd2513952470d0c10d74.nq.gz
    ├── 59d2079493940a8921c6669d2c4a12abda7bd826.nq.gz
    ├── 5aa135d4f4e7e62396e4dc44bb4dbd4afb8330eb.nq.gz
    ├── 5bc52307f902c70a33436c685eb39efdf603e526.nq.gz
    ├── 5c199fa9b9f73166d0261e93bbd4a89240dcc905.nq.gz
    ├── 5d0e174ef7960efb891a4109dc5689b5a31056be.nq.gz
    ├── 5d210ea9f97cb22f2a89d011a2f4811429d189c3.nq.gz
    ├── 5e8f32067b92784569c35a9f601b43fae2921617.nq.gz
    ├── 5f8c9798fe04c0d8ce2dd65f9fd771c4dbde7e2d.nq.gz
    ├── 5fd9addace32b642321f6673491195514c3b51ed.nq.gz
    ├── 621b686331cbd7c6f5d7d92097d5573345a826c1.nq.gz
    ├── 623f3feecce6f8323576f40d8a9688ee31d262d3.nq.gz
    ├── 627943e00c621e6f6cdd7a798b33c2ac9d9e6405.nq.gz
    ├── 64e04f5064484b86bf1d3b421603c37f472fb23a.nq.gz
    ├── 670609f9fcb5eaa6e4812c1c148489f3a70a6c65.nq.gz
    ├── 670c9f913762ad975f247142032242c8810e8ff4.nq.gz
    ├── 67e31ec8e506cf75e7693585a159426d8c2d58d4.nq.gz
    ├── 682480d35a290ee0056c500eb796fc0d52fa5d10.nq.gz
    ├── 6840174a506f56faa1947ff9556e6c656e2acd78.nq.gz
    ├── 6841f843ee5ddd85194fedf3761eab36d09d377a.nq.gz
    ├── 696d8fe0988c49e28c7728049a0906b9929aa861.nq.gz
    ├── 69fe8bb045d8aecb7fc5371af38d60a615906bde.nq.gz
    ├── 6aec7bdcd14ae07f7adb509da4f05f7bb3eff266.nq.gz
    ├── 6bb53bf0217f055b3bc4679cf074f8aa4e04375f.nq.gz
    ├── 6bd9770c95719b93d84b286daa14ebbb6312e084.nq.gz
    ├── 6bdd3896850cf2df8504090345de86efb446fb8d.nq.gz
    ├── 6d0c9fcbf5a1062c937b7a91206e814a72461e44.nq.gz
    ├── 6db3a6dfdbc605c37bc41dd2060c9864f9d6c992.nq.gz
    ├── 6e248893b1182992ebaad45efe25fa996e160c61.nq.gz
    ├── 703a5a4bbfcb806679a718fc300890a150e3f1c8.nq.gz
    ├── 70e40aefe8735f41ce5d02803cda9964a8a3aa2f.nq.gz
    ├── 71a85d5a44fc05d785fb5ef1641b93fd4dfba968.nq.gz
    ├── 71af45696c5a2f8faadcf5c03ccaa391794f8250.nq.gz
    ├── 71b05d178c5c5e641dcf09e629ed2b96159ce0cd.nq.gz
    ├── 71b961bc9f261132c3a68bc47039cb887d85edf8.nq.gz
    ├── 722d077f6a44f43cb0e5852bb20a82d2513cb51a.nq.gz
    ├── 7376a5a6481638336c2975ee3326d43160ba9449.nq.gz
    ├── 740dc3521537c89f08e018acb854ba46f6aad3e8.nq.gz
    ├── 749df09ec2505563a434c3a61b734637e947483f.nq.gz
    ├── 7513e1a8dfd107d0f80e78f97568afbe24f0cd91.nq.gz
    ├── 756fc3d035dfc76a40c6eb245abea0be69771629.nq.gz
    ├── 75a2a64919887bc719cfcfc79c87e1ed36d3d0bc.nq.gz
    ├── 766f9ac9734a885640ba9983fd0386ff52a921cb.nq.gz
    ├── 7856d32c6df7ef20ed1e2eff60592a98b900735d.nq.gz
    ├── 7a7a55606ee6b1030b3913c36b154f35b013abf8.nq.gz
    ├── 7b10484cbc792c3726408c7315d8aea9d04125c8.nq.gz
    ├── 7bb92ecf1a6d700b17234e5b0e0179ac26b50b4a.nq.gz
    ├── 7d4eeea118e86ac1d834f5695296888791748d8f.nq.gz
    ├── 7dcdcfe4d6e938a874542b1331656272665114c4.nq.gz
    ├── 7e4d1d2aa0ea3d15b6175f4010e53b2f27bd90cb.nq.gz
    ├── 7e5eea64c9bc21aecfddbe5bbfdf053c3a4017ed.nq.gz
    ├── 7fa1e2fc5013e0e2038d08b0aed53e642c662730.nq.gz
    ├── 80011c8a46717c6209981a08f2d2004147c6e160.nq.gz
    ├── 804bcf8ba3ec8af9fa371662b196cbeb58bff02a.nq.gz
    ├── 80537dba85e45c47b5ab257c325597bd86c5c837.nq.gz
    ├── 818b4a984bf0bc9da51715f0c5d1f8269df2f996.nq.gz
    ├── 82013e22b432802ec33bcb4c33caee972d820481.nq.gz
    ├── 83cfae4ee0e786049a93424a347aa36e3355a1ef.nq.gz
    ├── 8401cdf6a73f56e87798ac3847d12d2fd9f2ffb3.nq.gz
    ├── 8425ed3dcec55f8c90f93b663bdc4959ab876c86.nq.gz
    ├── 85e1062f5601cb60cd49cc428bbe7a8fba65ca42.nq.gz
    ├── 863a8b7b9377aac65acc2cb9c02f264640d08a21.nq.gz
    ├── 8646df461f1e10f8ff2bf707c1b242b2b8a541c9.nq.gz
    ├── 8815299ba437f512503d9a132a799a1022266f6a.nq.gz
    ├── 894b40ac398f92945d890e552f7003554268a0df.nq.gz
    ├── 8ad80d93f5b9acab2ba1ea117d0639df967bb225.nq.gz
    ├── 8c3bbc2270c05b85f03b80569d94210e1c5f6fb4.nq.gz
    ├── 8d1db4941a07254a7cbcf18932ba2c2564d6a322.nq.gz
    ├── 8ddcd402b5c2dc5c0ede2e06eb51340166ee84fc.nq.gz
    ├── 8de5ea30b2b431c3dd620565735d4b2dc22396f7.nq.gz
    ├── 8f75eb90c53d5069e7e26444eb7094bd722f83ec.nq.gz
    ├── 8fa747ceb3d50df82a826f0e7a48151d228e457a.nq.gz
    ├── 90eb678c03d53afefb317cb3597de7071197bb35.nq.gz
    ├── 92e37202f70bb5a0e78fbd8bdc7acb22adb23519.nq.gz
    ├── 94e6f2eb9e707c72a27ff7a24eef7e418b0e050e.nq.gz
    ├── 951589b5c42e170bbc46248342306d96187052fd.nq.gz
    ├── 962ade511653568a4b93329e66ace61288578499.nq.gz
    ├── 96d50952000ecbbbc366284a0f02e3f1f1a547dd.nq.gz
    ├── 9868d6ee6f4e4dcba0a095dd298e51be567d8305.nq.gz
    └── 988e8132fe9f6845795ddff15aa222e6c72c0065.nq.gz

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

[google-deepmind/multiscope](https://github.com/google-deepmind/multiscope)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
