# Repolex Knowledge Graph of huggingface/speech-to-speech

RDF knowledge graph data for [huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/speech-to-speech
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 327a8c190d4126f8f7e06287b1086078835a5a4a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 327a8c190d4126f8f7e06287b1086078835a5a4a
│           └── chunk-001.nq.gz
└── blob
    ├── 011fb2e5365abdf2377d1dc60d3b5d66f60e786b.nq.gz
    ├── 012eef2f31f3790c30e08ce7f6748bb0afd251ff.nq.gz
    ├── 017384a8756d0cbb02fa5fbd2a511c22890d2d91.nq.gz
    ├── 02391ad94e5ff87b7f2460be6e5ebec4647f4574.nq.gz
    ├── 02923e1a34e4357105c7fb8c9497020ccce22c69.nq.gz
    ├── 02cba30c048aefa1ae466c943ffc93ab9bccac72.nq.gz
    ├── 02fb45d5bf40095b996d4734616dec9c305684e8.nq.gz
    ├── 0327f70021cf0f2c4b20d1f19f873a7733d3a5d1.nq.gz
    ├── 0424f9481a451804f012dc618219416d607f42d9.nq.gz
    ├── 0449d6c592e21bab1d1e5ab2ca1f9339371db295.nq.gz
    ├── 050e1730acb2da4970251c41d1b6ae3cc592ce05.nq.gz
    ├── 052891ed72672298770ef49210dd1850a0b7b1cc.nq.gz
    ├── 054ec2d13ee4bdf8c9eb750c45c244bec96b908f.nq.gz
    ├── 054ec908c29c33b02166d5a5b2690e0ca9191e4b.nq.gz
    ├── 06b2f559459e8e6bb7bfa7507bbbfd668a7eecca.nq.gz
    ├── 082f60124d6dabee83d725055d264a373a4e4b39.nq.gz
    ├── 0a7607791f0cd8fbaabde0dd60776c729ebc8836.nq.gz
    ├── 0bf58e4bd86aff4387f79a1ffd363ad7de98f098.nq.gz
    ├── 0c9ced8582832a2b302aa6e01a247679ccbca267.nq.gz
    ├── 0cb7b980e1209c55b10c4b8bebab19ee924d3f5d.nq.gz
    ├── 0d38ea616c11d9c28ac0fe23e86bf33c456596ca.nq.gz
    ├── 0de26bb7aa5ebbb113b3dc7f5fb5caa183832dd0.nq.gz
    ├── 0ea26b04ad3701a1cb6609793b3ef7500614c15f.nq.gz
    ├── 0f93a3b90817fc050012c90a9d45d91e93a285df.nq.gz
    ├── 113b7eba2b5a3af6068071dfde921c1e9a56ba3e.nq.gz
    ├── 11694b953f94feaba0dd5be4508c4fd3a1e625d5.nq.gz
    ├── 12fc40eb321188c0968241621f511fa1cae38209.nq.gz
    ├── 13f45fbaf36df338801fbd9b6b71b26a619b51e1.nq.gz
    ├── 1580a760abbf01008e61272e0a6e950a0be400e3.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 1686baa968ae4694b8727dc3aed95e1dad738692.nq.gz
    ├── 16a3caa258bc9f6137e33e8d48f56061d7e6c7db.nq.gz
    ├── 1a1394154d39fe9ab5aa06218122f74ad775a82d.nq.gz
    ├── 1a8298a99450099394299b03fae156b7624eb15b.nq.gz
    ├── 1a9d50395bbb2b999e3bc136847a3013064ea3ef.nq.gz
    ├── 1b78d5a074e6ff3f13fa95602f5e044b197c3935.nq.gz
    ├── 1c9d27a30acd35521fa7a084a79cbcd2ca762578.nq.gz
    ├── 1d15dd909915b16d594e0dcb6dfa8c049fc0788e.nq.gz
    ├── 1e055e1bf490adb88b03f46c137598ebb128926b.nq.gz
    ├── 1fcca8a9fc00c707384ba939c87e420f53704bc3.nq.gz
    ├── 20d87bbeb1e3196234439d0380e64864398bc945.nq.gz
    ├── 2131ae3977f466a8b33d395b9fe676d67ef1eacf.nq.gz
    ├── 21b66e12423dc310f4e049a39460cf7d160ac7ec.nq.gz
    ├── 231301337ae474fcef133ed4f09640905925add4.nq.gz
    ├── 2356ddb2225fb9d593ebb655d8c058c207b09f2f.nq.gz
    ├── 242a9e930fa6f07d6688fc690f39839d52ecdc86.nq.gz
    ├── 256ecf2f8988661655ba928cd3771ee57526f560.nq.gz
    ├── 25c42b654013fedf1d3910e1ee2d4256b278ef73.nq.gz
    ├── 25d73bcf3b8ca1d41ae7f59c3ba63f9019a308b3.nq.gz
    ├── 2610928a06d3b92dad1beab4c209205826b68e50.nq.gz
    ├── 261beb792636cb03edfb6efbd00760a4964ccee3.nq.gz
    ├── 27becb6ab5ad6a3a6062375f899c4aeb2d8f3954.nq.gz
    ├── 27fe81826c27dfd7525a6cf15cb57b200a2a647a.nq.gz
    ├── 283045be3a06b4cec5d3472e83c546e5642bde4a.nq.gz
    ├── 295753099b3af51fdd51a88d8801b8cd90bc4d78.nq.gz
    ├── 2a78f0f902551ad9f6d59021c8c35d3c1ea8e9e6.nq.gz
    ├── 2aa25af4966a18155949cab2af91dc5210c15b34.nq.gz
    ├── 2cae514ca7493fa73f78b26411e9525d23ec1319.nq.gz
    ├── 2e6b26069ac1dfd45803d6e6d8ee5d970fc76b4a.nq.gz
    ├── 2e9c6e805bcdb7662e496cadb15d3604b502daaa.nq.gz
    ├── 2f028e293e2247a231dde19d0293cb1942376ff5.nq.gz
    ├── 2f8472b984f4fafbdc66ced1a36e010324dd9e5f.nq.gz
    ├── 306b1927098798d8f7cae4c479e98b130def7d5e.nq.gz
    ├── 3071b5cf0f8fcb6de98743c310a165ded392a5a1.nq.gz
    ├── 30e82c8cec2f477e4c3c1d700dccff44384f64a9.nq.gz
    ├── 31a68821e5f97863d5088296af766b105a7fed44.nq.gz
    ├── 31d4afd811c2f4c480c93649de2406545530159c.nq.gz
    ├── 327440441312bd5e9af8f1a0e73568af2c7ecdd7.nq.gz
    ├── 3319987845be12ee9449ae0e3dbd1a75774135b5.nq.gz
    ├── 3352faf9220bd696631aa680c05e7b53274aecce.nq.gz
    ├── 337fcc02dd8f1970b944edb6240572308257c3b3.nq.gz
    ├── 3399f2c2f212d62176bc96d25e6633191211e783.nq.gz
    ├── 34f6dc1229d5dc12ce1e2abaebb5f8f8dd986983.nq.gz
    ├── 3557f064fbea71ff7f4bec45711974f19f072031.nq.gz
    ├── 35a475dfd97c45756f0240ddb97eac35cbb38c0c.nq.gz
    ├── 35e4463dde0dc0fa7b087a8d9a0f43217b2accd7.nq.gz
    ├── 3670d1d719e58a7f28afb147be0f3149c39af65e.nq.gz
    ├── 367c41a4e0462cfd6761060fac9d2f2ac1f5af4c.nq.gz
    ├── 36a1dc89c2dcad2a3c3e760fccfdb14b6b3fff21.nq.gz
    ├── 38465b9ebe1f12c5c08e34cb817377a3ac82b1aa.nq.gz
    ├── 384f621934dbae2d1dc6129e6d97ab2862ad476c.nq.gz
    ├── 3bcc8c08fb93d43927d7892d8700a826d8bceec3.nq.gz
    ├── 3cf443a555a918c4292c5245a2d3ffe9c14e5244.nq.gz
    ├── 3e2c412a3beec01aa827237560733a00f933017c.nq.gz
    ├── 3f766ca549a7d8d1bee4d9988ed0167107f14122.nq.gz
    ├── 3fe6588301950e994ab980884fffaecaa7b07cce.nq.gz
    ├── 4068d7c862f33ca303db726fe9e25bed52488088.nq.gz
    ├── 43d57dd2c83b1eb7b0132af6cc04c2cf86bebaac.nq.gz
    ├── 44368d71f63dd38e8dcdbdf06b309f91de464395.nq.gz
    ├── 444232e83f2c32f4d7e4f860badb1b2fbcdda34d.nq.gz
    ├── 44f9b7c3092e093a0cd56f0c21999f48e26c2a66.nq.gz
    ├── 45cd896c13bc6202081d60abf454e26309317838.nq.gz
    ├── 464d79bab919186b550a6d071c9274e41e0d6d7e.nq.gz
    ├── 475374687155c66db5c44325db3a1155ce74fd09.nq.gz
    ├── 482c4ee63fafee421c6f867935ba6f8b0859ce72.nq.gz
    ├── 48999a3db93e53341e398c38ce60775614e7972c.nq.gz
    ├── 48e01a3d4e68aced021fb4f2ccd5883b00ef70d9.nq.gz
    ├── 4e1ad03a2a7e0006efcf919a2beff4b96a84d4e1.nq.gz
    ├── 4ebba270974c88ed6a54707413c17fbb4e1c24ca.nq.gz
    ├── 4ee4b85aea80eba64f6d859bdd12b721d8116605.nq.gz
    ├── 4fd25787334d83bed1dbc2788042a36c228d3a47.nq.gz
    ├── 50a6a3eef8515efcb21b3ad0b177965c16e37963.nq.gz
    ├── 50b52d28021c22da8df96682f7e9b933a2caae9e.nq.gz
    ├── 518984e79652cd967591ef09a60d7840ad034c20.nq.gz
    ├── 51c6ca09b8daf2bd89cd31e45bbe5499775c24b6.nq.gz
    ├── 51df5d052080c93200561a122f0e75a62e23e5fd.nq.gz
    ├── 5294ebe00ad067d5aa9261e162fa7dc76e30125b.nq.gz
    ├── 52c35582841d7a62bededcaa2a80059e71361175.nq.gz
    ├── 53116d68d8cf4ba61b5b8eb263289531da7ff165.nq.gz
    ├── 53ff0fc3f816efbc009ecbc7f7c6c634a19c3d3e.nq.gz
    ├── 5413e608cb57f17ba6d316ded87fbeaa37da06b2.nq.gz
    ├── 55f03dae029f0a0a1bbc2e1e86907132f5195b0e.nq.gz
    ├── 563c8392012295ab72394640b0cce70e14be186a.nq.gz
    ├── 56ae58cee4408450f138c9e4934f824083435060.nq.gz
    ├── 56c8519e7be4998ee67cc67eff4f8f193ad7c674.nq.gz
    ├── 56ce45f305b588274e0de35c53fb32baf7d37b6a.nq.gz
    ├── 56d84746902b5f6c5e8ecb4aa3ee1119e0c09316.nq.gz
    ├── 5727cce46e7db5df688cf7c910652c96124771a4.nq.gz
    ├── 583b3243687fe9b400546078c834b76e846bc463.nq.gz
    ├── 584082ddaa00b48721322d65cda0ccb21693c373.nq.gz
    ├── 585f5aca8e65899a70d37bff75a405be13875d46.nq.gz
    ├── 59a14b494d82496b63c3f552a6a061ed567ae349.nq.gz
    ├── 59e1c4543274ead18a11b89fc162317fbe701207.nq.gz
    ├── 5a68e53d9cf0501c8dc3d43ba98f4ed21397b642.nq.gz
    ├── 5a8895c6a3ac6d6a0b7235fb659b56fde800ea8d.nq.gz
    ├── 5bf71ab17c7e93d04740af71c1677d1cb2af973b.nq.gz
    ├── 5c29c6d5d91d5c797547426ab00702006cea282b.nq.gz
    ├── 5c31c600d25a7e9b6420fa8c9e2a1361654e2cc4.nq.gz
    ├── 5d0c25baee988544d135a474baad8c1f10f2af30.nq.gz
    ├── 5dba856d3c28e83602cc67012a75ecc934dbc40a.nq.gz
    ├── 5def69823faa8f24c3c40c477733337efead9b99.nq.gz
    ├── 5e0ba7c574a3bebf580808c8e6d4d8b935affb4a.nq.gz
    ├── 5eb1be9968dd92b9cdb36554a680ff0e512cd6a8.nq.gz
    ├── 5ef6c0ab23bb6253eb77097e4b22d4bfe9fe6d88.nq.gz
    ├── 5fbe66e60511f6f40c64431c4f6194e47d1dd5c5.nq.gz
    ├── 5fd3bd17e6fa0b79cbf62d0fafd75dab63a1a5d9.nq.gz
    ├── 5fd5001b1c622ee6380c7c3cce41348c6ea8c82d.nq.gz
    ├── 6010de8815a3a79f4f1a3a20056cb60e946c670c.nq.gz
    ├── 61605bb7e99e4507ffbc401d383089153d76e8f9.nq.gz
    ├── 61e197f210fba16b6fdbb2a326e57e79b7adfa1d.nq.gz
    ├── 6276f673766fca33be889d9cb17ea02dfeeb132f.nq.gz
    ├── 628835bfa7b922ee023eb9997f220757dde8abba.nq.gz
    ├── 62c940af062d7c885d43d70b8509277136158e9e.nq.gz
    ├── 631a9cba26caace53824220905092d524299a171.nq.gz
    ├── 671313312e3162bbba1ee478afcd6097050e0ad6.nq.gz
    ├── 67abad39f1020895d054414f65f440704eb669fb.nq.gz
    ├── 6940ffd0fab0f9b151939667cd5f0689117d6401.nq.gz
    ├── 69450648d44f75d8cb261ab1e26f238953e41d8f.nq.gz
    ├── 69f7c0766624829b6970b88ac67f8293e840ee22.nq.gz
    ├── 6ac5d10d7ae78eca51285f32995c4702f74aafa7.nq.gz
    ├── 6c5947b7c76ac709a884e02824df191a2c14e47f.nq.gz
    ├── 6cbc1db78968977e7ae88bbf7734312d7adf68f6.nq.gz
    ├── 6cfd079d54fc18befb2e74dfa9f9dcd020fdb40c.nq.gz
    ├── 6dc0a937247e1b46e869ccfcb8439051cd64ec10.nq.gz
    ├── 6e0fa3bc8f0db3007c8853f0ee9c4edf75badb19.nq.gz
    ├── 6e43c119d88876a739a2bfc7e9b559142fc5c269.nq.gz
    ├── 6e8ebca9631b6330957a5618ef880307b36469a8.nq.gz
    ├── 6fe163ce6bd6ac569a970230f9ec5267e9261f11.nq.gz
    ├── 7018de75ce8c961401abaae6ed035ed58ecce298.nq.gz
    ├── 707aa6fc4f42c2e7c92005e3f9d000a7f2a98a68.nq.gz
    ├── 7104b499121482588250f493a1462517e03e2bab.nq.gz
    ├── 71108fb67466c7046160507752eaeef6bee33e32.nq.gz
    ├── 714914a37884bf4dff8735dfd7fcfb5a6fe8171a.nq.gz
    ├── 7247d5d5451aab47d5a42daf08537a3b7565ecae.nq.gz
    ├── 7262792b18226aceac37f1fb2792fc55bd960a8a.nq.gz
    ├── 72eaf5609c67644fbdfe9237503562be6bbfa7b5.nq.gz
    ├── 72ff176b061f974c919e559ba58af0de05d61fdb.nq.gz
    ├── 734f26f535b6e81e8ad3f6d1a37d30586413ea4d.nq.gz
    ├── 73579eee002a13c54c0d48d59a4ee8883583ff85.nq.gz
    ├── 73724454556ca465cfa3508d9b157628cd61a39a.nq.gz
    ├── 73db82f4dfc1b6bfd3579161e9e06d6e19881caf.nq.gz
    ├── 740a50649486e3681ac7864200173a5a70a6cc2b.nq.gz
    ├── 741047bd5319e94c7777c224c5b5417dc3608ced.nq.gz
    ├── 74632f85bba18ab991e2bf5c5ab742463bcb5c81.nq.gz
    ├── 74ecbd8bc8696ef63517296bae37eb98e7aec4d8.nq.gz
    ├── 7694f9639bc34eb7e220e1223498dcd89aa39d2b.nq.gz
    ├── 779c07b2b9ff7cea9843cddb21522ce94f316f0e.nq.gz
    ├── 77e29caa32c47dc73917e852706ea7884881fbcc.nq.gz
    ├── 7877cf60bd95f23b2704e40831a63351c6937f8e.nq.gz
    ├── 791678f4ded289f976ab6b94056b7feb9329de9f.nq.gz
    ├── 7979299d424a05d56284e6bf39db737ecbc85f34.nq.gz
    ├── 7999fc1b54fb1e07a0d92e8113a884309bec0f3b.nq.gz
    ├── 7abebd8e866aa69af8f3dd1dedc2c44a5d67d596.nq.gz
    ├── 7aea2a6f8e0b250b3a7377721730e0a21cefbed2.nq.gz
    ├── 7b4732080392db635ac39b89a32c625c31f547dc.nq.gz
    ├── 7e9227f7846fb9c695a33cd935ed7632f17629c4.nq.gz
    ├── 7f122d167a8046d46d2f5ac4844fea165b0655f1.nq.gz
    ├── 7fb298aa7e018fe31dfbbb59d7f84f43ba7cbdce.nq.gz
    ├── 7fc530b8d4cdf584e2d7bf3dbde60f82872febea.nq.gz
    ├── 8013a71174c395ad09c15533a39368b9364d345e.nq.gz
    ├── 806a58b9252492d43a1d0cf55ea4c0157bc556d6.nq.gz
    ├── 806e16cfde9070b44c9383ac0555adfc23cb0252.nq.gz
    ├── 8074b12049d981555233fb347c3799b4b489d26b.nq.gz
    ├── 8108dbc480aa9d2ae50695c1ac64e5093850ff99.nq.gz
    ├── 828c130a967110d462cde239c77e765722322fd0.nq.gz
    ├── 8599b90efbc24d7ecb18747ff3d57cf50cd4c75a.nq.gz
    ├── 865df8c78b977710385a9bece5c2ec4b404a5204.nq.gz
    └── 86b48fa2c926e256559e2f5c9dc3bfe9323731b4.nq.gz

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

[huggingface/speech-to-speech](https://github.com/huggingface/speech-to-speech)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
