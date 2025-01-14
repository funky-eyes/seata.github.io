---
title: Release Notes
keywords: [Seata, Release Notes, 1.8.x]
description: 1.8.x Release Notes
---


# Downloads

# Seata

> GitHub: <https://github.com/apache/incubator-seata>
>
> Release Notes: <https://github.com/apache/incubator-seata/releases>

### 1.8.0 (2023-11-05)

[source](https://github.com/apache/incubator-seata/archive/v1.8.0.zip) |
[binary](https://github.com/apache/incubator-seata/releases/download/v1.8.0/seata-server-1.8.0.zip)

<details>
  <summary><mark>Release notes</mark></summary>

### Seata 1.8.0

Seata 1.8.0 Released

Seata is an easy-to-use, high-performance, open source distributed transaction solution.

The version is updated as follows:

### feature

- [[#3672](https://github.com/apache/incubator-seata/pull/3672)] support Dameng database
- [[#5892](https://github.com/apache/incubator-seata/pull/5892)] support PolarDB-X 2.0 database

### bugfix

- [[#5833](https://github.com/apache/incubator-seata/pull/5833)] bugfix: fix TC retry rollback wrongly, after the XA transaction fail and rollback
- [[#5884](https://github.com/apache/incubator-seata/pull/5884)] fix dm escaped characters for upper and lower case column names
- [[#5931](https://github.com/apache/incubator-seata/pull/5931)] fix the issue of missing sentinel password in store redis mode
- [[#5970](https://github.com/apache/incubator-seata/pull/5970)] fix some configurations that are not deprecated show "Deprecated"

### optimize

- [[#5866](https://github.com/apache/incubator-seata/pull/5866)] some minor syntax optimization
- [[#5889](https://github.com/apache/incubator-seata/pull/5889)] remove dependency without license
- [[#5890](https://github.com/apache/incubator-seata/pull/5890)] remove 7z format compression support
- [[#5891](https://github.com/apache/incubator-seata/pull/5891)] remove mariadb.jdbc dependency
- [[#5828](https://github.com/apache/incubator-seata/pull/5828)] fix codecov chart not display
- [[#5927](https://github.com/apache/incubator-seata/pull/5927)] optimize some scripts related to Apollo
- [[#5918](https://github.com/apache/incubator-seata/pull/5918)] standardized the properties of codecov.yml
- [[#5939](https://github.com/apache/incubator-seata/pull/5939)] support jmx port in seata

### security

- [[#5867](https://github.com/apache/incubator-seata/pull/5867)] fix npm package vulnerabilities
- [[#5898](https://github.com/apache/incubator-seata/pull/5898)] fix npm package vulnerabilities

### test

- [[#5888](https://github.com/apache/incubator-seata/pull/5888)] remove sofa test cases
- [[#5831](https://github.com/apache/incubator-seata/pull/5831)] upgrade druid and add `test-druid.yml`
- [[#5862](https://github.com/apache/incubator-seata/pull/5862)] fix unit test in java 21
- [[#5914](https://github.com/apache/incubator-seata/pull/5914)] upgrade native-lib-loader version
- [[#5960](https://github.com/apache/incubator-seata/pull/5960)] fix zookeeper UT failed
- [[#5981](https://github.com/apache/incubator-seata/pull/5981)] fixed jedis version for `seata-server`

Thanks to these contributors for their code commits. Please report an unintended omission.

<!-- Please make sure your Github ID is in the list below -->
- [slievrly](https://github.com/slievrly)
- [capthua](https://github.com/capthua)
- [funky-eyes](https://github.com/funky-eyes)
- [iquanzhan](https://github.com/iquanzhan)
- [leizhiyuan](https://github.com/leizhiyuan)
- [l81893521](https://github.com/l81893521)
- [PeppaO](https://github.com/PeppaO)
- [wangliang181230](https://github.com/wangliang181230)
- [hsien999](https://github.com/hsien999)

Also, we receive many valuable issues, questions and advices from our community. Thanks for you all.

#### Link

- **Seata:** <https://github.com/apache/incubator-seata>
- **Seata-Samples:** <https://github.com/apache/incubator-seata-samples>
- **Release:** <https://github.com/apache/incubator-seata/releases>
- **WebSite:** <https://seata.io>

</details>
