# [1.1.0](https://github.com/projectcaluma/ember-emeis/compare/v1.0.0...v1.1.0) (2021-08-11)


### Bug Fixes

* add ember-engines to blueprint, docs ([#258](https://github.com/projectcaluma/ember-emeis/issues/258)) ([35c40a7](https://github.com/projectcaluma/ember-emeis/commit/35c40a742e3d00ea0b5860f826a613777b09402f))


### Features

* indent scopes list according to level ([#260](https://github.com/projectcaluma/ember-emeis/issues/260)) ([13c822f](https://github.com/projectcaluma/ember-emeis/commit/13c822fcd172c9a871eefd10e4a1a638ae0e72fb))

# 1.0.0 (2021-08-11)


### Bug Fixes

* **application.hbs:** set container to overflow: auto ([853fb9e](https://github.com/projectcaluma/ember-emeis/commit/853fb9e8b45e09b5236c36366dd8d046cd939878))
* **concurrency:** use dropTask to prevent state issues ([7a0bb4a](https://github.com/projectcaluma/ember-emeis/commit/7a0bb4a09558e2d484b7362b5413e8d1c890313c))
* **edit-form:** prevent type error by checking if listViewRouteName is passed ([09e03c5](https://github.com/projectcaluma/ember-emeis/commit/09e03c5eb62998029639e8d02671abfade7dde6f))
* **edit-form:** replace hardcoded route name handling with dynamic since an engine can be mouted with a different name ([e770214](https://github.com/projectcaluma/ember-emeis/commit/e77021404a2a9e4d84ad2b900169d4cbccecea34))
* **import:** fix import of pagination controller ([27c6d1b](https://github.com/projectcaluma/ember-emeis/commit/27c6d1bf540fe1b4cea926ccc905314d2165e434))
* **pagination:** only check if strings are empty so they are not serialized as an empty qp ([d79e0a4](https://github.com/projectcaluma/ember-emeis/commit/d79e0a42da7b0db3f8a806f2a6f94540a30b9cb0))
* add ember-engines to blueprint, docs ([#258](https://github.com/projectcaluma/ember-emeis/issues/258)) ([35c40a7](https://github.com/projectcaluma/ember-emeis/commit/35c40a742e3d00ea0b5860f826a613777b09402f))
* **relationship-select:** only debounce if search is set so we dont debounce the initial request ([a8c2f03](https://github.com/projectcaluma/ember-emeis/commit/a8c2f0336bfb52a15ef311c1a1eb8a52c82dd54b))
* **relationship-select:** use let instead of with ([690c0ba](https://github.com/projectcaluma/ember-emeis/commit/690c0baab23b288a27656af9f56574cf4b7bd353))
* **route model hooks:** just return a promise to the model hook, no need for async ([fe9ccbf](https://github.com/projectcaluma/ember-emeis/commit/fe9ccbf57391f271603bcc1b61797af7f4dcb180))
* **user-edit:** make route name argument passed to edit form for listview relative ([80d16d5](https://github.com/projectcaluma/ember-emeis/commit/80d16d5544905a24d0c1e04c8cc604299b80f63d))
* **users/edit:** remove UkTab component usage ([abfd9d5](https://github.com/projectcaluma/ember-emeis/commit/abfd9d50a5c4893be59d7ad81ecf330d6505991c))


### Features

* **acl-wizzard:** add wizzard to guide user through acl creation ([50d5a22](https://github.com/projectcaluma/ember-emeis/commit/50d5a228b97eb265077186a0fbb8c5dbe43a6209))
* **create route:** add class for creating new models by reusing the edit view ([ac278ec](https://github.com/projectcaluma/ember-emeis/commit/ac278ec85c94beb6d7cab556b9fc86a09b93a16a))
* **decorators:** add error handling for common model usage ([38155db](https://github.com/projectcaluma/ember-emeis/commit/38155dbf22614b6fad9467c83521764712a49146))
* **edit-form:** add a minimalistic form for editing model fields ([31e4a99](https://github.com/projectcaluma/ember-emeis/commit/31e4a992a46ad13d3186bef22c8c33868e6a521f))
* **engine:** add blueprint and dependencies ([9d31cfb](https://github.com/projectcaluma/ember-emeis/commit/9d31cfb5aa5fe5ab35a943d3f57118f1574caa80))
* **engine:** initialize ember-engines configuration ([b22fcff](https://github.com/projectcaluma/ember-emeis/commit/b22fcffac9d1598875a88570fdde64ebb1f8be95))
* **models:** add models and factories ([fe09023](https://github.com/projectcaluma/ember-emeis/commit/fe090230df41223469cbcfd67a8eb2f98be457ce))
* **multilang:** add decorator for localized fields ([ec20d27](https://github.com/projectcaluma/ember-emeis/commit/ec20d273dcffec2bc73721f37ff0822c9aed99af))
* **multilang:** add serializers for localized models ([88c89c5](https://github.com/projectcaluma/ember-emeis/commit/88c89c58d07edafd9c15337bca0e08de84d7c68d))
* **nav:** add nav ([a40bdcc](https://github.com/projectcaluma/ember-emeis/commit/a40bdcc62b4af525e2f22779e1e1d535baf93417))
* **nav:** add nav components ([066f867](https://github.com/projectcaluma/ember-emeis/commit/066f8676a8395ceffd2657dc9906d9df6036a4f6))
* **permission index view:** add permission list view ([749b00c](https://github.com/projectcaluma/ember-emeis/commit/749b00ca862135af533b456068763144f64b92b7))
* **permissions:**  add permission edit view ([666c720](https://github.com/projectcaluma/ember-emeis/commit/666c72062c0b56f5e6b9853674bd9c3f2f22eb30))
* **permissions:** add a create view ([c5846ae](https://github.com/projectcaluma/ember-emeis/commit/c5846aecdfb84bffe670a883f618b7d532d4b7e6))
* **relationship-select:** add component to select a model for a relationship via power-select ([373f213](https://github.com/projectcaluma/ember-emeis/commit/373f2138b64e4152f5a311253ce7d03596c8457c))
* **role index view:** add roles list view ([5dccab4](https://github.com/projectcaluma/ember-emeis/commit/5dccab401512bfd2372359be8cbe799144d9ddc4))
* add example route and model for group ([10b7843](https://github.com/projectcaluma/ember-emeis/commit/10b784343332accf36ab6d46226ad266b5d8c2fd))
* **scopes:** add create view ([55b93ef](https://github.com/projectcaluma/ember-emeis/commit/55b93ef3cd737c684ea6412bf7bc23c78b98b446))
* indent scopes list according to level ([#260](https://github.com/projectcaluma/ember-emeis/issues/260)) ([13c822f](https://github.com/projectcaluma/ember-emeis/commit/13c822fcd172c9a871eefd10e4a1a638ae0e72fb))
* **roles:** add create view ([b9013d9](https://github.com/projectcaluma/ember-emeis/commit/b9013d97b6455fcfaff3cb69349bbd8765679dad))
* **roles:** add edit view ([7bb7cc4](https://github.com/projectcaluma/ember-emeis/commit/7bb7cc4ea0430e6394d575b3e4a06330ead276e1))
* **routes:** add basic route setup ([26b57ce](https://github.com/projectcaluma/ember-emeis/commit/26b57ce8511df5d814e8d1a17af7da9c0c8e89f3))
* **scope index view:** add list view for scopes ([490ead0](https://github.com/projectcaluma/ember-emeis/commit/490ead07e96c71fd6797b02e6a3a6124177d6bd0))
* **scopes:** add edit view for scopes ([a5847bf](https://github.com/projectcaluma/ember-emeis/commit/a5847bf32003904baa9174900175c12813b3312e))
* **section title:** add a component for section headings ([e0437bf](https://github.com/projectcaluma/ember-emeis/commit/e0437bf2288da6925111c420f0afab24e499c77d))
* **store blueprint:** add a blueprint for customizing the store passed to emeis engine ([2b434d6](https://github.com/projectcaluma/ember-emeis/commit/2b434d622c2e595d6da8d70aeef160bbef97138f))
* **user:** add acl edit and create views ([cc990ab](https://github.com/projectcaluma/ember-emeis/commit/cc990ab35a7efdea966240587fba2855c5819e12))
* **user:** add create view ([7a3caf4](https://github.com/projectcaluma/ember-emeis/commit/7a3caf40d215679a0dabb0fbdb5ed205b13b7e6f))
* **user:** add edit view ([2b19e3f](https://github.com/projectcaluma/ember-emeis/commit/2b19e3f0f69bbda630cd06cefcde69a03269cd4e))
* **user index view:** add user list view ([ac51323](https://github.com/projectcaluma/ember-emeis/commit/ac513234f095de508c2d9cd0869c22d1f4e5ae4a))

# 1.0.0 (2021-08-11)


### Bug Fixes

* **application.hbs:** set container to overflow: auto ([853fb9e](https://github.com/projectcaluma/ember-emeis/commit/853fb9e8b45e09b5236c36366dd8d046cd939878))
* **concurrency:** use dropTask to prevent state issues ([7a0bb4a](https://github.com/projectcaluma/ember-emeis/commit/7a0bb4a09558e2d484b7362b5413e8d1c890313c))
* **edit-form:** prevent type error by checking if listViewRouteName is passed ([09e03c5](https://github.com/projectcaluma/ember-emeis/commit/09e03c5eb62998029639e8d02671abfade7dde6f))
* **edit-form:** replace hardcoded route name handling with dynamic since an engine can be mouted with a different name ([e770214](https://github.com/projectcaluma/ember-emeis/commit/e77021404a2a9e4d84ad2b900169d4cbccecea34))
* **import:** fix import of pagination controller ([27c6d1b](https://github.com/projectcaluma/ember-emeis/commit/27c6d1bf540fe1b4cea926ccc905314d2165e434))
* **pagination:** only check if strings are empty so they are not serialized as an empty qp ([d79e0a4](https://github.com/projectcaluma/ember-emeis/commit/d79e0a42da7b0db3f8a806f2a6f94540a30b9cb0))
* add ember-engines to blueprint, docs ([#258](https://github.com/projectcaluma/ember-emeis/issues/258)) ([35c40a7](https://github.com/projectcaluma/ember-emeis/commit/35c40a742e3d00ea0b5860f826a613777b09402f))
* **relationship-select:** only debounce if search is set so we dont debounce the initial request ([a8c2f03](https://github.com/projectcaluma/ember-emeis/commit/a8c2f0336bfb52a15ef311c1a1eb8a52c82dd54b))
* **relationship-select:** use let instead of with ([690c0ba](https://github.com/projectcaluma/ember-emeis/commit/690c0baab23b288a27656af9f56574cf4b7bd353))
* **route model hooks:** just return a promise to the model hook, no need for async ([fe9ccbf](https://github.com/projectcaluma/ember-emeis/commit/fe9ccbf57391f271603bcc1b61797af7f4dcb180))
* **user-edit:** make route name argument passed to edit form for listview relative ([80d16d5](https://github.com/projectcaluma/ember-emeis/commit/80d16d5544905a24d0c1e04c8cc604299b80f63d))
* **users/edit:** remove UkTab component usage ([abfd9d5](https://github.com/projectcaluma/ember-emeis/commit/abfd9d50a5c4893be59d7ad81ecf330d6505991c))


### Features

* **acl-wizzard:** add wizzard to guide user through acl creation ([50d5a22](https://github.com/projectcaluma/ember-emeis/commit/50d5a228b97eb265077186a0fbb8c5dbe43a6209))
* **create route:** add class for creating new models by reusing the edit view ([ac278ec](https://github.com/projectcaluma/ember-emeis/commit/ac278ec85c94beb6d7cab556b9fc86a09b93a16a))
* **decorators:** add error handling for common model usage ([38155db](https://github.com/projectcaluma/ember-emeis/commit/38155dbf22614b6fad9467c83521764712a49146))
* **edit-form:** add a minimalistic form for editing model fields ([31e4a99](https://github.com/projectcaluma/ember-emeis/commit/31e4a992a46ad13d3186bef22c8c33868e6a521f))
* **engine:** add blueprint and dependencies ([9d31cfb](https://github.com/projectcaluma/ember-emeis/commit/9d31cfb5aa5fe5ab35a943d3f57118f1574caa80))
* **engine:** initialize ember-engines configuration ([b22fcff](https://github.com/projectcaluma/ember-emeis/commit/b22fcffac9d1598875a88570fdde64ebb1f8be95))
* **models:** add models and factories ([fe09023](https://github.com/projectcaluma/ember-emeis/commit/fe090230df41223469cbcfd67a8eb2f98be457ce))
* **multilang:** add decorator for localized fields ([ec20d27](https://github.com/projectcaluma/ember-emeis/commit/ec20d273dcffec2bc73721f37ff0822c9aed99af))
* **multilang:** add serializers for localized models ([88c89c5](https://github.com/projectcaluma/ember-emeis/commit/88c89c58d07edafd9c15337bca0e08de84d7c68d))
* **nav:** add nav ([a40bdcc](https://github.com/projectcaluma/ember-emeis/commit/a40bdcc62b4af525e2f22779e1e1d535baf93417))
* **nav:** add nav components ([066f867](https://github.com/projectcaluma/ember-emeis/commit/066f8676a8395ceffd2657dc9906d9df6036a4f6))
* **permission index view:** add permission list view ([749b00c](https://github.com/projectcaluma/ember-emeis/commit/749b00ca862135af533b456068763144f64b92b7))
* **permissions:**  add permission edit view ([666c720](https://github.com/projectcaluma/ember-emeis/commit/666c72062c0b56f5e6b9853674bd9c3f2f22eb30))
* **permissions:** add a create view ([c5846ae](https://github.com/projectcaluma/ember-emeis/commit/c5846aecdfb84bffe670a883f618b7d532d4b7e6))
* **relationship-select:** add component to select a model for a relationship via power-select ([373f213](https://github.com/projectcaluma/ember-emeis/commit/373f2138b64e4152f5a311253ce7d03596c8457c))
* **role index view:** add roles list view ([5dccab4](https://github.com/projectcaluma/ember-emeis/commit/5dccab401512bfd2372359be8cbe799144d9ddc4))
* add example route and model for group ([10b7843](https://github.com/projectcaluma/ember-emeis/commit/10b784343332accf36ab6d46226ad266b5d8c2fd))
* **scopes:** add create view ([55b93ef](https://github.com/projectcaluma/ember-emeis/commit/55b93ef3cd737c684ea6412bf7bc23c78b98b446))
* indent scopes list according to level ([#260](https://github.com/projectcaluma/ember-emeis/issues/260)) ([13c822f](https://github.com/projectcaluma/ember-emeis/commit/13c822fcd172c9a871eefd10e4a1a638ae0e72fb))
* **roles:** add create view ([b9013d9](https://github.com/projectcaluma/ember-emeis/commit/b9013d97b6455fcfaff3cb69349bbd8765679dad))
* **roles:** add edit view ([7bb7cc4](https://github.com/projectcaluma/ember-emeis/commit/7bb7cc4ea0430e6394d575b3e4a06330ead276e1))
* **routes:** add basic route setup ([26b57ce](https://github.com/projectcaluma/ember-emeis/commit/26b57ce8511df5d814e8d1a17af7da9c0c8e89f3))
* **scope index view:** add list view for scopes ([490ead0](https://github.com/projectcaluma/ember-emeis/commit/490ead07e96c71fd6797b02e6a3a6124177d6bd0))
* **scopes:** add edit view for scopes ([a5847bf](https://github.com/projectcaluma/ember-emeis/commit/a5847bf32003904baa9174900175c12813b3312e))
* **section title:** add a component for section headings ([e0437bf](https://github.com/projectcaluma/ember-emeis/commit/e0437bf2288da6925111c420f0afab24e499c77d))
* **store blueprint:** add a blueprint for customizing the store passed to emeis engine ([2b434d6](https://github.com/projectcaluma/ember-emeis/commit/2b434d622c2e595d6da8d70aeef160bbef97138f))
* **user:** add acl edit and create views ([cc990ab](https://github.com/projectcaluma/ember-emeis/commit/cc990ab35a7efdea966240587fba2855c5819e12))
* **user:** add create view ([7a3caf4](https://github.com/projectcaluma/ember-emeis/commit/7a3caf40d215679a0dabb0fbdb5ed205b13b7e6f))
* **user:** add edit view ([2b19e3f](https://github.com/projectcaluma/ember-emeis/commit/2b19e3f0f69bbda630cd06cefcde69a03269cd4e))
* **user index view:** add user list view ([ac51323](https://github.com/projectcaluma/ember-emeis/commit/ac513234f095de508c2d9cd0869c22d1f4e5ae4a))

# 1.0.0 (2020-10-27)


### Bug Fixes

* **application.hbs:** set container to overflow: auto ([853fb9e](https://github.com/projectcaluma/ember-emeis/commit/853fb9e8b45e09b5236c36366dd8d046cd939878))
* **concurrency:** use dropTask to prevent state issues ([7a0bb4a](https://github.com/projectcaluma/ember-emeis/commit/7a0bb4a09558e2d484b7362b5413e8d1c890313c))
* **edit-form:** prevent type error by checking if listViewRouteName is passed ([09e03c5](https://github.com/projectcaluma/ember-emeis/commit/09e03c5eb62998029639e8d02671abfade7dde6f))
* **edit-form:** replace hardcoded route name handling with dynamic since an engine can be mouted with a different name ([e770214](https://github.com/projectcaluma/ember-emeis/commit/e77021404a2a9e4d84ad2b900169d4cbccecea34))
* **import:** fix import of pagination controller ([27c6d1b](https://github.com/projectcaluma/ember-emeis/commit/27c6d1bf540fe1b4cea926ccc905314d2165e434))
* **pagination:** only check if strings are empty so they are not serialized as an empty qp ([d79e0a4](https://github.com/projectcaluma/ember-emeis/commit/d79e0a42da7b0db3f8a806f2a6f94540a30b9cb0))
* **relationship-select:** only debounce if search is set so we dont debounce the initial request ([a8c2f03](https://github.com/projectcaluma/ember-emeis/commit/a8c2f0336bfb52a15ef311c1a1eb8a52c82dd54b))
* **relationship-select:** use let instead of with ([690c0ba](https://github.com/projectcaluma/ember-emeis/commit/690c0baab23b288a27656af9f56574cf4b7bd353))
* **route model hooks:** just return a promise to the model hook, no need for async ([fe9ccbf](https://github.com/projectcaluma/ember-emeis/commit/fe9ccbf57391f271603bcc1b61797af7f4dcb180))
* **user-edit:** make route name argument passed to edit form for listview relative ([80d16d5](https://github.com/projectcaluma/ember-emeis/commit/80d16d5544905a24d0c1e04c8cc604299b80f63d))
* **users/edit:** remove UkTab component usage ([abfd9d5](https://github.com/projectcaluma/ember-emeis/commit/abfd9d50a5c4893be59d7ad81ecf330d6505991c))


### Features

* **acl-wizzard:** add wizzard to guide user through acl creation ([50d5a22](https://github.com/projectcaluma/ember-emeis/commit/50d5a228b97eb265077186a0fbb8c5dbe43a6209))
* **create route:** add class for creating new models by reusing the edit view ([ac278ec](https://github.com/projectcaluma/ember-emeis/commit/ac278ec85c94beb6d7cab556b9fc86a09b93a16a))
* **decorators:** add error handling for common model usage ([38155db](https://github.com/projectcaluma/ember-emeis/commit/38155dbf22614b6fad9467c83521764712a49146))
* **edit-form:** add a minimalistic form for editing model fields ([31e4a99](https://github.com/projectcaluma/ember-emeis/commit/31e4a992a46ad13d3186bef22c8c33868e6a521f))
* **engine:** add blueprint and dependencies ([9d31cfb](https://github.com/projectcaluma/ember-emeis/commit/9d31cfb5aa5fe5ab35a943d3f57118f1574caa80))
* **engine:** initialize ember-engines configuration ([b22fcff](https://github.com/projectcaluma/ember-emeis/commit/b22fcffac9d1598875a88570fdde64ebb1f8be95))
* **models:** add models and factories ([fe09023](https://github.com/projectcaluma/ember-emeis/commit/fe090230df41223469cbcfd67a8eb2f98be457ce))
* **multilang:** add decorator for localized fields ([ec20d27](https://github.com/projectcaluma/ember-emeis/commit/ec20d273dcffec2bc73721f37ff0822c9aed99af))
* **multilang:** add serializers for localized models ([88c89c5](https://github.com/projectcaluma/ember-emeis/commit/88c89c58d07edafd9c15337bca0e08de84d7c68d))
* **nav:** add nav ([a40bdcc](https://github.com/projectcaluma/ember-emeis/commit/a40bdcc62b4af525e2f22779e1e1d535baf93417))
* **nav:** add nav components ([066f867](https://github.com/projectcaluma/ember-emeis/commit/066f8676a8395ceffd2657dc9906d9df6036a4f6))
* **permission index view:** add permission list view ([749b00c](https://github.com/projectcaluma/ember-emeis/commit/749b00ca862135af533b456068763144f64b92b7))
* **permissions:**  add permission edit view ([666c720](https://github.com/projectcaluma/ember-emeis/commit/666c72062c0b56f5e6b9853674bd9c3f2f22eb30))
* **permissions:** add a create view ([c5846ae](https://github.com/projectcaluma/ember-emeis/commit/c5846aecdfb84bffe670a883f618b7d532d4b7e6))
* **relationship-select:** add component to select a model for a relationship via power-select ([373f213](https://github.com/projectcaluma/ember-emeis/commit/373f2138b64e4152f5a311253ce7d03596c8457c))
* **role index view:** add roles list view ([5dccab4](https://github.com/projectcaluma/ember-emeis/commit/5dccab401512bfd2372359be8cbe799144d9ddc4))
* **roles:** add create view ([b9013d9](https://github.com/projectcaluma/ember-emeis/commit/b9013d97b6455fcfaff3cb69349bbd8765679dad))
* **roles:** add edit view ([7bb7cc4](https://github.com/projectcaluma/ember-emeis/commit/7bb7cc4ea0430e6394d575b3e4a06330ead276e1))
* **routes:** add basic route setup ([26b57ce](https://github.com/projectcaluma/ember-emeis/commit/26b57ce8511df5d814e8d1a17af7da9c0c8e89f3))
* **scope index view:** add list view for scopes ([490ead0](https://github.com/projectcaluma/ember-emeis/commit/490ead07e96c71fd6797b02e6a3a6124177d6bd0))
* **scopes:** add create view ([55b93ef](https://github.com/projectcaluma/ember-emeis/commit/55b93ef3cd737c684ea6412bf7bc23c78b98b446))
* **scopes:** add edit view for scopes ([a5847bf](https://github.com/projectcaluma/ember-emeis/commit/a5847bf32003904baa9174900175c12813b3312e))
* **section title:** add a component for section headings ([e0437bf](https://github.com/projectcaluma/ember-emeis/commit/e0437bf2288da6925111c420f0afab24e499c77d))
* **store blueprint:** add a blueprint for customizing the store passed to emeis engine ([2b434d6](https://github.com/projectcaluma/ember-emeis/commit/2b434d622c2e595d6da8d70aeef160bbef97138f))
* **user:** add acl edit and create views ([cc990ab](https://github.com/projectcaluma/ember-emeis/commit/cc990ab35a7efdea966240587fba2855c5819e12))
* **user:** add create view ([7a3caf4](https://github.com/projectcaluma/ember-emeis/commit/7a3caf40d215679a0dabb0fbdb5ed205b13b7e6f))
* add example route and model for group ([10b7843](https://github.com/projectcaluma/ember-emeis/commit/10b784343332accf36ab6d46226ad266b5d8c2fd))
* **user:** add edit view ([2b19e3f](https://github.com/projectcaluma/ember-emeis/commit/2b19e3f0f69bbda630cd06cefcde69a03269cd4e))
* **user index view:** add user list view ([ac51323](https://github.com/projectcaluma/ember-emeis/commit/ac513234f095de508c2d9cd0869c22d1f4e5ae4a))
