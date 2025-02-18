# CHANGELOG


## v0.2.5 (2025-02-18)

### Bug Fixes

- **ci**: Coverage.svg file location
  ([`ab6555a`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/ab6555a4b4e55123be03972607dbb09e8d8b778e))

### Continuous Integration

- **release**: Test run for release badge
  ([`0960543`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/096054325fd11a4c76f1a29520235eeabbf76cfe))

### Documentation

- Add license badge [skip ci]
  ([`0973ee1`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/0973ee16231fd1efd5e151c1dd4c977c6d742c42))

- Add release badge to readme.md
  ([`e6aef8c`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/e6aef8cf1a324fb1ed03cefb4fe06e588688b8ed))

- More detailed explanation on what configuration view returns and what default values are used
  ([`b1bdc7d`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/b1bdc7d9b4f67e7f89516ff55d4fd0476ec0c8fe))

- Update readme project description
  ([`f0cad0e`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f0cad0eb3a0804bffdd413ac90685cc1a5b50314))

- **readme**: Add project-thumbnail image
  ([`df8de28`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/df8de28cbbfbb8a1a17e7d07fea755a02edb3718))

### Refactoring

- **badges**: Move badges to .github dir
  ([`99d9d0a`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/99d9d0a14d64bd1df1a2b6025d82ae6fcaca5412))


## v0.2.4 (2025-02-17)

### Code Style

- Add whale emoji to 'with docker' running instructions
  ([`758c176`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/758c1762c97240f1ffbe7efc70e6f14a0ebe9db3))

### Continuous Integration

- Add development deployment env in gh repo
  ([`9fa0dfa`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/9fa0dfa2387ecb952a15f69b11b24cd264a7fbe7))

### Documentation

- Add buymecoffee link
  ([`315d09a`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/315d09aa60dfd5333d06ae43ccad28aa1c0addc2))

### Performance Improvements

- Serve swagger ui staticfiles
  ([`63aecc8`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/63aecc8d2ac08b1761c527594868f1341561f5e6))


## v0.2.3 (2025-02-17)

### Bug Fixes

- **ci**: Remove unnecessary check for commit message "skip deploy"
  ([`31f3758`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/31f3758cfc729cd8e77891e1631beda074700794))

### Documentation

- **views**: Add descriptions to viewset routes and actions
  ([`5b494d0`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/5b494d0548398d9c917b739cc845b3c0c38021fd))

### Refactoring

- Move results serializer to serializers.py [skip deploy]
  ([`caae95c`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/caae95c7dddd2d09c386bbb32a3affd9211bb28c))

ci: allow skipping deployment


## v0.2.2 (2025-02-17)

### Bug Fixes

- **ci**: Use different cache scopes for test and deploy builds
  ([`26b1ea0`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/26b1ea05bfb5e1cd9510cd96abe663a0166a0a63))


## v0.2.1 (2025-02-17)

### Bug Fixes

- **schema**: Response schema for fuel calculation
  ([`d526894`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/d52689476c1ccb65db3a173364e54e50f1b9d354))


## v0.2.0 (2025-02-17)

### Features

- Add api route for list/detail of calculation results
  ([`f564b76`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f564b76a1377c9245874e6aede0434cc43269f7b))

### Refactoring

- Calculate fuel endpoint into smaller modules
  ([`405e395`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/405e3951fb98380861b8b0a76127ad690119879c))

- Put serializers into their own file
  ([`f54b069`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f54b0697a86a56d9473f4f79842b435a62579c54))

### Testing

- Fuel calculations use latest configuration resource
  ([`e6bdcdd`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/e6bdcddd725b42a3a10382b6ae971c950cf96cb0))


## v0.1.2 (2025-02-17)

### Bug Fixes

- **serializers**: Fix route request body openapi schema, fix related tests
  ([`8d6d47b`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/8d6d47b5895034ab90b390e00b7f0b9293288d74))


## v0.1.1 (2025-02-16)

### Bug Fixes

- **cd**: Remove duplicated release acton
  ([`8de9414`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/8de9414f23401816a2de50b684ae515150f0a0a2))

### Chores

- Remove unused auth-token endpoint
  ([`b41b713`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/b41b7132ecc267c11f0f63e23242136d8fdd1bbb))

### Documentation

- Remove kami name [skip ci]
  ([`7bd417f`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/7bd417f84bc207a2dca6ed714d2a519c703949b3))


## v0.1.0 (2025-02-15)

### Bug Fixes

- Don't read .env.local in prod
  ([`89d47a3`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/89d47a35e0db49ef54d9d1726787e2d588a0055f))

- No need to copy from docker compose service actually
  ([`dd57959`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/dd579595e590a4320e2df374e81c4f2175ef63ac))

- **ci**: Add missing postgres variables to django service
  ([`5ed5a6b`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/5ed5a6b7222f5c85ec64dc2d274955abf1967c05))

- **ci**: Fix coverage report command again, also upload to gh artifacts
  ([`cffcf2d`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/cffcf2dc4035154f9f3c9323bfe7fae0901a42b8))

- **ci**: Forgot to add root user as ssh user spec [skip ci]
  ([`5d15dee`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/5d15dee95a85b33a5808c8815bfea3ed6e45d748))

- **ci**: Run coverage test from django service
  ([`5f8c923`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/5f8c9235fc6c039be32c7003656d88a14e9f6b3b))

- **ci**: Use non deprecated upload-artifacts gh action, also copy over files to gh runner and
  upload from there
  ([`f4a2595`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f4a2595433e11da494e95a4d898d31d22692affb))

### Chores

- Fix typos in workflow names
  ([`97b2942`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/97b2942990d53460812c33689475ddfa8f2ae078))

- Merge image names and digital ocean secrets
  ([`a77efe3`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/a77efe39369f2e46c6cba861a559ac1eb7868315))

- Remove unused info
  ([`66e7284`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/66e7284321d41a7df7839dbc903ea7c5e5a0a2df))

- Rename test.yml -> tests.yml [skip ci]
  ([`99ddff4`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/99ddff46f2d956ca0a44a691bebc118a078f78f2))

- Scaffold a cookiecutter-django project
  ([`57866b8`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/57866b8b142f6b803901639129b27f74c707ea41))

- **gitignore**: Local notes [no ci]
  ([`717d8e9`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/717d8e978f466eb00fe651e3b494858af945abd1))

### Code Style

- Format pyproject.toml [skip ci] [skip test]
  ([`decd922`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/decd922af82e5e00e4bcca05d412f4fd9b10c585))

### Continuous Integration

- Add coverage badge
  ([`84c078b`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/84c078bcbfc61f585c885604309aef5d337da072))

- Add env file base64 [skip ci]
  ([`b06403e`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/b06403e04f6ac286c6e3b173dbb8b8afd13dfc33))

- Add skip test ci hook
  ([`774440b`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/774440bda360410bbac877140bc8b609faa8843a))

- Apply migrations as /start in django service
  ([`8fa39b2`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/8fa39b2639d1777774f65c90adb9823f5cb4c721))

- Push coverage badge to main
  ([`1f98c0e`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/1f98c0ef1021318a389b1a210b78dd6866174347))

- Run deployment also w/ dispatch
  ([`f586cae`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f586cae5957d3d7445a961a3a6e59d2be408b6ac))

- Run on tests workflow file update as well
  ([`afb7c1f`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/afb7c1f5ab9e50fb29384864b8838e701ea1eafc))

- Split pre-commit and test workflows
  ([`4424197`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/44241970eccf187bac93e3b79172b54a7ec6fc1a))

- Test for coverage failure under 100
  ([`f956c48`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f956c485cb11e43d9c6e85f49792eb5b084db9fc))

- Use wildcard service name for build cache w/ gha backend
  ([`5943074`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/59430740eaee79d28770f230747018a843e3999a))

- **cd**: Add and test out continuous delivery cicd
  ([`d89be6b`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/d89be6b268a5496ef35859361da392cef855d2f7))

- **cd**: Run if tests workflow succeeds
  ([`3bc24bf`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/3bc24bf0f9d3b796d1490d33054861f2d03d0389))

- **cd**: Test run for python-semantic-release
  ([`4a9d80b`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/4a9d80b3a0914ae68c6f05e860500f2b8d7514af))

- **cd**: Update docker compose for continuous delivery w/ gh actions
  ([`d111985`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/d111985de98db1f8dba71c7781b4fd2f22a59e58))

- **release**: Add workflow with auto release after successful deployment
  ([`e086ddc`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/e086ddc33edde3abe63e41808c82557cac15e89c))

### Documentation

- Add how to dispatch release workflow and how/when it runs
  ([`83966f2`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/83966f2102706a7352439984099ce56ba6b098d2))

- Add informantion about style guide: commit msgs, release versioning
  ([`04ad938`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/04ad938a49e692680092966126182d92493d37e7))

- Add more about ssl, acme and traefik; also add some details about docker swarm's cool features
  ([`d627ad0`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/d627ad07f6432bbf2ddf32b5e9c410b491257fe9))

- Add project design spec
  ([`35524ad`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/35524adcc1857d2e30b029feba93d0a4e62ef4ed))

- Add runserver cmd
  ([`2870fad`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/2870fad099acfa069f2195b4b1981d8bc501da88))

- Ci workflows information
  ([`01a9a87`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/01a9a8760017840b04df6f8c5cbb888f849fe3c9))

- Put newline breaks for docs descriptions
  ([`540e624`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/540e624393370121c0ccec681ec22e28e8668665))

- Update ci docs, add to toc
  ([`9511567`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/95115677e59a966fc82a6d9df7b8e56065306691))

- Update docs for cont/ delivery and update readme.md
  ([`5034c80`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/5034c809001e2b887d35a9611aac215f63ce2a48))

- Update readme.md
  ([`f389036`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/f389036fe6119042f646f69b0da5cdd47075c114))

- We actually don't need run id
  ([`6c93573`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/6c93573289195d7d72e874cbae165a32206aaa09))

- **readme**: Add instructions how to run with and without docker compose setup
  ([`7759366`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/7759366eb6e3265ee7a474337c8afd1c75a00f77))

### Features

- Implement base logic with tests
  ([`64c80d1`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/64c80d10ac254502074c811ac8a35a0b8d404e0f))

### Performance Improvements

- Self serve swagger staticfiles instead of public cdn
  ([`3f31d57`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/3f31d579e4a6c23d361466e8d48c839e116eaeca))

- **ci**: Build and cache docker compose, also add docker hub to prod env files
  ([`c4612c4`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/c4612c41276580e8273e351c967f9b1de69b7ba8))

### Refactoring

- Remove unnecessary code from default cookiecutter-django project
  ([`6cfab2a`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/6cfab2afdc9570707baa5b358b3c0dc81b49e300))

### Testing

- Reduce coverage failure limit
  ([`c2498cb`](https://github.com/aidoskanapyanov/fuel-tracker-rest-api-django/commit/c2498cb946341d1ff0320836285db59ca0f19cf3))
