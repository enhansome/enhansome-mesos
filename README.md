# awesome-mesos with stars

Everything about awesome [Apache Mesos](http://mesos.apache.org/).

Share your Mesos :heart: through pull requests :)

What can you expect to see here?

* [Frameworks](#frameworks)
  * [Data Processing](#data-processing)
  * [Storage and Serving](#storage-and-serving)
  * [Machine Learning](#machine-learning)
  * [Service/Meta Schedulers/ PaaS](#servicemeta-schedulers-paas)
  * [Consensus](#consensus)
  * [Continuous Integration](#continuous-integration)
  * [One-off tasks/commands](#one-off-taskscommands)
  * [Tracing](#tracing)
  * [Metric collection, logging and visualization](#metric-collection-logging-and-visualization)
  * [Benchmarking](#benchmarking)
  * [Experimental/Example/Unsorted](#experimentalexampleunsorted)

* [Language Bindings](#language-bindings)

* [Tools](#tools)
  * [Alternative UI/Dashboards](#alternative-uidashboards)
  * [Tools for Mesos Developers](#tools-for-mesos-developers)
  * [Tools for Mesos Framework Developers](#tools-for-mesos-framework-developers)
  * [Command line tools](#command-line-tools)
  * [Vagrant based setups](#vagrant-based-setups)
  * [Docker based setups](#docker-based-setups)
  * [Trace Visualization](#trace-visualization)

* [Deployment](#deployment)
  * [Ansible](#ansible)
  * [Chef](#chef)
  * [Puppet](#puppet)
  * [Babushka](#babushka)
  * [Cloudformation](#cloudformation)
  * [Terraform](#terraform)
  * [Systemd](#systemd)
  * [Shell-scripts](#shell-scripts)
  * [Packaging](#packaging)
  * [Networking](#networking)

* [Monitoring and alerting](#monitoring-and-alerting)

* [Service discovery and Load balancing](#service-discovery-and-load-balancing)

* [Modules](#modules)

* [Platforms and microservice architectures](#platforms-and-microservice-architectures)

* [Other Projects and Integrations](#other-projects-and-integrations)

* [Where to look for more?](#where-to-look-for-more)

## Frameworks

### Data Processing

#### Batch Processing

* [Flink](https://github.com/apache/flink/tree/master/flink-mesos) ⭐ 26,263 | 🐛 381 | 🌐 Java | 📅 2026-08-14
* [Dpark](https://github.com/douban/dpark) ⚠️ Archived
* [Apache Hadoop](https://github.com/mesos/hadoop) ⭐ 176 | 🐛 19 | 🌐 Java | 📅 2022-10-04
* [Apache Spark](https://spark.apache.org/docs/latest/running-on-mesos.html)
* [Apache Hama](http://wiki.apache.org/hama/GettingStartedMesos)

#### Stream/Event Processing

* [Heron](https://github.com/twitter/heron) ⚠️ Archived
* [Apache Storm](https://github.com/mesos/storm) ⭐ 140 | 🐛 27 | 🌐 Java | 📅 2021-08-17
* [Fabric](https://github.com/olacabs/fabric) ⭐ 57 | 🐛 7 | 🌐 Java | 📅 2023-04-13
* [Samza](https://github.com/Banno/samza-mesos) ⚠️ Archived

### Storage and Serving

* [Apache Kafka](https://github.com/mesos/kafka) ⭐ 413 | 🐛 49 | 🌐 Scala | 📅 2018-05-03

* [ElasticSearch](https://github.com/mesos/elasticsearch) ⭐ 240 | 🐛 76 | 🌐 Java | 📅 2017-02-19

* [Apache Cassandra](https://github.com/mesosphere/cassandra-mesos) ⚠️ Archived

* [HDFS](https://github.com/mesosphere/hdfs) ⚠️ Archived (and [HDFS](https://github.com/brugidou/hdfs-mesos) ⭐ 6 | 🐛 0 | 🌐 Java | 📅 2014-06-30 and [HDFS](https://github.com/brndnmtthws/hdfs) ⚠️ Archived)

* [MrRedis - Mesos runs Redis](https://github.com/dhilipkumars/MrRedis) ⚠️ Archived

* [Tachyon](https://github.com/mesosphere/tachyon-mesos) ⚠️ Archived

* [Crate](https://github.com/crate/crate-mesos-framework) ⚠️ Archived

* [Apache Accumulo](https://github.com/aredee/accumulo-mesos) ⭐ 17 | 🐛 4 | 🌐 JavaScript | 📅 2015-10-27

* [Riak](https://github.com/basho-labs/riak-mesos) ⭐ 15 | 🐛 11 | 🌐 Shell | 📅 2017-03-08

* [DataStax](https://github.com/elodina/datastax-enterprise-mesos) ⭐ 14 | 🐛 8 | 🌐 Scala | 📅 2016-05-25

* [Apache Drill](https://github.com/mhausenblas/dromedar) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2015-04-13

* [Phoenix](https://github.com/stealthly/phoenix) ⭐ 6 | 🐛 0 | 🌐 Scala | 📅 2015-08-13

* [Kafaka -> Cassandra mirroring](https://github.com/elodina/stockpile) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2016-04-29

* [Kafka client](https://github.com/elodina/go-kafka-client-mesos) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2016-04-06

* [Hemlock](https://github.com/spacejam/hemlock) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2015-02-25

* [Hypertable](https://code.google.com/p/hypertable/wiki/Mesos)

* [Apache Cotton - MySQL on Mesos](https://wiki.apache.org/incubator/MysosProposal)

* [MongoDB](https://github.com/massenz/mongo_fw)

* [Ceph](https://github.com/Intel-bigdata/ceph-mesos)

* [Apache Ignite](https://apacheignite.readme.io/docs/mesos-deployment)

* ~~memSQL~~

### Machine Learning

* [TensorFlow](https://github.com/douban/tfmesos) ⭐ 191 | 🐛 5 | 🌐 Python | 📅 2023-03-24

### Service/Meta Schedulers/ PaaS

* [ElasticJob](https://github.com/dangdangdotcom/elastic-job) ⭐ 8,210 | 🐛 116 | 🌐 Java | 📅 2026-07-29
* [Chronos](https://github.com/mesos/chronos) ⭐ 4,375 | 🐛 232 | 🌐 Scala | 📅 2022-06-29
* [Marathon](https://github.com/mesosphere/marathon) ⚠️ Archived
* [Singularity](https://github.com/HubSpot/Singularity) ⭐ 826 | 🐛 38 | 🌐 Java | 📅 2023-06-02
* [Kubernetes](https://github.com/mesosphere/kubernetes-mesos) ⚠️ Archived
* [Swan](https://github.com/Dataman-Cloud/swan) ⭐ 405 | 🐛 19 | 🌐 Go | 📅 2018-01-29
* [Cook Scheduler](https://github.com/twosigma/Cook) ⚠️ Archived
* [Myriad - Elastic YARN on Mesos](https://github.com/apache/incubator-myriad) ⭐ 155 | 🐛 20 | 🌐 Java | 📅 2026-05-15
* [Metronome](https://github.com/dcos/metronome) ⭐ 112 | 🐛 29 | 🌐 Scala | 📅 2022-10-05
* [CloudFoundry](https://github.com/mesos/cloudfoundry-mesos) ⭐ 106 | 🐛 7 | 🌐 Go | 📅 2016-03-01
* [Scale](https://github.com/ngageoint/scale) ⭐ 104 | 🐛 96 | 🌐 Python | 📅 2022-01-10
* [Waiter - Runs, manages, and autoscales web services](https://github.com/twosigma/waiter) ⚠️ Archived
* [Apache Aurora](http://aurora.incubator.apache.org/)

### Consensus

* [Etcd](https://github.com/mesosphere/etcd-mesos) ⭐ 67 | 🐛 43 | 🌐 Go | 📅 2017-04-27
* [ZooKeeper](https://github.com/CiscoCloud/exhibitor-mesos-framework) ⭐ 20 | 🐛 3 | 🌐 Scala | 📅 2016-05-18 and [ZooKeeper](https://github.com/elodina/exhibitor-mesos-framework) ⭐ 4 | 🐛 5 | 🌐 Scala | 📅 2016-05-18

### Continuous Integration

* [Jenkins](https://github.com/jenkinsci/mesos-plugin) ⭐ 289 | 🐛 2 | 🌐 Java | 📅 2024-08-09 and [Jenkins](https://github.com/mesosphere/jenkins-mesos) ⚠️ Archived
* [Teamcity Plugin](https://github.com/ankurcha/mesos-teamcity-plugin) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2014-11-17
* [GitLab CI](https://github.com/deric/gitlab-ci-mesos)

### One-off tasks/commands

* [Eremetic](https://github.com/eremetic-framework/eremetic) ⭐ 148 | 🐛 26 | 🌐 Go | 📅 2024-02-01
* [R scripts](https://github.com/MohamedBassem/r-cluster) ⭐ 8 | 🐛 4 | 🌐 HTML | 📅 2016-02-02
* [Sprint](https://github.com/adform/sprint)

### Tracing

* [Zipkin](https://github.com/elodina/zipkin-mesos-framework) ⭐ 31 | 🐛 10 | 🌐 Scala | 📅 2016-02-24

### Metric collection, logging and visualization

* [Logstash](https://github.com/mesos/logstash) ⭐ 69 | 🐛 18 | 🌐 Java | 📅 2017-06-29
* [Kibana](https://github.com/mesos/kibana) ⭐ 26 | 🐛 2 | 🌐 Shell | 📅 2016-04-14
* [Mesos slave metrics -> Kafka](https://github.com/elodina/syscol) ⭐ 20 | 🐛 2 | 🌐 Go | 📅 2016-01-29
* [Construct - Deploy a single task on all agents of the cluster](https://github.com/containersolutions/construct) ⭐ 10 | 🐛 6 | 🌐 Python | 📅 2015-11-06
* [Statsd -> Kafka](https://github.com/stealthly/statsd-mesos-kafka) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2016-02-19 and [Statsd -> Kafka](https://github.com/elodina/statsd-mesos-kafka) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2016-02-19
* [Go based Syslog service](https://github.com/elodina/syslog-service) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2016-04-22 and [Go based Syslog service](https://github.com/CiscoCloud/syslog-service) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2015-06-30

### Benchmarking

* [Hydra](https://github.com/lake-lerna/hydra) ⭐ 13 | 🐛 11 | 🌐 Python | 📅 2020-07-22
* [YCSB](https://github.com/yanglei99/YCSB_Mesos) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2016-12-06

### Experimental/Example/Unsorted

* [Deimos](https://github.com/mesosphere/deimos) ⭐ 250 | 🐛 10 | 🌐 Python | 📅 2019-03-06 (deprecated when native [Docker support](http://mesos.apache.org/documentation/latest/docker-containerizer/) was added to Mesos v0.20)
* [RENDLER](https://github.com/mesosphere/RENDLER) ⚠️ Archived
* [Volt](https://github.com/VoltFramework/volt) ⚠️ Archived
* [Amazon ECS Integration (proof-of-concept)](https://github.com/awslabs/ecs-mesos-scheduler-driver) ⚠️ Archived
* [Portainer](https://github.com/duedil-ltd/portainer) ⚠️ Archived - builds docker images using Mesos cluster
* [Exelixi](https://github.com/ceteri/exelixi) ⚠️ Archived
* [Bitcoin Miner](https://github.com/derekchiang/Mesos-Bitcoin-Miner) ⭐ 92 | 🐛 2 | 🌐 Go | 📅 2017-12-06
* [Example Mesos framework in Java to launch Docker containers](https://github.com/codefutures/mesos-docker-tutorial) ⭐ 71 | 🐛 3 | 🌐 Java | 📅 2014-10-01
* [Gozer](https://github.com/twitter/gozer) ⚠️ Archived - Prototype with low-level go API
* [SSSP](https://github.com/mesosphere/sssp) ⭐ 60 | 🐛 4 | 🌐 Scala | 📅 2015-04-25
* [Mesosaurus](https://github.com/mesosphere/mesosaurus) ⚠️ Archived
* [OwlCrawler](https://github.com/fmpwizard/owlcrawler) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2015-10-01
* [Elastic Sentiment Analysis](https://github.com/mhausenblas/elsa) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2015-03-16
* [Satyr](https://github.com/lensacom/satyr) ⭐ 33 | 🐛 13 | 🌐 Python | 📅 2017-10-19
* [MPI](https://github.com/mesosphere/mesos-hydra) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2014-02-09
* [distcc](https://github.com/mesos/mesos-distcc) ⭐ 27 | 🐛 2 | 🌐 Python | 📅 2016-08-31
* [Example Python Framework](https://github.com/tarnfeld/mesos-python-framework) ⭐ 26 | 🐛 1 | 🌐 Python | 📅 2014-08-28
* [ScaleIO](https://github.com/codedellemc/scaleio-framework) ⭐ 25 | 🐛 9 | 🌐 Go | 📅 2017-02-28
* [Retz](https://github.com/retz/retz) ⭐ 24 | 🐛 25 | 🌐 Java | 📅 2017-12-31
* [pinspider](https://github.com/SwathiMystery/mesos-pinspider) ⭐ 18 | 🐛 0 | 🌐 Java | 📅 2014-12-30
* [Logo Generator](https://github.com/remembertoplay/logo-generator) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2016-01-19
* [Changes Mesos Framework](https://github.com/dropbox/changes-mesos-framework) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2016-11-05
* [Example framework for Apache Mesos Essentials book](https://github.com/dharmeshkakadia/MonteCarloArea) ⭐ 16 | 🐛 0 | 🌐 Java | 📅 2017-07-03
* [openvdc](https://github.com/axsh/openvdc) ⭐ 12 | 🐛 18 | 🌐 Go | 📅 2018-10-09
* [Charmander](https://github.com/att-innovate/charmander-scheduler) ⭐ 9 | 🐛 0 | 🌐 Protocol Buffer | 📅 2015-10-13
* [Anagram Finder](https://github.com/mesosphere/ANAGRAMMER) ⚠️ Archived
* [QoSon](https://github.com/akshshar/QoSon) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2015-08-24
* [JobTree](https://github.com/kellrott/jobTree-mesos) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2014-01-22
* [Jetty](https://github.com/guenter/jetty-mesos) ⭐ 4 | 🐛 0 | 🌐 Scala | 📅 2014-01-13
* [Autoscaling](https://github.com/sammyas/autoscaling) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2014-08-25
* [Checkswarm](https://github.com/mbabineau/checkswarm) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2014-09-05
* [Clojure Example](https://github.com/edpaget/hello-mesos) ⭐ 2 | 🐛 0 | 🌐 Clojure | 📅 2015-06-24
* [Inverse Offer Example Framework](https://github.com/kaysoky/InverseOfferExampleFramework) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2016-06-08
* [SearchYA - simple distributed textual search engine](https://github.com/Dudi119/SearchYA) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2017-11-18
* [Sun Grid Engine](https://github.com/kellrott/grid-framework) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2014-03-22
* [Wraxl](https://github.com/kscherer/wraxl-scheduler) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2016-08-31
* [rexe - Remote Execution tool for Mesos](https://github.com/skytix-dev/rexe) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2018-08-04
* [Closest-pairs in 2D with divide-and-conquer](https://github.com/chenlily/closest-pair) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2015-06-17
* [Chapel Parallel Programming Language](https://github.com/nqn/mesos-chapel)
* [JobServer](http://www.grandlogic.com/content/html_docs/products.shtml#jobserverprod)
* [gasc - Generic Mesos Gang Scheduler for HPC tooling](https://github.com/nqn/gasc)
* [Tiniest Mesos Scheduler in Python](https://gist.github.com/porterjamesj/93e0ba46f0fa6faf660d)
* [Slurm](https://github.com/nqn/slurm-mesos) (deprecated)
* [hippo - Mesos framework for eating tasks off queues](https://github.com/Hobsons/hippo)

## Language Bindings

* [Go](https://github.com/mesos/mesos-go) ⭐ 540 | 🐛 46 | 🌐 Go | 📅 2021-08-05
  * [mesos-go-http](https://github.com/ondrej-smola/mesos-go-http) ⭐ 18 | 🐛 2 | 🌐 Go | 📅 2019-03-02 - HTTP Go
* [JavaScript](https://github.com/tobilg/mesos-framework) ⚠️ Archived
* [Haskell](https://github.com/iand675/hs-mesos) ⭐ 34 | 🐛 0 | 🌐 Haskell | 📅 2015-10-29
* [Erlang](https://github.com/mdevilliers/erlang-mesos) ⭐ 32 | 🐛 3 | 🌐 Erlang | 📅 2018-10-18 with [example framework](https://github.com/mdevilliers/merkxx) ⭐ 3 | 🐛 0 | 🌐 Erlang | 📅 2014-08-27
* [Scala](https://github.com/nokia/mesos-scala-api) ⭐ 22 | 🐛 2 | 🌐 Scala | 📅 2016-09-02
* [Ruby](https://github.com/burke/mesos-ruby) ⚠️ Archived
* [CLR](https://github.com/bcrusu/mesos-clr) ⭐ 8 | 🐛 0 | 🌐 C# | 📅 2016-12-19
* [Perl](https://github.com/mark-5/perl-mesos) ⭐ 7 | 🐛 0 | 🌐 C++ | 📅 2016-09-03
* [Rust](https://github.com/iron-oxide/mesos-rust) ⭐ 7 | 🐛 5 | 🌐 Rust | 📅 2016-04-19
* Java
  * [RxJava](https://github.com/mesosphere/mesos-rxjava) ⚠️ Archived
  * [Framework API](https://github.com/kevints/mesos-framework-api) ⭐ 14 | 🐛 0 | 🌐 Java | 📅 2014-07-19 - Pure JVM
  * [Java](http://mesos.apache.org/api/latest/java/)
  * [Jesos](https://github.com/groupon/jesos) - Pure Java
* Python
  * [Pesos](https://github.com/wickman/pesos) ⭐ 47 | 🐛 16 | 🌐 Python | 📅 2015-10-06 - Pure Python
  * [Python HTTP](https://github.com/osallou/python-mesos-http) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2020-12-16
  * [Pymesos](https://github.com/dangra/pymesos) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2014-09-11
* Clojure
  * [mesomatic](https://github.com/pyr/mesomatic) ⭐ 70 | 🐛 11 | 🌐 Clojure | 📅 2018-07-13
  * [Clojure](https://github.com/dgrnbrg/clj-mesos) ⭐ 30 | 🐛 2 | 🌐 Clojure | 📅 2015-11-05

## Tools

### Alternative UI/Dashboards

* [Mesos UI](https://github.com/Capgemini/mesos-ui) ⭐ 217 | 🐛 47 | 🌐 JavaScript | 📅 2021-12-07
* [Simple Mesos Dasboard](https://github.com/bspaans/simple-mesos-dashboard) ⭐ 7 | 🐛 2 | 🌐 HTML | 📅 2016-01-07
* [Mesos Visualizer](https://github.com/Clever/mesos-visualizer) ⚠️ Archived
* [Mesos UI](https://github.com/triforkse/mesos-ui) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2016-01-18

### Tools for Mesos Developers

* [Example repository for creating Mesos modules](https://github.com/mesos/modules) ⭐ 26 | 🐛 5 | 🌐 C++ | 📅 2021-04-07
* [Xcode Workspace for Apache Mesos](https://github.com/tillt/xcode-mesos) ⭐ 15 | 🐛 2 | 📅 2014-05-21
* [Windows support for Mesos](https://github.com/Microsoft/mesos-log) ⚠️ Archived
* [Docker image for Mesos modules](https://github.com/Bplotka/mesos-modules-dev) ⭐ 2 | 🐛 0 | 📅 2016-02-03

### Tools for Mesos Framework Developers

* [Fenzo - Cross framework pluggable task scheduling library](https://github.com/Netflix/Fenzo) ⚠️ Archived
* [mini-mesos - Testing infrastructure for Mesos frameworks](https://github.com/containersolutions/mini-mesos) ⚠️ Archived
* [Customizable Mesos Executor](https://github.com/allegro/mesos-executor) ⭐ 49 | 🐛 3 | 🌐 Go | 📅 2025-12-05
* [Spring Boot starter for Mesos](https://github.com/containersolutions/mesos-starter) ⭐ 47 | 🐛 15 | 🌐 Java | 📅 2018-09-09
* [Akka Mesos](https://github.com/drexin/akka-mesos) ⚠️ Archived
* [Write a Scala Mesos Framework in 7 Steps](https://github.com/mesosphere/scala-sbt-mesos-framework.g8) ⚠️ Archived
* [JavaScript framework boilerplate](https://github.com/tobilg/mesos-framework-boilerplate) ⚠️ Archived
* [Go-Mesos-Utils](https://github.com/elodina/go-mesos-utils) ⭐ 12 | 🐛 2 | 🌐 Go | 📅 2016-04-22
* [Mesos State Backed Collections](https://github.com/mesosphere/mesos-state-backed-collections) ⚠️ Archived
* [Mesos Go Stateful](https://github.com/huawei-cloudfederation/mesos-go-stateful) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2016-11-18
* [Simple Mesos "Hello world" in scala](https://gist.github.com/guenter/7471695)
* [Mesos Framework SDK](https://github.com/verizonlabs/mesos-framework-sdk)

### Command line tools

* [mesosctl](https://github.com/mesoshq/mesosctl) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2016-10-11
* [mesos-tail](https://github.com/felixb/mesos-tail) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2017-01-04

### Vagrant based setups

* [Playa Mesos](https://github.com/mesosphere/playa-mesos) ⚠️ Archived
* [Vagrant Mesos](https://github.com/everpeace/vagrant-mesos) ⭐ 429 | 🐛 22 | 🌐 Ruby | 📅 2016-06-15
* [Vagrant Mesos](https://github.com/ahunnargikar/vagrant-mesos) ⭐ 122 | 🐛 5 | 🌐 Shell | 📅 2014-07-14
* [Using Atlas](https://github.com/Banno/vagrant-mesos) ⚠️ Archived
* [Mesos CentOS](https://github.com/rasputnik/mesos-centos) ⭐ 7 | 🐛 2 | 🌐 Shell | 📅 2020-02-18
* [CoreOS Mesos Cluster](https://github.com/tobilg/coreos-mesos-cluster) ⚠️ Archived
* [Mesos Marathon Deimos Vagrant](https://github.com/liubin/mesos-marathon-deimos-vagrant) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2016-06-17
* [Vagrant Mesos Development Environment](https://github.com/mdevilliers/vagrant-mesos-development-environment) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2015-11-02
* [Vagrant Deimos](https://github.com/bskaggs/vagrant-deimos) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2014-05-18
* [Vagrant Mesos Spark](https://github.com/aharwood/vagrant-mesos-spark) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2013-11-14
* [Mesos Playground](https://github.com/antonlindstrom/mesos_playground) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2014-03-04

### Docker based setups

* [Fig Mesos](https://github.com/breerly/fig-mesos) ⭐ 69 | 🐛 6 | 📅 2015-12-17
* [Compose Mesos](https://github.com/dontrebootme/compose-mesos) ⚠️ Archived
* [Mesoscope](https://github.com/schibsted/mesoscope) ⭐ 34 | 🐛 1 | 🌐 Shell | 📅 2016-09-18
* [Docker Mesos](https://github.com/yaronr/docker-mesos) ⭐ 25 | 🐛 2 | 🌐 Shell | 📅 2014-09-09
* [Mesos workshop](https://github.com/datastrophic/mesos-workshop) ⭐ 24 | 🐛 0 | 🌐 Scala | 📅 2016-06-13
* [Mesos Docker containers](https://github.com/datastrophic/mesos-docker-containers) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2018-03-02

### Trace Visualization

* [Mesos tracing](https://github.com/mesosphere/mesos-tracing) ⚠️ Archived
* [Mesos traces vis](https://github.com/tnachen/mesos_traces_vis) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2015-07-08

## Deployment

### Ansible

* [Ansible Mesos](https://github.com/AnsibleShipyard/ansible-mesos) ⭐ 167 | 🐛 3 | 📅 2018-02-19
* [Anisble Marathon](https://github.com/AnsibleShipyard/ansible-marathon) ⭐ 37 | 🐛 3 | 🌐 Shell | 📅 2018-10-18
* [Ansible Mesos cluster](https://github.com/frankhinek/ansible-mesos-cluster) ⭐ 20 | 🐛 1 | 📅 2015-08-10
* [Anisble Mesos Docker](https://github.com/AnsibleShipyard/ansible-mesos-docker) ⭐ 9 | 🐛 0 | 📅 2015-12-16
* [Deploy apps on marathon from ansible](https://github.com/Topface/ansible-marathon_app) ⭐ 8 | 🐛 3 | 📅 2019-03-18
* [roger-mesos with Bamboo](https://github.com/seomoz/roger-mesos) ⚠️ Archived
* [Ansible Chronos](https://github.com/AnsibleShipyard/ansible-chronos) ⭐ 6 | 🐛 2 | 🌐 Shell | 📅 2017-04-20
* [Ansible Mesos](https://github.com/fupelaqu/ansible-mesos) ⭐ 2 | 🐛 0 | 📅 2014-11-04
* [Ansible MMD](https://github.com/curtisgithub/ansible-mmd) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2014-09-05
* [Ansible Mesos playbook](https://github.com/mhamrah/ansible-mesos-playbook)

### Chef

* [Mesos Cookbook](https://github.com/mdsol/mesos_cookbook) ⚠️ Archived
* [Cookbook Mesos](https://github.com/everpeace/cookbook-mesos) ⭐ 73 | 🐛 4 | 🌐 Ruby | 📅 2015-10-06

### Puppet

* [Puppet Mesos](https://github.com/deric/puppet-mesos) ⭐ 68 | 🐛 3 | 🌐 Ruby | 📅 2020-01-04

### Babushka

* [Mesos Babushka](https://github.com/parolkar/mesos-babushka) ⭐ 6 | 🐛 1 | 🌐 Ruby | 📅 2014-11-05

### Cloudformation

* [Cloudformation Mesos](https://github.com/thefactory/cloudformation-mesos) ⭐ 44 | 🐛 6 | 📅 2015-02-04

### Terraform

* [Terraform Mesos](https://github.com/ContainerSolutions/terraform-mesos) ⚠️ Archived

### Systemd

* [Mesos SystemD](https://github.com/adobe-platform/mesos-systemd) ⭐ 5 | 🐛 6 | 🌐 Shell | 📅 2017-04-07

### Shell-scripts

* [Mesos on Eucalyptus Private Cloud](https://github.com/strat0sphere/spark-euca) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2017-10-07

### Packaging

* [Mesos DEB packaging](https://github.com/mesosphere/mesos-deb-packaging) ⚠️ Archived
* [Mesos DEB packaging](https://github.com/deric/mesos-deb-packaging) ⭐ 31 | 🐛 3 | 🌐 Shell | 📅 2016-05-05
* [RPM Mesos](https://github.com/nmilford/rpm-mesos) ⭐ 7 | 🐛 0 | 📅 2013-08-06
* [Mesos RPM](https://github.com/berngp/mesos-rpm) ⚠️ Archived

### Networking

* [Project Calico](https://github.com/projectcalico/calico-mesos) ⚠️ Archived

## Monitoring and alerting

* [Satellite](https://github.com/twosigma/satellite) ⚠️ Archived
* [Complainer](https://github.com/cloudflare/complainer) ⭐ 81 | 🐛 8 | 🌐 Go | 📅 2026-04-24
* [Docker CollecD Mesos](https://github.com/bobrik/docker-collectd-mesos) ⭐ 55 | 🐛 3 | 🌐 Smarty | 📅 2016-09-19)
* [Prometheus](https://github.com/prometheus/mesos_exporter) ⚠️ Archived
* [marathon-slack](https://github.com/tobilg/marathon-slack) ⚠️ Archived
* [CollecD Mesos task](https://github.com/bobrik/collectd-mesos-tasks) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2019-07-01
* [Mesos InfluxDB Collector](https://github.com/kpacha/mesos-influxdb-collector) ⚠️ Archived
* [Prometheus](https://github.com/wndhydrnt/mesos-task-exporter) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2017-01-21
* [Nagios Mesos](https://github.com/opentable/nagios-mesos)

## Service discovery and Load balancing

* [Bamboo](https://github.com/QubitProducts/bamboo) ⭐ 793 | 🐛 44 | 🌐 Go | 📅 2017-09-28 - Automatically configuring HAProxy for Mesos+Marathon
* [DNS based Service Discovery for Mesos](https://github.com/mesosphere/mesos-dns) ⚠️ Archived
* [Mesos-Consul](https://github.com/CiscoCloud/mesos-consul) ⚠️ Archived and [Service Discovery & Orchestration With Mesos and Consul](http://philzim.com/2014/11/12/service-discovery-orchestration-with-mesos-and-consul/)
* [Marathon-Consul](https://github.com/allegro/marathon-consul) ⭐ 199 | 🐛 21 | 🌐 Go | 📅 2025-10-29 - Register Marathon Tasks as Consul Services for service discovery.
* [Aurproxy](https://github.com/tellapart/aurproxy) ⚠️ Archived
* [Zoidberg](https://github.com/bobrik/zoidberg) ⭐ 60 | 🐛 2 | 🌐 Go | 📅 2017-08-29
* [Automated HAProxy reconfiguration for Marathon](https://github.com/Wizcorp/frontrunner) ⭐ 57 | 🐛 3 | 🌐 JavaScript | 📅 2016-01-08
* [Marathoner](https://github.com/bobrik/marathoner) ⭐ 26 | 🐛 1 | 🌐 Go | 📅 2015-08-25 - Service discovery in Marathon
* [Ralph](https://github.com/bobrik/ralph) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2015-03-01
* [Service Discovery script for Mesos and Marathon](https://github.com/opencredo/mesos_service_discovery) ⚠️ Archived
* [traefik](https://github.com/emilevauge/traefik) ⭐ 11 | 🐛 1 | 🌐 Go | 📅 2026-07-03
* [Sprinter](https://github.com/lasp-lang/sprinter) ⭐ 10 | 🐛 1 | 🌐 Erlang | 📅 2020-02-24
* [roger-bamboo](https://github.com/seomoz/roger-bamboo) ⭐ 5 | 🐛 2 | 🌐 Go | 📅 2019-03-19
* [Surok](https://github.com/Difrex/surok) ⚠️ Archived

## Modules

* [Docker Volume Driver Isolator](https://github.com/emccode/mesos-module-dvdi) ⭐ 77 | 🐛 5 | 🌐 C++ | 📅 2017-05-16
* [Serenity](https://github.com/mesosphere/serenity) ⚠️ Archived
* [Metaswitch](https://github.com/mesosphere/metaswitch-modules) ⚠️ Archived
* [Network Isolator](https://github.com/mesosphere/net-modules) ⚠️ Archived
* [Flocker volumes](https://github.com/ClusterHQ/mesos-module-flocker) ⭐ 50 | 🐛 7 | 🌐 C++ | 📅 2016-12-19
* [Threshold-based Mesos Oversubscription](https://github.com/blue-yonder/mesos-threshold-oversubscription) ⭐ 42 | 🐛 0 | 🌐 C++ | 📅 2019-11-14
* [A customer allocator module](https://github.com/stealthly/alligator) ⭐ 6 | 🐛 2 | 🌐 C++ | 📅 2015-07-03
* [Remote Commands Execution](https://github.com/massenz/execute-module) ⚠️ Archived
* [Allocator module with Offer Filtering](https://github.com/gettyimages/mesos_offer_filtering_allocator_module) ⚠️ Archived

## Platforms and microservice architectures

* [Mantl](https://github.com/CiscoCloud/mantl) ⚠️ Archived
* [PaaSTA](https://github.com/Yelp/paasta) ⭐ 1,730 | 🐛 111 | 🌐 Python | 📅 2026-08-13
* [Apollo](https://github.com/Capgemini/Apollo) ⭐ 718 | 🐛 84 | 🌐 Python | 📅 2021-12-03
* [Peloton from Uber](https://github.com/uber/peloton) ⭐ 647 | 🐛 20 | 🌐 Go | 📅 2023-05-20
* [PanteraS](https://github.com/eBayClassifiedsGroup/PanteraS) ⭐ 200 | 🐛 3 | 🌐 Shell | 📅 2021-10-20 - PanteraS - Platform as a Service in a box
* [Compute platform](https://github.com/sttts/compute-platform) ⭐ 24 | 🐛 1 | 🌐 Shell | 📅 2015-06-17
* [DC/OS](https://dcos.io/)
* [Vamp](http://vamp.io/) - The Very Awesome Microservices Platform
* [Appsoma Welder](https://github.com/appsoma/welder)

## Other projects and Integrations

* [REX-Ray storage orchestration engine](https://github.com/thecodeteam/rexray) ⭐ 2,221 | 🐛 294 | 🌐 Go | 📅 2023-09-02

* [Toil - workflow engine](https://github.com/BD2KGenomics/toil) ⭐ 936 | 🐛 410 | 🌐 Python | 📅 2026-08-13

* [Vamp](https://github.com/magneticio/vamp) ⚠️ Archived

* [Universe](https://github.com/mesosphere/universe) ⚠️ Archived - Mesos package repository

* [Marathon Python](https://github.com/thefactory/marathon-python) ⭐ 196 | 🐛 25 | 🌐 Python | 📅 2020-10-26

* [Ochopod](https://github.com/autodesk-cloud/ochopod) ⭐ 122 | 🐛 9 | 🌐 Python | 📅 2016-03-29

* [Mesos CLI](https://github.com/mesosphere/mesos-cli) ⭐ 116 | 🐛 22 | 🌐 Python | 📅 2017-11-14

* [BigDataScript](https://github.com/pcingola/BigDataScript) ⭐ 92 | 🐛 11 | 🌐 Shell | 📅 2021-03-31

* [Autoscaling Mesos](https://github.com/thefactory/autoscale-python) ⭐ 74 | 🐛 1 | 🌐 Python | 📅 2018-11-22

* [Charmander](https://github.com/att-innovate/charmander) ⭐ 67 | 🐛 4 | 🌐 Shell | 📅 2016-05-30

* [CoreOS Mesos Marathon](https://github.com/veverjak/coreos-mesos-marathon) ⭐ 63 | 🐛 1 | 🌐 Shell | 📅 2014-08-15

* [Sample FluentD on Mesos Docker](https://github.com/riywo/sample-fluentd-on-mesos-docker) ⭐ 54 | 🐛 3 | 🌐 Python | 📅 2013-12-20

* [megos - Go(lang) client library for accessing information of a Apache Mesos cluster](https://github.com/andygrunwald/megos) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2021-06-22

* [Foundry bagrant Mesos Kafka cluster](https://github.com/theclaymethod/Foundry-vagrant-mesos-kafka-cluster) ⭐ 50 | 🐛 2 | 🌐 Shell | 📅 2014-12-03

* [Relay.Mesos](https://github.com/sailthru/relay.mesos) ⚠️ Archived

* [Chronos](https://github.com/cashoefman/chronos) ⭐ 36 | 🐛 0 | 🌐 Shell | 📅 2013-12-10

* [Compose-executor](https://github.com/mohitsoni/compose-executor) ⭐ 36 | 🐛 4 | 🌐 Java | 📅 2016-02-09

* [Chronos utils](https://github.com/mesosphere/chronos-utils) ⚠️ Archived

* [Presto Marathon Docker](https://github.com/sheepkiller/presto-marathon-docker) ⭐ 29 | 🐛 1 | 🌐 Shell | 📅 2018-03-07

* [Dask Mesos backend](https://github.com/lensacom/dask.mesos) ⭐ 28 | 🐛 5 | 🌐 Python | 📅 2017-10-19

* [Mesos BOSHrelease](https://github.com/cf-platform-eng/mesos-boshrelease) ⚠️ Archived

* [Mesos Utils](https://github.com/mesosphere/mesos-utils) ⚠️ Archived

* [Apache Mesos Platform as a Service Deploy](https://github.com/elodina/stack-deploy) ⭐ 21 | 🐛 5 | 🌐 Go | 📅 2016-05-26

* [GoMarathon](https://github.com/jbdalido/gomarathon) ⭐ 20 | 🐛 5 | 🌐 Go | 📅 2020-01-24

* [Triathlon - Marathon wrapper for distributed Mesos cluster selection](https://github.com/schibsted/triathlon) ⚠️ Archived

* [Mesos BOSHrelease](https://github.com/CloudCredo/mesos-boshrelease) ⭐ 19 | 🐛 0 | 🌐 Shell | 📅 2014-08-16

* [Mesosphere pkg](https://github.com/mesosphere/marathon-pkg) ⚠️ Archived

* [deathnode - Gracefully kill Mesos nodes for autoscaling](https://github.com/alanbover/deathnode) ⭐ 17 | 🐛 6 | 🌐 Go | 📅 2018-02-14

* [Marathon Logger](https://github.com/thefactory/marathon-logger) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2014-07-03

* [Mesos on Mesos](https://github.com/mesosphere/mom) ⚠️ Archived

* [OpenStack Kolla](https://github.com/openstack/kolla-mesos) ⚠️ Archived

* [Sample Mesos Executor](https://github.com/mesosphere/sample_mesos_executor) ⚠️ Archived

* [CDH patched for Mesos](https://github.com/mesos/cdh-mesos) ⭐ 13 | 🐛 0 | 🌐 Java | 📅 2011-11-06 - old

* Aurora REST interface - <https://github.com/misho-kr/mesos-aurora-restful> ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2014-11-14 and <https://github.com/smarth-madan/incubator-aurora> ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2015-08-11

* [NixOps Mesos](https://github.com/wmertens/nixops-mesos) ⭐ 11 | 🐛 0 | 🌐 Nix | 📅 2015-03-08

* [Storm Marathon](https://github.com/obaidsalikeen/storm-marathon) ⭐ 11 | 🐛 3 | 🌐 Shell | 📅 2015-01-05

* [Load replaying](https://github.com/stealthly/punxsutawney) ⭐ 10 | 🐛 0 | 🌐 Java | 📅 2015-08-10

* [Spring Cloud Data Flow](https://github.com/spring-cloud/spring-cloud-dataflow-server-mesos) ⚠️ Archived

* [Mesos in Hadoop](https://github.com/mesos/mih) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2011-08-26

* [Mammoth](https://github.com/mohitsoni/mammoth) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2014-03-31

* [Mesos on CoreOS](https://github.com/tnolet/mesos_on_coreos) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2014-08-27

* [Depcon](https://github.com/gondor/depcon) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2016-09-15

* [Docker Marathon](https://github.com/thefactory/docker-marathon) ⭐ 6 | 🐛 0 | 📅 2015-02-20

* [Chronos pkg](https://github.com/mesosphere/chronos-pkg) ⚠️ Archived

* [Weave Mesos Integration](https://github.com/TrentBrown/weave-into-mesos) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2015-12-27

* [Go Mesos Kafka Consumer](https://github.com/elodina/gonzo) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2016-04-24

* [Hecate](https://github.com/jbdalido/hecate) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2014-07-21

* [Magneto](https://github.com/nlamirault/magneto) ⭐ 3 | 🐛 1 | 🌐 Ruby | 📅 2022-01-14

* [VirtualMesos](https://github.com/charlescearl/VirtualMesos) ⭐ 3 | 🐛 0 | 🌐 C++ | 📅 2012-04-16 - old

* [Nix](https://github.com/kamilchm/nix-mesos) ⭐ 3 | 🐛 0 | 🌐 Nix | 📅 2016-10-11

* [PAPI performance counters for Mesos](https://github.com/ct-clmsn/mesos-papi) ⭐ 3 | 🐛 4 | 🌐 C++ | 📅 2017-01-10

* [Mesos Spark](https://github.com/ptorrestr/mesos-spark) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2014-11-19

* [Mesos](https://github.com/jayusor/mesos) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2014-06-22

* <https://github.com/datastrophic/mesos-scaler-ec2> ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2015-10-14

* <https://github.com/tailhook/mesos-tests> ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2015-02-10

* [REPL-MESOS](https://github.com/replme/repl-mesos) ⭐ 2 | 🐛 0 | 🌐 Clojure | 📅 2014-10-29

* [Service Bridge](https://github.com/mesosphere/service-bridge) ⚠️ Archived

* [Packer Mesos](https://github.com/JasonGiedymin/chef-mesos) ⭐ 1 | 🐛 0 | 🌐 Ruby | 📅 2014-12-12

* [Mesos Nerve](https://github.com/ortoo/mesos-nerve) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2013-11-13

* [Vault](https://github.com/jmspring/vault-on-mesos) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2015-11-23

* [JIRA on Mesos](https://github.com/elodina/mesos-jira) ⭐ 1 | 🐛 0 | 📅 2015-05-01

* [Mesos Akaros](https://github.com/alfongj/mesos-akaros) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2014-05-13

* [Packer Mesos](https://github.com/smarthall/packer-mesos) ⚠️ Archived

* [RogerOS](https://github.com/seomoz/roger-mesos-tools) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2019-02-27

* [Docker PAAS](https://github.com/siliconcow/docker_paas) - old

* [Angstrom](https://github.com/nqn/angstrom)

* [supervisor](https://github.com/tnn1t1s/learn-mesos-marathon)

* ~~Dispatch - execute scripts on Mesos cluster~~

* ~~OpenTable Mesoshub~~

* ~~Marvin Scheduler~~

## Where to look for more?

* [MesosCon](http://mesoscon.org)
  * [2014](https://www.youtube.com/playlist?list=PLDVc2EaAVPg9kp8cFzjR1Yxj96I4U5EGN)
  * [2015](https://www.youtube.com/playlist?list=PLVjgeV_avap2arug3vIz8c6l72rvh9poV)
  * [Europe 2015](https://www.youtube.com/watch?v=K-x7yOy8Ymk\&list=PLGeM09tlguZS6MhlSZDbf-gANWdKgje0I)
  * [Seattle 2015](https://www.youtube.com/watch?v=aV6pdWveN7s\&list=PLVjgeV_avap2arug3vIz8c6l72rvh9poV)
  * [North America 2016](https://www.youtube.com/playlist?list=PLGeM09tlguZQVL7ZsfNMffX9h1rGNVqnC)
  * [North America 2017](https://www.youtube.com/playlist?list=PLbzoR-pLrL6qAEnkhkh5tGI6oX_xXD3X4)
* [Mesos User Groups](http://mesos.apache.org/community/user-groups/)
* [Powered By Mesos](http://mesos.apache.org/documentation/latest/powered-by-mesos/)
* [Mesos Community](http://mesos.apache.org/community/)
* [Apache Mesos Youtube Channel](https://www.youtube.com/channel/UC0wxLxgX8ilUn0m31lCpzAw)
* [List of Mesos related conferences & meetups](https://github.com/parolkar/awesome-mesos#related-conferences--meetups) ⭐ 2 | 🐛 0 | 📅 2014-10-19
* [Apache Mesos Essentials book](http://dharmeshkakadia.blogspot.com/2015/06/apache-mesos-essential-is-now-available.html)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
