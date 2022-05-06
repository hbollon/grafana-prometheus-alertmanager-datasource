## [1.1.0](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/compare/v1.0.0...v1.1.0) (2022-05-05)


### Features

* add alertstatus and alertstatus_code fields to data frame ([#101](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/pull/101))
* add doc to configure singlestat panel ([8c51289](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/8c5128940c2baf97ac4118461cb2684170d82a40))
* add github actions for build process ([29a7494](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/29a7494d8ea864545612f1300970f3f80edb4698))
* display active alerts by default ([da31418](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/da31418b3aaf83931466656f1801f093491941b3))
* update tslib dependency ([b420606](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/b4206069fefca48d9c2555e7bb6d50a2de33471f))


### Bug Fixes

* regex escape in filters ([ad8ba67](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/ad8ba678ef80cf6889ca916671cd1bc9acbf43aa))
* revert to original plugin id ([#101](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/pull/101))
* packaging linting errors raised by Grafana plugins check webapp ([#96](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/pull/96))
* build workflow ([b4d72a7](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/b4d72a74782a572d91fc08356185ad65bf010030))
* **ci:** remove package-lock.json ([db32e71](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/db32e712ee1c6151ddbc5be6032e3d198e3e9800))
* **doc:** add missing images ([a26d316](https://www.github.com/camptocamp/grafana-prometheus-alertmanager-datasource/commit/a26d316a3067d72cc615937a683401ad9e0ed247))


## [1.3.0](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/compare/v1.2.0...v1.3.0) (2022-05-06)


### Features

* add doc to configure singlestat panel ([8c51289](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/8c5128940c2baf97ac4118461cb2684170d82a40))
* add github actions for build process ([29a7494](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/29a7494d8ea864545612f1300970f3f80edb4698))
* display active alerts by default ([da31418](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/da31418b3aaf83931466656f1801f093491941b3))
* Empty-Commit ([df67d7b](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/df67d7bba3b3acd8b0595789717a35abc2da257d))
* Empty-Commit ([c2bebbb](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/c2bebbb7ebcaf1ba97fce947f591b7ddbd0a1deb))
* new release workflow ([74b72dd](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/74b72dd5e23886c8f9ddee2272f5b526db3ff3fd))
* test release 1.3.0 ([60afd53](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/60afd537855bb37c4aadf33f176c677661caddb1))


### Bug Fixes

* 10, template variables single format ([111685e](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/111685ed46782fb2b9ac057b1a5c3347ee4361fb))
* build workflow ([b4d72a7](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/b4d72a74782a572d91fc08356185ad65bf010030))
* **ci:** remove package-lock.json ([db32e71](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/db32e712ee1c6151ddbc5be6032e3d198e3e9800))
* **doc:** add missing images ([a26d316](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/a26d316a3067d72cc615937a683401ad9e0ed247))
* remove data from datasource requests ([703ab37](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/703ab377ce31183d69545e7a6359749d4d00ecc3))

## [1.2.0](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/compare/v1.1.0...v1.2.0) (2022-05-06)


### Features

* Empty-Commit ([c2bebbb](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/c2bebbb7ebcaf1ba97fce947f591b7ddbd0a1deb))
* new release workflow ([74b72dd](https://github.com/hbollon/grafana-prometheus-alertmanager-datasource/commit/74b72dd5e23886c8f9ddee2272f5b526db3ff3fd))

## 1.0.0 (Feb 12, 2021)

- IMPROVEMENTS

  * Rewrite plugin to match latest dev standards (Typescript, Yarn)
  * Add support of latest Grafana versions

## 0.0.8 (Apr 22, 2020)

- IMPROVEMENTS

  * Add support of variable templating ([#55](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/pull/55))

- BUGFIX

  * Fix datasource request ([#73](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/pull/73))

## 0.0.7 (Jan 25, 2019)

- IMPROVEMENTS

  * Allow undefined severity labels ([#44](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/issues/44))
  * Allow usage of multi-values variables ([#40](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/issues/40))

- BUGFIX

  * Fix blank severity column ([#31](https://github.com/camptocamp/grafana-prometheus-alertmanager-datasource/issues/31))

## 0.0.6 (May 22, 2018)

  * Use Apache License 2.0
  * Fix severity labels struct (#26)

## 0.0.5 (May 23, 2018)

- Datasource:

  * Display annotations and labels in separate columns
  * Add a selector in query editor to choose the columns to display

## 0.0.4 (March 29, 2018)

- Datasource:

  * Allow manual definition of severity levels
  * Fix templating and add support of All and Multi variables

## 0.0.3 (December 01, 2017)

- Datasource:

  * Add templating support

## 0.0.2 (December 01, 2017)

- Datasource:
  
  * Add support annotations
