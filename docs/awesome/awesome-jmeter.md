<div class="github-widget" data-repo="aliesbelik/awesome-jmeter"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome JMeter [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of resources covering <a href="http://jmeter.apache.org/">Apache JMeter</a> and related stuff and shiny things: plugins, integrations, testing techniques, devops practicies, etc.

[<img src="https://raw.githubusercontent.com/aliesbelik/awesome-jmeter/master/assets/images/jmeter-logo.svg?sanitize=true" align="right" width="260" alt="Apache JMeter">](http://jmeter.apache.org/)

> The [Apache JMeter](http://jmeter.apache.org/) is open source, pure Java application designed to load test functional behavior and measure performance.

This list grew up from [an occasional answer](https://sqa.stackexchange.com/a/2552/1842) on Stack Exchange and personal JMeter-related links collection, got further inspiration from [awesome](https://github.com/sindresorhus/awesome) project and improved by these [amazing contributors](https://github.com/aliesbelik/awesome-jmeter/blob/master/CONTRIBUTORS.md).



## Official Resources

- [Apache JMeter Project](https://jmeter.apache.org/) - Apache JMeter official website.
- [GitHub Repository](https://github.com/apache/jmeter) - Apache JMeter source code repository.
- [JMeter Wiki](https://cwiki.apache.org/confluence/display/jmeter) - Apache JMeter official documentation.
- [Issue Tracking](https://jmeter.apache.org/issues.html) - Apache JMeter issue tracking system.
- [Mailing Lists](http://jmeter.apache.org//mail2.html) - Apache JMeter mailing lists.

## Distributions

- [Download Apache JMeter](http://jmeter.apache.org/download_jmeter.cgi) - Apache JMeter: Official downloads.
- [JMeter for Windows](https://sourceforge.net/projects/jmeterforwindows/) - Package for installation JMeter with plugins.
- [JMeter Bootstrap](https://github.com/cfpb/jmeter-bootstrap) - Solution to setup JMeter and JMeter plugins, suitable to be used as a submodule.

## Getting Started

- [Getting Started with Apache JMeter](https://dzone.com/refcardz/getting-started-with-apache-jmeter)
- [A Simple Load Test with JMeter](https://www.urbaninsight.com/article/simple-load-test-with-jmeter)
- [Performance testing with JMeter](https://www.atlassian.com/blog/archives/performance_testing_with_jmete)

## Tutorials

- [JMeter Tutorials](https://artoftesting.com/jmeter-tutorial)
- [Load Testing your Applications with Apache JMeter](http://www.jguru.com/article/server-side/load-testing-with-apache-jmeter.html) - By Keld H. Hansen.
- Load Testing with JMeter:
  - [part 1](https://lincolnloop.com/blog/2011/sep/21/load-testing-jmeter-part-1-getting-started/) - Getting started.
  - [part 2](https://lincolnloop.com/blog/2011/oct/12/load-testing-jmeter-part-2-headless-testing-and-je/) - Headless testing and Jenkins integration.
  - [part 3](https://lincolnloop.com/blog/2012/sep/19/load-testing-jmeter-part-3-replaying-apache-logs/) - Replaying Apache logs.
- [Concurrent, High Throughput Performance Testing with JMeter](https://planet.jboss.org/post/concurrent_high_throughput_performance_testing_with_jmeter)
- [Functional Testing with JMeter](https://hub.packtpub.com/functional-testing-jmeter/)
- [JMeter Resources](https://resources.infosecinstitute.com/search/?s=jmeter)
- [JMeter Tutorial](https://www.tutorialspoint.com/jmeter/)
- [JMeter Tutorial for Load Testing: The Ultimate Guide](https://www.javacodegeeks.com/2014/11/jmeter-tutorial-load-testing.html)
- [RESTful API testing with JMeter](https://www.ibm.com/developerworks/cloud/library/cl-jmeter-restful/)
- [How to Hit Your RESTful Web Service Using JMeter](https://crunchify.com/how-to-hit-your-restful-web-service-using-jmeter-perform-a-simple-load-test/)
- [JMeter: Load Development LifeCycle](https://gerardnico.com/jmeter/lifecycle)
- [Load Testing with Apache JMeter](https://www.digitalocean.com/community/tutorial_series/load-testing-with-apache-jmeter)
- [JMeter Tutorial](https://www.guru99.com/jmeter-tutorials.html) - By Guru99.
- [JMeter Series](http://blog.sourcepole.com/2011/01/04/jmeter-series/)

## Best Practices

- [JMeter Official Best Practices](http://jmeter.apache.org/usermanual/best-practices.html)
- [JMeter Best Practices](https://guide.blazemeter.com/hc/en-us/articles/207421405-JMeter-Best-Practices)
- [Optimize JMeter for Large Scale Tests](https://octoperf.com/blog/2017/10/12/optimize-jmeter-for-large-scale-tests/)

## Scripting

- [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance/) - Most popular scripting mechanisms performance comparison.
- [Testing with Groovy](https://static.packt-cdn.com/downloads/Testingwithgroovy.pdf) - Using JMeter and Groovy for load testing.
- [JMeter: забудьте про BeanShell Sampler](https://habr.com/ru/post/250731/) - JMeter: forget about BeanShell Sampler *(Russian)*.

## Automation

### DSL

- [RubyJMeter](https://github.com/flood-io/ruby-jmeter) - A Ruby-based DSL for building JMeter test plans.

### Packages

- [loadtest](https://github.com/tmobile/loadtest) - An R Package for load testing using JMeter.

### Frameworks

- [Lightning](http://automatictester.github.io/lightning/) - Framework to integrate JMeter non-functional tests with CI/CD server.
- [Taurus](https://gettaurus.org/) - Automation-friendly framework for Continuous Testing.

## CI

### Tools & Plugins

- [JMeter Ant Task](https://github.com/jfifield/ant-jmeter) - Ant task to automate running JMeter test plans.
- [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin) - Maven plugin that provides the ability to run JMeter tests as part of the build.
- [Jenkins Performance Plugin](https://plugins.jenkins.io/performance/) - Jenkins plugin to capture reports from JMeter and generate graphic charts with the trend report of performance and robustness.
- [TeamCity Performance Tests Analysis Plugin](https://github.com/jtorgan/jmeter_plugin) - TeamCity plugin to organize simplest performance testing in CI *(no updates more)*.
- Bamboo JMeter Aggregator Plugin: [documentation](https://marketplace.atlassian.com/apps/5902/jmeter-aggregator-for-bamboo), [sources](https://bitbucket.org/atlassian/bamboo-jmeter-plugin) - Bamboo plugin to collect, assert and graph JMeter test results.
- [Sonar JMeter Plugin](https://github.com/SonarQubeCommunity/sonar-jmeter) - Plugin to collect JMeter performance tests results and display in Sonar dashboard *(deprecated)*.
- [Lightning](http://automatictester.github.io/lightning/) - Framework to integrate JMeter non-functional tests with CI/CD server.
- [Taurus](https://gettaurus.org/) - Automation-friendly framework for Continuous Testing.

### Tutorials & Demo

- Jenkins
  - [Automated performance testing using JMeter and Maven](https://www.atlassian.com/blog/archives/automated_performance_testing_using_jmeter_and_maven)
  - [Performance Tests with JMeter, Maven and Hudson](https://medium.com/the-server-labs/performance-tests-with-jmeter-maven-and-hudson-d1cbdb3ffad8)
  - [CI with Jenkins, Git, Maven, Grunt, and JMeter](https://github.com/dzuluagaapigee/apigee-ci-jenkins-git-maven-jmeter)
  - [Continuous automated web tests using Jenkins and JMeter](https://www.linkedin.com/pulse/continuous-automated-web-tests-using-jenkins-jmeter-mahanta)
  - [Automating JMeter tests with Maven and Jenkins](https://blog.codecentric.de/en/2014/01/automating-jmeter-tests-maven-jenkins/)
  - How to automate JMeter tests with Maven and Jenkins:
    - [part 1](https://ribblescode.wordpress.com/2012/04/16/how-to-run-jmeter-tests-with-maven/)
    - [part 2](https://ribblescode.wordpress.com/2012/04/16/how-to-automate-jmeter-tests-with-maven-and-jenkins-hudson-8/)
  - JMeter Continuous Performance Testing (JMeter + Ant + Jenkins):
    - [part 1](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part1/)
    - [part 2](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part2/)
  - [Continuous Integration 101: How to Run JMeter with Jenkins](https://www.blazemeter.com/blog/continuous-integration-101-how-run-jmeter-jenkins/)
- Bamboo
  - [How to Run JMeter in a Continuous Integration Environment with Bamboo](https://www.blazemeter.com/blog/how-run-jmeter-continuous-integration-environment-bamboo/)
- TeamCity
  - [How to Run JMeter Tests with TeamCity for Continuous Integration](https://www.blazemeter.com/blog/how-run-jmeter-tests-teamcity-continuous-integration/)
- CircleCI
  - [How to integrate JMeter into CircleCI](https://www.blazemeter.com/blog/how-to-integrate-jmeter-into-circleci/)
- SonarQube
  - [JMeter with Sonar](http://testersinaction.blogspot.com/2013/05/v-behaviorurldefaultvmlo_24.html)

## Distributed Testing

- [JMeter Distributed Testing Step-by-step](http://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.pdf)
- [JMeter Remote Testing](http://jmeter.apache.org/usermanual/remote-test.html)
- [Setting up a JMeter Cluster for web server load testing](https://www.howtoforge.com/setting-up-jmeter-cluster-for-load-testing/)
- Dockerized
  - [Dockerized JMeter](https://gist.github.com/hhcordero/abd1dcaf6654cfe51d0b) - Distributed load testing workflow with Docker and JMeter.
  - [JMeter Docker Images](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=jmeter&starCount=0)
  - [Distributed JMeter testing using Docker](http://srivaths.blogspot.com/2014/08/distrubuted-jmeter-testing-using-docker.html)
  - [A Docker solution to JMeter + InfluxDB + Grafana performance testing](https://medium.com/@ellenhuang523/a-docker-solution-to-jmeter-influxdb-grafana-performance-testing-568848de7a0f)
- Testing in Cloud
  - Amazon Web Services
    - [jmeter-ec2](https://github.com/oliverlloyd/jmeter-ec2/) - Automates running Apache JMeter on Amazon EC2.
    - [gee](https://github.com/kowalcj0/gee) - A modified version of JMeter-EC2 project.
    - [Load Testing with JMeter and Amazon EC2](https://medium.com/@alttaf/load-testing-with-jmeter-and-amazon-ec2-e143a7350596)
    - [Performance Testing in the Cloud with JMeter & AWS](http://web.archive.org/web/20190526033436/http://www.artofsoftwaredevelopment.com/performance/performance-testing-in-the-cloud-with-jmeter-aws)
    - [JMeter distributed testing with Amazon EC2](https://vedovini.net/2009/08/17/jmeter-distributed-testing-with-amazon-ec2/)
  - DigitalOcean
    - [Lightweight JMeter Cloud](https://docs.google.com/presentation/d/1Yi5C27C3Q0AnT-uw9SRnMeEqXSKLQ8h9O9Jqo1gQiyI/) - Building your own JMeter Cloud using Digital Ocean, JMeter and Docker.

## Cloud Services / SaaS

*List of cloud-based load testing services with support of JMeter test plans execution.*

- [CA BlazeMeter](https://www.blazemeter.com/) - Performance engineering platform with JMeter and Selenium support.
- [OctoPerf](https://octoperf.com/) - Saas and On-Premise Load Testing Tool with JMeter and Selenium support.
- [Tricentis Flood](https://flood.io/) - Load testing service with JMeter, Gatling and Selenium scenarios support.
- [RedLine13](http://redline13.com/) - AWS-based load testing service with JMeter, Gatling and Selenium scenarios support.
- [LoadRunner Cloud](https://www.microfocus.com/en-us/products/loadrunner-cloud/overview) - Micro Focus cloud-based solution for web and mobile performance testing with JMeter and Gatling support (formerly HP StormRunner Load).
- [Loadster](https://loadster.app/) - Solution for distributes load testing of web applications and services.
- [Loadium](https://loadium.com/) - AWS-based load testing service with JMeter and Selenium support.

## Results Processing

### Results Analysis

- [JMeter Report Dashboard](http://jmeter.apache.org/usermanual/generating-dashboard.html)
- [JMeter Log Analysis](https://cwiki.apache.org/confluence/display/jmeter/LogAnalysis) - Suggestions and recipes for JMeter log analysis.
- [Analyzing JMeter Results](http://www.datazoo.de/articles/158/performance-testing-analyzing-jmeter-results)
- [JMeter Result Analysis: The Ultimate Guide](https://octoperf.com/blog/2017/10/19/how-to-analyze-jmeter-results/)
- [BlazeMeter Sense](https://sense.blazemeter.com/) - Service for storing and analysing performance test results.
- [JAnalyser](http://janalyser.com/) - Browser-based results analysis tool.
- [JMeter Result Analysis Plugin](https://github.com/afranken/jmeter-analysis-maven-plugin) - Maven plugin that parses JMeter test results and generates detailed reports with charts.
- [JMeter Results Analyser](https://sourceforge.net/projects/jmstats/) - Web-based application for collating, analysing and reporting JMeter test results.
- DB Result Collectors
  - [JMeter DBCollector Plugin](https://sourceforge.net/projects/jmeterdbcollect/) - Plugin to enable results logging into a database for more effective reporting.
  - [JMeter MySQLCollector Plugin](https://cwiki.apache.org/confluence/display/jmeter/MysqlCollectorPlugin) - Patch to configure listener to log into MySQL database.

### Results Visualisation

- Built-in Reporting
  - [JMeter Report Dashboard](http://jmeter.apache.org/usermanual/generating-dashboard.html) - JMeter supports dashboard report generation to get graphs and statistics from a test plan.
- Using Graphite & Grafana - *TBD*.
- Using InfluxDB & Grafana
  - [Using JMeter with InfluxDB & Grafana](http://www.vinsguru.com/category/influxdb/) - Collection of guides to collect and visualize real-time test-results and server monitoring stats using InfluxDB & Grafana.
  - [How to Use Grafana to Monitor JMeter Non-GUI Results](https://dzone.com/articles/how-to-use-grafana-to-monitor-jmeter-non-gui-resul)
  - Grafana Dashboards
    - [JMeter Load Test Dashboard](https://grafana.com/grafana/dashboards/1152) - By NovaTec-APM.
    - [JMeter Dashboard using Core InfluxdbBackendListenerClient](https://grafana.com/grafana/dashboards/5496) - By Philippe M.
    - [JMeter Dashboard (3.2 and up)](https://grafana.com/grafana/dashboards/3351) - By adrianbanu.
  - [JMeter-InfluxBD-Writer Plugin](https://github.com/NovatecConsulting/JMeter-InfluxDB-Writer) - JMeter plugin to write load test data on-the-fly into InfluxDB.
  - [JMeter Results to InfluxDB](https://github.com/soprasteria/jmeter2influxdb) - Read JMeter results from csv file and put into InfluxDB database.
- Using ELK Stack & Grafana
  - [Using ELK](http://ecmarchitect.com/archives/2014/09/09/3932) - Using Elasticsearch, Logstash, and Kibana to visualize JMeter test results.
  - [JMeter + ElasticSearch Live Monitoring](https://medium.com/@anthony.gauthier325/jmeter-elasticsearch-live-monitoring-c895c843c51e) - Using the ElasticSearch Backend listener and Grafana/Kibana to monitor results in realtime.
  - [JMeter ElasticSearch Backend Listener](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) - JMeter plugin to send test results to an ElasticSearch engine.
- Custom & Outdated
  - [Using Matplotlib & Python](https://www.metaltoad.com/blog/plotting-your-load-test-jmeter) - Plotting JMeter load test results with Matplotlib plotting tool and Python.
  - [Statistical Aggregate Report](http://rubenlaguna.com/wp/better-jmeter-graphs/) - Custom Statistical Aggregate Report listener for enhanced results visualization.
  - [JChav](https://github.com/d6y/jchav) - JMeter Chart History and Visualisation library.
  - JMeter Dashboard: [howto](http://seangkuan.blogspot.com/2015/06/jmeter-dashboard-realtime-monitoring-of.html), [sources](https://github.com/vincentskooi/JMeterDashboard) - Realtime monitoring of JMeter load test.
  - [Using CMDRunner & Powershell](http://performancewebautoamtionother.blogspot.com/2015/12/jmeter-create-graphs-with-cmdrunner.html) - Create JMeter graphs with CMDRunner with powershell parallel execution.

## Performance Testing

### Streaming Protocols

- [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](https://www.ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)
- [Using JMeter to Load Test Live HLS Concurrency of Wowza Streaming Engine](https://www.realeyes.com/blog/wowza-streaming/)
- [How to Load Test HTTP Live Media Streaming (HLS) with JMeter](https://www.blazemeter.com/blog/how-load-test-http-live-media-streaming-hls-jmeter/)
- [Monitoring UX Metrics in HLS Load Testing in JMeter](https://www.blazemeter.com/blog/monitoring-ux-metrics-in-hls-load-testing-in-jmeter/)
- [How to Load Test RTMPT Live Media Streaming with JMeter](https://www.blazemeter.com/blog/how-load-test-rtmpt-live-media-streaming-jmeter/)
- [HLS vs. RTMP Live Streaming Load Testing with JMeter](https://www.blazemeter.com/blog/hls-vs-rtmp-live-streaming-load-testing-with-jmeter/)
- [Load testing HLS with Ruby JMeter](https://flood.io/blog/load-testing-hls-with-ruby-jmeter/)
- HLS JMeter Plugin: [guide v.1](https://www.blazemeter.com/blog/the-new-hls-plugin-for-jmeter-the-complete-guide/), [guide v.2](https://www.blazemeter.com/blog/Introducing-the-HLS-Plugin-2.0/), [sources](https://github.com/Blazemeter/HLSPlugin)

### Mobile Apps

- [Record iOS application HTTP requests](http://www.testautomationguru.com/jmeter-record-ios-application-http-requests/)
- [Load Testing Mobile Apps Made Easy](https://www.blazemeter.com/blog/load-testing-mobile-apps-made-easy/)
- [Performance Testing for Native Mobile Apps](https://www.blazemeter.com/blog/view-webcast-performance-testing-native-mobile-apps/)

## APM Integration

*Integration with Application Performance Monitoring (APM) tools to analyze the performance of application servers, database servers, and web services.*

- [Servers Performance Monitoring Plugin](https://jmeter-plugins.org/wiki/PerfMon/) - Server monitoring plugin from [JMeter Plugins](https://jmeter-plugins.org/) project.
- [CA App Synthetic Monitor](https://asm.ca.com/en/feature/transaction-monitoring-web-application-testing.html) - Transaction monitoring & testing solution with JMeter support.
- Dynatrace
  - [Dynatrace and JMeter integration](https://www.dynatrace.com/support/help/setup-and-configuration/integrations/third-party-integrations/test-automation-frameworks/dynatrace-and-jmeter-integration/)
  - [Integrate web API performance monitoring in JMeter](https://www.dynatrace.com/support/doc/appmon/continuous-delivery-test-automation/test-automation-tutorials/integrate-web-api-performance-monitoring-in-jmeter/)
- [JMeter integration with AppDynamics](https://docplayer.net/62851982-Jmeter-integration-with-appdynamics.html) - APM & EUM solution with JMeter integration.
- Performance Remediation using New Relic and JMeter: [part 1](https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-1-3/), [part 2](https://moduscreate.com/blog/performance-remediation-using-new-relic-jmeter-part-2-3/)

## Plugins

- [JMeter Plugins list](https://docs.google.com/spreadsheets/d/1FYMw3zCMr2Y37QCG_vOyC3HyrLxxi7x5I3khWLj3isU/) - List of available plugins and extensions.
- [JMeter Plugins](https://jmeter-plugins.org/) - Independent set of plugins for Apache JMeter, with plugin manager references many plugins and simplifies installation.
- [UBIK Load Pack](https://ubikloadpack.com/) - Productivity extensions for Apache JMeter.

## Extending JMeter

- [JMeter Developer Manual](https://cwiki.apache.org/confluence/display/jmeter/DeveloperManual)
- [How to write a plugin for JMeter](https://jmeter.apache.org/usermanual/jmeter_tutorial.html)
- [How to build a JMeter plugin utilising groovy](https://web.archive.org/web/20180225144718/http://artur.ejsmont.org/blog/content/how-to-build-a-jmeter-plugin-utilising-groovy)
- [How to create a plugin in JMeter](https://stackoverflow.com/questions/20422640/how-to-create-a-plugin-in-jmeter)
- [Custom JMeter Samplers and Config Elements](http://codyaray.com/2014/07/custom-jmeter-samplers-and-config-elements)
- [Implement Custom JMeter Samplers](https://dzone.com/articles/implement-custom-jmeter-samplers)

## IDE Integration

- [Intellij IDEA IDE Plugin](https://plugins.jetbrains.com/plugin/7013-jmeter-plugin) - Create run configurations and run JMeter tests from Intellij IDEA.
- [JMeter + Eclipse HOWTO](https://cwiki.apache.org/confluence/display/jmeter/JMeterAndEclipseHowTo) - Develop the JMeter project with Eclipse IDE.
- [NetBeans JMeter Kit](http://plugins.netbeans.org/plugin/49923/jmeter) - JMeter integration module for NetBeans IDE.
- [Using a Load Generator in NetBeans IDE](https://netbeans.org/kb/docs/java/profile-loadgenerator.html)

## Editors

*Alternative editors for JMX files, in addition to standard JMeter GUI and XML editors.*

- [BlocklyJMX Editor](https://jmeter-plugins.org/editor/) - A Web-based viewer and editor for JMeter test plan files (part of [JMeter Plugins](https://jmeter-plugins.org/) project).
- [JMX Enhancer](https://www.jmxenhancer.com/) - A solution to expedite preparation of JMeter test plans.
- [jmx.js](http://www.vinodkd.org/jmx.js/) - Web-based editor for JMeter JMX files *(no updates more)*.

## JMeter Performance

- [JMeter Performance](https://cwiki.apache.org/confluence/display/jmeter/JMeterPerformance) - JMeter performance evolution across versions.
- [JMeter Performance and Tuning Tips](http://www.ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/) - By UBIK Ingenierie.
- [JMeter Performance and Tuning Tips](https://blazemeter.com/blog/jmeter-performance-and-tuning-tips) - By BlazeMeter.
- [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance/) - Most popular scripting mechanisms performance comparison.

## Tips & Tricks

- [JMeter tips](http://www.webwob.com/html/jmeter_tips.html) - JMeter tips and tricks scratchpad.

## Books

- [Apache JMeter: A Practical Beginner's Guide to Automated Testing and Performance Measurement for Your Websites](http://books.google.com/books?id=nX8oKIEvUcYC) - By Emily H. Halili ([Packt Publishing](https://www.packtpub.com/networking-and-servers/apache-jmeter)).
- [Performance Testing with JMeter 2.9](http://books.google.com/books?id=fpWmv3wPT64C) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/performance-testing-jmeter-29)); guide to test web applications using Apache JMeter with practical, hands-on examples.
- [Performance Testing with JMeter, 2nd Edition](https://books.google.com/books?id=6ditCAAAQBAJ) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/performance-testing-jmeter-second-edition)).
- [Performance Testing with JMeter 3, 3rd Edition](https://books.google.com/books?id=BedDDwAAQBAJ) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/web-development/performance-testing-jmeter-3-third-edition)).
- [JMeter Cookbook](https://books.google.com/books?id=gJUeBQAAQBAJ) - By Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/jmeter-cookbook)); 70 insightful and practical recipes to help successfully use Apache JMeter.
- [JMeter by Example](https://books.google.com/books?id=iWeJDAEACAAJ) - By Sai Matam and Jagdeep Jain ([Leanpub](https://leanpub.com/jmeterbyexample)); a simple, practical, step-by-step tutorial to measure the performance of websites.
- [Pro Apache JMeter: Web Application Performance Testing](https://books.google.com/books?id=YJ4xDwAAQBAJ) - By Sai Matam and Jagdeep Jain ([Apress](https://www.apress.com/gp/book/9781484229606)).
- [Master Apache JMeter: From load testing to DevOps](https://books.google.com/books?id=D_amDwAAQBAJ) - By Antonio Gomes Rodrigues, Bruno Demion (Milamber) and Philippe Mouawad ([Leanpub](https://leanpub.com/master-jmeter-from-load-test-to-devops), [Packt Publishing](https://www.packtpub.com/programming/master-apache-jmeter-from-load-testing-to-devops)).
- [Maîtriser JMeter: Du Test de charge à Devops](http://samples.leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops-sample.pdf) - By Antonio Gomes Rodrigues, Bruno Demion (Milamber) and Philippe Mouawad ([Leanpub](https://leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops)) *(French)*.
- [Advanced JMeter Testing](https://leanpub.com/advanced_jmeter_testing) - By Penny Curich ([Leanpub](https://leanpub.com/advanced_jmeter_testing)), guide to write custom components for Apache JMeter 5.0.

## Trainings & Courses

- [JMeter: Performance and Load Testing](https://www.linkedin.com/learning/jmeter-performance-and-load-testing) - By LinkedIn Learning.
- [JMeter Training Courses](https://www.nobleprog.co.uk/jmeter-training) - By NobleProg.
- [JMeter Training Course](https://info.blazemeter.com/jmeter-training-course) - By BlazeMeter.
- [JMeter Training Academy](https://www.blazemeter.com/university/) - By BlazeMeter.
- [JMeter Courses collection](https://www.udemy.com/courses/search/?q=jmeter) - By Udemy.
- [JMeter Training Course](http://www.absofttrainings.com/jmeter-training-course-and-tutorials/) - By ABSoft Trainings.
- [Web Applications (and Mobile Apps) Performance Testing with JMeter](http://pragmatictestlabs.com/web-applications-mobile-apps-performance-testing-jmeter/) - By Pragmatic Test Labs.
- [Training courses on Load Testing with Apache JMeter](https://www.ubik-ingenierie.com/blog/jmeter-trainings-by-contributors-and-committers/) - By Ubik Ingenierie.
- [Apache JMeter Testing Courses](https://qainsights.com/services/) - By QAInsights.
- [JMeter Getting Started Course](https://www.pluralsight.com/courses/jmeter-getting-started) - By Pluralsight.

## Community

### Blogs

- [BlazeMeter Blog](https://www.blazemeter.com/jmeter/) - BlazeMeter blog about JMeter and performance testing.
- [Ubik Load Pack Blog](http://www.ubik-ingenierie.com/blog/category/jmeter/) - Ubik Ingenierie blog.
- [TestAutomationGuru Blog](http://www.testautomationguru.com/category/jmeter/) - Technical blog on test automation.
- [RedLine13 Blog](https://www.redline13.com/blog/tag/jmeter/) - JMeter articles in RedLine13 blog.
- [Flood.io Blog](https://flood.io/blog/) - Load testing thoughts, stories and ideas from Flood IO.
- [JMeter Blog](https://shantonusarker.blogspot.com/p/jmeter.html) - Another blog for performance & automation testing using JMeter.
- [OctoPerf Blog](https://octoperf.com/categories/jmeter/) - OctoPerf blog about JMeter and load testing.
- [Abstracta JMeter Archives](https://abstracta.us/blog/tag/jmeter/) - Abstracta blog about JMeter.
- [JMeter Tips](http://jmeter-tips.blogspot.com/) - Blog about Apache JMeter and performance testing of web applications *(no updates more)*.
- [JMeter Expert Blog](http://jmeter-expert.blogspot.com/) - JMeterExpert blog *(no updates more)*.

### Forums

- [JMeter Nabble Forum](http://www.jmeter-archive.org/)
- [JMeter SQAforums](http://www.sqaforums.com/postlist.php?Cat=0&Board=UBB54)
- [JMeter - Тестирование производительности](https://software-testing.ru/forum/index.php?/forum/206-jmeter-testirovanie-proizvoditelnosti/) - Discussion board by Software-Testing.ru *(Russian)*.

### Newsletters

- [JMeter Community](https://www.reddit.com/r/jmeter/) - By Reddit.

### Twitter

- [@ApacheJMeter](https://twitter.com/apachejmeter) - Official Twitter account of the Apache JMeter load testing tool.
- [@jmeter_plugins](https://twitter.com/jmeter_plugins) - Twitter account of custom plugins project for JMeter load testing tool.
- [@BlazeMeter](https://twitter.com/BlazeMeter) - Official Twitter account of Blazemeter, performance engineering platform for DevOps, based on JMeter.
- [@masterjmeter](https://twitter.com/masterjmeter) - Official account of the [Master Apache JMeter from Load Testing to DevOps](#books) book.
- [@ubikloadpack](https://twitter.com/ubikloadpack) - Twitter account of [Ubik Load Pack](#plugins), custom JMeter plugins for Video Streaming & complex protocols load testing.

### Q&A

- [JMeter @ Stack Overflow](https://stackoverflow.com/questions/tagged/jmeter)
- [JMeter Slack workspace](https://jmeterusers.slack.com/)
- [JMeter @ gitter](https://gitter.im/aliesbelik/jmeter-chat)

## Related

### Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The original awesome list of awesome lists.
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of amazingly awesome awesomeness.
- [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) - A list of free software testing and verification resources.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
- [Awesome Web Performance Metrics](https://github.com/csabapalfi/awesome-web-performance-metrics) - Metrics to help understand page speed and user experience.
- [Awesome Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo) - A curated list of Web Performance Optimization.
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) - The Patterns of Scalable, Reliable, and Performant Large-Scale Systems.
- [Awesome Site Reliability Engineering](https://github.com/dastergon/awesome-sre) - A curated list of Site Reliability and Production Engineering resources.
- [Awesome inspectIT](https://github.com/inspectit-labs/awesome-inspectit) - Open source Java app performance management tool.

## Contributing

Contributions are welcome!<br>
Please take a look at the [contribution guidelines](https://github.com/aliesbelik/awesome-jmeter/blob/master/CONTRIBUTING.md) first.

## License

<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a>