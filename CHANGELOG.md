# Changelog

[PyPI History][1]

[1]: https://pypi.org/project/google-cloud-iot/#history

## [2.3.0](https://www.github.com/googleapis/python-iot/compare/v2.2.1...v2.3.0) (2021-09-24)


### Bug Fixes

* add 'dict' annotation type to 'request' ([d4db051](https://www.github.com/googleapis/python-iot/commit/d4db0513a5beba7936d33f011bdf1a8ee831d425))


### Documentation

* Added python sample codes for cloud-iot-token-service generateAccessToken API ([#149](https://www.github.com/googleapis/python-iot/issues/149)) ([c2a575e](https://www.github.com/googleapis/python-iot/commit/c2a575e76b7fd2fb6da7954dcb6406933cc50bd1))

### [2.2.1](https://www.github.com/googleapis/python-iot/compare/v2.2.0...v2.2.1) (2021-07-26)

### Bug Fixes

* **deps:** pin 'google-{api,cloud}-core', 'google-auth' to allow 2.x versions ([#153](https://www.github.com/googleapis/python-iot/issues/153)) ([9050b55](https://www.github.com/googleapis/python-iot/commit/9050b55fda8871de2948feb8fb8d301a3222ec46))
* enable self signed jwt for grpc ([#160](https://www.github.com/googleapis/python-iot/issues/160)) ([4cab54a](https://www.github.com/googleapis/python-iot/commit/4cab54a57d1c62b0909dc378b2478bb266103ee2))


### Documentation

* add Samples section to CONTRIBUTING.rst ([#154](https://www.github.com/googleapis/python-iot/issues/154)) ([418f8f0](https://www.github.com/googleapis/python-iot/commit/418f8f0865b84dd2193d4f2baa86060069a892ad))


### Miscellaneous Chores

* release as 2.2.1 ([#161](https://www.github.com/googleapis/python-iot/issues/161)) ([645b6cc](https://www.github.com/googleapis/python-iot/commit/645b6cc3785b023b91b0b028ddf7209190b9b2aa))

## [2.2.0](https://www.github.com/googleapis/python-iot/compare/v2.1.0...v2.2.0) (2021-07-07)


### Features

* add always_use_jwt_access ([#130](https://www.github.com/googleapis/python-iot/issues/130)) ([a1025c2](https://www.github.com/googleapis/python-iot/commit/a1025c214245fc2397ef06403671457954777260))


### Bug Fixes

* disable always_use_jwt_access ([#135](https://www.github.com/googleapis/python-iot/issues/135)) ([911eb25](https://www.github.com/googleapis/python-iot/commit/911eb258b9f41855c62682ec1f0e495057b5d0e8))


### Documentation

* omit mention of Python 2.7 in 'CONTRIBUTING.rst' ([#1127](https://www.github.com/googleapis/python-iot/issues/1127)) ([#124](https://www.github.com/googleapis/python-iot/issues/124)) ([8eadfe7](https://www.github.com/googleapis/python-iot/commit/8eadfe797a9f05463068d2be4aed9773ed37e55b)), closes [#1126](https://www.github.com/googleapis/python-iot/issues/1126)

## [2.1.0](https://www.github.com/googleapis/python-iot/compare/v2.0.2...v2.1.0) (2021-06-16)


### Features

* add `from_service_account_info` ([af130f4](https://www.github.com/googleapis/python-iot/commit/af130f4f45356086d934569adf101bce1073971c))
* add blunderbuss config to cloud iot label ([#91](https://www.github.com/googleapis/python-iot/issues/91)) ([efd4d1b](https://www.github.com/googleapis/python-iot/commit/efd4d1ba2cb55e37e7b5efbd42a1bac1a10ce0d0))


### Bug Fixes

* **deps:** add packaging requirement ([#112](https://www.github.com/googleapis/python-iot/issues/112)) ([7bb82a7](https://www.github.com/googleapis/python-iot/commit/7bb82a76b2ac008b3f6310bd050e10c503eb5d09))
* use correct retry deadlines ([#81](https://www.github.com/googleapis/python-iot/issues/81)) ([af130f4](https://www.github.com/googleapis/python-iot/commit/af130f4f45356086d934569adf101bce1073971c))

### [2.0.2](https://www.github.com/googleapis/python-iot/compare/v2.0.1...v2.0.2) (2021-02-05)


### Bug Fixes

* add fieldMask for getDevice and listDevices ([#64](https://www.github.com/googleapis/python-iot/issues/64)) ([24c9c9a](https://www.github.com/googleapis/python-iot/commit/24c9c9a98af4147c77aa632ec4a9c3fb6464f30c))

### [2.0.1](https://www.github.com/googleapis/python-iot/compare/v2.0.0...v2.0.1) (2020-09-10)


### Documentation

* fix link to client library docs ([#33](https://www.github.com/googleapis/python-iot/issues/33)) ([074cb0a](https://www.github.com/googleapis/python-iot/commit/074cb0aa5c94c53980e96d49edfa4cd8d3ee6b25))

## [2.0.0](https://www.github.com/googleapis/python-iot/compare/v1.0.0...v2.0.0) (2020-09-10)


### ⚠ BREAKING CHANGES

* migrate to use microgen (#29)

### Features

* migrate to use microgen ([#29](https://www.github.com/googleapis/python-iot/issues/29)) ([f420fd3](https://www.github.com/googleapis/python-iot/commit/f420fd37441c92f3c9324b1d7278b210e3c5a8bc))


### Bug Fixes

* update retry configs ([#19](https://www.github.com/googleapis/python-iot/issues/19)) ([5d7a613](https://www.github.com/googleapis/python-iot/commit/5d7a613f54e5326adf719e7aeb9cac06ef64f48c))

## [1.0.0](https://www.github.com/googleapis/python-iot/compare/v0.3.1...v1.0.0) (2020-02-28)


### Features

* bump release status to GA ([#6](https://www.github.com/googleapis/python-iot/issues/6)) ([6793d49](https://www.github.com/googleapis/python-iot/commit/6793d493ec576191996c2e82c52ff549ee26347c))

### [0.3.1](https://www.github.com/googleapis/python-iot/compare/v0.3.0...v0.3.1) (2020-02-06)


### Bug Fixes

* **iot:** modify retry and timeout configs; add 2.7 deprecation warning; add 'required' to docstring for required args; add 3.8 unit tests (via synth)  ([#10069](https://www.github.com/googleapis/python-iot/issues/10069)) ([ce6f5cf](https://www.github.com/googleapis/python-iot/commit/ce6f5cf2c1611af179da8dba3f73b1f8dc1bb1e1))

## 0.3.0

07-24-2019 16:35 PDT


### Implementation Changes
- Allow kwargs to be passed to create_channel (via synth). ([#8393](https://github.com/googleapis/google-cloud-python/pull/8393))
- Remove classifier for Python 3.4 for end-of-life. ([#7535](https://github.com/googleapis/google-cloud-python/pull/7535))
- Remove unused message exports. ([#7269](https://github.com/googleapis/google-cloud-python/pull/7269))
- Protoc-generated serialization update. ([#7085](https://github.com/googleapis/google-cloud-python/pull/7085))
- Pick up stub docstring fix in GAPIC generator. ([#6973](https://github.com/googleapis/google-cloud-python/pull/6973))

### New Features
- Add 'options_' argument to clients' 'get_iam_policy'; pin black version (via synth). ([#8655](https://github.com/googleapis/google-cloud-python/pull/8655))
- Add 'client_options' support, update list method docstrings (via synth). ([#8512](https://github.com/googleapis/google-cloud-python/pull/8512))

### Dependencies
- Bump minimum version for google-api-core to 1.14.0. ([#8709](https://github.com/googleapis/google-cloud-python/pull/8709))
- Update pin for 'grpc-google-iam-v1' to 0.12.3+. ([#8647](https://github.com/googleapis/google-cloud-python/pull/8647))

### Documentation
- Link to googleapis.dev documentation in READMEs. ([#8705](https://github.com/googleapis/google-cloud-python/pull/8705))
- Add compatibility check badges to READMEs. ([#8288](https://github.com/googleapis/google-cloud-python/pull/8288))
- Update docstrings (via synth). ([#7867](https://github.com/googleapis/google-cloud-python/pull/7867))
- Updated client library documentation URLs. ([#7307](https://github.com/googleapis/google-cloud-python/pull/7307))
- Update copyright: 2018 -> 2019. ([#7147](https://github.com/googleapis/google-cloud-python/pull/7147))

### Internal / Testing Changes
- Add docs job to publish to googleapis.dev. ([#8464](https://github.com/googleapis/google-cloud-python/pull/8464))
- Declare encoding as utf-8 in pb2 files (via synth). [#8354](https://github.com/googleapis/google-cloud-python/pull/8354))
- Add disclaimer to auto-generated template files (via synth). ([#8316](https://github.com/googleapis/google-cloud-python/pull/8316))
- Suppress checking 'cov-fail-under' in nox default session (via synth).  ([#8243](https://github.com/googleapis/google-cloud-python/pull/8243))
- Fix coverage in 'types.py' (via synth). ([#8155](https://github.com/googleapis/google-cloud-python/pull/8155))
- Blacken noxfile.py, setup.py (via synth). ([#8125](https://github.com/googleapis/google-cloud-python/pull/8125))
- Add empty lines (via synth). ([#8060](https://github.com/googleapis/google-cloud-python/pull/8060))
- Exclude docs/index.rst from move in synth. ([#7835](https://github.com/googleapis/google-cloud-python/pull/7835))
- Reorder methods, add nox session `docs` (via synth). ([#7773](https://github.com/googleapis/google-cloud-python/pull/7773))
- Copy lintified proto files (via synth). ([#7448](https://github.com/googleapis/google-cloud-python/pull/7448))
- Add clarifying comment to blacken nox target. ([#7394](https://github.com/googleapis/google-cloud-python/pull/7394))
- Add protos as an artifact to library ([#7205](https://github.com/googleapis/google-cloud-python/pull/7205))

## 0.2.0

12-18-2018 09:19 PST


### Implementation Changes
- Import `iam.policy` from `google.api_core`. ([#6741](https://github.com/googleapis/google-cloud-python/pull/6741))
- Pick up new methods from protos. ([#6613](https://github.com/googleapis/google-cloud-python/pull/6613))
- Pick up fixes to GAPIC generator. ([#6513](https://github.com/googleapis/google-cloud-python/pull/6513))
- Fix `client_info` bug, update docstrings. ([#6413](https://github.com/googleapis/google-cloud-python/pull/6413))

### Dependencies
- Bump minimum `api_core` version for all GAPIC libs to 1.4.1. ([#6391](https://github.com/googleapis/google-cloud-python/pull/6391))
- Update IAM version in dependencies ([#6362](https://github.com/googleapis/google-cloud-python/pull/6362))
- Avoid broken 'google-common-apis 1.5.4' release. ([#6355](https://github.com/googleapis/google-cloud-python/pull/6355))

### Documentation
- Document Python 2 deprecation ([#6910](https://github.com/googleapis/google-cloud-python/pull/6910))
- Fix GAX fossils ([#6264](https://github.com/googleapis/google-cloud-python/pull/6264))
- Normalize use of support level badges ([#6159](https://github.com/googleapis/google-cloud-python/pull/6159))
- Replace links to `/stable/` with `/latest/`. ([#5901](https://github.com/googleapis/google-cloud-python/pull/5901))

### Internal / Testing Changes
- Update noxfile.
- Blacken all gen'd libs ([#6792](https://github.com/googleapis/google-cloud-python/pull/6792))
- Omit local deps ([#6701](https://github.com/googleapis/google-cloud-python/pull/6701))
- Run black at end of synth.py ([#6698](https://github.com/googleapis/google-cloud-python/pull/6698))
- Run Black on Generated libraries ([#6666](https://github.com/googleapis/google-cloud-python/pull/6666))
- Add templates for flake8, coveragerc, noxfile, and black. ([#6642](https://github.com/googleapis/google-cloud-python/pull/6642))
- Add synth metadata. ([#6568](https://github.com/googleapis/google-cloud-python/pull/6568))
- Add 'mock' to unit test dependencies for autogen libs. ([#6402](https://github.com/googleapis/google-cloud-python/pull/6402))
- Add / fix badges for PyPI / versions. ([#6158](https://github.com/googleapis/google-cloud-python/pull/6158))
- Use new Nox ([#6175](https://github.com/googleapis/google-cloud-python/pull/6175))
- Add 'synth.py'. ([#6085](https://github.com/googleapis/google-cloud-python/pull/6085))
- Include IoT docs in build. ([#5679](https://github.com/googleapis/google-cloud-python/pull/5679))
- fix trove classifier ([#5386](https://github.com/googleapis/google-cloud-python/pull/5386))

## 0.1.0

### New Features
- Add v1 Endpoint for IoT (#5355)
