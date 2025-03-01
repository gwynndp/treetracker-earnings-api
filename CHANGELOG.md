## [1.7.7](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.6...v1.7.7) (2022-02-09)


### Bug Fixes

* wrong image names ([63694d2](https://github.com/Greenstand/treetracker-earnings/commit/63694d2080064b18851c6a70411e759ada504762))

## [1.7.6](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.5...v1.7.6) (2022-02-09)


### Bug Fixes

* lint ([bdb1672](https://github.com/Greenstand/treetracker-earnings/commit/bdb16726cec6e4912d95528df0aa8a0c516552aa))

## [1.7.5](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.4...v1.7.5) (2022-02-09)


### Bug Fixes

* database migration job with correct image ([cdd35ac](https://github.com/Greenstand/treetracker-earnings/commit/cdd35ac283334437a0efa304891ab71e65b170eb))

## [1.7.4](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.3...v1.7.4) (2022-02-09)

### Bug Fixes

- update deployment for database migrations ([91e7b3e](https://github.com/Greenstand/treetracker-earnings/commit/91e7b3e8ba75e24bd6c89f76b9bcb51bb11e98bf))

## [1.7.3](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.2...v1.7.3) (2022-02-09)

### Bug Fixes

- also use default node pool ([7809bd0](https://github.com/Greenstand/treetracker-earnings/commit/7809bd0fdac251d7c530f118903d2d6b683e225d))
- do not echo database connection string ([d38c2c7](https://github.com/Greenstand/treetracker-earnings/commit/d38c2c7dc2ad87236fda2966a8c602a6f4ded36d))
- update deployment for database migrations ([cdb32e8](https://github.com/Greenstand/treetracker-earnings/commit/cdb32e87f227fb2f181960a59d3ef9e40ed4ccc7))

## [1.7.2](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.1...v1.7.2) (2022-02-08)

### Bug Fixes

- update image name ([1280381](https://github.com/Greenstand/treetracker-earnings/commit/12803817120d0d000a64df368b007036c959f8ff))

## [1.7.1](https://github.com/Greenstand/treetracker-earnings/compare/v1.7.0...v1.7.1) (2022-02-08)

### Bug Fixes

- add capture count column ([c0e5c18](https://github.com/Greenstand/treetracker-earnings/commit/c0e5c184460732e60001e2391e3b8f429fa968b4))
- move expect-runtime to dependencies ([ccda0b6](https://github.com/Greenstand/treetracker-earnings/commit/ccda0b6ea6ea96e13acca482c97e5a311a4a4536))
- remove schema from migration ([7bbf926](https://github.com/Greenstand/treetracker-earnings/commit/7bbf92694e0f323d259350d07e21a184935c8766))

# [1.7.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.6.0...v1.7.0) (2022-02-08)

### Bug Fixes

- add logic to manage cors for dev env ([c56219b](https://github.com/Greenstand/treetracker-earnings/commit/c56219b3d35570e5dfe7d6e78a3fd016679217dc))
- linted ([84d0232](https://github.com/Greenstand/treetracker-earnings/commit/84d0232710b1fd4a3bdd2eb7249e0837e88c760b))
- update api request to stakeholder tool ([08b9819](https://github.com/Greenstand/treetracker-earnings/commit/08b98197030f63e8c8320955a9db82442475f1f7))

### Features

- default sort by paid_at ([d90b147](https://github.com/Greenstand/treetracker-earnings/commit/d90b14788f62c084c4aadc1af13c51b8e09ff1bc))

# [1.6.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.5.0...v1.6.0) (2022-02-08)

### Bug Fixes

- add authorization header to integration tests ([5270dda](https://github.com/Greenstand/treetracker-earnings/commit/5270dda55a3ee984c741ad24da8f988a45b5f76f))

### Features

- **earnings patch:** include payment confirmed by field in processing single payment ([da0d7a0](https://github.com/Greenstand/treetracker-earnings/commit/da0d7a0c4bf551d28c34f07d943fbbc602da46f2))

# [1.5.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.4.2...v1.5.0) (2022-02-03)

### Features

- **batch update earnings:** set payment comfirmed by field ([2c52c90](https://github.com/Greenstand/treetracker-earnings/commit/2c52c90afe4457e2b1bd3665a2243a7ddea4905d))
- **earnings model:** include id field in earnings model ([bd78348](https://github.com/Greenstand/treetracker-earnings/commit/bd78348bfa447bc9d1c31606a81282f18d0b2a3b))
- **earnings model:** return concatenated first name and last name as grower name ([180b849](https://github.com/Greenstand/treetracker-earnings/commit/180b8493ed630c43dea2f33e0d342ea8fc231c62))
- **earnings patch:** set confirmation method in processing single earning ([04e247a](https://github.com/Greenstand/treetracker-earnings/commit/04e247ab4592a9ba46addfc4f80fcaab5a6fab0c))
- **earnings:** improve grower and phone filters ([9532d4a](https://github.com/Greenstand/treetracker-earnings/commit/9532d4ad3eb484d1c910a97307520cea09d3ca40))
- **earnings:** undo including payment confirmed by in processing payments ([c64b1a5](https://github.com/Greenstand/treetracker-earnings/commit/c64b1a551138478a2ce5d0055f812b4b2c382e01))
- **migrations:** add migration to change confirmed by data type to bigint ([5c2400c](https://github.com/Greenstand/treetracker-earnings/commit/5c2400ca9db264d85692fb05a7c23995085339f6))

## [1.4.2](https://github.com/Greenstand/treetracker-earnings/compare/v1.4.1...v1.4.2) (2022-01-18)

### Bug Fixes

- include blank template fields ([3224abc](https://github.com/Greenstand/treetracker-earnings/commit/3224abc4b6251522078d59aa268af5800f4f2f28))

## [1.4.1](https://github.com/Greenstand/treetracker-earnings/compare/v1.4.0...v1.4.1) (2021-12-14)

### Bug Fixes

- update sealed secret ([c9fd173](https://github.com/Greenstand/treetracker-earnings/commit/c9fd173b27fd5103cbbd5e40d7cf9e6a30193c2c))

# [1.4.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.3.1...v1.4.0) (2021-11-23)

### Bug Fixes

- add external api call to get phone value for batch requests ([7826245](https://github.com/Greenstand/treetracker-earnings/commit/7826245a8fc8083ab92687de39adb5679da6bec9))
- add filter params to next/prev links ([66596e0](https://github.com/Greenstand/treetracker-earnings/commit/66596e04f86c5de7e98bd508fd7762ee8e0400fe))
- external api call issue ([86def0d](https://github.com/Greenstand/treetracker-earnings/commit/86def0dc3ab07fa81239d38ca9b35c911b7220d5))
- returning correct query in the links ([6420713](https://github.com/Greenstand/treetracker-earnings/commit/642071385a11fddae676c3435791090c3f763768))

### Features

- return and add sorting by grower and funder ([a0d7a24](https://github.com/Greenstand/treetracker-earnings/commit/a0d7a24bdc0c17119daed9e4daa8e9bacf1a71cd))

## [1.3.1](https://github.com/Greenstand/treetracker-earnings/compare/v1.3.0...v1.3.1) (2021-11-11)

### Bug Fixes

- rename overlay dir ([814eed0](https://github.com/Greenstand/treetracker-earnings/commit/814eed0883d5bb29ad63d62566fffdcd1e33663d))

# [1.3.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.2.0...v1.3.0) (2021-11-11)

### Bug Fixes

- lint fix ([cc8eac1](https://github.com/Greenstand/treetracker-earnings/commit/cc8eac107d3c385c9285b4a3078ee574f42ea0a7))
- remove schema creationg from migrations ([41479e6](https://github.com/Greenstand/treetracker-earnings/commit/41479e6e0ab4692d95479ea8e462e594d413e158))

### Features

- add database secrets for test and prod ([5bcd255](https://github.com/Greenstand/treetracker-earnings/commit/5bcd255f3b8b5b9b2091642b80becad0d77b744e))
- add Sierra Leone currency to enum ([513d285](https://github.com/Greenstand/treetracker-earnings/commit/513d285e8bae8aac767b7ff74c0fe828e7819f53))

# [1.2.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.10...v1.2.0) (2021-11-04)

### Bug Fixes

- add earnings schema to batch repository ([6563b9b](https://github.com/Greenstand/treetracker-earnings/commit/6563b9b99f92f37efb7369851e3a660225ff230a))
- change earnings/batch GET to use streams ([0980970](https://github.com/Greenstand/treetracker-earnings/commit/0980970be784aa9135b41a8ceb86b1aa6e283b42))
- rename column consolidation_id to consolidation_rule_id ([526c45b](https://github.com/Greenstand/treetracker-earnings/commit/526c45b036f0ede71f25f0846b8a6057d5b61a3e))

### Features

- port earning/batch PATCH to using streams ([d109d10](https://github.com/Greenstand/treetracker-earnings/commit/d109d10f7df3087a71de730a5be1d4cc425ad701))
- put add sorting support for id, amount, effective_payment_date, payment_system ([3c6536c](https://github.com/Greenstand/treetracker-earnings/commit/3c6536c547fdf3b288b27f0877fe2dba535be00f))
- return total count ([748f993](https://github.com/Greenstand/treetracker-earnings/commit/748f99366fe567a3bf2583cba3a9b4bfd3dbe24e))

## [1.1.10](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.9...v1.1.10) (2021-11-03)

### Bug Fixes

- update CORS settings ([98d8205](https://github.com/Greenstand/treetracker-earnings/commit/98d8205bc138bb0a8ab676579d32f5be6b4e57bd))

## [1.1.9](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.8...v1.1.9) (2021-11-03)

### Bug Fixes

- add authorization header to CORS ([302c4a0](https://github.com/Greenstand/treetracker-earnings/commit/302c4a00b4517106d62fb9bd20aeb0e7b5be9fe8))

## [1.1.8](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.7...v1.1.8) (2021-11-02)

### Bug Fixes

- cors ([64f5eca](https://github.com/Greenstand/treetracker-earnings/commit/64f5ecaf12eb0a132ec6beefd6d25e0d5d36e99a))

## [1.1.7](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.6...v1.1.7) (2021-10-29)

### Bug Fixes

- correct the mapping file ([de68150](https://github.com/Greenstand/treetracker-earnings/commit/de6815002fc2302897c3ba28cdd3d3248ec3f40c))

## [1.1.6](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.5...v1.1.6) (2021-10-29)

### Bug Fixes

- open up CORS for dev ([71906ab](https://github.com/Greenstand/treetracker-earnings/commit/71906abbd1753c9628d5cbe00d5e5c9665447e03))

## [1.1.5](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.4...v1.1.5) (2021-10-20)

### Bug Fixes

- do not use public schema ([8980263](https://github.com/Greenstand/treetracker-earnings/commit/8980263e7fa5afcb389b7cb695ce9f2914f89d6e))

## [1.1.4](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.3...v1.1.4) (2021-10-20)

### Bug Fixes

- correct name of secret ([b5b4a3a](https://github.com/Greenstand/treetracker-earnings/commit/b5b4a3a6c9695f8c2b8ae57916002a85040eae2a))

## [1.1.3](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.2...v1.1.3) (2021-10-20)

### Bug Fixes

- set up service name ([66c1817](https://github.com/Greenstand/treetracker-earnings/commit/66c1817e05fb859db151c109116b999e98cfb10a))

## [1.1.2](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.1...v1.1.2) (2021-10-20)

### Bug Fixes

- correct namespace ([3f185be](https://github.com/Greenstand/treetracker-earnings/commit/3f185be35cf71b24051b9a8147b3e409f9dd6bbf))

## [1.1.1](https://github.com/Greenstand/treetracker-earnings/compare/v1.1.0...v1.1.1) (2021-10-20)

### Bug Fixes

- add namespace ([e91cf93](https://github.com/Greenstand/treetracker-earnings/commit/e91cf93ebe64d4da8a282c638424981a4577759b))
- add service name ([7430fa3](https://github.com/Greenstand/treetracker-earnings/commit/7430fa3fd3d59a97e76b1200eccb697ad3e25f34))
- update database secret ([fb6025c](https://github.com/Greenstand/treetracker-earnings/commit/fb6025c716528b8a751bf1c155e5ff648a761061))

# [1.1.0](https://github.com/Greenstand/treetracker-earnings/compare/v1.0.1...v1.1.0) (2021-10-20)

### Features

- update to node 16 alpine image ([f07148b](https://github.com/Greenstand/treetracker-earnings/commit/f07148b618dd9d5d54038f36094b9242ae9ad2da))

## [1.0.1](https://github.com/Greenstand/treetracker-earnings/compare/v1.0.0...v1.0.1) (2021-10-20)

### Bug Fixes

- run npm ci without silent to debug ([f23eb61](https://github.com/Greenstand/treetracker-earnings/commit/f23eb6163a893a9589db96a4090c063df37c9da8))

# 1.0.0 (2021-10-20)

### Bug Fixes

- check husky ([0a96bc8](https://github.com/Greenstand/treetracker-earnings/commit/0a96bc8ef529e4af7b8fc334bec8acedb4298eb9))
- configure project name in package.json ([97424b9](https://github.com/Greenstand/treetracker-earnings/commit/97424b97048c3684c6633f9bc83417af4f63e0e3))
- disable test automation for now ([84bd19a](https://github.com/Greenstand/treetracker-earnings/commit/84bd19a3628cd82badf8f6a037c39beb44a648e6))
- force deployment ([c944dfe](https://github.com/Greenstand/treetracker-earnings/commit/c944dfe545fce3b176838b53b49629455e6f97f9))
- force deployment ([f747e41](https://github.com/Greenstand/treetracker-earnings/commit/f747e419d18fff81e8c83238b55e210a516b4989))
- lint:fix applied ([9e61b7c](https://github.com/Greenstand/treetracker-earnings/commit/9e61b7c6aceea415e717262bafff4ab0d106f2ad))
- resolve lint errors ([6024f90](https://github.com/Greenstand/treetracker-earnings/commit/6024f90899296055783a1b50f71a187a191142ea))
- update workflows to use node 16 ([c8c62af](https://github.com/Greenstand/treetracker-earnings/commit/c8c62afec1210b27df17ee05eca289a8d0ba950f))
- use main branch ([3b048d7](https://github.com/Greenstand/treetracker-earnings/commit/3b048d7ae69cb45b022852f3f68c24de8483cd52))

### Features

- add earnings batch endpoints ([c229c39](https://github.com/Greenstand/treetracker-earnings/commit/c229c397df44d9ae58be34329cb0351703791b19))
- earnings get and patch ([9d9a1da](https://github.com/Greenstand/treetracker-earnings/commit/9d9a1da4c38f8cbcde6fed0d638d9a4f3d081d55))
- tests added ([8215178](https://github.com/Greenstand/treetracker-earnings/commit/8215178d573df357cfebddcef434815dad14a5ea))
