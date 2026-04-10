# Repolex Knowledge Graph of netlify/cli

RDF knowledge graph data for [netlify/cli](https://github.com/netlify/cli), parsed by [repolex](https://repolex.ai).

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
lexq download netlify/cli
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── be7538b5114031aa84f11707f8e46a8cda7f824f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── be7538b5114031aa84f11707f8e46a8cda7f824f.nq.gz
│   └── repolex
│       └── be7538b5114031aa84f11707f8e46a8cda7f824f
│           └── chunk-001.nq.gz
└── blob
    ├── 00572999ea9ae7ad9ea839b2e0c7398391a3d0eb.nq.gz
    ├── 00a202eb37c8aa52dbf629781581aea10a603d98.nq.gz
    ├── 00fe967affe3450f3d8e0806ea1386b5b6e6ea05.nq.gz
    ├── 018f812f7be4f29ac98884965ae5b61929124fb2.nq.gz
    ├── 01d07f75348b377bf6dea7d45279b4838e6592e6.nq.gz
    ├── 0209e106eb7acb3bb79e632fa242b06b5027c624.nq.gz
    ├── 024ee6bed5bd2febf05fdcc6c32f934bdb130fe6.nq.gz
    ├── 028bdbc7adff9ad45fb62a8e23e9b9ee83380db8.nq.gz
    ├── 02a8d3f50e734281080e1fecacd49d626c0fbcaf.nq.gz
    ├── 030a0506d1528664878896049417726e60019e04.nq.gz
    ├── 0355c4a3097ccf7154b4eb542004327ccda64dd7.nq.gz
    ├── 0363cb1d0d1e23b6dfbbe9fd57033bfa0181c5ff.nq.gz
    ├── 0382e9c891b4aeb9df8e0b81832cc6fa3bd63e9e.nq.gz
    ├── 03b5f94b2874decf3b7563291f3473cbea193ce8.nq.gz
    ├── 03d8b34e8cb1fcdcb76d8bc33f8bf31d2d4dc468.nq.gz
    ├── 040b491f434d734bcd91c99556a7d32463c890fa.nq.gz
    ├── 0411054705b07476e01cf0f1de25b2199d8eea5d.nq.gz
    ├── 043f218cbb4f942a0394bf41b43a6719339320b9.nq.gz
    ├── 04a4788a9b401ada9a3a1d8aa0961290c4780f58.nq.gz
    ├── 0531b20294812347c932b1e133c3e0198b0ce3d2.nq.gz
    ├── 064625c444bd080c4b9ef98d73a2bf0df87e100c.nq.gz
    ├── 076dd8096af19ddb0512c021993eb1468c5d5d0d.nq.gz
    ├── 0775c79f230231f2a3473f2c6f16d7ad31fb38e9.nq.gz
    ├── 07bef3a31db6baccc56bdb2e8721a28efd0d277f.nq.gz
    ├── 0866c8b6e0238385382672a0bf482e1dda15b66c.nq.gz
    ├── 091ea94fca573f367c03157d8f66cb91ef90a533.nq.gz
    ├── 09225c0b5d993905ffd5b3787cbd0aac33ba5112.nq.gz
    ├── 094c3ba00ce0fba73ea28feb652c7046fba945a9.nq.gz
    ├── 09a8c1ae32646d7bf1525ef7f5b8c0a1a53cb16e.nq.gz
    ├── 0a78cdd16e3451ee2205ed0ebef3a61cc5632c1d.nq.gz
    ├── 0aa32a4a1384498738982b8da72b0f75a0d58adb.nq.gz
    ├── 0b105e97d05a26ee4395dc79f814a349809b21d2.nq.gz
    ├── 0b2a5fed09edd4a24dc1c2dce5bc610a0c575c8a.nq.gz
    ├── 0b7c6243bc554b756d732c61df769c48243b13be.nq.gz
    ├── 0c04261cf1fe304b10613f2ebe96badf9bf0dd61.nq.gz
    ├── 0dec5c39fd4fc3eb9a3503aa466f1b22bc239bc5.nq.gz
    ├── 0e01094a3b3105de88d89cb5f331d9f6f63267e2.nq.gz
    ├── 0e71da25257ed7276442636968cf5b3151452233.nq.gz
    ├── 1034634ebd1e870fd78c982b678095609e470dce.nq.gz
    ├── 104d1a34fa1484148cd60aa4c33122a9bb4d935c.nq.gz
    ├── 10e0a272efd13d56f7316d489e0fc8bc918b0c30.nq.gz
    ├── 10ed886fab52046296b6055cd987fdc396dd51bf.nq.gz
    ├── 113f1a42efb254e58838f0f52386a9383688155a.nq.gz
    ├── 1186308ee8a33227fda05b693fd86aa44a363e7a.nq.gz
    ├── 1197411722bd3a17028e154c4eadbc8a62dceb0e.nq.gz
    ├── 11bc934dc7fc3b4a2b013c2433a31a35260ca760.nq.gz
    ├── 11c887ec00fd6f5371e45f760a3dc7a870936166.nq.gz
    ├── 11f5da7b1bab129ce741d09e1084c853c89b6107.nq.gz
    ├── 128ececfd050566d532ce44fd91a44139c6764f3.nq.gz
    ├── 12a8d8d6bc19d2ca8621867cc878d509e1272191.nq.gz
    ├── 12e6d0726ac6f7e485123dfdc443339f956472c0.nq.gz
    ├── 13057c1864fd8703ab305c29bd12c30dc94c205c.nq.gz
    ├── 13ec66d5e2641f966070a2110b4d648dfe8aa1ae.nq.gz
    ├── 142460a4a044fb4fe28c210379930177601f2520.nq.gz
    ├── 1490cf5215c125c42855639c486cdbbf5c19e763.nq.gz
    ├── 14e1aa8ded6df7db2f8d1aa25ea18c5e99f22a18.nq.gz
    ├── 153c401cf7794f3a039b5d42113f630b638d4ce8.nq.gz
    ├── 15b4825127a1d092f74c3dd379f12905bca721ce.nq.gz
    ├── 183e3984724ca52e293be73d5e49d883ff6f6232.nq.gz
    ├── 184b8ef1b4c0b177ec093c7d4d78383f9d4a0495.nq.gz
    ├── 18a0350ef3c95ba85f05232501db2aa388a515af.nq.gz
    ├── 18efd1969b1a78b1b79341b767860df264b07c45.nq.gz
    ├── 196faf91891106b9cfab2d03b2e04207409d7ea1.nq.gz
    ├── 19b8d48d5111599c4ae9da9d401fcd79cc6d4a22.nq.gz
    ├── 19c05d861edb141b67e87e5485299fe82b9d6297.nq.gz
    ├── 1a0cff793f2fb79a352871b89a3d756b08075966.nq.gz
    ├── 1a14da1d55572421a3680c47e4c13559b53bc5a3.nq.gz
    ├── 1a1a274d7a7a064a3981cf139cbf5535813e2725.nq.gz
    ├── 1be35774b8e5cf7548d2e4c3e3ea2c63cc9a73f2.nq.gz
    ├── 1be43ba7bd5c6cbd32530a850f90ce64a5a000aa.nq.gz
    ├── 1c3b5549dffcd512cdac31a4970170d28fd19194.nq.gz
    ├── 1d3a75d8d5b2861e08c84aaa014cb1828a80f25f.nq.gz
    ├── 1d6147825a3c4dc6b2183d312d5b310c14f3a1ff.nq.gz
    ├── 1d95e2f45771785dd4be9ef34c29ec2747817a22.nq.gz
    ├── 1e82f9322a80ebd42da92ee65357b2741c799889.nq.gz
    ├── 1e8589531f292723b8974ea5a4eefe279b131921.nq.gz
    ├── 1e995fb64411cec5d43ee3570c8f9e9881f85fbb.nq.gz
    ├── 1f1e643a77ed5c0e6345337fc8d73488feb45047.nq.gz
    ├── 1f24269f77818dd872143e62ab444ddfcb2b0d53.nq.gz
    ├── 1f6cafdee62d74981ac99fc4c678b94f7b6e01d1.nq.gz
    ├── 1fea38caefd4e427860b6c87028a594f1d38e583.nq.gz
    ├── 201becc5afb54ccc38cb071c1273d68dd53e1a71.nq.gz
    ├── 204585a4853e703a38ee75dc05c9f0fb68cfd933.nq.gz
    ├── 206ab20fbab50705c6d95b6a69a0540b989154d6.nq.gz
    ├── 208a709e2647c315f6e004017de7bab1a80b6100.nq.gz
    ├── 20da7ccbcefd9fd554e8f55fbb4a88be122167e5.nq.gz
    ├── 2194476e3a6e4baf4c60b0e354b1a91fb303450e.nq.gz
    ├── 22110a3cedea2bd39fedf3dc27e221b4570ea8c0.nq.gz
    ├── 22666fb3352f0c6d107754bcef0f38cdf3b65c25.nq.gz
    ├── 227adb1ab229726e31577d3c4540f129351488c4.nq.gz
    ├── 22eaebc7e53826c1371ed1fcb9dbdbce4f0001b1.nq.gz
    ├── 232132f87cf8fafc9b25aacfa532a086e85353f5.nq.gz
    ├── 245c34cb8ae2b679f38cc8265213bc29df713de7.nq.gz
    ├── 24a00228e6a0c4fb482142e41fbec221ccafa436.nq.gz
    ├── 25196e16ed3f5c68daf5a8f2691014bfd3dfc22a.nq.gz
    ├── 256aba557f0d242161a3387cb75eff8e5c570a3b.nq.gz
    ├── 269593b3074d7f4e382ec8a0e8cd063df11ebb3b.nq.gz
    ├── 27cebc921637dd5d3e7c5ff01fc2d3f032f793fc.nq.gz
    ├── 27d2ca25f54318b62cbdbb0ee839377e49b3b099.nq.gz
    ├── 2810d2e8f64aba667d00688bd78cc008e3fd52da.nq.gz
    ├── 290e8f4171da1915aaf974f394d4609d34ae31aa.nq.gz
    ├── 2a107f22b994f143c17d8b03c9772d43b41bb4dd.nq.gz
    ├── 2a2ce0e91445f58eed38de8e5a12f23345105557.nq.gz
    ├── 2a2e4b3bf8ba1c86d96fc2f5786597ad77a0e5e9.nq.gz
    ├── 2a8c5388c4d1d4a68c4e191bc0c1dcebfe61d2cd.nq.gz
    ├── 2ade1040131e1652a0a2ecaa4b4f9f2df4570fec.nq.gz
    ├── 2b345292b360a49543d26b4f4e831556949704ea.nq.gz
    ├── 2be0f0c198de1013ee21614484f9b585d42b1fa0.nq.gz
    ├── 2c79148ce11716999dff6420896ae412b22ba8bc.nq.gz
    ├── 2c81e52ecd63c82fbd2c26412c5051cbcf66dcb9.nq.gz
    ├── 2cc1ac3bf1732ebebed55e0aa350a6a91eeb757f.nq.gz
    ├── 2de37951736fa3f11845c8a264e85c6a56237b3c.nq.gz
    ├── 2ea4282c6a79bfce6c733d3607cc06ea2bf637aa.nq.gz
    ├── 2eb83252ab91fc7a820d74a8db2f17909e214de4.nq.gz
    ├── 2ec6462b225a29ebff9c5eeb22df2af15f77c656.nq.gz
    ├── 2f16797b03a17153441c38be9956c67be9845103.nq.gz
    ├── 2fcdfe0134becc2892ff9404f9179037eeb9ade4.nq.gz
    ├── 2ff2f5c817ed80e9686de6424e9a1d94f9b9abe1.nq.gz
    ├── 304c4fcef134f057d72d23be341306242baf29d0.nq.gz
    ├── 3071b210ada121d877fd5d0e99b5941fcac03e43.nq.gz
    ├── 308fb6fb717bcbd6f76b2f0159df1d578de25e43.nq.gz
    ├── 30c49b40a63dcab419c061ec362c47bde004ef79.nq.gz
    ├── 31492fd5da0fffe2ccee6a1eedcf9b4e10a5c8d6.nq.gz
    ├── 332bc8dbba6e592681a27ea3e5b307df49490af5.nq.gz
    ├── 3439443c16a3c4aba278daa23888875b00cc10fe.nq.gz
    ├── 345b87101f334e97c54b88c72aa6702aea13ca6b.nq.gz
    ├── 3504377137e605ef16e4bc76b43acdbf9692041d.nq.gz
    ├── 3512f40e3035f4a15b9565f6de961bd750c2a647.nq.gz
    ├── 358e7eb3e232241014fa556741174306a679f8b3.nq.gz
    ├── 35c86c2be63ce85a531afa88b0e225a7e352c381.nq.gz
    ├── 35f4a601d808bc1ea2745fa8bc301e71788ac9f3.nq.gz
    ├── 367e1823cc5b0a4646dd88b20690840c69f4a022.nq.gz
    ├── 3683980d9ff4d84cde09628649f38c50a2030380.nq.gz
    ├── 36d3cb1caf1d68f67f087c74ca50d4cd9ba9410b.nq.gz
    ├── 36d99398181ebe4884f919f960cb4aa05b1b4238.nq.gz
    ├── 36f2bcec074ceccb9b7d2fc8a7403ddd92844d20.nq.gz
    ├── 370c3a3730c182f68defc5ed8cbe549192e29ecf.nq.gz
    ├── 376f41a61481cc6515cc78a5145350127eba6cf5.nq.gz
    ├── 37dfa2281df679cbbbabd965d029f5c784b919c3.nq.gz
    ├── 38d89ca822597ce0436ad2cea6f7158ae28b63a1.nq.gz
    ├── 39600f15c563a29adee6d53540319264bf8986a4.nq.gz
    ├── 396599947640a367b3c7e72e43d28aab8f134b70.nq.gz
    ├── 39918666deb79d8817cb4e4fb9a061b2fcb6b897.nq.gz
    ├── 39f18a825794286baed85c8e00509b419d8c1432.nq.gz
    ├── 3a653e93fdbb32b701aacd83ee8b7d76019f08c3.nq.gz
    ├── 3ab96e1dfbbe801561b4e1327d8912f80cb56832.nq.gz
    ├── 3ac82e477e74251f643120e6df6933ac7f3c8e36.nq.gz
    ├── 3b18e512dba79e4c8300dd08aeb37f8e728b8dad.nq.gz
    ├── 3b725f601e27f51bbe5e6ae749b20ede15409e15.nq.gz
    ├── 3c01ebf17a3c163d2f5e9334b0b3ed85b27b4291.nq.gz
    ├── 3c1be8415ac624ef7dba71adc0736404cb5639f7.nq.gz
    ├── 3c3629e647f5ddf82548912e337bea9826b434af.nq.gz
    ├── 3c49ae63f1f4bb839cdb33c839a312bb80d4a3df.nq.gz
    ├── 3c4a2a5f08eb1b0da12bc744fe73efa2bc54546e.nq.gz
    ├── 3c82e582d24c39ecca8af556082f121f3e3c329e.nq.gz
    ├── 3d9d40a7391cf107d0f3aa34118ce1768d09c768.nq.gz
    ├── 3dbc1ca591c0557e35b6004aeba250e6a70b56e3.nq.gz
    ├── 3e1de1e1ca431225d12452902edb7ad76a6c69c5.nq.gz
    ├── 3e3b564c27a8ed103ea8a2a30ba5d114b1188c1c.nq.gz
    ├── 3e3baebf8e5887a60911c2b8e3c421f769289dc9.nq.gz
    ├── 3e619ce482ccbafdda1f62cb70938828de6d8ac8.nq.gz
    ├── 3ed7d282c3a882940e1604bd3d84522f4eff009a.nq.gz
    ├── 3f2201ebfb476fd4934ca527de67636c32e43f0e.nq.gz
    ├── 3f94c3d0c04866a2b46552bb290eaf8953b1656d.nq.gz
    ├── 3fda158dd585f89bea29b01ac8b65443a0c3a2b4.nq.gz
    ├── 40086e383a834c9167bd3bd7e023f69b4399e05c.nq.gz
    ├── 40c38861efe55b55289a5901fa5fbd46a96b7e7b.nq.gz
    ├── 40e50bf6b80cf80b906f715def4341a53745d381.nq.gz
    ├── 41231145f9bda0abe221a06812f62bacbc3343de.nq.gz
    ├── 41a0ae700cc820da610792b6cb248b476d74f2ca.nq.gz
    ├── 41fb9772d463c6b003f4d7ef844fccc00cc679aa.nq.gz
    ├── 4260bf1401641852498fec87b65173dd83448d37.nq.gz
    ├── 42e320b0212deb5232000c9c2d5ec843de323528.nq.gz
    ├── 43083f312a5f3fda7348faeb25cbb5ca95b60eda.nq.gz
    ├── 437bf5aa425c8151093dfe8546699081ae378424.nq.gz
    ├── 4404a8b4c70d322f8bcf0a96c993d9f4600a04b0.nq.gz
    ├── 4570b2ef9f282e5e0f0db6e90f5eeb1034b8027c.nq.gz
    ├── 465f2c5d72c03848467ae24551f0e3f622476155.nq.gz
    ├── 4676fbfdb321b7d34fe3cb40d1fd33d7f6f3552e.nq.gz
    ├── 46b570e557393fae40ad248f0d018e46f0d1620b.nq.gz
    ├── 47c0378df7768423b0d665cacdec590b106be410.nq.gz
    ├── 47f64e32a8ad1674e2b8cac1735190f09e492cfd.nq.gz
    ├── 493f4395dc17309295d108015bd904db09536c51.nq.gz
    ├── 4b55fc1058ed0b9ea623c18c56e5bb4a147a30f9.nq.gz
    ├── 4c8384a4c9a8c7f8b2c57e414575508bf11dda7d.nq.gz
    ├── 4ca9e8e179b04883d733f8c949d59ca8b6980bed.nq.gz
    ├── 4f9ce1a1b9510ad4980ce1abd9505eda3d8737d0.nq.gz
    ├── 5039edf707c59cdb159aa4dd9362578129cc222f.nq.gz
    ├── 50b661aa141f811091271d8b1a1ee93b64c97a0a.nq.gz
    ├── 510b470d2808bbd82128217f8033cede9306d1bc.nq.gz
    ├── 5153ba6981f2bcb68814bcf77d349fc87e738470.nq.gz
    ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
    ├── 51d7d7a82e750fc04a2c71ddabd0b3e73ebcc31f.nq.gz
    ├── 52952eafdc03774d364cf730b374f7a2539f473d.nq.gz
    ├── 53a75135bd7643b8a572a3d8a3d4841632855c24.nq.gz
    ├── 53fcd8701938db7b3620ba2e26dda8299b34ac83.nq.gz
    └── 540069ac7444ad61a32e344682ab399abaca56ae.nq.gz

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

[netlify/cli](https://github.com/netlify/cli)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
