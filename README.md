# Elastic-Job - distributed scheduled job solution

# ä¸ªäººåå®¢

[http://www.iocoder.cn](http://www.iocoder.cn/?github)

-------

![](http://www.iocoder.cn/images/common/wechat_mp.jpeg)

> ðððå³æ³¨**å¾®ä¿¡å¬ä¼å·ï¼ãèè¿çåç«¯å°å±ã**æç¦å©ï¼  
> 1. RocketMQ / MyCAT / Sharding-JDBC **ææ**æºç åææç« åè¡¨  
> 2. RocketMQ / MyCAT / Sharding-JDBC **ä¸­ææ³¨éæºç  GitHub å°å**  
> 3. æ¨å¯¹äºæºç ççé®æ¯æ¡çè¨**é½**å°å¾å°**è®¤ç**åå¤ã**çè³ä¸ç¥éå¦ä½è¯»æºç ä¹å¯ä»¥è¯·æå¢**ã  
> 4. **æ°ç**æºç è§£ææç« **å®æ¶**æ¶å°éç¥ã**æ¯å¨æ´æ°ä¸ç¯å·¦å³**ã

-------

* ç¥è¯æçï¼![ç¥è¯æç](http://www.iocoder.cn/images/Architecture/2017_12_29/01.png)

* è°åº¦ä½ä¸ä¸­é´ä»¶ **Elastic-Job-Lite**
    * [ãElastic-Job æºç åæ ââ ä¸ºä»ä¹éè¯» Elastic-Job æºç ï¼ã](http://www.iocoder.cn/Elastic-Job/why-read-Elastic-Job-source-code?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸éç½®ã](http://www.iocoder.cn/Elastic-Job/job-config?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸åå§åã](http://www.iocoder.cn/Elastic-Job/job-init?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸æ§è¡ã](http://www.iocoder.cn/Elastic-Job/job-execute?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ æ³¨åä¸­å¿ã](http://www.iocoder.cn/Elastic-Job/reg-center-zookeeper?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸æ°æ®å­å¨ã](http://www.iocoder.cn/Elastic-Job/job-storage?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ æ³¨åä¸­å¿çå¬å¨ã](http://www.iocoder.cn/Elastic-Job/reg-center-zookeeper-listener?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä¸»èç¹éä¸¾ã](http://www.iocoder.cn/Elastic-Job/election?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸åçç­ç¥ã](http://www.iocoder.cn/Elastic-Job/job-sharding-strategy?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸åçã](http://www.iocoder.cn/Elastic-Job/job-sharding?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸å¤±æè½¬ç§»ã](http://www.iocoder.cn/Elastic-Job/job-failover?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸äºä»¶è¿½è¸ªã](http://www.iocoder.cn/Elastic-Job/job-event-trace?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸çå¬å¨ã](http://www.iocoder.cn/Elastic-Job/job-listener?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ èªè¯æ­ä¿®å¤ã](http://www.iocoder.cn/Elastic-Job/reconcile?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ ä½ä¸çæ§æå¡ã](http://www.iocoder.cn/Elastic-Job/job-monitor?github&1604)
    * [ãElastic-Job-Lite æºç åæ ââ è¿ç»´å¹³å°ã](http://www.iocoder.cn/Elastic-Job/job-console?github&1604)

* è°åº¦ä½ä¸ä¸­é´ä»¶ **Elastic-Job-Cloud**
    * [ãElastic-Job-Cloud æºç åæ ââ ä½ä¸éç½®ã](http://www.iocoder.cn/Elastic-Job/cloud-job-config?github&1605)
    * [ãElastic-Job-Cloud æºç åæ ââ ä½ä¸è°åº¦ï¼ä¸ï¼ã](http://www.iocoder.cn/Elastic-Job/cloud-job-scheduler-and-executor-first?github&1605)
    * [ãElastic-Job-Cloud æºç åæ ââ ä½ä¸è°åº¦ï¼äºï¼ã](http://www.iocoder.cn/Elastic-Job/cloud-job-scheduler-and-executor-second?github&1605)
    * [ãElastic-Job-Cloud æºç åæ ââ æ¬å°è¿è¡æ¨¡å¼ã](http://www.iocoder.cn/Elastic-Job/cloud-local-executor?github&1605)
    * [ãElastic-Job-Cloud æºç åæ ââ ä½ä¸å¤±æè½¬ç§»ã](http://www.iocoder.cn/Elastic-Job/cloud-job-failover?github&1605)
    * [ãElastic-Job-Cloud æºç åæ ââ é«å¯ç¨ã](http://www.iocoder.cn/Elastic-Job/cloud-high-availability?github&1605)

[![Build Status](https://secure.travis-ci.org/dangdangdotcom/elastic-job.png?branch=master)](https://travis-ci.org/dangdangdotcom/elastic-job)
[![Maven Status](https://maven-badges.herokuapp.com/maven-central/com.dangdang/elastic-job/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.dangdang/elastic-job)
[![Coverage Status](https://coveralls.io/repos/dangdangdotcom/elastic-job/badge.svg?branch=master&service=github)](https://coveralls.io/github/dangdangdotcom/elastic-job?branch=master)
[![GitHub release](https://img.shields.io/github/release/dangdangdotcom/elastic-job.svg)](https://github.com/dangdangdotcom/elastic-job/releases)
[![Hex.pm](http://dangdangdotcom.github.io/elastic-job/elastic-job-lite/img/license.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)

# [Elastic-Job-Liteä¸­æä¸»é¡µ](http://dangdangdotcom.github.io/elastic-job/elastic-job-lite) [![GitHub release](https://img.shields.io/badge/release-download-orange.svg)](https://dangdangdotcom.github.io/elastic-job/elastic-job-lite/dist/elastic-job-lite-console-2.1.4.tar.gz)
# [Elastic-Job-Cloudä¸­æä¸»é¡µ](http://dangdangdotcom.github.io/elastic-job/elastic-job-cloud) [![GitHub release](https://img.shields.io/badge/release-download-orange.svg)](https://dangdangdotcom.github.io/elastic-job/elastic-job-cloud/dist/elastic-job-cloud-scheduler-2.1.4.tar.gz)
# [Elastic-Job 1.xä¸­æä¸»é¡µ(å·²åºå¼)](http://dangdangdotcom.github.io/elastic-job/elastic-job-lite-1.x)

# Overview

Elastic-Job is a distributed scheduled job solution. Elastic-Job is composited from 2 independent sub projects: Elastic-Job-Lite and Elastic-Job-Cloud.

Elastic-Job-Lite is a centre-less solution, use lightweight jar to coordinate distributed jobs.
Elastic-Job-Cloud is a Mesos framework which use Mesos + Docker(todo) to manage and isolate resources and processes.

Elastic-Job-Lite and Elastic-Job-Cloud provide unified API. Developers only need code one time, then decide to deploy Lite or Cloud as you want.

# Features

## 1. Elastic-Job-Lite

* Distributed schedule job coordinate
* Elastic scale in and scale out supported
* Failover
* Misfired jobs refire
* Sharding consistently, same sharding item for a job only one running instance
* Self diagnose and recover when distribute environment unstable
* Parallel scheduling supported
* Job lifecycle operation
* Lavish job types
* Spring integrated and namespace supported
* Web console

## 2. Elastic-Job-Cloud
* All Elastic-Job-Lite features included
* Application distributed automatically
* Fenzo based resources allocated elastically
* Docker based processes isolation support (TBD)

# Architecture

## Elastic-Job-Lite

![Elastic-Job-Lite Architecture](http://dangdangdotcom.github.io/elastic-job/elastic-job-lite/img/architecture/elastic_job_lite.png)
***

## Elastic-Job-Cloud

![Elastic-Job-Cloud Architecture](http://dangdangdotcom.github.io/elastic-job/elastic-job-cloud/img/architecture/elastic_job_cloud.png)


# [Release Notes](https://github.com/dangdangdotcom/elastic-job/releases)

# [Roadmap](ROADMAP.md)

# Quick Start

## Elastic-Job-Lite

### Add maven dependency

```xml
<!-- import elastic-job lite core -->
<dependency>
    <groupId>com.dangdang</groupId>
    <artifactId>elastic-job-lite-core</artifactId>
    <version>${lasted.release.version}</version>
</dependency>

<!-- import other module if need -->
<dependency>
    <groupId>com.dangdang</groupId>
    <artifactId>elastic-job-lite-spring</artifactId>
    <version>${lasted.release.version}</version>
</dependency>
```
### Job development

```java
public class MyElasticJob implements SimpleJob {
    
    @Override
    public void execute(ShardingContext context) {
        switch (context.getShardingItem()) {
            case 0: 
                // do something by sharding item 0
                break;
            case 1: 
                // do something by sharding item 1
                break;
            case 2: 
                // do something by sharding item 2
                break;
            // case n: ...
        }
    }
}
```

### Job configuration

```xml
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xmlns:reg="http://www.dangdang.com/schema/ddframe/reg"
    xmlns:job="http://www.dangdang.com/schema/ddframe/job"
    xsi:schemaLocation="http://www.springframework.org/schema/beans
                        http://www.springframework.org/schema/beans/spring-beans.xsd
                        http://www.dangdang.com/schema/ddframe/reg
                        http://www.dangdang.com/schema/ddframe/reg/reg.xsd
                        http://www.dangdang.com/schema/ddframe/job
                        http://www.dangdang.com/schema/ddframe/job/job.xsd
                        ">
    <!--configure registry center -->
    <reg:zookeeper id="regCenter" server-lists="yourhost:2181" namespace="dd-job" base-sleep-time-milliseconds="1000" max-sleep-time-milliseconds="3000" max-retries="3" />

    <!--configure job -->
    <job:simple id="myElasticJob" class="xxx.MyElasticJob" registry-center-ref="regCenter" cron="0/10 * * * * ?"   sharding-total-count="3" sharding-item-parameters="0=A,1=B,2=C" />
</beans>
```

***

## Elastic-Job-Cloud

### Add maven dependency

```xml
<!-- import elastic-job cloud executor -->
<dependency>
    <groupId>com.dangdang</groupId>
    <artifactId>elastic-job-cloud-executor</artifactId>
    <version>${lasted.release.version}</version>
</dependency>
```

### Job development

Same with `Elastic-Job-Lite`

### Job App configuration

```shell
curl -l -H "Content-type: application/json" -X POST -d '{"appName":"yourAppName","appURL":"http://app_host:8080/foo-job.tar.gz","cpuCount":0.1,"memoryMB":64.0,"bootstrapScript":"bin/start.sh","appCacheEnable":true}' http://elastic_job_cloud_host:8899/api/app
```

### Job configuration

```shell
curl -l -H "Content-type: application/json" -X POST -d '{"jobName":"foo_job","appName":"yourAppName","jobClass":"yourJobClass","jobType":"SIMPLE","jobExecutionType":"TRANSIENT","cron":"0/5 * * * * ?","shardingTotalCount":5,"cpuCount":0.1,"memoryMB":64.0,"failover":true,"misfire":true,"bootstrapScript":"bin/start.sh"}' http://elastic_job_cloud_host:8899/api/job/register
```
