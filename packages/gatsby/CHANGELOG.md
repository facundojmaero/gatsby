# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.13.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.13.0-next.0...gatsby@3.13.0-next.1) (2021-08-19)

### Bug Fixes

- **gatsby:** Hashes and anchors in redirects also work in production ([#32850](https://github.com/gatsbyjs/gatsby/issues/32850)) ([0654800](https://github.com/gatsbyjs/gatsby/commit/0654800d550b6dfaa41d9598842887eb15167ec7))
- **gatsby:** Remove `removeDimensions` from svgo config ([#32834](https://github.com/gatsbyjs/gatsby/issues/32834)) ([09679a1](https://github.com/gatsbyjs/gatsby/commit/09679a1d1a6cd745591304d069b0266a4b8f5bbf))

### Features

- **gatsby:** Add `defer` to createPage ([#32783](https://github.com/gatsbyjs/gatsby/issues/32783)) ([58d5a2c](https://github.com/gatsbyjs/gatsby/commit/58d5a2c6955f1263dd5f2b28369a9c177485d36a))
- **gatsby:** Opt in 20% of users to webpack dev server caching ([#32829](https://github.com/gatsbyjs/gatsby/issues/32829)) ([51b8420](https://github.com/gatsbyjs/gatsby/commit/51b8420dd45c42aab1e8da490548eabeaeed67a1))

# [3.13.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.12.0-next.3...gatsby@3.13.0-next.0) (2021-08-12)

### Bug Fixes

- **gatsby:** reduce parse cost writing page-data ([#32763](https://github.com/gatsbyjs/gatsby/issues/32763)) ([b97782f](https://github.com/gatsbyjs/gatsby/commit/b97782f35c92a2c51fdd5c997a0ac3fe45cf2524))
- **gatsby:** Wrap performance mark in check ([#32778](https://github.com/gatsbyjs/gatsby/issues/32778)) ([365d00b](https://github.com/gatsbyjs/gatsby/commit/365d00b2ee413ef38f56ba4262304865ecd4256e))

### Features

- **gatsby:** measure how long GraphQL takes to run in createPages and warn if > 10s ([#32751](https://github.com/gatsbyjs/gatsby/issues/32751)) ([8bd7cf0](https://github.com/gatsbyjs/gatsby/commit/8bd7cf06a0f0bea14c376b8c0daca8856baf6db6))

# [3.12.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.12.0-next.2...gatsby@3.12.0-next.3) (2021-08-09)

### Bug Fixes

- **gatsby:** fix incorrect filtering with experimental LMDB indexes ([#32728](https://github.com/gatsbyjs/gatsby/issues/32728)) ([9b456cd](https://github.com/gatsbyjs/gatsby/commit/9b456cd1d9fdf8096d12fd367e679d815e08b6cf))
- **gatsby:** fix node manifest processing in inc builds ([#32538](https://github.com/gatsbyjs/gatsby/issues/32538)) ([1577f9b](https://github.com/gatsbyjs/gatsby/commit/1577f9b0ab9909cdc4dfe0acca2dbbae89418ad5))
- **gatsby:** Silence process.send Error ([#32744](https://github.com/gatsbyjs/gatsby/issues/32744)) ([5d7831d](https://github.com/gatsbyjs/gatsby/commit/5d7831d949b3352b7bb39718072b75102707ad99))
- **gatsby:** Worker support in fast-refresh-module ([#32432](https://github.com/gatsbyjs/gatsby/issues/32432)) ([6daead6](https://github.com/gatsbyjs/gatsby/commit/6daead63ce02c21690a48cdd531fdb2761628703))

### Features

- **gatsby:** add env flag to disable lazy function compilation in develop ([#32707](https://github.com/gatsbyjs/gatsby/issues/32707)) ([ed04979](https://github.com/gatsbyjs/gatsby/commit/ed04979ed66219ed9f5f07a5b859f07217d32393))
- **gatsby:** write node manifests to public dir instead of .cache ([#32547](https://github.com/gatsbyjs/gatsby/issues/32547)) ([9c41b7a](https://github.com/gatsbyjs/gatsby/commit/9c41b7a90e97d971049dd9b5d296a37ca8912fa8))

# [3.12.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.12.0-next.1...gatsby@3.12.0-next.2) (2021-08-05)

**Note:** Version bump only for package gatsby

# [3.12.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.12.0-next.0...gatsby@3.12.0-next.1) (2021-08-05)

### Bug Fixes

- **deps:** update dependency chalk to ^4.1.2 ([#32576](https://github.com/gatsbyjs/gatsby/issues/32576)) ([5c4e109](https://github.com/gatsbyjs/gatsby/commit/5c4e109313cd1b59f814332fdb4dfdcaf1faed1a))
- **deps:** update dependency eslint to ^7.32.0 ([#32628](https://github.com/gatsbyjs/gatsby/issues/32628)) ([65fe945](https://github.com/gatsbyjs/gatsby/commit/65fe94547e0892b3978a7c7376ff1297acb0144f))
- **deps:** update dependency eslint-plugin-flowtype to ^5.8.2 ([#32629](https://github.com/gatsbyjs/gatsby/issues/32629)) ([4391f05](https://github.com/gatsbyjs/gatsby/commit/4391f05bcae65c36820c3407f09df668dacc692e))
- **deps:** update dependency eslint-plugin-import to ^2.23.4 ([#32581](https://github.com/gatsbyjs/gatsby/issues/32581)) ([769e98f](https://github.com/gatsbyjs/gatsby/commit/769e98f3dbcdbededfa1909d86aad83050a291c7))
- **deps:** update dependency eslint-plugin-react to ^7.24.0 ([#32582](https://github.com/gatsbyjs/gatsby/issues/32582)) ([de676bc](https://github.com/gatsbyjs/gatsby/commit/de676bc45d4196c78bf88e91346625ef80e93545))
- **deps:** update dependency eslint-webpack-plugin to ^2.5.4 ([#32583](https://github.com/gatsbyjs/gatsby/issues/32583)) ([170e58b](https://github.com/gatsbyjs/gatsby/commit/170e58b1ea30e3ee9927e9ef61be9c0c629b9534))
- **deps:** update dependency mini-css-extract-plugin to v1.6.2 ([#32586](https://github.com/gatsbyjs/gatsby/issues/32586)) ([6c6d4e5](https://github.com/gatsbyjs/gatsby/commit/6c6d4e501764614ad737c88ba5810b6fbbcbff68))
- **docs:** clarify redirectInBrowser option ([#32669](https://github.com/gatsbyjs/gatsby/issues/32669)) ([774e680](https://github.com/gatsbyjs/gatsby/commit/774e680e186f3ac0928a7b178d395d64b7d8a4e9))
- **gatsby:** load page and static queries texts in PQR only once per worker ([#32545](https://github.com/gatsbyjs/gatsby/issues/32545)) ([bbec42b](https://github.com/gatsbyjs/gatsby/commit/bbec42bd599dfbed4c7a4728f50b3c9fba5f903c))

### Features

- **gatsby:** allow sites to disable the dev 404 page ([#32686](https://github.com/gatsbyjs/gatsby/issues/32686)) ([af5525e](https://github.com/gatsbyjs/gatsby/commit/af5525e59cbc8052ccac1c646ef12a0c5d9843bf))

# [3.12.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.6...gatsby@3.12.0-next.0) (2021-07-29)

### Bug Fixes

- **gatsby:** correct results for multiple range filters with indexes ([#32406](https://github.com/gatsbyjs/gatsby/issues/32406)) ([9b42793](https://github.com/gatsbyjs/gatsby/commit/9b427936752ec0b107b36331f444366987355fbb))

# [3.11.0-next.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.5...gatsby@3.11.0-next.6) (2021-07-27)

### Bug Fixes

- **gatsby:** PQR - Wait for Jobs to be Completed before restarting ([#32520](https://github.com/gatsbyjs/gatsby/issues/32520)) ([50a3eec](https://github.com/gatsbyjs/gatsby/commit/50a3eecc96f744498b1f6be03f0ba11e85326f39))

# [3.11.0-next.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.4...gatsby@3.11.0-next.5) (2021-07-26)

### Bug Fixes

- **gatsby:** correct pagination logic ([#32496](https://github.com/gatsbyjs/gatsby/issues/32496)) ([2dbe647](https://github.com/gatsbyjs/gatsby/commit/2dbe6477d88bf6e0138f247dc9dda1bd67a2a613)), closes [#32319](https://github.com/gatsbyjs/gatsby/issues/32319)

# [3.11.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.3...gatsby@3.11.0-next.4) (2021-07-23)

### Bug Fixes

- **gatsby:** merge data deps state instead of replaying actions ([#32440](https://github.com/gatsbyjs/gatsby/issues/32440)) ([fd1d8cc](https://github.com/gatsbyjs/gatsby/commit/fd1d8ccc8dd27c316d24f91475a24702d228910c))

# [3.11.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.2...gatsby@3.11.0-next.3) (2021-07-23)

### Bug Fixes

- **gatsby:** Configurable PQR chunksize by env var ([#32487](https://github.com/gatsbyjs/gatsby/issues/32487)) ([33f9855](https://github.com/gatsbyjs/gatsby/commit/33f98555ba00d244a7f5deb6dffe2b9c4a41599f))

# [3.11.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.1...gatsby@3.11.0-next.2) (2021-07-22)

### Bug Fixes

- **gatsby:** Add encoding option to GatsbyCacheLmdb ([#32466](https://github.com/gatsbyjs/gatsby/issues/32466)) ([f4a6525](https://github.com/gatsbyjs/gatsby/commit/f4a65256ba4d322fe8db1981797ecde858ef05bc))
- expose ".del" function on lmdb cache ([#32459](https://github.com/gatsbyjs/gatsby/issues/32459)) ([e1a1396](https://github.com/gatsbyjs/gatsby/commit/e1a1396e1582a18047e2cefaeff0f57d61c0c83a))

### Features

- store partial page-data results in lmdb ([#32431](https://github.com/gatsbyjs/gatsby/issues/32431)) ([7601014](https://github.com/gatsbyjs/gatsby/commit/76010147a007bb4b643f363a25cca8ac38c53cdf))
- **gatsby:** display message about unfit flags found in config ([#32394](https://github.com/gatsbyjs/gatsby/issues/32394)) ([7df39aa](https://github.com/gatsbyjs/gatsby/commit/7df39aa18809103cfabd403bb23a5b14b31028d7))
- **gatsby:** PQR: merge data dependencies from workers to the main process ([#32305](https://github.com/gatsbyjs/gatsby/issues/32305)) ([bdb9352](https://github.com/gatsbyjs/gatsby/commit/bdb9352bed68e384970c8bf152643304bc228dcf))

# [3.11.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.11.0-next.0...gatsby@3.11.0-next.1) (2021-07-19)

### Bug Fixes

- **gatsby:** Add `directory` to GatsbyCacheLmdb ([#32391](https://github.com/gatsbyjs/gatsby/issues/32391)) ([7480849](https://github.com/gatsbyjs/gatsby/commit/7480849844884d6ee9f7ce5108f8ca0fe4dc4d15))
- **gatsby:** catch error from this.process.send ([#32356](https://github.com/gatsbyjs/gatsby/issues/32356)) ([99936a8](https://github.com/gatsbyjs/gatsby/commit/99936a8cb24a0bafe4794e6ceffc864e6e103bc7))
- **gatsby:** correct hasNextPage pagination info when resultOffset is provided ([#32319](https://github.com/gatsbyjs/gatsby/issues/32319)) ([9f8a580](https://github.com/gatsbyjs/gatsby/commit/9f8a580287ec3a4bf9696237e7e8ac49e2fc001c))
- **gatsby:** handle errors thrown when importing html renderer ([#32417](https://github.com/gatsbyjs/gatsby/issues/32417)) ([b6f1272](https://github.com/gatsbyjs/gatsby/commit/b6f127248aa6126d6a186bd4ee1a49a98c9a239e))
- **gatsby,gatsby-plugin-image:** fix createRoot on React 18 ([#32378](https://github.com/gatsbyjs/gatsby/issues/32378)) ([79b7b04](https://github.com/gatsbyjs/gatsby/commit/79b7b0407ddc6b53c2e86b0cdd16866283a928d2))

# [3.11.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.7...gatsby@3.11.0-next.0) (2021-07-15)

### Features

- **gatsby:** Add cache-lmdb implementation ([#32373](https://github.com/gatsbyjs/gatsby/issues/32373)) ([7897834](https://github.com/gatsbyjs/gatsby/commit/789783410878d562f1499c1915155135ac258d82))
- **gatsby:** Add webpack fs caching for development flag ([#32264](https://github.com/gatsbyjs/gatsby/issues/32264)) ([4f9a724](https://github.com/gatsbyjs/gatsby/commit/4f9a724b91ce35b0232952023eaecb8db448719d))

# [3.10.0-next.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.6...gatsby@3.10.0-next.7) (2021-07-14)

### Bug Fixes

- **gatsby:** Hide page/static queries activities for PQR ([#32361](https://github.com/gatsbyjs/gatsby/issues/32361)) ([d65de41](https://github.com/gatsbyjs/gatsby/commit/d65de413b8d0ad5720c46652936b44dda3f872c9))
- **gatsby:** shut down worker pool after html generation ([#32366](https://github.com/gatsbyjs/gatsby/issues/32366)) ([8cba0b9](https://github.com/gatsbyjs/gatsby/commit/8cba0b915cd0bd987675c4ed1839bbdaf39ae217))

### Features

- **gatsby:** restart worker pool after query running in workers ([#32365](https://github.com/gatsbyjs/gatsby/issues/32365)) ([b9236e1](https://github.com/gatsbyjs/gatsby/commit/b9236e16aac8c889c526571738c716cfb520043d))

# [3.10.0-next.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.5...gatsby@3.10.0-next.6) (2021-07-14)

### Bug Fixes

- **gatsby:** freeze the schema in workers ([#32352](https://github.com/gatsbyjs/gatsby/issues/32352)) ([8c9afc6](https://github.com/gatsbyjs/gatsby/commit/8c9afc648bda3770a06a6d5d440b15149c112bf1))
- **gatsby:** Use shared gql runner in PQR workers ([#32355](https://github.com/gatsbyjs/gatsby/issues/32355)) ([f75c833](https://github.com/gatsbyjs/gatsby/commit/f75c8332aad031990e6ad0d68146b13782343b3b))

### Features

- **gatsby:** Track persistence time of save-state ([#32192](https://github.com/gatsbyjs/gatsby/issues/32192)) ([eef99cc](https://github.com/gatsbyjs/gatsby/commit/eef99cce69c537025882f352a14f32e8065c380e))

# [3.10.0-next.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.4...gatsby@3.10.0-next.5) (2021-07-13)

### Bug Fixes

- **gatsby:** Pass search/hash to location after swUpdated ([#32323](https://github.com/gatsbyjs/gatsby/issues/32323)) ([636df42](https://github.com/gatsbyjs/gatsby/commit/636df42c8cc73c234c979aadfcd0265eb3a08174))

### Features

- **gatsby:** add page data for failed page to logs ([#32301](https://github.com/gatsbyjs/gatsby/issues/32301)) ([ce0ae00](https://github.com/gatsbyjs/gatsby/commit/ce0ae00754b55d34d6b03981a3e689fb638d3a13))
- **gatsby:** Redirect passes search & hash parameter to final URL ([#32334](https://github.com/gatsbyjs/gatsby/issues/32334)) ([46cbfec](https://github.com/gatsbyjs/gatsby/commit/46cbfecee7b864f725587cbba1c4421e386ef572))

# [3.10.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.3...gatsby@3.10.0-next.4) (2021-07-09)

### Bug Fixes

- **gatsby:** delay 'unstable_onPluginInit' lifecycle to after cache is initialized ([#32307](https://github.com/gatsbyjs/gatsby/issues/32307)) ([b348b7c](https://github.com/gatsbyjs/gatsby/commit/b348b7cb830be148af7d5bb9921d8e5bee3d498f))
- **gatsby:** Delete `.cache/worker` before each run ([#32304](https://github.com/gatsbyjs/gatsby/issues/32304)) ([8c9eb29](https://github.com/gatsbyjs/gatsby/commit/8c9eb292bdbb95f6bd2c60a1cc1526249366ebbe))

### Features

- **gatsby:** experimental secondary indexes in lmdb ([#32261](https://github.com/gatsbyjs/gatsby/issues/32261)) ([54ed0c3](https://github.com/gatsbyjs/gatsby/commit/54ed0c301631450720e341a33ebc7ffce99e5528))
- **pqr:** handle structured logs ([#32289](https://github.com/gatsbyjs/gatsby/issues/32289)) ([a4ab474](https://github.com/gatsbyjs/gatsby/commit/a4ab4749fb085fb1b3cfcc5927100c0487bb6b1e))

# [3.10.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.2...gatsby@3.10.0-next.3) (2021-07-08)

### Bug Fixes

- **deps:** update dependency chalk to ^4.1.1 ([#32250](https://github.com/gatsbyjs/gatsby/issues/32250)) ([bd03035](https://github.com/gatsbyjs/gatsby/commit/bd03035b35d4e2f69e86b9ff3bbcfb8bd3eece4a))
- **deps:** update dependency execa to v5 ([#32232](https://github.com/gatsbyjs/gatsby/issues/32232)) ([8a13969](https://github.com/gatsbyjs/gatsby/commit/8a1396995c02d45f00f241e22c626a20086fa955))
- **deps:** update typescript ([#31152](https://github.com/gatsbyjs/gatsby/issues/31152)) ([124cfcc](https://github.com/gatsbyjs/gatsby/commit/124cfcc4cd42a50a992dde5b420610f290227a78))
- don't import from other package src (even just types) ([#32234](https://github.com/gatsbyjs/gatsby/issues/32234)) ([51af0b9](https://github.com/gatsbyjs/gatsby/commit/51af0b9bc6ae1ff374bb59ea0b5b6ec6270b38ee))

### Features

- **gatsby:** Add PQR to bootstrap ([#32187](https://github.com/gatsbyjs/gatsby/issues/32187)) ([d58de3b](https://github.com/gatsbyjs/gatsby/commit/d58de3b53fb4a2d4deb1c4a0b014cb4d6f508a85))
- **gatsby:** forward jobs to main process from workers ([#32162](https://github.com/gatsbyjs/gatsby/issues/32162)) ([ef7eb19](https://github.com/gatsbyjs/gatsby/commit/ef7eb1952c30db2ad6c984bc23d639bd84e79bce))
- **gatsby:** PQR worker saves queries state to disk ([#32281](https://github.com/gatsbyjs/gatsby/issues/32281)) ([2268d5a](https://github.com/gatsbyjs/gatsby/commit/2268d5ad273f47d031ff85c66f96899f4c42dda4))

# [3.10.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.1...gatsby@3.10.0-next.2) (2021-07-05)

### Features

- **gatsby:** enable async rendering with react 18 ([#32188](https://github.com/gatsbyjs/gatsby/issues/32188)) ([32e9b4a](https://github.com/gatsbyjs/gatsby/commit/32e9b4ab7d8a0fdac067a7130820a0766e4da74f))
- **gatsby:** enable replaceRenderer to be async ([#32182](https://github.com/gatsbyjs/gatsby/issues/32182)) ([d68148d](https://github.com/gatsbyjs/gatsby/commit/d68148d2c37f72f5561d9b730654c44ec3b137f8))
- **gatsby:** swap createRoot to new hydrateRoot ([#32181](https://github.com/gatsbyjs/gatsby/issues/32181)) ([0d78669](https://github.com/gatsbyjs/gatsby/commit/0d786693d99e1f0a035ab5b985082ad8a4242baa))

# [3.10.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.10.0-next.0...gatsby@3.10.0-next.1) (2021-07-02)

### Bug Fixes

- **gatsby:** add fallback for resolveType ([#32195](https://github.com/gatsbyjs/gatsby/issues/32195)) ([dfef2fb](https://github.com/gatsbyjs/gatsby/commit/dfef2fbeb49b8ad5a7a7a178f28d9b1ce358d757))

# [3.10.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.9.0-next.1...gatsby@3.10.0-next.0) (2021-07-01)

### Bug Fixes

- **gatsby:** update async requires in dev loader ([#32189](https://github.com/gatsbyjs/gatsby/issues/32189)) ([f4c5c48](https://github.com/gatsbyjs/gatsby/commit/f4c5c482ba5da626d4f7e2d592fdc4d43eb817ba))

### Features

- worker pool that can execute tasks on all workers ([#32120](https://github.com/gatsbyjs/gatsby/issues/32120)) ([a82f6db](https://github.com/gatsbyjs/gatsby/commit/a82f6dbe354f2e82a5d944727622ddb0bb44e05d))
- **gatsby:** Add activity for writing out page-data.json files to the public directory ([#31987](https://github.com/gatsbyjs/gatsby/issues/31987)) ([0be1025](https://github.com/gatsbyjs/gatsby/commit/0be10250a7c461efdc4e7a6b6bf261e245954d53))
- **gatsby:** Prevent generation of polyfill bundle if not needed ([#31993](https://github.com/gatsbyjs/gatsby/issues/31993)) ([7d41a98](https://github.com/gatsbyjs/gatsby/commit/7d41a985669438e3504987968ed326eb2fd42bca))

# [3.9.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.9.0-next.0...gatsby@3.9.0-next.1) (2021-06-28)

### Bug Fixes

- **gatsby:** correct args type in createParentChildLink ([#32139](https://github.com/gatsbyjs/gatsby/issues/32139)) ([31828e4](https://github.com/gatsbyjs/gatsby/commit/31828e48fe1e5cd8fb2246440e3edb7d0a4ec779))
- **gatsby:** leave `xmlns` element when optimizing SVGs ([#32123](https://github.com/gatsbyjs/gatsby/issues/32123)) ([27c01fc](https://github.com/gatsbyjs/gatsby/commit/27c01fcdb6a923986cf390a2bb5ac61b340a2865))

### Features

- add unstable_onPluginInit that would execute once in all processes ([#31901](https://github.com/gatsbyjs/gatsby/issues/31901)) ([2bf8c0d](https://github.com/gatsbyjs/gatsby/commit/2bf8c0d37fd6de3fbbbe7e543275cfd6d64ec9de))
- **gatsby:** enable webpack caching for all ([#32018](https://github.com/gatsbyjs/gatsby/issues/32018)) ([174d3f1](https://github.com/gatsbyjs/gatsby/commit/174d3f1496949a8751bd052ef365f901bbdde23b))
- **gatsby:** PQR worker can create schema ([#31919](https://github.com/gatsbyjs/gatsby/issues/31919)) ([308eb94](https://github.com/gatsbyjs/gatsby/commit/308eb942f3264fd0c1579b553cc74d81f9219fff))
- **gatsby:** PQR worker can run page queries ([#32017](https://github.com/gatsbyjs/gatsby/issues/32017)) ([44257b6](https://github.com/gatsbyjs/gatsby/commit/44257b636fe0cc4d4294673f9cb76f26b72f91b5))
- **gatsby:** PQR worker can run static queries ([#32000](https://github.com/gatsbyjs/gatsby/issues/32000)) ([a6fd7b1](https://github.com/gatsbyjs/gatsby/commit/a6fd7b102480e3a9d74789e5181c8ad297641366))

# [3.9.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.8.0-next.2...gatsby@3.9.0-next.0) (2021-06-18)

**Note:** Version bump only for package gatsby

# [3.8.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.8.0-next.1...gatsby@3.8.0-next.2) (2021-06-17)

### Bug Fixes

- **gatsby:** infer shape of warning object ([#31489](https://github.com/gatsbyjs/gatsby/issues/31489)) ([96dc88a](https://github.com/gatsbyjs/gatsby/commit/96dc88aa8cef36a16d41f16e415c0e82606806e1))
- **gatsby:** Update eslint a11y config ([#31896](https://github.com/gatsbyjs/gatsby/issues/31896)) ([28ca867](https://github.com/gatsbyjs/gatsby/commit/28ca8676d6bddfef117a1361b1dad0973b700e57))

### Features

- **gatsby:** Main process can save slices of state & worker can access it ([#31822](https://github.com/gatsbyjs/gatsby/issues/31822)) ([7aa9c85](https://github.com/gatsbyjs/gatsby/commit/7aa9c85b01e12c48d73a69d89b7f1fa7c62ef7c3))
- **gatsby:** PQR workers can access inference metadata ([#31858](https://github.com/gatsbyjs/gatsby/issues/31858)) ([315b694](https://github.com/gatsbyjs/gatsby/commit/315b69454222e2b079ce891616687c084b86487b))
- **gatsby:** PQR workers can access page & static queries ([#31852](https://github.com/gatsbyjs/gatsby/issues/31852)) ([222a5ed](https://github.com/gatsbyjs/gatsby/commit/222a5edde3fcce0a71e14781ed62cc150ad1f8d7))
- **gatsby-plugin-google-analytics:** enable core webvitals tracking ([#31665](https://github.com/gatsbyjs/gatsby/issues/31665)) ([1ecd6e1](https://github.com/gatsbyjs/gatsby/commit/1ecd6e12eeedcabc54f3be00137a5d092978de58))

# [3.8.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.8.0-next.0...gatsby@3.8.0-next.1) (2021-06-10)

### Bug Fixes

- **gatsby:** do not add global id to style tag ([#31813](https://github.com/gatsbyjs/gatsby/issues/31813)) ([132d829](https://github.com/gatsbyjs/gatsby/commit/132d829e01b3b2ca50bfbe4533ae47b57b55a50c))
- **gatsby:** do not use domready package ([#31368](https://github.com/gatsbyjs/gatsby/issues/31368)) ([7a9a50c](https://github.com/gatsbyjs/gatsby/commit/7a9a50c9492c1c523daa64cf891b3de82635a632))
- **gatsby:** fix signature for latest experimental version of react-dom ([#31750](https://github.com/gatsbyjs/gatsby/issues/31750)) ([087cdd5](https://github.com/gatsbyjs/gatsby/commit/087cdd590929e1e29f5a658ffb3910292a8ca948))

### Features

- **gatsby:** remove concurrent-features flag and depend on export ([#31818](https://github.com/gatsbyjs/gatsby/issues/31818)) ([34b6d47](https://github.com/gatsbyjs/gatsby/commit/34b6d476f84c647f82c0b7e641caf4f64d48491a))
- **gatsby:** switch from arrays to node iterators ([#31718](https://github.com/gatsbyjs/gatsby/issues/31718)) ([5278e1e](https://github.com/gatsbyjs/gatsby/commit/5278e1e3a5148fb17b65310e6333d457db7e8446))
- **gatsby:** Turn on Functions experiment for everybody ([#31807](https://github.com/gatsbyjs/gatsby/issues/31807)) ([a485415](https://github.com/gatsbyjs/gatsby/commit/a4854150cb2d10501e0bafbbb86753c7905ff45f))

# [3.8.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.7.0-next.2...gatsby@3.8.0-next.0) (2021-06-03)

### Bug Fixes

- **gatsby:** fix PNP resolving from the .cache folder ([#31732](https://github.com/gatsbyjs/gatsby/issues/31732)) ([d10e8ce](https://github.com/gatsbyjs/gatsby/commit/d10e8ceddf915b8a6e8c2552cdb342d6ea4e6790))
- **gatsby:** fix tests for state persistence with lmdb ([#31736](https://github.com/gatsbyjs/gatsby/issues/31736)) ([5660ce9](https://github.com/gatsbyjs/gatsby/commit/5660ce98133bb9c4c5eab38c64ebdc56ccc4d792))

### Features

- **gatsby:** add createNodeManifest action ([#31127](https://github.com/gatsbyjs/gatsby/issues/31127)) ([eed6108](https://github.com/gatsbyjs/gatsby/commit/eed610813da645356316826a4558640ecc4365b5))

# [3.7.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.7.0-next.1...gatsby@3.7.0-next.2) (2021-06-02)

### Bug Fixes

- **gatsby:** merge resolveType when merging abstract types ([#31710](https://github.com/gatsbyjs/gatsby/issues/31710)) ([2dde956](https://github.com/gatsbyjs/gatsby/commit/2dde956bd1de6ad404416ec9dc4406a25951fe4b))

### Features

- **gatsby:** node persistence ([#31371](https://github.com/gatsbyjs/gatsby/issues/31371)) ([334d2bc](https://github.com/gatsbyjs/gatsby/commit/334d2bc2d3a03c83882dbc55bdc168647903c9f9)), closes [#31403](https://github.com/gatsbyjs/gatsby/issues/31403)

# [3.7.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.7.0-next.0...gatsby@3.7.0-next.1) (2021-05-31)

### Bug Fixes

- **gatsby:** add componentChunkName to components list so don't need to loop over pages ([#31547](https://github.com/gatsbyjs/gatsby/issues/31547)) ([783b937](https://github.com/gatsbyjs/gatsby/commit/783b937c8f70478796bce37808bf8bf967bb4252))
- **gatsby:** better detection of Babel rules for HMR when customizing the Webpack config ([#31477](https://github.com/gatsbyjs/gatsby/issues/31477)) ([42951f0](https://github.com/gatsbyjs/gatsby/commit/42951f0f459a15cb7a8923f97c52cc131ba6714d))
- **gatsby:** Correct config for svgo plugins whitelist ([7e787bd](https://github.com/gatsbyjs/gatsby/commit/7e787bd020788cb6bc9f72d88c7878bbb34d46c9))
- **gatsby:** prevent infinite loop in fast-refresh-overlay ([#31594](https://github.com/gatsbyjs/gatsby/issues/31594)) ([3368884](https://github.com/gatsbyjs/gatsby/commit/3368884db230b0ccbcd1c357273516859e9f0556))

### Features

- **gatsby:** enable concurrent features ([#31394](https://github.com/gatsbyjs/gatsby/issues/31394)) ([3457163](https://github.com/gatsbyjs/gatsby/commit/34571630f9b7e5de360cbf91c1e53aa655e86633))
- **gatsby:** lazily compile functions in development ([#31508](https://github.com/gatsbyjs/gatsby/issues/31508)) ([d38f4d9](https://github.com/gatsbyjs/gatsby/commit/d38f4d97256fe4654a68177bc81cdea6277267d5))

# [3.7.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.6...gatsby@3.7.0-next.0) (2021-05-21)

**Note:** Version bump only for package gatsby

# [3.6.0-next.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.5...gatsby@3.6.0-next.6) (2021-05-20)

### Features

- **gatsby:** enable webpack fs caching for functions ([#31505](https://github.com/gatsbyjs/gatsby/issues/31505)) ([4ff7dd3](https://github.com/gatsbyjs/gatsby/commit/4ff7dd36376ffa7581fe8b02a54a2a06e00bcaba))
- **gatsby:** Resolve typescript files in functions without needing to add the extension ([#31487](https://github.com/gatsbyjs/gatsby/issues/31487)) ([04f7a45](https://github.com/gatsbyjs/gatsby/commit/04f7a4562dc0b5922730d71acd3b157b7ad732b5))

# [3.6.0-next.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.4...gatsby@3.6.0-next.5) (2021-05-19)

### Features

- **gatsby:** Speedup building Functions by disabling minification ([#31473](https://github.com/gatsbyjs/gatsby/issues/31473)) ([a8a4f76](https://github.com/gatsbyjs/gatsby/commit/a8a4f7670eaaafb67e2999efb0dc4af51e52ede6))

# [3.6.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.3...gatsby@3.6.0-next.4) (2021-05-19)

### Features

- **gatsby:** Support uploading files as part of forms ([#31470](https://github.com/gatsbyjs/gatsby/issues/31470)) ([0d3886c](https://github.com/gatsbyjs/gatsby/commit/0d3886cf37f845a765f283ce4d850ca8bbd502a3))

# [3.6.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.2...gatsby@3.6.0-next.3) (2021-05-18)

### Features

- **gatsby:** Support Functions in plugins ([#31466](https://github.com/gatsbyjs/gatsby/issues/31466)) ([54aaca4](https://github.com/gatsbyjs/gatsby/commit/54aaca49f1a1404328e21df4c7ea53c7697d1d41))

# [3.6.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.1...gatsby@3.6.0-next.2) (2021-05-18)

### Bug Fixes

- **gatsby:** preload and prefetches check for in-browser redirects ([#31366](https://github.com/gatsbyjs/gatsby/issues/31366)) ([d86cd9f](https://github.com/gatsbyjs/gatsby/commit/d86cd9ffd460f0840bc8ce572b628fb82d8004f8))

# [3.6.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.6.0-next.0...gatsby@3.6.0-next.1) (2021-05-12)

### Bug Fixes

- **gatsby:** don't print out flag suggestions if none are enabled or opted-in ([#31299](https://github.com/gatsbyjs/gatsby/issues/31299)) ([48eea6f](https://github.com/gatsbyjs/gatsby/commit/48eea6f4f155b354c000cd7fdf1ed4830aaad642))
- **gatsby:** fix proxy creation on read-only properties ([#31346](https://github.com/gatsbyjs/gatsby/issues/31346)) ([c210f1d](https://github.com/gatsbyjs/gatsby/commit/c210f1dba38b16da851a72f9f864d0d21f9878f7))
- **gatsby:** Fixes incorrect type ([#31358](https://github.com/gatsbyjs/gatsby/issues/31358)) ([f629806](https://github.com/gatsbyjs/gatsby/commit/f6298068b3b4e0528c006bcc3d163a9873e76783))
- **gatsby:** only load gatsby-plugin-gatsby-cloud on cloud ([#31345](https://github.com/gatsbyjs/gatsby/issues/31345)) ([ec0fc57](https://github.com/gatsbyjs/gatsby/commit/ec0fc571bcb5a1ee25fb507c52b64310a86e935b))
- **gatsby:** Pass reporter from functions code for reporting warning ([#31336](https://github.com/gatsbyjs/gatsby/issues/31336)) ([f09fae8](https://github.com/gatsbyjs/gatsby/commit/f09fae8f415a018f60abb56fff017f574ae8c871))
- **gatsby-plugin-mdx:** enable hmr when importing mdx ([#31288](https://github.com/gatsbyjs/gatsby/issues/31288)) ([c8db78f](https://github.com/gatsbyjs/gatsby/commit/c8db78fad43294413b950c49205adcf3dbb6dd1e))
- **tests:** update cheerio snapshots ([#31298](https://github.com/gatsbyjs/gatsby/issues/31298)) ([e06599d](https://github.com/gatsbyjs/gatsby/commit/e06599d9acc53442f8830b04f8fa2c749a820cc5))

### Features

- **gatsby:** change bgcolor of 'EXPERIMENTAL' label so it does look like an error ([#31352](https://github.com/gatsbyjs/gatsby/issues/31352)) ([043371f](https://github.com/gatsbyjs/gatsby/commit/043371fc60bf7e2dea851eff307fe24e5416f077))
- **gatsby:** Functions aren't GA but they're not longer EXPERIMENTAL ([#31353](https://github.com/gatsbyjs/gatsby/issues/31353)) ([c1f365a](https://github.com/gatsbyjs/gatsby/commit/c1f365a80877032116587061b708b1c23c0caecc))
- **gatsby:** Improve dev 404 page ([#31332](https://github.com/gatsbyjs/gatsby/issues/31332)) ([dfaea09](https://github.com/gatsbyjs/gatsby/commit/dfaea09dc7c0cb4a3694eb75c5f0a9ab5a32e39f))
- **gatsby:** New overlay for DEV_SSR ([#31061](https://github.com/gatsbyjs/gatsby/issues/31061)) ([7110189](https://github.com/gatsbyjs/gatsby/commit/7110189fda3942aba27cf35f577ce14d7b252d0b))

# [3.6.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.5.0-next.4...gatsby@3.6.0-next.0) (2021-05-06)

### Bug Fixes

- **deps:** update dependency mini-css-extract-plugin to v1.6.0 ([#31158](https://github.com/gatsbyjs/gatsby/issues/31158)) ([137630e](https://github.com/gatsbyjs/gatsby/commit/137630ec719ae67836755a44ddd8451ef25435ed))
- **gatsby:** update plugin api types ([#30819](https://github.com/gatsbyjs/gatsby/issues/30819)) ([aa09e6f](https://github.com/gatsbyjs/gatsby/commit/aa09e6fb2f525242680d53d77b5ce7f76b5b63a8))

### Features

- **gatsby:** Don't send error for function errors if headers are already sent ([#31265](https://github.com/gatsbyjs/gatsby/issues/31265)) ([d9c78a0](https://github.com/gatsbyjs/gatsby/commit/d9c78a052d2187ad6808b584185f731c0988d610))

### Performance Improvements

- **gatsby:** use fastq instead of better-queue + refactor ([#31269](https://github.com/gatsbyjs/gatsby/issues/31269)) ([fef8d6b](https://github.com/gatsbyjs/gatsby/commit/fef8d6ba5fdb1386fd7716dc59423c65fa9fd402))

# [3.5.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.5.0-next.3...gatsby@3.5.0-next.4) (2021-05-05)

### Bug Fixes

- **gatsby:** add generic type to GatsbyFunctionResponse ([#31182](https://github.com/gatsbyjs/gatsby/issues/31182)) ([4b9d0d4](https://github.com/gatsbyjs/gatsby/commit/4b9d0d4d4757d006ec385bb80f1db415a9636f63))
- **gatsby:** rehydration issue in Dev404Page with DEV_SSR ([#30581](https://github.com/gatsbyjs/gatsby/issues/30581)) ([5005588](https://github.com/gatsbyjs/gatsby/commit/5005588c92101d8be19c23d9404bdd952ac3ed73))
- **gatsby:** upgrade css-minimizer-webpack-plugin to v2 ([#31176](https://github.com/gatsbyjs/gatsby/issues/31176)) ([257de93](https://github.com/gatsbyjs/gatsby/commit/257de93a6e1caf46cbad4172ef342e928aa4b97e))

### Performance Improvements

- **gatsby:** Create page object & SitePage node in same action creator ([#31104](https://github.com/gatsbyjs/gatsby/issues/31104)) ([d1005fa](https://github.com/gatsbyjs/gatsby/commit/d1005fae2fe273f26cc650137426369c4c84b067)), closes [#31236](https://github.com/gatsbyjs/gatsby/issues/31236)

# [3.5.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.5.0-next.2...gatsby@3.5.0-next.3) (2021-05-01)

### Bug Fixes

- **gatsby:** fix profiler for build ([#31116](https://github.com/gatsbyjs/gatsby/issues/31116)) ([643ea7a](https://github.com/gatsbyjs/gatsby/commit/643ea7af1d6e586e7963cb04b4e3d95fd23b5fb5))

### Features

- **gatsby:** enable gatsby-plugin-gatsby-cloud by default ([#30624](https://github.com/gatsbyjs/gatsby/issues/30624)) ([4259940](https://github.com/gatsbyjs/gatsby/commit/4259940f2b6d70ea7fb9f57d763dd6008caaceef))
- **gatsby:** first pass at API functions docs ([#31066](https://github.com/gatsbyjs/gatsby/issues/31066)) ([88ca620](https://github.com/gatsbyjs/gatsby/commit/88ca6209a3f0cf4f0357df3e6047c17812b0ebac))

# [3.5.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.5.0-next.1...gatsby@3.5.0-next.2) (2021-04-29)

### Bug Fixes

- **webpack-theme-component-shadowing:** Support shadowing in yarn-style workspaces with Webpack 5 ([#30435](https://github.com/gatsbyjs/gatsby/issues/30435)) ([ab919ea](https://github.com/gatsbyjs/gatsby/commit/ab919ea04ed3f9a4490a68fab4cda22834383673))

# [3.5.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.5.0-next.0...gatsby@3.5.0-next.1) (2021-04-28)

### Bug Fixes

- **gatsby:** handle case of changing page path casing on case-insensitive fs ([#31071](https://github.com/gatsbyjs/gatsby/issues/31071)) ([940eddf](https://github.com/gatsbyjs/gatsby/commit/940eddf9be41deab9544d26db38a661095ee37a7))

### Features

- **gatsby:** Add note to DEV_SSR flag about custom webpack config ([#31063](https://github.com/gatsbyjs/gatsby/issues/31063)) ([0fd6c1f](https://github.com/gatsbyjs/gatsby/commit/0fd6c1f23a02bdbd873be4694f8c6de75769193e)), closes [/github.com/gatsbyjs/gatsby/discussions/28138#discussioncomment-598599](https://github.com//github.com/gatsbyjs/gatsby/discussions/28138/issues/discussioncomment-598599)

# [3.5.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.6...gatsby@3.5.0-next.0) (2021-04-23)

### Bug Fixes

- **gatsby:** Refactor overlay utils ([#31005](https://github.com/gatsbyjs/gatsby/issues/31005)) ([4930aa5](https://github.com/gatsbyjs/gatsby/commit/4930aa5b34e08ad49177820304bb6dd262c56b3f))
- use cpuCount for all parallel parts ([#30548](https://github.com/gatsbyjs/gatsby/issues/30548)) ([9dbb772](https://github.com/gatsbyjs/gatsby/commit/9dbb77238f23eedbb9b6dcf5ffb3453cb67bc9b8))
- **gatsby:** honor flags disabled via config when deciding wether to add included flags ([#30992](https://github.com/gatsbyjs/gatsby/issues/30992)) ([e7327c3](https://github.com/gatsbyjs/gatsby/commit/e7327c311c0b606dc3ddc8e06507ad0c55a82f07))
- **gatsby:** persist pages between runs ([#28590](https://github.com/gatsbyjs/gatsby/issues/28590)) ([a0b31bc](https://github.com/gatsbyjs/gatsby/commit/a0b31bcaaa04db8ff0675b3653c841bf47c67814)), closes [#28760](https://github.com/gatsbyjs/gatsby/issues/28760) [#29431](https://github.com/gatsbyjs/gatsby/issues/29431) [#30848](https://github.com/gatsbyjs/gatsby/issues/30848)
- **gatsby:** try to get linenumber from compile error ([#30615](https://github.com/gatsbyjs/gatsby/issues/30615)) ([7dd645d](https://github.com/gatsbyjs/gatsby/commit/7dd645d65dd971cb6eaa800895f7267fa2fa6c5c))
- **gatsby,gatsby-plugin-offline:** register offline plugin when not on preview ([#30984](https://github.com/gatsbyjs/gatsby/issues/30984)) ([17f028d](https://github.com/gatsbyjs/gatsby/commit/17f028d7085e1e4dc7bd361134bf0230b2cb7d95))

### Features

- **gatsby:** test redirects ([#31011](https://github.com/gatsbyjs/gatsby/issues/31011)) ([7838b18](https://github.com/gatsbyjs/gatsby/commit/7838b18306d4290b2eced775ade23b10c663ec82))
- **gatsby:** use webpack fs caching in prod behind feature flag ([#30857](https://github.com/gatsbyjs/gatsby/issues/30857)) ([66127cc](https://github.com/gatsbyjs/gatsby/commit/66127cc34d7568f3343aebfb7d2e1a71ec5ee150))

# [3.4.0-next.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.5...gatsby@3.4.0-next.6) (2021-04-22)

### Bug Fixes

- **gatsby:** Don't use process.cwd() to find public directory for DEV_SSR ([#30605](https://github.com/gatsbyjs/gatsby/issues/30605)) ([31e2f79](https://github.com/gatsbyjs/gatsby/commit/31e2f79a3e3e7efa5b53345399f935b8dba7aefb))
- **gatsby:** filter out not applicable flags (isCi / command) when constructing flags message ([#30977](https://github.com/gatsbyjs/gatsby/issues/30977)) ([b9ef04a](https://github.com/gatsbyjs/gatsby/commit/b9ef04a1d47f1178feadb49afca336a4b5d077cf))

### Features

- **gatsby:** Add Typescript types for function requests/responses ([#30991](https://github.com/gatsbyjs/gatsby/issues/30991)) ([b8692ac](https://github.com/gatsbyjs/gatsby/commit/b8692ac15bcef0c6bdbd3f6c920e36af848240b3))
- **gatsby:** parse cookies in functions to req.cookies ([#30993](https://github.com/gatsbyjs/gatsby/issues/30993)) ([ca172c8](https://github.com/gatsbyjs/gatsby/commit/ca172c8f043c842a297f1e6029b078b94031d3b5))

# [3.4.0-next.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.4...gatsby@3.4.0-next.5) (2021-04-20)

**Note:** Version bump only for package gatsby

# [3.4.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.3...gatsby@3.4.0-next.4) (2021-04-20)

### Bug Fixes

- **gatsby:** add support for useStaticQuery with commonjs/require ([#30941](https://github.com/gatsbyjs/gatsby/issues/30941)) ([0d23703](https://github.com/gatsbyjs/gatsby/commit/0d23703c104c3557a77cfbc0e98d5dc9f947c909))
- **gatsby:** change order of feedbackDisabled checks to allow CI AWS lambda build ([#30653](https://github.com/gatsbyjs/gatsby/issues/30653)) ([303dc4b](https://github.com/gatsbyjs/gatsby/commit/303dc4bd5b1c79b5bb982e2ac8b5de67630d7083))

### Features

- **gatsby:** add support for dynamic routes for API functions ([#30904](https://github.com/gatsbyjs/gatsby/issues/30904)) ([e44d6a7](https://github.com/gatsbyjs/gatsby/commit/e44d6a78f7f63e434a159536f07d1105067e997b))

# [3.4.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.2...gatsby@3.4.0-next.3) (2021-04-19)

### Bug Fixes

- **gatsby:** Better Fast Refresh handling for <Root /> ([#30901](https://github.com/gatsbyjs/gatsby/issues/30901)) ([70b25d1](https://github.com/gatsbyjs/gatsby/commit/70b25d1f82ba35fd992d0442bc72f660c8427f87))

# [3.4.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.1...gatsby@3.4.0-next.2) (2021-04-16)

### Features

- **gatsby-plugin-functions:** Add the ability to run functions locally and on Gatsby Cloud ([#30192](https://github.com/gatsbyjs/gatsby/issues/30192)) ([41eef2b](https://github.com/gatsbyjs/gatsby/commit/41eef2bdcc8890991e8d5e7c0d5df795992096ff)), closes [#30222](https://github.com/gatsbyjs/gatsby/issues/30222) [#30277](https://github.com/gatsbyjs/gatsby/issues/30277) [#30338](https://github.com/gatsbyjs/gatsby/issues/30338)

# [3.4.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.4.0-next.0...gatsby@3.4.0-next.1) (2021-04-16)

### Bug Fixes

- **gatsby:** "Cannot find module 'babel-preset-gatsby'" error ([#30813](https://github.com/gatsbyjs/gatsby/issues/30813)) ([9789823](https://github.com/gatsbyjs/gatsby/commit/97898232e98e59926f39a711e263cf999ddc37ca))
- **gatsby:** Decode base path in runtime ([#30682](https://github.com/gatsbyjs/gatsby/issues/30682)) ([304e585](https://github.com/gatsbyjs/gatsby/commit/304e5859d5b25691c3d1f5183c3c2855aac79602))
- **gatsby:** lower memory pressure in SSR ([#30793](https://github.com/gatsbyjs/gatsby/issues/30793)) ([c03e562](https://github.com/gatsbyjs/gatsby/commit/c03e562e3b7493c1903e710f80c24857b01267b6))
- **gatsby:** webpack warnings are no longer in object format by default ([#30801](https://github.com/gatsbyjs/gatsby/issues/30801)) ([33415c8](https://github.com/gatsbyjs/gatsby/commit/33415c821bf9546aa3d1ac62afb75b9ffeb67a76))
- **gatsby:** z-index for loading-indicator ([#30888](https://github.com/gatsbyjs/gatsby/issues/30888)) ([18482b1](https://github.com/gatsbyjs/gatsby/commit/18482b123ec87e76cdc738180a1314ea81ad7afa))

### Features

- **gatsby:** Add aggregation resolvers ([#30789](https://github.com/gatsbyjs/gatsby/issues/30789)) ([0e91c82](https://github.com/gatsbyjs/gatsby/commit/0e91c82ace7eff1c21ec23667021a9f19056c564))
- **gatsby:** Memoize process.env access and repeated function calls ([#30768](https://github.com/gatsbyjs/gatsby/issues/30768)) ([7802e3c](https://github.com/gatsbyjs/gatsby/commit/7802e3c371b20b4f212a45b7a23887d23847709a))

# [3.4.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.3.0-next.3...gatsby@3.4.0-next.0) (2021-04-09)

**Note:** Version bump only for package gatsby

# [3.3.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.3.0-next.2...gatsby@3.3.0-next.3) (2021-04-09)

### Performance Improvements

- **gatsby:** cache babel config items ([#28738](https://github.com/gatsbyjs/gatsby/issues/28738)) ([ecd823f](https://github.com/gatsbyjs/gatsby/commit/ecd823fb424a82a8f7b8aa5da56dbaca74d3269d))

# [3.3.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.3.0-next.1...gatsby@3.3.0-next.2) (2021-04-07)

### Bug Fixes

- **docs:** edits to Gatsby Node APIs doc ([#30656](https://github.com/gatsbyjs/gatsby/issues/30656)) ([9699e31](https://github.com/gatsbyjs/gatsby/commit/9699e31e354fd484b3834bea2ac4a2e50d6179b4))
- **gatsby:** fix incorrect intersection of filtered results ([#30594](https://github.com/gatsbyjs/gatsby/issues/30594)) ([e432c23](https://github.com/gatsbyjs/gatsby/commit/e432c231eb65e66208ab29605aa670e6c873303f))

# [3.3.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.3.0-next.0...gatsby@3.3.0-next.1) (2021-03-30)

### Bug Fixes

- **gatsby:** Handle arrays of dates in distinct ([#30460](https://github.com/gatsbyjs/gatsby/issues/30460)) ([2f87f89](https://github.com/gatsbyjs/gatsby/commit/2f87f8934c4bf5a14d6ac5297d8f0ce37f55e223))
- **gatsby:** merge inherited interfaces when merging types ([#30501](https://github.com/gatsbyjs/gatsby/issues/30501)) ([e1f1656](https://github.com/gatsbyjs/gatsby/commit/e1f1656b36e4912c1712cada0124fc38f4b4e07e))

# [3.3.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.2.0-next.1...gatsby@3.3.0-next.0) (2021-03-25)

### Bug Fixes

- **gatsby:** Add allowNamespace option to ESLint config ([#30023](https://github.com/gatsbyjs/gatsby/issues/30023)) ([98001eb](https://github.com/gatsbyjs/gatsby/commit/98001ebd36b4eaace6c9b35ecc3a96f96e6f7010))
- **gatsby:** Add reporter.panic in empty catch in load-themes ([#29640](https://github.com/gatsbyjs/gatsby/issues/29640)) ([3a8789b](https://github.com/gatsbyjs/gatsby/commit/3a8789b4875444c0ce33d313bc82290d2c38261e))
- **gatsby:** update nested input types when rebuilding SitePage ([#30426](https://github.com/gatsbyjs/gatsby/issues/30426)) ([54d4721](https://github.com/gatsbyjs/gatsby/commit/54d4721462b9303fed723fdcb15ac5d72e103778))
- **gatsby:** validate local plugin options schema ([#29787](https://github.com/gatsbyjs/gatsby/issues/29787)) ([096eb38](https://github.com/gatsbyjs/gatsby/commit/096eb38464d9ad7da79f3acb45ade6aee8765b75))
- **gatsby,gatsby-cli:** Correct behavior for reporter.error with pluginName ([#30331](https://github.com/gatsbyjs/gatsby/issues/30331)) ([eb1e2d8](https://github.com/gatsbyjs/gatsby/commit/eb1e2d8a3fa78027613b530f667b22fe99b4bfcd))

### Performance Improvements

- **gatsby:** Optimise `distinct` queries ([#30457](https://github.com/gatsbyjs/gatsby/issues/30457)) ([f462e23](https://github.com/gatsbyjs/gatsby/commit/f462e23c26459ccdc30d7abdce1abc375f6ee4eb))

# [3.2.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.2.0-next.0...gatsby@3.2.0-next.1) (2021-03-19)

### Bug Fixes

- **gatsby:** be less aggressive when marking builtin methods as unsafe ([#30216](https://github.com/gatsbyjs/gatsby/issues/30216)) ([331d76e](https://github.com/gatsbyjs/gatsby/commit/331d76e41533db65d896df2c08c55b929219d124))
- **gatsby:** do not fail on 3rd-party schemas with relay-classic support ([#30318](https://github.com/gatsbyjs/gatsby/issues/30318)) ([3c2888c](https://github.com/gatsbyjs/gatsby/commit/3c2888c011d24153422a48ca20f37200f002ee67))

# [3.2.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.1.0-next.4...gatsby@3.2.0-next.0) (2021-03-11)

### Bug Fixes

- **gatsby:** workaround some webpack issues causing first save after running gatsby develop to not have any effect ([#30193](https://github.com/gatsbyjs/gatsby/issues/30193)) ([a9d65f6](https://github.com/gatsbyjs/gatsby/commit/a9d65f640891ebcaa8da9ccc9c8ef0f40e4905cd))
- **gatsyby:** improve error messages for errors outside of react" ([#30031](https://github.com/gatsbyjs/gatsby/issues/30031)) ([8183012](https://github.com/gatsbyjs/gatsby/commit/818301227f6f8946e2130a43b75f3d685bc32b70))

# [3.1.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.1.0-next.3...gatsby@3.1.0-next.4) (2021-03-10)

### Bug Fixes

- **deps:** update lodash monorepo to ^4.17.21 ([#29382](https://github.com/gatsbyjs/gatsby/issues/29382)) ([9fd287b](https://github.com/gatsbyjs/gatsby/commit/9fd287ba89eacd55652d468b18f6e1526230e7c6))
- **gatsby:** Add dir=ltr to Fast Refresh overlay ([#29900](https://github.com/gatsbyjs/gatsby/issues/29900)) ([89d3150](https://github.com/gatsbyjs/gatsby/commit/89d3150a33441b3690d56ce5a99afd19452f6f03))
- **gatsby:** always pass `stage` option to `babel-preset-gatsby` ([#30047](https://github.com/gatsbyjs/gatsby/issues/30047)) ([8cedc8d](https://github.com/gatsbyjs/gatsby/commit/8cedc8dd15e0fd3cb5bc62e8276a4a1f96e7c6f4))
- **gatsby:** change browserlist to web/es5 ([#29954](https://github.com/gatsbyjs/gatsby/issues/29954)) ([ba8a498](https://github.com/gatsbyjs/gatsby/commit/ba8a498c268694999bfa7961d41018b09b523779))
- **gatsby:** don't ignore SOURCE_FILE_CHANGED event ([#30127](https://github.com/gatsbyjs/gatsby/issues/30127)) ([f6d1c09](https://github.com/gatsbyjs/gatsby/commit/f6d1c093d2f5cf73e8bfdbfeefac18115a145463))
- **gatsby:** Fix broken reporter call ([#30092](https://github.com/gatsbyjs/gatsby/issues/30092)) ([9429b3b](https://github.com/gatsbyjs/gatsby/commit/9429b3bfc5ab00ae02efddc20188a3bb95629e6d))
- **gatsby:** fix routing for paths with characters like `@` etc ([#29935](https://github.com/gatsbyjs/gatsby/issues/29935)) ([157ae16](https://github.com/gatsbyjs/gatsby/commit/157ae165a4d1baa55a272b43f21c7acc89b4294b))
- **gatsby:** fix some css HMR edge cases ([#29839](https://github.com/gatsbyjs/gatsby/issues/29839)) ([52facaf](https://github.com/gatsbyjs/gatsby/commit/52facaf7c5bf377cbec42d9d9f18832751a429a1))
- **gatsby:** Fix various small DEV_SSR bugs exposed in development_runtime tests ([#29720](https://github.com/gatsbyjs/gatsby/issues/29720)) ([114e006](https://github.com/gatsbyjs/gatsby/commit/114e006c5866c15c8448904746d968e4ef904f83))
- **gatsby:** freeze the schema only after rebuilding with SitePage ([#30132](https://github.com/gatsbyjs/gatsby/issues/30132)) ([4fc4248](https://github.com/gatsbyjs/gatsby/commit/4fc424868fa72b04a8152b2e8f0dceeb4955b15f))
- **gatsby:** handle case of removing trailing slash in inc builds ([#29953](https://github.com/gatsbyjs/gatsby/issues/29953)) ([7462030](https://github.com/gatsbyjs/gatsby/commit/7462030b9f3c6ad028a2469b850e3477b4f0b954))
- **gatsby:** Improve Fast Refresh overlay styles ([#29855](https://github.com/gatsbyjs/gatsby/issues/29855)) ([c8bf060](https://github.com/gatsbyjs/gatsby/commit/c8bf0605ada2f4f20c518d51ef8629fb2ea48de7))
- **gatsby:** Remove `react-hot-loader` deps & other unused deps ([#29864](https://github.com/gatsbyjs/gatsby/issues/29864)) ([39721fd](https://github.com/gatsbyjs/gatsby/commit/39721fd2f3f4a997c6a954c60ae81bb93712c0b1))
- **gatsby:** set program.verbose when VERBOSE env var is used ([#30123](https://github.com/gatsbyjs/gatsby/issues/30123)) ([632f915](https://github.com/gatsbyjs/gatsby/commit/632f9151ceb2d5621dc720adca3ee8049e6179d6))
- **gatsby:** with some custom babel configs array spreading with Set is not safe ([#29885](https://github.com/gatsbyjs/gatsby/issues/29885)) ([5d312fe](https://github.com/gatsbyjs/gatsby/commit/5d312fe5433dbafb9a6b7eeba6abb563dba27ef2))
- **gatsby-plugin-preact:** fix fast-refresh ([#29831](https://github.com/gatsbyjs/gatsby/issues/29831)) ([81a3776](https://github.com/gatsbyjs/gatsby/commit/81a377650e267b930482abf647053b1a0b6bc384))

### Features

- **gatsby:** Add darkmode support to Fast Refresh overlay ([#30025](https://github.com/gatsbyjs/gatsby/issues/30025)) ([b7fb616](https://github.com/gatsbyjs/gatsby/commit/b7fb616ab79f10dd8f1faf6ea23fea0fa4424f26))
- **gatsby:** improve error messages at runtime ([#29970](https://github.com/gatsbyjs/gatsby/issues/29970)) ([d37f275](https://github.com/gatsbyjs/gatsby/commit/d37f2757b6b6e46335f3ba4fcaabf3a85251f045))

# [3.1.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.1.0-next.2...gatsby@3.1.0-next.3) (2021-02-28)

### Bug Fixes

- query on demand loading indicator always active on preact. ([#29829](https://github.com/gatsbyjs/gatsby/issues/29829)) ([fa1e2d6](https://github.com/gatsbyjs/gatsby/commit/fa1e2d66b806c92a04d63f023f77bb5770981808))
- **gatsby:** eslint linting ([#29796](https://github.com/gatsbyjs/gatsby/issues/29796)) ([2d52a55](https://github.com/gatsbyjs/gatsby/commit/2d52a5567018b5ebb185cd08bc41500a0d657136))
- **gatsby:** workaround graphql-compose issue ([#29822](https://github.com/gatsbyjs/gatsby/issues/29822)) ([7f9bcf1](https://github.com/gatsbyjs/gatsby/commit/7f9bcf10797f0e1ba1583c6f1a6417ffe91f1b5e))
- **hmr:** accept hot updates for modules above page templates ([#29752](https://github.com/gatsbyjs/gatsby/issues/29752)) ([55778eb](https://github.com/gatsbyjs/gatsby/commit/55778eb11e816ceaf29ad20d6ff05192cdf68f4c))

# [3.1.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.1.0-next.1...gatsby@3.1.0-next.2) (2021-02-26)

### Bug Fixes

- **gatsby:** Update styles & overlay for Fast Refresh ([#29797](https://github.com/gatsbyjs/gatsby/issues/29797)) ([22da802](https://github.com/gatsbyjs/gatsby/commit/22da8028395d61fb2bef0b66418ae2c83fe29e6e))
- **gatsby:** Use vendored @reach/router ([#29772](https://github.com/gatsbyjs/gatsby/issues/29772)) ([8754e0c](https://github.com/gatsbyjs/gatsby/commit/8754e0c6eb1b8f88422e60f31a1dca37925e8b2e))
- **mini-css-extract:** don't use loader in ssr ([#29801](https://github.com/gatsbyjs/gatsby/issues/29801)) ([b2d6617](https://github.com/gatsbyjs/gatsby/commit/b2d66171081dffbfdd9e5def281d09c011a6a821))

# [3.1.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.1.0-next.0...gatsby@3.1.0-next.1) (2021-02-26)

**Note:** Version bump only for package gatsby

# [3.1.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.9...gatsby@3.1.0-next.0) (2021-02-26)

### Bug Fixes

- **gatsby:** temporarily pin mini-css-extract-plugin version ([#29773](https://github.com/gatsbyjs/gatsby/issues/29773)) ([8967b88](https://github.com/gatsbyjs/gatsby/commit/8967b888b71ce2621b3f2957dae42f78b394ba20))

### Features

- **gatsby:** Add ignoreCase option for createRedirect and support it in client sid… ([#29714](https://github.com/gatsbyjs/gatsby/issues/29714)) ([09f58de](https://github.com/gatsbyjs/gatsby/commit/09f58defb6c3b4b26a3efbc8151fbf129e5cb7fd))
- **gatsby:** Set up Fast Refresh ([#29588](https://github.com/gatsbyjs/gatsby/issues/29588)) ([e0bd955](https://github.com/gatsbyjs/gatsby/commit/e0bd955677dd23c26491e794d9a339eb343e632b))

# [3.0.0-next.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.8...gatsby@3.0.0-next.9) (2021-02-25)

### Bug Fixes

- don't print deprecation warning for deleteNode for the sample plugin multiple times ([#29746](https://github.com/gatsbyjs/gatsby/issues/29746)) ([66477f1](https://github.com/gatsbyjs/gatsby/commit/66477f1e40355c56a5fdabc572388d8c81a213e2))
- don't print deprecation warning for touchNode for the sample plugin multiple times ([#29745](https://github.com/gatsbyjs/gatsby/issues/29745)) ([d024b70](https://github.com/gatsbyjs/gatsby/commit/d024b70528232818ee573394e42ca47cc28ce8a8))
- re-implement loadPageDataSync for onRenderBody in gatsby-ssr ([#29734](https://github.com/gatsbyjs/gatsby/issues/29734)) ([3d8a7db](https://github.com/gatsbyjs/gatsby/commit/3d8a7db7f51f61f6ba41de60782c28c4a298187e))
- **DEV_SSR:** set NODE_ENV to production for render-html worker process instead of pointing externals to production react ([#29620](https://github.com/gatsbyjs/gatsby/issues/29620)) ([d8772ec](https://github.com/gatsbyjs/gatsby/commit/d8772ec9dd398ebf1a0e4ecf423f16455a4cbf11))
- **develop:** add blank .css to ensure mini-css-extract-plugin always has something to extract ([#29681](https://github.com/gatsbyjs/gatsby/issues/29681)) ([5de8562](https://github.com/gatsbyjs/gatsby/commit/5de8562e38e3874040717fa00153b2753861a383))
- **gatsby:** context.nodeModel.runQuery should return [] instead of null ([#25885](https://github.com/gatsbyjs/gatsby/issues/25885)) ([684ac0e](https://github.com/gatsbyjs/gatsby/commit/684ac0eeb0d0ed2935079a69240977256714a4f2))
- **gatsby:** fix fs empty webpack5 deprecation ([#29631](https://github.com/gatsbyjs/gatsby/issues/29631)) ([893219e](https://github.com/gatsbyjs/gatsby/commit/893219ebceb84c5eb43beebbdeefe81fece33330))
- **gatsby:** fix regex filter in graphql queries ([#26592](https://github.com/gatsbyjs/gatsby/issues/26592)) ([9ecec6c](https://github.com/gatsbyjs/gatsby/commit/9ecec6c0074e34a4d558974171634fa722a0d8e3))
- **gatsby:** fix root resolving of resources ([#29577](https://github.com/gatsbyjs/gatsby/issues/29577)) ([affb1d6](https://github.com/gatsbyjs/gatsby/commit/affb1d6c055efd58586d4e6fb667f64dee9cd18e))
- **gatsby:** re-add prefetch/preload links for child assets ([#29693](https://github.com/gatsbyjs/gatsby/issues/29693)) ([170c604](https://github.com/gatsbyjs/gatsby/commit/170c604ace4cd27b056412cadbbd008d87ec2379))
- **gatsby:** render QoD overlay in its own root element to avoid hydration issues ([#29692](https://github.com/gatsbyjs/gatsby/issues/29692)) ([d3dd3e1](https://github.com/gatsbyjs/gatsby/commit/d3dd3e15e27ea040d764a81c6f77f15c281f2499))
- **webpack:** don't disable webpack's cache ([#29663](https://github.com/gatsbyjs/gatsby/issues/29663)) ([258e0f7](https://github.com/gatsbyjs/gatsby/commit/258e0f7dbfa500353cdadf80077896383a35c76c))

### Features

- **gatsby:** Respect VERBOSE env var ([#29708](https://github.com/gatsbyjs/gatsby/issues/29708)) ([97d6d3e](https://github.com/gatsbyjs/gatsby/commit/97d6d3ed841268adcf3b0de51ed2abd4d4770e70))
- shim reporter from gatsby ([#29669](https://github.com/gatsbyjs/gatsby/issues/29669)) ([249905a](https://github.com/gatsbyjs/gatsby/commit/249905ac92f11efdb2333828667b946a860a1a27))
- **conditional-page-builds:** track potentially unsafe Node.js builtin modules usage ([#29560](https://github.com/gatsbyjs/gatsby/issues/29560)) ([fe737d0](https://github.com/gatsbyjs/gatsby/commit/fe737d0784b11dd03f6d3b8c69cf964de5bd50f5))
- **gatsby:** move sync-requires to async-requires in develop ([#29391](https://github.com/gatsbyjs/gatsby/issues/29391)) ([82b7c03](https://github.com/gatsbyjs/gatsby/commit/82b7c03476370d1ec76491ff192c29c05c0f878f))

# [3.0.0-next.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.7...gatsby@3.0.0-next.8) (2021-02-22)

### Bug Fixes

- **gatsby:** cleanup fullySpecified resolving ([#29576](https://github.com/gatsbyjs/gatsby/issues/29576)) ([1343d38](https://github.com/gatsbyjs/gatsby/commit/1343d38a6f22e8919eacbfdcb718fbdc409a03dc))

### Features

- **gatsby-core-utils:** Add file download functions ([#29531](https://github.com/gatsbyjs/gatsby/issues/29531)) ([1a9469d](https://github.com/gatsbyjs/gatsby/commit/1a9469d67a19007faebebfb8ce876970c5e0ffaf))

# [3.0.0-next.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.6...gatsby@3.0.0-next.7) (2021-02-19)

### Bug Fixes

- **css-modules:** fix webpack config for css modules ([#29596](https://github.com/gatsbyjs/gatsby/issues/29596)) ([c43fb52](https://github.com/gatsbyjs/gatsby/commit/c43fb520ae7f7e028ac77ac39e89c411cbaf1452))
- **gatsby:** fix deprecation export messages ([#29563](https://github.com/gatsbyjs/gatsby/issues/29563)) ([15b55f0](https://github.com/gatsbyjs/gatsby/commit/15b55f09ba97c7cabe368900bcdc4c120f988d47))
- **gatsby:** prevent errors when backwards compat node.nodeId is for a deleted node in touchNode ([#29575](https://github.com/gatsbyjs/gatsby/issues/29575)) ([077eb16](https://github.com/gatsbyjs/gatsby/commit/077eb16f78cf72f2f4291bd4e51de61a5d6d826c))

### Features

- remove react-hot-loader ([#29540](https://github.com/gatsbyjs/gatsby/issues/29540)) ([a5210b2](https://github.com/gatsbyjs/gatsby/commit/a5210b2550b9646656aae28c28cb5be580cd5677))

# [3.0.0-next.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.5...gatsby@3.0.0-next.6) (2021-02-18)

### Features

- **conditional-page-builds:** make it default ([#29548](https://github.com/gatsbyjs/gatsby/issues/29548)) ([348a5bf](https://github.com/gatsbyjs/gatsby/commit/348a5bf989a955345d1b958e25978ed90864cd72))

# [3.0.0-next.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.4...gatsby@3.0.0-next.5) (2021-02-17)

### Bug Fixes

- **conditional-page-builds:** track page data and not page query ([#29498](https://github.com/gatsbyjs/gatsby/issues/29498)) ([31a23d8](https://github.com/gatsbyjs/gatsby/commit/31a23d873d4b1fa76d4c432fcecfe54876c0af1d))

### Features

- **conditional-page-builds:** track ssr compilation hash ([#29482](https://github.com/gatsbyjs/gatsby/issues/29482)) ([2157ca9](https://github.com/gatsbyjs/gatsby/commit/2157ca9a08887256e22bb75e899b3964ba5d675c))
- **conditional-page-builds:** track static query results ([#29486](https://github.com/gatsbyjs/gatsby/issues/29486)) ([16d16ce](https://github.com/gatsbyjs/gatsby/commit/16d16ce0824006c25576f32772cecb8fa3101c75))
- **gatsby:** upgrade webpack to version 5 ([#29145](https://github.com/gatsbyjs/gatsby/issues/29145)) ([a7a3991](https://github.com/gatsbyjs/gatsby/commit/a7a3991ca2ad450abaacdc168e9900dad995b584))

# [3.0.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.3...gatsby@3.0.0-next.4) (2021-02-15)

### Bug Fixes

- **gatsby:** skip unions in input types ([#29479](https://github.com/gatsbyjs/gatsby/issues/29479)) ([8ef695d](https://github.com/gatsbyjs/gatsby/commit/8ef695dfae16c46e46641f2559ccc64b79aaaae2))
- drop terminal-link ([#29472](https://github.com/gatsbyjs/gatsby/issues/29472)) ([260c297](https://github.com/gatsbyjs/gatsby/commit/260c29795537bb2e5bf04f0f719b5aeadbb3cc16))

### Features

- **gatsby:** display GraphQL deprecations as CLI warnings ([#29450](https://github.com/gatsbyjs/gatsby/issues/29450)) ([bfd8c8c](https://github.com/gatsbyjs/gatsby/commit/bfd8c8c41db5fea654a9b84c54bbf63db0ce3a54))

# [3.0.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.2...gatsby@3.0.0-next.3) (2021-02-12)

### Features

- **gatsby:** support GraphQL interface inheritance ([#29427](https://github.com/gatsbyjs/gatsby/issues/29427)) ([6365768](https://github.com/gatsbyjs/gatsby/commit/63657680436f946c94589eb639fd692048c597bd))

# [3.0.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.1...gatsby@3.0.0-next.2) (2021-02-11)

### Bug Fixes

- clear tracked queries when deleting stale page-data files ([#29431](https://github.com/gatsbyjs/gatsby/issues/29431)) ([478cf68](https://github.com/gatsbyjs/gatsby/commit/478cf68f0077d95d5e46a235cf235e01fe4eaddc))

### chore

- **gatsby:** do not add \_\_typename to GraphQL query ([#29399](https://github.com/gatsbyjs/gatsby/issues/29399)) ([ddb1d27](https://github.com/gatsbyjs/gatsby/commit/ddb1d279b9d7324d23c2d73e0514ac61a0172e7e))
- **gatsby:** no implicit `childOf` with `dontInfer` ([#29369](https://github.com/gatsbyjs/gatsby/issues/29369)) ([09d6cfb](https://github.com/gatsbyjs/gatsby/commit/09d6cfbf8b641bd467e109b8c4b533777bb9dfd5))
- **gatsby:** remove noDefaultResolvers argument from infer extension ([#29367](https://github.com/gatsbyjs/gatsby/issues/29367)) ([5d0dfa2](https://github.com/gatsbyjs/gatsby/commit/5d0dfa2cf455a86ac0b215a7ee8c4c83a71a4cd4))

### Features

- **gatsby:** Remove boundActionCreators ([#29129](https://github.com/gatsbyjs/gatsby/issues/29129)) ([b1f8663](https://github.com/gatsbyjs/gatsby/commit/b1f866394345117d9eec0cb47270a18a9d2bf485))
- **gatsby:** Remove deleteNode with ID arg ([#29205](https://github.com/gatsbyjs/gatsby/issues/29205)) ([01b6123](https://github.com/gatsbyjs/gatsby/commit/01b6123d7b1fca922a4fe450651d39e6de4b96a1))
- **gatsby:** Remove deleteNodes ([#29194](https://github.com/gatsbyjs/gatsby/issues/29194)) ([7ee8025](https://github.com/gatsbyjs/gatsby/commit/7ee802580f477530a5398337f3c6bc3d5770f37d))
- **gatsby:** Remove fieldName & fieldValue from createNodeField ([#29207](https://github.com/gatsbyjs/gatsby/issues/29207)) ([a1f3cf6](https://github.com/gatsbyjs/gatsby/commit/a1f3cf67846285a9bbd59714ac0934c8bcfa4729))
- **gatsby:** Remove old touchNode signature ([#29245](https://github.com/gatsbyjs/gatsby/issues/29245)) ([0927cb0](https://github.com/gatsbyjs/gatsby/commit/0927cb007d0774bed8cf5ead3130ff6b7c3393b7))
- **gatsby:** Remove possibility to use global graphql tag for queries ([#29291](https://github.com/gatsbyjs/gatsby/issues/29291)) ([d933462](https://github.com/gatsbyjs/gatsby/commit/d933462d64f004e1a9db2d3407797d45ff8b4762))
- **gatsby:** track connections by default in runQuery and getAllNodes ([#29392](https://github.com/gatsbyjs/gatsby/issues/29392)) ([5cbc085](https://github.com/gatsbyjs/gatsby/commit/5cbc0858cef1b115289fc9a02ef531c7896f2f5d))

### BREAKING CHANGES

- **gatsby:** extensions `dateformat`, `fileByRelativePath`, `link`, `proxy` are not added automatically anymore

See also https://www.gatsbyjs.com/blog/2019-05-17-improvements-to-schema-customization#-nodefaultresolvers-and-inference-modes

- **gatsby:** We no longer add \_\_typename field to abstract types automatically. This will affect a minority of sites that were relying on this old behavior of Relay compiler to discriminate union and interface values in the runtime.

The migration is as simple as adding \_\_typename field to the query manually.

- revert whitespace changes
- **gatsby:** child[Type] and children[Type] fields are not added automatically to types with `dontInfer` directive

# [3.0.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@3.0.0-next.0...gatsby@3.0.0-next.1) (2021-02-08)

**Note:** Version bump only for package gatsby

# [3.0.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.33.0-next.1...gatsby@3.0.0-next.0) (2021-02-05)

**Note:** Version bump only for package gatsby

# [2.33.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.33.0-next.0...gatsby@2.33.0-next.1) (2021-02-04)

### Bug Fixes

- **gatsby:** use separate eslint-loader for rules that are always required ([#29317](https://github.com/gatsbyjs/gatsby/issues/29317)) ([a1543bf](https://github.com/gatsbyjs/gatsby/commit/a1543bf535871a921fdd2e9893abce064cbe5565))

# [2.33.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.32.0-next.1...gatsby@2.33.0-next.0) (2021-01-28)

### Bug Fixes

- **gatsby:** queue fs writes so event loop not overwhelmed on large sites ([#29219](https://github.com/gatsbyjs/gatsby/issues/29219)) ([7c38997](https://github.com/gatsbyjs/gatsby/commit/7c38997090f550d2b2cd902128f87fc5b19a631b))
- **gatsby:** Upgrade v8-compile-cache ([#29244](https://github.com/gatsbyjs/gatsby/issues/29244)) ([1af6e10](https://github.com/gatsbyjs/gatsby/commit/1af6e10a8c00d72f5aeebe120d06888394ca1bd9))

### Features

- **gatsby:** cache/memoize hot functions in runAPI ([#29240](https://github.com/gatsbyjs/gatsby/issues/29240)) ([e1c899f](https://github.com/gatsbyjs/gatsby/commit/e1c899f3abc54af038bd5aa3fb1c2ee79dd098fc))
- **gatsby:** distinguish total number of pages from number of written html files ([#29149](https://github.com/gatsbyjs/gatsby/issues/29149)) ([e676944](https://github.com/gatsbyjs/gatsby/commit/e676944d629eab2b92446d3dac72f9a290fa4367))

# [2.32.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.32.0-next.0...gatsby@2.32.0-next.1) (2021-01-26)

### Bug Fixes

- **eslint-config:** don't use .eslintrc and set parser settings ([#29109](https://github.com/gatsbyjs/gatsby/issues/29109)) ([5f0d214](https://github.com/gatsbyjs/gatsby/commit/5f0d2146b591a0c09576c455f2f4f7e1424f8a20))
- **gatsby:** Add missing prev location TS property for RouteUpdateArgs ([#29125](https://github.com/gatsbyjs/gatsby/issues/29125)) ([e363adb](https://github.com/gatsbyjs/gatsby/commit/e363adb642423a08f4cd70009cb41fb59a4499d6))

# [2.32.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.31.0-next.1...gatsby@2.32.0-next.0) (2021-01-18)

### Bug Fixes

- **gatsby:** Always render the body component to ensure needed head & pre/post body components are added ([#29077](https://github.com/gatsbyjs/gatsby/issues/29077)) ([e998870](https://github.com/gatsbyjs/gatsby/commit/e99887039d822d3940069c9f35655e9653b27967))
- **gatsby:** fix broken GraphQL resolver tracing ([#29015](https://github.com/gatsbyjs/gatsby/issues/29015)) ([48db6ac](https://github.com/gatsbyjs/gatsby/commit/48db6ac672220c21b4fef9b117237c73d622a344))
- **gatsby:** Use fast-refresh for React 17 ([#28930](https://github.com/gatsbyjs/gatsby/issues/28930)) ([90b6e3d](https://github.com/gatsbyjs/gatsby/commit/90b6e3d3c5526e4f3db891019969f7cfddc11958))
- **security:** update vulnerable packages, include React 17 in peerDeps ([#28545](https://github.com/gatsbyjs/gatsby/issues/28545)) ([18b5f30](https://github.com/gatsbyjs/gatsby/commit/18b5f30e367895aa5f3af46e4989b347912a0f35))

### Features

- **gatsby:** Add eslint rules to warn against bad patterns in pageTemplates (for Fast Refresh) ([#28689](https://github.com/gatsbyjs/gatsby/issues/28689)) ([9a55d12](https://github.com/gatsbyjs/gatsby/commit/9a55d1231331ebd8e1fab5496a85ba0a14dacdca))
- **gatsby:** allow to skip cache persistence ([#29047](https://github.com/gatsbyjs/gatsby/issues/29047)) ([bd5b5f7](https://github.com/gatsbyjs/gatsby/commit/bd5b5f75d3c95819c7bf6a548e4c4c98aaae5dfe))
- **gatsby:** bump opt-in % to dev-ssr to 20% ([#29075](https://github.com/gatsbyjs/gatsby/issues/29075)) ([a1921b5](https://github.com/gatsbyjs/gatsby/commit/a1921b537cda6cbfd73188fba8ea0d6a8dba3ef7))
- **gatsby-graphiql-explorer:** add support for magic fragments ([#28878](https://github.com/gatsbyjs/gatsby/issues/28878)) ([a03e862](https://github.com/gatsbyjs/gatsby/commit/a03e862fe1ec54ac6609a67528234476dfb76dfa))

# [2.31.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.31.0-next.0...gatsby@2.31.0-next.1) (2021-01-12)

### Bug Fixes

- **gatsby:** fix stale query results on data updates ([#28986](https://github.com/gatsbyjs/gatsby/issues/28986)) ([811c2a8](https://github.com/gatsbyjs/gatsby/commit/811c2a839c44999967b5f081cc1998fc4a347e85))
- **gatsby:** rewrite a spread that would break at scale ([#28910](https://github.com/gatsbyjs/gatsby/issues/28910)) ([638ac0a](https://github.com/gatsbyjs/gatsby/commit/638ac0af798de9727ec2488f201b7c578464c916))
- **gatsby:** show stack trace for non-graphql errors ([#28888](https://github.com/gatsbyjs/gatsby/issues/28888)) ([1769fc3](https://github.com/gatsbyjs/gatsby/commit/1769fc361b5d3f664ec71bd5ecf4f22b85bfe5a2))
- **gatsby,gatsby-admin:** Pin socket.io version to 2.3.0 ([#28885](https://github.com/gatsbyjs/gatsby/issues/28885)) ([247b1dc](https://github.com/gatsbyjs/gatsby/commit/247b1dc0441fdade52a5ff7a71de8c9340ee05fd))

### Features

- **gatsby:** Partially release develop SSR to 5% ([#28844](https://github.com/gatsbyjs/gatsby/issues/28844)) ([6b8cd5d](https://github.com/gatsbyjs/gatsby/commit/6b8cd5d69bc8a5ad63413756eb71ff3e739230e5))

### Performance Improvements

- **develop:** don't use debug config for bluebird ([#28957](https://github.com/gatsbyjs/gatsby/issues/28957)) ([125f571](https://github.com/gatsbyjs/gatsby/commit/125f571880190b55d6e9c03672b6d79e854dd4bd))
- **gatsby:** do not call and iterate getAllNodes(File) for each file ([#28891](https://github.com/gatsbyjs/gatsby/issues/28891)) ([a455a23](https://github.com/gatsbyjs/gatsby/commit/a455a2396c97997dca6fb0797e845de0acebd2f6))

# [2.31.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.8...gatsby@2.31.0-next.0) (2020-12-29)

### Features

- **gatsby:** use production React for dev-ssr when CI=true ([#28728](https://github.com/gatsbyjs/gatsby/issues/28728)) ([bd6b899](https://github.com/gatsbyjs/gatsby/commit/bd6b899fdb22748c2ecc016643ed39e32d014a6b))

# [2.30.0-next.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.7...gatsby@2.30.0-next.8) (2020-12-29)

### Bug Fixes

- **gatsby:** print childOf directive for implicit child fields ([#28483](https://github.com/gatsbyjs/gatsby/issues/28483)) ([146b197](https://github.com/gatsbyjs/gatsby/commit/146b1975cc83f862c883b27415b914e152c708e8))
- **gatsby:** use correct stageLabel instead of `undefined` ([#28701](https://github.com/gatsbyjs/gatsby/issues/28701)) ([a77e1d8](https://github.com/gatsbyjs/gatsby/commit/a77e1d80d5b3a75979760d3be2005742feb09266))

# [2.30.0-next.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.6...gatsby@2.30.0-next.7) (2020-12-18)

### Bug Fixes

- **gatsby:** always add both `childField` and `childrenField` in GraphQL ([#28656](https://github.com/gatsbyjs/gatsby/issues/28656)) ([739df13](https://github.com/gatsbyjs/gatsby/commit/739df134adbffddab58d9f85032579169362a348))
- **gatsby:** remove redundant dispatch of query extraction error ([#28676](https://github.com/gatsbyjs/gatsby/issues/28676)) ([1d7dc76](https://github.com/gatsbyjs/gatsby/commit/1d7dc76a18de379e0004bd62a26d7630e0a060fe))

# [2.30.0-next.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.5...gatsby@2.30.0-next.6) (2020-12-17)

**Note:** Version bump only for package gatsby

# [2.30.0-next.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.4...gatsby@2.30.0-next.5) (2020-12-17)

**Note:** Version bump only for package gatsby

# [2.30.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.3...gatsby@2.30.0-next.4) (2020-12-17)

### Bug Fixes

- **gatsby:** Do not activate inspect if already active ([#28643](https://github.com/gatsbyjs/gatsby/issues/28643)) ([f4e90b6](https://github.com/gatsbyjs/gatsby/commit/f4e90b61c8826dca7f9e07727c8cd7179c51a8a0))

### Features

- **gatsby:** decouple html activities ([#28648](https://github.com/gatsbyjs/gatsby/issues/28648)) ([140d123](https://github.com/gatsbyjs/gatsby/commit/140d12375e61f76238e7d1b8073eaf897918284a))

# [2.30.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.2...gatsby@2.30.0-next.3) (2020-12-16)

### Bug Fixes

- **gatsby:** Only set auto optin flags if not in config ([#28627](https://github.com/gatsbyjs/gatsby/issues/28627)) ([b81e6bd](https://github.com/gatsbyjs/gatsby/commit/b81e6bdb70fbda4f02739728f79b12c166b1a188))
- **gatsby:** require gatsby-config.js before accessing process.env ([#28572](https://github.com/gatsbyjs/gatsby/issues/28572)) ([b3f11ed](https://github.com/gatsbyjs/gatsby/commit/b3f11ed1b48113142333ccb57124fd5dc625aac5))

### Features

- **gatsby:** Add AVIF file support to image loader in webpack config ([#28638](https://github.com/gatsbyjs/gatsby/issues/28638)) ([1a59200](https://github.com/gatsbyjs/gatsby/commit/1a592001eecee463b25a0ec599c2223956066905))
- **gatsby:** improve refresh endpoint output ([#28621](https://github.com/gatsbyjs/gatsby/issues/28621)) ([deb4e1e](https://github.com/gatsbyjs/gatsby/commit/deb4e1ebdfbf4c9e9f4516bb6c24afbaf61e81ff))

# [2.30.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.1...gatsby@2.30.0-next.2) (2020-12-15)

**Note:** Version bump only for package gatsby

# [2.30.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.30.0-next.0...gatsby@2.30.0-next.1) (2020-12-11)

### Bug Fixes

- **gatsby:** correct opt-in percentage for QUERY_ON_DEMAND and LAZY_IMAGES ([#28579](https://github.com/gatsbyjs/gatsby/issues/28579)) ([c21dac9](https://github.com/gatsbyjs/gatsby/commit/c21dac9e8cf97093e00889e850c5a441aef46bda))

# [2.30.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.29.0-next.4...gatsby@2.30.0-next.0) (2020-12-10)

### Bug Fixes

- **gatsby:** Avoid undefined object errors ([#28554](https://github.com/gatsbyjs/gatsby/issues/28554)) ([39995ae](https://github.com/gatsbyjs/gatsby/commit/39995ae008d72ff17ab57bb91cbb625ed64e39f5))
- **gatsby:** correct GraphQL warning text ([#28563](https://github.com/gatsbyjs/gatsby/issues/28563)) ([2bb4214](https://github.com/gatsbyjs/gatsby/commit/2bb4214d36616ae593a8a82d63102dca2d5e44e6))
- **gatsby:** show multiple invites together & at end where people are more likely to see them ([#28450](https://github.com/gatsbyjs/gatsby/issues/28450)) ([7e734cc](https://github.com/gatsbyjs/gatsby/commit/7e734cc5716e6fcc6c1bdc5806f492ad5414b7e9))
- **query-on-demand:** don't resolve get-page-data if query is marked as dirty ([#28535](https://github.com/gatsbyjs/gatsby/issues/28535)) ([56c2b4c](https://github.com/gatsbyjs/gatsby/commit/56c2b4cd3983eb1d540d2f456c93332f9757f863))

### Features

- **gatsby:** loading indicator for query-on-demand ([#28562](https://github.com/gatsbyjs/gatsby/issues/28562)) ([1b97f5f](https://github.com/gatsbyjs/gatsby/commit/1b97f5f44b715704ebaff2a714bc81116189aec3))
- **gatsby:** track how long query-on-demand querying takes ([#28544](https://github.com/gatsbyjs/gatsby/issues/28544)) ([fbf9694](https://github.com/gatsbyjs/gatsby/commit/fbf96942efb920a883ea679972461140d3b770ec))

### Performance Improvements

- **gatsby:** do not force resolvers to be async ([#28525](https://github.com/gatsbyjs/gatsby/issues/28525)) ([cf06435](https://github.com/gatsbyjs/gatsby/commit/cf064355d77a9958b5e3240945b46729dfdac538))

# [2.29.0-next.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.29.0-next.3...gatsby@2.29.0-next.4) (2020-12-08)

### Bug Fixes

- **gatsby:** better text for missing inferred extension ([#28530](https://github.com/gatsbyjs/gatsby/issues/28530)) ([298110c](https://github.com/gatsbyjs/gatsby/commit/298110c28c7635114cab300f44180fd641ffce36))
- **gatsby:** do not fail the build when eslint loader is removed ([#28494](https://github.com/gatsbyjs/gatsby/issues/28494)) ([b3c171f](https://github.com/gatsbyjs/gatsby/commit/b3c171f0d6dd5a91cdc9ecbe73606b503bd40bda))
- **gatsby:** improve deprecation text for missing childOf directive ([#28532](https://github.com/gatsbyjs/gatsby/issues/28532)) ([f733f4e](https://github.com/gatsbyjs/gatsby/commit/f733f4e941198f4ac4378f141d87f9ad6cfec6a0))
- **gatsby:** Wait for jobs to complete in onPostBuild ([#28534](https://github.com/gatsbyjs/gatsby/issues/28534)) ([98f22e7](https://github.com/gatsbyjs/gatsby/commit/98f22e702ee3defefd8e99d49aa50b080bbe0d6f))

### Features

- **gatsby:** add preload headers for critical resources so those can started fetching before common.js is fetched ([#28460](https://github.com/gatsbyjs/gatsby/issues/28460)) ([b4a76f5](https://github.com/gatsbyjs/gatsby/commit/b4a76f581d1f4e0f1f7f61f96eedd94703468116))
- **gatsby:** Expose plugin-specific refresh endpoint in gatsby-serve ([#27931](https://github.com/gatsbyjs/gatsby/issues/27931)) ([903439b](https://github.com/gatsbyjs/gatsby/commit/903439bcb4c909c1881cb3139b7545b161ea580b))

# [2.29.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.29.0-next.2...gatsby@2.29.0-next.3) (2020-12-04)

### Bug Fixes

- **gatsby:** Add bodyComponent to replaceRenderer args ([#28456](https://github.com/gatsbyjs/gatsby/issues/28456)) ([9a77810](https://github.com/gatsbyjs/gatsby/commit/9a77810b1f2f0a529dd13760d0a7b73b2b50fd81))

# [2.29.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.29.0-next.1...gatsby@2.29.0-next.2) (2020-12-03)

### Bug Fixes

- PRESERVE_WEBPACK_CACHE notice should actually show after 30 seconds ([#28427](https://github.com/gatsbyjs/gatsby/issues/28427)) ([95b4fdd](https://github.com/gatsbyjs/gatsby/commit/95b4fdd7a7ce2032a658a9cc14e6bcb219fb2bc2))

### Features

- **gatsby:** Add new caching clearing behavior for webpack/file downloads behind flags ([#28334](https://github.com/gatsbyjs/gatsby/issues/28334)) ([f57d590](https://github.com/gatsbyjs/gatsby/commit/f57d590142a67bd8c79c7805d3298f316198fde9))

# [2.29.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.29.0-next.0...gatsby@2.29.0-next.1) (2020-12-01)

### Bug Fixes

- **develop:** emit stale page data messages when staticQueryHashes change ([#28349](https://github.com/gatsbyjs/gatsby/issues/28349)) ([5096e90](https://github.com/gatsbyjs/gatsby/commit/5096e90f3af9490f910a47331ac42efa2edfd9e2))
- **gatsby:** Add `FAST_REFRESH` config flag ([#28409](https://github.com/gatsbyjs/gatsby/issues/28409)) ([ce090e5](https://github.com/gatsbyjs/gatsby/commit/ce090e5e058ff4927e51aaadba1a834f9f5c4e9f))
- **gatsby:** correct tracing for GraphQL queries ([#28415](https://github.com/gatsbyjs/gatsby/issues/28415)) ([4e50d5c](https://github.com/gatsbyjs/gatsby/commit/4e50d5c8008e1608138b2cecabd00b014bc90bf9))
- **gatsby:** fix telemetryId for LAZY_IMAGES ([#28340](https://github.com/gatsbyjs/gatsby/issues/28340)) ([4998303](https://github.com/gatsbyjs/gatsby/commit/49983036de2bf7a61fe654b37fb8b3fe7d639153))
- **gatsby:** handle in dev-ssr when a page is deleted ([#28325](https://github.com/gatsbyjs/gatsby/issues/28325)) ([a9f9a23](https://github.com/gatsbyjs/gatsby/commit/a9f9a23705edaf393466b30bc89546b59de59158))
- **gatsby:** move starting dev-ssr listener inside function & only init listeners once ([#28395](https://github.com/gatsbyjs/gatsby/issues/28395)) ([3ce476b](https://github.com/gatsbyjs/gatsby/commit/3ce476b1eac97aedd16f9d150cd6a81f36255380))
- **gatsby:** re-render route when location state changes ([#28346](https://github.com/gatsbyjs/gatsby/issues/28346)) ([3ccaec8](https://github.com/gatsbyjs/gatsby/commit/3ccaec855b376b267c02009f51772c237620088d))
- **gatsby:** scroll restoration issue in browser API ([#27384](https://github.com/gatsbyjs/gatsby/issues/27384)) ([4a7a324](https://github.com/gatsbyjs/gatsby/commit/4a7a324553669a72445a427ed8cc30e812f38bd1))

### Features

- **gatsby:** people who are using a flag, invite them to try out other flags ([#28338](https://github.com/gatsbyjs/gatsby/issues/28338)) ([9c8f788](https://github.com/gatsbyjs/gatsby/commit/9c8f78842784c6882953d2f5c72dd71d61ba3e29))
- **gatsby:** Track the use of flags in gatsby-config.js ([#28337](https://github.com/gatsbyjs/gatsby/issues/28337)) ([3e056d1](https://github.com/gatsbyjs/gatsby/commit/3e056d1ab51cffb8fbf15c7b932fd4f11e1db545))

# [2.29.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.28.0-next.2...gatsby@2.29.0-next.0) (2020-11-26)

### Bug Fixes

- **gatsby:** Actually handle timeout while waiting for page component to be bundled ([#28302](https://github.com/gatsbyjs/gatsby/issues/28302)) ([7846fd4](https://github.com/gatsbyjs/gatsby/commit/7846fd4a591094d57bd24a7f0927b97725caf3ed))
- **gatsby:** do not ignore source file changes during recompilation ([#28237](https://github.com/gatsbyjs/gatsby/issues/28237)) ([4148877](https://github.com/gatsbyjs/gatsby/commit/41488778ddcb102a5147b7acfb9631565ede958e))
- **gatsby:** fix materialization edge case ([#28244](https://github.com/gatsbyjs/gatsby/issues/28244)) ([807589b](https://github.com/gatsbyjs/gatsby/commit/807589bf759b01fe5a5235282bbcdc5a9a969265))

### Features

- **gatsby:** Add preliminary fast-refresh integration ([#26664](https://github.com/gatsbyjs/gatsby/issues/26664)) ([613f5c7](https://github.com/gatsbyjs/gatsby/commit/613f5c791fd059e8a64eeaa81993d1f9f14bec53))
- **gatsby:** make dev ssr bundling lazy ([#28149](https://github.com/gatsbyjs/gatsby/issues/28149)) ([70b81a6](https://github.com/gatsbyjs/gatsby/commit/70b81a6e825c583387728c02d83a70e0d4e16072))
- **gatsby-plugin-sharp:** add experimental opt-in lazy image processing mode for `gatsby develop` ([#28288](https://github.com/gatsbyjs/gatsby/issues/28288)) ([cc68a1f](https://github.com/gatsbyjs/gatsby/commit/cc68a1f435e6fc923908d7a2b84f52dc2a999f4d))

# [2.28.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.28.0-next.1...gatsby@2.28.0-next.2) (2020-11-23)

### Features

- **gatsby:** bump % that get invited to try dev_ssr to 5% from 1% ([#28232](https://github.com/gatsbyjs/gatsby/issues/28232)) ([2b494c3](https://github.com/gatsbyjs/gatsby/commit/2b494c34b5a8bb798fa1134a8a482165afc72fce))
- **gatsby:** track usage of GATSBY_EXPERIMENTAL_FAST_DEV ([#28223](https://github.com/gatsbyjs/gatsby/issues/28223)) ([849b3bd](https://github.com/gatsbyjs/gatsby/commit/849b3bd4ec871ecb7596819940f8004ce9ec3793))

# [2.28.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.28.0-next.0...gatsby@2.28.0-next.1) (2020-11-22)

### Bug Fixes

- **gatsby:** get-page-data should timeout gracefully ([#28131](https://github.com/gatsbyjs/gatsby/issues/28131)) ([c517b60](https://github.com/gatsbyjs/gatsby/commit/c517b605b7572171607be140175be279748de7fa))
- **gatsby:** pull out a few bug fixes from https://github.com/gatsbyjs/gatsby/pull/28149/ ([#28186](https://github.com/gatsbyjs/gatsby/issues/28186)) ([f9fd11d](https://github.com/gatsbyjs/gatsby/commit/f9fd11d319b3ec097cce6378ccedb86a7f2f8cc8))

### Features

- **gatsby:** add telemetry for usage of lazy devjs bundling ([#28147](https://github.com/gatsbyjs/gatsby/issues/28147)) ([48f2b2d](https://github.com/gatsbyjs/gatsby/commit/48f2b2d76af060b7d9d83d28be5c4f6d069133d5))
- **gatsby:** enable all dev improvements with one env var ([#28166](https://github.com/gatsbyjs/gatsby/issues/28166)) ([158ceb7](https://github.com/gatsbyjs/gatsby/commit/158ceb7d404967920613c5e8e4f57520b049167d))
- **gatsby:** invite people with long page query running to try out query on demand feature ([#28181](https://github.com/gatsbyjs/gatsby/issues/28181)) ([413888b](https://github.com/gatsbyjs/gatsby/commit/413888b61ad3014b9cd3fc9d846b5382a1ec82f9))

# [2.28.0-next.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.27.0-next.1...gatsby@2.28.0-next.0) (2020-11-18)

### Bug Fixes

- **gatsby:** fix race condition in cache lock ([#28097](https://github.com/gatsbyjs/gatsby/issues/28097)) ([5b2d9b6](https://github.com/gatsbyjs/gatsby/commit/5b2d9b6343019f458e1c1f1d5c38b9b43ff47c32))
- **gatsby:** rename env var for lazy dev bundling to make consistent with other experiments ([#28150](https://github.com/gatsbyjs/gatsby/issues/28150)) ([9e3ceec](https://github.com/gatsbyjs/gatsby/commit/9e3ceeccf2e6821429c7ae808588956fe7e3ef67))

### Features

- **develop:** add query on demand behind feature flag ([#28127](https://github.com/gatsbyjs/gatsby/issues/28127)) ([088eef4](https://github.com/gatsbyjs/gatsby/commit/088eef4fe125d03427712c557fbf19e96034d66d))
- **gatsby:** invite (1%) of Gatsby users to try out develop ssr ([#28139](https://github.com/gatsbyjs/gatsby/issues/28139)) ([a612f26](https://github.com/gatsbyjs/gatsby/commit/a612f26cab94a7672f6c63067368ec6efc49ec49))
- **gatsby:** invite people with long develop bundling times to try the lazy dev js bundling feature ([#28116](https://github.com/gatsbyjs/gatsby/issues/28116)) ([a737ea7](https://github.com/gatsbyjs/gatsby/commit/a737ea77ded04e0896d43ec233589b1dd8be7e63))
- **gatsby:** lazy bundle page components in dev server ([#27884](https://github.com/gatsbyjs/gatsby/issues/27884)) ([04349a0](https://github.com/gatsbyjs/gatsby/commit/04349a042f9106a88b7a9054c0e1c4dc70469d1f))
- **gatsby:** SSR pages during development ([#27432](https://github.com/gatsbyjs/gatsby/issues/27432)) ([23da2c3](https://github.com/gatsbyjs/gatsby/commit/23da2c3fb2e16b7e3fe1e15c19decd799000a212))
- add utility to show experiment invitation notices ([#28120](https://github.com/gatsbyjs/gatsby/issues/28120)) ([195d623](https://github.com/gatsbyjs/gatsby/commit/195d6233e2615074e2e5ce95d05e09d264ac1066))

### Performance Improvements

- **gatsby:** fix performance regression with query dependency cleaning ([#28032](https://github.com/gatsbyjs/gatsby/issues/28032)) ([de5517b](https://github.com/gatsbyjs/gatsby/commit/de5517b9db0b86c8b1729cb67c570a105596a97b))

# [2.27.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.27.0-next.0...gatsby@2.27.0-next.1) (2020-11-16)

### Bug Fixes

- **gatsby:** allow unknown plugin options ([#27938](https://github.com/gatsbyjs/gatsby/issues/27938)) ([412b523](https://github.com/gatsbyjs/gatsby/commit/412b523fcb2909eabc3fae00f4bba5c3b59cc466))
- **gatsby:** don't hide original error if stack-trace point to not existing file ([#27953](https://github.com/gatsbyjs/gatsby/issues/27953)) ([5e2b3ee](https://github.com/gatsbyjs/gatsby/commit/5e2b3eeb4af46a203de80fa8ce45774f9c6c3fa5))

### Features

- **create-gatsby:** Add create-gatsby ([#27703](https://github.com/gatsbyjs/gatsby/issues/27703)) ([2371fd5](https://github.com/gatsbyjs/gatsby/commit/2371fd584d6824444d93f8667c45421c34aa5f54)), closes [#27801](https://github.com/gatsbyjs/gatsby/issues/27801) [#27995](https://github.com/gatsbyjs/gatsby/issues/27995)
- **develop:** add explicit express handler for page-data requests ([#27882](https://github.com/gatsbyjs/gatsby/issues/27882)) ([3d0de4a](https://github.com/gatsbyjs/gatsby/commit/3d0de4a93f23271417028843297b78a0d9450c3f))

### Performance Improvements

- **gatsby:** pull in cache lib and change lock from fs to mem ([#27873](https://github.com/gatsbyjs/gatsby/issues/27873)) ([84aae96](https://github.com/gatsbyjs/gatsby/commit/84aae96434b2432420dbdb851477c67c30b6c732))

### Reverts

- Revert "fix(gatsby): refresh browser when receiving update and runtime errored (#27467)" (#28034) ([076b59f](https://github.com/gatsbyjs/gatsby/commit/076b59fdd259be238d79bbbcda7fdb9c578adcd6)), closes [#27467](https://github.com/gatsbyjs/gatsby/issues/27467) [#28034](https://github.com/gatsbyjs/gatsby/issues/28034)

# [2.26.0-next.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.26.0-next.2...gatsby@2.26.0-next.3) (2020-11-10)

### Bug Fixes

- **gatsby:** account for edge case when payload of DELETE_NODE is undefined ([#27929](https://github.com/gatsbyjs/gatsby/issues/27929)) ([d3471e0](https://github.com/gatsbyjs/gatsby/commit/d3471e08543536895016ccb023045ffa25275873))
- **gatsby:** Update TS types to allow Node 'parent' to be nullable ([#26570](https://github.com/gatsbyjs/gatsby/issues/26570)) ([90bb57b](https://github.com/gatsbyjs/gatsby/commit/90bb57b51a41b40200239471df6b66d9fcc730c2))
- **gatsby-transformer-remark:** wait for cache promises before returning ([#27871](https://github.com/gatsbyjs/gatsby/issues/27871)) ([071d50d](https://github.com/gatsbyjs/gatsby/commit/071d50d665c6f5542e29286eaef4dc54a61bb4d8))

### Features

- File System Route API - General Availability ([#27424](https://github.com/gatsbyjs/gatsby/issues/27424)) ([07eeb2e](https://github.com/gatsbyjs/gatsby/commit/07eeb2ec35deadd212f009ce26f55f38d8304b11))

# [2.26.0-next.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.26.0-next.1...gatsby@2.26.0-next.2) (2020-11-09)

### Features

- **gatsby-cli:** Augment plugin errors with plugin name ([#27435](https://github.com/gatsbyjs/gatsby/issues/27435)) ([700d245](https://github.com/gatsbyjs/gatsby/commit/700d2454c824dcfbf7535a40df5032e1dc208c0c))

# [2.26.0-next.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.26.0-next.0...gatsby@2.26.0-next.1) (2020-11-05)

### Bug Fixes

- **docs:** Update documentation for createPages ([#27735](https://github.com/gatsbyjs/gatsby/issues/27735)) ([27c3083](https://github.com/gatsbyjs/gatsby/commit/27c3083a8dccbab06f72f7259ddf6a79b7043bbd))
- **gatsby:** Remove version annotation in createPages ([#27851](https://github.com/gatsbyjs/gatsby/issues/27851)) ([b57e41f](https://github.com/gatsbyjs/gatsby/commit/b57e41f04616a6a7da72213a57e33b9e361c56c0))

## [2.25.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.25.0...gatsby@2.25.1) (2020-11-02)

**Note:** Version bump only for package gatsby

# [2.25.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.92...gatsby@2.25.0) (2020-11-02)

### Features

- **gatsby:** release plugin option validation ([#27437](https://github.com/gatsbyjs/gatsby/issues/27437)) ([41ae1c0](https://github.com/gatsbyjs/gatsby/commit/41ae1c07ad9919655782ef17feed8cf4f14f12d8))

## [2.24.92](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.91...gatsby@2.24.92) (2020-11-02)

### Bug Fixes

- **gatsby:** include graphql type definition in published files ([#27646](https://github.com/gatsbyjs/gatsby/issues/27646)) ([875b214](https://github.com/gatsbyjs/gatsby/commit/875b214a7dd58d1e532a605d45906e5942a4e2c5))
- **gatsby:** print real plugin loading error in verbose ([#27664](https://github.com/gatsbyjs/gatsby/issues/27664)) ([c947568](https://github.com/gatsbyjs/gatsby/commit/c9475689615eb1b4e34f599e80c36bcef76ee77a))
- **gatsby:** purge jobsV2 results when cache is corrupt ([#27700](https://github.com/gatsbyjs/gatsby/issues/27700)) ([a6ecfb2](https://github.com/gatsbyjs/gatsby/commit/a6ecfb2b01d761e8a3612b8ea132c698659923d9))
- **gatsby:** show theme that has faulty config ([#27708](https://github.com/gatsbyjs/gatsby/issues/27708)) ([d7d1b97](https://github.com/gatsbyjs/gatsby/commit/d7d1b97e69cc5fa8030722a792a56e6d30937d2d))

### Features

- **gatsby:** allow configuration of default socket type ([#27734](https://github.com/gatsbyjs/gatsby/issues/27734)) ([f43a6bd](https://github.com/gatsbyjs/gatsby/commit/f43a6bd8ab3226afdfa79519d477c2a43f86e66d))
- Add "gatsby plugin" command ([#27725](https://github.com/gatsbyjs/gatsby/issues/27725)) ([5869cc5](https://github.com/gatsbyjs/gatsby/commit/5869cc5ab2189b257944a4c3f99af564be81ea80))

## [2.24.91](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.90...gatsby@2.24.91) (2020-10-28)

### Bug Fixes

- **gatsby:** fix subplugin validation ([#27616](https://github.com/gatsbyjs/gatsby/issues/27616)) ([65deab8](https://github.com/gatsbyjs/gatsby/commit/65deab8b47802262d19f7577ba5db302a2cd22e6))

## [2.24.90](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.89...gatsby@2.24.90) (2020-10-28)

### Performance Improvements

- **gatsby:** cache `createNodeId` locally ([#27686](https://github.com/gatsbyjs/gatsby/issues/27686)) ([5acfb60](https://github.com/gatsbyjs/gatsby/commit/5acfb605e971a6296a4dd588eb5a96031f9948cd))

## [2.24.89](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.88...gatsby@2.24.89) (2020-10-27)

### Bug Fixes

- **gatsby:** leak less in chokidar listeners ([#27685](https://github.com/gatsbyjs/gatsby/issues/27685)) ([e0a3645](https://github.com/gatsbyjs/gatsby/commit/e0a3645d7c788b7c589d69187840305a650678f7))

## [2.24.88](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.87...gatsby@2.24.88) (2020-10-27)

### Bug Fixes

- **gatsby:** add missing printTypeDefinitions ([#27670](https://github.com/gatsbyjs/gatsby/issues/27670)) ([2da94bf](https://github.com/gatsbyjs/gatsby/commit/2da94bfcd612d10b0816e38a95e43651986fd94b))
- **gatsby:** better heuristic for automatic cache purging ([#27682](https://github.com/gatsbyjs/gatsby/issues/27682)) ([a5665d2](https://github.com/gatsbyjs/gatsby/commit/a5665d28f585c7f8727e2bbaccb4ab0fffeaa8e7))

## [2.24.87](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.86...gatsby@2.24.87) (2020-10-26)

**Note:** Version bump only for package gatsby

## [2.24.86](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.85...gatsby@2.24.86) (2020-10-26)

### Features

- **gatsby:** disable automatic by default ([#27615](https://github.com/gatsbyjs/gatsby/issues/27615)) ([18c182a](https://github.com/gatsbyjs/gatsby/commit/18c182a574475c9c06dbbeb7ddae27f5cb008fe9))

## [2.24.85](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.84...gatsby@2.24.85) (2020-10-22)

### Bug Fixes

- **gatsby:** trigger location effects in navigation ([#27594](https://github.com/gatsbyjs/gatsby/issues/27594)) ([642eeb1](https://github.com/gatsbyjs/gatsby/commit/642eeb10a56a0618f2f0c608a035293cd3d5269f))

## [2.24.84](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.83...gatsby@2.24.84) (2020-10-21)

### Bug Fixes

- duplicate types to solve circular dependency ([#27578](https://github.com/gatsbyjs/gatsby/issues/27578)) ([029ec48](https://github.com/gatsbyjs/gatsby/commit/029ec489a271ddeb7ad3fa174bd536c1b38db246))

## [2.24.83](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.82...gatsby@2.24.83) (2020-10-20)

### Bug Fixes

- **gatsby:** Handle double prefix case for `extendErrorIdWithPluginName` ([#27547](https://github.com/gatsbyjs/gatsby/issues/27547)) ([b4d8342](https://github.com/gatsbyjs/gatsby/commit/b4d8342008de8fac199e3a524130573ba81ed354))

## [2.24.82](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.81...gatsby@2.24.82) (2020-10-19)

### Bug Fixes

- **gatsby:** notify when Gatsby cache is incomplete ([#27549](https://github.com/gatsbyjs/gatsby/issues/27549)) ([2d6a153](https://github.com/gatsbyjs/gatsby/commit/2d6a1535ca2fa45bc6821d3273c32e18f66913fc))

## [2.24.81](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.80...gatsby@2.24.81) (2020-10-19)

### Features

- **gatsby-plugin-utils:** save validation resulting value to plugin options ([#27381](https://github.com/gatsbyjs/gatsby/issues/27381)) ([0073fb1](https://github.com/gatsbyjs/gatsby/commit/0073fb167e7ccddefbff8872b5b9bd488660804d))

## [2.24.80](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.79...gatsby@2.24.80) (2020-10-16)

### Bug Fixes

- **gatsby:** refresh browser when receiving update and runtime errored ([#27467](https://github.com/gatsbyjs/gatsby/issues/27467)) ([f227e85](https://github.com/gatsbyjs/gatsby/commit/f227e85728168d104ed0a7982823923dcd3bba62))

### Performance Improvements

- **gatsby:** test sync before calling onCreateNode ([#27442](https://github.com/gatsbyjs/gatsby/issues/27442)) ([6400383](https://github.com/gatsbyjs/gatsby/commit/6400383287db9967a7124df7fb0d096408372b95))

## [2.24.79](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.78...gatsby@2.24.79) (2020-10-16)

### Bug Fixes

- **gatsby:** add runtime check for react 17 ([#27468](https://github.com/gatsbyjs/gatsby/issues/27468)) ([239d539](https://github.com/gatsbyjs/gatsby/commit/239d539b76421f210a0db901786021ac45a42ac7))

## [2.24.78](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.77...gatsby@2.24.78) (2020-10-15)

### Features

- **gatsby-plugin-typescript:** Add schema ([#27361](https://github.com/gatsbyjs/gatsby/issues/27361)) ([072ef6c](https://github.com/gatsbyjs/gatsby/commit/072ef6c992168c89505143670013d5d8147f4ab4))

## [2.24.77](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.76...gatsby@2.24.77) (2020-10-14)

**Note:** Version bump only for package gatsby

## [2.24.76](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.75...gatsby@2.24.76) (2020-10-13)

### Bug Fixes

- **gatsby:** Error context for 11328 ([#27419](https://github.com/gatsbyjs/gatsby/issues/27419)) ([3dcde6e](https://github.com/gatsbyjs/gatsby/commit/3dcde6e9973ff36143d1e43f3f2d00d7016c966c))
- **gatsby:** materialization should always use resolver when defined ([#27411](https://github.com/gatsbyjs/gatsby/issues/27411)) ([1ceb0c3](https://github.com/gatsbyjs/gatsby/commit/1ceb0c3ba836d027632e51822f2acb4010275b63))

## [2.24.75](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.74...gatsby@2.24.75) (2020-10-13)

**Note:** Version bump only for package gatsby

## [2.24.74](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.73...gatsby@2.24.74) (2020-10-12)

### Bug Fixes

- **gatsby:** Make pluginOptionsSchema optional ([#27397](https://github.com/gatsbyjs/gatsby/issues/27397)) ([a67fb02](https://github.com/gatsbyjs/gatsby/commit/a67fb0212ac9bd94964d8d5c256beebe6cb6f253)), closes [#27242](https://github.com/gatsbyjs/gatsby/issues/27242)
- **gatsby:** wait for extracted query enqueuing before running queries ([#27408](https://github.com/gatsbyjs/gatsby/issues/27408)) ([f50093e](https://github.com/gatsbyjs/gatsby/commit/f50093e90c07a9447f72c968a349711806b4f897))
- **gatsby-plugin-google-analytics:** remove required on trackingId ([#27398](https://github.com/gatsbyjs/gatsby/issues/27398)) ([3518d10](https://github.com/gatsbyjs/gatsby/commit/3518d10c3541277a3ba2da5bb099a54d02179257))
- lint ([#27371](https://github.com/gatsbyjs/gatsby/issues/27371)) ([6b37713](https://github.com/gatsbyjs/gatsby/commit/6b3771309459f76071ea239cdd62fda902836d80))

## [2.24.73](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.72...gatsby@2.24.73) (2020-10-09)

**Note:** Version bump only for package gatsby

## [2.24.72](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.71...gatsby@2.24.72) (2020-10-08)

**Note:** Version bump only for package gatsby

## [2.24.71](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.70...gatsby@2.24.71) (2020-10-08)

**Note:** Version bump only for package gatsby

## [2.24.70](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.69...gatsby@2.24.70) (2020-10-08)

### Bug Fixes

- **gatsby:** route lifecycle ordering ([#27261](https://github.com/gatsbyjs/gatsby/issues/27261)) ([b64f89e](https://github.com/gatsbyjs/gatsby/commit/b64f89e4fc22fdfbe8c7edf670a4b25d757db7a3))

### Features

- **gatsby,gatsby-cli:** Pass an errorMap to reporter.error ([#27176](https://github.com/gatsbyjs/gatsby/issues/27176)) ([56402db](https://github.com/gatsbyjs/gatsby/commit/56402dbb26aa56f8f1d69a0d4e2d079efccec669))

### Performance Improvements

- **redirect:** minified redirect file size ([#27160](https://github.com/gatsbyjs/gatsby/issues/27160)) ([41f0881](https://github.com/gatsbyjs/gatsby/commit/41f08814fa016683d9bb1c1aa064e6e9519d38fc))

## [2.24.69](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.68...gatsby@2.24.69) (2020-10-07)

### Bug Fixes

- **gatsby:** support `--https` develop ([#27302](https://github.com/gatsbyjs/gatsby/issues/27302)) ([17cdc22](https://github.com/gatsbyjs/gatsby/commit/17cdc223ed2b9ce362f2718dfaac7f21a3a5b60e)), closes [#27294](https://github.com/gatsbyjs/gatsby/issues/27294)

### Features

- **gatsby:** plugin option validation ([#27242](https://github.com/gatsbyjs/gatsby/issues/27242)) ([9b01ca7](https://github.com/gatsbyjs/gatsby/commit/9b01ca7926efa1c4c6d58b33a137c2f0a0ef99b7))

## [2.24.68](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.67...gatsby@2.24.68) (2020-10-06)

**Note:** Version bump only for package gatsby

## [2.24.67](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.66...gatsby@2.24.67) (2020-10-01)

### Bug Fixes

- **gatsby:** retry socket when connection closes ([#27060](https://github.com/gatsbyjs/gatsby/issues/27060)) ([8d62b2c](https://github.com/gatsbyjs/gatsby/commit/8d62b2c21acbac64c715e957b50aeaec1b906fac))

## [2.24.66](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.65...gatsby@2.24.66) (2020-09-28)

### Bug Fixes

- **gatsby:** PageProps TS type: add `params` ([#26974](https://github.com/gatsbyjs/gatsby/issues/26974)) ([026d49d](https://github.com/gatsbyjs/gatsby/commit/026d49dee032c98f87fa88c85b4f8a1393258b28))
- **gatsby:** set proper cacheIdentifier for babel ([#26809](https://github.com/gatsbyjs/gatsby/issues/26809)) ([e28d9ba](https://github.com/gatsbyjs/gatsby/commit/e28d9ba3a70ad5936dc6ee171da38c2caf192ae7))

## [2.24.65](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.64...gatsby@2.24.65) (2020-09-24)

### Bug Fixes

- **build:** remove stale page-data files ([#26937](https://github.com/gatsbyjs/gatsby/issues/26937)) ([dfe9fb0](https://github.com/gatsbyjs/gatsby/commit/dfe9fb00fa9d1bc5dce740c49901a6398638b742))
- **gatsby:** Recognise null pages as not found ([#27003](https://github.com/gatsbyjs/gatsby/issues/27003)) ([18944ce](https://github.com/gatsbyjs/gatsby/commit/18944cec9d87af4744b5583736cc9ed7adf0df0b))

## [2.24.64](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.63...gatsby@2.24.64) (2020-09-23)

### Features

- **gatsby:** Expose typescript transpiler to default site in plugin list ([#26452](https://github.com/gatsbyjs/gatsby/issues/26452)) ([a8ce6e6](https://github.com/gatsbyjs/gatsby/commit/a8ce6e6e2ad46693a49af052cd302187d56e5943))

## [2.24.63](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.62...gatsby@2.24.63) (2020-09-18)

### Bug Fixes

- **gatsby:** Finish running queries if source files change ([#26940](https://github.com/gatsbyjs/gatsby/issues/26940)) ([d7d2dda](https://github.com/gatsbyjs/gatsby/commit/d7d2dda329d5bf11e1f03d2a6ffb153df3a08031))

## [2.24.62](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.61...gatsby@2.24.62) (2020-09-16)

### Features

- **gatsby:** add babel-lodash plugin to reduce lodash filesize ([#26611](https://github.com/gatsbyjs/gatsby/issues/26611)) ([ede2fd9](https://github.com/gatsbyjs/gatsby/commit/ede2fd9eb89b08d97e5eab0883af819621d7f55f))

## [2.24.61](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.60...gatsby@2.24.61) (2020-09-16)

### Bug Fixes

- **gatsby-cli:** pass --verbose flag to gatsby build properly ([#26904](https://github.com/gatsbyjs/gatsby/issues/26904)) ([55e82f3](https://github.com/gatsbyjs/gatsby/commit/55e82f3e90adc87750aedcc00fe52ec1ca9de38f))

### Features

- **gatsby:** add `Site` and `SiteSiteMetadata` to built-in GraphQL types ([#26866](https://github.com/gatsbyjs/gatsby/issues/26866)) ([8636370](https://github.com/gatsbyjs/gatsby/commit/8636370ceeb0443f56dea4797157ec8887301e6b))
- **gatsby:** print node counts in CLI ([#26907](https://github.com/gatsbyjs/gatsby/issues/26907)) ([34f7a5a](https://github.com/gatsbyjs/gatsby/commit/34f7a5a1ed79cd2cc167502f2f07dffff3088766))
- **gatsby-admin:** track errors ([#26903](https://github.com/gatsbyjs/gatsby/issues/26903)) ([617cc1d](https://github.com/gatsbyjs/gatsby/commit/617cc1dd0e16d60abbea1caec8d3a63f8dbe4142))

## [2.24.60](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.59...gatsby@2.24.60) (2020-09-15)

### Bug Fixes

- **gatsby:** resend pageData when socket disconnect ([#26868](https://github.com/gatsbyjs/gatsby/issues/26868)) ([d153729](https://github.com/gatsbyjs/gatsby/commit/d1537293e27616079c78e8fcd3f29cae131d057f))

## [2.24.59](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.58...gatsby@2.24.59) (2020-09-15)

**Note:** Version bump only for package gatsby

## [2.24.58](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.57...gatsby@2.24.58) (2020-09-14)

### Features

- **gatsby:** create telemetry service and start it during develop ([#26832](https://github.com/gatsbyjs/gatsby/issues/26832)) ([6132b95](https://github.com/gatsbyjs/gatsby/commit/6132b9517f2d4668c55e98fe63f2509fdb3d130a)), closes [#26853](https://github.com/gatsbyjs/gatsby/issues/26853)
- **gatsby:** merge GraphQL types defined by different plugins (with a warning) ([#26864](https://github.com/gatsbyjs/gatsby/issues/26864)) ([0bc63fe](https://github.com/gatsbyjs/gatsby/commit/0bc63fe533f8419708a34b962339f43f4955355d))
- **gatsby-admin:** track plugin telemetry ([#26885](https://github.com/gatsbyjs/gatsby/issues/26885)) ([bf61854](https://github.com/gatsbyjs/gatsby/commit/bf61854dc5bb87911825f925fe839d67e44da986)), closes [#26853](https://github.com/gatsbyjs/gatsby/issues/26853) [#26853](https://github.com/gatsbyjs/gatsby/issues/26853) [#26853](https://github.com/gatsbyjs/gatsby/issues/26853)

## [2.24.57](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.56...gatsby@2.24.57) (2020-09-10)

### Bug Fixes

- **gatsby:** do not initialize cache in onPreInit API ([#26810](https://github.com/gatsbyjs/gatsby/issues/26810)) ([39df4fa](https://github.com/gatsbyjs/gatsby/commit/39df4fa51304bc05f5d9413da7ee80479a3ff726))
- **gatsby:** Handle node mutations immediately after file change ([#26848](https://github.com/gatsbyjs/gatsby/issues/26848)) ([de68259](https://github.com/gatsbyjs/gatsby/commit/de68259d990d4b43660655724122d2cfbc79a7d8))
- **gatsby:** Run actions while recreating pages and draining mutation queue ([#26847](https://github.com/gatsbyjs/gatsby/issues/26847)) ([4b494b6](https://github.com/gatsbyjs/gatsby/commit/4b494b6c259d29ec85f78fe5137036fc16e967ce))

## [2.24.56](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.55...gatsby@2.24.56) (2020-09-09)

**Note:** Version bump only for package gatsby

## [2.24.55](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.54...gatsby@2.24.55) (2020-09-08)

### Bug Fixes

- **gatsby:** fix `$in` operator to return unique elements ([#26822](https://github.com/gatsbyjs/gatsby/issues/26822)) ([df9014d](https://github.com/gatsbyjs/gatsby/commit/df9014d))
- **gatsby:** Run mutations during query running ([#26808](https://github.com/gatsbyjs/gatsby/issues/26808)) ([4427f13](https://github.com/gatsbyjs/gatsby/commit/4427f13))
- **gatsby-cli:** Fix typo (repeated ://) ([#26781](https://github.com/gatsbyjs/gatsby/issues/26781)) ([6a7fcfb](https://github.com/gatsbyjs/gatsby/commit/6a7fcfb))

## [2.24.54](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.53...gatsby@2.24.54) (2020-09-07)

### Bug Fixes

- **doc:** updated onCreateBabelConfig documentation ([#25212](https://github.com/gatsbyjs/gatsby/issues/25212)) ([5538c49](https://github.com/gatsbyjs/gatsby/commit/5538c49))
- **gatsby:** catch when lock already unlocked ([#26805](https://github.com/gatsbyjs/gatsby/issues/26805)) ([9509d01](https://github.com/gatsbyjs/gatsby/commit/9509d01))
- **gatsby:** tap just into main compilation in webpack-dep-tree-plugin ([#26778](https://github.com/gatsbyjs/gatsby/issues/26778)) ([bf7d633](https://github.com/gatsbyjs/gatsby/commit/bf7d633))

## [2.24.53](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.52...gatsby@2.24.53) (2020-08-31)

### Bug Fixes

- **gatsby:** only enable debugger when argument is given ([#26669](https://github.com/gatsbyjs/gatsby/issues/26669)) ([93fdc09](https://github.com/gatsbyjs/gatsby/commit/93fdc09))
- **gatsby:** properly unlock processes onExit ([#26670](https://github.com/gatsbyjs/gatsby/issues/26670)) ([c2aeded](https://github.com/gatsbyjs/gatsby/commit/c2aeded))

## [2.24.52](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.51...gatsby@2.24.52) (2020-08-28)

### Bug Fixes

- **gatsby:** fix error from ts conversion ([#26681](https://github.com/gatsbyjs/gatsby/issues/26681)) ([04c75bb](https://github.com/gatsbyjs/gatsby/commit/04c75bb))
- **gatsby:** fix materialization edge case with nullish values ([#26677](https://github.com/gatsbyjs/gatsby/issues/26677)) ([25e3a63](https://github.com/gatsbyjs/gatsby/commit/25e3a63))

### Features

- **gatsby:** Support React 17's new JSX Transform ([#26652](https://github.com/gatsbyjs/gatsby/issues/26652)) ([6ba68f8](https://github.com/gatsbyjs/gatsby/commit/6ba68f8))

## [2.24.51](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.50...gatsby@2.24.51) (2020-08-26)

### Bug Fixes

- **gatsby:** fix filtering by sub-fields of the field with custom resolver ([#26644](https://github.com/gatsbyjs/gatsby/issues/26644)) ([6eefdee](https://github.com/gatsbyjs/gatsby/commit/6eefdee))

## [2.24.50](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.49...gatsby@2.24.50) (2020-08-25)

### Bug Fixes

- move babel/types from devDependencies to dependencies ([#26404](https://github.com/gatsbyjs/gatsby/issues/26404)) ([318a8a2](https://github.com/gatsbyjs/gatsby/commit/318a8a2))

## [2.24.49](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.48...gatsby@2.24.49) (2020-08-24)

### Bug Fixes

- **gatsby:** take into account possible invalid values in getValueAt ([#26613](https://github.com/gatsbyjs/gatsby/issues/26613)) ([bc3a177](https://github.com/gatsbyjs/gatsby/commit/bc3a177))

## [2.24.48](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.47...gatsby@2.24.48) (2020-08-24)

### Bug Fixes

- **gatsby:** update devcert ([#26566](https://github.com/gatsbyjs/gatsby/issues/26566)) ([1328a97](https://github.com/gatsbyjs/gatsby/commit/1328a97))

### Features

- **gatsby-core-utils:** Add node.js export, and move site-metadata into its own function ([#26237](https://github.com/gatsbyjs/gatsby/issues/26237)) ([b164147](https://github.com/gatsbyjs/gatsby/commit/b164147))

## [2.24.47](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.46...gatsby@2.24.47) (2020-08-12)

**Note:** Version bump only for package gatsby

## [2.24.46](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.45...gatsby@2.24.46) (2020-08-12)

### Bug Fixes

- **gatsby:** place auto-generated virtual modules in `.cache` ([#26396](https://github.com/gatsbyjs/gatsby/issues/26396)) ([9590a2c](https://github.com/gatsbyjs/gatsby/commit/9590a2c))

## [2.24.45](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.44...gatsby@2.24.45) (2020-08-12)

**Note:** Version bump only for package gatsby

## [2.24.44](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.43...gatsby@2.24.44) (2020-08-12)

**Note:** Version bump only for package gatsby

## [2.24.43](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.42...gatsby@2.24.43) (2020-08-11)

### Bug Fixes

- **gatsby:** improve the log for service lock issues ([#26360](https://github.com/gatsbyjs/gatsby/issues/26360)) ([5a4496c](https://github.com/gatsbyjs/gatsby/commit/5a4496c))

## [2.24.42](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.41...gatsby@2.24.42) (2020-08-11)

### Bug Fixes

- **gatsby:** set correct content-type header for socket.io.js ([#26358](https://github.com/gatsbyjs/gatsby/issues/26358)) ([87babc9](https://github.com/gatsbyjs/gatsby/commit/87babc9))

### Features

- **gatsby-cli:** Allow setting the server status port ([#25862](https://github.com/gatsbyjs/gatsby/issues/25862)) ([67615bf](https://github.com/gatsbyjs/gatsby/commit/67615bf))

## [2.24.41](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.40...gatsby@2.24.41) (2020-08-11)

**Note:** Version bump only for package gatsby

## [2.24.40](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.39...gatsby@2.24.40) (2020-08-10)

**Note:** Version bump only for package gatsby

## [2.24.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.38...gatsby@2.24.39) (2020-08-10)

### Features

- **gatsby:** Extend support for file system pages to build client-only and collections of pages! ([#25204](https://github.com/gatsbyjs/gatsby/issues/25204)) ([61d8849](https://github.com/gatsbyjs/gatsby/commit/61d8849))

## [2.24.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.37...gatsby@2.24.38) (2020-08-10)

### Bug Fixes

- **gatsby:** Added { default } to default exports ([#26020](https://github.com/gatsbyjs/gatsby/issues/26020)) ([6e6e419](https://github.com/gatsbyjs/gatsby/commit/6e6e419))

## [2.24.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.36...gatsby@2.24.37) (2020-08-08)

**Note:** Version bump only for package gatsby

## [2.24.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.35...gatsby@2.24.36) (2020-08-07)

### Features

- **gatsby:** add flag to disable schema rebuilding ([#26291](https://github.com/gatsbyjs/gatsby/issues/26291)) ([44175f6](https://github.com/gatsbyjs/gatsby/commit/44175f6))

## [2.24.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.34...gatsby@2.24.35) (2020-08-07)

**Note:** Version bump only for package gatsby

## [2.24.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.33...gatsby@2.24.34) (2020-08-06)

**Note:** Version bump only for package gatsby

## [2.24.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.32...gatsby@2.24.33) (2020-08-06)

### Bug Fixes

- **gatsby:** Move static queries to page data dir ([#26242](https://github.com/gatsbyjs/gatsby/issues/26242)) ([de979d3](https://github.com/gatsbyjs/gatsby/commit/de979d3))

## [2.24.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.31...gatsby@2.24.32) (2020-08-06)

**Note:** Version bump only for package gatsby

## [2.24.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.30...gatsby@2.24.31) (2020-08-06)

**Note:** Version bump only for package gatsby

## [2.24.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.29...gatsby@2.24.30) (2020-08-05)

### Bug Fixes

- **gatsby:** enable ipc messaging on develop ([#26221](https://github.com/gatsbyjs/gatsby/issues/26221)) ([a063a1f](https://github.com/gatsbyjs/gatsby/commit/a063a1f))

## [2.24.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.28...gatsby@2.24.29) (2020-08-05)

**Note:** Version bump only for package gatsby

## [2.24.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.27...gatsby@2.24.28) (2020-08-05)

### Features

- **gatsby:** Store site metadata ([#26162](https://github.com/gatsbyjs/gatsby/issues/26162)) ([36367c4](https://github.com/gatsbyjs/gatsby/commit/36367c4))

## [2.24.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.26...gatsby@2.24.27) (2020-08-04)

**Note:** Version bump only for package gatsby

## [2.24.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.25...gatsby@2.24.26) (2020-08-03)

**Note:** Version bump only for package gatsby

## [2.24.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.24...gatsby@2.24.25) (2020-08-03)

### Features

- **gatsby-recipes:** add recipes gui ([#24595](https://github.com/gatsbyjs/gatsby/issues/24595)) ([07085fa](https://github.com/gatsbyjs/gatsby/commit/07085fa)), closes [#24655](https://github.com/gatsbyjs/gatsby/issues/24655) [#25133](https://github.com/gatsbyjs/gatsby/issues/25133) [#25930](https://github.com/gatsbyjs/gatsby/issues/25930) [#25939](https://github.com/gatsbyjs/gatsby/issues/25939) [#26009](https://github.com/gatsbyjs/gatsby/issues/26009) [#26085](https://github.com/gatsbyjs/gatsby/issues/26085) [#26115](https://github.com/gatsbyjs/gatsby/issues/26115) [#25763](https://github.com/gatsbyjs/gatsby/issues/25763) [#25812](https://github.com/gatsbyjs/gatsby/issues/25812) [#24306](https://github.com/gatsbyjs/gatsby/issues/24306) [#25884](https://github.com/gatsbyjs/gatsby/issues/25884) [#25883](https://github.com/gatsbyjs/gatsby/issues/25883) [#25886](https://github.com/gatsbyjs/gatsby/issues/25886) [#25316](https://github.com/gatsbyjs/gatsby/issues/25316) [#25874](https://github.com/gatsbyjs/gatsby/issues/25874) [#25606](https://github.com/gatsbyjs/gatsby/issues/25606) [#25891](https://github.com/gatsbyjs/gatsby/issues/25891) [#25896](https://github.com/gatsbyjs/gatsby/issues/25896) [#25894](https://github.com/gatsbyjs/gatsby/issues/25894) [#25905](https://github.com/gatsbyjs/gatsby/issues/25905) [#25902](https://github.com/gatsbyjs/gatsby/issues/25902) [#25907](https://github.com/gatsbyjs/gatsby/issues/25907) [#25882](https://github.com/gatsbyjs/gatsby/issues/25882) [#25892](https://github.com/gatsbyjs/gatsby/issues/25892) [#25879](https://github.com/gatsbyjs/gatsby/issues/25879) [#25875](https://github.com/gatsbyjs/gatsby/issues/25875) [#25744](https://github.com/gatsbyjs/gatsby/issues/25744) [#25903](https://github.com/gatsbyjs/gatsby/issues/25903) [#25863](https://github.com/gatsbyjs/gatsby/issues/25863) [#25915](https://github.com/gatsbyjs/gatsby/issues/25915) [#25910](https://github.com/gatsbyjs/gatsby/issues/25910) [#25912](https://github.com/gatsbyjs/gatsby/issues/25912) [#25901](https://github.com/gatsbyjs/gatsby/issues/25901) [#25643](https://github.com/gatsbyjs/gatsby/issues/25643) [#25720](https://github.com/gatsbyjs/gatsby/issues/25720) [#24652](https://github.com/gatsbyjs/gatsby/issues/24652) [#24549](https://github.com/gatsbyjs/gatsby/issues/24549) [#24549](https://github.com/gatsbyjs/gatsby/issues/24549) [#11](https://github.com/gatsbyjs/gatsby/issues/11) [#25832](https://github.com/gatsbyjs/gatsby/issues/25832) [#25936](https://github.com/gatsbyjs/gatsby/issues/25936) [#25344](https://github.com/gatsbyjs/gatsby/issues/25344) [#25721](https://github.com/gatsbyjs/gatsby/issues/25721) [#25943](https://github.com/gatsbyjs/gatsby/issues/25943) [#25479](https://github.com/gatsbyjs/gatsby/issues/25479) [#25716](https://github.com/gatsbyjs/gatsby/issues/25716) [#25946](https://github.com/gatsbyjs/gatsby/issues/25946) [#25940](https://github.com/gatsbyjs/gatsby/issues/25940) [#25954](https://github.com/gatsbyjs/gatsby/issues/25954) [#25464](https://github.com/gatsbyjs/gatsby/issues/25464) [#25914](https://github.com/gatsbyjs/gatsby/issues/25914) [#25970](https://github.com/gatsbyjs/gatsby/issues/25970) [#25972](https://github.com/gatsbyjs/gatsby/issues/25972) [#25815](https://github.com/gatsbyjs/gatsby/issues/25815) [#25944](https://github.com/gatsbyjs/gatsby/issues/25944) [#25941](https://github.com/gatsbyjs/gatsby/issues/25941) [#25974](https://github.com/gatsbyjs/gatsby/issues/25974) [#25971](https://github.com/gatsbyjs/gatsby/issues/25971) [#25921](https://github.com/gatsbyjs/gatsby/issues/25921) [#25276](https://github.com/gatsbyjs/gatsby/issues/25276) [#25463](https://github.com/gatsbyjs/gatsby/issues/25463) [#25980](https://github.com/gatsbyjs/gatsby/issues/25980) [#25965](https://github.com/gatsbyjs/gatsby/issues/25965) [#25926](https://github.com/gatsbyjs/gatsby/issues/25926) [#25983](https://github.com/gatsbyjs/gatsby/issues/25983) [#25958](https://github.com/gatsbyjs/gatsby/issues/25958) [#25978](https://github.com/gatsbyjs/gatsby/issues/25978) [#25998](https://github.com/gatsbyjs/gatsby/issues/25998) [#26002](https://github.com/gatsbyjs/gatsby/issues/26002) [#25997](https://github.com/gatsbyjs/gatsby/issues/25997) [#25984](https://github.com/gatsbyjs/gatsby/issues/25984) [#26006](https://github.com/gatsbyjs/gatsby/issues/26006) [#26043](https://github.com/gatsbyjs/gatsby/issues/26043) [#26030](https://github.com/gatsbyjs/gatsby/issues/26030) [#26016](https://github.com/gatsbyjs/gatsby/issues/26016) [#25960](https://github.com/gatsbyjs/gatsby/issues/25960) [#26054](https://github.com/gatsbyjs/gatsby/issues/26054) [#25929](https://github.com/gatsbyjs/gatsby/issues/25929) [#25995](https://github.com/gatsbyjs/gatsby/issues/25995) [#26068](https://github.com/gatsbyjs/gatsby/issues/26068) [#26051](https://github.com/gatsbyjs/gatsby/issues/26051) [#25747](https://github.com/gatsbyjs/gatsby/issues/25747) [#25613](https://github.com/gatsbyjs/gatsby/issues/25613) [#26067](https://github.com/gatsbyjs/gatsby/issues/26067) [#25682](https://github.com/gatsbyjs/gatsby/issues/25682) [#25631](https://github.com/gatsbyjs/gatsby/issues/25631) [#26065](https://github.com/gatsbyjs/gatsby/issues/26065) [#25683](https://github.com/gatsbyjs/gatsby/issues/25683) [#25792](https://github.com/gatsbyjs/gatsby/issues/25792) [#26078](https://github.com/gatsbyjs/gatsby/issues/26078) [#26053](https://github.com/gatsbyjs/gatsby/issues/26053) [#26077](https://github.com/gatsbyjs/gatsby/issues/26077) [#25371](https://github.com/gatsbyjs/gatsby/issues/25371) [#26092](https://github.com/gatsbyjs/gatsby/issues/26092) [#26101](https://github.com/gatsbyjs/gatsby/issues/26101) [#25952](https://github.com/gatsbyjs/gatsby/issues/25952) [#26104](https://github.com/gatsbyjs/gatsby/issues/26104) [#25776](https://github.com/gatsbyjs/gatsby/issues/25776) [#26109](https://github.com/gatsbyjs/gatsby/issues/26109)

## [2.24.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.23...gatsby@2.24.24) (2020-08-03)

**Note:** Version bump only for package gatsby

## [2.24.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.21...gatsby@2.24.23) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.21...gatsby@2.24.22) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.20...gatsby@2.24.21) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.19...gatsby@2.24.20) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.18...gatsby@2.24.19) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.17...gatsby@2.24.18) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.16...gatsby@2.24.17) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.15...gatsby@2.24.16) (2020-07-31)

**Note:** Version bump only for package gatsby

## [2.24.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.14...gatsby@2.24.15) (2020-07-30)

### Bug Fixes

- **gatsby:** Resolve node mutations in waiting state ([#26138](https://github.com/gatsbyjs/gatsby/issues/26138)) ([f9e12cc](https://github.com/gatsbyjs/gatsby/commit/f9e12cc))

### Features

- **gatsby-telemetry:** Track if cache was purged ([#26096](https://github.com/gatsbyjs/gatsby/issues/26096)) ([495fd73](https://github.com/gatsbyjs/gatsby/commit/495fd73))

## [2.24.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.13...gatsby@2.24.14) (2020-07-29)

### Bug Fixes

- **gatsby:** Load resources in ProdPageRenderer ([#26092](https://github.com/gatsbyjs/gatsby/issues/26092)) ([f8b7b35](https://github.com/gatsbyjs/gatsby/commit/f8b7b35))

## [2.24.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.12...gatsby@2.24.13) (2020-07-29)

### Bug Fixes

- **gatsby:** Delete babel and terser cache dirs ([#26053](https://github.com/gatsbyjs/gatsby/issues/26053)) ([9497c97](https://github.com/gatsbyjs/gatsby/commit/9497c97))
- **gatsby:** Load static query results from its own Db ([#26077](https://github.com/gatsbyjs/gatsby/issues/26077)) ([5cf9687](https://github.com/gatsbyjs/gatsby/commit/5cf9687))

## [2.24.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.11...gatsby@2.24.12) (2020-07-28)

### Bug Fixes

- **gatsby:** Defer node mutation in more APIs ([#26067](https://github.com/gatsbyjs/gatsby/issues/26067)) ([5e5b413](https://github.com/gatsbyjs/gatsby/commit/5e5b413))
- Enable CLI integration tests ([#25997](https://github.com/gatsbyjs/gatsby/issues/25997)) ([ffabe75](https://github.com/gatsbyjs/gatsby/commit/ffabe75))

### Features

- **gatsby:** Add top-level error handling to state machine ([#25995](https://github.com/gatsbyjs/gatsby/issues/25995)) ([b84ea14](https://github.com/gatsbyjs/gatsby/commit/b84ea14))

## [2.24.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.10...gatsby@2.24.11) (2020-07-24)

### Bug Fixes

- **gatsby:** call predicate for the root ancestor in findRootNodeAncestor ([#25974](https://github.com/gatsbyjs/gatsby/issues/25974)) ([ac40874](https://github.com/gatsbyjs/gatsby/commit/ac40874))

### Features

- **gatsby:** Add internal types export ([#25921](https://github.com/gatsbyjs/gatsby/issues/25921)) ([08d2d70](https://github.com/gatsbyjs/gatsby/commit/08d2d70))

## [2.24.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.9...gatsby@2.24.10) (2020-07-23)

**Note:** Version bump only for package gatsby

## [2.24.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.8...gatsby@2.24.9) (2020-07-22)

### Bug Fixes

- **gatsby:** don't place virtual modules in node_modules directory ([#25720](https://github.com/gatsbyjs/gatsby/issues/25720)) ([7b1a0f2](https://github.com/gatsbyjs/gatsby/commit/7b1a0f2))

### Features

- **gatsby:** Defer node mutation during querying ([#25479](https://github.com/gatsbyjs/gatsby/issues/25479)) ([cf14989](https://github.com/gatsbyjs/gatsby/commit/cf14989)), closes [#25716](https://github.com/gatsbyjs/gatsby/issues/25716)

## [2.24.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.7...gatsby@2.24.8) (2020-07-21)

### Bug Fixes

- **gatsby:** Support symlinks in static directories ([#25894](https://github.com/gatsbyjs/gatsby/issues/25894)) ([42d342e](https://github.com/gatsbyjs/gatsby/commit/42d342e))
- Restore CLI port in use prompt feature ([#25863](https://github.com/gatsbyjs/gatsby/issues/25863)) ([fc2f6f0](https://github.com/gatsbyjs/gatsby/commit/fc2f6f0))

## [2.24.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.6...gatsby@2.24.7) (2020-07-20)

### Features

- **gatsby:** Load static query results in Gatsby runtime ([#25723](https://github.com/gatsbyjs/gatsby/issues/25723)) ([b00c3df](https://github.com/gatsbyjs/gatsby/commit/b00c3df))

## [2.24.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.5...gatsby@2.24.6) (2020-07-20)

### Bug Fixes

- **docs:** change LeKoArts to LekoArts ([#25843](https://github.com/gatsbyjs/gatsby/issues/25843)) ([724d717](https://github.com/gatsbyjs/gatsby/commit/724d717))

## [2.24.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.4...gatsby@2.24.5) (2020-07-20)

**Note:** Version bump only for package gatsby

## [2.24.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.3...gatsby@2.24.4) (2020-07-17)

### Bug Fixes

- **gatsby-cli:** enable inspect-brk & inspect options ([#24693](https://github.com/gatsbyjs/gatsby/issues/24693)) ([ddfff2a](https://github.com/gatsbyjs/gatsby/commit/ddfff2a))

## [2.24.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.2...gatsby@2.24.3) (2020-07-15)

### Bug Fixes

- **gatsby:** fix timing issue around marking webpack as pending due to requires-writer run ([#25759](https://github.com/gatsbyjs/gatsby/issues/25759)) ([fa3a7eb](https://github.com/gatsbyjs/gatsby/commit/fa3a7eb))
- **gatsby:** Fixes process.env replacement for some packages ([#25684](https://github.com/gatsbyjs/gatsby/issues/25684)) ([d276917](https://github.com/gatsbyjs/gatsby/commit/d276917))
- **gatsby:** Support numbers in navigate function ([#25611](https://github.com/gatsbyjs/gatsby/issues/25611)) ([83926c8](https://github.com/gatsbyjs/gatsby/commit/83926c8))

### Features

- **gatsby:** Track static queries by template ([#25549](https://github.com/gatsbyjs/gatsby/issues/25549)) ([e640c5b](https://github.com/gatsbyjs/gatsby/commit/e640c5b))

## [2.24.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.1...gatsby@2.24.2) (2020-07-10)

### Bug Fixes

- **gatsby:** fix setting total in progress activities created by plugins ([#25648](https://github.com/gatsbyjs/gatsby/issues/25648)) ([4fe0a2e](https://github.com/gatsbyjs/gatsby/commit/4fe0a2e))

## [2.24.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.24.0...gatsby@2.24.1) (2020-07-09)

### Bug Fixes

- **gatsby:** Check if page data exists when hash matches ([#25614](https://github.com/gatsbyjs/gatsby/issues/25614)) ([1399426](https://github.com/gatsbyjs/gatsby/commit/1399426))

# [2.24.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.23...gatsby@2.24.0) (2020-07-09)

### Features

- **gatsby:** add polyfill chunk to gatsby ([#25159](https://github.com/gatsbyjs/gatsby/issues/25159)) ([0b7738c](https://github.com/gatsbyjs/gatsby/commit/0b7738c))
- **gatsby:** shim much used polyfills to noOp ([#25162](https://github.com/gatsbyjs/gatsby/issues/25162)) ([669de83](https://github.com/gatsbyjs/gatsby/commit/669de83))
- **gatsby-recipes:** add GatsbyPage provider ([#25248](https://github.com/gatsbyjs/gatsby/issues/25248)) ([9c58ee1](https://github.com/gatsbyjs/gatsby/commit/9c58ee1))

## [2.23.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.22...gatsby@2.23.23) (2020-07-09)

### Bug Fixes

- **gatsby:** end activity if plugin didn't do it ([#25470](https://github.com/gatsbyjs/gatsby/issues/25470)) ([44d0c2a](https://github.com/gatsbyjs/gatsby/commit/44d0c2a))

## [2.23.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.21...gatsby@2.23.22) (2020-07-07)

### Features

- **gatsby:** Use state machine for query running in develop ([#25378](https://github.com/gatsbyjs/gatsby/issues/25378)) ([e5ce35b](https://github.com/gatsbyjs/gatsby/commit/e5ce35b))

## [2.23.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.20...gatsby@2.23.21) (2020-07-06)

### Bug Fixes

- **gatsby:** correctly pass through exit signals from child process ([#25520](https://github.com/gatsbyjs/gatsby/issues/25520)) ([be78563](https://github.com/gatsbyjs/gatsby/commit/be78563))
- **gatsby-transformer-sharp:** removed unnecessary conversion to webp ([#25325](https://github.com/gatsbyjs/gatsby/issues/25325)) ([a5459bc](https://github.com/gatsbyjs/gatsby/commit/a5459bc))

## [2.23.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.19...gatsby@2.23.20) (2020-07-03)

**Note:** Version bump only for package gatsby

## [2.23.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.18...gatsby@2.23.19) (2020-07-03)

**Note:** Version bump only for package gatsby

## [2.23.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.17...gatsby@2.23.18) (2020-07-02)

### Bug Fixes

- **eslint-config:** Remove deprecated jsx-a11y/label-has-for rule ([#25317](https://github.com/gatsbyjs/gatsby/issues/25317)) ([ff4ce02](https://github.com/gatsbyjs/gatsby/commit/ff4ce02))

## [2.23.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.16...gatsby@2.23.17) (2020-07-02)

**Note:** Version bump only for package gatsby

## [2.23.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.15...gatsby@2.23.16) (2020-07-02)

**Note:** Version bump only for package gatsby

## [2.23.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.14...gatsby@2.23.15) (2020-07-02)

### Features

- **gatsby:** Track static queries by template ([#25120](https://github.com/gatsbyjs/gatsby/issues/25120)) ([6b39645](https://github.com/gatsbyjs/gatsby/commit/6b39645))

## [2.23.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.13...gatsby@2.23.14) (2020-07-01)

**Note:** Version bump only for package gatsby

## [2.23.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.12...gatsby@2.23.13) (2020-07-01)

### Bug Fixes

- update packages ([#25381](https://github.com/gatsbyjs/gatsby/issues/25381)) ([622e3c1](https://github.com/gatsbyjs/gatsby/commit/622e3c1))
- **gatsby:** fix typings in resolve-module-exports ([#25401](https://github.com/gatsbyjs/gatsby/issues/25401)) ([fdd71f4](https://github.com/gatsbyjs/gatsby/commit/fdd71f4))

### Features

- **gatsby:** Use state machine for bootstrap in develop ([#25305](https://github.com/gatsbyjs/gatsby/issues/25305)) ([ed9771b](https://github.com/gatsbyjs/gatsby/commit/ed9771b))

## [2.23.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.11...gatsby@2.23.12) (2020-06-29)

### Bug Fixes

- **gatsby:** fix build-html error stacktrace ([#25385](https://github.com/gatsbyjs/gatsby/issues/25385)) ([eac89cb](https://github.com/gatsbyjs/gatsby/commit/eac89cb))

## [2.23.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.10...gatsby@2.23.11) (2020-06-24)

### Bug Fixes

- **gatsby:** Fix SSL for develop ([#25230](https://github.com/gatsbyjs/gatsby/issues/25230)) ([432c4f7](https://github.com/gatsbyjs/gatsby/commit/432c4f7))

## [2.23.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.9...gatsby@2.23.10) (2020-06-23)

### Bug Fixes

- **gatsby:** Typo in the code example of the PageProps inline docs ([#25200](https://github.com/gatsbyjs/gatsby/issues/25200)) ([a72caa6](https://github.com/gatsbyjs/gatsby/commit/a72caa6))

## [2.23.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.8...gatsby@2.23.9) (2020-06-22)

**Note:** Version bump only for package gatsby

## [2.23.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.7...gatsby@2.23.8) (2020-06-22)

### Bug Fixes

- **gatsby:** convert module.exports to es6 in redux/filters ([#25191](https://github.com/gatsbyjs/gatsby/issues/25191)) ([3934c37](https://github.com/gatsbyjs/gatsby/commit/3934c37))
- **gatsby:** show error message instead of [Object object](<[#25182](https://github.com/gatsbyjs/gatsby/issues/25182)>) ([445e315](https://github.com/gatsbyjs/gatsby/commit/445e315))

## [2.23.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.6...gatsby@2.23.7) (2020-06-20)

### Bug Fixes

- **bin:** point bin to always existing files ([#25121](https://github.com/gatsbyjs/gatsby/issues/25121)) ([eba033e](https://github.com/gatsbyjs/gatsby/commit/eba033e))
- **gatsby:** remove page-date from jest-worker ([#25135](https://github.com/gatsbyjs/gatsby/issues/25135)) ([bed5dc4](https://github.com/gatsbyjs/gatsby/commit/bed5dc4))

## [2.23.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.5...gatsby@2.23.6) (2020-06-19)

**Note:** Version bump only for package gatsby

## [2.23.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.4...gatsby@2.23.5) (2020-06-19)

### Bug Fixes

- **gatsby:** allow amending autoprefixer options ([#24907](https://github.com/gatsbyjs/gatsby/issues/24907)) ([8e6e021](https://github.com/gatsbyjs/gatsby/commit/8e6e021))
- **gatsby:** Several fixes for scroll handling and restoration ([#24306](https://github.com/gatsbyjs/gatsby/issues/24306)) ([4c0916b](https://github.com/gatsbyjs/gatsby/commit/4c0916b))

### Features

- **gatsby:** allow serving of dotfiles from public folder ([#24958](https://github.com/gatsbyjs/gatsby/issues/24958)) ([2270c5a](https://github.com/gatsbyjs/gatsby/commit/2270c5a))
- **gatsby:** Instrument partial writes to page data ([#24808](https://github.com/gatsbyjs/gatsby/issues/24808)) ([b2bf298](https://github.com/gatsbyjs/gatsby/commit/b2bf298))

### Performance Improvements

- **gatsby:** Lazily re-create GraphQL runner ([#25063](https://github.com/gatsbyjs/gatsby/issues/25063)) ([0407cc6](https://github.com/gatsbyjs/gatsby/commit/0407cc6))

## [2.23.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.3...gatsby@2.23.4) (2020-06-15)

### Bug Fixes

- **gatsby:** Add null context check ([#24904](https://github.com/gatsbyjs/gatsby/issues/24904)) ([b554bd5](https://github.com/gatsbyjs/gatsby/commit/b554bd5))

## [2.23.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.2...gatsby@2.23.3) (2020-06-09)

**Note:** Version bump only for package gatsby

## [2.23.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.1...gatsby@2.23.2) (2020-06-09)

### Bug Fixes

- **babel-plugin-remove-graphql-queries:** Strip ignored characters from query text for better caching and deduping ([#24807](https://github.com/gatsbyjs/gatsby/issues/24807)) ([752f5ff](https://github.com/gatsbyjs/gatsby/commit/752f5ff))
- **gatsby:** Fix issue where inline static query in page gets added to page data ([#24805](https://github.com/gatsbyjs/gatsby/issues/24805)) ([7c9711b](https://github.com/gatsbyjs/gatsby/commit/7c9711b))

## [2.23.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.23.0...gatsby@2.23.1) (2020-06-05)

**Note:** Version bump only for package gatsby

# [2.23.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.22...gatsby@2.23.0) (2020-06-04)

### Performance Improvements

- **gatsby:** stop using Sift as fallback ([#24743](https://github.com/gatsbyjs/gatsby/issues/24743)) ([6ee4a35](https://github.com/gatsbyjs/gatsby/commit/6ee4a35))

## [2.22.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.21...gatsby@2.22.22) (2020-06-04)

### Bug Fixes

- **gatsby:** add connection data dependency on concrete types when abstract type is queried ([#24754](https://github.com/gatsbyjs/gatsby/issues/24754)) ([54d0cf9](https://github.com/gatsbyjs/gatsby/commit/54d0cf9))

## [2.22.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.20...gatsby@2.22.21) (2020-06-04)

**Note:** Version bump only for package gatsby

## [2.22.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.19...gatsby@2.22.20) (2020-06-03)

### Bug Fixes

- **gatsby:** bind develop-proxy server to host specified by user ([#24761](https://github.com/gatsbyjs/gatsby/issues/24761)) ([8750898](https://github.com/gatsbyjs/gatsby/commit/8750898))

## [2.22.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.18...gatsby@2.22.19) (2020-06-03)

### Bug Fixes

- **gatsby:** Fix develop SSL by moving the SSL setup to the proxy ([#24335](https://github.com/gatsbyjs/gatsby/issues/24335)) ([7180b26](https://github.com/gatsbyjs/gatsby/commit/7180b26))

## [2.22.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.17...gatsby@2.22.18) (2020-06-03)

### Performance Improvements

- **gatsby:** be more conservative in when to sort ([#24609](https://github.com/gatsbyjs/gatsby/issues/24609)) ([2b578e8](https://github.com/gatsbyjs/gatsby/commit/2b578e8))
- **gatsby:** drop severe scaling regression caused by analytics ([#24709](https://github.com/gatsbyjs/gatsby/issues/24709)) ([2528a85](https://github.com/gatsbyjs/gatsby/commit/2528a85))

## [2.22.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.16...gatsby@2.22.17) (2020-06-02)

### Bug Fixes

- **data-dependency-tracking:** clear data dependencies when rerunning dirty queries ([#24378](https://github.com/gatsbyjs/gatsby/issues/24378)) ([a56012c](https://github.com/gatsbyjs/gatsby/commit/a56012c))

### Features

- **gatsby:** Add support for relative links ([#24054](https://github.com/gatsbyjs/gatsby/issues/24054)) ([e2c6cf2](https://github.com/gatsbyjs/gatsby/commit/e2c6cf2))

## [2.22.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.15...gatsby@2.22.16) (2020-06-02)

**Note:** Version bump only for package gatsby

## [2.22.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.14...gatsby@2.22.15) (2020-05-31)

**Note:** Version bump only for package gatsby

## [2.22.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.13...gatsby@2.22.14) (2020-05-31)

**Note:** Version bump only for package gatsby

## [2.22.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.12...gatsby@2.22.13) (2020-05-30)

### Bug Fixes

- **gatsby:** show correct `serve` info when running on another port ([#24591](https://github.com/gatsbyjs/gatsby/issues/24591)) ([3717ad6](https://github.com/gatsbyjs/gatsby/commit/3717ad6))
- **gatsby:** Turn off react/jsx-pascal-case in ESLint to fix Theme-UI warnings ([#24560](https://github.com/gatsbyjs/gatsby/issues/24560)) ([ee00a6f](https://github.com/gatsbyjs/gatsby/commit/ee00a6f))

### Features

- **gatsby:** serve Admin from develop parent process ([#23734](https://github.com/gatsbyjs/gatsby/issues/23734)) ([a6eb21b](https://github.com/gatsbyjs/gatsby/commit/a6eb21b))

## [2.22.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.11...gatsby@2.22.12) (2020-05-28)

### Bug Fixes

- **code:** redux types - sireUrl -> siteUrl ([#24488](https://github.com/gatsbyjs/gatsby/issues/24488)) ([2beab4b](https://github.com/gatsbyjs/gatsby/commit/2beab4b))

### Performance Improvements

- **gatsby:** stop using sets and use ordered arrays instead ([#24486](https://github.com/gatsbyjs/gatsby/issues/24486)) ([928fd05](https://github.com/gatsbyjs/gatsby/commit/928fd05))

## [2.22.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.10...gatsby@2.22.11) (2020-05-26)

### Bug Fixes

- **gatsby:** add explicit dependency on `socket.io-client` and explicitly set `url-loader` fallback ([#24465](https://github.com/gatsbyjs/gatsby/issues/24465)) ([36357ab](https://github.com/gatsbyjs/gatsby/commit/36357ab))
- **gatsby:** Also traverse `FunctionDeclaration` ([#24472](https://github.com/gatsbyjs/gatsby/issues/24472)) ([6eb7290](https://github.com/gatsbyjs/gatsby/commit/6eb7290))

## [2.22.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.9...gatsby@2.22.10) (2020-05-25)

### Bug Fixes

- **docs:** brand name Webpack to webpack ([#22906](https://github.com/gatsbyjs/gatsby/issues/22906)) ([44cbb14](https://github.com/gatsbyjs/gatsby/commit/44cbb14))
- **gatsby:** Pass through ws in proxy ([#24352](https://github.com/gatsbyjs/gatsby/issues/24352)) ([5389bfd](https://github.com/gatsbyjs/gatsby/commit/5389bfd))

## [2.22.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.8...gatsby@2.22.9) (2020-05-22)

### Performance Improvements

- **gatsby:** support empty filters without sift ([#24258](https://github.com/gatsbyjs/gatsby/issues/24258)) ([542cda8](https://github.com/gatsbyjs/gatsby/commit/542cda8))

## [2.22.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.7...gatsby@2.22.8) (2020-05-22)

**Note:** Version bump only for package gatsby

## [2.22.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.6...gatsby@2.22.7) (2020-05-22)

**Note:** Version bump only for package gatsby

## [2.22.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.5...gatsby@2.22.6) (2020-05-21)

**Note:** Version bump only for package gatsby

## [2.22.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.4...gatsby@2.22.5) (2020-05-21)

### Bug Fixes

- **gatsby:** add control-has-associated-label rule into eslint-config ([#24311](https://github.com/gatsbyjs/gatsby/issues/24311)) ([c1ae8f2](https://github.com/gatsbyjs/gatsby/commit/c1ae8f2))
- **gatsby:** adjust `create-react-context` alias to match actual package exports ([#24305](https://github.com/gatsbyjs/gatsby/issues/24305)) ([cb5d055](https://github.com/gatsbyjs/gatsby/commit/cb5d055))

## [2.22.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.3...gatsby@2.22.4) (2020-05-20)

**Note:** Version bump only for package gatsby

## [2.22.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.2...gatsby@2.22.3) (2020-05-20)

**Note:** Version bump only for package gatsby

## [2.22.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.1...gatsby@2.22.2) (2020-05-20)

### Bug Fixes

- **gatsby-core-utils:** create lock per service, rather than per site ([#24252](https://github.com/gatsbyjs/gatsby/issues/24252)) ([718deb3](https://github.com/gatsbyjs/gatsby/commit/718deb3))

## [2.22.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.22.0...gatsby@2.22.1) (2020-05-20)

**Note:** Version bump only for package gatsby

# [2.22.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.40...gatsby@2.22.0) (2020-05-19)

### Features

- **gatsby:** Prompt users to restart process on gatsby-config & gatsby-node changes ([#22759](https://github.com/gatsbyjs/gatsby/issues/22759)) ([d4ec5e5](https://github.com/gatsbyjs/gatsby/commit/d4ec5e5))

## [2.21.40](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.39...gatsby@2.21.40) (2020-05-19)

**Note:** Version bump only for package gatsby

## [2.21.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.38...gatsby@2.21.39) (2020-05-19)

### Performance Improvements

- **gatsby:** Enable fast filters for $regex/$glob ([#24188](https://github.com/gatsbyjs/gatsby/issues/24188)) ([acfc455](https://github.com/gatsbyjs/gatsby/commit/acfc455))

## [2.21.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.37...gatsby@2.21.38) (2020-05-19)

**Note:** Version bump only for package gatsby

## [2.21.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.36...gatsby@2.21.37) (2020-05-18)

**Note:** Version bump only for package gatsby

## [2.21.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.35...gatsby@2.21.36) (2020-05-18)

**Note:** Version bump only for package gatsby

## [2.21.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.34...gatsby@2.21.35) (2020-05-18)

### Performance Improvements

- **gatsby:** Enable fast filters for \$nin comparator ([#24184](https://github.com/gatsbyjs/gatsby/issues/24184)) ([8e3428f](https://github.com/gatsbyjs/gatsby/commit/8e3428f))

## [2.21.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.33...gatsby@2.21.34) (2020-05-18)

### Features

- **gatsby:** Warn when pageContext is over 500k ([#23310](https://github.com/gatsbyjs/gatsby/issues/23310)) ([02bdba9](https://github.com/gatsbyjs/gatsby/commit/02bdba9))

## [2.21.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.32...gatsby@2.21.33) (2020-05-15)

### Performance Improvements

- **gatsby:** enable fast filters for `in` comparator ([#24095](https://github.com/gatsbyjs/gatsby/issues/24095)) ([70a7533](https://github.com/gatsbyjs/gatsby/commit/70a7533))

## [2.21.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.31...gatsby@2.21.32) (2020-05-15)

### Bug Fixes

- **gatsby:** Protect about possibly missing context in graphql ([#24108](https://github.com/gatsbyjs/gatsby/issues/24108)) ([9ad511b](https://github.com/gatsbyjs/gatsby/commit/9ad511b))

### Features

- **gatsby:** Add total count to pageInfo ([#24084](https://github.com/gatsbyjs/gatsby/issues/24084)) ([1e3b775](https://github.com/gatsbyjs/gatsby/commit/1e3b775))

## [2.21.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.30...gatsby@2.21.31) (2020-05-14)

### Bug Fixes

- **gatsby:** Update to handle changes to fast refresh webpack plugin ([#24091](https://github.com/gatsbyjs/gatsby/issues/24091)) ([7adad91](https://github.com/gatsbyjs/gatsby/commit/7adad91))

## [2.21.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.29...gatsby@2.21.30) (2020-05-14)

**Note:** Version bump only for package gatsby

## [2.21.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.28...gatsby@2.21.29) (2020-05-13)

### Bug Fixes

- **gatsby:** don't fail validation on fragments that are not used ([#24032](https://github.com/gatsbyjs/gatsby/issues/24032)) ([61d0ef4](https://github.com/gatsbyjs/gatsby/commit/61d0ef4))
- **gatsby:** update script to generate apis.json to accommodate TypeScript ([#24023](https://github.com/gatsbyjs/gatsby/issues/24023)) ([7878d0f](https://github.com/gatsbyjs/gatsby/commit/7878d0f))

## [2.21.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.27...gatsby@2.21.28) (2020-05-13)

### Bug Fixes

- **gatsby:** add generic locationState to types ([#24029](https://github.com/gatsbyjs/gatsby/issues/24029)) ([8f16846](https://github.com/gatsbyjs/gatsby/commit/8f16846))

### Performance Improvements

- **gatsby:** enable fast filters for \$ne ([#24050](https://github.com/gatsbyjs/gatsby/issues/24050)) ([8e5e5f7](https://github.com/gatsbyjs/gatsby/commit/8e5e5f7))

## [2.21.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.26...gatsby@2.21.27) (2020-05-13)

**Note:** Version bump only for package gatsby

## [2.21.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.25...gatsby@2.21.26) (2020-05-13)

### Bug Fixes

- **gatsby:** wait for app-data.json file writing ([#22099](https://github.com/gatsbyjs/gatsby/issues/22099)) ([037de56](https://github.com/gatsbyjs/gatsby/commit/037de56))

## [2.21.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.24...gatsby@2.21.25) (2020-05-13)

**Note:** Version bump only for package gatsby

## [2.21.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.23...gatsby@2.21.24) (2020-05-12)

### Bug Fixes

- **gatsby:** allow elemMatch on non-arrays, fix tests ([#23634](https://github.com/gatsbyjs/gatsby/issues/23634)) ([1d99ffd](https://github.com/gatsbyjs/gatsby/commit/1d99ffd))

### Performance Improvements

- **gatsby:** enable fast filters for lt and gt ([#23978](https://github.com/gatsbyjs/gatsby/issues/23978)) ([1d22341](https://github.com/gatsbyjs/gatsby/commit/1d22341))

## [2.21.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.22...gatsby@2.21.23) (2020-05-12)

### Bug Fixes

- handle nullish announcementRef to fix client side redirect error ([#23956](https://github.com/gatsbyjs/gatsby/issues/23956)) ([7a23392](https://github.com/gatsbyjs/gatsby/commit/7a23392))

### Features

- **gatsby:** Add tracing for graphql resolvers ([#23589](https://github.com/gatsbyjs/gatsby/issues/23589)) ([e124aae](https://github.com/gatsbyjs/gatsby/commit/e124aae))
- **gatsby:** Gatsby config validation should suggest related keys ([#23284](https://github.com/gatsbyjs/gatsby/issues/23284)) ([e50407a](https://github.com/gatsbyjs/gatsby/commit/e50407a))

## [2.21.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.21...gatsby@2.21.22) (2020-05-11)

**Note:** Version bump only for package gatsby

## [2.21.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.20...gatsby@2.21.21) (2020-05-08)

**Note:** Version bump only for package gatsby

## [2.21.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.19...gatsby@2.21.20) (2020-05-08)

**Note:** Version bump only for package gatsby

## [2.21.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.18...gatsby@2.21.19) (2020-05-07)

**Note:** Version bump only for package gatsby

## [2.21.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.17...gatsby@2.21.18) (2020-05-07)

### Performance Improvements

- **gatsby:** replace `mitt` with a modern Map/Set based version of it ([#23223](https://github.com/gatsbyjs/gatsby/issues/23223)) ([986f7b8](https://github.com/gatsbyjs/gatsby/commit/986f7b8))

## [2.21.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.16...gatsby@2.21.17) (2020-05-07)

### Bug Fixes

- **gatsby:** print LAN url with serve (like gatsby develop) ([#23418](https://github.com/gatsbyjs/gatsby/issues/23418)) ([0dc20a3](https://github.com/gatsbyjs/gatsby/commit/0dc20a3))
- **gatsby:** use scoped requires for theme plugins ([#23696](https://github.com/gatsbyjs/gatsby/issues/23696)) ([4430687](https://github.com/gatsbyjs/gatsby/commit/4430687))

### Performance Improvements

- **gatsby:** include node counts in output after sourcing steps ([#23671](https://github.com/gatsbyjs/gatsby/issues/23671)) ([192faf6](https://github.com/gatsbyjs/gatsby/commit/192faf6))

## [2.21.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.15...gatsby@2.21.16) (2020-05-06)

### Features

- **gatsby/dev-404-page:** support reading and writing filter to `?filter` query string ([#23618](https://github.com/gatsbyjs/gatsby/issues/23618)) ([8f4257a](https://github.com/gatsbyjs/gatsby/commit/8f4257a))

## [2.21.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.14...gatsby@2.21.15) (2020-05-06)

**Note:** Version bump only for package gatsby

## [2.21.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.13...gatsby@2.21.14) (2020-05-06)

**Note:** Version bump only for package gatsby

## [2.21.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.12...gatsby@2.21.13) (2020-05-05)

### Bug Fixes

- Add 98124 error to better help with "Can't resolve [...]" errors ([#23741](https://github.com/gatsbyjs/gatsby/issues/23741)) ([9970faf](https://github.com/gatsbyjs/gatsby/commit/9970faf))

## [2.21.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.11...gatsby@2.21.12) (2020-05-05)

### Bug Fixes

- **babel-preset-gatsby:** remove prop-types in production for dependencies ([#23609](https://github.com/gatsbyjs/gatsby/issues/23609)) ([a844157](https://github.com/gatsbyjs/gatsby/commit/a844157))
- **gatsby:** log config validation errors ([#23620](https://github.com/gatsbyjs/gatsby/issues/23620)) ([62d6bb4](https://github.com/gatsbyjs/gatsby/commit/62d6bb4))

## [2.21.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.10...gatsby@2.21.11) (2020-05-04)

### Bug Fixes

- **gatsby:** Fix dirty check for schema rebuilding ([#23658](https://github.com/gatsbyjs/gatsby/issues/23658)) ([fa50f3e](https://github.com/gatsbyjs/gatsby/commit/fa50f3e))

## [2.21.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.9...gatsby@2.21.10) (2020-05-04)

**Note:** Version bump only for package gatsby

## [2.21.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.8...gatsby@2.21.9) (2020-05-01)

**Note:** Version bump only for package gatsby

## [2.21.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.7...gatsby@2.21.8) (2020-05-01)

### Bug Fixes

- **gatsby:** add maxAsyncRequests to infinity to reduce bundle size ([#23528](https://github.com/gatsbyjs/gatsby/issues/23528)) ([0acafdd](https://github.com/gatsbyjs/gatsby/commit/0acafdd))

## [2.21.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.6...gatsby@2.21.7) (2020-04-30)

### Bug Fixes

- **gatsby:** fix binary search incorrectly setting next pivot + tests ([#23637](https://github.com/gatsbyjs/gatsby/issues/23637)) ([867cb31](https://github.com/gatsbyjs/gatsby/commit/867cb31))

## [2.21.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.5...gatsby@2.21.6) (2020-04-30)

### Performance Improvements

- **gatsby:** support fast filters for gte ([#23348](https://github.com/gatsbyjs/gatsby/issues/23348)) ([a69701b](https://github.com/gatsbyjs/gatsby/commit/a69701b))

## [2.21.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.4...gatsby@2.21.5) (2020-04-29)

**Note:** Version bump only for package gatsby

## [2.21.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.3...gatsby@2.21.4) (2020-04-29)

**Note:** Version bump only for package gatsby

## [2.21.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.2...gatsby@2.21.3) (2020-04-29)

**Note:** Version bump only for package gatsby

## [2.21.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.1...gatsby@2.21.2) (2020-04-29)

### Bug Fixes

- **gatsby:** fix dirty check for inference metadata with related nodes ([#23472](https://github.com/gatsbyjs/gatsby/issues/23472)) ([7b43a60](https://github.com/gatsbyjs/gatsby/commit/7b43a60))

## [2.21.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.21.0...gatsby@2.21.1) (2020-04-28)

### Bug Fixes

- update packages ([#23525](https://github.com/gatsbyjs/gatsby/issues/23525)) ([e65dd1e](https://github.com/gatsbyjs/gatsby/commit/e65dd1e))
- **gatsby:** don't show error for proper redirects ([#19789](https://github.com/gatsbyjs/gatsby/issues/19789)) ([2e6c509](https://github.com/gatsbyjs/gatsby/commit/2e6c509))

# [2.21.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.36...gatsby@2.21.0) (2020-04-27)

### Bug Fixes

- **webpack:** ensure resolution of react-refresh-webpack-plugin ([#23456](https://github.com/gatsbyjs/gatsby/issues/23456)) ([8c32917](https://github.com/gatsbyjs/gatsby/commit/8c32917))

## [2.20.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.35...gatsby@2.20.36) (2020-04-25)

**Note:** Version bump only for package gatsby

## [2.20.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.34...gatsby@2.20.35) (2020-04-25)

**Note:** Version bump only for package gatsby

## [2.20.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.33...gatsby@2.20.34) (2020-04-25)

**Note:** Version bump only for package gatsby

## [2.20.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.32...gatsby@2.20.33) (2020-04-24)

**Note:** Version bump only for package gatsby

## [2.20.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.31...gatsby@2.20.32) (2020-04-24)

**Note:** Version bump only for package gatsby

## [2.20.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.30...gatsby@2.20.31) (2020-04-24)

**Note:** Version bump only for package gatsby

## [2.20.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.29...gatsby@2.20.30) (2020-04-24)

**Note:** Version bump only for package gatsby

## [2.20.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.28...gatsby@2.20.29) (2020-04-22)

### Bug Fixes

- **gatsby:** fix Uncaught TypeError in navigation.js ([#23196](https://github.com/gatsbyjs/gatsby/issues/23196)) ([da535a8](https://github.com/gatsbyjs/gatsby/commit/da535a8)), closes [#21263](https://github.com/gatsbyjs/gatsby/issues/21263)
- **gatsby:** Improve error message when calling useStaticQuery without graphql ([#23189](https://github.com/gatsbyjs/gatsby/issues/23189)) ([6a079fb](https://github.com/gatsbyjs/gatsby/commit/6a079fb))

## [2.20.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.27...gatsby@2.20.28) (2020-04-21)

### Bug Fixes

- **gatsby:** Check for files before delete action when using GATSBY_EXPERIMENTAL_PAGE_BUILD_ON_DATA_CHANGES ([#23219](https://github.com/gatsbyjs/gatsby/issues/23219)) ([ea7160d](https://github.com/gatsbyjs/gatsby/commit/ea7160d))

## [2.20.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.26...gatsby@2.20.27) (2020-04-20)

**Note:** Version bump only for package gatsby

## [2.20.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.25...gatsby@2.20.26) (2020-04-20)

### Bug Fixes

- **gatsby:** Throw error on default export in gatsby-ssr/brows… ([#23133](https://github.com/gatsbyjs/gatsby/issues/23133)) ([3def3a7](https://github.com/gatsbyjs/gatsby/commit/3def3a7))

## [2.20.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.24...gatsby@2.20.25) (2020-04-18)

### Bug Fixes

- **gatsby:** Add self-signed cert to node trust store (https) ([#18703](https://github.com/gatsbyjs/gatsby/issues/18703)) ([4fd8f8e](https://github.com/gatsbyjs/gatsby/commit/4fd8f8e))

## [2.20.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.23...gatsby@2.20.24) (2020-04-17)

### Bug Fixes

- wrap ignore pattern in quotes ([#23176](https://github.com/gatsbyjs/gatsby/issues/23176)) ([7563db6](https://github.com/gatsbyjs/gatsby/commit/7563db6))

## [2.20.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.22...gatsby@2.20.23) (2020-04-16)

### Features

- **Gatsby Recipes:** Initial release ([#22709](https://github.com/gatsbyjs/gatsby/issues/22709)) ([c59a421](https://github.com/gatsbyjs/gatsby/commit/c59a421)), closes [#22721](https://github.com/gatsbyjs/gatsby/issues/22721) [#22743](https://github.com/gatsbyjs/gatsby/issues/22743) [#22764](https://github.com/gatsbyjs/gatsby/issues/22764) [#22783](https://github.com/gatsbyjs/gatsby/issues/22783) [#22805](https://github.com/gatsbyjs/gatsby/issues/22805) [#22823](https://github.com/gatsbyjs/gatsby/issues/22823) [#22830](https://github.com/gatsbyjs/gatsby/issues/22830) [#22861](https://github.com/gatsbyjs/gatsby/issues/22861) [#22864](https://github.com/gatsbyjs/gatsby/issues/22864) [#22876](https://github.com/gatsbyjs/gatsby/issues/22876) [#22885](https://github.com/gatsbyjs/gatsby/issues/22885) [#22889](https://github.com/gatsbyjs/gatsby/issues/22889) [#22891](https://github.com/gatsbyjs/gatsby/issues/22891) [#22909](https://github.com/gatsbyjs/gatsby/issues/22909) [#22911](https://github.com/gatsbyjs/gatsby/issues/22911) [#22648](https://github.com/gatsbyjs/gatsby/issues/22648) [#22903](https://github.com/gatsbyjs/gatsby/issues/22903) [#22901](https://github.com/gatsbyjs/gatsby/issues/22901) [#22902](https://github.com/gatsbyjs/gatsby/issues/22902) [#22895](https://github.com/gatsbyjs/gatsby/issues/22895) [#22900](https://github.com/gatsbyjs/gatsby/issues/22900) [#22772](https://github.com/gatsbyjs/gatsby/issues/22772) [#22653](https://github.com/gatsbyjs/gatsby/issues/22653) [#22628](https://github.com/gatsbyjs/gatsby/issues/22628) [#22882](https://github.com/gatsbyjs/gatsby/issues/22882) [#22708](https://github.com/gatsbyjs/gatsby/issues/22708) [#22871](https://github.com/gatsbyjs/gatsby/issues/22871) [#22863](https://github.com/gatsbyjs/gatsby/issues/22863) [#22874](https://github.com/gatsbyjs/gatsby/issues/22874) [#22851](https://github.com/gatsbyjs/gatsby/issues/22851) [#22870](https://github.com/gatsbyjs/gatsby/issues/22870) [#22786](https://github.com/gatsbyjs/gatsby/issues/22786) [#22687](https://github.com/gatsbyjs/gatsby/issues/22687) [#22866](https://github.com/gatsbyjs/gatsby/issues/22866) [#22666](https://github.com/gatsbyjs/gatsby/issues/22666) [#22865](https://github.com/gatsbyjs/gatsby/issues/22865) [#22820](https://github.com/gatsbyjs/gatsby/issues/22820) [#22793](https://github.com/gatsbyjs/gatsby/issues/22793) [#4](https://github.com/gatsbyjs/gatsby/issues/4) [#22796](https://github.com/gatsbyjs/gatsby/issues/22796) [#22775](https://github.com/gatsbyjs/gatsby/issues/22775) [#22835](https://github.com/gatsbyjs/gatsby/issues/22835) [#22767](https://github.com/gatsbyjs/gatsby/issues/22767) [#22850](https://github.com/gatsbyjs/gatsby/issues/22850) [#22836](https://github.com/gatsbyjs/gatsby/issues/22836) [#22800](https://github.com/gatsbyjs/gatsby/issues/22800) [#22801](https://github.com/gatsbyjs/gatsby/issues/22801) [#21847](https://github.com/gatsbyjs/gatsby/issues/21847) [#22808](https://github.com/gatsbyjs/gatsby/issues/22808) [#22828](https://github.com/gatsbyjs/gatsby/issues/22828) [#22815](https://github.com/gatsbyjs/gatsby/issues/22815) [#22827](https://github.com/gatsbyjs/gatsby/issues/22827) [#22848](https://github.com/gatsbyjs/gatsby/issues/22848) [#22845](https://github.com/gatsbyjs/gatsby/issues/22845) [#22839](https://github.com/gatsbyjs/gatsby/issues/22839) [#22837](https://github.com/gatsbyjs/gatsby/issues/22837) [#22787](https://github.com/gatsbyjs/gatsby/issues/22787) [#22362](https://github.com/gatsbyjs/gatsby/issues/22362) [#22769](https://github.com/gatsbyjs/gatsby/issues/22769) [#22756](https://github.com/gatsbyjs/gatsby/issues/22756) [#22712](https://github.com/gatsbyjs/gatsby/issues/22712) [#22698](https://github.com/gatsbyjs/gatsby/issues/22698) [#22371](https://github.com/gatsbyjs/gatsby/issues/22371) [#22790](https://github.com/gatsbyjs/gatsby/issues/22790) [#22824](https://github.com/gatsbyjs/gatsby/issues/22824) [#22797](https://github.com/gatsbyjs/gatsby/issues/22797) [#22803](https://github.com/gatsbyjs/gatsby/issues/22803) [#22819](https://github.com/gatsbyjs/gatsby/issues/22819) [#22807](https://github.com/gatsbyjs/gatsby/issues/22807) [#22802](https://github.com/gatsbyjs/gatsby/issues/22802) [#22771](https://github.com/gatsbyjs/gatsby/issues/22771) [#22799](https://github.com/gatsbyjs/gatsby/issues/22799) [#22791](https://github.com/gatsbyjs/gatsby/issues/22791) [#22779](https://github.com/gatsbyjs/gatsby/issues/22779) [#22780](https://github.com/gatsbyjs/gatsby/issues/22780) [#22766](https://github.com/gatsbyjs/gatsby/issues/22766) [#22760](https://github.com/gatsbyjs/gatsby/issues/22760) [#22710](https://github.com/gatsbyjs/gatsby/issues/22710) [#22563](https://github.com/gatsbyjs/gatsby/issues/22563) [#22752](https://github.com/gatsbyjs/gatsby/issues/22752) [#22738](https://github.com/gatsbyjs/gatsby/issues/22738) [#22770](https://github.com/gatsbyjs/gatsby/issues/22770) [#22740](https://github.com/gatsbyjs/gatsby/issues/22740) [#22781](https://github.com/gatsbyjs/gatsby/issues/22781) [#22692](https://github.com/gatsbyjs/gatsby/issues/22692) [#22686](https://github.com/gatsbyjs/gatsby/issues/22686) [#22736](https://github.com/gatsbyjs/gatsby/issues/22736) [#22761](https://github.com/gatsbyjs/gatsby/issues/22761) [#22690](https://github.com/gatsbyjs/gatsby/issues/22690) [#22729](https://github.com/gatsbyjs/gatsby/issues/22729) [#22732](https://github.com/gatsbyjs/gatsby/issues/22732) [#22745](https://github.com/gatsbyjs/gatsby/issues/22745) [#22737](https://github.com/gatsbyjs/gatsby/issues/22737) [#22739](https://github.com/gatsbyjs/gatsby/issues/22739) [#22727](https://github.com/gatsbyjs/gatsby/issues/22727) [#22603](https://github.com/gatsbyjs/gatsby/issues/22603) [#22723](https://github.com/gatsbyjs/gatsby/issues/22723) [#22720](https://github.com/gatsbyjs/gatsby/issues/22720) [#22705](https://github.com/gatsbyjs/gatsby/issues/22705) [#22604](https://github.com/gatsbyjs/gatsby/issues/22604) [#22716](https://github.com/gatsbyjs/gatsby/issues/22716) [#22699](https://github.com/gatsbyjs/gatsby/issues/22699) [#22953](https://github.com/gatsbyjs/gatsby/issues/22953) [#22986](https://github.com/gatsbyjs/gatsby/issues/22986) [#22987](https://github.com/gatsbyjs/gatsby/issues/22987) [#23003](https://github.com/gatsbyjs/gatsby/issues/23003) [#23064](https://github.com/gatsbyjs/gatsby/issues/23064) [#23063](https://github.com/gatsbyjs/gatsby/issues/23063) [#23076](https://github.com/gatsbyjs/gatsby/issues/23076) [#23079](https://github.com/gatsbyjs/gatsby/issues/23079) [#23083](https://github.com/gatsbyjs/gatsby/issues/23083) [#23085](https://github.com/gatsbyjs/gatsby/issues/23085) [#23084](https://github.com/gatsbyjs/gatsby/issues/23084) [#23086](https://github.com/gatsbyjs/gatsby/issues/23086) [#23108](https://github.com/gatsbyjs/gatsby/issues/23108) [#23112](https://github.com/gatsbyjs/gatsby/issues/23112) [#23078](https://github.com/gatsbyjs/gatsby/issues/23078) [#23117](https://github.com/gatsbyjs/gatsby/issues/23117) [#23119](https://github.com/gatsbyjs/gatsby/issues/23119) [#23122](https://github.com/gatsbyjs/gatsby/issues/23122) [#23113](https://github.com/gatsbyjs/gatsby/issues/23113) [#23111](https://github.com/gatsbyjs/gatsby/issues/23111) [#23103](https://github.com/gatsbyjs/gatsby/issues/23103) [#23072](https://github.com/gatsbyjs/gatsby/issues/23072) [#23100](https://github.com/gatsbyjs/gatsby/issues/23100) [#23073](https://github.com/gatsbyjs/gatsby/issues/23073) [#23096](https://github.com/gatsbyjs/gatsby/issues/23096) [#23080](https://github.com/gatsbyjs/gatsby/issues/23080) [#23095](https://github.com/gatsbyjs/gatsby/issues/23095) [#23043](https://github.com/gatsbyjs/gatsby/issues/23043) [#22932](https://github.com/gatsbyjs/gatsby/issues/22932) [#23075](https://github.com/gatsbyjs/gatsby/issues/23075) [#23074](https://github.com/gatsbyjs/gatsby/issues/23074) [#23089](https://github.com/gatsbyjs/gatsby/issues/23089) [#23088](https://github.com/gatsbyjs/gatsby/issues/23088) [#23065](https://github.com/gatsbyjs/gatsby/issues/23065) [#23055](https://github.com/gatsbyjs/gatsby/issues/23055) [#23022](https://github.com/gatsbyjs/gatsby/issues/23022) [#23069](https://github.com/gatsbyjs/gatsby/issues/23069) [#23070](https://github.com/gatsbyjs/gatsby/issues/23070) [#23068](https://github.com/gatsbyjs/gatsby/issues/23068) [#23066](https://github.com/gatsbyjs/gatsby/issues/23066) [#23067](https://github.com/gatsbyjs/gatsby/issues/23067) [#22954](https://github.com/gatsbyjs/gatsby/issues/22954) [#22883](https://github.com/gatsbyjs/gatsby/issues/22883) [#22858](https://github.com/gatsbyjs/gatsby/issues/22858) [#22788](https://github.com/gatsbyjs/gatsby/issues/22788) [#23060](https://github.com/gatsbyjs/gatsby/issues/23060) [#23028](https://github.com/gatsbyjs/gatsby/issues/23028) [#23056](https://github.com/gatsbyjs/gatsby/issues/23056) [#23021](https://github.com/gatsbyjs/gatsby/issues/23021) [#23048](https://github.com/gatsbyjs/gatsby/issues/23048) [#23053](https://github.com/gatsbyjs/gatsby/issues/23053) [#23042](https://github.com/gatsbyjs/gatsby/issues/23042) [#22960](https://github.com/gatsbyjs/gatsby/issues/22960) [#23025](https://github.com/gatsbyjs/gatsby/issues/23025) [#23046](https://github.com/gatsbyjs/gatsby/issues/23046) [#23009](https://github.com/gatsbyjs/gatsby/issues/23009) [#23034](https://github.com/gatsbyjs/gatsby/issues/23034) [#23036](https://github.com/gatsbyjs/gatsby/issues/23036) [#22965](https://github.com/gatsbyjs/gatsby/issues/22965) [#22843](https://github.com/gatsbyjs/gatsby/issues/22843) [#22703](https://github.com/gatsbyjs/gatsby/issues/22703) [#23029](https://github.com/gatsbyjs/gatsby/issues/23029) [#23017](https://github.com/gatsbyjs/gatsby/issues/23017) [#23014](https://github.com/gatsbyjs/gatsby/issues/23014) [#23016](https://github.com/gatsbyjs/gatsby/issues/23016) [#23015](https://github.com/gatsbyjs/gatsby/issues/23015) [#22985](https://github.com/gatsbyjs/gatsby/issues/22985) [#21907](https://github.com/gatsbyjs/gatsby/issues/21907) [#23008](https://github.com/gatsbyjs/gatsby/issues/23008) [#22750](https://github.com/gatsbyjs/gatsby/issues/22750) [#23007](https://github.com/gatsbyjs/gatsby/issues/23007) [#23001](https://github.com/gatsbyjs/gatsby/issues/23001) [#22881](https://github.com/gatsbyjs/gatsby/issues/22881) [#23000](https://github.com/gatsbyjs/gatsby/issues/23000) [#22638](https://github.com/gatsbyjs/gatsby/issues/22638) [#22854](https://github.com/gatsbyjs/gatsby/issues/22854) [#22993](https://github.com/gatsbyjs/gatsby/issues/22993) [#22872](https://github.com/gatsbyjs/gatsby/issues/22872) [#22893](https://github.com/gatsbyjs/gatsby/issues/22893) [#22992](https://github.com/gatsbyjs/gatsby/issues/22992) [#22297](https://github.com/gatsbyjs/gatsby/issues/22297) [#22984](https://github.com/gatsbyjs/gatsby/issues/22984) [#22942](https://github.com/gatsbyjs/gatsby/issues/22942) [#22981](https://github.com/gatsbyjs/gatsby/issues/22981) [#22967](https://github.com/gatsbyjs/gatsby/issues/22967) [#22966](https://github.com/gatsbyjs/gatsby/issues/22966) [#22544](https://github.com/gatsbyjs/gatsby/issues/22544) [#22696](https://github.com/gatsbyjs/gatsby/issues/22696) [#22747](https://github.com/gatsbyjs/gatsby/issues/22747) [#22774](https://github.com/gatsbyjs/gatsby/issues/22774) [#22929](https://github.com/gatsbyjs/gatsby/issues/22929) [#22898](https://github.com/gatsbyjs/gatsby/issues/22898) [#22943](https://github.com/gatsbyjs/gatsby/issues/22943) [#22873](https://github.com/gatsbyjs/gatsby/issues/22873) [#22617](https://github.com/gatsbyjs/gatsby/issues/22617) [#22798](https://github.com/gatsbyjs/gatsby/issues/22798) [#22956](https://github.com/gatsbyjs/gatsby/issues/22956) [#22860](https://github.com/gatsbyjs/gatsby/issues/22860) [#22944](https://github.com/gatsbyjs/gatsby/issues/22944) [#22946](https://github.com/gatsbyjs/gatsby/issues/22946) [#22947](https://github.com/gatsbyjs/gatsby/issues/22947) [#22961](https://github.com/gatsbyjs/gatsby/issues/22961) [#22959](https://github.com/gatsbyjs/gatsby/issues/22959) [#22810](https://github.com/gatsbyjs/gatsby/issues/22810) [#22869](https://github.com/gatsbyjs/gatsby/issues/22869) [#22879](https://github.com/gatsbyjs/gatsby/issues/22879) [#23138](https://github.com/gatsbyjs/gatsby/issues/23138) [#23146](https://github.com/gatsbyjs/gatsby/issues/23146) [#23154](https://github.com/gatsbyjs/gatsby/issues/23154) [#23152](https://github.com/gatsbyjs/gatsby/issues/23152) [#23168](https://github.com/gatsbyjs/gatsby/issues/23168) [#23169](https://github.com/gatsbyjs/gatsby/issues/23169) [#23175](https://github.com/gatsbyjs/gatsby/issues/23175)

## [2.20.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.20...gatsby@2.20.22) (2020-04-15)

**Note:** Version bump only for package gatsby

## [2.20.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.19...gatsby@2.20.20) (2020-04-14)

### Performance Improvements

- **gatsby:** Support `lte` for indexed fast filters ([#22932](https://github.com/gatsbyjs/gatsby/issues/22932)) ([fd57224](https://github.com/gatsbyjs/gatsby/commit/fd57224))

## [2.20.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.18...gatsby@2.20.19) (2020-04-14)

### Bug Fixes

- **gatsby:** call schema rebuild manually on \_\_refresh ([#23009](https://github.com/gatsbyjs/gatsby/issues/23009)) ([8493de8](https://github.com/gatsbyjs/gatsby/commit/8493de8))
- **gatsby:** Set a timeout of 15 seconds on queries ([#23036](https://github.com/gatsbyjs/gatsby/issues/23036)) ([1e81c76](https://github.com/gatsbyjs/gatsby/commit/1e81c76))
- Ensure component order is deterministic ([#22965](https://github.com/gatsbyjs/gatsby/issues/22965)) ([94267be](https://github.com/gatsbyjs/gatsby/commit/94267be))

## [2.20.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.17...gatsby@2.20.18) (2020-04-11)

### Bug Fixes

- **gatsby:** Use `moveSync` over `renameSync` to fix cross mount cases ([#23029](https://github.com/gatsbyjs/gatsby/issues/23029)) ([96f8d4b](https://github.com/gatsbyjs/gatsby/commit/96f8d4b))

## [2.20.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.16...gatsby@2.20.17) (2020-04-10)

**Note:** Version bump only for package gatsby

## [2.20.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.15...gatsby@2.20.16) (2020-04-10)

### Bug Fixes

- **gatsby:** Use tmp dir for tmp redux cache folder ([#22959](https://github.com/gatsbyjs/gatsby/issues/22959)) ([86cf920](https://github.com/gatsbyjs/gatsby/commit/86cf920))

## [2.20.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.14...gatsby@2.20.15) (2020-04-09)

### Bug Fixes

- **gatsby:** improve async commons chunking ([#22879](https://github.com/gatsbyjs/gatsby/issues/22879)) ([7cf056f](https://github.com/gatsbyjs/gatsby/commit/7cf056f))

## [2.20.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.13...gatsby@2.20.14) (2020-04-08)

### Performance Improvements

- **gatsby:** support `elemMatch` as fast filter ([#22742](https://github.com/gatsbyjs/gatsby/issues/22742)) ([66b3d35](https://github.com/gatsbyjs/gatsby/commit/66b3d35))

## [2.20.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.12...gatsby@2.20.13) (2020-04-07)

**Note:** Version bump only for package gatsby

## [2.20.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.11...gatsby@2.20.12) (2020-04-03)

### Bug Fixes

- **gatsby:** Fix OOM from telemetry storing too much ([#22752](https://github.com/gatsbyjs/gatsby/issues/22752)) ([a7281c2](https://github.com/gatsbyjs/gatsby/commit/a7281c2))

## [2.20.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.10...gatsby@2.20.11) (2020-04-03)

### Bug Fixes

- **gatsby:** Support grouping by reserved keywords ([#22603](https://github.com/gatsbyjs/gatsby/issues/22603)) ([ad6bc16](https://github.com/gatsbyjs/gatsby/commit/ad6bc16))

## [2.20.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.9...gatsby@2.20.10) (2020-04-01)

### Bug Fixes

- **core:** Add gatsby/graphql type definitions ([#22652](https://github.com/gatsbyjs/gatsby/issues/22652)) ([ac205cf](https://github.com/gatsbyjs/gatsby/commit/ac205cf))

## [2.20.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.8...gatsby@2.20.9) (2020-03-30)

### Bug Fixes

- **gatsby:** Collect nested webpack compilation stats errors ([#22598](https://github.com/gatsbyjs/gatsby/issues/22598)) ([3986380](https://github.com/gatsbyjs/gatsby/commit/3986380)), closes [#22597](https://github.com/gatsbyjs/gatsby/issues/22597)

## [2.20.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.7...gatsby@2.20.8) (2020-03-27)

### Bug Fixes

- **gatsby:** Mark plugin parameter as optional for actions ([#22546](https://github.com/gatsbyjs/gatsby/issues/22546)) ([6d1356c](https://github.com/gatsbyjs/gatsby/commit/6d1356c))

## [2.20.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.6...gatsby@2.20.7) (2020-03-26)

### Features

- **gatsby:** enable granular chunks ([#22253](https://github.com/gatsbyjs/gatsby/issues/22253)) ([0f02ea7](https://github.com/gatsbyjs/gatsby/commit/0f02ea7))

## [2.20.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.5...gatsby@2.20.6) (2020-03-25)

### Features

- **gatsby-telemetry:** Make build collect GraphQL/Sift query data for telemetry ([#22540](https://github.com/gatsbyjs/gatsby/issues/22540)) ([1bec140](https://github.com/gatsbyjs/gatsby/commit/1bec140))

## [2.20.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.4...gatsby@2.20.5) (2020-03-25)

### Features

- **gatsby-source-graphql:** Query batching ([#22347](https://github.com/gatsbyjs/gatsby/issues/22347)) ([2a4c7fd](https://github.com/gatsbyjs/gatsby/commit/2a4c7fd))

## [2.20.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.3...gatsby@2.20.4) (2020-03-24)

### Bug Fixes

- **docs:** remove double words ([#22494](https://github.com/gatsbyjs/gatsby/issues/22494)) ([75f6ee2](https://github.com/gatsbyjs/gatsby/commit/75f6ee2))

## [2.20.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.2...gatsby@2.20.3) (2020-03-23)

**Note:** Version bump only for package gatsby

## [2.20.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.1...gatsby@2.20.2) (2020-03-20)

**Note:** Version bump only for package gatsby

## [2.20.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.20.0...gatsby@2.20.1) (2020-03-20)

**Note:** Version bump only for package gatsby

# [2.20.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.50...gatsby@2.20.0) (2020-03-20)

### Features

- **gatsby:** bump node min version to 10.13.0 ([#22400](https://github.com/gatsbyjs/gatsby/issues/22400)) ([83d681a](https://github.com/gatsbyjs/gatsby/commit/83d681a))

## [2.19.50](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.49...gatsby@2.19.50) (2020-03-20)

### Bug Fixes

- **gatsby:** Incorrect PackageJson type ([#22406](https://github.com/gatsbyjs/gatsby/issues/22406)) ([5496e6b](https://github.com/gatsbyjs/gatsby/commit/5496e6b))

## [2.19.49](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.48...gatsby@2.19.49) (2020-03-19)

**Note:** Version bump only for package gatsby

## [2.19.48](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.47...gatsby@2.19.48) (2020-03-18)

**Note:** Version bump only for package gatsby

## [2.19.47](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.46...gatsby@2.19.47) (2020-03-18)

**Note:** Version bump only for package gatsby

## [2.19.46](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.45...gatsby@2.19.46) (2020-03-18)

### Bug Fixes

- update dependency axios to ^0.19.2 ([#22317](https://github.com/gatsbyjs/gatsby/issues/22317)) ([91e780f](https://github.com/gatsbyjs/gatsby/commit/91e780f))
- update dependency mini-css-extract-plugin ([#22320](https://github.com/gatsbyjs/gatsby/issues/22320)) ([d5c936e](https://github.com/gatsbyjs/gatsby/commit/d5c936e))
- update dependency webpack-stats-plugin to ^0.3.1 ([#22325](https://github.com/gatsbyjs/gatsby/issues/22325)) ([cc75305](https://github.com/gatsbyjs/gatsby/commit/cc75305))
- update minor updates in packages ([#22329](https://github.com/gatsbyjs/gatsby/issues/22329)) ([bfb864b](https://github.com/gatsbyjs/gatsby/commit/bfb864b))

## [2.19.45](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.44...gatsby@2.19.45) (2020-03-16)

**Note:** Version bump only for package gatsby

## [2.19.44](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.43...gatsby@2.19.44) (2020-03-16)

**Note:** Version bump only for package gatsby

## [2.19.43](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.42...gatsby@2.19.43) (2020-03-13)

### Bug Fixes

- **gatsby:** render <RouteAnnouncer> in html ([#21625](https://github.com/gatsbyjs/gatsby/issues/21625)) ([2fdd518](https://github.com/gatsbyjs/gatsby/commit/2fdd518))

## [2.19.42](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.41...gatsby@2.19.42) (2020-03-13)

### Bug Fixes

- **gatsby:** make SSR more compatible with PnP (fixes gatsby-plugin-sitemap usage in PnP) ([#21976](https://github.com/gatsbyjs/gatsby/issues/21976)) ([2eb8861](https://github.com/gatsbyjs/gatsby/commit/2eb8861))
- ensure that errorParser always returns something ([#20749](https://github.com/gatsbyjs/gatsby/issues/20749)) ([2688f29](https://github.com/gatsbyjs/gatsby/commit/2688f29))

## [2.19.41](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.40...gatsby@2.19.41) (2020-03-12)

### Bug Fixes

- runtime network/resource loading resilience fixes + restore e2e tests for it ([#18051](https://github.com/gatsbyjs/gatsby/issues/18051)) ([030d927](https://github.com/gatsbyjs/gatsby/commit/030d927))

## [2.19.40](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.39...gatsby@2.19.40) (2020-03-12)

### Bug Fixes

- **gatsby:** Show meaningful error when directory names are too long ([#21518](https://github.com/gatsbyjs/gatsby/issues/21518)) ([4404af1](https://github.com/gatsbyjs/gatsby/commit/4404af1))

## [2.19.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.38...gatsby@2.19.39) (2020-03-11)

### Features

- **gatsby:** Support FastRefresh for development hot reloading ([#21534](https://github.com/gatsbyjs/gatsby/issues/21534)) ([205847b](https://github.com/gatsbyjs/gatsby/commit/205847b))

## [2.19.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.37...gatsby@2.19.38) (2020-03-11)

**Note:** Version bump only for package gatsby

## [2.19.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.36...gatsby@2.19.37) (2020-03-11)

**Note:** Version bump only for package gatsby

## [2.19.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.35...gatsby@2.19.36) (2020-03-10)

**Note:** Version bump only for package gatsby

## [2.19.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.34...gatsby@2.19.35) (2020-03-10)

### Bug Fixes

- **gatsby:** Update types for WrapPageElement\*Args ([#22120](https://github.com/gatsbyjs/gatsby/issues/22120)) ([97fa23e](https://github.com/gatsbyjs/gatsby/commit/97fa23e)), closes [#21542](https://github.com/gatsbyjs/gatsby/issues/21542)

### Performance Improvements

- **gatsby:** more efficient parent-child check through arrays ([#22126](https://github.com/gatsbyjs/gatsby/issues/22126)) ([be7111b](https://github.com/gatsbyjs/gatsby/commit/be7111b))

## [2.19.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.33...gatsby@2.19.34) (2020-03-09)

**Note:** Version bump only for package gatsby

## [2.19.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.32...gatsby@2.19.33) (2020-03-09)

**Note:** Version bump only for package gatsby

## [2.19.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.31...gatsby@2.19.32) (2020-03-06)

**Note:** Version bump only for package gatsby

## [2.19.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.30...gatsby@2.19.31) (2020-03-06)

**Note:** Version bump only for package gatsby

## [2.19.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.29...gatsby@2.19.30) (2020-03-06)

### Bug Fixes

- **gatsby:** Prevent cache invalidation case for loki ([#22009](https://github.com/gatsbyjs/gatsby/issues/22009)) ([b5942d6](https://github.com/gatsbyjs/gatsby/commit/b5942d6))

## [2.19.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.28...gatsby@2.19.29) (2020-03-05)

**Note:** Version bump only for package gatsby

## [2.19.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.27...gatsby@2.19.28) (2020-03-04)

### Bug Fixes

- **gatsby:** Resolve linked interfaces consistently with objec… ([#21936](https://github.com/gatsbyjs/gatsby/issues/21936)) ([bd5bdd1](https://github.com/gatsbyjs/gatsby/commit/bd5bdd1))

## [2.19.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.26...gatsby@2.19.27) (2020-03-03)

### Features

- **gatsby:** Page build optimisations for incremental data changes ([#21523](https://github.com/gatsbyjs/gatsby/issues/21523)) ([c49d7b4](https://github.com/gatsbyjs/gatsby/commit/c49d7b4))

## [2.19.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.25...gatsby@2.19.26) (2020-03-03)

### Features

- **gatsby:** add react profiling option ([#21863](https://github.com/gatsbyjs/gatsby/issues/21863)) ([3e8f2c7](https://github.com/gatsbyjs/gatsby/commit/3e8f2c7))

## [2.19.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.24...gatsby@2.19.25) (2020-03-02)

### Bug Fixes

- **gatsby:** bump flex-bug postcss-plugin and postcss-loader ([#21398](https://github.com/gatsbyjs/gatsby/issues/21398)) ([47b05fc](https://github.com/gatsbyjs/gatsby/commit/47b05fc))
- **gatsby:** Check for nullable locations in query-runner ([#21839](https://github.com/gatsbyjs/gatsby/issues/21839)) ([dc484eb](https://github.com/gatsbyjs/gatsby/commit/dc484eb))
- **gatsby:** fix codepaths that result in js errors ([#21829](https://github.com/gatsbyjs/gatsby/issues/21829)) ([a87f1bd](https://github.com/gatsbyjs/gatsby/commit/a87f1bd))
- **gatsby:** Improve warning for built-in GraphQL type overrides ([#21899](https://github.com/gatsbyjs/gatsby/issues/21899)) ([1f4db4b](https://github.com/gatsbyjs/gatsby/commit/1f4db4b))
- hot fix for `gatsby develop` when HOME is not set ([#21914](https://github.com/gatsbyjs/gatsby/issues/21914)) ([b6de2b9](https://github.com/gatsbyjs/gatsby/commit/b6de2b9))

### Features

- **gatsby:** Allow silencing the warning for adding resolvers for missing types ([#21769](https://github.com/gatsbyjs/gatsby/issues/21769)) ([6b7ed63](https://github.com/gatsbyjs/gatsby/commit/6b7ed63))

## [2.19.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.23...gatsby@2.19.24) (2020-03-02)

### Bug Fixes

- **gatsby:** Improve error message when EnsureResources fails to ensure a resource ([#21429](https://github.com/gatsbyjs/gatsby/issues/21429)) ([7527993](https://github.com/gatsbyjs/gatsby/commit/7527993))
- **gatsby:** Switching from devcert-san to devcert to fix HTTP… ([#16726](https://github.com/gatsbyjs/gatsby/issues/16726)) ([22ead19](https://github.com/gatsbyjs/gatsby/commit/22ead19)), closes [#16212](https://github.com/gatsbyjs/gatsby/issues/16212)

## [2.19.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.22...gatsby@2.19.23) (2020-02-28)

### Bug Fixes

- Remove global namespace hack for a proper workflow ([#21591](https://github.com/gatsbyjs/gatsby/issues/21591)) ([4bc595b](https://github.com/gatsbyjs/gatsby/commit/4bc595b))

## [2.19.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.21...gatsby@2.19.22) (2020-02-25)

### Bug Fixes

- **gatsby:** Chunk nodes when serializing redux to prevent OOM ([#21555](https://github.com/gatsbyjs/gatsby/issues/21555)) ([c944aae](https://github.com/gatsbyjs/gatsby/commit/c944aae)), closes [#17233](https://github.com/gatsbyjs/gatsby/issues/17233)

## [2.19.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.20...gatsby@2.19.21) (2020-02-24)

**Note:** Version bump only for package gatsby

## [2.19.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.19...gatsby@2.19.20) (2020-02-24)

### Bug Fixes

- **gatsby:** add app-data to preload list ([#21537](https://github.com/gatsbyjs/gatsby/issues/21537)) ([ad92e13](https://github.com/gatsbyjs/gatsby/commit/ad92e13))
- **gatsby:** Fix wrongly skipping graphql filter cache ([#21578](https://github.com/gatsbyjs/gatsby/issues/21578)) ([4f68761](https://github.com/gatsbyjs/gatsby/commit/4f68761))

## [2.19.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.18...gatsby@2.19.19) (2020-02-20)

### Bug Fixes

- **gatsby:** Fix static query parsing for a special case ([#21551](https://github.com/gatsbyjs/gatsby/issues/21551)) ([dd344ac](https://github.com/gatsbyjs/gatsby/commit/dd344ac))

## [2.19.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.17...gatsby@2.19.18) (2020-02-17)

### Bug Fixes

- **gatsby:** Fix an edge case with sift queries using index ([#21458](https://github.com/gatsbyjs/gatsby/issues/21458)) ([b7e6bb1](https://github.com/gatsbyjs/gatsby/commit/b7e6bb1))

## [2.19.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.16...gatsby@2.19.17) (2020-02-13)

### Bug Fixes

- **gatsby:** add onPostBuild activity ([#21366](https://github.com/gatsbyjs/gatsby/issues/21366)) ([6780461](https://github.com/gatsbyjs/gatsby/commit/6780461))
- **gatsby:** Reset graphql runner on certain node events ([#20586](https://github.com/gatsbyjs/gatsby/issues/20586)) ([ef72f2b](https://github.com/gatsbyjs/gatsby/commit/ef72f2b))
- **gatsby:** revert auto-adding id field to queries ([#21216](https://github.com/gatsbyjs/gatsby/issues/21216)) ([e1fd083](https://github.com/gatsbyjs/gatsby/commit/e1fd083)), closes [#20943](https://github.com/gatsbyjs/gatsby/issues/20943)
- **gatsby:** Use argument for updating cache ([#21365](https://github.com/gatsbyjs/gatsby/issues/21365)) ([fb36368](https://github.com/gatsbyjs/gatsby/commit/fb36368)), closes [/github.com/gatsbyjs/gatsby/pull/20729#pullrequestreview-350948674](https://github.com//github.com/gatsbyjs/gatsby/pull/20729/issues/pullrequestreview-350948674)

## [2.19.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.15...gatsby@2.19.16) (2020-02-11)

### Features

- **www:** Convert API pages to MDX ([#20763](https://github.com/gatsbyjs/gatsby/issues/20763)) ([c905014](https://github.com/gatsbyjs/gatsby/commit/c905014))

## [2.19.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.14...gatsby@2.19.15) (2020-02-10)

**Note:** Version bump only for package gatsby

## [2.19.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.13...gatsby@2.19.14) (2020-02-10)

**Note:** Version bump only for package gatsby

## [2.19.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.12...gatsby@2.19.13) (2020-02-10)

**Note:** Version bump only for package gatsby

## [2.19.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.11...gatsby@2.19.12) (2020-02-02)

### Bug Fixes

- **gatsby:** Pin reach since they do not pass in location.href… ([#21144](https://github.com/gatsbyjs/gatsby/issues/21144)) ([f7d2f03](https://github.com/gatsbyjs/gatsby/commit/f7d2f03))

## [2.19.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.10...gatsby@2.19.11) (2020-02-01)

### Bug Fixes

- **gatsby:** Fix invalid algorithm of fragment cycles detection ([#21128](https://github.com/gatsbyjs/gatsby/issues/21128)) ([f570db3](https://github.com/gatsbyjs/gatsby/commit/f570db3))
- **gatsby:** fix onCreatePage typings ([#20871](https://github.com/gatsbyjs/gatsby/issues/20871)) ([26e0cbc](https://github.com/gatsbyjs/gatsby/commit/26e0cbc))

## [2.19.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.9...gatsby@2.19.10) (2020-01-29)

### Bug Fixes

- **gatsby-plugin-mdx:** support yarn PnP ([#20638](https://github.com/gatsbyjs/gatsby/issues/20638)) ([6375ba9](https://github.com/gatsbyjs/gatsby/commit/6375ba9))

## [2.19.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.8...gatsby@2.19.9) (2020-01-29)

### Bug Fixes

- **gatsby:** Do not add field `id` to the query when `id` alias exists ([#20980](https://github.com/gatsbyjs/gatsby/issues/20980)) ([acf2c35](https://github.com/gatsbyjs/gatsby/commit/acf2c35))
- **gatsby:** Fix potential issue in fragment cycles detection ([#20953](https://github.com/gatsbyjs/gatsby/issues/20953)) ([c6f4c62](https://github.com/gatsbyjs/gatsby/commit/c6f4c62))

## [2.19.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.7...gatsby@2.19.8) (2020-01-28)

### Bug Fixes

- **gatsby:** Fix stack overflow on queries with circular fragments ([#20936](https://github.com/gatsbyjs/gatsby/issues/20936)) ([094ca4c](https://github.com/gatsbyjs/gatsby/commit/094ca4c))
- **gatsby:** remove role alert on gatsby-announcer ([#20914](https://github.com/gatsbyjs/gatsby/issues/20914)) ([0008bc4](https://github.com/gatsbyjs/gatsby/commit/0008bc4))
- **gatsby:** structured error might be a string ([#20909](https://github.com/gatsbyjs/gatsby/issues/20909)) ([7e40b21](https://github.com/gatsbyjs/gatsby/commit/7e40b21))

### Performance Improvements

- **gatsby:** Create index on the fly for non-id index ([#20729](https://github.com/gatsbyjs/gatsby/issues/20729)) ([115d5c4](https://github.com/gatsbyjs/gatsby/commit/115d5c4))

## [2.19.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.6...gatsby@2.19.7) (2020-01-27)

### Bug Fixes

- wrap `GraphQLRunner.query` return in Promise.resolve ([#20904](https://github.com/gatsbyjs/gatsby/issues/20904)) ([86d3cda](https://github.com/gatsbyjs/gatsby/commit/86d3cda))

## [2.19.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.5...gatsby@2.19.6) (2020-01-27)

### Bug Fixes

- **gatsby:** Add `__typename` and `id` fields in queries to ma… ([#20849](https://github.com/gatsbyjs/gatsby/issues/20849)) ([4d27336](https://github.com/gatsbyjs/gatsby/commit/4d27336))

## [2.19.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.4...gatsby@2.19.5) (2020-01-24)

### Features

- **gatsby:** enable external jobs with ipc ([#20835](https://github.com/gatsbyjs/gatsby/issues/20835)) ([b4c5bfb](https://github.com/gatsbyjs/gatsby/commit/b4c5bfb))

## [2.19.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.3...gatsby@2.19.4) (2020-01-24)

### Bug Fixes

- **gatsby:** revert [#19664](https://github.com/gatsbyjs/gatsby/issues/19664) fix duplicate runs in develop mode ([#20836](https://github.com/gatsbyjs/gatsby/issues/20836)) ([9419bb3](https://github.com/gatsbyjs/gatsby/commit/9419bb3))

## [2.19.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.2...gatsby@2.19.3) (2020-01-23)

### Bug Fixes

- remove 1px line from gatsby-announcer on 100vh pages ([#20781](https://github.com/gatsbyjs/gatsby/issues/20781)) ([3880394](https://github.com/gatsbyjs/gatsby/commit/3880394))
- **chore:** remove processing and waiting queue ([#20757](https://github.com/gatsbyjs/gatsby/issues/20757)) ([c2ecb3a](https://github.com/gatsbyjs/gatsby/commit/c2ecb3a))

## [2.19.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.1...gatsby@2.19.2) (2020-01-23)

### Bug Fixes

- **gatsby:** Improve `gatsby` TS types for `sourceNodes` ([#20397](https://github.com/gatsbyjs/gatsby/issues/20397)) ([2a1508e](https://github.com/gatsbyjs/gatsby/commit/2a1508e))

## [2.19.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.19.0...gatsby@2.19.1) (2020-01-21)

### Bug Fixes

- **gatsby:** use slash from gatsby-core-utils ([#20744](https://github.com/gatsbyjs/gatsby/issues/20744)) ([00f3190](https://github.com/gatsbyjs/gatsby/commit/00f3190))

# [2.19.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.25...gatsby@2.19.0) (2020-01-21)

### Features

- **gatsby:** enable Jobs API v2 ([#19858](https://github.com/gatsbyjs/gatsby/issues/19858)) ([039c601](https://github.com/gatsbyjs/gatsby/commit/039c601)), closes [#19831](https://github.com/gatsbyjs/gatsby/issues/19831)

## [2.18.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.24...gatsby@2.18.25) (2020-01-17)

### Performance Improvements

- **gatsby:** cache parsing and validation results in graphql-runner ([#20477](https://github.com/gatsbyjs/gatsby/issues/20477)) ([ac7c79f](https://github.com/gatsbyjs/gatsby/commit/ac7c79f))

## [2.18.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.23...gatsby@2.18.24) (2020-01-17)

### Bug Fixes

- **gatsby:** Respect `[@dont](https://github.com/dont)Infer` directive on `SitePage` type ([#20662](https://github.com/gatsbyjs/gatsby/issues/20662)) ([631ba49](https://github.com/gatsbyjs/gatsby/commit/631ba49))

## [2.18.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.22...gatsby@2.18.23) (2020-01-16)

### Performance Improvements

- **gatsby:** Create one promise per queue, not one per job ([#20606](https://github.com/gatsbyjs/gatsby/issues/20606)) ([79eb6de](https://github.com/gatsbyjs/gatsby/commit/79eb6de))
- **gatsby:** Shortcut trivial queries by id ([#20609](https://github.com/gatsbyjs/gatsby/issues/20609)) ([fa4ff69](https://github.com/gatsbyjs/gatsby/commit/fa4ff69))
- **gatsby:** Use a Map instead of Object for job id lookups ([#20605](https://github.com/gatsbyjs/gatsby/issues/20605)) ([54fb530](https://github.com/gatsbyjs/gatsby/commit/54fb530))

## [2.18.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.21...gatsby@2.18.22) (2020-01-14)

### Bug Fixes

- **gatsby:** fix error cannot read referencePath of undefined ([#20517](https://github.com/gatsbyjs/gatsby/issues/20517)) ([c759a7d](https://github.com/gatsbyjs/gatsby/commit/c759a7d))
- **typing:** more precise typing for ssr api ([#20564](https://github.com/gatsbyjs/gatsby/issues/20564)) ([b53ec9a](https://github.com/gatsbyjs/gatsby/commit/b53ec9a))

### Features

- **gatsby:** Supports multiple development proxies ([#20369](https://github.com/gatsbyjs/gatsby/issues/20369)) ([8d1e37a](https://github.com/gatsbyjs/gatsby/commit/8d1e37a))

## [2.18.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.20...gatsby@2.18.21) (2020-01-09)

**Note:** Version bump only for package gatsby

## [2.18.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.18...gatsby@2.18.20) (2020-01-09)

### Bug Fixes

- **gatsby:** webpack /_ webpackPrefetch/webpackPreload _/ comments causing a bug ([#20403](https://github.com/gatsbyjs/gatsby/issues/20403)) ([1b89b10](https://github.com/gatsbyjs/gatsby/commit/1b89b10))

### Features

- **gatsby:** Allow alternative import syntax for useStaticQuery ([#20330](https://github.com/gatsbyjs/gatsby/issues/20330)) ([17eaa72](https://github.com/gatsbyjs/gatsby/commit/17eaa72))

## [2.18.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.18...gatsby@2.18.19) (2020-01-09)

### Bug Fixes

- **gatsby:** webpack /_ webpackPrefetch/webpackPreload _/ comments causing a bug ([#20403](https://github.com/gatsbyjs/gatsby/issues/20403)) ([1b89b10](https://github.com/gatsbyjs/gatsby/commit/1b89b10))

### Features

- **gatsby:** Allow alternative import syntax for useStaticQuery ([#20330](https://github.com/gatsbyjs/gatsby/issues/20330)) ([17eaa72](https://github.com/gatsbyjs/gatsby/commit/17eaa72))

## [2.18.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.17...gatsby@2.18.18) (2020-01-06)

**Note:** Version bump only for package gatsby

## [2.18.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.16...gatsby@2.18.17) (2019-12-23)

### Bug Fixes

- **gatsby:** don't write out `isCreatedByStatefulCreatePages` to page-data files ([#20241](https://github.com/gatsbyjs/gatsby/issues/20241)) ([4b113bd](https://github.com/gatsbyjs/gatsby/commit/4b113bd))

### Features

- **gatsby:** Improve structured errors around GraphQL ([#20120](https://github.com/gatsbyjs/gatsby/issues/20120)) ([a5740f9](https://github.com/gatsbyjs/gatsby/commit/a5740f9))

## [2.18.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.15...gatsby@2.18.16) (2019-12-20)

### Bug Fixes

- **gatsby:** enable static queries in `wrapRootElement` ([#19986](https://github.com/gatsbyjs/gatsby/issues/19986)) ([c591eb7](https://github.com/gatsbyjs/gatsby/commit/c591eb7))

### Features

- **gatsby:** bundle and page-data stats for telemetry ([#20146](https://github.com/gatsbyjs/gatsby/issues/20146)) ([3fe97f2](https://github.com/gatsbyjs/gatsby/commit/3fe97f2))

## [2.18.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.14...gatsby@2.18.15) (2019-12-19)

### Bug Fixes

- **gatsby:** Fix sift query against empty nodes ([#20212](https://github.com/gatsbyjs/gatsby/issues/20212)) ([6beeec3](https://github.com/gatsbyjs/gatsby/commit/6beeec3))

## [2.18.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.13...gatsby@2.18.14) (2019-12-18)

### Bug Fixes

- **gatsby:** add ./ prefix to paths in async-requires ([#20169](https://github.com/gatsbyjs/gatsby/issues/20169)) ([4f2154a](https://github.com/gatsbyjs/gatsby/commit/4f2154a))
- **gatsby:** do not rebuild schema having identical conflicts ([#20099](https://github.com/gatsbyjs/gatsby/issues/20099)) ([0d14926](https://github.com/gatsbyjs/gatsby/commit/0d14926))
- **gatsby:** support file inference for any field name (not just [a-zA-Z0-9_]) ([#20186](https://github.com/gatsbyjs/gatsby/issues/20186)) ([b681959](https://github.com/gatsbyjs/gatsby/commit/b681959))
- **gatsby:** support unicode characters for 404 page ([#20165](https://github.com/gatsbyjs/gatsby/issues/20165)) ([51474e8](https://github.com/gatsbyjs/gatsby/commit/51474e8))
- **gatsby-telemetry:** only report unique plugins ([#20147](https://github.com/gatsbyjs/gatsby/issues/20147)) ([4c138d5](https://github.com/gatsbyjs/gatsby/commit/4c138d5))

## [2.18.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.12...gatsby@2.18.13) (2019-12-17)

### Bug Fixes

- **gatsby:** fix circular ref stack overflow checks ([#20039](https://github.com/gatsbyjs/gatsby/issues/20039)) ([f780d21](https://github.com/gatsbyjs/gatsby/commit/f780d21))

### Features

- **gatsby:** Use webpack watchOptions config for webpack-dev-middleware ([#20067](https://github.com/gatsbyjs/gatsby/issues/20067)) ([aff5540](https://github.com/gatsbyjs/gatsby/commit/aff5540))

### Performance Improvements

- **gatsby:** Eliminate generator ([#20102](https://github.com/gatsbyjs/gatsby/issues/20102)) ([c3ca41a](https://github.com/gatsbyjs/gatsby/commit/c3ca41a))

## [2.18.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.11...gatsby@2.18.12) (2019-12-15)

**Note:** Version bump only for package gatsby

## [2.18.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.10...gatsby@2.18.11) (2019-12-11)

### Bug Fixes

- **gatsby:** Add early return in link resolver for empty arrays ([#20068](https://github.com/gatsbyjs/gatsby/issues/20068)) ([3e2ad17](https://github.com/gatsbyjs/gatsby/commit/3e2ad17))
- **gatsby:** remove default noscript tag from html.js template ([#20023](https://github.com/gatsbyjs/gatsby/issues/20023)) ([ebdaf6d](https://github.com/gatsbyjs/gatsby/commit/ebdaf6d))

## [2.18.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.8...gatsby@2.18.10) (2019-12-10)

**Note:** Version bump only for package gatsby

## [2.18.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.8...gatsby@2.18.9) (2019-12-10)

**Note:** Version bump only for package gatsby

## [2.18.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.7...gatsby@2.18.8) (2019-12-09)

### Bug Fixes

- **gatsby:** Ensure the number of jest-workers respects GATSBY_CPU_COUNT env var ([#19975](https://github.com/gatsbyjs/gatsby/issues/19975)) ([ce53d81](https://github.com/gatsbyjs/gatsby/commit/ce53d81))

## [2.18.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.6...gatsby@2.18.7) (2019-12-05)

### Bug Fixes

- **gatsby:** support union types for one-to-one \_\_\_NODE relations ([#19916](https://github.com/gatsbyjs/gatsby/issues/19916)) ([44875b8](https://github.com/gatsbyjs/gatsby/commit/44875b8))

### Features

- **gatsby:** add all rules from eslint-plugin-jsx-a11y ([#19946](https://github.com/gatsbyjs/gatsby/issues/19946)) ([000bef3](https://github.com/gatsbyjs/gatsby/commit/000bef3))

## [2.18.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.5...gatsby@2.18.6) (2019-12-02)

### Bug Fixes

- **gatsby:** use correct state in the schema hot reloader ([#19862](https://github.com/gatsbyjs/gatsby/issues/19862)) ([f92cb9c](https://github.com/gatsbyjs/gatsby/commit/f92cb9c))

## [2.18.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.4...gatsby@2.18.5) (2019-11-28)

### Bug Fixes

- **gatsby:** Call cwd() when called instead of on import ([#19800](https://github.com/gatsbyjs/gatsby/issues/19800)) ([451a489](https://github.com/gatsbyjs/gatsby/commit/451a489))
- **gatsby:** do not cause stack overflow over circular refs ([#19802](https://github.com/gatsbyjs/gatsby/issues/19802)) ([89c6b89](https://github.com/gatsbyjs/gatsby/commit/89c6b89)), closes [#11364](https://github.com/gatsbyjs/gatsby/issues/11364)

### Performance Improvements

- **gatsby:** Avoid unnecessary type inference during bootstrap ([#19781](https://github.com/gatsbyjs/gatsby/issues/19781)) ([006ecd8](https://github.com/gatsbyjs/gatsby/commit/006ecd8))

## [2.18.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.3...gatsby@2.18.4) (2019-11-26)

### Bug Fixes

- **gatsby:** Remove relay compiler & use our own ([#19665](https://github.com/gatsbyjs/gatsby/issues/19665)) ([bda9f1f](https://github.com/gatsbyjs/gatsby/commit/bda9f1f))
- update minor updates in packages ([#19776](https://github.com/gatsbyjs/gatsby/issues/19776)) ([559beb2](https://github.com/gatsbyjs/gatsby/commit/559beb2))
- **gatsby:** memoize shadowCreatePagePath to fix performance r… ([#19774](https://github.com/gatsbyjs/gatsby/issues/19774)) ([3043786](https://github.com/gatsbyjs/gatsby/commit/3043786))

## [2.18.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.2...gatsby@2.18.3) (2019-11-25)

**Note:** Version bump only for package gatsby

## [2.18.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.1...gatsby@2.18.2) (2019-11-22)

### Bug Fixes

- **gatsby:** Clean up third party schema customizations to avoid schema rebuilding failure ([#19712](https://github.com/gatsbyjs/gatsby/issues/19712)) ([b703ab1](https://github.com/gatsbyjs/gatsby/commit/b703ab1))
- **gatsby:** Fix createRequireFromPath deprecation warning ([#19677](https://github.com/gatsbyjs/gatsby/issues/19677)) ([78a7858](https://github.com/gatsbyjs/gatsby/commit/78a7858))
- **gatsby:** Improve warning message about implicit child fields ([#19657](https://github.com/gatsbyjs/gatsby/issues/19657)) ([3501267](https://github.com/gatsbyjs/gatsby/commit/3501267))

### Performance Improvements

- **gatsby:** perf problem for match-page search in large sites ([#19691](https://github.com/gatsbyjs/gatsby/issues/19691)) ([58b89fa](https://github.com/gatsbyjs/gatsby/commit/58b89fa)), closes [#19512](https://github.com/gatsbyjs/gatsby/issues/19512)

## [2.18.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.18.0...gatsby@2.18.1) (2019-11-20)

### Bug Fixes

- **gatsby:** don't rerun static queries if text didn't change ([#19616](https://github.com/gatsbyjs/gatsby/issues/19616)) ([824b685](https://github.com/gatsbyjs/gatsby/commit/824b685))
- **gatsby:** Improve discoverPluginsWithoutNodes performance ([#19594](https://github.com/gatsbyjs/gatsby/issues/19594)) ([83f3f0f](https://github.com/gatsbyjs/gatsby/commit/83f3f0f))
- **reporter:** TypeScript definitions for Reporter ([#19189](https://github.com/gatsbyjs/gatsby/issues/19189)) ([02ddd46](https://github.com/gatsbyjs/gatsby/commit/02ddd46)), closes [#19025](https://github.com/gatsbyjs/gatsby/issues/19025)

### Features

- **gatsby:** add plugin data to `gatsby develop` telemetry to… ([#19623](https://github.com/gatsbyjs/gatsby/issues/19623)) ([3c559c9](https://github.com/gatsbyjs/gatsby/commit/3c559c9))
- **gatsby:** Enable shadowing of page template queries ([#17681](https://github.com/gatsbyjs/gatsby/issues/17681)) ([6a82da8](https://github.com/gatsbyjs/gatsby/commit/6a82da8))

# [2.18.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.17...gatsby@2.18.0) (2019-11-19)

### Features

- **gatsby:** Schema rebuilding ([#19092](https://github.com/gatsbyjs/gatsby/issues/19092)) ([e4dae4d](https://github.com/gatsbyjs/gatsby/commit/e4dae4d))

## [2.17.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.16...gatsby@2.17.17) (2019-11-18)

### Bug Fixes

- **gatsby:** Handle special characters in windows paths ([#19600](https://github.com/gatsbyjs/gatsby/issues/19600)) ([9929cf0](https://github.com/gatsbyjs/gatsby/commit/9929cf0))
- **gatsby:** Improve perf of stale node detection ([#19599](https://github.com/gatsbyjs/gatsby/issues/19599)) ([2e8f381](https://github.com/gatsbyjs/gatsby/commit/2e8f381))

## [2.17.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.15...gatsby@2.17.16) (2019-11-18)

### Bug Fixes

- **gatsby:** Fix filtering on resolvable children ([#19586](https://github.com/gatsbyjs/gatsby/issues/19586)) ([7b500f4](https://github.com/gatsbyjs/gatsby/commit/7b500f4))

## [2.17.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.14...gatsby@2.17.15) (2019-11-15)

### Bug Fixes

- **gatsby:** createIndexHtml call missing activity ([#19544](https://github.com/gatsbyjs/gatsby/issues/19544)) ([b2df860](https://github.com/gatsbyjs/gatsby/commit/b2df860))

## [2.17.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.13...gatsby@2.17.14) (2019-11-15)

### Bug Fixes

- update dependency babel-plugin-dynamic-import-node to v2 ([#19535](https://github.com/gatsbyjs/gatsby/issues/19535)) ([500ebf6](https://github.com/gatsbyjs/gatsby/commit/500ebf6))
- update dependency convert-hrtime to v3 ([#19530](https://github.com/gatsbyjs/gatsby/issues/19530)) ([1a5ddc5](https://github.com/gatsbyjs/gatsby/commit/1a5ddc5))
- update dependency copyfiles to v2 ([#19531](https://github.com/gatsbyjs/gatsby/issues/19531)) ([1f9a2b5](https://github.com/gatsbyjs/gatsby/commit/1f9a2b5))

## [2.17.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.12...gatsby@2.17.13) (2019-11-13)

### Bug Fixes

- **gatsby:** Use crossorigin for link in linkPrefetch strategy ([#17581](https://github.com/gatsbyjs/gatsby/issues/17581)) ([2aac625](https://github.com/gatsbyjs/gatsby/commit/2aac625))

## [2.17.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.11...gatsby@2.17.12) (2019-11-13)

### Bug Fixes

- **gatsby:** add / to prefix when stripping prefixes ([#17544](https://github.com/gatsbyjs/gatsby/issues/17544)) ([58fe032](https://github.com/gatsbyjs/gatsby/commit/58fe032))
- **gatsby:** controlled search input component on dev-404-page ([#19168](https://github.com/gatsbyjs/gatsby/issues/19168)) ([d65183b](https://github.com/gatsbyjs/gatsby/commit/d65183b))
- **gatsby:** Ensure inferred types do not conflict with types created via schema customization ([#19338](https://github.com/gatsbyjs/gatsby/issues/19338)) ([3565d5a](https://github.com/gatsbyjs/gatsby/commit/3565d5a))
- **gatsby:** non-latin hash link ([#19376](https://github.com/gatsbyjs/gatsby/issues/19376)) ([8938c95](https://github.com/gatsbyjs/gatsby/commit/8938c95))
- **gatsby:** Re-use plugin resolution logic for theme dir resolution ([#19470](https://github.com/gatsbyjs/gatsby/issues/19470)) ([52be765](https://github.com/gatsbyjs/gatsby/commit/52be765))
- update minor updates in packages ([#19423](https://github.com/gatsbyjs/gatsby/issues/19423)) ([9935376](https://github.com/gatsbyjs/gatsby/commit/9935376))

## [2.17.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.10...gatsby@2.17.11) (2019-11-10)

**Note:** Version bump only for package gatsby

## [2.17.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.9...gatsby@2.17.10) (2019-11-06)

### Bug Fixes

- **gatsby:** Use CWD to get name if not specified in package.j… ([#19304](https://github.com/gatsbyjs/gatsby/issues/19304)) ([d50ddbc](https://github.com/gatsbyjs/gatsby/commit/d50ddbc))

## [2.17.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.8...gatsby@2.17.9) (2019-11-05)

### Bug Fixes

- **requires-writer:** use `@reach/router` path ranking algorit… ([#19050](https://github.com/gatsbyjs/gatsby/issues/19050)) ([813c191](https://github.com/gatsbyjs/gatsby/commit/813c191))

## [2.17.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.7...gatsby@2.17.8) (2019-11-04)

### Bug Fixes

- **gatsby:** clear cache before refresh ([#19159](https://github.com/gatsbyjs/gatsby/issues/19159)) ([4d5d780](https://github.com/gatsbyjs/gatsby/commit/4d5d780))
- **gatsby:** Fix flatMap import in schema/print.js ([#19208](https://github.com/gatsbyjs/gatsby/issues/19208)) ([0471751](https://github.com/gatsbyjs/gatsby/commit/0471751))
- **webpack-utils:** compact user JS only in production builds ([#19240](https://github.com/gatsbyjs/gatsby/issues/19240)) ([982fd22](https://github.com/gatsbyjs/gatsby/commit/982fd22)), closes [#19128](https://github.com/gatsbyjs/gatsby/issues/19128)

## [2.17.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.6...gatsby@2.17.7) (2019-10-29)

### Bug Fixes

- update minor updates in packages ([#19087](https://github.com/gatsbyjs/gatsby/issues/19087)) ([294a48f](https://github.com/gatsbyjs/gatsby/commit/294a48f))

### Features

- **gatsby:** enable local themes ([#15856](https://github.com/gatsbyjs/gatsby/issues/15856)) ([bd85555](https://github.com/gatsbyjs/gatsby/commit/bd85555))

## [2.17.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.5...gatsby@2.17.6) (2019-10-28)

### Bug Fixes

- update minor updates in packages ([#19086](https://github.com/gatsbyjs/gatsby/issues/19086)) ([54565f0](https://github.com/gatsbyjs/gatsby/commit/54565f0))

## [2.17.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.4...gatsby@2.17.5) (2019-10-28)

### Bug Fixes

- update minor updates in packages ([#19080](https://github.com/gatsbyjs/gatsby/issues/19080)) ([95e908e](https://github.com/gatsbyjs/gatsby/commit/95e908e))
- **gatsby:** Remove internal Node modules in getNonGatsbyCallS… ([#19009](https://github.com/gatsbyjs/gatsby/issues/19009)) ([467aa54](https://github.com/gatsbyjs/gatsby/commit/467aa54))
- update minor updates in packages ([#18875](https://github.com/gatsbyjs/gatsby/issues/18875)) ([b692879](https://github.com/gatsbyjs/gatsby/commit/b692879))

### Features

- **redirects:** allow multiple redirects from same path when they have different options ([#19048](https://github.com/gatsbyjs/gatsby/issues/19048)) ([84f8aea](https://github.com/gatsbyjs/gatsby/commit/84f8aea))

## [2.17.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.3...gatsby@2.17.4) (2019-10-25)

### Bug Fixes

- **gatsby:** fix hashes used in webpack for output ([#18973](https://github.com/gatsbyjs/gatsby/issues/18973)) ([76ac266](https://github.com/gatsbyjs/gatsby/commit/76ac266))

## [2.17.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.2...gatsby@2.17.3) (2019-10-25)

### Bug Fixes

- **gatsby:** Fix matchpath ordering ([#18478](https://github.com/gatsbyjs/gatsby/issues/18478)) ([b8aa333](https://github.com/gatsbyjs/gatsby/commit/b8aa333))

## [2.17.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.1...gatsby@2.17.2) (2019-10-23)

### Bug Fixes

- fix overriding default options of `gatsby-plugin-page-creator` on Windows ([#18828](https://github.com/gatsbyjs/gatsby/issues/18828)) ([fc61f06](https://github.com/gatsbyjs/gatsby/commit/fc61f06))
- **gatsby:** ensure `[@child](https://github.com/child)Of` adds convenience fields before root field arguments ([#18935](https://github.com/gatsbyjs/gatsby/issues/18935)) ([366d915](https://github.com/gatsbyjs/gatsby/commit/366d915))

### Features

- **gatsby:** Ensure status is set to Failed for thrown errors or panicOnBuild in plugins ([#18887](https://github.com/gatsbyjs/gatsby/issues/18887)) ([d7950e1](https://github.com/gatsbyjs/gatsby/commit/d7950e1))

## [2.17.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.17.0...gatsby@2.17.1) (2019-10-22)

**Note:** Version bump only for package gatsby

# [2.17.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.16.5...gatsby@2.17.0) (2019-10-21)

### Features

- **gatsby:** Move webpackCompilationHash into app-data.json ([#16686](https://github.com/gatsbyjs/gatsby/issues/16686)) ([ebff315](https://github.com/gatsbyjs/gatsby/commit/ebff315))

## [2.16.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.16.4...gatsby@2.16.5) (2019-10-18)

**Note:** Version bump only for package gatsby

## [2.16.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.16.3...gatsby@2.16.4) (2019-10-17)

**Note:** Version bump only for package gatsby

## [2.16.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.16.2...gatsby@2.16.3) (2019-10-15)

### Performance Improvements

- **schema:** speed up and lower memory usage of type inference ([#18008](https://github.com/gatsbyjs/gatsby/issues/18008)) ([e87ac50](https://github.com/gatsbyjs/gatsby/commit/e87ac50))

## [2.16.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.16.1...gatsby@2.16.2) (2019-10-15)

### Bug Fixes

- **gatsby:** create page dependencies from contextual node model methods even if no path is passed ([#18650](https://github.com/gatsbyjs/gatsby/issues/18650)) ([3d38af2](https://github.com/gatsbyjs/gatsby/commit/3d38af2))
- **gatsby:** Extend fields when merging types ([#18500](https://github.com/gatsbyjs/gatsby/issues/18500)) ([302aa26](https://github.com/gatsbyjs/gatsby/commit/302aa26))

## [2.16.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.16.0...gatsby@2.16.1) (2019-10-14)

### Bug Fixes

- **gatsby:** Fix sort for Node 12 ([#18502](https://github.com/gatsbyjs/gatsby/issues/18502)) ([d2869ad](https://github.com/gatsbyjs/gatsby/commit/d2869ad))
- update dependency autoprefixer to ^9.6.5 ([#18598](https://github.com/gatsbyjs/gatsby/issues/18598)) ([1525257](https://github.com/gatsbyjs/gatsby/commit/1525257))
- update dependency core-js to ^2.6.10 ([#18569](https://github.com/gatsbyjs/gatsby/issues/18569)) ([7a20eb7](https://github.com/gatsbyjs/gatsby/commit/7a20eb7))

# [2.16.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.37...gatsby@2.16.0) (2019-10-14)

### Features

- **gatsby:** structured logging ([#14973](https://github.com/gatsbyjs/gatsby/issues/14973)) ([eafb8c6](https://github.com/gatsbyjs/gatsby/commit/eafb8c6))

## [2.15.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.36...gatsby@2.15.37) (2019-10-14)

### Bug Fixes

- update dependency webpack to v4.41.1 ([#18504](https://github.com/gatsbyjs/gatsby/issues/18504)) ([a93df04](https://github.com/gatsbyjs/gatsby/commit/a93df04))

## [2.15.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.35...gatsby@2.15.36) (2019-10-11)

### Bug Fixes

- **gatsby:** update location state when location.key changes ([#18039](https://github.com/gatsbyjs/gatsby/issues/18039)) ([de3f323](https://github.com/gatsbyjs/gatsby/commit/de3f323))

## [2.15.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.34...gatsby@2.15.35) (2019-10-10)

**Note:** Version bump only for package gatsby

## [2.15.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.33...gatsby@2.15.34) (2019-10-09)

**Note:** Version bump only for package gatsby

## [2.15.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.32...gatsby@2.15.33) (2019-10-08)

**Note:** Version bump only for package gatsby

## [2.15.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.31...gatsby@2.15.32) (2019-10-08)

### Bug Fixes

- **gatsby:** In public actions, don't let actionOptions overwr… ([#18302](https://github.com/gatsbyjs/gatsby/issues/18302)) ([014b95e](https://github.com/gatsbyjs/gatsby/commit/014b95e))

## [2.15.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.30...gatsby@2.15.31) (2019-10-08)

### Bug Fixes

- update dependency react-hot-loader to ^4.12.15 ([#18295](https://github.com/gatsbyjs/gatsby/issues/18295)) ([7c3e8b3](https://github.com/gatsbyjs/gatsby/commit/7c3e8b3))

## [2.15.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.29...gatsby@2.15.30) (2019-10-08)

### Bug Fixes

- update dependency autoprefixer to ^9.6.4 ([#18204](https://github.com/gatsbyjs/gatsby/issues/18204)) ([b31fc56](https://github.com/gatsbyjs/gatsby/commit/b31fc56))
- update dependency eslint-plugin-react to ^7.16.0 ([#18119](https://github.com/gatsbyjs/gatsby/issues/18119)) ([a8144ee](https://github.com/gatsbyjs/gatsby/commit/a8144ee))
- **gatsby:** catch more browser only variable for SSR error ([#18112](https://github.com/gatsbyjs/gatsby/issues/18112)) ([e9ef934](https://github.com/gatsbyjs/gatsby/commit/e9ef934))

## [2.15.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.28...gatsby@2.15.29) (2019-10-04)

### Bug Fixes

- update dependency bluebird to ^3.7.0 ([#18029](https://github.com/gatsbyjs/gatsby/issues/18029)) ([bd235a8](https://github.com/gatsbyjs/gatsby/commit/bd235a8))
- update dependency chokidar to v3.2.1 ([#18009](https://github.com/gatsbyjs/gatsby/issues/18009)) ([4df0306](https://github.com/gatsbyjs/gatsby/commit/4df0306))
- update dependency eslint-plugin-react to ^7.15.0 ([#18010](https://github.com/gatsbyjs/gatsby/issues/18010)) ([6a5cd19](https://github.com/gatsbyjs/gatsby/commit/6a5cd19))
- update dependency eslint-plugin-react to ^7.15.1 ([#18031](https://github.com/gatsbyjs/gatsby/issues/18031)) ([8d5597f](https://github.com/gatsbyjs/gatsby/commit/8d5597f))
- update dependency webpack-dev-server to ^3.8.2 ([#18055](https://github.com/gatsbyjs/gatsby/issues/18055)) ([aa540c3](https://github.com/gatsbyjs/gatsby/commit/aa540c3))
- **gatsby:** Fix not materializing concrete fields ([#17942](https://github.com/gatsbyjs/gatsby/issues/17942)) ([8439305](https://github.com/gatsbyjs/gatsby/commit/8439305))

## [2.15.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.26...gatsby@2.15.28) (2019-09-26)

### Bug Fixes

- **gatsby:** console output: npm run build -> gatsby build ([#17896](https://github.com/gatsbyjs/gatsby/issues/17896)) ([fbbf406](https://github.com/gatsbyjs/gatsby/commit/fbbf406))

## [2.15.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.26...gatsby@2.15.27) (2019-09-26)

### Bug Fixes

- **gatsby:** console output: npm run build -> gatsby build ([#17896](https://github.com/gatsbyjs/gatsby/issues/17896)) ([fbbf406](https://github.com/gatsbyjs/gatsby/commit/fbbf406))

## [2.15.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.25...gatsby@2.15.26) (2019-09-25)

**Note:** Version bump only for package gatsby

## [2.15.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.24...gatsby@2.15.25) (2019-09-25)

### Bug Fixes

- **gatsby:** don't add undefined ([#17886](https://github.com/gatsbyjs/gatsby/issues/17886)) ([f0cdef0](https://github.com/gatsbyjs/gatsby/commit/f0cdef0))

## [2.15.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.23...gatsby@2.15.24) (2019-09-25)

### Bug Fixes

- **query:** improve query performance ([#17682](https://github.com/gatsbyjs/gatsby/issues/17682)) ([a1b1396](https://github.com/gatsbyjs/gatsby/commit/a1b1396))

## [2.15.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.22...gatsby@2.15.23) (2019-09-25)

### Bug Fixes

- **gatsby:** remove 404 pagedata logic on client side pages ([#17412](https://github.com/gatsbyjs/gatsby/issues/17412)) ([6c64948](https://github.com/gatsbyjs/gatsby/commit/6c64948))
- update dependency webpack to ~4.41.0 ([#17863](https://github.com/gatsbyjs/gatsby/issues/17863)) ([9c24bca](https://github.com/gatsbyjs/gatsby/commit/9c24bca))
- **gatsby:** prevent unmount wrapPageElement while page-data l… ([#17111](https://github.com/gatsbyjs/gatsby/issues/17111)) ([610b581](https://github.com/gatsbyjs/gatsby/commit/610b581))

### Features

- **gatsby-telemetry:** add exitCode to `BUILD_END` event ([#17847](https://github.com/gatsbyjs/gatsby/issues/17847)) ([6ab4de6](https://github.com/gatsbyjs/gatsby/commit/6ab4de6))

## [2.15.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.21...gatsby@2.15.22) (2019-09-24)

### Bug Fixes

- update dependency react-hot-loader to ^4.12.14 ([#17817](https://github.com/gatsbyjs/gatsby/issues/17817)) ([9e9dc3b](https://github.com/gatsbyjs/gatsby/commit/9e9dc3b))

## [2.15.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.20...gatsby@2.15.21) (2019-09-23)

### Bug Fixes

- update dependency is-wsl to ^2.1.1 ([#17815](https://github.com/gatsbyjs/gatsby/issues/17815)) ([1287648](https://github.com/gatsbyjs/gatsby/commit/1287648))

## [2.15.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.19...gatsby@2.15.20) (2019-09-20)

### Bug Fixes

- **gatsby:** add timeout so fetching API info doesn't fail on very slow connections ([#17735](https://github.com/gatsbyjs/gatsby/issues/17735)) ([e85278c](https://github.com/gatsbyjs/gatsby/commit/e85278c))
- update dependency eslint-plugin-graphql to ^3.1.0 ([#17775](https://github.com/gatsbyjs/gatsby/issues/17775)) ([5f4db21](https://github.com/gatsbyjs/gatsby/commit/5f4db21))
- update dependency socket.io to ^2.3.0 ([#17760](https://github.com/gatsbyjs/gatsby/issues/17760)) ([1ef5053](https://github.com/gatsbyjs/gatsby/commit/1ef5053))

## [2.15.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.18...gatsby@2.15.19) (2019-09-20)

### Bug Fixes

- **gatsby:** support `export { X as default }` syntax when checking if page template files have default export ([#17752](https://github.com/gatsbyjs/gatsby/issues/17752)) ([b785583](https://github.com/gatsbyjs/gatsby/commit/b785583))

## [2.15.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.17...gatsby@2.15.18) (2019-09-18)

**Note:** Version bump only for package gatsby

## [2.15.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.16...gatsby@2.15.17) (2019-09-18)

### Bug Fixes

- update dependency webpack-dev-server to ^3.8.1 ([#17669](https://github.com/gatsbyjs/gatsby/issues/17669)) ([97f328c](https://github.com/gatsbyjs/gatsby/commit/97f328c))

## [2.15.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.15...gatsby@2.15.16) (2019-09-16)

### Bug Fixes

- update dependency @babel/parser to ^7.6.0 ([#17620](https://github.com/gatsbyjs/gatsby/issues/17620)) ([2d942ed](https://github.com/gatsbyjs/gatsby/commit/2d942ed))

## [2.15.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.14...gatsby@2.15.15) (2019-09-13)

### Bug Fixes

- update dependency react-hot-loader to ^4.12.13 ([#17580](https://github.com/gatsbyjs/gatsby/issues/17580)) ([d43d2be](https://github.com/gatsbyjs/gatsby/commit/d43d2be))
- update minor updates in packages except react, babel and eslint ([#17601](https://github.com/gatsbyjs/gatsby/issues/17601)) ([588cd8f](https://github.com/gatsbyjs/gatsby/commit/588cd8f))

## [2.15.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.13...gatsby@2.15.14) (2019-09-10)

**Note:** Version bump only for package gatsby

## [2.15.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.12...gatsby@2.15.13) (2019-09-09)

### Bug Fixes

- **gatsby:** fix node internal validation ([#17511](https://github.com/gatsbyjs/gatsby/issues/17511)) ([97a720d](https://github.com/gatsbyjs/gatsby/commit/97a720d))

## [2.15.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.11...gatsby@2.15.12) (2019-09-09)

### Bug Fixes

- **gatsby:** move default-site-plugin lower than plugin page-creation ([#17409](https://github.com/gatsbyjs/gatsby/issues/17409)) ([4af8a59](https://github.com/gatsbyjs/gatsby/commit/4af8a59))

## [2.15.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.10...gatsby@2.15.11) (2019-09-09)

### Bug Fixes

- **gatsby:** Allow overriding options for default instance of gatsby-plugin-page-creator ([#17420](https://github.com/gatsbyjs/gatsby/issues/17420)) ([9bdeda4](https://github.com/gatsbyjs/gatsby/commit/9bdeda4))

## [2.15.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.9...gatsby@2.15.10) (2019-09-09)

### Bug Fixes

- **gatsby:** fix mapping stack trace to source file after dependency upgrade ([#17445](https://github.com/gatsbyjs/gatsby/issues/17445)) ([f38d8c7](https://github.com/gatsbyjs/gatsby/commit/f38d8c7))
- **gatsby:** Handle Windows drive letter casing correctly ([#17492](https://github.com/gatsbyjs/gatsby/issues/17492)) ([beddfb8](https://github.com/gatsbyjs/gatsby/commit/beddfb8))
- **gatsby:** Use concrete type resolver on interface fields ([#17284](https://github.com/gatsbyjs/gatsby/issues/17284)) ([fd72133](https://github.com/gatsbyjs/gatsby/commit/fd72133))

## [2.15.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.8...gatsby@2.15.9) (2019-09-05)

**Note:** Version bump only for package gatsby

## [2.15.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.7...gatsby@2.15.8) (2019-09-05)

### Bug Fixes

- **gatsby:** order matchpaths paths by specificity ([#17411](https://github.com/gatsbyjs/gatsby/issues/17411)) ([2968413](https://github.com/gatsbyjs/gatsby/commit/2968413))

## [2.15.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.6...gatsby@2.15.7) (2019-09-04)

**Note:** Version bump only for package gatsby

## [2.15.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.5...gatsby@2.15.6) (2019-09-04)

### Features

- **gatsby:** enable page-creator on all themes ([#16698](https://github.com/gatsbyjs/gatsby/issues/16698)) ([7398da4](https://github.com/gatsbyjs/gatsby/commit/7398da4))

## [2.15.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.4...gatsby@2.15.5) (2019-09-03)

### Bug Fixes

- update dependency webpack-dev-middleware to ^3.7.1 ([#17343](https://github.com/gatsbyjs/gatsby/issues/17343)) ([a578f4e](https://github.com/gatsbyjs/gatsby/commit/a578f4e))

## [2.15.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.3...gatsby@2.15.4) (2019-09-03)

**Note:** Version bump only for package gatsby

## [2.15.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.2...gatsby@2.15.3) (2019-09-02)

**Note:** Version bump only for package gatsby

## [2.15.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.1...gatsby@2.15.2) (2019-09-01)

### Bug Fixes

- **gatsby:** fix an infinite loop in node child collection ([#17078](https://github.com/gatsbyjs/gatsby/issues/17078)) ([240b4f8](https://github.com/gatsbyjs/gatsby/commit/240b4f8))
- **gatsby-cli:** Open Lan URL if Windows ([#16769](https://github.com/gatsbyjs/gatsby/issues/16769)) ([b2a2d6b](https://github.com/gatsbyjs/gatsby/commit/b2a2d6b))
- update minor updates in packages except react, babel and eslint ([#17254](https://github.com/gatsbyjs/gatsby/issues/17254)) ([252d867](https://github.com/gatsbyjs/gatsby/commit/252d867))

## [2.15.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.15.0...gatsby@2.15.1) (2019-08-30)

**Note:** Version bump only for package gatsby

# [2.15.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.7...gatsby@2.15.0) (2019-08-30)

### Features

- **gatsby:** Materialization ([#16091](https://github.com/gatsbyjs/gatsby/issues/16091)) ([ac10d3d](https://github.com/gatsbyjs/gatsby/commit/ac10d3d))

## [2.14.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.6...gatsby@2.14.7) (2019-08-30)

**Note:** Version bump only for package gatsby

## [2.14.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.5...gatsby@2.14.6) (2019-08-29)

**Note:** Version bump only for package gatsby

## [2.14.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.4...gatsby@2.14.5) (2019-08-29)

### Bug Fixes

- update minor updates in packages except react, babel and eslint ([#17178](https://github.com/gatsbyjs/gatsby/issues/17178)) ([77dad68](https://github.com/gatsbyjs/gatsby/commit/77dad68))

## [2.14.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.3...gatsby@2.14.4) (2019-08-29)

### Bug Fixes

- **gatsby:** revert redirects map to array ([#17168](https://github.com/gatsbyjs/gatsby/issues/17168)) ([b553891](https://github.com/gatsbyjs/gatsby/commit/b553891))

## [2.14.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.2...gatsby@2.14.3) (2019-08-29)

### Bug Fixes

- update dependency react-hot-loader to ^4.12.12 ([#17103](https://github.com/gatsbyjs/gatsby/issues/17103)) ([41f60b7](https://github.com/gatsbyjs/gatsby/commit/41f60b7))

## [2.14.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.1...gatsby@2.14.2) (2019-08-28)

### Bug Fixes

- **gatsby:** Release stdio streams when exiting `gatsby develop` ([#16714](https://github.com/gatsbyjs/gatsby/issues/16714)) ([280cf7f](https://github.com/gatsbyjs/gatsby/commit/280cf7f))

## [2.14.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.14.0...gatsby@2.14.1) (2019-08-28)

**Note:** Version bump only for package gatsby

# [2.14.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.83...gatsby@2.14.0) (2019-08-26)

### Bug Fixes

- update dependency address to v1.1.2 ([#17083](https://github.com/gatsbyjs/gatsby/issues/17083)) ([1f9664a](https://github.com/gatsbyjs/gatsby/commit/1f9664a))

### Features

- **gatsby:** add better splitchunks config ([#17093](https://github.com/gatsbyjs/gatsby/issues/17093)) ([fc93b7b](https://github.com/gatsbyjs/gatsby/commit/fc93b7b))

## [2.13.83](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.82...gatsby@2.13.83) (2019-08-25)

### Bug Fixes

- update dependency babel-eslint to ^10.0.3 ([#17071](https://github.com/gatsbyjs/gatsby/issues/17071)) ([28a7daf](https://github.com/gatsbyjs/gatsby/commit/28a7daf))

## [2.13.82](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.81...gatsby@2.13.82) (2019-08-24)

### Bug Fixes

- update dependency del to v5 ([#17026](https://github.com/gatsbyjs/gatsby/issues/17026)) ([47b2d86](https://github.com/gatsbyjs/gatsby/commit/47b2d86))

## [2.13.81](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.80...gatsby@2.13.81) (2019-08-24)

### Bug Fixes

- update dependency dotenv to v8 ([#17027](https://github.com/gatsbyjs/gatsby/issues/17027)) ([f92295e](https://github.com/gatsbyjs/gatsby/commit/f92295e))
- update dependency fs-extra to v8 ([#17031](https://github.com/gatsbyjs/gatsby/issues/17031)) ([d891a19](https://github.com/gatsbyjs/gatsby/commit/d891a19))
- update dependency is-relative-url to v3 ([#17038](https://github.com/gatsbyjs/gatsby/issues/17038)) ([ff9ae84](https://github.com/gatsbyjs/gatsby/commit/ff9ae84))
- update dependency is-wsl to v2 ([#17039](https://github.com/gatsbyjs/gatsby/issues/17039)) ([bfed424](https://github.com/gatsbyjs/gatsby/commit/bfed424))
- update dependency jest-worker to v24 ([#17040](https://github.com/gatsbyjs/gatsby/issues/17040)) ([bd089a4](https://github.com/gatsbyjs/gatsby/commit/bd089a4))
- update dependency slash to v3 ([#17019](https://github.com/gatsbyjs/gatsby/issues/17019)) ([c81f45c](https://github.com/gatsbyjs/gatsby/commit/c81f45c))

## [2.13.80](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.79...gatsby@2.13.80) (2019-08-23)

### Bug Fixes

- update dependency @gatsbyjs/relay-compiler to v2.0.0-prin… ([#16986](https://github.com/gatsbyjs/gatsby/issues/16986)) ([25f0318](https://github.com/gatsbyjs/gatsby/commit/25f0318))

## [2.13.79](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.78...gatsby@2.13.79) (2019-08-23)

### Bug Fixes

- update dependency chokidar to v3 ([#16975](https://github.com/gatsbyjs/gatsby/issues/16975)) ([816d475](https://github.com/gatsbyjs/gatsby/commit/816d475))

## [2.13.78](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.77...gatsby@2.13.78) (2019-08-23)

### Bug Fixes

- **gatsby:** update check for default exports ([#16979](https://github.com/gatsbyjs/gatsby/issues/16979)) ([d16474d](https://github.com/gatsbyjs/gatsby/commit/d16474d))

## [2.13.77](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.76...gatsby@2.13.77) (2019-08-23)

### Bug Fixes

- update minor updates in packages except react, babel and… ([#16960](https://github.com/gatsbyjs/gatsby/issues/16960)) ([d6bd515](https://github.com/gatsbyjs/gatsby/commit/d6bd515))

## [2.13.76](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.75...gatsby@2.13.76) (2019-08-22)

### Bug Fixes

- update minor updates in packages except react, babel and… ([#16948](https://github.com/gatsbyjs/gatsby/issues/16948)) ([1c34c9b](https://github.com/gatsbyjs/gatsby/commit/1c34c9b))
- **gatsby:** Remove deprecation warning from express-graphql ([#16956](https://github.com/gatsbyjs/gatsby/issues/16956)) ([58ed3ca](https://github.com/gatsbyjs/gatsby/commit/58ed3ca))

## [2.13.75](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.74...gatsby@2.13.75) (2019-08-22)

**Note:** Version bump only for package gatsby

## [2.13.74](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.73...gatsby@2.13.74) (2019-08-21)

### Bug Fixes

- update dependency bluebird to ^3.5.5 ([#16825](https://github.com/gatsbyjs/gatsby/issues/16825)) ([ec0be83](https://github.com/gatsbyjs/gatsby/commit/ec0be83))
- update dependency cache-manager to ^2.10.0 ([#16828](https://github.com/gatsbyjs/gatsby/issues/16828)) ([917a1a7](https://github.com/gatsbyjs/gatsby/commit/917a1a7))
- update dependency chalk to ^2.4.2 ([#16830](https://github.com/gatsbyjs/gatsby/issues/16830)) ([3c89607](https://github.com/gatsbyjs/gatsby/commit/3c89607))
- update dependency common-tags to ^1.8.0 ([#16834](https://github.com/gatsbyjs/gatsby/issues/16834)) ([8ed5197](https://github.com/gatsbyjs/gatsby/commit/8ed5197))
- update dependency core-js to ^2.6.9 ([#16839](https://github.com/gatsbyjs/gatsby/issues/16839)) ([e1860c0](https://github.com/gatsbyjs/gatsby/commit/e1860c0))
- update dependency css-loader to ^1.0.1 ([#16858](https://github.com/gatsbyjs/gatsby/issues/16858)) ([2d3536f](https://github.com/gatsbyjs/gatsby/commit/2d3536f))
- update dependency debug to ^3.2.6 ([#16859](https://github.com/gatsbyjs/gatsby/issues/16859)) ([697f76b](https://github.com/gatsbyjs/gatsby/commit/697f76b))
- update dependency detect-port to ^1.3.0 ([#16860](https://github.com/gatsbyjs/gatsby/issues/16860)) ([d4246d8](https://github.com/gatsbyjs/gatsby/commit/d4246d8))
- update dependency eslint to ^5.16.0 ([#16862](https://github.com/gatsbyjs/gatsby/issues/16862)) ([e3b306c](https://github.com/gatsbyjs/gatsby/commit/e3b306c))
- update dependency eslint-loader to ^2.2.1 ([#16864](https://github.com/gatsbyjs/gatsby/issues/16864)) ([7c7c79c](https://github.com/gatsbyjs/gatsby/commit/7c7c79c))
- update dependency eslint-plugin-flowtype to ^2.50.3 ([#16866](https://github.com/gatsbyjs/gatsby/issues/16866)) ([aeaa141](https://github.com/gatsbyjs/gatsby/commit/aeaa141))
- update dependency eslint-plugin-import to ^2.18.2 ([#16867](https://github.com/gatsbyjs/gatsby/issues/16867)) ([aed2414](https://github.com/gatsbyjs/gatsby/commit/aed2414))
- update dependency eslint-plugin-jsx-a11y to ^6.2.3 ([#16868](https://github.com/gatsbyjs/gatsby/issues/16868)) ([a6a1d4f](https://github.com/gatsbyjs/gatsby/commit/a6a1d4f))
- update dependency eslint-plugin-react to ^7.14.3 ([#16869](https://github.com/gatsbyjs/gatsby/issues/16869)) ([6864ef6](https://github.com/gatsbyjs/gatsby/commit/6864ef6))
- update dependency event-source-polyfill to ^1.0.8 ([#16870](https://github.com/gatsbyjs/gatsby/issues/16870)) ([1430af5](https://github.com/gatsbyjs/gatsby/commit/1430af5))
- **gatsby:** Fix tracing so that everything happens under one span ([#16893](https://github.com/gatsbyjs/gatsby/issues/16893)) ([f8cae16](https://github.com/gatsbyjs/gatsby/commit/f8cae16))
- **gatsby:** Use publicLoader in production-app ([#16800](https://github.com/gatsbyjs/gatsby/issues/16800)) ([4ea8cb1](https://github.com/gatsbyjs/gatsby/commit/4ea8cb1))
- update dependency express to ^4.17.1 ([#16872](https://github.com/gatsbyjs/gatsby/issues/16872)) ([b0ae41e](https://github.com/gatsbyjs/gatsby/commit/b0ae41e))
- update dependency express-graphql to ^0.9.0 ([#16873](https://github.com/gatsbyjs/gatsby/issues/16873)) ([9e16547](https://github.com/gatsbyjs/gatsby/commit/9e16547))
- update dependency flat to ^4.1.0 ([#16875](https://github.com/gatsbyjs/gatsby/issues/16875)) ([19e5b30](https://github.com/gatsbyjs/gatsby/commit/19e5b30))
- update dependency got to v8.3.2 ([#16881](https://github.com/gatsbyjs/gatsby/issues/16881)) ([ac583b1](https://github.com/gatsbyjs/gatsby/commit/ac583b1))
- update dependency graphql-compose to ^6.3.5 ([#16882](https://github.com/gatsbyjs/gatsby/issues/16882)) ([10ec53b](https://github.com/gatsbyjs/gatsby/commit/10ec53b))

### Features

- **gatsby:** Bumps eslint-config-react-app 4.x ([#16168](https://github.com/gatsbyjs/gatsby/issues/16168)) ([1bbce27](https://github.com/gatsbyjs/gatsby/commit/1bbce27))

## [2.13.73](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.72...gatsby@2.13.73) (2019-08-21)

### Bug Fixes

- update dependency babel-plugin-add-module-exports to ^0.3.3([#16810](https://github.com/gatsbyjs/gatsby/issues/16810)) ([6378994](https://github.com/gatsbyjs/gatsby/commit/6378994))
- update dependency better-queue to ^3.8.10 ([#16824](https://github.com/gatsbyjs/gatsby/issues/16824)) ([6834344](https://github.com/gatsbyjs/gatsby/commit/6834344))
- update dependency cache-manager-fs-hash to ^0.0.7 ([#16829](https://github.com/gatsbyjs/gatsby/issues/16829)) ([3ceb6db](https://github.com/gatsbyjs/gatsby/commit/3ceb6db))
- update dependency chokidar to v2.1.6 ([#16832](https://github.com/gatsbyjs/gatsby/issues/16832)) ([dbcf65f](https://github.com/gatsbyjs/gatsby/commit/dbcf65f))
- update dependency compression to ^1.7.4 ([#16836](https://github.com/gatsbyjs/gatsby/issues/16836)) ([2e60499](https://github.com/gatsbyjs/gatsby/commit/2e60499))

## [2.13.72](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.71...gatsby@2.13.72) (2019-08-20)

### Bug Fixes

- update dependency [@hapi](https://github.com/hapi)/joi to ^15.1.1 ([#16796](https://github.com/gatsbyjs/gatsby/issues/16796)) ([2cfc19c](https://github.com/gatsbyjs/gatsby/commit/2cfc19c))
- update dependency [@reach](https://github.com/reach)/router to ^1.2.1 ([#16797](https://github.com/gatsbyjs/gatsby/issues/16797)) ([f3554bc](https://github.com/gatsbyjs/gatsby/commit/f3554bc))
- update dependency address to v1.1.0 ([#16802](https://github.com/gatsbyjs/gatsby/issues/16802)) ([503f1b3](https://github.com/gatsbyjs/gatsby/commit/503f1b3))
- update dependency autoprefixer to ^9.6.1 ([#16807](https://github.com/gatsbyjs/gatsby/issues/16807)) ([780c62a](https://github.com/gatsbyjs/gatsby/commit/780c62a))

## [2.13.71](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.70...gatsby@2.13.71) (2019-08-20)

### Bug Fixes

- **gatsby:** keep all page-data files in public ([#16766](https://github.com/gatsbyjs/gatsby/issues/16766)) ([a573f9f](https://github.com/gatsbyjs/gatsby/commit/a573f9f))

## [2.13.70](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.69...gatsby@2.13.70) (2019-08-20)

### Features

- **gatsby:** Add meta tag for development ([#16743](https://github.com/gatsbyjs/gatsby/issues/16743)) ([d0e24d2](https://github.com/gatsbyjs/gatsby/commit/d0e24d2))

## [2.13.69](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.68...gatsby@2.13.69) (2019-08-20)

### Bug Fixes

- **telemetry:** only look at websocket updates when we have active clients. ([#16750](https://github.com/gatsbyjs/gatsby/issues/16750)) ([164cd5b](https://github.com/gatsbyjs/gatsby/commit/164cd5b))

## [2.13.68](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.67...gatsby@2.13.68) (2019-08-19)

### Bug Fixes

- **gatsby:** remove finally to enable ie11 + firefox support ([#16734](https://github.com/gatsbyjs/gatsby/issues/16734)) ([a4c97e3](https://github.com/gatsbyjs/gatsby/commit/a4c97e3))

### Features

- **gatsby:** Allow specifying type on link extension ([#16680](https://github.com/gatsbyjs/gatsby/issues/16680)) ([f9bbb55](https://github.com/gatsbyjs/gatsby/commit/f9bbb55))

## [2.13.67](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.66...gatsby@2.13.67) (2019-08-16)

**Note:** Version bump only for package gatsby

## [2.13.66](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.65...gatsby@2.13.66) (2019-08-16)

### Bug Fixes

- **gatsby:** don't break if an ancestor directory is inaccessible ([#15876](https://github.com/gatsbyjs/gatsby/issues/15876)) ([cac4246](https://github.com/gatsbyjs/gatsby/commit/cac4246))

## [2.13.65](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.64...gatsby@2.13.65) (2019-08-16)

### Bug Fixes

- **gatsby:** Set default for modulesThatUseGatsby ([#16657](https://github.com/gatsbyjs/gatsby/issues/16657)) ([278ff98](https://github.com/gatsbyjs/gatsby/commit/278ff98))

## [2.13.64](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.63...gatsby@2.13.64) (2019-08-15)

### Bug Fixes

- **gatsby:** adjust regex to handle MODULE_NOT_FOUND errors thrown by Bazel ([#16573](https://github.com/gatsbyjs/gatsby/issues/16573)) ([ee19535](https://github.com/gatsbyjs/gatsby/commit/ee19535))

## [2.13.63](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.62...gatsby@2.13.63) (2019-08-14)

### Bug Fixes

- **gatsby:** Set CORS to \* in serve ([#14483](https://github.com/gatsbyjs/gatsby/issues/14483)) ([74959ab](https://github.com/gatsbyjs/gatsby/commit/74959ab))
- **gatsby:** Use anonymous requests when fetching resources ([#14443](https://github.com/gatsbyjs/gatsby/issues/14443)) ([cdd800f](https://github.com/gatsbyjs/gatsby/commit/cdd800f)), closes [/github.com/gatsbyjs/gatsby/issues/14293#issue-448125073](https://github.com//github.com/gatsbyjs/gatsby/issues/14293/issues/issue-448125073) [#14293](https://github.com/gatsbyjs/gatsby/issues/14293)

## [2.13.62](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.61...gatsby@2.13.62) (2019-08-13)

### Bug Fixes

- **gatsby:** check if navigator.connection is defined ([#16572](https://github.com/gatsbyjs/gatsby/issues/16572)) ([8c54e5b](https://github.com/gatsbyjs/gatsby/commit/8c54e5b))
- **gatsby:** Don't show deprecation warning when adding childr… ([#16559](https://github.com/gatsbyjs/gatsby/issues/16559)) ([5c7a3e1](https://github.com/gatsbyjs/gatsby/commit/5c7a3e1))

## [2.13.61](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.60...gatsby@2.13.61) (2019-08-12)

### Features

- **gatsby-plugin-schema-snapshot:** First version ([#16561](https://github.com/gatsbyjs/gatsby/issues/16561)) ([9dd1070](https://github.com/gatsbyjs/gatsby/commit/9dd1070))

## [2.13.60](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.59...gatsby@2.13.60) (2019-08-12)

### Bug Fixes

- **gatsby:** improve hot-reloading for hooks ([#16546](https://github.com/gatsbyjs/gatsby/issues/16546)) ([8d66161](https://github.com/gatsbyjs/gatsby/commit/8d66161))

## [2.13.59](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.58...gatsby@2.13.59) (2019-08-12)

### Bug Fixes

- **gatsby:** remove page not found for client routes in develop ([#16301](https://github.com/gatsbyjs/gatsby/issues/16301)) ([69b808a](https://github.com/gatsbyjs/gatsby/commit/69b808a))

### Features

- **gatsby:** Allow proxying field values from nested fields ([#16149](https://github.com/gatsbyjs/gatsby/issues/16149)) ([d2128ab](https://github.com/gatsbyjs/gatsby/commit/d2128ab))

## [2.13.58](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.57...gatsby@2.13.58) (2019-08-11)

### Features

- **gatsby:** Display network url for GraphiQL when using -H ([#16530](https://github.com/gatsbyjs/gatsby/issues/16530)) ([44fd333](https://github.com/gatsbyjs/gatsby/commit/44fd333))
- **gatsby:** enable richer error handling for unknown APIs ([#16105](https://github.com/gatsbyjs/gatsby/issues/16105)) ([0adab13](https://github.com/gatsbyjs/gatsby/commit/0adab13))

## [2.13.57](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.56...gatsby@2.13.57) (2019-08-09)

**Note:** Version bump only for package gatsby

## [2.13.56](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.55...gatsby@2.13.56) (2019-08-09)

**Note:** Version bump only for package gatsby

## [2.13.55](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.54...gatsby@2.13.55) (2019-08-09)

### Bug Fixes

- **gatsby:** Make root plural fields non nullable ([#15321](https://github.com/gatsbyjs/gatsby/issues/15321)) ([2c79309](https://github.com/gatsbyjs/gatsby/commit/2c79309))
- **gatsby:** Reserve graphqljs internal directive names ([#16483](https://github.com/gatsbyjs/gatsby/issues/16483)) ([4032012](https://github.com/gatsbyjs/gatsby/commit/4032012))

### Features

- **gatsby:** Allow field extensions to register return types ([#16484](https://github.com/gatsbyjs/gatsby/issues/16484)) ([0df297b](https://github.com/gatsbyjs/gatsby/commit/0df297b))
- **gatsby:** Allow printing type definitions to file (schema lock-down) ([#16291](https://github.com/gatsbyjs/gatsby/issues/16291)) ([23a460a](https://github.com/gatsbyjs/gatsby/commit/23a460a))

## [2.13.54](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.53...gatsby@2.13.54) (2019-08-08)

### Bug Fixes

- **gatsby:** reevaluate page query if context modified via createPage ([#15404](https://github.com/gatsbyjs/gatsby/issues/15404)) ([ddddc68](https://github.com/gatsbyjs/gatsby/commit/ddddc68))

## [2.13.53](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.52...gatsby@2.13.53) (2019-08-08)

### Bug Fixes

- **gatsby-plugin-offline:** Change navigation handler logic ([#13502](https://github.com/gatsbyjs/gatsby/issues/13502)) ([504b077](https://github.com/gatsbyjs/gatsby/commit/504b077))

## [2.13.52](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.51...gatsby@2.13.52) (2019-08-06)

### Bug Fixes

- **gatsby:** Add findMatchPath to the default loader ([#16334](https://github.com/gatsbyjs/gatsby/issues/16334)) ([f6aa41e](https://github.com/gatsbyjs/gatsby/commit/f6aa41e))
- **gatsby:** always use publicLoader for window.\_\_\_loader ([#16122](https://github.com/gatsbyjs/gatsby/issues/16122)) ([afb3485](https://github.com/gatsbyjs/gatsby/commit/afb3485))
- **gatsby:** createSchemaCustomization typings ([#16369](https://github.com/gatsbyjs/gatsby/issues/16369)) ([ac48c51](https://github.com/gatsbyjs/gatsby/commit/ac48c51))

### Features

- **gatsby:** Allow custom resolver context ([#16359](https://github.com/gatsbyjs/gatsby/issues/16359)) ([142b8ff](https://github.com/gatsbyjs/gatsby/commit/142b8ff))

## [2.13.51](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.50...gatsby@2.13.51) (2019-08-05)

### Bug Fixes

- **gatsby:** Don't delete 404 page-data so we don't crash build ([#16354](https://github.com/gatsbyjs/gatsby/issues/16354)) ([a2855b3](https://github.com/gatsbyjs/gatsby/commit/a2855b3))
- **gatsby:** Prefer a user's shouldUpdateScroll over a plugin's ([#16328](https://github.com/gatsbyjs/gatsby/issues/16328)) ([f02f366](https://github.com/gatsbyjs/gatsby/commit/f02f366))

### Features

- **gatsby:** Allow all dateformat options as directive args ([#16335](https://github.com/gatsbyjs/gatsby/issues/16335)) ([1a02b85](https://github.com/gatsbyjs/gatsby/commit/1a02b85))

## [2.13.50](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.48...gatsby@2.13.50) (2019-08-01)

**Note:** Version bump only for package gatsby

## [2.13.48](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.47...gatsby@2.13.48) (2019-08-01)

**Note:** Version bump only for package gatsby

## [2.13.47](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.46...gatsby@2.13.47) (2019-08-01)

### Bug Fixes

- **gatsby:** Handle missing match-paths.json in serve ([#16246](https://github.com/gatsbyjs/gatsby/issues/16246)) ([d54de72](https://github.com/gatsbyjs/gatsby/commit/d54de72))

## [2.13.46](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.45...gatsby@2.13.46) (2019-08-01)

### Bug Fixes

- **gatsby:** Check if callSite exists in stack-trace-utils ([#16257](https://github.com/gatsbyjs/gatsby/issues/16257)) ([4a348b2](https://github.com/gatsbyjs/gatsby/commit/4a348b2))
- **gatsby:** Check if page exists before trying to get page data ([#16220](https://github.com/gatsbyjs/gatsby/issues/16220)) ([065a551](https://github.com/gatsbyjs/gatsby/commit/065a551))
- **gatsby:** Panic when root config is a function ([#16272](https://github.com/gatsbyjs/gatsby/issues/16272)) ([81ff489](https://github.com/gatsbyjs/gatsby/commit/81ff489))
- **gatsby:** use Set instead of Array in page-component state machine ([#15533](https://github.com/gatsbyjs/gatsby/issues/15533)) ([d5d7e5d](https://github.com/gatsbyjs/gatsby/commit/d5d7e5d))

## [2.13.45](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.44...gatsby@2.13.45) (2019-07-30)

### Bug Fixes

- **gatsby:** Add error message for field extension validation ([#16232](https://github.com/gatsbyjs/gatsby/issues/16232)) ([f64a9e0](https://github.com/gatsbyjs/gatsby/commit/f64a9e0))
- **gatsby:** Fix absent parents ([#16228](https://github.com/gatsbyjs/gatsby/issues/16228)) ([5330a21](https://github.com/gatsbyjs/gatsby/commit/5330a21))
- **gatsby:** Fix special case id:eq queries for abstract types ([#16114](https://github.com/gatsbyjs/gatsby/issues/16114)) ([6d8b663](https://github.com/gatsbyjs/gatsby/commit/6d8b663))
- **gatsby:** Respect infer extension in schema update ([#16110](https://github.com/gatsbyjs/gatsby/issues/16110)) ([ce56b9d](https://github.com/gatsbyjs/gatsby/commit/ce56b9d))

## [2.13.44](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.43...gatsby@2.13.44) (2019-07-30)

### Bug Fixes

- **gatsby:** enable babel.config.js once again ([#16205](https://github.com/gatsbyjs/gatsby/issues/16205)) ([d72b6d9](https://github.com/gatsbyjs/gatsby/commit/d72b6d9))
- **gatsby:** run onPrefetchPathname when prefetch is disabled ([#16208](https://github.com/gatsbyjs/gatsby/issues/16208)) ([da859c0](https://github.com/gatsbyjs/gatsby/commit/da859c0))

## [2.13.43](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.42...gatsby@2.13.43) (2019-07-30)

**Note:** Version bump only for package gatsby

## [2.13.42](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.41...gatsby@2.13.42) (2019-07-29)

**Note:** Version bump only for package gatsby

## [2.13.41](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.40...gatsby@2.13.41) (2019-07-25)

**Note:** Version bump only for package gatsby

## [2.13.40](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.39...gatsby@2.13.40) (2019-07-25)

**Note:** Version bump only for package gatsby

## [2.13.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.38...gatsby@2.13.39) (2019-07-24)

**Note:** Version bump only for package gatsby

## [2.13.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.37...gatsby@2.13.38) (2019-07-23)

### Bug Fixes

- **gatsby:** use joi validation result instead of payload ([#15379](https://github.com/gatsbyjs/gatsby/issues/15379)) ([5856fb7](https://github.com/gatsbyjs/gatsby/commit/5856fb7))

## [2.13.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.36...gatsby@2.13.37) (2019-07-23)

**Note:** Version bump only for package gatsby

## [2.13.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.35...gatsby@2.13.36) (2019-07-23)

### Features

- **gatsby:** Includes ts/tsx files to eslint rules ([#15976](https://github.com/gatsbyjs/gatsby/issues/15976)) ([6adcb9a](https://github.com/gatsbyjs/gatsby/commit/6adcb9a))

## [2.13.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.34...gatsby@2.13.35) (2019-07-23)

**Note:** Version bump only for package gatsby

## [2.13.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.33...gatsby@2.13.34) (2019-07-23)

### Bug Fixes

- **gatsby:** add jsdoc for matchPath on page Object ([#15749](https://github.com/gatsbyjs/gatsby/issues/15749)) ([5633fdb](https://github.com/gatsbyjs/gatsby/commit/5633fdb))
- **gatsby:** Add touchNode to populate typeOwners ([#15919](https://github.com/gatsbyjs/gatsby/issues/15919)) ([9d5026f](https://github.com/gatsbyjs/gatsby/commit/9d5026f))

## [2.13.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.32...gatsby@2.13.33) (2019-07-22)

### Bug Fixes

- **gatsby:** Use UTC dates in test ([#15895](https://github.com/gatsbyjs/gatsby/issues/15895)) ([6eb1b76](https://github.com/gatsbyjs/gatsby/commit/6eb1b76))

## [2.13.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.31...gatsby@2.13.32) (2019-07-20)

**Note:** Version bump only for package gatsby

## [2.13.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.30...gatsby@2.13.31) (2019-07-19)

**Note:** Version bump only for package gatsby

## [2.13.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.29...gatsby@2.13.30) (2019-07-19)

**Note:** Version bump only for package gatsby

## [2.13.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.28...gatsby@2.13.29) (2019-07-19)

**Note:** Version bump only for package gatsby

## [2.13.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.27...gatsby@2.13.28) (2019-07-18)

### Bug Fixes

- **gatsby:** 404 page when using path-prefix ([#15858](https://github.com/gatsbyjs/gatsby/issues/15858)) ([51886a3](https://github.com/gatsbyjs/gatsby/commit/51886a3))
- **gatsby:** Make intermediate schema available to createResolvers API ([#15838](https://github.com/gatsbyjs/gatsby/issues/15838)) ([055a1b0](https://github.com/gatsbyjs/gatsby/commit/055a1b0))

### Features

- **gatsby:** Allow explicitly defining parent-child relations with type extensions ([#15715](https://github.com/gatsbyjs/gatsby/issues/15715)) ([696106d](https://github.com/gatsbyjs/gatsby/commit/696106d))

## [2.13.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.26...gatsby@2.13.27) (2019-07-17)

### Bug Fixes

- **gatsby:** Hot reload package and theme queries ([#15739](https://github.com/gatsbyjs/gatsby/issues/15739)) ([1685a2b](https://github.com/gatsbyjs/gatsby/commit/1685a2b))
- **gatsby:** Track nodes when mutated ([#15720](https://github.com/gatsbyjs/gatsby/issues/15720)) ([f939f6c](https://github.com/gatsbyjs/gatsby/commit/f939f6c))

## [2.13.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.25...gatsby@2.13.26) (2019-07-17)

### Bug Fixes

- **docs:** Don’t include example code in API docs that doesn’t work ([#15803](https://github.com/gatsbyjs/gatsby/issues/15803)) ([044eea5](https://github.com/gatsbyjs/gatsby/commit/044eea5))

### Features

- **gatsby:** pass webhook data to sourceNodes functions ([#15564](https://github.com/gatsbyjs/gatsby/issues/15564)) ([dd130f1](https://github.com/gatsbyjs/gatsby/commit/dd130f1))

## [2.13.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.24...gatsby@2.13.25) (2019-07-16)

### Bug Fixes

- **gatsby:** fix matchpath prioritisation ([#15762](https://github.com/gatsbyjs/gatsby/issues/15762)) ([a1ab8bc](https://github.com/gatsbyjs/gatsby/commit/a1ab8bc))

## [2.13.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.23...gatsby@2.13.24) (2019-07-16)

### Bug Fixes

- **gatsby:** Fix import on cache-dir/gatsby-browser-entry.js ([#15735](https://github.com/gatsbyjs/gatsby/issues/15735)) ([4b206c3](https://github.com/gatsbyjs/gatsby/commit/4b206c3)), closes [/github.com/gatsbyjs/gatsby/blob/2d27d7d42112fcbeb13cd52fa9fe0d46b1764d13/packages/gatsby/cache-dir/loader.js#L355](https://github.com//github.com/gatsbyjs/gatsby/blob/2d27d7d42112fcbeb13cd52fa9fe0d46b1764d13/packages/gatsby/cache-dir/loader.js/issues/L355)

## [2.13.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.22...gatsby@2.13.23) (2019-07-15)

### Features

- **gatsby:** Refine typing on createPage ([#15723](https://github.com/gatsbyjs/gatsby/issues/15723)) ([65d5181](https://github.com/gatsbyjs/gatsby/commit/65d5181))

## [2.13.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.21...gatsby@2.13.22) (2019-07-15)

### Bug Fixes

- **gatsby:** Add NodeInput for createNode function types ([#14537](https://github.com/gatsbyjs/gatsby/issues/14537)) ([1b549e8](https://github.com/gatsbyjs/gatsby/commit/1b549e8))

### Features

- **gatsby:** Add nodeInterface extension ([#15545](https://github.com/gatsbyjs/gatsby/issues/15545)) ([8c46237](https://github.com/gatsbyjs/gatsby/commit/8c46237))
- **gatsby:** add prefetchPathname the public api ([#13985](https://github.com/gatsbyjs/gatsby/issues/13985)) ([7173f96](https://github.com/gatsbyjs/gatsby/commit/7173f96))

## [2.13.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.20...gatsby@2.13.21) (2019-07-14)

### Features

- **gatsby:** Add enum and scalar type builders ([#15689](https://github.com/gatsbyjs/gatsby/issues/15689)) ([e12d79d](https://github.com/gatsbyjs/gatsby/commit/e12d79d))

## [2.13.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.19...gatsby@2.13.20) (2019-07-13)

**Note:** Version bump only for package gatsby

## [2.13.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.18...gatsby@2.13.19) (2019-07-12)

**Note:** Version bump only for package gatsby

## [2.13.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.17...gatsby@2.13.18) (2019-07-12)

**Note:** Version bump only for package gatsby

## [2.13.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.16...gatsby@2.13.17) (2019-07-12)

### Bug Fixes

- **gatsby:** blank dev-404-page when no custom 404 page found ([#15658](https://github.com/gatsbyjs/gatsby/issues/15658)) ([11e86a6](https://github.com/gatsbyjs/gatsby/commit/11e86a6))

## [2.13.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.15...gatsby@2.13.16) (2019-07-12)

### Bug Fixes

- **gatsby:** Make createPage action errors structured ([#15619](https://github.com/gatsbyjs/gatsby/issues/15619)) ([44654be](https://github.com/gatsbyjs/gatsby/commit/44654be))
- **svg:** don't try to use convertShapeToPath svgo optim ([#15636](https://github.com/gatsbyjs/gatsby/issues/15636)) ([4db78dc](https://github.com/gatsbyjs/gatsby/commit/4db78dc))

## [2.13.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.14...gatsby@2.13.15) (2019-07-11)

### Bug Fixes

- **gatsby:** handle `/404/`, `/404`, `404/` or `404` page paths ([#15615](https://github.com/gatsbyjs/gatsby/issues/15615)) ([482ea8d](https://github.com/gatsbyjs/gatsby/commit/482ea8d))

## [2.13.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.13...gatsby@2.13.14) (2019-07-11)

**Note:** Version bump only for package gatsby

## [2.13.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.12...gatsby@2.13.13) (2019-07-10)

### Bug Fixes

- don't break joi validation for production bundles webpack… ([#15602](https://github.com/gatsbyjs/gatsby/issues/15602)) ([4c50024](https://github.com/gatsbyjs/gatsby/commit/4c50024))
- don't break joi validation for unhandledRejections & apirunner ([#15600](https://github.com/gatsbyjs/gatsby/issues/15600)) ([14ba538](https://github.com/gatsbyjs/gatsby/commit/14ba538))

## [2.13.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.11...gatsby@2.13.12) (2019-07-10)

### Bug Fixes

- **gatsby:** Prefer nodes over inline objects in findRootNodeAncestor ([#14843](https://github.com/gatsbyjs/gatsby/issues/14843)) ([e18acb6](https://github.com/gatsbyjs/gatsby/commit/e18acb6))

### Features

- **gatsby:** Make builtin field extensions wrap resolvers ([#15515](https://github.com/gatsbyjs/gatsby/issues/15515)) ([c2edf6c](https://github.com/gatsbyjs/gatsby/commit/c2edf6c))

## [2.13.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.10...gatsby@2.13.11) (2019-07-09)

### Bug Fixes

- support unicode paths ([#15552](https://github.com/gatsbyjs/gatsby/issues/15552)) ([f3b9912](https://github.com/gatsbyjs/gatsby/commit/f3b9912))

## [2.13.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.9...gatsby@2.13.10) (2019-07-09)

### Bug Fixes

- **gatsby:** restore client-only-paths behaviour ([#15457](https://github.com/gatsbyjs/gatsby/issues/15457)) ([0ffbe59](https://github.com/gatsbyjs/gatsby/commit/0ffbe59))

## [2.13.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.8...gatsby@2.13.9) (2019-07-08)

### Bug Fixes

- **gatsby:** support for yarn workspaces in gatsby-dependents ([#15517](https://github.com/gatsbyjs/gatsby/issues/15517)) ([3b5e41b](https://github.com/gatsbyjs/gatsby/commit/3b5e41b))

## [2.13.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.7...gatsby@2.13.8) (2019-07-08)

### Bug Fixes

- **gatsby:** speed up and lower memory of createPages ([#15503](https://github.com/gatsbyjs/gatsby/issues/15503)) ([0ffa8bc](https://github.com/gatsbyjs/gatsby/commit/0ffa8bc))

## [2.13.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.6...gatsby@2.13.7) (2019-07-07)

### Bug Fixes

- **gatsby:** bump `react-hot-loader` version to fix regression… ([#15485](https://github.com/gatsbyjs/gatsby/issues/15485)) ([02eaaa4](https://github.com/gatsbyjs/gatsby/commit/02eaaa4))
- **gatsby:** Exclude node_modules when depth > 1 ([#15442](https://github.com/gatsbyjs/gatsby/issues/15442)) ([ba0c3cb](https://github.com/gatsbyjs/gatsby/commit/ba0c3cb))

## [2.13.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.5...gatsby@2.13.6) (2019-07-06)

### Bug Fixes

- **gatsby:** parse pageData response when contentType is not s… ([#15410](https://github.com/gatsbyjs/gatsby/issues/15410)) ([8bf80be](https://github.com/gatsbyjs/gatsby/commit/8bf80be))

## [2.13.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.4...gatsby@2.13.5) (2019-07-06)

### Bug Fixes

- **PnP:** updates the test to account for the property name ch… ([#15463](https://github.com/gatsbyjs/gatsby/issues/15463)) ([f657474](https://github.com/gatsbyjs/gatsby/commit/f657474))

## [2.13.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.3...gatsby@2.13.4) (2019-07-05)

**Note:** Version bump only for package gatsby

## [2.13.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.2...gatsby@2.13.3) (2019-07-03)

### Bug Fixes

- **gatsby:** regression ~ show non structured grapqhl errors ([#15352](https://github.com/gatsbyjs/gatsby/issues/15352)) ([a364c3d](https://github.com/gatsbyjs/gatsby/commit/a364c3d))

## [2.13.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.13.1...gatsby@2.13.2) (2019-07-03)

### Bug Fixes

- **gatsby:** fix not focusing router wrapper after navigation ([#13197](https://github.com/gatsbyjs/gatsby/issues/13197)) ([b8e2adc](https://github.com/gatsbyjs/gatsby/commit/b8e2adc))

## [2.13.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.12.1...gatsby@2.13.1) (2019-07-02)

### Bug Fixes

- **gatsby:** Default to empty arrays in load-themes ([#15331](https://github.com/gatsbyjs/gatsby/issues/15331)) ([6366914](https://github.com/gatsbyjs/gatsby/commit/6366914))

### Features

- **gatsby:** Make \_\_experimentalThemes part of plugin APIs ([#15144](https://github.com/gatsbyjs/gatsby/issues/15144)) ([3dce8cb](https://github.com/gatsbyjs/gatsby/commit/3dce8cb))

## [2.12.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.12.1...gatsby@2.12.2) (2019-07-02)

### Bug Fixes

- **gatsby:** Default to empty arrays in load-themes ([#15331](https://github.com/gatsbyjs/gatsby/issues/15331)) ([6366914](https://github.com/gatsbyjs/gatsby/commit/6366914))

### Features

- **gatsby:** Make \_\_experimentalThemes part of plugin APIs ([#15144](https://github.com/gatsbyjs/gatsby/issues/15144)) ([3dce8cb](https://github.com/gatsbyjs/gatsby/commit/3dce8cb))

## [2.12.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.12.0...gatsby@2.12.1) (2019-07-02)

### Bug Fixes

- **gatsby:** adds the missing micromatch dependency ([#15310](https://github.com/gatsbyjs/gatsby/issues/15310)) ([5f66f21](https://github.com/gatsbyjs/gatsby/commit/5f66f21))
- **gatsby:** Exclude gatsby itself in gatsby-dependents ([#15318](https://github.com/gatsbyjs/gatsby/issues/15318)) ([25cd90e](https://github.com/gatsbyjs/gatsby/commit/25cd90e))
- **gatsby:** various TypeScript definitions ([#15268](https://github.com/gatsbyjs/gatsby/issues/15268)) ([b8f3ed5](https://github.com/gatsbyjs/gatsby/commit/b8f3ed5))
- **themes:** normalize plugin entries before merging plugin ar… ([#15307](https://github.com/gatsbyjs/gatsby/issues/15307)) ([300d331](https://github.com/gatsbyjs/gatsby/commit/300d331))

### Features

- **gatsby:** enable babel in deps ([#15284](https://github.com/gatsbyjs/gatsby/issues/15284)) ([4ea3fa1](https://github.com/gatsbyjs/gatsby/commit/4ea3fa1))
- **gatsby:** Refine typing on createPages’ graphql function ([#14575](https://github.com/gatsbyjs/gatsby/issues/14575)) ([5bedc01](https://github.com/gatsbyjs/gatsby/commit/5bedc01))
- **gatsby:** support symlinked directories ([#15295](https://github.com/gatsbyjs/gatsby/issues/15295)) ([54b417f](https://github.com/gatsbyjs/gatsby/commit/54b417f))
- **gatsby:** Switch to name based package filtering for speed ([#15308](https://github.com/gatsbyjs/gatsby/issues/15308)) ([b79e96a](https://github.com/gatsbyjs/gatsby/commit/b79e96a))

# [2.12.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.8...gatsby@2.12.0) (2019-07-02)

### Features

- **gatsby:** Allow adding custom field extensions ([#14610](https://github.com/gatsbyjs/gatsby/issues/14610)) ([4f9c790](https://github.com/gatsbyjs/gatsby/commit/4f9c790))

## [2.11.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.7...gatsby@2.11.8) (2019-07-02)

### Bug Fixes

- enable separate config for node_modules transpilation ([#15270](https://github.com/gatsbyjs/gatsby/issues/15270)) ([7e39a12](https://github.com/gatsbyjs/gatsby/commit/7e39a12))

### Features

- **gatsby:** Add gatsby-dependents util ([#15269](https://github.com/gatsbyjs/gatsby/issues/15269)) ([f55250e](https://github.com/gatsbyjs/gatsby/commit/f55250e))
- **gatsby:** Handle duplicated fragment definitions ([#15179](https://github.com/gatsbyjs/gatsby/issues/15179)) ([a92f6e1](https://github.com/gatsbyjs/gatsby/commit/a92f6e1))

## [2.11.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.6...gatsby@2.11.7) (2019-07-01)

### Bug Fixes

- **gatsby:** update tsc definition for some actions ([1adb7d5](https://github.com/gatsbyjs/gatsby/commit/1adb7d5))

## [2.11.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.5...gatsby@2.11.6) (2019-06-30)

### Bug Fixes

- pin terser-webpack-plugin ([#15253](https://github.com/gatsbyjs/gatsby/issues/15253)) ([62cdce2](https://github.com/gatsbyjs/gatsby/commit/62cdce2))

## [2.11.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.4...gatsby@2.11.5) (2019-06-29)

**Note:** Version bump only for package gatsby

## [2.11.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.3...gatsby@2.11.4) (2019-06-29)

**Note:** Version bump only for package gatsby

## [2.11.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.2...gatsby@2.11.3) (2019-06-28)

**Note:** Version bump only for package gatsby

## [2.11.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.1...gatsby@2.11.2) (2019-06-28)

### Features

- **gatsby-cli:** Add error codes and structured errors ([#14904](https://github.com/gatsbyjs/gatsby/issues/14904)) ([d26651e](https://github.com/gatsbyjs/gatsby/commit/d26651e))

## [2.11.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.11.0...gatsby@2.11.1) (2019-06-28)

### Features

- **gatsby:** Rewrite resource loading - retry mechanism ([#14889](https://github.com/gatsbyjs/gatsby/issues/14889)) ([68e15e7](https://github.com/gatsbyjs/gatsby/commit/68e15e7))

# [2.11.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.10.5...gatsby@2.11.0) (2019-06-27)

### Bug Fixes

- **gatsby:** update tsc definition of cache in NodePluginArgs ([#14955](https://github.com/gatsbyjs/gatsby/issues/14955)) ([65b42e9](https://github.com/gatsbyjs/gatsby/commit/65b42e9))

### Features

- **gatsby:** enable babel-loader for all dependencies ([#14111](https://github.com/gatsbyjs/gatsby/issues/14111)) ([268ed27](https://github.com/gatsbyjs/gatsby/commit/268ed27))
- **gatsby:** Support absolute certificate paths for developme… ([#14932](https://github.com/gatsbyjs/gatsby/issues/14932)) ([7694c0c](https://github.com/gatsbyjs/gatsby/commit/7694c0c))

## [2.10.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.10.4...gatsby@2.10.5) (2019-06-25)

**Note:** Version bump only for package gatsby

## [2.10.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.10.3...gatsby@2.10.4) (2019-06-24)

### Bug Fixes

- **gatsby:** Fix client side routing match paths regression ([#15010](https://github.com/gatsbyjs/gatsby/issues/15010)) ([f52bbac](https://github.com/gatsbyjs/gatsby/commit/f52bbac))

## [2.10.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.10.2...gatsby@2.10.3) (2019-06-24)

**Note:** Version bump only for package gatsby

## [2.10.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.10.1...gatsby@2.10.2) (2019-06-24)

**Note:** Version bump only for package gatsby

## [2.10.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.10.0...gatsby@2.10.1) (2019-06-24)

**Note:** Version bump only for package gatsby

# [2.10.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.11...gatsby@2.10.0) (2019-06-20)

**Note:** Version bump only for package gatsby

## [2.9.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.10...gatsby@2.9.11) (2019-06-19)

### Bug Fixes

- **gatsby:** Normalize paths for run queries before caching ([#14910](https://github.com/gatsbyjs/gatsby/issues/14910)) ([f03bf5c](https://github.com/gatsbyjs/gatsby/commit/f03bf5c)), closes [#14903](https://github.com/gatsbyjs/gatsby/issues/14903)

## [2.9.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.9...gatsby@2.9.10) (2019-06-19)

**Note:** Version bump only for package gatsby

## [2.9.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.6...gatsby@2.9.9) (2019-06-19)

**Note:** Version bump only for package gatsby

## [2.9.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.7...gatsby@2.9.8) (2019-06-19)

**Note:** Version bump only for package gatsby

## [2.9.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.6...gatsby@2.9.7) (2019-06-18)

**Note:** Version bump only for package gatsby

## [2.9.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.5...gatsby@2.9.6) (2019-06-18)

**Note:** Version bump only for package gatsby

## [2.9.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.4...gatsby@2.9.5) (2019-06-18)

**Note:** Version bump only for package gatsby

## [2.9.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.2...gatsby@2.9.4) (2019-06-14)

### Bug Fixes

- **gatsby:** Move importing of match-paths.json outside of loader.js ([#14732](https://github.com/gatsbyjs/gatsby/issues/14732)) ([672e384](https://github.com/gatsbyjs/gatsby/commit/672e384))

## [2.9.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.2...gatsby@2.9.3) (2019-06-14)

### Bug Fixes

- **gatsby:** Move importing of match-paths.json outside of loader.js ([#14732](https://github.com/gatsbyjs/gatsby/issues/14732)) ([672e384](https://github.com/gatsbyjs/gatsby/commit/672e384))

## [2.9.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.0...gatsby@2.9.2) (2019-06-12)

### Bug Fixes

- **gatsby:** Fix group and distinct when used with fragments ([#14728](https://github.com/gatsbyjs/gatsby/issues/14728)) ([3a15873](https://github.com/gatsbyjs/gatsby/commit/3a15873))
- **gatsby:** Make createPageDependency public again ([#14679](https://github.com/gatsbyjs/gatsby/issues/14679)) ([9ff3ba7](https://github.com/gatsbyjs/gatsby/commit/9ff3ba7))

## [2.9.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.9.0...gatsby@2.9.1) (2019-06-12)

**Note:** Version bump only for package gatsby

# [2.9.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.8...gatsby@2.9.0) (2019-06-11)

**Note:** Version bump only for package gatsby

## [2.8.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.7...gatsby@2.8.8) (2019-06-10)

### Bug Fixes

- **react-hooks-support:** Changed the gatsby browser entry to not bre… ([#13184](https://github.com/gatsbyjs/gatsby/issues/13184)) ([f311698](https://github.com/gatsbyjs/gatsby/commit/f311698))

## [2.8.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.6...gatsby@2.8.7) (2019-06-10)

### Bug Fixes

- **gatsby:** Resolve group and distinct field ([#14625](https://github.com/gatsbyjs/gatsby/issues/14625)) ([0c3cba1](https://github.com/gatsbyjs/gatsby/commit/0c3cba1))

## [2.8.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.5...gatsby@2.8.6) (2019-06-07)

### Bug Fixes

- **gatsby:** respect the GATSBY_CPU_COUNT env var, if set, by default for sharp ([#14624](https://github.com/gatsbyjs/gatsby/issues/14624)) ([a812c5f](https://github.com/gatsbyjs/gatsby/commit/a812c5f))

## [2.8.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.4...gatsby@2.8.5) (2019-06-05)

**Note:** Version bump only for package gatsby

## [2.8.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.3...gatsby@2.8.4) (2019-06-05)

### Bug Fixes

- **themes:** Upgrade Tapable Calls ([#14552](https://github.com/gatsbyjs/gatsby/issues/14552)) ([9359098](https://github.com/gatsbyjs/gatsby/commit/9359098))

## [2.8.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.2...gatsby@2.8.3) (2019-06-04)

### Bug Fixes

- **gatsby:** autoprefixer browsers option warning ([#14533](https://github.com/gatsbyjs/gatsby/issues/14533)) ([cb09e78](https://github.com/gatsbyjs/gatsby/commit/cb09e78))

## [2.8.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.1...gatsby@2.8.2) (2019-05-31)

**Note:** Version bump only for package gatsby

## [2.8.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.8.0...gatsby@2.8.1) (2019-05-31)

**Note:** Version bump only for package gatsby

# [2.8.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.6...gatsby@2.8.0) (2019-05-31)

### Features

- **gatsby:** Allow sorting resolved fields ([#14423](https://github.com/gatsbyjs/gatsby/issues/14423)) ([461439a](https://github.com/gatsbyjs/gatsby/commit/461439a))

## [2.7.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.5...gatsby@2.7.6) (2019-05-31)

### Bug Fixes

- **gatsby:** Find identifiers only in the first argument when extracting queries from useStaticQuery ([#14362](https://github.com/gatsbyjs/gatsby/issues/14362)) ([524817a](https://github.com/gatsbyjs/gatsby/commit/524817a)), closes [#14345](https://github.com/gatsbyjs/gatsby/issues/14345)
- **schema:** Handle types wrapped in js array in createResolvers ([#14422](https://github.com/gatsbyjs/gatsby/issues/14422)) ([56647bc](https://github.com/gatsbyjs/gatsby/commit/56647bc))

## [2.7.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.4...gatsby@2.7.5) (2019-05-29)

**Note:** Version bump only for package gatsby

## [2.7.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.3...gatsby@2.7.4) (2019-05-29)

### Features

- **gatsby:** Add `ogv` support to webpack media rule ([#14365](https://github.com/gatsbyjs/gatsby/issues/14365)) ([6070279](https://github.com/gatsbyjs/gatsby/commit/6070279))

## [2.7.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.2...gatsby@2.7.3) (2019-05-27)

### Features

- **gatsby:** use graphiql-explorer ([#14280](https://github.com/gatsbyjs/gatsby/issues/14280)) ([3863f24](https://github.com/gatsbyjs/gatsby/commit/3863f24))

## [2.7.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.1...gatsby@2.7.2) (2019-05-27)

### Bug Fixes

- **gatsby:** send all responses from the proxy API to the client ([#14329](https://github.com/gatsbyjs/gatsby/issues/14329)) ([17b6ea0](https://github.com/gatsbyjs/gatsby/commit/17b6ea0))

## [2.7.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.7.0...gatsby@2.7.1) (2019-05-23)

### Bug Fixes

- **gatsby:** fix `gatsby develop` with Yarn PnP ([#14261](https://github.com/gatsbyjs/gatsby/issues/14261)) ([2870dfb](https://github.com/gatsbyjs/gatsby/commit/2870dfb))

# [2.7.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.6.4...gatsby@2.7.0) (2019-05-23)

### Features

- **schema:** Merge user-defined types with plugin-defined types ([#14116](https://github.com/gatsbyjs/gatsby/issues/14116)) ([321ae05](https://github.com/gatsbyjs/gatsby/commit/321ae05))

## [2.6.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.6.3...gatsby@2.6.4) (2019-05-23)

### Bug Fixes

- **gatsby:** improve `externals` webpack configuration to better support yarn PnP ([#14208](https://github.com/gatsbyjs/gatsby/issues/14208)) ([e47ed89](https://github.com/gatsbyjs/gatsby/commit/e47ed89))

## [2.6.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.6.2...gatsby@2.6.3) (2019-05-22)

### Bug Fixes

- **docs:** Updating Docs so CommonJS syntax with wrapPageElement works ([#14235](https://github.com/gatsbyjs/gatsby/issues/14235)) ([4f53fd5](https://github.com/gatsbyjs/gatsby/commit/4f53fd5))

## [2.6.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.6.1...gatsby@2.6.2) (2019-05-22)

**Note:** Version bump only for package gatsby

## [2.6.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.6.0...gatsby@2.6.1) (2019-05-22)

**Note:** Version bump only for package gatsby

# [2.6.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.7...gatsby@2.6.0) (2019-05-21)

**Note:** Version bump only for package gatsby

## [2.5.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.6...gatsby@2.5.7) (2019-05-20)

### Bug Fixes

- **themes:** package names don't have to match filesystem ([#14149](https://github.com/gatsbyjs/gatsby/issues/14149)) ([e4b27b3](https://github.com/gatsbyjs/gatsby/commit/e4b27b3)), closes [#14134](https://github.com/gatsbyjs/gatsby/issues/14134)

## [2.5.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.5...gatsby@2.5.6) (2019-05-20)

### Bug Fixes

- **develop:** fix "Unexpected token < in JSON at position 0" after restarting development server ([#14166](https://github.com/gatsbyjs/gatsby/issues/14166)) ([c63dbb8](https://github.com/gatsbyjs/gatsby/commit/c63dbb8))
- **gatsby:** Fix ordering for node links when search field isn't id ([#14176](https://github.com/gatsbyjs/gatsby/issues/14176)) ([eeb1f8c](https://github.com/gatsbyjs/gatsby/commit/eeb1f8c))

## [2.5.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.4...gatsby@2.5.5) (2019-05-18)

**Note:** Version bump only for package gatsby

## [2.5.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.3...gatsby@2.5.4) (2019-05-18)

### Features

- **gatsby-source-contentful:** add options validation and more detailed error messages ([#9231](https://github.com/gatsbyjs/gatsby/issues/9231)) ([68cb1a5](https://github.com/gatsbyjs/gatsby/commit/68cb1a5))

## [2.5.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.2...gatsby@2.5.3) (2019-05-17)

### Bug Fixes

- **gatsby:** include includePrerelease in semver.satisfies check ([#14118](https://github.com/gatsbyjs/gatsby/issues/14118)) ([20c2169](https://github.com/gatsbyjs/gatsby/commit/20c2169))

## [2.5.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.1...gatsby@2.5.2) (2019-05-17)

### Bug Fixes

- **gatsby:** fix hot-reloading for hooks (patch hmr) ([#13713](https://github.com/gatsbyjs/gatsby/issues/13713)) ([117fbb4](https://github.com/gatsbyjs/gatsby/commit/117fbb4))

## [2.5.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.5.0...gatsby@2.5.1) (2019-05-17)

### Bug Fixes

- **schema:** Fix proxying invalid field names ([#14108](https://github.com/gatsbyjs/gatsby/issues/14108)) ([6d297c5](https://github.com/gatsbyjs/gatsby/commit/6d297c5))

# [2.5.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.7...gatsby@2.5.0) (2019-05-16)

### Features

- **schema:** Inference controls and improvements ([#13028](https://github.com/gatsbyjs/gatsby/issues/13028)) ([0f8febf](https://github.com/gatsbyjs/gatsby/commit/0f8febf))

## [2.4.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.6...gatsby@2.4.7) (2019-05-16)

### Features

- **gatsby:** cors is enabled correctly in development ([#14065](https://github.com/gatsbyjs/gatsby/issues/14065)) ([32e49ce](https://github.com/gatsbyjs/gatsby/commit/32e49ce))

## [2.4.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.5...gatsby@2.4.6) (2019-05-15)

### Bug Fixes

- **gatsby:** compile themes through default webpack config ([#13651](https://github.com/gatsbyjs/gatsby/issues/13651)) ([d5be306](https://github.com/gatsbyjs/gatsby/commit/d5be306))

## [2.4.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.4...gatsby@2.4.5) (2019-05-14)

### Features

- **gatsby:** allow awaiting API run triggered by createNode action ([#12748](https://github.com/gatsbyjs/gatsby/issues/12748)) ([17a67a5](https://github.com/gatsbyjs/gatsby/commit/17a67a5))

## [2.4.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.3...gatsby@2.4.4) (2019-05-14)

**Note:** Version bump only for package gatsby

## [2.4.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.2...gatsby@2.4.3) (2019-05-09)

**Note:** Version bump only for package gatsby

## [2.4.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.1...gatsby@2.4.2) (2019-05-03)

**Note:** Version bump only for package gatsby

## [2.4.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.4.0...gatsby@2.4.1) (2019-05-03)

**Note:** Version bump only for package gatsby

# [2.4.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.36...gatsby@2.4.0) (2019-05-02)

### Features

- **gatsby:** add assetPrefix to support deploying assets separate from html ([#12128](https://github.com/gatsbyjs/gatsby/issues/12128)) ([8291044](https://github.com/gatsbyjs/gatsby/commit/8291044))

## [2.3.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.35...gatsby@2.3.36) (2019-05-02)

### Bug Fixes

- **types:** node APIs typings should be in GatsbyNode interface not in Node ([#13799](https://github.com/gatsbyjs/gatsby/issues/13799)) ([cbdb039](https://github.com/gatsbyjs/gatsby/commit/cbdb039))

## [2.3.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.34...gatsby@2.3.35) (2019-05-01)

### Bug Fixes

- **types:** update TypeScript declarations ([#13755](https://github.com/gatsbyjs/gatsby/issues/13755)) ([b41755b](https://github.com/gatsbyjs/gatsby/commit/b41755b))

## [2.3.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.33...gatsby@2.3.34) (2019-04-30)

**Note:** Version bump only for package gatsby

## [2.3.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.32...gatsby@2.3.33) (2019-04-29)

### Bug Fixes

- **gatsby:** development proxy should proceed request headers and method ([#13685](https://github.com/gatsbyjs/gatsby/issues/13685)) ([842d9ce](https://github.com/gatsbyjs/gatsby/commit/842d9ce))
- **typo:** fix typos in error message ([#13683](https://github.com/gatsbyjs/gatsby/issues/13683)) ([f472a08](https://github.com/gatsbyjs/gatsby/commit/f472a08))

## [2.3.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.31...gatsby@2.3.32) (2019-04-27)

**Note:** Version bump only for package gatsby

## [2.3.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.30...gatsby@2.3.31) (2019-04-25)

### Bug Fixes

- **gatsby:** fixes react-hot-reloader for new react features ([#13610](https://github.com/gatsbyjs/gatsby/issues/13610)) ([213da5a](https://github.com/gatsbyjs/gatsby/commit/213da5a))

## [2.3.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.29...gatsby@2.3.30) (2019-04-25)

### Features

- **gatsby:** Add details to pagination info ([#13625](https://github.com/gatsbyjs/gatsby/issues/13625)) ([f115994](https://github.com/gatsbyjs/gatsby/commit/f115994))

## [2.3.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.28...gatsby@2.3.29) (2019-04-24)

**Note:** Version bump only for package gatsby

## [2.3.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.27...gatsby@2.3.28) (2019-04-24)

### Bug Fixes

- Add fallback for createContentDigest ([#13584](https://github.com/gatsbyjs/gatsby/issues/13584)) ([093f1f2](https://github.com/gatsbyjs/gatsby/commit/093f1f2))

## [2.3.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.26...gatsby@2.3.27) (2019-04-23)

**Note:** Version bump only for package gatsby

## [2.3.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.25...gatsby@2.3.26) (2019-04-23)

### Bug Fixes

- **docs:** Fix typo in Gatsby Browser APIs ([#13527](https://github.com/gatsbyjs/gatsby/issues/13527)) ([a60a909](https://github.com/gatsbyjs/gatsby/commit/a60a909))
- raise Unexpected Errors in resolve-module-exports ([#13476](https://github.com/gatsbyjs/gatsby/issues/13476)) ([805a1dd](https://github.com/gatsbyjs/gatsby/commit/805a1dd))
- **gatsby:** respect node type owner in deleteNode ([#13492](https://github.com/gatsbyjs/gatsby/issues/13492)) ([dffb74e](https://github.com/gatsbyjs/gatsby/commit/dffb74e))
- **gatsby:** Set fixed precision for "bootstrap finished" timer ([#13528](https://github.com/gatsbyjs/gatsby/issues/13528)) ([74a60af](https://github.com/gatsbyjs/gatsby/commit/74a60af))

## [2.3.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.24...gatsby@2.3.25) (2019-04-18)

**Note:** Version bump only for package gatsby

## [2.3.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.23...gatsby@2.3.24) (2019-04-17)

### Bug Fixes

- Handle links to array of array of File nodes ([#13295](https://github.com/gatsbyjs/gatsby/issues/13295)) ([ed74ec0](https://github.com/gatsbyjs/gatsby/commit/ed74ec0)), closes [#13272](https://github.com/gatsbyjs/gatsby/issues/13272)

## [2.3.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.22...gatsby@2.3.23) (2019-04-15)

### Bug Fixes

- pageInfo.totalCount should be total number of results ([#13352](https://github.com/gatsbyjs/gatsby/issues/13352)) ([f77b053](https://github.com/gatsbyjs/gatsby/commit/f77b053)), closes [#13342](https://github.com/gatsbyjs/gatsby/issues/13342)
- Pin graphql-compose version ([#13356](https://github.com/gatsbyjs/gatsby/issues/13356)) ([7a34c6d](https://github.com/gatsbyjs/gatsby/commit/7a34c6d))
- **cpu-core-count:** fallback to generic Node.JS method if system specific call fails ([#13294](https://github.com/gatsbyjs/gatsby/issues/13294)) ([857e9e3](https://github.com/gatsbyjs/gatsby/commit/857e9e3)), closes [#12734](https://github.com/gatsbyjs/gatsby/issues/12734)
- **gatsby:** bail early if pageResources are not available in public pageRenderer ([#13113](https://github.com/gatsbyjs/gatsby/issues/13113)) ([da1d5a6](https://github.com/gatsbyjs/gatsby/commit/da1d5a6))

### Features

- pathname in SSR APIs when in develop ([#12995](https://github.com/gatsbyjs/gatsby/issues/12995)) ([077a9c8](https://github.com/gatsbyjs/gatsby/commit/077a9c8))

## [2.3.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.21...gatsby@2.3.22) (2019-04-12)

### Bug Fixes

- **gatsby:** fix NODE_ENV & GATSBY_ACTIVE_ENV in webpack ([#13314](https://github.com/gatsbyjs/gatsby/issues/13314)) ([21db36f](https://github.com/gatsbyjs/gatsby/commit/21db36f))
- **themes:** Include user's site in the list of potential shadowFiles ([#13323](https://github.com/gatsbyjs/gatsby/issues/13323)) ([116cb48](https://github.com/gatsbyjs/gatsby/commit/116cb48))

## [2.3.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.20...gatsby@2.3.21) (2019-04-12)

### Bug Fixes

- **themes:** Restrict the paths that count as shadowable for an issuer ([#12930](https://github.com/gatsbyjs/gatsby/issues/12930)) ([e040947](https://github.com/gatsbyjs/gatsby/commit/e040947))

## [2.3.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.19...gatsby@2.3.20) (2019-04-11)

### Features

- **gatsby:** use V8.serialize instead of JSON.stringify if available ([#10732](https://github.com/gatsbyjs/gatsby/issues/10732)) ([c043816](https://github.com/gatsbyjs/gatsby/commit/c043816))

## [2.3.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.18...gatsby@2.3.19) (2019-04-11)

### Bug Fixes

- Get parent not root File node in resolver ([#13289](https://github.com/gatsbyjs/gatsby/issues/13289)) ([8031fcf](https://github.com/gatsbyjs/gatsby/commit/8031fcf)), closes [#13267](https://github.com/gatsbyjs/gatsby/issues/13267) [#13267](https://github.com/gatsbyjs/gatsby/issues/13267)

## [2.3.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.17...gatsby@2.3.18) (2019-04-11)

**Note:** Version bump only for package gatsby

## [2.3.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.16...gatsby@2.3.17) (2019-04-10)

**Note:** Version bump only for package gatsby

## [2.3.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.15...gatsby@2.3.16) (2019-04-09)

### Features

- **gatsby:** Add normalization for pathPrefix, siteUrl, etc ([#12139](https://github.com/gatsbyjs/gatsby/issues/12139)) ([1e74779](https://github.com/gatsbyjs/gatsby/commit/1e74779)), closes [#11871](https://github.com/gatsbyjs/gatsby/issues/11871) [#11871](https://github.com/gatsbyjs/gatsby/issues/11871)

## [2.3.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.14...gatsby@2.3.15) (2019-04-08)

### Bug Fixes

- **gatsby:** move db.startAutosave after bootstrap in `gatsby develop` ([#13180](https://github.com/gatsbyjs/gatsby/issues/13180)) ([530e087](https://github.com/gatsbyjs/gatsby/commit/530e087))

## [2.3.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.13...gatsby@2.3.14) (2019-04-05)

**Note:** Version bump only for package gatsby

## [2.3.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.12...gatsby@2.3.13) (2019-04-04)

### Features

- **gatsby:** add DANGEROUSLY_DISABLE_OOM ([#13066](https://github.com/gatsbyjs/gatsby/issues/13066)) ([800b8d7](https://github.com/gatsbyjs/gatsby/commit/800b8d7))

## [2.3.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.11...gatsby@2.3.12) (2019-04-04)

**Note:** Version bump only for package gatsby

## [2.3.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.10...gatsby@2.3.11) (2019-04-03)

### Bug Fixes

- **query-extraction:** handle duplicated graphql query names error ([#12931](https://github.com/gatsbyjs/gatsby/issues/12931)) ([0263a77](https://github.com/gatsbyjs/gatsby/commit/0263a77))

### Features

- **gatsby:** write match-paths.json ([#13012](https://github.com/gatsbyjs/gatsby/issues/13012)) ([cec5e28](https://github.com/gatsbyjs/gatsby/commit/cec5e28))

## [2.3.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.9...gatsby@2.3.10) (2019-04-03)

### Bug Fixes

- **gatsby:** ignore \_\_esModule export in gatsby-node exports ([#13081](https://github.com/gatsbyjs/gatsby/issues/13081)) ([1c78ffb](https://github.com/gatsbyjs/gatsby/commit/1c78ffb)), closes [#13079](https://github.com/gatsbyjs/gatsby/issues/13079)

## [2.3.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.8...gatsby@2.3.9) (2019-04-03)

### Features

- **gatsby:** add util.promisify polyfill for older node version ([#13024](https://github.com/gatsbyjs/gatsby/issues/13024)) ([b278a60](https://github.com/gatsbyjs/gatsby/commit/b278a60))

## [2.3.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.7...gatsby@2.3.8) (2019-04-03)

### Bug Fixes

- **gatsby:** don't try to statically analyze gatsby-node, require it and examine exports instead ([#13053](https://github.com/gatsbyjs/gatsby/issues/13053)) ([d74b3f0](https://github.com/gatsbyjs/gatsby/commit/d74b3f0))

## [2.3.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.6...gatsby@2.3.7) (2019-04-02)

**Note:** Version bump only for package gatsby

## [2.3.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.5...gatsby@2.3.6) (2019-04-02)

**Note:** Version bump only for package gatsby

## [2.3.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.4...gatsby@2.3.5) (2019-04-02)

### Bug Fixes

- **gatsby:** Only use one redux namespace for plugins ([#12263](https://github.com/gatsbyjs/gatsby/issues/12263)) ([bba69e9](https://github.com/gatsbyjs/gatsby/commit/bba69e9))

### Features

- **gatsby-cli:** Detect if something is already running on a port when running gatsby serve ([#12989](https://github.com/gatsbyjs/gatsby/issues/12989)) ([e587e57](https://github.com/gatsbyjs/gatsby/commit/e587e57))

## [2.3.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.3...gatsby@2.3.4) (2019-03-28)

### Features

- **schema:** Use extensions to specify infer config ([ff102c9](https://github.com/gatsbyjs/gatsby/commit/ff102c9))

## [2.3.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.2...gatsby@2.3.3) (2019-03-27)

### Bug Fixes

- **gatsby:** Handle already deleted nodes in deleteNode action ([#12866](https://github.com/gatsbyjs/gatsby/issues/12866)) ([1548841](https://github.com/gatsbyjs/gatsby/commit/1548841))
- **gatsby-telemetry:** Ensure quickly running commands exit freely ([#12888](https://github.com/gatsbyjs/gatsby/issues/12888)) ([e30d264](https://github.com/gatsbyjs/gatsby/commit/e30d264))
- **themes:** Handle shared parent theme with component shadowing ([#12883](https://github.com/gatsbyjs/gatsby/issues/12883)) ([7a82dc2](https://github.com/gatsbyjs/gatsby/commit/7a82dc2))

### Features

- **themes:** copy static folders in themes ([#12746](https://github.com/gatsbyjs/gatsby/issues/12746)) ([edd6cb1](https://github.com/gatsbyjs/gatsby/commit/edd6cb1))

## [2.3.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.1...gatsby@2.3.2) (2019-03-26)

**Note:** Version bump only for package gatsby

## [2.3.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.3.0...gatsby@2.3.1) (2019-03-26)

**Note:** Version bump only for package gatsby

# [2.3.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.13...gatsby@2.3.0) (2019-03-26)

### Features

- **gatsby:** add anonymous telemetry instrumentation to gatsby ([#12758](https://github.com/gatsbyjs/gatsby/issues/12758)) ([da8ded9](https://github.com/gatsbyjs/gatsby/commit/da8ded9))

## [2.2.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.12...gatsby@2.2.13) (2019-03-26)

### Bug Fixes

- **schema:** Add tests for incorrect list counting ([#12824](https://github.com/gatsbyjs/gatsby/issues/12824)) ([d2bf6f5](https://github.com/gatsbyjs/gatsby/commit/d2bf6f5))
- **schema:** Remove accidental capitalization of lowercase typenames. ([#12837](https://github.com/gatsbyjs/gatsby/issues/12837)) ([d25b39d](https://github.com/gatsbyjs/gatsby/commit/d25b39d))

## [2.2.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.11...gatsby@2.2.12) (2019-03-26)

### Features

- **gatsby:** Move page component state & side effect handling to xstate ([#11897](https://github.com/gatsbyjs/gatsby/issues/11897)) ([91086d4](https://github.com/gatsbyjs/gatsby/commit/91086d4))

## [2.2.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.10...gatsby@2.2.11) (2019-03-25)

**Note:** Version bump only for package gatsby

## [2.2.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.9...gatsby@2.2.10) (2019-03-25)

### Bug Fixes

- **gatsby:** added looksLikeADate to check date on schema creation ([#12722](https://github.com/gatsbyjs/gatsby/issues/12722)) ([aff2c5d](https://github.com/gatsbyjs/gatsby/commit/aff2c5d))
- **gatsby:** Allow setting nullability in createResolvers ([#12775](https://github.com/gatsbyjs/gatsby/issues/12775)) ([4fbac99](https://github.com/gatsbyjs/gatsby/commit/4fbac99))
- **gatsby:** Improve handling of sparse arrays in example value creation ([#12807](https://github.com/gatsbyjs/gatsby/issues/12807)) ([3e84352](https://github.com/gatsbyjs/gatsby/commit/3e84352))
- **schema:** Don't default to tracking all nodes ([#12825](https://github.com/gatsbyjs/gatsby/issues/12825)) ([a9b6d68](https://github.com/gatsbyjs/gatsby/commit/a9b6d68))
- **schema:** fix `types` for buildUnionType config object ([#12814](https://github.com/gatsbyjs/gatsby/issues/12814)) ([0c2cda4](https://github.com/gatsbyjs/gatsby/commit/0c2cda4))
- **schema:** Fix querying for filtered File type ([#12752](https://github.com/gatsbyjs/gatsby/issues/12752)) ([c949b9a](https://github.com/gatsbyjs/gatsby/commit/c949b9a))
- **schema:** Preserve resolvers on \_\_\_NODE fields ([#12806](https://github.com/gatsbyjs/gatsby/issues/12806)) ([e8816bf](https://github.com/gatsbyjs/gatsby/commit/e8816bf))

## [2.2.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.8...gatsby@2.2.9) (2019-03-23)

### Features

- **redux:** cache truePath lookups for performance ([#12693](https://github.com/gatsbyjs/gatsby/issues/12693)) ([d5c3351](https://github.com/gatsbyjs/gatsby/commit/d5c3351))

## [2.2.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.7...gatsby@2.2.8) (2019-03-22)

### Bug Fixes

- **gatsby:** tolerate null object values ([#12756](https://github.com/gatsbyjs/gatsby/issues/12756)) ([7e51263](https://github.com/gatsbyjs/gatsby/commit/7e51263))
- **gatsby-source-filesystem:** pin chokidar@2.1.2 to fix unix issues ([#12759](https://github.com/gatsbyjs/gatsby/issues/12759)) ([0ea1505](https://github.com/gatsbyjs/gatsby/commit/0ea1505))

## [2.2.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.6...gatsby@2.2.7) (2019-03-22)

### Bug Fixes

- **gatsby:** make sure interface implementations in third-party schema ([#12721](https://github.com/gatsbyjs/gatsby/issues/12721)) ([423c953](https://github.com/gatsbyjs/gatsby/commit/423c953))

## [2.2.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.5...gatsby@2.2.6) (2019-03-21)

**Note:** Version bump only for package gatsby

## [2.2.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.4...gatsby@2.2.5) (2019-03-21)

**Note:** Version bump only for package gatsby

## [2.2.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.3...gatsby@2.2.4) (2019-03-21)

### Bug Fixes

- **gatsby:** keep track of pages created by stateful createPages after edits ([#12671](https://github.com/gatsbyjs/gatsby/issues/12671)) ([62f0d10](https://github.com/gatsbyjs/gatsby/commit/62f0d10)), closes [#12143](https://github.com/gatsbyjs/gatsby/issues/12143)
- **gatsby:** quick check if string looks like a date ([#12700](https://github.com/gatsbyjs/gatsby/issues/12700)) ([22a2689](https://github.com/gatsbyjs/gatsby/commit/22a2689)), closes [#12692](https://github.com/gatsbyjs/gatsby/issues/12692)

### Features

- **gatsby:** Add stack trace to error reporting in GraphiQL ([#12690](https://github.com/gatsbyjs/gatsby/issues/12690)) ([efa7d1a](https://github.com/gatsbyjs/gatsby/commit/efa7d1a))

## [2.2.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.2...gatsby@2.2.3) (2019-03-20)

### Features

- **gatsby:** add support for microsecond and alternative iso datetime formats ([#12533](https://github.com/gatsbyjs/gatsby/issues/12533)) ([dfe93ee](https://github.com/gatsbyjs/gatsby/commit/dfe93ee))

## [2.2.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.1...gatsby@2.2.2) (2019-03-19)

### Bug Fixes

- **develop:** query runner queue - use priority buckets for tasks instead of sorting ([#12365](https://github.com/gatsbyjs/gatsby/issues/12365)) ([653d771](https://github.com/gatsbyjs/gatsby/commit/653d771)), closes [#12343](https://github.com/gatsbyjs/gatsby/issues/12343)

## [2.2.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.2.0...gatsby@2.2.1) (2019-03-19)

### Bug Fixes

- **gatsby:** Fix third-party schemas with self-referential queries failing ([#12668](https://github.com/gatsbyjs/gatsby/issues/12668)) ([a1953e0](https://github.com/gatsbyjs/gatsby/commit/a1953e0))

# [2.2.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.39...gatsby@2.2.0) (2019-03-19)

### Features

- **gatsby:** allow schema customization ([#11480](https://github.com/gatsbyjs/gatsby/issues/11480)) ([07e69be](https://github.com/gatsbyjs/gatsby/commit/07e69be))

## [2.1.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.38...gatsby@2.1.39) (2019-03-19)

### Bug Fixes

- **gatsby:** filter null values in headComponents, preBodyComponents and postBodyComponents ([#12555](https://github.com/gatsbyjs/gatsby/issues/12555)) ([f7dbc8b](https://github.com/gatsbyjs/gatsby/commit/f7dbc8b))
- **gatsby:** workaround webpack terser plugin hanging on WSL ([#12636](https://github.com/gatsbyjs/gatsby/issues/12636)) ([8f71f50](https://github.com/gatsbyjs/gatsby/commit/8f71f50)), closes [#6540](https://github.com/gatsbyjs/gatsby/issues/6540) [#7013](https://github.com/gatsbyjs/gatsby/issues/7013)

## [2.1.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.37...gatsby@2.1.38) (2019-03-18)

### Features

- let shadowed components import parents ([#12586](https://github.com/gatsbyjs/gatsby/issues/12586)) ([368c9e0](https://github.com/gatsbyjs/gatsby/commit/368c9e0))

## [2.1.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.36...gatsby@2.1.37) (2019-03-16)

### Bug Fixes

- **gatsby:** extract queries from themes not starting with "gatsby-theme-\*" name ([#12604](https://github.com/gatsbyjs/gatsby/issues/12604)) ([b9808f2](https://github.com/gatsbyjs/gatsby/commit/b9808f2))

## [2.1.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.35...gatsby@2.1.36) (2019-03-16)

**Note:** Version bump only for package gatsby

## [2.1.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.34...gatsby@2.1.35) (2019-03-15)

### Features

- **gatsby:** set up webpack config for eventual PnP support ([#12315](https://github.com/gatsbyjs/gatsby/issues/12315)) ([ad6319b](https://github.com/gatsbyjs/gatsby/commit/ad6319b)), closes [/github.com/arcanis/pnp-webpack-plugin/blob/master/index.js#L110-L138](https://github.com//github.com/arcanis/pnp-webpack-plugin/blob/master/index.js/issues/L110-L138) [#10245](https://github.com/gatsbyjs/gatsby/issues/10245) [#12163](https://github.com/gatsbyjs/gatsby/issues/12163)

## [2.1.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.33...gatsby@2.1.34) (2019-03-14)

### Bug Fixes

- **gatsby:** properly support --no-color for pretty-error ([#12531](https://github.com/gatsbyjs/gatsby/issues/12531)) ([e493538](https://github.com/gatsbyjs/gatsby/commit/e493538))

## [2.1.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.32...gatsby@2.1.33) (2019-03-14)

### Bug Fixes

- **gatsby:** allow environment variables to be replaced per environment ([#10565](https://github.com/gatsbyjs/gatsby/issues/10565)) ([828eaf8](https://github.com/gatsbyjs/gatsby/commit/828eaf8))

## [2.1.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.31...gatsby@2.1.32) (2019-03-13)

### Features

- **redirects:** handle absolute from paths when path prefix is used ([#12509](https://github.com/gatsbyjs/gatsby/issues/12509)) ([c6583d4](https://github.com/gatsbyjs/gatsby/commit/c6583d4)), closes [#12497](https://github.com/gatsbyjs/gatsby/issues/12497)

## [2.1.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.30...gatsby@2.1.31) (2019-03-12)

**Note:** Version bump only for package gatsby

## [2.1.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.29...gatsby@2.1.30) (2019-03-11)

**Note:** Version bump only for package gatsby

## [2.1.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.28...gatsby@2.1.29) (2019-03-11)

### Bug Fixes

- **gatsby:** return graphqlRunner from bootstrap ([#12477](https://github.com/gatsbyjs/gatsby/issues/12477)) ([79b7d4e](https://github.com/gatsbyjs/gatsby/commit/79b7d4e))

## [2.1.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.27...gatsby@2.1.28) (2019-03-11)

### Bug Fixes

- **gatsby:** correct bootstrap emit order ([#12473](https://github.com/gatsbyjs/gatsby/issues/12473)) ([fceb4e7](https://github.com/gatsbyjs/gatsby/commit/fceb4e7))
- **gatsby:** Emit BOOTSTRAP_FINISHED when bootstrap finishes ([#12461](https://github.com/gatsbyjs/gatsby/issues/12461)) ([0f136d5](https://github.com/gatsbyjs/gatsby/commit/0f136d5))

## [2.1.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.26...gatsby@2.1.27) (2019-03-08)

### Bug Fixes

- **gatsby:** Vendor express-static so we can avoid loading html files from public during development ([#12336](https://github.com/gatsbyjs/gatsby/issues/12336)) ([800e023](https://github.com/gatsbyjs/gatsby/commit/800e023)), closes [/github.com/gatsbyjs/gatsby/pull/12243#pullrequestreview-210895624](https://github.com//github.com/gatsbyjs/gatsby/pull/12243/issues/pullrequestreview-210895624)

## [2.1.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.25...gatsby@2.1.26) (2019-03-08)

### Bug Fixes

- **gatsby): Revert "chore(gatsby:** Update more dependencies to support graphql@14" ([#12408](https://github.com/gatsbyjs/gatsby/issues/12408)) ([b040b44](https://github.com/gatsbyjs/gatsby/commit/b040b44)), closes [gatsbyjs/gatsby#11512](https://github.com/gatsbyjs/gatsby/issues/11512)

## [2.1.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.24...gatsby@2.1.25) (2019-03-08)

**Note:** Version bump only for package gatsby

## [2.1.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.23...gatsby@2.1.24) (2019-03-07)

### Features

- **gatsby:** add pnp resolving by passing rootdir in pkg resolving ([#12163](https://github.com/gatsbyjs/gatsby/issues/12163)) ([72e0d6f](https://github.com/gatsbyjs/gatsby/commit/72e0d6f)), closes [#10245](https://github.com/gatsbyjs/gatsby/issues/10245)

## [2.1.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.22...gatsby@2.1.23) (2019-03-05)

### Bug Fixes

- **core:** Only delete html/css files during prod builds ([#12243](https://github.com/gatsbyjs/gatsby/issues/12243)) ([9835f56](https://github.com/gatsbyjs/gatsby/commit/9835f56))
- **gatsby:** don't delete /404.html during development ([#12297](https://github.com/gatsbyjs/gatsby/issues/12297)) ([23488ea](https://github.com/gatsbyjs/gatsby/commit/23488ea))

## [2.1.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.21...gatsby@2.1.22) (2019-03-05)

**Note:** Version bump only for package gatsby

## [2.1.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.20...gatsby@2.1.21) (2019-03-04)

**Note:** Version bump only for package gatsby

## [2.1.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.19...gatsby@2.1.20) (2019-03-04)

### Bug Fixes

- **gatsby:** Call onPostBootstrap only once after bootstrap ([#12262](https://github.com/gatsbyjs/gatsby/issues/12262)) ([8fc999f](https://github.com/gatsbyjs/gatsby/commit/8fc999f))

### Features

- **gatsby:** configure physical cores, logical_cores or fixed number ([#10257](https://github.com/gatsbyjs/gatsby/issues/10257)) ([c51440e](https://github.com/gatsbyjs/gatsby/commit/c51440e))

## [2.1.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.18...gatsby@2.1.19) (2019-02-28)

### Bug Fixes

- **gatsby:** Adapt Loki workaround for eq:null ([#12062](https://github.com/gatsbyjs/gatsby/issues/12062)) ([ff7f5ba](https://github.com/gatsbyjs/gatsby/commit/ff7f5ba))
- **gatsby:** Don't delete nodes multiple times ([#12049](https://github.com/gatsbyjs/gatsby/issues/12049)) ([9a15739](https://github.com/gatsbyjs/gatsby/commit/9a15739))

## [2.1.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.17...gatsby@2.1.18) (2019-02-25)

### Bug Fixes

- **gatsby:** Catch errors when persisting state ([#12046](https://github.com/gatsbyjs/gatsby/issues/12046)) ([8460992](https://github.com/gatsbyjs/gatsby/commit/8460992))
- **gatsby:** normalize component path casing ([#12005](https://github.com/gatsbyjs/gatsby/issues/12005)) ([3006163](https://github.com/gatsbyjs/gatsby/commit/3006163))
- **gatsby:** theme component shadow fails when extension is used ([#12010](https://github.com/gatsbyjs/gatsby/issues/12010)) ([0d11ff5](https://github.com/gatsbyjs/gatsby/commit/0d11ff5))

## [2.1.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.16...gatsby@2.1.17) (2019-02-22)

**Note:** Version bump only for package gatsby

## [2.1.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.15...gatsby@2.1.16) (2019-02-22)

**Note:** Version bump only for package gatsby

## [2.1.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.14...gatsby@2.1.15) (2019-02-22)

**Note:** Version bump only for package gatsby

## [2.1.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.13...gatsby@2.1.14) (2019-02-21)

### Bug Fixes

- **themes:** reverse order of themes checked when shadowing ([#11954](https://github.com/gatsbyjs/gatsby/issues/11954)) ([8284793](https://github.com/gatsbyjs/gatsby/commit/8284793))

## [2.1.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.12...gatsby@2.1.13) (2019-02-20)

### Bug Fixes

- **gatsby:** don't show false positive async createPage warning ([#11929](https://github.com/gatsbyjs/gatsby/issues/11929)) ([5e66f87](https://github.com/gatsbyjs/gatsby/commit/5e66f87))

## [2.1.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.11...gatsby@2.1.12) (2019-02-20)

### Bug Fixes

- **gatsby:** Stopped queueing further calls to onCreatePage after a page is deleted ([#11777](https://github.com/gatsbyjs/gatsby/issues/11777)) ([f32c016](https://github.com/gatsbyjs/gatsby/commit/f32c016))

## [2.1.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.10...gatsby@2.1.11) (2019-02-20)

### Bug Fixes

- **webpack.config.js:** Fix test for one CSS chunk to cover more flavors of CSS ([#11927](https://github.com/gatsbyjs/gatsby/issues/11927)) ([c2c66b9](https://github.com/gatsbyjs/gatsby/commit/c2c66b9))

## [2.1.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.9...gatsby@2.1.10) (2019-02-20)

### Bug Fixes

- **themes:** Remove require.resolve in component resolve path ([#11848](https://github.com/gatsbyjs/gatsby/issues/11848)) ([6295325](https://github.com/gatsbyjs/gatsby/commit/6295325))
- check for dirty pages when nodes are deleted (so queries are ru-run and data is removed from pages) ([#11831](https://github.com/gatsbyjs/gatsby/issues/11831)) ([1fff689](https://github.com/gatsbyjs/gatsby/commit/1fff689))

## [2.1.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.8...gatsby@2.1.9) (2019-02-19)

### Features

- **gatsby:** show warning if createPage was called after createPages API finished ([#11883](https://github.com/gatsbyjs/gatsby/issues/11883)) ([258b655](https://github.com/gatsbyjs/gatsby/commit/258b655))

## [2.1.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.7...gatsby@2.1.8) (2019-02-19)

### Features

- **gatsby-cli:** add a clean command to wipe out local dirs ([#9126](https://github.com/gatsbyjs/gatsby/issues/9126)) ([5807936](https://github.com/gatsbyjs/gatsby/commit/5807936))

## [2.1.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.6...gatsby@2.1.7) (2019-02-19)

### Bug Fixes

- **gatsby:** use route path to serve _exact_ page in client routing ([#11740](https://github.com/gatsbyjs/gatsby/issues/11740)) ([a680e69](https://github.com/gatsbyjs/gatsby/commit/a680e69))

## [2.1.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.5...gatsby@2.1.6) (2019-02-19)

**Note:** Version bump only for package gatsby

## [2.1.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.4...gatsby@2.1.5) (2019-02-19)

**Note:** Version bump only for package gatsby

## [2.1.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.3...gatsby@2.1.4) (2019-02-15)

### Features

- **gatsby:** update cache.set to resolve with set value ([#11327](https://github.com/gatsbyjs/gatsby/issues/11327)) ([930164a](https://github.com/gatsbyjs/gatsby/commit/930164a)), closes [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#11275](https://github.com/gatsbyjs/gatsby/issues/11275)

## [2.1.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.2...gatsby@2.1.3) (2019-02-15)

### Bug Fixes

- Only create one CSS file during builds to avoid problems caused by split CSS files loading in different orders ([#11800](https://github.com/gatsbyjs/gatsby/issues/11800)) ([7058a25](https://github.com/gatsbyjs/gatsby/commit/7058a25)), closes [#11072](https://github.com/gatsbyjs/gatsby/issues/11072)

## [2.1.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.1...gatsby@2.1.2) (2019-02-14)

**Note:** Version bump only for package gatsby

## [2.1.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.1.0...gatsby@2.1.1) (2019-02-14)

### Bug Fixes

- **gatsby:** move to @gatsby scoped version of relay-compiler to fix some upstream bugs([#11759](https://github.com/gatsbyjs/gatsby/pull/11759))

# [2.1.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.120...gatsby@2.1.0) (2019-02-13)

### Features

- **gatsby:** add useStaticQuery hook ([#11588](https://github.com/gatsbyjs/gatsby/issues/11588)) ([f149c4c](https://github.com/gatsbyjs/gatsby/commit/f149c4c))

## [2.0.120](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.119...gatsby@2.0.120) (2019-02-13)

### Bug Fixes

- **core:** added event source polyfill in develop to fix IE/edge hmr ([#11582](https://github.com/gatsbyjs/gatsby/issues/11582)) ([8a6db6a](https://github.com/gatsbyjs/gatsby/commit/8a6db6a)), closes [#11495](https://github.com/gatsbyjs/gatsby/issues/11495)

## [2.0.119](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.118...gatsby@2.0.119) (2019-02-12)

### Bug Fixes

- **gatsby:** add history fallback for client-only routes ([#11610](https://github.com/gatsbyjs/gatsby/issues/11610)) ([a0da7a2](https://github.com/gatsbyjs/gatsby/commit/a0da7a2)), closes [#11581](https://github.com/gatsbyjs/gatsby/issues/11581) [#11581](https://github.com/gatsbyjs/gatsby/issues/11581)

## [2.0.118](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.117...gatsby@2.0.118) (2019-02-08)

### Bug Fixes

- **gatsby:** pin webpack to fix unexpected token error during build ([#11640](https://github.com/gatsbyjs/gatsby/issues/11640)) ([f460b7f](https://github.com/gatsbyjs/gatsby/commit/f460b7f)), closes [#11198](https://github.com/gatsbyjs/gatsby/issues/11198) [webpack/webpack#8656](https://github.com/webpack/webpack/issues/8656) [#11198](https://github.com/gatsbyjs/gatsby/issues/11198) [webpack/webpack#8656](https://github.com/webpack/webpack/issues/8656)

## [2.0.117](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.116...gatsby@2.0.117) (2019-02-07)

### Bug Fixes

- **gatsby:** add sanity check before displaying path for static html build error ([#11620](https://github.com/gatsbyjs/gatsby/issues/11620)) ([3ee60d5](https://github.com/gatsbyjs/gatsby/commit/3ee60d5))
- **gatsby:** Fix Loki query operators special casing ([#11517](https://github.com/gatsbyjs/gatsby/issues/11517)) ([e61692d](https://github.com/gatsbyjs/gatsby/commit/e61692d))

### Features

- **gatsby:** Cache resolved nodes in develop ([#11522](https://github.com/gatsbyjs/gatsby/issues/11522)) ([55e3425](https://github.com/gatsbyjs/gatsby/commit/55e3425))

## [2.0.116](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.115...gatsby@2.0.116) (2019-02-06)

### Bug Fixes

- **gatsby:** use history fallback to display client-only routes in serve ([#11581](https://github.com/gatsbyjs/gatsby/issues/11581)) ([75f6118](https://github.com/gatsbyjs/gatsby/commit/75f6118)), closes [#8080](https://github.com/gatsbyjs/gatsby/issues/8080)

### Features

- **gatsby-plugin-netlify:** Allow status codes in redirects ([#11255](https://github.com/gatsbyjs/gatsby/issues/11255)) ([#11484](https://github.com/gatsbyjs/gatsby/issues/11484)) ([024f6f4](https://github.com/gatsbyjs/gatsby/commit/024f6f4))

## [2.0.115](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.114...gatsby@2.0.115) (2019-02-05)

### Bug Fixes

- **gatsby-cli:** use host option if it is passed ([#11566](https://github.com/gatsbyjs/gatsby/issues/11566)) ([ec15b04](https://github.com/gatsbyjs/gatsby/commit/ec15b04)), closes [#8080](https://github.com/gatsbyjs/gatsby/issues/8080)

## [2.0.114](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.113...gatsby@2.0.114) (2019-02-04)

**Note:** Version bump only for package gatsby

## [2.0.113](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.112...gatsby@2.0.113) (2019-02-04)

**Note:** Version bump only for package gatsby

## [2.0.112](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.111...gatsby@2.0.112) (2019-02-04)

### Bug Fixes

- **gatsby:** update terser-webpack-plugin to avoid webpack error ([#11542](https://github.com/gatsbyjs/gatsby/issues/11542)) ([f945fe8](https://github.com/gatsbyjs/gatsby/commit/f945fe8))

## [2.0.111](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.110...gatsby@2.0.111) (2019-02-01)

### Bug Fixes

- **core:** empty cache if delete fails [docker](<[#11454](https://github.com/gatsbyjs/gatsby/issues/11454)>) ([c2fa762](https://github.com/gatsbyjs/gatsby/commit/c2fa762)), closes [#11097](https://github.com/gatsbyjs/gatsby/issues/11097)

## [2.0.110](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.109...gatsby@2.0.110) (2019-02-01)

**Note:** Version bump only for package gatsby

## [2.0.109](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.108...gatsby@2.0.109) (2019-02-01)

**Note:** Version bump only for package gatsby

## [2.0.108](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.107...gatsby@2.0.108) (2019-02-01)

### Bug Fixes

- **core:** Disable HMR for CSS modules ([#11032](https://github.com/gatsbyjs/gatsby/issues/11032)) ([97c98e9](https://github.com/gatsbyjs/gatsby/commit/97c98e9))

### Features

- **gatsby:** Update graphql to ^14.1.1, relay-compiler to 2.0.0 ([#11377](https://github.com/gatsbyjs/gatsby/issues/11377)) ([97c98e9](https://github.com/gatsbyjs/gatsby/commit/a5b322d))

## [2.0.107](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.106...gatsby@2.0.107) (2019-01-31)

### Bug Fixes

- **gatsby:** always respond with index html without checking path ([#11400](https://github.com/gatsbyjs/gatsby/issues/11400)) ([2f79efe](https://github.com/gatsbyjs/gatsby/commit/2f79efe)), closes [/github.com/gatsbyjs/gatsby/blob/aa4f9397665d6d1e7ea6cdd3bfd6f40b449daccf/packages/gatsby/src/commands/develop.js#L192](https://github.com//github.com/gatsbyjs/gatsby/blob/aa4f9397665d6d1e7ea6cdd3bfd6f40b449daccf/packages/gatsby/src/commands/develop.js/issues/L192)
- **gatsby:** check type when querying by ID ([#11448](https://github.com/gatsbyjs/gatsby/issues/11448)) ([1d95e67](https://github.com/gatsbyjs/gatsby/commit/1d95e67))

### Features

- **gatsby:** Allow specifying sort order per sort field ([#11381](https://github.com/gatsbyjs/gatsby/issues/11381)) ([11e8930](https://github.com/gatsbyjs/gatsby/commit/11e8930))

## [2.0.106](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.105...gatsby@2.0.106) (2019-01-29)

### Features

- **gatsby:** add support for GraphQL playground ([#11193](https://github.com/gatsbyjs/gatsby/issues/11193)) ([2b1b551](https://github.com/gatsbyjs/gatsby/commit/2b1b551))

## [2.0.105](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.104...gatsby@2.0.105) (2019-01-29)

### Features

- **gatsby:** show path to page that fails to render html ([#11390](https://github.com/gatsbyjs/gatsby/issues/11390)) ([3677150](https://github.com/gatsbyjs/gatsby/commit/3677150))

## [2.0.104](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.103...gatsby@2.0.104) (2019-01-29)

### Bug Fixes

- reevaluate page query when page context is modified ([#11048](https://github.com/gatsbyjs/gatsby/issues/11048)) ([6d7c576](https://github.com/gatsbyjs/gatsby/commit/6d7c576))

## [2.0.103](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.102...gatsby@2.0.103) (2019-01-28)

### Features

- **gatsby:** add support for ExportSpecifier in API files ([#11171](https://github.com/gatsbyjs/gatsby/issues/11171)) ([84abff0](https://github.com/gatsbyjs/gatsby/commit/84abff0))
- **gatsby:** extend core theming composition API to be recursive ([#10787](https://github.com/gatsbyjs/gatsby/issues/10787)) ([63c9dd9](https://github.com/gatsbyjs/gatsby/commit/63c9dd9))

## [2.0.102](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.101...gatsby@2.0.102) (2019-01-28)

**Note:** Version bump only for package gatsby

## [2.0.101](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.100...gatsby@2.0.101) (2019-01-28)

**Note:** Version bump only for package gatsby

## [2.0.100](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.99...gatsby@2.0.100) (2019-01-28)

### Features

- **gatsby-plugin-offline:** reload when missing resources and SW was updated + add "onServiceWorkerUpdateReady" API ([#10432](https://github.com/gatsbyjs/gatsby/issues/10432)) ([4a01c6d](https://github.com/gatsbyjs/gatsby/commit/4a01c6d))

## [2.0.99](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.98...gatsby@2.0.99) (2019-01-28)

### Features

- **gatsby:** add Jaeger tracing support ([#10268](https://github.com/gatsbyjs/gatsby/issues/10268)) ([916b834](https://github.com/gatsbyjs/gatsby/commit/916b834))

## [2.0.98](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.97...gatsby@2.0.98) (2019-01-25)

### Bug Fixes

- **gatsby:** Fix regression introduced in [#11149](https://github.com/gatsbyjs/gatsby/issues/11149) ([#11263](https://github.com/gatsbyjs/gatsby/issues/11263)) ([70c3f32](https://github.com/gatsbyjs/gatsby/commit/70c3f32))

## [2.0.97](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.96...gatsby@2.0.97) (2019-01-24)

### Bug Fixes

- **docs:** change bound-action-creators links into actions links ([#11207](https://github.com/gatsbyjs/gatsby/issues/11207)) ([5aaaadb](https://github.com/gatsbyjs/gatsby/commit/5aaaadb))

<a name="2.0.96"></a>

## [2.0.96](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.95...gatsby@2.0.96) (2019-01-24)

**Note:** Version bump only for package gatsby

<a name="2.0.95"></a>

## [2.0.95](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.94...gatsby@2.0.95) (2019-01-24)

### Bug Fixes

- **gatsby:** Resolve all fields before querying with Sift ([#11149](https://github.com/gatsbyjs/gatsby/issues/11149)) ([d432e2a](https://github.com/gatsbyjs/gatsby/commit/d432e2a))
- handle escaped regex string ([#11002](https://github.com/gatsbyjs/gatsby/issues/11002)) ([d7a2885](https://github.com/gatsbyjs/gatsby/commit/d7a2885))

<a name="2.0.94"></a>

## [2.0.94](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.93...gatsby@2.0.94) (2019-01-24)

**Note:** Version bump only for package gatsby

<a name="2.0.93"></a>

## [2.0.93](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.92...gatsby@2.0.93) (2019-01-23)

### Bug Fixes

- **gatsby:** Ensure publicPath is always relative for gatsby develop ([#11227](https://github.com/gatsbyjs/gatsby/issues/11227)) ([549b8ac](https://github.com/gatsbyjs/gatsby/commit/549b8ac))

<a name="2.0.92"></a>

## [2.0.92](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.91...gatsby@2.0.92) (2019-01-23)

### Bug Fixes

- **graphql:** findLinkedNodeByField not returning any value ([#11045](https://github.com/gatsbyjs/gatsby/issues/11045)) ([cef713a](https://github.com/gatsbyjs/gatsby/commit/cef713a)), closes [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234)

### Features

- **browser-api:** add previous location argument to navigation updates ([#11095](https://github.com/gatsbyjs/gatsby/issues/11095)) ([b842255](https://github.com/gatsbyjs/gatsby/commit/b842255))

<a name="2.0.91"></a>

## [2.0.91](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.90...gatsby@2.0.91) (2019-01-10)

**Note:** Version bump only for package gatsby

<a name="2.0.90"></a>

## [2.0.90](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.89...gatsby@2.0.90) (2019-01-09)

### Features

- **gatsby:** Add noscript tag to default-html ([#10945](https://github.com/gatsbyjs/gatsby/issues/10945)) ([d517ead](https://github.com/gatsbyjs/gatsby/commit/d517ead))

<a name="2.0.89"></a>

## [2.0.89](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.88...gatsby@2.0.89) (2019-01-08)

### Bug Fixes

- **gatsby:** test plugin name to handle symlinks, rather than path ([#10835](https://github.com/gatsbyjs/gatsby/issues/10835)) ([f914607](https://github.com/gatsbyjs/gatsby/commit/f914607))

<a name="2.0.88"></a>

## [2.0.88](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.87...gatsby@2.0.88) (2019-01-08)

### Features

- **gatsby:** provide a mechanism for plugins to use a named cache instance ([#10146](https://github.com/gatsbyjs/gatsby/issues/10146)) ([b9a8c00](https://github.com/gatsbyjs/gatsby/commit/b9a8c00))

<a name="2.0.87"></a>

## [2.0.87](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.86...gatsby@2.0.87) (2019-01-08)

### Bug Fixes

- allow plugins to use gatsby-browser.js to load global styles, etc. ([#10845](https://github.com/gatsbyjs/gatsby/issues/10845)) ([33a3e61](https://github.com/gatsbyjs/gatsby/commit/33a3e61))

<a name="2.0.86"></a>

## [2.0.86](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.85...gatsby@2.0.86) (2019-01-08)

### Bug Fixes

- fix SSL naming error caused by @ scoped package name in develop ([#10863](https://github.com/gatsbyjs/gatsby/issues/10863)) ([b5209b9](https://github.com/gatsbyjs/gatsby/commit/b5209b9))

<a name="2.0.85"></a>

## [2.0.85](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.84...gatsby@2.0.85) (2019-01-04)

### Bug Fixes

- **gatsby:** correctly inject static query in theme components ([#10786](https://github.com/gatsbyjs/gatsby/issues/10786)) ([edff703](https://github.com/gatsbyjs/gatsby/commit/edff703))

<a name="2.0.84"></a>

## [2.0.84](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.83...gatsby@2.0.84) (2019-01-04)

### Features

- update builtin ESLint to v5 ([#10220](https://github.com/gatsbyjs/gatsby/issues/10220)) ([2429459](https://github.com/gatsbyjs/gatsby/commit/2429459))

<a name="2.0.83"></a>

## [2.0.83](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.82...gatsby@2.0.83) (2019-01-03)

### Bug Fixes

- don't change default node_modules resolution ([#10561](https://github.com/gatsbyjs/gatsby/issues/10561)) ([201ff4b](https://github.com/gatsbyjs/gatsby/commit/201ff4b))

<a name="2.0.82"></a>

## [2.0.82](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.81...gatsby@2.0.82) (2019-01-02)

**Note:** Version bump only for package gatsby

<a name="2.0.81"></a>

## [2.0.81](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.80...gatsby@2.0.81) (2019-01-01)

**Note:** Version bump only for package gatsby

<a name="2.0.80"></a>

## [2.0.80](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.79...gatsby@2.0.80) (2019-01-01)

**Note:** Version bump only for package gatsby

<a name="2.0.79"></a>

## [2.0.79](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.78...gatsby@2.0.79) (2018-12-31)

### Features

- dev server can now reuse the same tab on Mac ([#6550](https://github.com/gatsbyjs/gatsby/issues/6550)) ([1a4ea3c](https://github.com/gatsbyjs/gatsby/commit/1a4ea3c))

<a name="2.0.78"></a>

## [2.0.78](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.77...gatsby@2.0.78) (2018-12-29)

### Bug Fixes

- **gatsby:** avoid full page refresh when navigating to non-existent page ([#10684](https://github.com/gatsbyjs/gatsby/issues/10684)) ([88866c7](https://github.com/gatsbyjs/gatsby/commit/88866c7))

<a name="2.0.77"></a>

## [2.0.77](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.76...gatsby@2.0.77) (2018-12-27)

### Bug Fixes

- **gatsby:** wrap dev 404 component with route update ([#10653](https://github.com/gatsbyjs/gatsby/issues/10653)) ([754174d](https://github.com/gatsbyjs/gatsby/commit/754174d))

<a name="2.0.76"></a>

## [2.0.76](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.75...gatsby@2.0.76) (2018-12-24)

### Bug Fixes

- **gatsby:** handle missing pages metadata chunk ([#10507](https://github.com/gatsbyjs/gatsby/issues/10507)) ([b9411d8](https://github.com/gatsbyjs/gatsby/commit/b9411d8))
- don't use EnsureResources for development 404 page ([#10625](https://github.com/gatsbyjs/gatsby/issues/10625)) ([f6e2e65](https://github.com/gatsbyjs/gatsby/commit/f6e2e65))

<a name="2.0.75"></a>

## [2.0.75](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.74...gatsby@2.0.75) (2018-12-21)

### Bug Fixes

- **query-runner:** replace .off with .removeListener ([#10613](https://github.com/gatsbyjs/gatsby/issues/10613)) ([ed5e5d5](https://github.com/gatsbyjs/gatsby/commit/ed5e5d5)), closes [#10593](https://github.com/gatsbyjs/gatsby/issues/10593) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#1234](https://github.com/gatsbyjs/gatsby/issues/1234) [#10612](https://github.com/gatsbyjs/gatsby/issues/10612)

<a name="2.0.74"></a>

## [2.0.74](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.73...gatsby@2.0.74) (2018-12-21)

### Bug Fixes

- **gatsby:** fix eventemitter leak in page query runner ([#10593](https://github.com/gatsbyjs/gatsby/issues/10593)) ([80a856f](https://github.com/gatsbyjs/gatsby/commit/80a856f))

<a name="2.0.73"></a>

## [2.0.73](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.72...gatsby@2.0.73) (2018-12-19)

### Bug Fixes

- **gatsby:** Ignore fields with key set to empty string in getExampleValues ([#10557](https://github.com/gatsbyjs/gatsby/issues/10557)) ([86fc9dc](https://github.com/gatsbyjs/gatsby/commit/86fc9dc)), closes [/github.com/graphql/graphql-js/blob/958eb961513de1147c19508d66f97920c26e99e5/src/type/validate.js#L220](https://github.com//github.com/graphql/graphql-js/blob/958eb961513de1147c19508d66f97920c26e99e5/src/type/validate.js/issues/L220) [#10480](https://github.com/gatsbyjs/gatsby/issues/10480)

<a name="2.0.72"></a>

## [2.0.72](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.71...gatsby@2.0.72) (2018-12-18)

**Note:** Version bump only for package gatsby

<a name="2.0.71"></a>

## [2.0.71](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.70...gatsby@2.0.71) (2018-12-18)

### Bug Fixes

- **gatsby:** add Safari 10 support to default terser options ([#10536](https://github.com/gatsbyjs/gatsby/issues/10536)) ([9db27c1](https://github.com/gatsbyjs/gatsby/commit/9db27c1)), closes [/github.com/parcel-bundler/parcel/blob/75310e15f6fa3c8a0ce6593ada1bcca00240ea54/packages/core/parcel-bundler/src/transforms/terser.js#L13](https://github.com//github.com/parcel-bundler/parcel/blob/75310e15f6fa3c8a0ce6593ada1bcca00240ea54/packages/core/parcel-bundler/src/transforms/terser.js/issues/L13)
- **gatsby:** bump minimum react-hot-loader version to get quick fix ([#10542](https://github.com/gatsbyjs/gatsby/issues/10542)) ([9cec72a](https://github.com/gatsbyjs/gatsby/commit/9cec72a)), closes [#10528](https://github.com/gatsbyjs/gatsby/issues/10528)

### Features

- **gatsby:** don't watch files in static directory for production builds ([#5807](https://github.com/gatsbyjs/gatsby/issues/5807)) ([a0bcc58](https://github.com/gatsbyjs/gatsby/commit/a0bcc58))

<a name="2.0.70"></a>

## [2.0.70](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.69...gatsby@2.0.70) (2018-12-17)

**Note:** Version bump only for package gatsby

<a name="2.0.69"></a>

## [2.0.69](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.68...gatsby@2.0.69) (2018-12-17)

**Note:** Version bump only for package gatsby

<a name="2.0.68"></a>

## [2.0.68](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.67...gatsby@2.0.68) (2018-12-17)

**Note:** Version bump only for package gatsby

<a name="2.0.67"></a>

## [2.0.67](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.66...gatsby@2.0.67) (2018-12-13)

### Bug Fixes

- **gatsby:** fix extracting StaticQuery nested in shorthand fragment ([#10443](https://github.com/gatsbyjs/gatsby/issues/10443)) ([d504d44](https://github.com/gatsbyjs/gatsby/commit/d504d44))

<a name="2.0.66"></a>

## [2.0.66](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.65...gatsby@2.0.66) (2018-12-11)

### Features

- **prefetch:** add support for effective-connection-type & saveData ([#10365](https://github.com/gatsbyjs/gatsby/issues/10365)) ([1c51831](https://github.com/gatsbyjs/gatsby/commit/1c51831))

<a name="2.0.65"></a>

## [2.0.65](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.64...gatsby@2.0.65) (2018-12-11)

### Bug Fixes

- **gatsby:** fix false type conflict warning on plugin fields ([#10355](https://github.com/gatsbyjs/gatsby/issues/10355)) ([510fb88](https://github.com/gatsbyjs/gatsby/commit/510fb88))

<a name="2.0.64"></a>

## [2.0.64](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.63...gatsby@2.0.64) (2018-12-07)

### Bug Fixes

- **gatsby:** [loki] sync db autosaves ([#10212](https://github.com/gatsbyjs/gatsby/issues/10212)) ([1c0d051](https://github.com/gatsbyjs/gatsby/commit/1c0d051))

<a name="2.0.63"></a>

## [2.0.63](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.62...gatsby@2.0.63) (2018-12-05)

### Bug Fixes

- **gatsby:** don't remount matchPath pages ([#10261](https://github.com/gatsbyjs/gatsby/issues/10261)) ([1dd3987](https://github.com/gatsbyjs/gatsby/commit/1dd3987))

<a name="2.0.62"></a>

## [2.0.62](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.61...gatsby@2.0.62) (2018-12-04)

### Features

- **gatsby:** update react-hot-loader dependency to enable hooks ([#10259](https://github.com/gatsbyjs/gatsby/issues/10259)) ([bf46002](https://github.com/gatsbyjs/gatsby/commit/bf46002))

<a name="2.0.61"></a>

## [2.0.61](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.60...gatsby@2.0.61) (2018-12-03)

**Note:** Version bump only for package gatsby

<a name="2.0.60"></a>

## [2.0.60](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.59...gatsby@2.0.60) (2018-12-01)

### Bug Fixes

- **gatsby:** skip functions when inferring schema ([#10177](https://github.com/gatsbyjs/gatsby/issues/10177)) ([64a8844](https://github.com/gatsbyjs/gatsby/commit/64a8844)), closes [/github.com/gatsbyjs/gatsby/pull/10159#issuecomment-442045709](https://github.com//github.com/gatsbyjs/gatsby/pull/10159/issues/issuecomment-442045709)

### Features

- **gatsby:** Add type checks to createNodeId ([#10234](https://github.com/gatsbyjs/gatsby/issues/10234)) ([6a86b4d](https://github.com/gatsbyjs/gatsby/commit/6a86b4d))

<a name="2.0.59"></a>

## [2.0.59](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.58...gatsby@2.0.59) (2018-11-29)

### Features

- **gatsby:** add lokijs nodes db implementation ([#9919](https://github.com/gatsbyjs/gatsby/issues/9919)) ([4bcca2a](https://github.com/gatsbyjs/gatsby/commit/4bcca2a)), closes [#9338](https://github.com/gatsbyjs/gatsby/issues/9338)

<a name="2.0.58"></a>

## [2.0.58](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.57...gatsby@2.0.58) (2018-11-29)

**Note:** Version bump only for package gatsby

<a name="2.0.57"></a>

## [2.0.57](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.56...gatsby@2.0.57) (2018-11-28)

### Bug Fixes

- **gatsby:** fix infinite reloads when resources fail ([#10141](https://github.com/gatsbyjs/gatsby/issues/10141)) ([9fc25f3](https://github.com/gatsbyjs/gatsby/commit/9fc25f3)), closes [#10074](https://github.com/gatsbyjs/gatsby/issues/10074)

<a name="2.0.56"></a>

## [2.0.56](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.55...gatsby@2.0.56) (2018-11-27)

**Note:** Version bump only for package gatsby

<a name="2.0.55"></a>

## [2.0.55](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.54...gatsby@2.0.55) (2018-11-22)

### Features

- **gatsby:** use cheap-module-source-map devtool webpack config in develop mode for easier debugging ([#10083](https://github.com/gatsbyjs/gatsby/issues/10083)) ([ce5cbe8](https://github.com/gatsbyjs/gatsby/commit/ce5cbe8)), closes [#6278](https://github.com/gatsbyjs/gatsby/issues/6278)

<a name="2.0.54"></a>

## [2.0.54](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.53...gatsby@2.0.54) (2018-11-21)

### Features

- **gatsby:** warn user about incompatible plugins ([#10034](https://github.com/gatsbyjs/gatsby/issues/10034)) ([8421707](https://github.com/gatsbyjs/gatsby/commit/8421707)), closes [#7143](https://github.com/gatsbyjs/gatsby/issues/7143) [#9731](https://github.com/gatsbyjs/gatsby/issues/9731)

<a name="2.0.53"></a>

## [2.0.53](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.52...gatsby@2.0.53) (2018-11-20)

### Features

- **gatsby-plugin-offline:** replace no-cache detection with dynamic path whitelist ([#9907](https://github.com/gatsbyjs/gatsby/issues/9907)) ([8d3af3f](https://github.com/gatsbyjs/gatsby/commit/8d3af3f))

<a name="2.0.52"></a>

## [2.0.52](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.51...gatsby@2.0.52) (2018-11-19)

### Bug Fixes

- prefix graphql type names with underscore if it starts with number ([#10007](https://github.com/gatsbyjs/gatsby/issues/10007)) ([1d2a9be](https://github.com/gatsbyjs/gatsby/commit/1d2a9be)), closes [#9950](https://github.com/gatsbyjs/gatsby/issues/9950)

<a name="2.0.51"></a>

## [2.0.51](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.50...gatsby@2.0.51) (2018-11-19)

### Bug Fixes

- avoid leaking defined env vars when trying to access not defined env vars ([#10030](https://github.com/gatsbyjs/gatsby/issues/10030)) ([8061e3b](https://github.com/gatsbyjs/gatsby/commit/8061e3b))

<a name="2.0.50"></a>

## [2.0.50](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.49...gatsby@2.0.50) (2018-11-15)

### Bug Fixes

- **gatsby:** correctly pick up browserslist overrides ([#9669](https://github.com/gatsbyjs/gatsby/issues/9669)) ([0f0feac](https://github.com/gatsbyjs/gatsby/commit/0f0feac))

<a name="2.0.49"></a>

## [2.0.49](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.48...gatsby@2.0.49) (2018-11-14)

### Bug Fixes

- **docs:** update broken links with working links ([#9912](https://github.com/gatsbyjs/gatsby/issues/9912)) ([e9f2a6f](https://github.com/gatsbyjs/gatsby/commit/e9f2a6f))

<a name="2.0.48"></a>

## [2.0.48](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.47...gatsby@2.0.48) (2018-11-13)

**Note:** Version bump only for package gatsby

<a name="2.0.47"></a>

## [2.0.47](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.46...gatsby@2.0.47) (2018-11-12)

**Note:** Version bump only for package gatsby

<a name="2.0.46"></a>

## [2.0.46](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.45...gatsby@2.0.46) (2018-11-12)

**Note:** Version bump only for package gatsby

<a name="2.0.45"></a>

## [2.0.45](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.44...gatsby@2.0.45) (2018-11-09)

### Bug Fixes

- handle development proxy exceptions and show some context ([#9839](https://github.com/gatsbyjs/gatsby/issues/9839)) ([b605ade](https://github.com/gatsbyjs/gatsby/commit/b605ade)), closes [#6771](https://github.com/gatsbyjs/gatsby/issues/6771)

<a name="2.0.44"></a>

## [2.0.44](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.43...gatsby@2.0.44) (2018-11-09)

### Features

- show GraphQL compile errors in browser overlay ([#6247](https://github.com/gatsbyjs/gatsby/issues/6247)) ([2cd7bfa](https://github.com/gatsbyjs/gatsby/commit/2cd7bfa)), closes [#5234](https://github.com/gatsbyjs/gatsby/issues/5234)

<a name="2.0.43"></a>

## [2.0.43](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.42...gatsby@2.0.43) (2018-11-08)

**Note:** Version bump only for package gatsby

<a name="2.0.42"></a>

## [2.0.42](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.41...gatsby@2.0.42) (2018-11-08)

### Bug Fixes

- use relative HMR path ([#9734](https://github.com/gatsbyjs/gatsby/issues/9734)) ([c4b9283](https://github.com/gatsbyjs/gatsby/commit/c4b9283))

<a name="2.0.41"></a>

## [2.0.41](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.40...gatsby@2.0.41) (2018-11-08)

### Features

- pass pathname to replaceRenderer and onPreRenderHTML SSR APIs ([#9792](https://github.com/gatsbyjs/gatsby/issues/9792)) ([f032ceb](https://github.com/gatsbyjs/gatsby/commit/f032ceb))

<a name="2.0.40"></a>

## [2.0.40](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.39...gatsby@2.0.40) (2018-11-06)

### Bug Fixes

- adjust page order to make nested matchPaths work ([#9719](https://github.com/gatsbyjs/gatsby/issues/9719)) ([5b4e0b5](https://github.com/gatsbyjs/gatsby/commit/5b4e0b5)), closes [#9705](https://github.com/gatsbyjs/gatsby/issues/9705)

<a name="2.0.39"></a>

## [2.0.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.38...gatsby@2.0.39) (2018-11-05)

**Note:** Version bump only for package gatsby

<a name="2.0.38"></a>

## [2.0.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.37...gatsby@2.0.38) (2018-11-02)

### Bug Fixes

- load plugin object style without options object ([#9647](https://github.com/gatsbyjs/gatsby/issues/9647)) ([42a2d07](https://github.com/gatsbyjs/gatsby/commit/42a2d07)), closes [#9559](https://github.com/gatsbyjs/gatsby/issues/9559)

<a name="2.0.37"></a>

## [2.0.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.36...gatsby@2.0.37) (2018-11-01)

**Note:** Version bump only for package gatsby

<a name="2.0.36"></a>

## [2.0.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.35...gatsby@2.0.36) (2018-11-01)

### Bug Fixes

- **gatsby:** detect additional 404 page locations when performing canonical path redirects ([679db41](https://github.com/gatsbyjs/gatsby/commit/679db41))

### Features

- **gatsby:** Move connection out of sift ([#9508](https://github.com/gatsbyjs/gatsby/issues/9508)) ([8c7a745](https://github.com/gatsbyjs/gatsby/commit/8c7a745)), closes [#9416](https://github.com/gatsbyjs/gatsby/issues/9416) [#9338](https://github.com/gatsbyjs/gatsby/issues/9338)

<a name="2.0.35"></a>

## [2.0.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.34...gatsby@2.0.35) (2018-10-30)

### Bug Fixes

- **gatsby:** fix crash on inferring input type with missing node ([#9487](https://github.com/gatsbyjs/gatsby/issues/9487)) ([b5b43d5](https://github.com/gatsbyjs/gatsby/commit/b5b43d5))

<a name="2.0.34"></a>

## [2.0.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.33...gatsby@2.0.34) (2018-10-29)

### Features

- **gatsby:** use json-stream-stringify to serialize redux state ([#9370](https://github.com/gatsbyjs/gatsby/issues/9370)) ([c334075](https://github.com/gatsbyjs/gatsby/commit/c334075)), closes [#9362](https://github.com/gatsbyjs/gatsby/issues/9362)

<a name="2.0.33"></a>

## [2.0.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.32...gatsby@2.0.33) (2018-10-29)

### Features

- **gatsby:** Add nodes db module ([#9416](https://github.com/gatsbyjs/gatsby/issues/9416)) ([7d31fe7](https://github.com/gatsbyjs/gatsby/commit/7d31fe7)), closes [#9338](https://github.com/gatsbyjs/gatsby/issues/9338)

<a name="2.0.32"></a>

## [2.0.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.31...gatsby@2.0.32) (2018-10-29)

### Bug Fixes

- **gatsby-plugin-jss:** use separate SheetsRegistry for each page ([#9401](https://github.com/gatsbyjs/gatsby/issues/9401)) ([15375c8](https://github.com/gatsbyjs/gatsby/commit/15375c8)), closes [#7716](https://github.com/gatsbyjs/gatsby/issues/7716)

<a name="2.0.31"></a>

## [2.0.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.30...gatsby@2.0.31) (2018-10-24)

**Note:** Version bump only for package gatsby

<a name="2.0.30"></a>

## [2.0.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.29...gatsby@2.0.30) (2018-10-24)

**Note:** Version bump only for package gatsby

<a name="2.0.29"></a>

## [2.0.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.28...gatsby@2.0.29) (2018-10-23)

### Bug Fixes

- handle node api-api error gracefully ([#9255](https://github.com/gatsbyjs/gatsby/issues/9255)) ([fa8ef4e](https://github.com/gatsbyjs/gatsby/commit/fa8ef4e))
- **package.json:** update homepage to point at the package ([#9227](https://github.com/gatsbyjs/gatsby/issues/9227)) ([69fd92b](https://github.com/gatsbyjs/gatsby/commit/69fd92b))

<a name="2.0.28"></a>

## [2.0.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.27...gatsby@2.0.28) (2018-10-19)

### Bug Fixes

- **schema:** share union type instances ([#9052](https://github.com/gatsbyjs/gatsby/issues/9052)) ([d87881a](https://github.com/gatsbyjs/gatsby/commit/d87881a))
- fix builds without gatsby-config [#8917](https://github.com/gatsbyjs/gatsby/issues/8917) ([#9256](https://github.com/gatsbyjs/gatsby/issues/9256)) ([27fcc4d](https://github.com/gatsbyjs/gatsby/commit/27fcc4d))

<a name="2.0.27"></a>

## [2.0.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.26...gatsby@2.0.27) (2018-10-19)

### Bug Fixes

- **gatsby:** ignore `__esModule` property when resolving module exports ([#9226](https://github.com/gatsbyjs/gatsby/issues/9226)) ([c57f1e0](https://github.com/gatsbyjs/gatsby/commit/c57f1e0))

<a name="2.0.26"></a>

## [2.0.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.25...gatsby@2.0.26) (2018-10-18)

### Bug Fixes

- check for empty fields in InputFilter inference ([#9057](https://github.com/gatsbyjs/gatsby/issues/9057)) ([4a0563e](https://github.com/gatsbyjs/gatsby/commit/4a0563e))

<a name="2.0.25"></a>

## [2.0.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.24...gatsby@2.0.25) (2018-10-16)

### Bug Fixes

- **gatsby:** Prevent minifier from compressing output using ES6+ syntax ([#9135](https://github.com/gatsbyjs/gatsby/issues/9135)) ([fed6d35](https://github.com/gatsbyjs/gatsby/commit/fed6d35))

<a name="2.0.24"></a>

## [2.0.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.23...gatsby@2.0.24) (2018-10-16)

### Bug Fixes

- **gatsby:** add main field pointing to transpiled commonjs entry ([#9123](https://github.com/gatsbyjs/gatsby/issues/9123)) ([eeca436](https://github.com/gatsbyjs/gatsby/commit/eeca436))
- make elemMatch operator work with \_\_\_NODE arrays ([#8076](https://github.com/gatsbyjs/gatsby/issues/8076)) ([d0b9d94](https://github.com/gatsbyjs/gatsby/commit/d0b9d94))

<a name="2.0.23"></a>

## [2.0.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.22...gatsby@2.0.23) (2018-10-15)

### Bug Fixes

- querying nodes by id and operator different than eq ([#9101](https://github.com/gatsbyjs/gatsby/issues/9101)) ([ccc3082](https://github.com/gatsbyjs/gatsby/commit/ccc3082))

<a name="2.0.22"></a>

## [2.0.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.21...gatsby@2.0.22) (2018-10-12)

**Note:** Version bump only for package gatsby

<a name="2.0.21"></a>

## [2.0.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.20...gatsby@2.0.21) (2018-10-10)

### Features

- add onCreateDevServer node api ([#7556](https://github.com/gatsbyjs/gatsby/issues/7556)) ([a1d3d70](https://github.com/gatsbyjs/gatsby/commit/a1d3d70))
- store sync token for contentful preview ([#8814](https://github.com/gatsbyjs/gatsby/issues/8814)) ([365942b](https://github.com/gatsbyjs/gatsby/commit/365942b))

<a name="2.0.20"></a>

## [2.0.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.19...gatsby@2.0.20) (2018-10-09)

### Bug Fixes

- **gatsby-plugin-offline:** delay adding resources for paths until we have urls ([#8613](https://github.com/gatsbyjs/gatsby/issues/8613)) ([2605aa0](https://github.com/gatsbyjs/gatsby/commit/2605aa0))
- **register-service-worker:** show an error if installing SW not over HTTPS ([#8958](https://github.com/gatsbyjs/gatsby/issues/8958)) ([2ba57ea](https://github.com/gatsbyjs/gatsby/commit/2ba57ea))
- more work to prevent queries from running when there's in-progress node processing ([#8859](https://github.com/gatsbyjs/gatsby/issues/8859)) ([00eeef0](https://github.com/gatsbyjs/gatsby/commit/00eeef0))

<a name="2.0.19"></a>

## [2.0.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.18...gatsby@2.0.19) (2018-10-05)

### Bug Fixes

- hot-reload page updates when querying by id ([#8799](https://github.com/gatsbyjs/gatsby/issues/8799)) ([508d3b6](https://github.com/gatsbyjs/gatsby/commit/508d3b6))
- pretty print syntax error in gatsby api files ([#8723](https://github.com/gatsbyjs/gatsby/issues/8723)) ([1ef38c2](https://github.com/gatsbyjs/gatsby/commit/1ef38c2))

<a name="2.0.18"></a>

## [2.0.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.17...gatsby@2.0.18) (2018-10-03)

### Features

- **gatsby:** switch to different caching mechanism backed by fs ([#8435](https://github.com/gatsbyjs/gatsby/issues/8435)) ([5386e1d](https://github.com/gatsbyjs/gatsby/commit/5386e1d))

<a name="2.0.17"></a>

## [2.0.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.16...gatsby@2.0.17) (2018-10-02)

**Note:** Version bump only for package gatsby

<a name="2.0.16"></a>

## [2.0.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.15...gatsby@2.0.16) (2018-10-02)

### Bug Fixes

- **gatsby:** add mjs config to webpack and resolve correctly ([#8717](https://github.com/gatsbyjs/gatsby/issues/8717)) ([a0cbbcb](https://github.com/gatsbyjs/gatsby/commit/a0cbbcb)), closes [#8655](https://github.com/gatsbyjs/gatsby/issues/8655)

<a name="2.0.15"></a>

## [2.0.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.14...gatsby@2.0.15) (2018-10-02)

**Note:** Version bump only for package gatsby

<a name="2.0.14"></a>

## [2.0.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.13...gatsby@2.0.14) (2018-10-01)

**Note:** Version bump only for package gatsby

<a name="2.0.13"></a>

## [2.0.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.12...gatsby@2.0.13) (2018-10-01)

### Bug Fixes

- run onPreRenderHTML after gatsby-script-loader and gatsby-chunk-mapper ([#8043](https://github.com/gatsbyjs/gatsby/issues/8043)) ([3bec55e](https://github.com/gatsbyjs/gatsby/commit/3bec55e))

<a name="2.0.12"></a>

## [2.0.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.11...gatsby@2.0.12) (2018-09-28)

### Bug Fixes

- add missing html and body attributes from ssr apis to develop mode ([#8594](https://github.com/gatsbyjs/gatsby/issues/8594)) ([e4dcd85](https://github.com/gatsbyjs/gatsby/commit/e4dcd85))

<a name="2.0.11"></a>

## [2.0.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.10...gatsby@2.0.11) (2018-09-27)

### Bug Fixes

- fix unhandled rejection when no browser found when running with --open flag ([#8507](https://github.com/gatsbyjs/gatsby/issues/8507)) ([f497b74](https://github.com/gatsbyjs/gatsby/commit/f497b74))

<a name="2.0.10"></a>

## [2.0.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.9...gatsby@2.0.10) (2018-09-27)

### Bug Fixes

- fix displaying and hydrating 404 page in production builds ([#8510](https://github.com/gatsbyjs/gatsby/issues/8510)) ([c42924a](https://github.com/gatsbyjs/gatsby/commit/c42924a))

### Features

- **cache-dir:** Add a button for custom 404s in development ([#8548](https://github.com/gatsbyjs/gatsby/issues/8548)) ([0658f0b](https://github.com/gatsbyjs/gatsby/commit/0658f0b)), closes [#8234](https://github.com/gatsbyjs/gatsby/issues/8234)

<a name="2.0.9"></a>

## [2.0.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.8...gatsby@2.0.9) (2018-09-26)

### Bug Fixes

- scroll behaviour when navigating back to anchor on the same page ([#8061](https://github.com/gatsbyjs/gatsby/issues/8061)) ([ef44cff](https://github.com/gatsbyjs/gatsby/commit/ef44cff))

<a name="2.0.8"></a>

## [2.0.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.7...gatsby@2.0.8) (2018-09-24)

### Bug Fixes

- check for INVALID_VALUE to avoid throwing exceptions on bad data ([#8346](https://github.com/gatsbyjs/gatsby/issues/8346)) ([bb5c0d2](https://github.com/gatsbyjs/gatsby/commit/bb5c0d2))

<a name="2.0.7"></a>

## [2.0.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.6...gatsby@2.0.7) (2018-09-21)

**Note:** Version bump only for package gatsby

<a name="2.0.6"></a>

## [2.0.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.5...gatsby@2.0.6) (2018-09-19)

**Note:** Version bump only for package gatsby

<a name="2.0.5"></a>

## [2.0.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.4...gatsby@2.0.5) (2018-09-19)

**Note:** Version bump only for package gatsby

<a name="2.0.4"></a>

## [2.0.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.3...gatsby@2.0.4) (2018-09-19)

**Note:** Version bump only for package gatsby

<a name="2.0.3"></a>

## [2.0.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.2...gatsby@2.0.3) (2018-09-18)

**Note:** Version bump only for package gatsby

<a name="2.0.2"></a>

## [2.0.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.1...gatsby@2.0.2) (2018-09-18)

### Features

- add --prefix-paths option to gatsby serve cli ([#8060](https://github.com/gatsbyjs/gatsby/issues/8060)) ([98c8e91](https://github.com/gatsbyjs/gatsby/commit/98c8e91))

<a name="2.0.1"></a>

## [2.0.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.28...gatsby@2.0.1) (2018-09-18)

**Note:** Version bump only for package gatsby

<a name="2.0.0"></a>

## [2.0.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.28...gatsby@2.0.0) (2018-09-17)

### Added

- Improve Gatsby's routing accessibility by integrating @reach/router (#6918) @KyleAMathews
- Add new onPreRenderHTML SSR API to manage head components in html.js (#6760) @octalmage
- Improve build speeds on larger sites (HulkSmash!) (#6226) @KyleAMathews
- Add multi-process HTML rendering support(#6417) @KyleAMathews
- Add babel-plugin-macros for custom babel config (#7129) @porfirioribeiro
- Upgrade webpack to v3, improve webpack utils (#3126) @jquense
- Add gatsby-remark-graphviz plugin to render dot (graphviz) code blocks to SVG (#7341) @Moocar
- Improve support for non-latin language content in gatsby-transformer-remark (#6992) @youngboy
- Improve support for Drupal relationships in gatsby-source-drupal (#5020) @pieh
- Add support for extra connection string params in gatsby-source-mongodb (#5972) @lcostea
- Add support for additional options supplied to gatsby-plugin-styled-components (#5240) @nihgwu
- Add guide on debugging the Gatsby build process (#6369) @pieh
- Add docs on unit testing, Cypress, react-testing-library and testing CSS-in-JS (#6678, #6708) @ascorbic, @LekoArts
- Redesigned docs navigation and expanded docs topics (#6245, #6610) @shannonbux, @fk
- Allow plugins to override core prefetching behavior (#5320) @KyleAMathews
- Add gatsby-codemods package to assist v1 -> v2 transition (#6122) @jquense
- Add gatsby-plugin-layout package to allow use of v1 layout components in v2 (#7204) @pieh
- Add support for service worker caching of prefetched resources in gatsby-plugin-offline (#6566) @kkemple
- Add critical scripts and links to static file globs in service worker in gatsby-plugin-offline (#6316) @kkemple
- Add snapshot testing for gatsby-link (#7090) @alexandernanberg
- Introduce REPL command to gatsby-cli (#7262) @kkemple
- Add support for webpackPrefetch (#5901) @pistachiology
- Explicitly export graphql tag from Gatsby (#5415) @pieh
- Add eslint-loader and eslint configuration (#4893) @kkemple
- Improve loading graphql query results ("ludicrous mode!") (#4555) @m-allanson
- Improve error messaging when Gatsby is not installed (#7106) @KyleAMathews
- Improve modifyWebpackConfig error messaging (#7152) @m-allanson
- Add support for open tracing with zipkin (#6347) @Moocar
- Improve error messaging when plugin can't be loaded (#7023) @KyleAMathews
- Display formatted message for graphql resolver errors (#6142) @pieh
- Improve error formatting on HTML build errors (#6188) @pieh

### Fixed

- Fix out of memory error by saving state to after bootstrap is complete (#6636) @KyleAMathews
- Fix out of memory error by flattening entry values (#6797) @chuntley
- Fix code syntax formatting bug which highlighted keywords in plaintext (#7342) @tryzniak
- Remove dependency on react-lifecycles-compat (#7070) @alexandernanberg
- Prevent both preloading and inlining css in head (#6009) @thescientist13
- Fix service worker bug originating from inlining webpack-runtime (#5540) @KyleAMathews
- Fix bug producing duplicates when naming GraphQL queries (#6765) @fusepilot
- Fix typo in type annotation (#6288) @sudodoki
- Fix showing 404 page in development (#7140) @KyleAMathews
- Tighten externals matching to prevent code imports from causing build errors (#7325) @m-allanson

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.28"></a>

# [2.0.0-rc.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.27...gatsby@2.0.0-rc.28) (2018-09-17)

### Features

- add generator meta tag for gatsby version ([#8221](https://github.com/gatsbyjs/gatsby/issues/8221)) ([0de459a](https://github.com/gatsbyjs/gatsby/commit/0de459a))

<a name="2.0.0-rc.27"></a>

# [2.0.0-rc.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.26...gatsby@2.0.0-rc.27) (2018-09-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.26"></a>

# [2.0.0-rc.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.25...gatsby@2.0.0-rc.26) (2018-09-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.25"></a>

# [2.0.0-rc.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.24...gatsby@2.0.0-rc.25) (2018-09-14)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.24"></a>

# [2.0.0-rc.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.23...gatsby@2.0.0-rc.24) (2018-09-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.23"></a>

# [2.0.0-rc.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.22...gatsby@2.0.0-rc.23) (2018-09-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.22"></a>

# [2.0.0-rc.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.21...gatsby@2.0.0-rc.22) (2018-09-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.21"></a>

# [2.0.0-rc.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.20...gatsby@2.0.0-rc.21) (2018-09-12)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.20"></a>

# [2.0.0-rc.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.19...gatsby@2.0.0-rc.20) (2018-09-12)

### Bug Fixes

- bug where client routes are redirected to their base page path ([#8083](https://github.com/gatsbyjs/gatsby/issues/8083)) ([4cd37ea](https://github.com/gatsbyjs/gatsby/commit/4cd37ea))

<a name="2.0.0-rc.19"></a>

# [2.0.0-rc.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.18...gatsby@2.0.0-rc.19) (2018-09-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.18"></a>

# [2.0.0-rc.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.17...gatsby@2.0.0-rc.18) (2018-09-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.17"></a>

# [2.0.0-rc.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.16...gatsby@2.0.0-rc.17) (2018-09-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.16"></a>

# [2.0.0-rc.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.15...gatsby@2.0.0-rc.16) (2018-09-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.15"></a>

# [2.0.0-rc.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.14...gatsby@2.0.0-rc.15) (2018-09-08)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.14"></a>

# [2.0.0-rc.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.13...gatsby@2.0.0-rc.14) (2018-09-07)

### Bug Fixes

- ensure graphql key (starting with numeric) is valid ([#7913](https://github.com/gatsbyjs/gatsby/issues/7913)) ([dd8f79c](https://github.com/gatsbyjs/gatsby/commit/dd8f79c))
- remove some warnings on promises ([#7922](https://github.com/gatsbyjs/gatsby/issues/7922)) ([e069f27](https://github.com/gatsbyjs/gatsby/commit/e069f27))

<a name="2.0.0-rc.13"></a>

# [2.0.0-rc.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.12...gatsby@2.0.0-rc.13) (2018-09-05)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.12"></a>

# [2.0.0-rc.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.11...gatsby@2.0.0-rc.12) (2018-09-05)

### Bug Fixes

- sort data before writing into the data.json cache file ([#7878](https://github.com/gatsbyjs/gatsby/issues/7878)) ([4cfee57](https://github.com/gatsbyjs/gatsby/commit/4cfee57))

<a name="2.0.0-rc.11"></a>

# [2.0.0-rc.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.10...gatsby@2.0.0-rc.11) (2018-09-05)

### Bug Fixes

- babel options ([#7865](https://github.com/gatsbyjs/gatsby/issues/7865)) ([9c45441](https://github.com/gatsbyjs/gatsby/commit/9c45441))

<a name="2.0.0-rc.10"></a>

# [2.0.0-rc.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.9...gatsby@2.0.0-rc.10) (2018-09-04)

### Bug Fixes

- babel default options ([300277d](https://github.com/gatsbyjs/gatsby/commit/300277d))

<a name="2.0.0-rc.9"></a>

# [2.0.0-rc.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.8...gatsby@2.0.0-rc.9) (2018-09-03)

### Bug Fixes

- setBabelOptions ([#7838](https://github.com/gatsbyjs/gatsby/issues/7838)) ([66101ca](https://github.com/gatsbyjs/gatsby/commit/66101ca))

<a name="2.0.0-rc.8"></a>

# [2.0.0-rc.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.7...gatsby@2.0.0-rc.8) (2018-09-03)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.7"></a>

# [2.0.0-rc.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.6...gatsby@2.0.0-rc.7) (2018-08-31)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.6"></a>

# [2.0.0-rc.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.5...gatsby@2.0.0-rc.6) (2018-08-31)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.5"></a>

# [2.0.0-rc.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.4...gatsby@2.0.0-rc.5) (2018-08-31)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.4"></a>

# [2.0.0-rc.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.3...gatsby@2.0.0-rc.4) (2018-08-29)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.3"></a>

# [2.0.0-rc.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.2...gatsby@2.0.0-rc.3) (2018-08-29)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.2"></a>

# [2.0.0-rc.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.1...gatsby@2.0.0-rc.2) (2018-08-29)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.1"></a>

# [2.0.0-rc.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-rc.0...gatsby@2.0.0-rc.1) (2018-08-29)

**Note:** Version bump only for package gatsby

<a name="2.0.0-rc.0"></a>

# [2.0.0-rc.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.113...gatsby@2.0.0-rc.0) (2018-08-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.113"></a>

# [2.0.0-beta.113](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.112...gatsby@2.0.0-beta.113) (2018-08-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.112"></a>

# [2.0.0-beta.112](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.111...gatsby@2.0.0-beta.112) (2018-08-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.111"></a>

# [2.0.0-beta.111](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.110...gatsby@2.0.0-beta.111) (2018-08-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.110"></a>

# [2.0.0-beta.110](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.109...gatsby@2.0.0-beta.110) (2018-08-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.109"></a>

# [2.0.0-beta.109](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.108...gatsby@2.0.0-beta.109) (2018-08-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.108"></a>

# [2.0.0-beta.108](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.107...gatsby@2.0.0-beta.108) (2018-08-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.107"></a>

# [2.0.0-beta.107](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.106...gatsby@2.0.0-beta.107) (2018-08-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.106"></a>

# [2.0.0-beta.106](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.105...gatsby@2.0.0-beta.106) (2018-08-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.105"></a>

# [2.0.0-beta.105](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.104...gatsby@2.0.0-beta.105) (2018-08-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.104"></a>

# [2.0.0-beta.104](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.103...gatsby@2.0.0-beta.104) (2018-08-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.103"></a>

# [2.0.0-beta.103](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.102...gatsby@2.0.0-beta.103) (2018-08-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.102"></a>

# [2.0.0-beta.102](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.101...gatsby@2.0.0-beta.102) (2018-08-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.101"></a>

# [2.0.0-beta.101](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.100...gatsby@2.0.0-beta.101) (2018-08-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.100"></a>

# [2.0.0-beta.100](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.99...gatsby@2.0.0-beta.100) (2018-08-14)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.99"></a>

# [2.0.0-beta.99](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.97...gatsby@2.0.0-beta.99) (2018-08-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.97"></a>

# [2.0.0-beta.97](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.96...gatsby@2.0.0-beta.97) (2018-08-10)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.96"></a>

# [2.0.0-beta.96](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.95...gatsby@2.0.0-beta.96) (2018-08-10)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.95"></a>

# [2.0.0-beta.95](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.94...gatsby@2.0.0-beta.95) (2018-08-10)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.94"></a>

# [2.0.0-beta.94](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.93...gatsby@2.0.0-beta.94) (2018-08-10)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.93"></a>

# [2.0.0-beta.93](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.92...gatsby@2.0.0-beta.93) (2018-08-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.92"></a>

# [2.0.0-beta.92](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.91...gatsby@2.0.0-beta.92) (2018-08-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.91"></a>

# [2.0.0-beta.91](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.90...gatsby@2.0.0-beta.91) (2018-08-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.90"></a>

# [2.0.0-beta.90](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.89...gatsby@2.0.0-beta.90) (2018-08-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.89"></a>

# [2.0.0-beta.89](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.88...gatsby@2.0.0-beta.89) (2018-08-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.88"></a>

# [2.0.0-beta.88](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.87...gatsby@2.0.0-beta.88) (2018-08-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.87"></a>

# [2.0.0-beta.87](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.86...gatsby@2.0.0-beta.87) (2018-08-08)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.86"></a>

# [2.0.0-beta.86](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.85...gatsby@2.0.0-beta.86) (2018-08-08)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.85"></a>

# [2.0.0-beta.85](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.84...gatsby@2.0.0-beta.85) (2018-08-08)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.84"></a>

# [2.0.0-beta.84](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.83...gatsby@2.0.0-beta.84) (2018-08-08)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.83"></a>

# [2.0.0-beta.83](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.81...gatsby@2.0.0-beta.83) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.81"></a>

# [2.0.0-beta.81](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.79...gatsby@2.0.0-beta.81) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.80"></a>

# [2.0.0-beta.80](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.79...gatsby@2.0.0-beta.80) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.79"></a>

# [2.0.0-beta.79](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.77...gatsby@2.0.0-beta.79) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.77"></a>

# [2.0.0-beta.77](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.76...gatsby@2.0.0-beta.77) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.76"></a>

# [2.0.0-beta.76](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.75...gatsby@2.0.0-beta.76) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.75"></a>

# [2.0.0-beta.75](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.74...gatsby@2.0.0-beta.75) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.74"></a>

# [2.0.0-beta.74](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.73...gatsby@2.0.0-beta.74) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.73"></a>

# [2.0.0-beta.73](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.71...gatsby@2.0.0-beta.73) (2018-08-07)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.72"></a>

# [2.0.0-beta.72](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.71...gatsby@2.0.0-beta.72) (2018-08-06)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.71"></a>

# [2.0.0-beta.71](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.70...gatsby@2.0.0-beta.71) (2018-08-06)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.70"></a>

# [2.0.0-beta.70](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.69...gatsby@2.0.0-beta.70) (2018-08-06)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.69"></a>

# [2.0.0-beta.69](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.68...gatsby@2.0.0-beta.69) (2018-08-04)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.68"></a>

# [2.0.0-beta.68](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.67...gatsby@2.0.0-beta.68) (2018-08-04)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.67"></a>

# [2.0.0-beta.67](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.66...gatsby@2.0.0-beta.67) (2018-08-03)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.66"></a>

# [2.0.0-beta.66](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.65...gatsby@2.0.0-beta.66) (2018-08-02)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.65"></a>

# [2.0.0-beta.65](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.64...gatsby@2.0.0-beta.65) (2018-08-01)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.64"></a>

# [2.0.0-beta.64](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.63...gatsby@2.0.0-beta.64) (2018-07-31)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.63"></a>

# [2.0.0-beta.63](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.62...gatsby@2.0.0-beta.63) (2018-07-31)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.62"></a>

# [2.0.0-beta.62](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.61...gatsby@2.0.0-beta.62) (2018-07-31)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.61"></a>

# [2.0.0-beta.61](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.60...gatsby@2.0.0-beta.61) (2018-07-28)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.60"></a>

# [2.0.0-beta.60](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.59...gatsby@2.0.0-beta.60) (2018-07-27)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.59"></a>

# [2.0.0-beta.59](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.58...gatsby@2.0.0-beta.59) (2018-07-25)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.58"></a>

# [2.0.0-beta.58](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.57...gatsby@2.0.0-beta.58) (2018-07-25)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.57"></a>

# [2.0.0-beta.57](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.56...gatsby@2.0.0-beta.57) (2018-07-24)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.56"></a>

# [2.0.0-beta.56](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.55...gatsby@2.0.0-beta.56) (2018-07-24)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.55"></a>

# [2.0.0-beta.55](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.54...gatsby@2.0.0-beta.55) (2018-07-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.54"></a>

# [2.0.0-beta.54](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.53...gatsby@2.0.0-beta.54) (2018-07-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.53"></a>

# [2.0.0-beta.53](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.52...gatsby@2.0.0-beta.53) (2018-07-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.52"></a>

# [2.0.0-beta.52](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.51...gatsby@2.0.0-beta.52) (2018-07-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.51"></a>

# [2.0.0-beta.51](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.50...gatsby@2.0.0-beta.51) (2018-07-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.50"></a>

# [2.0.0-beta.50](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.49...gatsby@2.0.0-beta.50) (2018-07-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.49"></a>

# [2.0.0-beta.49](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.48...gatsby@2.0.0-beta.49) (2018-07-20)

### Bug Fixes

- Bumping Serve Up to 9.2.0 Broke Calls to Serve's API ([#6598](https://github.com/gatsbyjs/gatsby/issues/6598)) ([ce9c3a8](https://github.com/gatsbyjs/gatsby/commit/ce9c3a8))

<a name="2.0.0-beta.48"></a>

# [2.0.0-beta.48](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.47...gatsby@2.0.0-beta.48) (2018-07-19)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.47"></a>

# [2.0.0-beta.47](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.46...gatsby@2.0.0-beta.47) (2018-07-18)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.46"></a>

# [2.0.0-beta.46](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.45...gatsby@2.0.0-beta.46) (2018-07-18)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.45"></a>

# [2.0.0-beta.45](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.44...gatsby@2.0.0-beta.45) (2018-07-18)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.44"></a>

# [2.0.0-beta.44](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.43...gatsby@2.0.0-beta.44) (2018-07-18)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.43"></a>

# [2.0.0-beta.43](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.42...gatsby@2.0.0-beta.43) (2018-07-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.42"></a>

# [2.0.0-beta.42](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.41...gatsby@2.0.0-beta.42) (2018-07-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.41"></a>

# [2.0.0-beta.41](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.40...gatsby@2.0.0-beta.41) (2018-07-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.40"></a>

# [2.0.0-beta.40](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.39...gatsby@2.0.0-beta.40) (2018-07-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.39"></a>

# [2.0.0-beta.39](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.38...gatsby@2.0.0-beta.39) (2018-07-16)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.38"></a>

# [2.0.0-beta.38](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.37...gatsby@2.0.0-beta.38) (2018-07-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.37"></a>

# [2.0.0-beta.37](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.36...gatsby@2.0.0-beta.37) (2018-07-15)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.36"></a>

# [2.0.0-beta.36](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.35...gatsby@2.0.0-beta.36) (2018-07-14)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.35"></a>

# [2.0.0-beta.35](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.34...gatsby@2.0.0-beta.35) (2018-07-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.34"></a>

# [2.0.0-beta.34](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.33...gatsby@2.0.0-beta.34) (2018-07-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.33"></a>

# [2.0.0-beta.33](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.32...gatsby@2.0.0-beta.33) (2018-07-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.32"></a>

# [2.0.0-beta.32](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.31...gatsby@2.0.0-beta.32) (2018-07-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.31"></a>

# [2.0.0-beta.31](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.30...gatsby@2.0.0-beta.31) (2018-07-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.30"></a>

# [2.0.0-beta.30](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.29...gatsby@2.0.0-beta.30) (2018-07-13)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.29"></a>

# [2.0.0-beta.29](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.28...gatsby@2.0.0-beta.29) (2018-07-12)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.28"></a>

# [2.0.0-beta.28](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.27...gatsby@2.0.0-beta.28) (2018-07-12)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.27"></a>

# [2.0.0-beta.27](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.26...gatsby@2.0.0-beta.27) (2018-07-12)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.26"></a>

# [2.0.0-beta.26](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.25...gatsby@2.0.0-beta.26) (2018-07-12)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.25"></a>

# [2.0.0-beta.25](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.24...gatsby@2.0.0-beta.25) (2018-07-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.24"></a>

# [2.0.0-beta.24](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.23...gatsby@2.0.0-beta.24) (2018-07-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.23"></a>

# [2.0.0-beta.23](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.22...gatsby@2.0.0-beta.23) (2018-07-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.22"></a>

# [2.0.0-beta.22](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.21...gatsby@2.0.0-beta.22) (2018-07-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.21"></a>

# [2.0.0-beta.21](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.20...gatsby@2.0.0-beta.21) (2018-07-11)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.20"></a>

# [2.0.0-beta.20](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.19...gatsby@2.0.0-beta.20) (2018-07-09)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.19"></a>

# [2.0.0-beta.19](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.18...gatsby@2.0.0-beta.19) (2018-07-06)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.18"></a>

# [2.0.0-beta.18](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.17...gatsby@2.0.0-beta.18) (2018-07-06)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.17"></a>

# [2.0.0-beta.17](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.16...gatsby@2.0.0-beta.17) (2018-07-03)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.16"></a>

# [2.0.0-beta.16](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.15...gatsby@2.0.0-beta.16) (2018-07-03)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.15"></a>

# [2.0.0-beta.15](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.14...gatsby@2.0.0-beta.15) (2018-07-02)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.14"></a>

# [2.0.0-beta.14](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.13...gatsby@2.0.0-beta.14) (2018-07-02)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.13"></a>

# [2.0.0-beta.13](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.12...gatsby@2.0.0-beta.13) (2018-06-29)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.12"></a>

# [2.0.0-beta.12](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.11...gatsby@2.0.0-beta.12) (2018-06-26)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.11"></a>

# [2.0.0-beta.11](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.10...gatsby@2.0.0-beta.11) (2018-06-25)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.10"></a>

# [2.0.0-beta.10](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.9...gatsby@2.0.0-beta.10) (2018-06-25)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.9"></a>

# [2.0.0-beta.9](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.8...gatsby@2.0.0-beta.9) (2018-06-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.8"></a>

# [2.0.0-beta.8](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.7...gatsby@2.0.0-beta.8) (2018-06-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.7"></a>

# [2.0.0-beta.7](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.6...gatsby@2.0.0-beta.7) (2018-06-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.6"></a>

# [2.0.0-beta.6](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.5...gatsby@2.0.0-beta.6) (2018-06-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.5"></a>

# [2.0.0-beta.5](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.4...gatsby@2.0.0-beta.5) (2018-06-21)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.4"></a>

# [2.0.0-beta.4](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.3...gatsby@2.0.0-beta.4) (2018-06-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.3"></a>

# [2.0.0-beta.3](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.2...gatsby@2.0.0-beta.3) (2018-06-20)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.2"></a>

# [2.0.0-beta.2](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.1...gatsby@2.0.0-beta.2) (2018-06-19)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.1"></a>

# [2.0.0-beta.1](https://github.com/gatsbyjs/gatsby/compare/gatsby@2.0.0-beta.0...gatsby@2.0.0-beta.1) (2018-06-17)

**Note:** Version bump only for package gatsby

<a name="2.0.0-beta.0"></a>

# [2.0.0-beta.0](https://github.com/gatsbyjs/gatsby/compare/gatsby@1.9.272...gatsby@2.0.0-beta.0) (2018-06-17)

**Note:** Version bump only for package gatsby

## [1.5.0] - 2017-07-27

### Added

- Add gatsby-source-mongodb plugin to gatsby (#1570) @jorishermans
- [www] Refactor Homepage and Navigation & convert diagram to html/css (#1605)
  @fk
- Included example with WP-API-MENUS items (#1619) @sebastienfi
- added new site to showcase (#1616) @dvzrd
- Docs: add grommet starter (#1626) @alampros
- add a bunch of tests for various plugins (#1581) @DSchau

### Fixed

- fix broken gatsby link definition for TypeScript 2.4.2 (#1628) @DominikGuzei
- test: fix failing test due to missing argyle image (#1636) @DSchau
- Revise part one of tutorial to use hello-world starter (#1630) @KyleAMathews
- Fix passing createNode as argument (#1629) @sebastienfi
- Don't mutate page context (#1537) @okcoker
- Updated instructions for Windows (#1621) @sebastienfi
- Tweak JSS links + add it to plugins page (#1615) @KyleAMathews

## [1.4.0] - 2017-07-25

### Added

- Add gatsby-plugin-feed to www #1569 @nicholaswyoung
- Implement gatsby-plugin-jss #1431 @wizardzloy
- gatsby-transformer-sharp: Added the option to use the original image #1556
  @chiedo

### Fixed

- [www] Blog post meta styles #1561 @fk
- Fix unsupported method in IE #1573 @variadicintegrity
- Don't set a default title in html.js as not overridden by react-helmet #1578
  @KyleAMathews
- Downgrade Glamor to v2 as v3 unstable #1580 @KyleAMathews
- Remove the slash between the pathPrefix and pathname when navigating #1574
  @DaleWebb
- Fix url in Contentful example #1596 @axe312ger
- Small fixes to tutorial #1586 @benmathews
- Add missing dep to gatsby-source-filesystem #1607 @jquense
- WordPress -> WordPress #1608 @Alaev
- Fix typo #1609 @fk
- Update modifyWebpackConfig docs #1613 @KyleAMathews
- Fix broken links #1614 @KyleAMathews

## [1.3.0] - 2017-07-19

### Added

- docs: add "creating a static blog with gatsby" blog post #1560 @DSchau
- add tests to gatsby-remark-images #1559 @DSchau
- add glitch-gatsby-starter-blog #1554 @100ideas
- use consistent chunk ids #1534 @stevensurgnier
- Enhance API for multiple feeds #1548 @nicholaswyoung
- Add new plugin to handle csv files #1496 @ssonal
- Adds showcase segment for starters/websites built with Gatsby. #1535 @Vagr9K
- Fancy JavaScript Example #1492 @jbolda
- Add sitemap plugin to www #1541 @nicholaswyoung

### Fixed

- Clone context to prevent mutations #1553 @kyleamathews
- Update dependencies to avoid hoisting errors #1552 @kyleamathews
- Set pathPrefix if not defined to an empty string to avoid undefined #1551
  @kyleamathews
- Fix prefixes in gatsby-link + navigateTo #1550 @kyleamathews
- Make path to packages the same on website as GitHub #1549 @kyleamathews
- Fixing sw.js 404-ing because of pathPrefix not being prefixed to sw.js
  properly. Fixing #1539 #1540 @gregsqueeb
- [gatsby-plugin-sharp] Fix PNG generation when using the "duotone" option #1506
  @fk
- fix: ensure pathPrefix is added to responsive images #1510 @DSchau
- Fix the onClick override logic #1489 @jakedeichert
- Check if node.value is set as otherwise cheerio throws an error #1543
  @kyleamathews
- Fix docs referencing outdated React Router <Link> API #1523 @ahfarmer
- Fixes component-renderer to allow for use of internal routing #1542 @scottyeck
- Center .twitter-tweet-rendered #1529 @fk
- double '... use use ...' word #1528 @GoreStarry

## [1.2.0] - 2017-07-13

### Added

- Watch for changes to html.js #1473 @felixjung
- Add stylus example #1479 @iansinnott
- Added support for nested img tags in html nodes #1485 @chiedo
- Prism plugin bugfix alt #1491 @bvaughn
- Allow for env files #1462 @okcoker
- Create deploy-gatsby.md #1480 @couturecraigj

### Fixed

- Fix Contentful example URL #1483 @oscar-b
- Fix reference to program.directory #1490 @jakedeichert
- Fixes docs referencing removed "1.0" branch source code instead of master.
  #1495 @Vagr9K
- fix(gatsby-source-contentful): missing host param in createClient #1487
  @Smiter
- use program directory over cwd #1478 @craig-mulligan

## [1.1.0] - 2017-07-11

### Added

- Add gatsby-plugin-twitter for embedding Tweets #1389 @KyleAMathews
- Document promise/callback interface for async plugins #1409 @KyleAMathews
- Add an example of a config query to migration docs #1429 @benmccormick
- Adds more information to documentation pages. #1428 @Vagr9K
- Add new plugin `gatsby-plugin-emotion` #1447 @rawrmonstar
- Gatsby remark images default alt tags and optional linking #1451 @chiedo
- Add stylus support #1437 @iansinnott
- [gatsby-source-contentful] Add Support for preview api #1464 @Khaledgarbaya

### Fixed

- Update init-starter.js #1393 @kimown
- fix URL for packages, using the master branch #1399 @bmackinney
- Use latest instead of next for versions in examples #1404 @KyleAMathews
- Update www dependencies #1402 @KyleAMathews
- Fix frontpage copy issues #1401 @KyleAMathews
- Add missing return statement #1405 @ahmedlhanafy
- Fixed documentation #1406 @chiedo
- fix: Update examples directory URL due to 404 with current link #1410
  @bencodezen
- Add link to gatsby-dev-cli + we're stable + copy editing @KyleAMathews
- fix glamor + babel modification #1416 @jaredly
- Typo, grammar and standardising flags #1426 @IrregularShed
- Fix bug where the target is incorrectly set #1427 @samzhao
- Fix "gastsby" to "gatsby" on line 34 #1433 @trautlein
- Fix "Creating Pages" example's variable reference #1430 @benmccormick
- Fixes the example for navigateTo. #1440 @Vagr9K
- Properly load options for Remark #1441 @benmccormick
- Use lowercase require for "rss" #1444 @nicholaswyoung
- fix issue with ssr for redux example #1445 lemuelbarango
- Update .nvmrc, Node 8 #1446 @nicholaswyoung
- Set a key on pages so when switching between pages, the same component
  instance isn't reusued #1460 @KyleAMathews
- Removed `owner` assignation to prevent error #1454 @sebastienfi
- Update gatsby-node.js #1452 @sebastienfi
- Update README.md #1453 @sebastienfi
- Improve TypeScript example #1466 @fabien0102
- Remove react-helmet from src/html.js fixes #1443 #1474 @KyleAMathews
- Updates add-custom-webpack-config.md to fix broken links #1420 @marcustisater
- Fix source-wordpress npmignore #1476 @KyleAMathews

## [1.0.0] - 2017-07-06

### Added

- Adds Material Blog starter to the list of starters. #1344 @Vagr9K committed
  with KyleAMathews 4 days ago
- Continuation: WIP update home page with new design #1355 @fk
- WordPress source plugin and example site #1321 @sebastienfi
- [v1.0] Documentation improvements. #1370 @Vagr9K
- 1.0.0 announcement blog post #1379 @KyleAMathews
- Adds gatsby-transformer-toml to the core. ##1382 @Vagr9K

### Fixed

- Update README to make it clearer about deploying to gh pages #1343 @jsfeb26
- Call next() after serving HTML #1349 @levibuzolic
- Use int for defaultValue of int field #1352 @KyleAMathews
- Make default sitemap meet expectations #1351 @chiedo
- Guard against calling ga function if it doesn't (yet) exist #1361
  @KyleAMathews
- Namespace type names for Contentful #1374 @KyleAMathews
- Add missing parens in code examples #1376 @okcoker
- Fix gatsby-transformer-react-docgen dependencies #1377 @jquense

## [1.0.0-beta.6] - 2017-07-01

### Added

- Use the sync endpoint to pull data from Contentful #1241 @Khaledgarbaya
- Use localized space #1266 @Khaledgarbaya
- gatsby-transformer-javascript-static-exports #1253 @jbolda
- Added support for HTML img tags #1285 @chiedo
- [gatsby-source-contentful] support creating localized nodes #1279
  @kyleamathews
- Link pages to their plugin creators for easier understanding/debugging fixes
  #1281 #1297 @kyleamathews
- Support NavLink in gatsby-link #1302 @abi
- Add an example for using the sass plugin #1312 @danielfarrell
- Add CSS Modules example site #1314 @kyleamathews
- Add TypeScript example #1319 @kyleamathews
- Support using browserslist for setting per-site browser targeting for JS/CSS
  transformations #1336 @kyleamathews
- Add gatsby-plugin-canonical-url #1337 @kyleamathews
- [source-contentful] Allow for querying gifs & when user queries for image
  height, actually crop #1339 @kyleamathews

### Changed

- Replace build-images with just images @kyleamathews
- Make mediaType optional #1299 @kyleamathews
- Just use name/value for createNodeField #1325 @kyleamathews
- Renamed remark-responsive-image-plugin to gatsby-remark-images @chiedo
- Write images processed by sharp to public/static along with other assets #1332
  @kyleamathews

### Fixed

- using-remark fixes #1250 @fk
- Broken example commands in DOCS / Getting Started page #1252 @sebastienfi
- Don't catch links to files #1260 @kyleamathews
- Improve develop-html stage #1254 @craig-mulligan
- Make various tweaks to the tutorial #1262 @kyleamathews
- Add tests for parsing regex args + fix bug #1267 @kyleamathews
- Fixes for feed plugin README #1273 @kyleamathews
- [gatsby-source-contentful] Add testing for existing API processing #1274
  @kyleamathews
- Throw error and quit if there's a JS parse error for gatsby-config.js #1296
  @kyleamathews
- Add missing npmignore files #1298 @kyleamathews
- Move creating 404.html page into plugin so can enforce pages only created by
  plugins #1300 @kyleamathews
- Fix occasionally out-of-order query watching which would throw errors #1301
  @kyleamathews
- Waiting for query extraction wasn't actually waiting #1303 @kyleamathews
- Improved plugin error without exit #1309 @0x80
- Fixed a small typo in gatsby-plugin-postcss-sass that prevented CSS modules
  from working #1307 @levibuzolic
- Don't use the sass loader on build-javascript #1278 @danielfarrell
- Fixes 1317 Google Analytics plugin; updates attachHistory listener logic #1318
  @camsjams
- Call onRouteUpdate on initial page load #1320 @kyleamathews
- Fix check if there's a sw plugin added #1323 @kyleamathews
- Only build 1 html page in development and always serve it #1324 @kyleamathews
- Fix server/client rendering mismatch #1326 @kyleamathews
- update gatsby-remark-responsive-iframe readme #1328 @eddywashere
- Use memory lowdb as it is significantly faster. Also snuck in yurnalist for
  better console output #1329 @kyleamathews
- Quit on ctrl-c #1334 @kyleamathews
- Set keys on head/body components #1335 @kyleamathews

## [1.0.0-beta.4] - 2017-06-23

### Added

- Add using-remark example site #1230 @fk
- Add friendly webpack output #1240 @craig-mulligan
- Add documentation on how to use custom webpack-config #1242 @bananenmannfrau
- Add graphql fields for creating responsive images using Contentful image API
  #1228 @kyleamathews

### Changed

- Refactor Contentful data processing into own module + use more standard
  GraphQL type names @kyleamathews
- Prefer floats over integers when inferring a GraphQL field #1229 @kyleamathews

### Fixed

- Fix babel compilation so targets uglify #1244 @kyleamathews
- Open external image link with rel='noopener' #1227 @wangsongiam
- Update index.d.ts for gatsby-link #1232 @timsuchanek

## [1.0.0-beta.3] - 2017-06-21

### Added

- Show better errors when there's a graphql compilation problem #1222
  @kyleamathews
- Add google tagmanager plugin #1123 @0x80
- Support path prefixes for service workers @kyleamathews
- When a new service worker is loaded, force reload #1217 @kyleamathews
- www: Make the header fixed for tablets and up #1215 @fk
- Update on Gatsby Windows instructions #1216 @sebastienfi
- Improve GQL query error handling #1214 @0x80
- An array of linked nodes linking to heterogeneous node types is now converted
  to a union type #1211 @kyleamathews

### Fixed

- Final fixes to highlight code line whitespace, doc #1207 @fk
- Increase contentful fetch limit to max of 1000 #1209 @kyleamathews
- Fix broken links on website #1205 @kyleamathews
- Merge sidebar components #1191 @fk
- absolute resolves for gatsby config files #1195 @craig-mulligan
- Update the default sitemap query #1204 @nicholaswyoung
- For Contentful, filter out unresolvable entries and create markdown text nodes
  #1202 @kyleamathews
- Reduce font-size of the mobile menu labels #1201 @fk
- gatsby-remark-responsive-image: fix misaligned images #1196 @rstacruz
- Fix 100% width code highlight background only being drawn for the vis… #1192
  @fk

## [1.0.0-beta.2] - 2017-06-16

### Added

- Add beta 1 blog post #1183 @kyleamathews

### Fixed

- Fix prism line highlighting #1187 @kyleamathews
- Add .npmignore to source-drupal plugin so it'll publish @kyleamathews
- Fix building thumbnails when an image is processed multiple times #1185
  @kyleamathews
- Add event when all plugins are finished running so know when to start running
  queries #1182 @kyleamathews | Fix a typo on gatby-link updating #1181
  @danielfarrell

## [1.0.0-beta.1] - 2017-06-15

Our first beta!!! 🎉

### Added

- Allow for gatsby-remark-smartypants options #1166 @mitchejj
- New design (for gatsbyjs.org) + new home page #1170 @kyleamathews
- Add ability to locally define plugins #1126 @0x80
- Add rough draft for docs for creating source plugins #1159 @kyleamathews
- Optimizations around prefetching page resources #1133 @kyleamathews
- Redux example site #1081 @scottyeck
- Sitemap Generator Plugin #1115 @nicholaswyoung
- Add documentation to gatsby-remark-prism @kyleamathews

### Changed

- Move all filter operators for connections under a top-level "filter" field
  #1177 @kyleamathews
- Change `linkPrefix` to `pathPrefix` and add an example site #1155
  @kyleamathews
- Make the plugin options for remark plugins the second argument (like
  everywhere else) #1167 @kyleamathews
- Start using next instead of canary in example sites for package versions
  @kyleamathews

### Fixed

- Fix graphql compiler on TypeScript #949 @fabien0102
- Replace react.createClass with ES6 classes in examples html.js, add PropTypes
  #1169 @abachuk
- Fix windows build issue #1158 @kyleamathews
- Use custom delimiter when flattening example values for enum fields so easy to
  convert back @kyleamathews
- gatsby-remark-responsive-images: use span instead of div #1151 @rstacruz
- Add check that we can actually find a linked image file node @kyleamathews
- Ignore SVGs in gatsby-remark-responsive-image #1157 @fk
- Replace using levelup for caching with lowdb to avoid native dependency #1142
  @kyleamathews
- Fix Appveyor bug regarding build all examples on release #1118 @jbolda

## [1.0.0-alpha20] - 2017-06-05

### Added

- RSS Feed plugin #1073 @nicholaswyoung
- Contentful source plugin #1084 @mericsson
- MVP part 1 of new community Gatsby tutorial #1107 @kyleamathews
- Debuggin help when building HTML fails #1109 @kyleamathews
- Default `html.js` component #1107 @kyleamathews
- Can now highlight specific line numbers in markdown code blocks #1107
  @kyleamathews

## Changed

- `gatsby-config.js` is no longer required #1107 @kyleamathews
- The Gatsby `serve-build` command is now just `serve` #1107 @kyleamathews

## Fixed

- Windows builds on Appveyor #1049 @jbolda

## [1.0.0-alpha19] - 2017-06-02

(Skipping over the previous two releases as they had bugs).

### Added

- Add a helpful 404 page during development that lists the page you might have
  wanted @kyleamathews to link to or how to create a new page at that link #1051
  @kyleamathews
- Add "Plop" script for quickly creating new packages #1059 @kyleamathews
- Add new plugin supporting server rendering of Styled Components #1060 @gutenye
- Add new plugin supporting server rendering of react-helmet #1085 @kyleamathews
- Add new plugin for extracting JSDocs information from JavaScript files using
  documentation.js #1053 @kyleamathews
- Add new API spec (rough draft) @kyleamathews
  https://www.gatsbyjs.org/docs/api-specification/
- Add new API reference pages @kyleamathews e.g.
  https://www.gatsbyjs.org/docs/node-apis/
- Add "duotone" image processing option to gatsby-plugin-sharp #1047 @fk
- Add example site for image processing @fk
  https://image-processing.gatsbyjs.org/
- Add example site for css-in-js library Glamor @kyleamathews
  https://using-glamor.gatsbyjs.org/
- Add example site for css-in-js library Styled Components @kyleamathews
  https://using-styled-components.gatsbyjs.org/

### Changed

#### Grand big API renaming based on our new API spec https://www.gatsbyjs.org/docs/api-specification/

API changes:

[Action creators](https://www.gatsbyjs.org/docs/bound-action-creators/):

- `upsertPage` is now `createPage`
- `addFieldToNode` is now `createNodeField`
- `deletePageByPath` is now `deletePage`
- `addNodeToParent` is now `createParentChildLink`

[gatsby-browser.js APIs](https://www.gatsbyjs.org/docs/browser-apis/):

- `clientEntry` is now `onClientEntry`

[gatsby-node.js APIs](https://www.gatsbyjs.org/docs/node-apis/):

- `onNodeCreate` is now `onCreateNode`
- `onUpsertPage` is now `onCreatePage`
- `extendNodeType` is now `setFieldsOnGraphQLNodeType`

[gatsby-ssr.js APIs](https://www.gatsbyjs.org/docs/ssr-apis/):

- `modifyHeadComponents` and `modifyPostBodyComponents` were removed in favor of
  a new API
  [`onRenderBody`](https://www.gatsbyjs.org/docs/ssr-apis/#onRenderBody).
- `replaceServerBodyRender` is now `replaceRenderer`

### Fixed

- Fix sharp image quality and force file format #1054 @0x80
- Expose crop focus parameter and make consistent with base64 #1055 @0x80
- Clean up TravisCI config #1066 @hawkrives
- Fix inference bug #1087 @jquense
- Provide default context for GraphQL #1052 @kyleamathews
- Make determining when a given stage is finished much more reliable #1080
  @kyleamathews
- Pick values off plugin's package.json to avoid weird metadata from NPM #1090
  @kyleamathews

### New 1.0 sites launched

- https://www.vauxlab.com
- https://meetfabric.com

## [1.0.0-alpha16] - 2017-05-26

### Added

- Migration guide @kyleamathews #1032
- Made nodes fully immutable @kyleamathews #1035
- Add no-plugins example @scottyeck #1028
- Add support for "internal" plugins #1010
- Expose internal Gatsby data through GraphQL @kyleamathews #1014

### Changed

- Removed `updateNode` action creator as part of making nodes immutable in
  #1035. Now sites/plugins should use `addFieldToNode` for adding fields to
  nodes created by other plugins and `addNodeToParent` for adding a new node as
  a child to an existing node.

### Fixed

- Don't override the default onClick handler in gatsby-link @scottyeck #1019

## [1.0.0-alpha15] - 2017-05-15

### Added

- Update version of React Router to v4 #940
- API proxy for use during development #957
- "static" directory for files to be copied directly into the "public" directory
  #956
- Add `toFormat` argument to the ImageSharp GraphQL type so can change format of
  image e.g. from `png` to `jpg`.
- React Docgen transformer plugin for parsing propType info from React
  components #928

### Changed

- Change node format to hide most node-specific fields under an "internal" key.
  Any code referencing `node.type` and others will need changed to
  `node.internal.type` #960
- Changed the id for the root `<div>` used by Gatsby to mount React to
  `___gatsby`
- The default layout component should be at `layouts/index.js` not
  `layouts/default.js`
  https://github.com/gatsbyjs/gatsby/pull/940#issuecomment-300537162
- `this.props.children` in layout components is now a function
  https://github.com/gatsbyjs/gatsby/pull/940#issuecomment-300878300
- Change the default port for serve-build to 9000
- Change the path to GraphiQL to `/___graphql`

### Chore

- Upgrade Jest to v20 #935

## [1.0.0-alpha14] - 2017-05-05

### Added

- Use the Relay Modern compiler for extracting GraphQL queries from components.
  This allows us to now support components being added to _all_ components. This
  means you can now write queries next to the views that use them. #912
- Hook for modifying pages #863
- New Drupal source plugin and example site #890
- Detect if a site's plugins have changed and when they do, delete the site
  cache as it might now be invalid #927
- New way to make connections between nodes e.g. article --> author #902

### Changed

- Combine transformer and typegen plugins. The distinction between the two types
  of plugins has proved somewhat artificial so they were combined. Any typegen
  plugins in your `package.json` and `gatsby-config.js` need to be removed. #918
- Gatsby now garbage collects old nodes. Source plugins should now "touch"
- nodes that haven't changed #861
- Due to adopting the Relay compiler, GraphQL query template strings need named
  "graphql" plus must be named. So if previously you wrote:

```js
export const pageQuery = `
{
  allMarkdownMark {
    edges {
      node {
        id
      }
    }
  }
}
`
```

You must now write:

```js
export const pageQuery = graphql`
  query IndexQuery {
    allMarkdownMark {
      edges {
        node {
          id
        }
      }
    }
  }
`
```

## [1.0.0-alpha10] - 2016-11-17

### Added

- Did the intitial build of the new gatsbyjs.org! It's in the `www` subdirectory
  on the 1.0 branch and is built on each push! That's my kind of integration
  testing :-) You can see the early version of the site at
  https://gatsbyjs.netlify.app/. PRs welcome!
- Added <link preload> for page scripts. This speeds up loading scripts slightly
  by telling the browser to start downloading the scripts when the HTML first
  starts being parsed instead of when the browser reaches the end. This is
  especially helpful for large HTML documents on slow mobile networks.
  [PR](https://github.com/gatsbyjs/gatsby/pull/558)

## Changed

- Use namedmodulesplugin instead of recordsPath for ensuring deterministic
  builds and long-term cachability. The
  [previous PR adding support for recordsPath](https://github.com/gatsbyjs/gatsby/pull/533)
  proved unpleasant as you had to build locally and commit the outputted
  records.json which was confusing and annoying.
  [PR](https://github.com/gatsbyjs/gatsby/pull/559)

## [1.0.0-alpha9] - 2016-11-04

### Added

- Put the routes module on `window` to support experimental idea. See this issue
  for more](https://github.com/gatsbyjs/gatsby/issues/537).
  [commit](https://github.com/gatsbyjs/gatsby/commit/28e84f3aed480d1f5a8f9859172d1c6f531696d4)

### Changed

- Removed the package `sharp` as it's not used and is preventing Gatsby 1.0 from
  being installed on Windows.
  [commit](https://github.com/gatsbyjs/gatsby/commit/34fff74e6fb3cae88010b42f74d784382ead4031)

## [1.0.0-alpha8] - 2016-11-01

### Added

- Extension API `swOnUpdated` for when a service worker finishes updating. Use
  this to alert users of your app to reload to see the latest version.
  [commit](https://github.com/gatsbyjs/gatsby/commit/5173bdc5424e7c874b3f2abfad706cea2e38ebc3)

### Fixed

- hot reloading now fully works. Apparently you can't use function components
  for top-level routes on react-router with react-hot-loader 3.0 `¯\_( ツ )_/¯`
  [#532](https://github.com/gatsbyjs/gatsby/pull/532) and
  [commit](https://github.com/gatsbyjs/gatsby/commit/36f2c169586ea30518639d7b1493e08e05befb73)
- webpack needs the help of an obscure setting `recordsPath` to preserve module
  ids across builds. Big thanks to @NekR for pointing this out to me. Previous
  to this change, loading changed JS chunks could cause a JS error as the module
  ids the new chunk expects wouldn't match the module ids from the older chunks.
  [#533](https://github.com/gatsbyjs/gatsby/pull/533)

### Changed

- Disabled hard-source-webpack-plugin. It speeds up builds significantly but has
  been causing hard-to-debug errors while developing. We'll circle back to it
  down the road.
  [commit](https://github.com/gatsbyjs/gatsby/commit/4bc9660ac8c371d23c0295cde52002775eee5aa1)
- Restored using ChunkManifestPlugin. It was disabled while trying to debug the
  mismatched module id bug but that being fixed, we're using it again.
  [commit](https://github.com/gatsbyjs/gatsby/commit/8d16905f31b80ca56db225904d60ed78c6091ca9)
- Name modules ids in development for easier debugging. Primary benefit is you
  can see which modules are getting hot reloaded.
  [commit](https://github.com/gatsbyjs/gatsby/commit/93f6bd2c4206e71623c1a7fa007322f8dc9887be)

## [1.0.0-alpha7] - 2016-10-27

### Fixed

- Removed entries from the webpack config looking for
  `node_modules/gatsby/node_modules`. This was added to help when developing
  Gatsby using `npm link` but when Gatsby is installed regularly, it then fails
  the webpack validation as `node_modules/gatsby/node_modules` doesn't now
  exist.

## [1.0.0-alpha6] - 2016-10-27

### Added

- extension API for adding types to the GraphQL schema
  [commit](https://github.com/gatsbyjs/gatsby/commit/18b8b64ed4cbe3399fb262395c0c6e6a5a16099a)

### Fixed

- Use babel-traverse instead of using babel-plugin so that don't say done early
  when running graphql queries that have async resolvers
  [commit](https://github.com/gatsbyjs/gatsby/commit/a19677e38d1ce8ba4fb39ddff75482904f168db6)

## [1.0.0-alpha5] - 2016-10-14

### Added

- hard-source-webpack-plugin
  [commit](https://github.com/gatsbyjs/gatsby/commit/2c48e5c42887fecabc01c5f5b6f3dd8e06d3372f)
- New replacement API to wrap root component (useful for Redux, et al.)
  [commit](https://github.com/gatsbyjs/gatsby/commit/ebd57d2bd6c39b51a455b76018737e2957e146ef)
- yarn.lock
  [commit](https://github.com/gatsbyjs/gatsby/commit/5ce3321b84e912925c4705ececef6f2c817b0684)

### Changed

- Disable extracting the webpack chunk manifest until understand why this breaks
  updates when using Service Workers
  [commit](https://github.com/gatsbyjs/gatsby/commit/07ed5b010ad27b1816084b361f06fd0ae6a017ba)

## [1.0.0-alpha4] - 2016-10-07

### Added

- Add more file extensions to file/url loader config. Default to url loader
  unless it never makes sense to use data-uri e.g. favicons.
- Use api-runner-browser for calling browser extension APIs/replacements. Prep
  for plugin system.
- Add extension API `clientEntry` that let's site code and plugins to run code
  at the very start of client app.

### Changed

- Add config to uglify to ignore ie8.
- Disable building AppCache until can research if useful.
- Turn on screw_ie8 options in UglifyJS.

### Fixed

- Actually use the "sources" key from gatsby-config.js for looking for markdown
  files. This will be getting an overhaul soon.
- Don't use null-loader for css during the build-js stage as this prevents
  offline-plugin from caching files referenced in your CSS.
- Add missing publicPath for build-html step.

## [1.0.0-alpha3] - 2016-10-05

### Added

- Introduce way to programmatically add components to `<head>` + API to take
  over SSR rendering
  [a39c2a5](https://github.com/gatsbyjs/gatsby/commit/a39c2a5)
- Extract webpack manifest from commons.js so it doesn't change on every build
  improving its cachability
  [0941d33](https://github.com/gatsbyjs/gatsby/commit/0941d33)
- Always add babel-plugin-add-module-exports
  [97f083d](https://github.com/gatsbyjs/gatsby/commit/97f083d)

### Changed

- Upgraded React Hot Loader to 3.0-beta5
  [5185c3a](https://github.com/gatsbyjs/gatsby/commit/5185c3a)

### Fixed

- Ensure bundle names for components and paths are unique
  [342030d](https://github.com/gatsbyjs/gatsby/commit/342030d)
  [a1dfe19](https://github.com/gatsbyjs/gatsby/commit/a1dfe19)
- Remove old code loading config.toml
  [66f901](https://github.com/gatsbyjs/gatsby/commit/66f901)

## [1.0.0-alpha2] - 2016-09-21

### Added

- New system for specifying page layouts inspired by Jekyll.
- `<HTMLScripts />` and `<HTMLStyles />` helper components for rendering correct
  scripts and styles in your html.js,
- Validate at runtime gatsby-config.js and page objects.
- Start of new plugin system.
- New extension API: `onPostCreatePages` — called with pages after all pages are
  created. Useful for programmatically modifying pages created in plugins.

### Changed

- Removed remaining 0.x code
- Exit if can't find local install of Gatsby.
  [030f655](https://github.com/gatsbyjs/gatsby/commit/030f655075be5ad91af1dc12a05e6bd153a861df)
- Fix folder hierarchy for looking for loaders and modules #435
- Changed default `Config` GraphQL type to `Site` and added some Jekyll-inspired
  fields.

## [1.0.0-alpha1] - 2016-09-02

### Added

- Initial versions of new GraphQL data layer, PRPL pattern, programmatic routes,
  code splitting, supporting long-term caching of JS files.
