Changelog
=========

0.3.0
-----

- Add forgotten import. `d1b0ab33d <https://github.com/fedora-infra/fmn.rules/commit/d1b0ab33dee0e9f6a654a6ab02543279037d5169>`_
- Start an utility method to retrieve the member of a group `get_user_of_group` `ae0e02c9c <https://github.com/fedora-infra/fmn.rules/commit/ae0e02c9c2d7b49e535a8fe8e9d3b7e82e56937f>`_
- Expand _get_pkgdb2_packagers_for to include the members of a group if the group has ACLs `d04966c17 <https://github.com/fedora-infra/fmn.rules/commit/d04966c17c8a33d95a94055365b699d0158e4351>`_
- get_user_of_group requires access to the fedmsg config `4663e3954 <https://github.com/fedora-infra/fmn.rules/commit/4663e3954885a5660959eae30efa78631f405dff>`_
- Add logic to instantiate an AccountSystem object if there isn't already one `f7ac04f40 <https://github.com/fedora-infra/fmn.rules/commit/f7ac04f40fc750cc78cca0c54f22a4256279641c>`_
- If the package has a group with some ACL, get the AccountSystem client and forward the configuration `fb75e310c <https://github.com/fedora-infra/fmn.rules/commit/fb75e310c9e091cc6b3d3435fed769f03d003492>`_
- Adjust the structure of the FAS credential per @ralphbean's advice `ccbea668e <https://github.com/fedora-infra/fmn.rules/commit/ccbea668e28ff6c9df21f881081af034d9867fe5>`_
- pep8. `89b22b5d6 <https://github.com/fedora-infra/fmn.rules/commit/89b22b5d6a189fe06169e6c7f6f31012d73b9b8d>`_
- Typofix. `7d50e5751 <https://github.com/fedora-infra/fmn.rules/commit/7d50e5751e423f6f4cc7b3601984e1d8089fd855>`_
- Apply group-ownership stuff to packages-of-user in addition to packagers-of-package. `23a469e91 <https://github.com/fedora-infra/fmn.rules/commit/23a469e91afa77a72d2187833ebcee7f5a86bf67>`_
- Merge pull request #16 from fedora-infra/feature/group_maintainer `ea438e745 <https://github.com/fedora-infra/fmn.rules/commit/ea438e7457fc8514fb2478ce5ee7d1ac1e426e4c>`_
- Add a rule that lets you filter by koji instance(s). `9b9e6b963 <https://github.com/fedora-infra/fmn.rules/commit/9b9e6b96386ed56c63778c2b05d3fd078fe3e2a2>`_
- Strip instances. `07b8cb64e <https://github.com/fedora-infra/fmn.rules/commit/07b8cb64e71f55f1fd77ecea3281ff9b58385189>`_
- Merge pull request #17 from fedora-infra/feature/koji-instances `8c77c2648 <https://github.com/fedora-infra/fmn.rules/commit/8c77c2648f603145ec8466329e5213a777d2f047>`_

0.2.5
-----

- Add a rule for matching a generic regex. `07276649c <https://github.com/fedora-infra/fmn.rules/commit/07276649c5d1479d80ead5e3ec3171b87cd53ce1>`_
- Merge pull request #15 from fedora-infra/feature/generic-regex `063d5fc46 <https://github.com/fedora-infra/fmn.rules/commit/063d5fc46327f5cb872e390b23ad8269266b3e8f>`_

0.2.4
-----

- More Copr messages: success, failed, skipped `c7004cd1f <https://github.com/fedora-infra/fmn.rules/commit/c7004cd1fb50acb94ef6f991e375fbfa7c2a6352>`_
- Merge pull request #14 from hroncok/copr_status `e3b6ebe9e <https://github.com/fedora-infra/fmn.rules/commit/e3b6ebe9e6c84539af40d37ca32ffd7b5fd20e38>`_

0.2.3
-----

- Switch back to using user-centric caching. `664a27fd8 <https://github.com/fedora-infra/fmn.rules/commit/664a27fd82f26dbcc288900096eecc9dbe60c519>`_
- Use our own cache keys for dogpile.cache. `a197a39ed <https://github.com/fedora-infra/fmn.rules/commit/a197a39ed4d8288a713a53e63d1c6271bde930a9>`_
- Add a cache invalidation function. `08afda487 <https://github.com/fedora-infra/fmn.rules/commit/08afda48728864ade9a033bef5f1008e97980adc>`_
- Typofixes. `12d7f5bd8 <https://github.com/fedora-infra/fmn.rules/commit/12d7f5bd88e9f5f39f0c76257f5ccf9a5f6a7783>`_
- Merge pull request #13 from fedora-infra/feature/whats-old-is-new-again `9e6b00e5f <https://github.com/fedora-infra/fmn.rules/commit/9e6b00e5f9615fc4a1ba78b6f99644d2cfe228ec>`_

0.2.2
-----

- Double check we retrieved  data `b2b5c27e0 <https://github.com/fedora-infra/fmn.rules/commit/b2b5c27e02a036672a48ce66dd925861ae94f93a>`_
- Typofix. `07f618ec6 <https://github.com/fedora-infra/fmn.rules/commit/07f618ec67fe4c59c757d88cba2fc20735dcc09c>`_
- Typofix Mark II. `0d4035a94 <https://github.com/fedora-infra/fmn.rules/commit/0d4035a9421d6b138f97169cc29949badd07cc42>`_
- Merge pull request #9 from fedora-infra/be_safe `f8fbf543c <https://github.com/fedora-infra/fmn.rules/commit/f8fbf543c569bc2be1a8aea4723468ed2881b7a9>`_
- Try 3 times before failing to talk to pkgdb2. `6ce5d9052 <https://github.com/fedora-infra/fmn.rules/commit/6ce5d90527945eed1a4c524db4080cea70cc8772>`_
- Link to dev instructions from the README. `96ace35fe <https://github.com/fedora-infra/fmn.rules/commit/96ace35fe5abe3908a2d872d68728ee09c14ddb6>`_
- Merge pull request #12 from fedora-infra/feature/careful-with-the-pkgdb2-plz `fb3dc02ae <https://github.com/fedora-infra/fmn.rules/commit/fb3dc02aeb527cc258da90dde37190911c4da9aa>`_

0.2.1
-----

- Add package-centric caching routines to fmn.rules.utils. `2c3901c24 <https://github.com/fedora-infra/fmn.rules/commit/2c3901c243fdbb902057ed0f52ae9b7f238afbf8>`_
- Use package-centric caching routines. `c0e0fc2c4 <https://github.com/fedora-infra/fmn.rules/commit/c0e0fc2c445288b750050bd8e95118cbfe11157e>`_
- Safety first. `ec26c9aeb <https://github.com/fedora-infra/fmn.rules/commit/ec26c9aebb9508389bbd5c934099cb8f2ea289a3>`_
- Merge pull request #10 from fedora-infra/feature/package-centric-caching `89009d55e <https://github.com/fedora-infra/fmn.rules/commit/89009d55e78cd21de83eba1995c579e50706981c>`_

0.2.0
-----

- Typofix. `30d0e1eb8 <https://github.com/fedora-infra/fmn.rules/commit/30d0e1eb84b335813a0efecf2f0faac43a131d21>`_
- Travis.yml `69f30367a <https://github.com/fedora-infra/fmn.rules/commit/69f30367ab554ba0e679961b1562c41a9b51c16c>`_
- If the pkgdb call fails, return an empty list of packages `44a746471 <https://github.com/fedora-infra/fmn.rules/commit/44a74647142869b3d8e9a9ee347f135f059c3f40>`_
- Add debugging log if the pkgdb call fails `86139c9a6 <https://github.com/fedora-infra/fmn.rules/commit/86139c9a6f00c480f90524b9161d3c2b4b5fcc1c>`_
- Generate the URL before calling it, and log it `1a20b0201 <https://github.com/fedora-infra/fmn.rules/commit/1a20b02010e973ddecebb0bc038a4fb93dfc3c88>`_
- Merge pull request #8 from fedora-infra/fix_pkgdb2 `805714bf3 <https://github.com/fedora-infra/fmn.rules/commit/805714bf3c603dfbcaf39bc53064a2534b93a912>`_
- Remove old pkgdb1 code.  :yolo: `5f5278e38 <https://github.com/fedora-infra/fmn.rules/commit/5f5278e38e36bffdddffabdedb955c2b687486aa>`_
- Use None as the sentinnel value here. `f106a4de6 <https://github.com/fedora-infra/fmn.rules/commit/f106a4de6989eb6f833ab074d77cf35593c9cbb1>`_

0.1.6
-----

- Pass the config obj along to fedmsg.meta. `aa0ad36c1 <https://github.com/fedora-infra/fmn.rules/commit/aa0ad36c1e04f052721b1e824362cb61a6233c38>`_
- Always return a set here. `70f4f589f <https://github.com/fedora-infra/fmn.rules/commit/70f4f589fe1672bf99ece68b6ae81621c8f6930a>`_
- Add a generic filter to get the message of a specific fedoraproject project `ff49c7c3f <https://github.com/fedora-infra/fmn.rules/commit/ff49c7c3f2b16945cf542feeb23642bdeea7b18f>`_
- Enable the generic fedorahosted per project filter to support multiple projects `b39e003f4 <https://github.com/fedora-infra/fmn.rules/commit/b39e003f4a76faed56297dcedb0e3eee8e869490>`_
- Update the generic filter for Fedora Hosted projects `b18b568d7 <https://github.com/fedora-infra/fmn.rules/commit/b18b568d78ecb73ae3c687e85ad2992db06a850b>`_
- Add filter to exclude notifications about one or more users `9def8f908 <https://github.com/fedora-infra/fmn.rules/commit/9def8f90822f2e36ca3206df7b223300848cffeb>`_
- Make sure there is no un-desired spaces `621be6aa0 <https://github.com/fedora-infra/fmn.rules/commit/621be6aa011ecd5996a12ecf7abfd5396a80e092>`_
- Fix the docstring to be more accurate about the function's action `f792b874e <https://github.com/fedora-infra/fmn.rules/commit/f792b874ee835ed06edaa660f13b56972412f1c0>`_
- Pep8 fix and be consistent about docstring formating `56c1ea56a <https://github.com/fedora-infra/fmn.rules/commit/56c1ea56a3675ea87e6f682f286dd56cc62a1b7c>`_
- Here we exclude message so the logic is reversed `5efd4a25f <https://github.com/fedora-infra/fmn.rules/commit/5efd4a25fba4143aced4e1f9dc8fdc1a5540029f>`_
- Handle case where project or fasnick is None `3764f5813 <https://github.com/fedora-infra/fmn.rules/commit/3764f58130cf5c4c952993190504ed6a05c1c004>`_
- Merge pull request #4 from fedora-infra/filter_hosted `249692094 <https://github.com/fedora-infra/fmn.rules/commit/2496920946cac6559a5e6ac5c937e37458a19df8>`_
- Merge pull request #5 from fedora-infra/filter_no_users `593e1bd95 <https://github.com/fedora-infra/fmn.rules/commit/593e1bd95ff059d0af689b31d3c6311897181d2d>`_
- Typofix. `a6de307b0 <https://github.com/fedora-infra/fmn.rules/commit/a6de307b038fa43cbf8199d361f1886fc072a9b9>`_
- Merge branch 'develop' of github.com:fedora-infra/fmn.rules into develop `6b6f7b83e <https://github.com/fedora-infra/fmn.rules/commit/6b6f7b83e19466ea5847881dfbc9cec97cfdf28a>`_
- Copy over pkgdb pagination fixes... `a872277f2 <https://github.com/fedora-infra/fmn.rules/commit/a872277f28145e2f0f78e0f75bc87f34478b7a50>`_
- Merge pull request #6 from fedora-infra/feature/pkgdb-pagination `5ff78cf45 <https://github.com/fedora-infra/fmn.rules/commit/5ff78cf455e9e64ca06744217c2b15b74c9b28c6>`_
- Add a rule for matching packages by regex. `38efb1366 <https://github.com/fedora-infra/fmn.rules/commit/38efb136609b645b0076c0aa1481330f9e28ee51>`_
- Merge pull request #7 from fedora-infra/feature/package-name-regex `4e2d8b327 <https://github.com/fedora-infra/fmn.rules/commit/4e2d8b3276bfec0db9968d795b51a3b668c3ee79>`_

0.1.5
-----

- Fix koji rules. `739bf99f7 <https://github.com/fedora-infra/fmn.rules/commit/739bf99f7903699360dae982a3ec079bff5afc88>`_
- Add rules for scratch builds. `36e749fe1 <https://github.com/fedora-infra/fmn.rules/commit/36e749fe1f83339893f17e00d43142e0abd700ba>`_

0.1.4
-----

- Add a rule for logger.log test messages. `c59765101 <https://github.com/fedora-infra/fmn.rules/commit/c5976510158ff8b5947fe832b7588889aac71be8>`_
- Merge pull request #1 from fedora-infra/logger.log `cfe70273b <https://github.com/fedora-infra/fmn.rules/commit/cfe70273bf11faf2f93c7fc7eda5ec0904b71957>`_
- COPR rules. `d95c5648c <https://github.com/fedora-infra/fmn.rules/commit/d95c5648c7580f1e423ea83fc3be148f39523d48>`_
- Merge branch 'develop' of github.com:fedora-infra/fmn.rules into develop `7b0a19536 <https://github.com/fedora-infra/fmn.rules/commit/7b0a195369e784f6abc6775b114c9e8cc7869641>`_
- Add fedocal rules. `0369a65ec <https://github.com/fedora-infra/fmn.rules/commit/0369a65ec48e482fccc421199d123ed643dda2a6>`_
- PEP8. `f8d0874e8 <https://github.com/fedora-infra/fmn.rules/commit/f8d0874e85d3b5ccc4fbe56a2fe890bd6d2179ce>`_
- Add forgotten fedocal rules for realsies this time. `2a1f68695 <https://github.com/fedora-infra/fmn.rules/commit/2a1f6869535950a8f033645ee2936596f32a1a4d>`_
- Adjust english. `4769df0d4 <https://github.com/fedora-infra/fmn.rules/commit/4769df0d48f35e4de1786a2d0df49ba1499a8a59>`_
- Add some debug statements. `31fe928ee <https://github.com/fedora-infra/fmn.rules/commit/31fe928eec181de67eea62a6bd7da95df63ffb2b>`_
- Pass the fedmsg config to the pkgdb query function. `a8a5f5b13 <https://github.com/fedora-infra/fmn.rules/commit/a8a5f5b1310a295b28e060b7a37f28b6287404f0>`_
- Provide option to use pkgdb1 or pkgdb2 API. `cbe70f5c1 <https://github.com/fedora-infra/fmn.rules/commit/cbe70f5c177c09f715403f6e407cb801d3e6089e>`_
- Use dogpile.cache to cache pkgdb queries. `e061b21a3 <https://github.com/fedora-infra/fmn.rules/commit/e061b21a3aea719781c1aa219776a8daa8816e14>`_

0.1.3
-----

- Add missing deps. `388893ee9 <https://github.com/fedora-infra/fmn.rules/commit/388893ee9b3e2388ccc84c2207ffedc619b9851e>`_
- Move pkgdb interface in from fmn.lib. `4cbb225ad <https://github.com/fedora-infra/fmn.rules/commit/4cbb225ad552b0b2e45c0bbf92ea9b77b4d43c59>`_
- 0.1.2 `e6a33d57d <https://github.com/fedora-infra/fmn.rules/commit/e6a33d57d96e9bade9db6b6a0d24f43f504f7642>`_

0.1.2
-----

- Ignore stuff. `aa9dc15d1 <https://github.com/fedora-infra/fmn.rules/commit/aa9dc15d11fe20a433ac5b0735267f6a95294f37>`_
- Include license files. `249006670 <https://github.com/fedora-infra/fmn.rules/commit/24900667070173f8cb2568a1dc6700973114f1c7>`_
- Include changelog. `37ff6dc8d <https://github.com/fedora-infra/fmn.rules/commit/37ff6dc8d311bae5cbe60e402bf7eb1ea35c80e3>`_

0.1.1
-----

- Update URL for pypi. `e628ef0c2 <https://github.com/fedora-infra/fmn.rules/commit/e628ef0c2623d1c3eaec9d5577bde71532f2a9a0>`_
