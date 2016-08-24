### Downloads

Install Lightbend Activator

https://www.lightbend.com/activator/download

On Windows, Add path to bin/ folder to the PATH variable. Open a Git Bash prompt and try the following


```
$ activator
Getting org.fusesource.jansi jansi 1.11 ...
downloading https://repo1.maven.org/maven2/org/fusesource/jansi/jansi/1.11/jansi-1.11.jar ...
        [SUCCESSFUL ] org.fusesource.jansi#jansi;1.11!jansi.jar (136ms)
:: retrieving :: org.scala-sbt#boot-jansi
        confs: [default]
        1 artifacts copied, 0 already retrieved (111kB/24ms)
Getting com.typesafe.activator activator-launcher 1.3.10 ...
downloading https://repo.typesafe.com/typesafe/ivy-releases/com.typesafe.activator/activator-launcher/1.3.10/jars/activator-launcher.jar ...
        [SUCCESSFUL ] com.typesafe.activator#activator-launcher;1.3.10!activator-launcher.jar (1153ms)
downloading https://repo1.maven.org/maven2/org/scala-lang/scala-library/2.11.8/scala-library-2.11.8.jar ...
        [SUCCESSFUL ] org.scala-lang#scala-library;2.11.8!scala-library.jar (1985ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/com.typesafe.activator/activator-props/1.3.10/jars/activator-props.jar ...
        [SUCCESSFUL ] com.typesafe.activator#activator-props;1.3.10!activator-props.jar (1022ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/com.typesafe.activator/activator-ui-common/1.3.10/jars/activator-ui-common.jar ...
        [SUCCESSFUL ] com.typesafe.activator#activator-ui-common;1.3.10!activator-ui-common.jar (1179ms)
downloading https://repo1.maven.org/maven2/org/scala-sbt/launcher-interface/1.0.0-M1/launcher-interface-1.0.0-M1.jar ...
        [SUCCESSFUL ] org.scala-sbt#launcher-interface;1.0.0-M1!launcher-interface.jar (100ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/org.scala-sbt/completion_2.11/0.13.11/jars/completion_2.11.jar ...
        [SUCCESSFUL ] org.scala-sbt#completion_2.11;0.13.11!completion_2.11.jar (1416ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/com.typesafe.activator/activator-templates-cache/1.0-a0afb008ea619bf9d87dc010156cddffa8a6f880/jars/activator-templates-cache.jar ...
        [SUCCESSFUL ] com.typesafe.activator#activator-templates-cache;1.0-a0afb008ea619bf9d87dc010156cddffa8a6f880!activator-templates-cache.jar (1221ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/com.typesafe.activator/activator-common/1.0-a0afb008ea619bf9d87dc010156cddffa8a6f880/jars/activator-common.jar ...
        [SUCCESSFUL ] com.typesafe.activator#activator-common;1.0-a0afb008ea619bf9d87dc010156cddffa8a6f880!activator-common.jar (1207ms)
downloading https://repo1.maven.org/maven2/org/scala-lang/modules/scala-xml_2.11/1.0.1/scala-xml_2.11-1.0.1.jar ...
        [SUCCESSFUL ] org.scala-lang.modules#scala-xml_2.11;1.0.1!scala-xml_2.11.jar(bundle) (318ms)
downloading https://repo1.maven.org/maven2/org/scala-lang/modules/scala-parser-combinators_2.11/1.0.1/scala-parser-combinators_2.11-1.0.1.jar ...
        [SUCCESSFUL ] org.scala-lang.modules#scala-parser-combinators_2.11;1.0.1!scala-parser-combinators_2.11.jar(bundle) (236ms)
downloading https://repo1.maven.org/maven2/org/apache/lucene/lucene-core/4.3.0/lucene-core-4.3.0.jar ...
        [SUCCESSFUL ] org.apache.lucene#lucene-core;4.3.0!lucene-core.jar (832ms)
downloading https://repo1.maven.org/maven2/org/apache/lucene/lucene-analyzers-common/4.3.0/lucene-analyzers-common-4.3.0.jar ...
        [SUCCESSFUL ] org.apache.lucene#lucene-analyzers-common;4.3.0!lucene-analyzers-common.jar (905ms)
downloading https://repo1.maven.org/maven2/org/apache/lucene/lucene-queryparser/4.3.0/lucene-queryparser-4.3.0.jar ...
        [SUCCESSFUL ] org.apache.lucene#lucene-queryparser;4.3.0!lucene-queryparser.jar (232ms)
downloading https://repo1.maven.org/maven2/com/typesafe/akka/akka-actor_2.11/2.3.9/akka-actor_2.11-2.3.9.jar ...
        [SUCCESSFUL ] com.typesafe.akka#akka-actor_2.11;2.3.9!akka-actor_2.11.jar (930ms)
downloading https://repo1.maven.org/maven2/com/amazonaws/aws-java-sdk/1.3.29/aws-java-sdk-1.3.29.jar ...
        [SUCCESSFUL ] com.amazonaws#aws-java-sdk;1.3.29!aws-java-sdk.jar (2852ms)
downloading https://repo1.maven.org/maven2/org/apache/commons/commons-compress/1.4.1/commons-compress-1.4.1.jar ...
        [SUCCESSFUL ] org.apache.commons#commons-compress;1.4.1!commons-compress.jar (168ms)
downloading https://repo1.maven.org/maven2/org/tukaani/xz/1.0/xz-1.0.jar ...
        [SUCCESSFUL ] org.tukaani#xz;1.0!xz.jar (124ms)
downloading https://repo1.maven.org/maven2/org/apache/lucene/lucene-queries/4.3.0/lucene-queries-4.3.0.jar ...
        [SUCCESSFUL ] org.apache.lucene#lucene-queries;4.3.0!lucene-queries.jar (160ms)
downloading https://repo1.maven.org/maven2/org/apache/lucene/lucene-sandbox/4.3.0/lucene-sandbox-4.3.0.jar ...
        [SUCCESSFUL ] org.apache.lucene#lucene-sandbox;4.3.0!lucene-sandbox.jar (112ms)
downloading https://repo1.maven.org/maven2/jakarta-regexp/jakarta-regexp/1.4/jakarta-regexp-1.4.jar ...
        [SUCCESSFUL ] jakarta-regexp#jakarta-regexp;1.4!jakarta-regexp.jar (104ms)
downloading https://repo1.maven.org/maven2/com/typesafe/config/1.2.1/config-1.2.1.jar ...
        [SUCCESSFUL ] com.typesafe#config;1.2.1!config.jar(bundle) (164ms)
downloading https://repo1.maven.org/maven2/commons-logging/commons-logging/1.1.1/commons-logging-1.1.1.jar ...
        [SUCCESSFUL ] commons-logging#commons-logging;1.1.1!commons-logging.jar (112ms)
downloading https://repo1.maven.org/maven2/org/apache/httpcomponents/httpclient/4.1/httpclient-4.1.jar ...
        [SUCCESSFUL ] org.apache.httpcomponents#httpclient;4.1!httpclient.jar (224ms)
downloading https://repo1.maven.org/maven2/commons-codec/commons-codec/1.3/commons-codec-1.3.jar ...
        [SUCCESSFUL ] commons-codec#commons-codec;1.3!commons-codec.jar (120ms)
downloading https://repo1.maven.org/maven2/org/codehaus/jackson/jackson-core-asl/1.8.9/jackson-core-asl-1.8.9.jar ...
        [SUCCESSFUL ] org.codehaus.jackson#jackson-core-asl;1.8.9!jackson-core-asl.jar (236ms)
downloading https://repo1.maven.org/maven2/org/codehaus/jackson/jackson-mapper-asl/1.8.9/jackson-mapper-asl-1.8.9.jar ...
        [SUCCESSFUL ] org.codehaus.jackson#jackson-mapper-asl;1.8.9!jackson-mapper-asl.jar (424ms)
downloading https://repo1.maven.org/maven2/org/apache/httpcomponents/httpcore/4.1/httpcore-4.1.jar ...
        [SUCCESSFUL ] org.apache.httpcomponents#httpcore;4.1!httpcore.jar (152ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/org.scala-sbt/collections_2.11/0.13.11/jars/collections_2.11.jar ...
        [SUCCESSFUL ] org.scala-sbt#collections_2.11;0.13.11!collections_2.11.jar (1381ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/org.scala-sbt/control_2.11/0.13.11/jars/control_2.11.jar ...
        [SUCCESSFUL ] org.scala-sbt#control_2.11;0.13.11!control_2.11.jar (1006ms)
downloading https://repo.typesafe.com/typesafe/ivy-releases/org.scala-sbt/io_2.11/0.13.11/jars/io_2.11.jar ...
        [SUCCESSFUL ] org.scala-sbt#io_2.11;0.13.11!io_2.11.jar (1248ms)
downloading https://repo1.maven.org/maven2/jline/jline/2.13/jline-2.13.jar ...
        [SUCCESSFUL ] jline#jline;2.13!jline.jar (172ms)
:: retrieving :: org.scala-sbt#boot-app
        confs: [default]
        31 artifacts copied, 0 already retrieved (20211kB/172ms)
Getting Scala 2.11.8 (for activator-launcher)...
downloading https://repo1.maven.org/maven2/org/scala-lang/scala-compiler/2.11.8/scala-compiler-2.11.8.jar ...
        [SUCCESSFUL ] org.scala-lang#scala-compiler;2.11.8!scala-compiler.jar (5548ms)
downloading https://repo1.maven.org/maven2/org/scala-lang/scala-reflect/2.11.8/scala-reflect-2.11.8.jar ...
        [SUCCESSFUL ] org.scala-lang#scala-reflect;2.11.8!scala-reflect.jar (1615ms)
downloading https://repo1.maven.org/maven2/org/scala-lang/modules/scala-xml_2.11/1.0.4/scala-xml_2.11-1.0.4.jar ...
        [SUCCESSFUL ] org.scala-lang.modules#scala-xml_2.11;1.0.4!scala-xml_2.11.jar(bundle) (396ms)
downloading https://repo1.maven.org/maven2/org/scala-lang/modules/scala-parser-combinators_2.11/1.0.4/scala-parser-combinators_2.11-1.0.4.jar ...
        [SUCCESSFUL ] org.scala-lang.modules#scala-parser-combinators_2.11;1.0.4!scala-parser-combinators_2.11.jar(bundle) (328ms)
downloading https://repo1.maven.org/maven2/jline/jline/2.12.1/jline-2.12.1.jar ...
        [SUCCESSFUL ] jline#jline;2.12.1!jline.jar (200ms)
:: retrieving :: org.scala-sbt#boot-scala
        confs: [default]
        6 artifacts copied, 0 already retrieved (26456kB/88ms)
 Did not detect an activator project in this directory.
 - activator
 Load an existing project (has to be executed from the project directory)
 or print this help message if no project is found

 Sub-commands
 - activator ui
 Open the project in the UI if executed from an existing project
 directory, otherwise open a project-creation UI.

 - activator new [project-name] [template-name]
 Create a new project, prompting for project-name if missing and helping you
 find a template if template-name is not provided.

 - activator list-templates
 Fetch the latest template list and print it to the console.
```

```sh
$ activator list-templates

Fetching the latest list of templates...

[WARN] [08/24/2016 09:23:42.162] [default-akka.actor.default-dispatcher-4] [ActorSystem(default)] Failed to download new template catalog properties: java.lang.IllegalArgumentException: requirement failed: Source file 'C:\Users\droid\.activator\1.3.10\templates\index.db_295995dd7ddbef2b.tmp' is a directory.
[INFO] [08/24/2016 09:23:42.164] [default-akka.actor.default-dispatcher-4] [akka://default/user/template-cache] We have index hash 8a2285c306189290715965bc7fae4399d0d5c882 but haven't downloaded that index - attempting to download it now.
Featured Seed Templates:
  minimal-akka-java-seed
  minimal-akka-scala-seed
  minimal-java
  minimal-scala
  play-java
  play-scala

Featured Tutorial Templates:
  hello-akka
  hello-scala
  hello-slick-3.0
  reactive-maps
  reactive-stocks

Other Seed Templates:
  akka-http-adaptive-cluster-aws
  akka-http-microservice-quickstart
  akka-scala-seed
  basic-project
  boilerplay
  bootzooka
  cats-seed
  commercetools-sunrise-java
  cs1331-hw
  cs1331-hw-
  finagle-thrift-server-quickstart
  finatra-http-seed
  finatra-seed
  finatra-thrift-seed
  finch-hello-world
  finch-seed
  gilt-lib
  hmrc-frontend
  hw-template
  ismet-scalongo-seed
  japila-play-slick-postgresql-seed
  just-play-java
  just-play-scala
  lagom-java
  libgdx-scala-seed
  mdtp-api-microservice
  mdtp-frontend-microservice
  minimal-akka-java-seed-reactive-platform-15v09
  minimal-akka-scala-seed-reactive-platform-15v09
  minimal-scala-akka-http-seed
  minimal-scala-akka-seed
  minimal-scala-lib-seed
  minimal-scala-project
  minimal-scala-specs2
  minimal-scala-specs2-scalacheck
  minimal-scalismo-seed
  netlogo-extension
  netlogo-java-extension
  netty-akka-template
  play-2.4-crud-with-reactive-mongo
  play-angularjs-webapp-seed
  play-api-rest-seed
  play-framework-scala-seed
  play-heroku-seed
  play-image-processing-classification
  play-java-2.3
  play-java-2.4
  play-java-preview
  play-java-react-seed
  play-java-reactive-platform-15v09
  play-java-service
  play-macwire-di
  play-multidomain-seed
  play-scala-2.3
  play-scala-2.4
  play-scala-preview
  play-scala-reactive-platform-15v09
  play-scala-test
  play-silhouette-angular-seed
  play-silhouette-credentials-seed
  play-silhouette-postgres-async-seed
  play-silhouette-seed
  play-silhouette-seed-slick
  play-silhouette-slick-seed
  play-slick-codegen-flyway-seed
  play-slick-quickstart
  play-swagger-service
  play23-silhouette2-slick2-seed
  playJooq
  playSecureSocial
  reactive-play-scala-akka-slick-guice-domain_validation-seed
  reactive-salesforce-rest-javascript-seed
  salesforce-canvas-seed
  sbt-plugin-seed
  scala-forklift-with-slick-start-seed
  scala-library-seed
  ScalaQualityCodeMultiprojectSeed
  scrupal-activator-seed
  simple-mini-akka-scala-seed
  simple-rest-scala
  siw-template-roma-tre
  slick-play-angularjs-securesocial-seed
  slim-play-scala
  sphere-hello-api-scala-jvm-sdk
  spray-slick-seed
  unfiltered-basic-project
  vamp-project
  webjars-sample-play2

Other Tutorial Templates:
  activator-akka-cassandra
  activator-akka-scala-guice
  activator-akka-scala-parfait
  activator-akka-spray
  activator-akka-tracing
  activator-gilt-app
  activator-offline-test
  activator-play-autosource-reactivemongo
  activator-play-tracing
  activator-scalding
  activator-service-container-tutorial
  activator-spray-twitter
  advance-tweetmap-java8
  afta-collect-tmpl
  afta-compute-tmpl
  afta-distribute-tmpl
  afta-module
  afta-repository-tmpl
  agile-scala-android-example
  akka-callcenter
  akka-camel-cxf-weather
  akka-circuit-breaker-java
  akka-cluster-sharding-scala
  akka-clustering
  akka-custom-dispatcher
  akka-dddd-cqrs
  akka-distributed-workers
  akka-distributed-workers-java
  akka-docker-cluster
  akka-eventuate-scala
  akka-http-demo
  akka-http-microservice
  akka-http-rest
  akka-http-rest-example
  akka-http-slick
  akka-http-websocket-reactive-streams
  akka-java-spring
  akka-monitoring-kamon-statsd
  akka-persistence-event-sourcing
  Akka-Quartz-Scheduler-Application
  akka-realtime-predictor
  akka-sample-camel-java
  akka-sample-camel-java-reactive-platform-15v09
  akka-sample-camel-scala
  akka-sample-camel-scala-reactive-platform-15v09
  akka-sample-cluster-java
  akka-sample-cluster-java-reactive-platform-15v09
  akka-sample-cluster-scala
  akka-sample-cluster-scala-reactive-platform-15v09
  akka-sample-distributed-data-java
  akka-sample-distributed-data-scala
  akka-sample-fsm-java-lambda
  akka-sample-fsm-java-lambda-reactive-platform-15v09
  akka-sample-fsm-scala
  akka-sample-fsm-scala-reactive-platform-15v09
  akka-sample-http-stream
  akka-sample-main-java
  akka-sample-main-java-lambda
  akka-sample-main-java-lambda-reactive-platform-15v09
  akka-sample-main-java-reactive-platform-15v09
  akka-sample-main-scala
  akka-sample-main-scala-reactive-platform-15v09
  akka-sample-multi-node-scala
  akka-sample-multi-node-scala-reactive-platform-15v09
  akka-sample-persistence-java
  akka-sample-persistence-java-lambda
  akka-sample-persistence-scala
  akka-sample-persistent-fsm
  akka-sample-remote-java
  akka-sample-remote-java-reactive-platform-15v09
  akka-sample-remote-scala
  akka-sample-remote-scala-reactive-platform-15v09
  akka-sample-twitter-streaming
  akka-scala-spring
  akka-scheduler
  akka-spray-websocket
  akka-stream-java8
  akka-stream-scala
  akka-supervision
  akka-supervision-java-lambda
  akka-supervision-java-lambda-reactive-platform-15v09
  akka-with-cqrs-eventsourcing
  akka-with-esper
  android-libgdx-rxscala
  angular-seed-play
  angular-seed-play-java
  anonymous-chat
  atomic-scala-examples
  babel-hello
  banner-roulette
  bay-scalajs
  blogdog
  blogimistic
  camel-http
  clustered-chat
  computer-database-java
  computer-database-scala
  config-guice-akka-spray
  dart-akka-spray
  ddd-leaven-akka
  dwws-test1
  eventual
  finagle-quickstart
  finatra-angular-example
  finatra-mysql-seed
  functional-kats-scala-introduction
  graphx-scala
  hazelcast-spray-akka
  hello-akka-java8
  hello-akka-reactive-platform-15v09
  hello-apache-spark
  hello-kafka
  hello-play-2_3-scala
  hello-play-backbone
  hello-play-java
  hello-play-scala
  hello-sbt
  hello-scala-2_11
  hello-scala-eclipse
  hello-scaladin
  hello-scaloid
  hello-slick
  hello-slick-2.1
  hello-slick-3.1
  hello-slick-reactive-platform-15v09
  inno-playground
  jqueryTableContentsPostAndFileDownload
  kastomer
  lagom-java-chirper
  leanovate-scala-schulung
  lolcode-dsl
  lunatech-securesocial-poc
  macroid-akka-pingpong
  macwire-activator
  macwire-akka-activator
  mapsurfer-template
  matthiasn-sse-chat-template
  metrics-visualizer
  microservices-seed-project
  mirror
  modern-web-template
  mytemplate-scala
  nvwa-scala
  play-2.3-highlights
  play-akka-angular-websocket
  play-akka-cluster-sample
  play-angular-require-seed
  play-angular2-typescript
  play-authenticate-mongo
  play-bigpipe-with-rxjava-hystrix
  play-cake
  play-elastic-beanstalk
  play-embedded
  play-entitytled-simple
  play-example-form
  play-guice
  play-hbase
  play-hibernate
  play-ine5646
  play-iteratees
  play-java-dagger-dependency-injection
  play-java-intro
  play-java-intro-preview
  play-java-intro-reactive-platform-15v09
  play-java-spring
  play-java-spring-jinq
  play-js-active
  play-jsmessages
  play-macwire
  play-modular-multiproject
  play-monad-transformers
  play-mongo-knockout
  play-multidomain-auth
  play-oauth-spotify
  play-oauth2-scala
  play-quill-jdbc
  play-reactive-mongo
  play-reactive-mongo-db
  play-reactivemongo-polymer
  play-restfb-jaba
  play-restful-docker
  play-rethinkdb
  play-roca
  play-sbt-layout-seed
  play-scala-angularjs-gulp
  play-scala-backbone-todo
  play-scala-intro
  play-scala-intro-preview
  play-scala-intro-reactive-platform-15v09
  play-scala-rest-elasticsearch
  play-scala-scalajs
  play-scalajs-showcase
  play-scalatest-subcut
  play-simple-web
  play-slick
  play-slick-advanced
  play-slick-angular-test-example
  play-slick-bootstrap3
  play-slick-guice-angular-reactive
  play-slick-rest
  play-slick3-example
  play-spring-data-jpa
  play-sqlite
  play-system-monitor-with-chart-js
  play-tepkin-mongo-example
  play-tls-example
  play-web-portal
  play-web-simple
  play-webrtc
  play-websocket
  play-with-angular
  play-with-appspokes
  play-with-deadbolt-and-auth0
  play-yeoman
  play2-crud-activator
  Play2.3-Spring-PlayAuthenticate-deadbolt2-and-mongo-with-morphia
  play2bars-squeryl
  playing-google-recaptcha
  playing-gravatar
  playing-microservices
  playing-reactive-mongo
  playing-reactjs
  playing-rethinkdb
  PlayStartApp
  rabbitmq-akka-stream
  reactive-fx
  reactive-gen-easymda
  reactive-instruments-workshop
  reactive-java8-play
  reactive-kafka-scala
  reactive-maps-java
  reactive-microservices
  reactive-orientation
  reactive-salesforce-rest-angular-crud
  reactive-scales
  reactive-solar-farm-monitor
  reactive-stocks-java8
  reactive-ticket-booking
  reactive-turtle
  reactive-workshop
  realtime-search
  redis-twitter-clone
  resumable-play-example
  rx_zmq_streams
  salesforce-developer-workshop-java
  sangria-akka-http-example
  sangria-playground
  sbe-scala-example
  sbt-github-project-template
  sbt-jmh-seed
  sbt-native-package-server
  scala-android-preparing-the-environment
  scala-lwjgl
  scala-phantom-types
  scala-testing
  scalacheck-example
  scalajs-play-core
  scalajs-play-core-react
  scalatra-activate-swagger-demo
  scalatra-mongodb-seed
  scaldi-akka-example
  scaldi-play-23-example
  scaldi-play-example
  scalikejdbc-activator-template
  securesocial-slick-bootstrap3-sample
  signalj-chat-java
  signalj-chat-scala
  six-minute-apps
  skalholt
  skinny-orm-in-play
  slick-active-record
  slick-akka-http
  slick-android-example
  slick-codegen-customization-example
  slick-codegen-example
  slick-direct
  slick-direct-2.1
  slick-multidb
  slick-multidb-2.1
  slick-multidb-3.0
  slick-multidb-3.1
  slick-multidb-reactive-platform-15v09
  slick-plainsql
  slick-plainsql-2.1
  slick-plainsql-3.0
  slick-plainsql-3.1
  slick-plainsql-reactive-platform-15v09
  slick-sortable
  slick-starting-on-the-right-foot
  slick-testkit-example
  slick-testkit-example-2.1
  slick-testkit-example-3.0
  slick-testkit-example-3.1
  slick-testkit-example-reactive-platform-15v09
  snakeyard
  spark-in-action
  spark-mllib-scala-play
  spark-play
  spark-sample-project
  spark-streaming-scala
  spark-streaming-scala-akka
  spark-tutorial
  spark-workshop
  spray-actor-per-request
  spray-person
  spray-rest-memcached
  spray-slick-swagger
  spray-spark-react
  spray-swagger-slick3-seed
  sse-chat-template-java
  streams-workshop
  tcp-async
  template-api-rest-java-playframework
  template-template
  test-patterns-scala
  tlh-seed
  tweetmap-java8
  tweetmap-workshop
  typeclass-tips
  typesafe-emojr
  vaadin-in-akka
  widok-skeleton
```

On Ubuntu

```sh
activator-dist-1.3.10/bin$ ./activator
Getting com.typesafe.activator activator-launcher 1.3.10 ...
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/com.typesafe.activator/activator-launcher/1.3.10/jars/activator-launcher.jar ...
	[SUCCESSFUL ] com.typesafe.activator#activator-launcher;1.3.10!activator-launcher.jar (8ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-lang/scala-library/2.11.8/jars/scala-library.jar ...
	[SUCCESSFUL ] org.scala-lang#scala-library;2.11.8!scala-library.jar (61ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/com.typesafe.activator/activator-props/1.3.10/jars/activator-props.jar ...
	[SUCCESSFUL ] com.typesafe.activator#activator-props;1.3.10!activator-props.jar (3ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/com.typesafe.activator/activator-ui-common/1.3.10/jars/activator-ui-common.jar ...
	[SUCCESSFUL ] com.typesafe.activator#activator-ui-common;1.3.10!activator-ui-common.jar (10ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-sbt/completion_2.11/0.13.11/jars/completion_2.11.jar ...
	[SUCCESSFUL ] org.scala-sbt#completion_2.11;0.13.11!completion_2.11.jar (7ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-sbt/collections_2.11/0.13.11/jars/collections_2.11.jar ...
	[SUCCESSFUL ] org.scala-sbt#collections_2.11;0.13.11!collections_2.11.jar (38ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-sbt/control_2.11/0.13.11/jars/control_2.11.jar ...
	[SUCCESSFUL ] org.scala-sbt#control_2.11;0.13.11!control_2.11.jar (3ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-sbt/io_2.11/0.13.11/jars/io_2.11.jar ...
	[SUCCESSFUL ] org.scala-sbt#io_2.11;0.13.11!io_2.11.jar (5ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/jline/jline/2.13/jars/jline.jar ...
	[SUCCESSFUL ] jline#jline;2.13!jline.jar (27ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.fusesource.jansi/jansi/1.11/jars/jansi.jar ...
	[SUCCESSFUL ] org.fusesource.jansi#jansi;1.11!jansi.jar (24ms)
:: retrieving :: org.scala-sbt#boot-app
	confs: [default]
	31 artifacts copied, 0 already retrieved (20211kB/521ms)
Getting Scala 2.11.8 (for activator-launcher)...
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-lang/scala-compiler/2.11.8/jars/scala-compiler.jar ...
	[SUCCESSFUL ] org.scala-lang#scala-compiler;2.11.8!scala-compiler.jar (135ms)
downloading file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/repository/org.scala-lang/scala-reflect/2.11.8/jars/scala-reflect.jar ...
	[SUCCESSFUL ] org.scala-lang#scala-reflect;2.11.8!scala-reflect.jar (78ms)
:: retrieving :: org.scala-sbt#boot-scala
	confs: [default]
	6 artifacts copied, 0 already retrieved (26456kB/79ms)
Unable to open the docs in your web browser.  To open them manually navigate to:
file:/home/droid/software/typesafe-activator/activator-dist-1.3.10/README.html
 Did not detect an activator project in this directory.
 - activator
 Load an existing project (has to be executed from the project directory)
 or print this help message if no project is found

 Sub-commands
 - activator ui
 Open the project in the UI if executed from an existing project
 directory, otherwise open a project-creation UI.

 - activator new [project-name] [template-name]
 Create a new project, prompting for project-name if missing and helping you
 find a template if template-name is not provided.

 - activator list-templates
 Fetch the latest template list and print it to the console.
```

```sh
activator-dist-1.3.10/bin$ ./activator new

Fetching the latest list of templates...

Browse the list of templates: http://lightbend.com/activator/templates
Choose from these featured templates or enter a template name:
  1) minimal-akka-java-seed
  2) minimal-akka-scala-seed
  3) minimal-java
  4) minimal-scala
  5) play-java
  6) play-scala
(hit tab to see a list of all templates)
> 
Display all 457 possibilities? (y or n) 
Akka-Quartz-Scheduler-Application                                  Play2.3-Spring-PlayAuthenticate-deadbolt2-and-mongo-with-morphia   PlayStartApp                                                       
ScalaQualityCodeMultiprojectSeed                                   activator-akka-cassandra                                           activator-akka-scala-guice                                         
activator-akka-scala-parfait                                       activator-akka-spray                                               activator-akka-tracing                                             
activator-gilt-app                                                 activator-kafka-java-producer-consumer                             activator-kafka-scala-producer-consumer                            
activator-longevity-tutorial                                       activator-offline-test                                             activator-play-autosource-reactivemongo                            
activator-play-slick-angularjs                                     activator-play-slick-app                                           activator-play-tracing                                             
activator-scalding                                                 activator-service-container-tutorial                               activator-spray-twitter                                            
advance-tweetmap-java8                                             afta-collect-tmpl                                                  afta-compute-tmpl                                                  
afta-distribute-tmpl                                               afta-module                                                        afta-repository-tmpl                                               
agile-scala-android-example                                        akka-callcenter                                                    akka-camel-cxf-weather                                             
akka-circuit-breaker-java                                          akka-cluster-sharding-scala                                        akka-clustering                                                    
akka-custom-dispatcher                                             akka-dddd-cqrs                                                     akka-distributed-workers                                           
akka-distributed-workers-java                                      akka-docker-cluster                                                akka-eventuate-scala                                               
akka-http-adaptive-cluster-aws                                     akka-http-demo                                                     akka-http-java8-client                                             
akka-http-logging-starter-kit                                      akka-http-microservice                                             akka-http-microservice-quickstart                                  
akka-http-rest                                                     akka-http-rest-example                                             akka-http-slick                                                    
akka-http-slick-guice                                              akka-http-websocket-microservices                                  akka-java-spring                                                   
akka-monitoring-kamon-statsd                                       akka-persistence-event-sourcing                                    akka-realtime-predictor                                            
akka-sample-camel-java                                             akka-sample-camel-java-reactive-platform-15v09                     akka-sample-camel-scala                                            
akka-sample-camel-scala-reactive-platform-15v09                    akka-sample-cluster-java                                           akka-sample-cluster-java-reactive-platform-15v09                   
akka-sample-cluster-scala                                          akka-sample-cluster-scala-reactive-platform-15v09                  akka-sample-distributed-data-java                                  
akka-sample-distributed-data-scala                                 akka-sample-fsm-java-lambda                                        akka-sample-fsm-java-lambda-reactive-platform-15v09                
akka-sample-fsm-scala                                              akka-sample-fsm-scala-reactive-platform-15v09                      akka-sample-http-stream                                            
akka-sample-main-java                                              akka-sample-main-java-lambda                                       akka-sample-main-java-lambda-reactive-platform-15v09               
akka-sample-main-java-reactive-platform-15v09                      akka-sample-main-scala                                             akka-sample-main-scala-reactive-platform-15v09                     
akka-sample-multi-node-scala                                       akka-sample-multi-node-scala-reactive-platform-15v09               akka-sample-persistence-java                                       
akka-sample-persistence-java-lambda                                akka-sample-persistence-scala                                      akka-sample-persistent-fsm                                         
akka-sample-remote-java                                            akka-sample-remote-java-reactive-platform-15v09                    akka-sample-remote-scala                                           
akka-sample-remote-scala-reactive-platform-15v09                   akka-sample-twitter-streaming                                      akka-scala-seed                                                    
akka-scala-spring                                                  akka-scheduler                                                     akka-spray-websocket                                               
akka-stream-java8                                                  akka-stream-scala                                                  akka-supervision                                                   
akka-supervision-java-lambda                                       akka-supervision-java-lambda-reactive-platform-15v09               akka-with-cqrs-eventsourcing                                       
akka-with-esper                                                    akkaHttp-angular2-typescript                                       android-libgdx-rxscala                                             
angular-seed-play                                                  angular-seed-play-java                                             anonymous-chat                                                     
api-first-hand                                                     appspokes-template                                                 atomic-scala-examples                                              
aws-lambda-seed                                                    babel-hello                                                        banner-roulette                                                    
basic-project                                                      bay-scalajs                                                        blogdog                                                            
blogimistic                                                        boilerplay                                                         bootzooka                                                          
camel-http                                                         cats-seed                                                          clustered-chat                                                     
commercetools-sunrise-java                                         computer-database-java                                             computer-database-scala                                            
config-guice-akka-spray                                            cs1331-hw                                                          cs1331-hw-                                                         
dart-akka-spray                                                    ddd-leaven-akka                                                    dwws-test1                                                         
eventual                                                           finagle-quickstart                                                 finagle-thrift-server-quickstart                                   
finatra-angular-example                                            finatra-http-seed                                                  finatra-mysql-seed                                                 
finatra-seed                                                       finatra-thrift-seed                                                finch-hello-world                                                  
finch-seed                                                         functional-kats-scala-introduction                                 gilt-lib                                                           
graphx-scala                                                       hazelcast-spray-akka                                               hello-akka                                                         
hello-akka-java8                                                   hello-akka-reactive-platform-15v09                                 hello-apache-spark                                                 
hello-kafka                                                        hello-play-2_3-scala                                               hello-play-backbone                                                
hello-play-java                                                    hello-play-scala                                                   hello-sbt                                                          
hello-scala                                                        hello-scala-2_11                                                   hello-scala-eclipse                                                
hello-scaladin                                                     hello-scaloid                                                      hello-slick                                                        
hello-slick-2.1                                                    hello-slick-3.0                                                    hello-slick-3.1                                                    
hello-slick-reactive-platform-15v09                                hmrc-frontend                                                      htwg-scala-seed                                                    
hw-template                                                        inno-playground                                                    ismet-scalongo-seed                                                
japila-play-slick-postgresql-seed                                  jqueryTableContentsPostAndFileDownload                             just-play-java                                                     
just-play-scala                                                    kastomer                                                           lagom-java                                                         
lagom-java-chirper                                                 lagom-scala-scalajs-scalatags                                      leanovate-scala-schulung                                           
libgdx-scala-seed                                                  lolcode-dsl                                                        lunatech-securesocial-poc                                          
macroid-akka-pingpong                                              macwire-activator                                                  macwire-akka-activator                                             
mapsurfer-template                                                 matthiasn-sse-chat-template                                        mdtp-api-microservice                                              
mdtp-frontend-microservice                                         metrics-visualizer                                                 microservices-seed-project                                         
minimal-akka-java-seed                                             minimal-akka-java-seed-reactive-platform-15v09                     minimal-akka-scala-seed                                            
minimal-akka-scala-seed-reactive-platform-15v09                    minimal-aws-lambda                                                 minimal-java                                                       
minimal-scala                                                      minimal-scala-akka-http-seed                                       minimal-scala-akka-seed                                            
minimal-scala-lib-seed                                             minimal-scala-project                                              minimal-scala-specs2                                               
minimal-scala-specs2-scalacheck                                    minimal-scalismo-seed                                              mirror                                                             
modern-web-template                                                mytemplate-scala                                                   neo4j-with-scala                                                   
netlogo-extension                                                  netlogo-java-extension                                             netty-akka-template                                                
nvwa-scala                                                         play-2-skeleto-application                                         play-2.3-highlights                                                
play-2.4-crud-with-reactive-mongo                                  play-akka-angular-websocket                                        play-akka-cluster-sample                                           
play-angular-require-seed                                          play-angular2-typescript                                           play-angularjs-webapp-seed                                         
play-api-rest-seed                                                 play-authenticate-mongo                                            play-bigpipe-with-rxjava-hystrix                                   
play-cake                                                          play-elastic-beanstalk                                             play-elasticsearch-autocomplate                                    
play-embedded                                                      play-entitytled-simple                                             play-example-form                                                  
play-framework-scala-seed                                          play-guice                                                         play-hbase                                                         
play-heroku-seed                                                   play-hibernate                                                     play-image-processing-classification                               
play-ine5646                                                       play-iteratees                                                     play-java                                                          
play-java-2.3                                                      play-java-2.4                                                      play-java-dagger-dependency-injection                              
play-java-intro                                                    play-java-intro-preview                                            play-java-intro-reactive-platform-15v09                            
play-java-preview                                                  play-java-react-seed                                               play-java-reactive-platform-15v09                                  
play-java-service                                                  play-java-spring                                                   play-java-spring-jinq                                              
play-js-active                                                     play-jsmessages                                                    play-macwire                                                       
play-macwire-di                                                    play-modular-multiproject                                          play-monad-transformers                                            
play-mongo-knockout                                                play-multidomain-auth                                              play-multidomain-seed                                              
play-ng2-webpack2                                                  play-oauth-spotify                                                 play-oauth2-scala                                                  
play-quill-jdbc                                                    play-react-scalikejdbc-postgres-bootstrap4                         play-reactive-mongo                                                
play-reactive-mongo-db                                             play-reactivemongo-polymer                                         play-restfb-jaba                                                   
play-restful-docker                                                play-rethinkdb                                                     play-roca                                                          
play-sbt-layout-seed                                               play-scala                                                         play-scala-2.3                                                     
play-scala-2.4                                                     play-scala-angularjs-gulp                                          play-scala-backbone-todo                                           
play-scala-intro                                                   play-scala-intro-preview                                           play-scala-intro-reactive-platform-15v09                           
play-scala-preview                                                 play-scala-reactive-platform-15v09                                 play-scala-rest-elasticsearch                                      
play-scala-scalajs                                                 play-scala-scalajs-scalatags                                       play-scala-slickpg-play2auth                                       
play-scala-test                                                    play-scalajs-showcase                                              play-scalatest-subcut                                              
play-silhouette-angular-seed                                       play-silhouette-credentials-seed                                   play-silhouette-postgres-async-seed                                
play-silhouette-seed                                               play-silhouette-seed-slick                                         play-silhouette-slick-seed                                         
play-simple-web                                                    play-slick                                                         play-slick-advanced                                                
play-slick-angular-test-example                                    play-slick-bootstrap3                                              play-slick-codegen-flyway-seed                                     
play-slick-guice-angular-reactive                                  play-slick-oauth2                                                  play-slick-quickstart                                              
play-slick-rest                                                    play-slick3-example                                                play-spring-data-jpa                                               
play-sqlite                                                        play-swagger-service                                               play-system-monitor-with-chart-js                                  
play-tepkin-mongo-example                                          play-tls-example                                                   play-web-portal                                                    
play-web-simple                                                    play-webrtc                                                        play-websocket                                                     
play-with-angular                                                  play-with-appspokes                                                play-with-deadbolt-and-auth0                                       
play-yeoman                                                        play2-crud-activator                                               play23-silhouette2-slick2-seed                                     
play2bars-squeryl                                                  playJooq                                                           playSecureSocial                                                   
playing-google-recaptcha                                           playing-gravatar                                                   playing-microservices                                              
playing-reactive-mongo                                             playing-reactjs                                                    playing-rethinkdb                                                  
primary-scala-scalatest-seed                                       primitive-scala-scalatest-seed                                     quill-async-akka-http                                              
rabbitmq-akka-stream                                               reactive-fx                                                        reactive-gen-easymda                                               
reactive-instruments-workshop                                      reactive-java8-play                                                reactive-kafka-scala                                               
reactive-maps                                                      reactive-maps-java                                                 reactive-microservices                                             
reactive-orientation                                               reactive-play-scala-akka-slick-guice-domain_validation-seed        reactive-salesforce-rest-angular-crud                              
reactive-salesforce-rest-javascript-seed                           reactive-scales                                                    reactive-solar-farm-monitor                                        
reactive-stocks                                                    reactive-stocks-java8                                              reactive-ticket-booking                                            
reactive-turtle                                                    reactive-workshop                                                  realtime-search                                                    
redis-twitter-clone                                                resumable-play-example                                             rx_zmq_streams                                                     
salesforce-canvas-seed                                             salesforce-developer-workshop-java                                 sangria-akka-http-example                                          
sangria-playground                                                 sbe-scala-example                                                  sbt-github-project-template                                        
sbt-jmh-seed                                                       sbt-native-package-server                                          sbt-plugin-seed                                                    
scala-android-preparing-the-environment                            scala-forklift-with-slick-start-seed                               scala-library-seed                                                 
scala-lwjgl                                                        scala-mqtt-client-rasberrypi-starter-kit                           scala-phantom-types                                                
scala-testing                                                      scalacheck-example                                                 scalajs-node-activator-seed                                        
scalajs-play-core                                                  scalajs-play-core-react                                            scalatra-activate-swagger-demo                                     
scalatra-mongodb-seed                                              scalatra-sbt-app                                                   scaldi-akka-example                                                
scaldi-play-23-example                                             scaldi-play-example                                                scalikejdbc-activator-template                                     
scrupal-activator-seed                                             securesocial-slick-bootstrap3-sample                               signalj-chat-java                                                  
signalj-chat-scala                                                 simple-akka-http-websocket-example                                 simple-mini-akka-scala-seed                                        
simple-rest-scala                                                  siw-template-roma-tre                                              six-minute-apps                                                    
skalholt                                                           skinny-orm-in-play                                                 slick-active-record                                                
slick-akka-http                                                    slick-akka-http-oauth2                                             slick-android-example                                              
slick-codegen-customization-example                                slick-codegen-example                                              slick-direct                                                       
slick-direct-2.1                                                   slick-multidb                                                      slick-multidb-2.1                                                  
slick-multidb-3.0                                                  slick-multidb-3.1                                                  slick-multidb-reactive-platform-15v09                              
slick-plainsql                                                     slick-plainsql-2.1                                                 slick-plainsql-3.0                                                 
slick-plainsql-3.1                                                 slick-plainsql-reactive-platform-15v09                             slick-play-angularjs-securesocial-seed                             
slick-sortable                                                     slick-starting-on-the-right-foot                                   slick-testkit-example                                              
slick-testkit-example-2.1                                          slick-testkit-example-3.0                                          slick-testkit-example-3.1                                          
slick-testkit-example-reactive-platform-15v09                      slim-play-scala                                                    snakeyard                                                          
spark-akka-http-couchbase-starter-kit                              spark-in-action                                                    spark-mllib-scala-play                                             
spark-play                                                         spark-sample-project                                               spark-streaming-scala                                              
spark-streaming-scala-akka                                         spark-tutorial                                                     spark-workshop                                                     
sphere-hello-api-scala-jvm-sdk                                     spray-actor-per-request                                            spray-person                                                       
spray-rest-memcached                                               spray-slick-seed                                                   spray-slick-swagger                                                
spray-spark-react                                                  spray-swagger-slick3-seed                                          squbs-java-sample                                                  
squbs-scala-sample                                                 sse-chat-template-java                                             streams-workshop                                                   
tcp-async                                                          template-api-rest-java-playframework                               template-template                                                  
test-patterns-scala                                                tlh-seed                                                           tweetmap-java8                                                     
tweetmap-workshop                                                  typeclass-tips                                                     typesafe-emojr                                                     
unfiltered-basic-project                                           unidirectional-akka-es                                             uss-service                                                        
vaadin-in-akka                                                     vamp-project                                                       webjars-sample-play2                                               
widok-skeleton                                                     
> 
```
