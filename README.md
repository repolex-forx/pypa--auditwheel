# Repolex Knowledge Graph of pypa/auditwheel

RDF knowledge graph data for [pypa/auditwheel](https://github.com/pypa/auditwheel), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/auditwheel
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 63a51b2f62936e38b6504faa60db5ca042559f97
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 63a51b2f62936e38b6504faa60db5ca042559f97
│           └── chunk-001.nq.gz
├── blob
│   ├── 00e28645826f343c63b0483bba12a9304c441435.nq.gz
│   ├── 038da92ac7ed7d8362238d84076d486cc891b279.nq.gz
│   ├── 03b2213bb9a36c589f8e5342bea47a7d63b28573.nq.gz
│   ├── 049956b1e95d194b840302439588e23a8e539307.nq.gz
│   ├── 04ea917f70dc15956ec1ee7598b67dd370513e81.nq.gz
│   ├── 062b856510dab137a0efcac0d0a8933d67846d42.nq.gz
│   ├── 0799f439da30ea6298e5683ec77e1c2b989b0b58.nq.gz
│   ├── 0818de54ad55b32e527bd4b82ca43dabd65a61cc.nq.gz
│   ├── 0911ebcadacce396150661a661d7e72e49ee2e5f.nq.gz
│   ├── 0a2e8d817affd4dbd3959e04ef8a609956d181ab.nq.gz
│   ├── 0a4ec8310d8d66f9cf5cf6764ae1f17d3d110d13.nq.gz
│   ├── 0ac07d4d4c00930794a7c7417ea5f5ff5a1cfcdb.nq.gz
│   ├── 0c7a88b9e13e55b8b3f9f8a9a0fe79c248b23678.nq.gz
│   ├── 0d1289fb7828d3dcf56748e372649f95a567503d.nq.gz
│   ├── 108b3248281243ebbd1905a236c684fa4988a55c.nq.gz
│   ├── 115be45bdfb5bf1a6c9dca87471c5ca0839f63b1.nq.gz
│   ├── 1165e04d95c2c8ec978cb3a856d5924e0dfb91ad.nq.gz
│   ├── 11845e416548f463a2044b8016405308c9dfd87d.nq.gz
│   ├── 13bcf514e157e2a0961a3cb54978899face07495.nq.gz
│   ├── 14ed4308153ac94de85f32d25b67d47cdefeb402.nq.gz
│   ├── 14fa9374102d329d54af24c0a101befa9d4cdde5.nq.gz
│   ├── 1560dac8411cc8b0b8ce91f4febda539b38424af.nq.gz
│   ├── 17fd5628637e24e9fde0240298503742a3497dda.nq.gz
│   ├── 190e7af1af4e1251f69089940e3162406204d53b.nq.gz
│   ├── 1ad4d0665e32bebdf0cc1627c9f5dd610b4f9b95.nq.gz
│   ├── 1b91d7147c56544b202d43e6b14b56c6fdf05deb.nq.gz
│   ├── 1dc4d7479f318350b29f2363c4ddb790cc9446f7.nq.gz
│   ├── 1dd7dffef532422e2e8795f6b19370e61c3a68e7.nq.gz
│   ├── 1fff29d2f6adb12945651e85afe71e6bf2f72c65.nq.gz
│   ├── 2746f31aad61d3b23ab25cacaf9c4428bd9052a1.nq.gz
│   ├── 27db268a0af4c9d02d2de856bb33abf6c0028641.nq.gz
│   ├── 2ab457b9553ed0bac7d374bcda60ad1816dc9484.nq.gz
│   ├── 2bb1ef605b6ff9db1c3e52766fe82dae28846584.nq.gz
│   ├── 2c27726119cd50788e23ef6c4e859509fd049080.nq.gz
│   ├── 2e4992a3b79994a3b622d0a2f56550c4ed3a3531.nq.gz
│   ├── 2f6b009b6da15b12166e694ecccd4bf57a664a44.nq.gz
│   ├── 304a494908c296eb41205ea6676a116471e95c49.nq.gz
│   ├── 316567965039ec5274cde02b71b02c069cde9cb3.nq.gz
│   ├── 31fb3caa5635bcb8eacb4285e7da9a04a1edc736.nq.gz
│   ├── 32731129b68d5b0205323841019601f511945625.nq.gz
│   ├── 32db9d0bd696b126f6c1183226dd54d0b7028a01.nq.gz
│   ├── 3313ccc102eb62b63865c01f1dfd61a987a496ad.nq.gz
│   ├── 349a8f7bea8082538efebe3093bcd58ea7c730a9.nq.gz
│   ├── 35fd25d85f44e6b966905f72d1ee23d7d1c30cb2.nq.gz
│   ├── 37e9426f18a4b1b4d5c6e9105068fc922efd0092.nq.gz
│   ├── 398d1297ee09549d841ec6a3265e9ca8cf85d7d7.nq.gz
│   ├── 3be5b9ea02a1fec6e7d05a88174a43a8f16ba197.nq.gz
│   ├── 425aec9ed22ca90f648b356a453b1b8e2b241f01.nq.gz
│   ├── 4453c14e90e7b6e0785553b2faf585eab34a93ed.nq.gz
│   ├── 499a036f191c8e53737c8f18501c9851d94913dd.nq.gz
│   ├── 49bcbf42a30a1123a05d8084ac8c2ef1a4c5a7d4.nq.gz
│   ├── 49ca14a8be4a750f404f997967c2bd671f2aa058.nq.gz
│   ├── 4dffe9fee58c1e445decb10a7b7f5c4d46ebf595.nq.gz
│   ├── 503efe0848d0015681a636aa10811ea715fdab56.nq.gz
│   ├── 510b2f0b5ede8151d1af3905b3107b3ca6e434a6.nq.gz
│   ├── 541b5f74d3065e3b29d81b52f1b1d4a65e082a9a.nq.gz
│   ├── 554e046795ab70a89aac606c7471c8fb72a9b143.nq.gz
│   ├── 56311bb192bde9f3cc57eb9a7705b70645c478c7.nq.gz
│   ├── 56496cd107103d474bfbe468a36303cb522222b2.nq.gz
│   ├── 588626bd669eea5ce00d594eab7297d3a217bf66.nq.gz
│   ├── 5c7406be28657082a104db07de9ed77a8b54463f.nq.gz
│   ├── 5ce2e62d1753489d5eabfdd3718ceb62e4c8e69b.nq.gz
│   ├── 638ebd958019513f87b794c4e95c7b1db7bb8245.nq.gz
│   ├── 639a06508bc9703bb587df1c8cee55bf2dc9c096.nq.gz
│   ├── 6417d44d582ca5ceff7da9cd5f233dd894c420f0.nq.gz
│   ├── 67fd77293436e5d49ca92f3c84d833f052a15334.nq.gz
│   ├── 68c5c212168ad1f46e0f9ea7839ac4ff6040dc38.nq.gz
│   ├── 6d8372e596dbbf49ae78c6edc7f052ec6f994cb9.nq.gz
│   ├── 745445f4000ae3a6b123f2f6bb53a4e39ed1643d.nq.gz
│   ├── 74719924605b8cca2e7217002a5fed1159af70aa.nq.gz
│   ├── 7555b45cce5cd3fd2c3aea4bbce4cf107f972f9a.nq.gz
│   ├── 76804e33473b9cf732f4df8a1326f9d326954669.nq.gz
│   ├── 76d42e1aea9bcc65319a28e783705c72fea7fa7d.nq.gz
│   ├── 787a3d94c8a80db9d0264adcd419c9e34232184c.nq.gz
│   ├── 789a2b00fac45ac620ab9ea3510ead9b57e73039.nq.gz
│   ├── 78c74d2320544ab88291a48b1a4eec112beb15f3.nq.gz
│   ├── 7919f6ddcd4a23f1ea07ad6aa2d95101f6011d19.nq.gz
│   ├── 7956e0e931d2c23f1eb6778af243c92df6d3a231.nq.gz
│   ├── 7b8c24105fc62da6b6980cdea47cb5c681e281ad.nq.gz
│   ├── 7c907faa548db09997422814436d0eac36e212af.nq.gz
│   ├── 7d11c3e5a1379cf0f8ed80c8dfec2a70d2c9a9b3.nq.gz
│   ├── 7ef62bd9e6ff48fccc5ed359892fb5656f2b2dd8.nq.gz
│   ├── 7f1b1319c4dfdb062f2f1b4fe9a6a01409d7ca7c.nq.gz
│   ├── 83c896a7a754d3cf4b2502e64e177137b83dc651.nq.gz
│   ├── 83f0ece8673c7dd3087a41a579027b145335dfde.nq.gz
│   ├── 841200d18f94c22bde0de0f23fdd3848e890f40f.nq.gz
│   ├── 85b0408bf2c7c13d5ab3593b9ff0867aae92d626.nq.gz
│   ├── 86555e61a3e01df2a71ed0a5ee57c22c9761c44b.nq.gz
│   ├── 88928768ac7667e2d4a7705a1d5d41b775c30e76.nq.gz
│   ├── 8edb9c58170808d60ed28b2276d30a5cd0d8847c.nq.gz
│   ├── 92da3c7d07181ee70025d5fec7af7ee9cbcdd528.nq.gz
│   ├── 9307927e8a0cfa286dca88ef8664c21c62ca5cd9.nq.gz
│   ├── 9371ec4e7b9d7df6b5fcf1a2ae6a0166dcac7e17.nq.gz
│   ├── 93a2a6e39a657d717a96ae1665626b48994c91df.nq.gz
│   ├── 9481993da4622c3ae6a121a32581d6d9f831fac4.nq.gz
│   ├── 9593d7d5465a76dc7ace5fff093571babbb1c7e9.nq.gz
│   ├── 98b2a75998a04ced1bcdbf49ef308ad60b98280c.nq.gz
│   ├── 99047eddb6ad22bfd9d67e14817404867229c0a1.nq.gz
│   ├── a1db18a0a9d9774eeac452e67eb69f2f888041c0.nq.gz
│   ├── a5504fe8a12fcc20fa6dfa1cbc23ff6aa217e342.nq.gz
│   ├── a55e5fb870203fb0fee75009685d1c5cb0d17020.nq.gz
│   ├── a5a40b9b4c270c19979c0059c610a1e590392a3a.nq.gz
│   ├── a8fc3f72fea960ccdd072479dadf5519b28a1bbf.nq.gz
│   ├── ab1a292c0aaec748067087c90ce5d567dd07600c.nq.gz
│   ├── ae1d60a93bcd3a123e5edaec24363c89499886e1.nq.gz
│   ├── aeb85623fed45bb9a4b5b46e84ca7f55f4a3a7a3.nq.gz
│   ├── af46a8e0648786b647990c4a882ca34ab3199bf1.nq.gz
│   ├── b0b3e2a038ccd80ea95a02834341d1be178b29c7.nq.gz
│   ├── b14b6098b34d81314c8a69786bd0bbe74816430e.nq.gz
│   ├── b2a6bf9de4f14c5a0c9a74f58346157b9c87217e.nq.gz
│   ├── b308ab0d9b470df80dddfc685fcf30fcf029991d.nq.gz
│   ├── b377e3a3226a2eb73c57fa55d86a08c2e7ab9e7f.nq.gz
│   ├── b55fc597882895db0294bb15c0262d6fa51ec079.nq.gz
│   ├── b799bc0ae395ad1ca98ef3afd90b7c5efb199669.nq.gz
│   ├── b7bac53f45a8684ea9aa25201cf0bbc8456e64ea.nq.gz
│   ├── b9ca254f90f8a9bd89bba88339bbbb15ccf4a8c6.nq.gz
│   ├── bbd03369e2437fabb5c35292dc6675acf4f4a453.nq.gz
│   ├── bc9ad9ad2bdfe351e824fe177724f63ead809c46.nq.gz
│   ├── c3441e6cc8443ced85b4f25f5171912926f6db6d.nq.gz
│   ├── c943a10e4b8a445f58800012d38c7514f1bf3f98.nq.gz
│   ├── cf1a07769721db861c770c2b6263896c85388ad7.nq.gz
│   ├── cf1db3d4fd6c993ef94a99c386568dd41c0e5427.nq.gz
│   ├── cf23e1a2e49bd845fe6eebe4e8ba7ba6bfdcec03.nq.gz
│   ├── cf42c9893f6c6d57f377b9470a0121b540ab8e66.nq.gz
│   ├── d1b58faca34ac0abf7ec07f40469656a857d8c06.nq.gz
│   ├── d2043918d592fe87b3e64d00efebcb345dda1f6c.nq.gz
│   ├── d756f9a7bcba9ab396481c20e42866d578810f9f.nq.gz
│   ├── da5acddc0a115e1958d3e9014c23ade13dab5977.nq.gz
│   ├── dc9aaf052d8be20270ae4e762c0766f4ebe2283e.nq.gz
│   ├── dce57278f6fd1ff435233bd72723ece5f9c4c45c.nq.gz
│   ├── e01b25e4898f8f134e1d69732ba36e7c37607d32.nq.gz
│   ├── e1491ba0a4ca7c14021d842fe413383a95b254d1.nq.gz
│   ├── e1dffcc32e666978bfcd03b76f8906bf0727574c.nq.gz
│   ├── e2e9d280514799b2eea85ccb2fa7dd5b458ed6a6.nq.gz
│   ├── e37abd812a834085511ccd02b2b7e04ac3bd4684.nq.gz
│   ├── e39daf90eb007489ec2ba82cb218d340467dc9b7.nq.gz
│   ├── e420e71214f829edb3ca9e07d9972af5e68dcfa2.nq.gz
│   ├── e50aa73255cc129a9ff1ce6d5727b21ffe189599.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e722263477b8a311093dc4ce994cd5b56ba36259.nq.gz
│   ├── e8b5fdf2917f903849729117c81394b332b60768.nq.gz
│   ├── eacbedfa66dbf3831f38be80a2a24c68304fb8e3.nq.gz
│   ├── ec65595c48a620edbe3e1a2b8825beddb5ca417f.nq.gz
│   ├── ee76ffdd590788c75a86f66101adb3893b0c58d1.nq.gz
│   ├── eeb8bc191dd5b8c60c485ef5edd33ec8f1656f47.nq.gz
│   ├── ef42ae4030d04abec2fa27b8752235c8c975b763.nq.gz
│   ├── f0d0647375b560fc391b071bd339e905a164edcf.nq.gz
│   ├── f38cbc35180347f3ab01a7ca19c470110677f8cf.nq.gz
│   ├── f5c9921b56bf4c80eef08d423ef58600a7ba8068.nq.gz
│   ├── fa3e3fe1fd48e061ecf6e923a209c17d90e97b3d.nq.gz
│   ├── fc78f06027c9e47ecbbbdfabf22829c2ded49ddd.nq.gz
│   ├── fd9283b9e3de2132854719ab728a5802666b907f.nq.gz
│   └── fed528d4a7a148fd0bf0b0198a6461f8c91b87e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 63a51b2f62936e38b6504faa60db5ca042559f97.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 161 files
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

[pypa/auditwheel](https://github.com/pypa/auditwheel)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
