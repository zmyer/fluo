<!--
Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

[![Fluo][logo]][fluo]
---
[![Build Status][ti]][tl] [![Apache License][li]][ll] [![Maven Central][mi]][ml] [![Javadoc][ji]][jl]

[Apache Fluo][fluo] is a distributed processing system that lets users make incremental updates to large
data sets. With Apache Fluo, users can set up workflows that execute cross node transactions when data
changes. These workflows enable users to continuously join new data into large existing data sets without
reprocessing all data. Apache Fluo is built on [Apache Accumulo]. Check out the [Fluo project website][fluo]
for news and general information.

## Getting Started

* Take the [Fluo Tour][tour] if you are completely new to Fluo.
* Read the [Fluo documentation][fluo-docs] to learn how to install Fluo and start a Fluo application
  on a cluster where Accumulo, Hadoop & Zookeeper are running. If you need help setting up these
  dependencies, see the [related projects page][related] for external projects that may help.

[fluo]: https://fluo.apache.org/
[related]: https://fluo.apache.org/related-projects/
[tour]: https://fluo.apache.org/tour/
[Apache Accumulo]: https://accumulo.apache.org
[Percolator]: https://research.google.com/pubs/pub36726.html
[fluo-docs]: https://fluo.apache.org/docs/
[ti]: https://travis-ci.org/apache/fluo.svg?branch=master
[tl]: https://travis-ci.org/apache/fluo
[li]: http://img.shields.io/badge/license-ASL-blue.svg
[ll]: https://github.com/apache/fluo/blob/master/LICENSE
[mi]: https://maven-badges.herokuapp.com/maven-central/org.apache.fluo/fluo-api/badge.svg
[ml]: https://maven-badges.herokuapp.com/maven-central/org.apache.fluo/fluo-api/
[ji]: https://www.javadoc.io/badge/org.apache.fluo/fluo-api.svg
[jl]: http://www.javadoc.io/doc/org.apache.fluo/fluo-api
[logo]: contrib/fluo-logo.png
