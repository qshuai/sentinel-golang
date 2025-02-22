<p align="center">
	<img src="https://user-images.githubusercontent.com/9434884/43697219-3cb4ef3a-9975-11e8-9a9c-73f4f537442d.png" alt="Sentinel Logo" width="50%">
<p align="center">
  
# Sentinel: The Sentinel of Your Microservices

![CI](https://github.com/qshuai/sentinel-golang/workflows/CI/badge.svg?branch=master)
[![Build Status](https://travis-ci.org/qshuai/sentinel-golang.svg?branch=master)](https://travis-ci.org/qshuai/sentinel-golang)
[![codecov](https://codecov.io/gh/qshuai/sentinel-golang/branch/master/graph/badge.svg)](https://codecov.io/gh/qshuai/sentinel-golang)
[![Go Report Card](https://goreportcard.com/badge/github.com/qshuai/sentinel-golang)](https://goreportcard.com/report/github.com/qshuai/sentinel-golang)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Gitter](https://badges.gitter.im/alibaba/Sentinel.svg)](https://gitter.im/alibaba/Sentinel)
[![GitHub last commit](https://img.shields.io/github/last-commit/qshuai/sentinel-golang.svg?style=flat-square)](https://github.com/qshuai/sentinel-golang/commits/dev)
[![GitHub repo size](https://img.shields.io/github/repo-size/qshuai/sentinel-golang)](https://github.com/qshuai/sentinel-golang)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/qshuai/sentinel-golang.svg?style=flat-square)](qshuai/sentinel-golang/issues?q=is%3Aissue+is%3Aclosed)

## Introduction

As distributed systems become increasingly popular, the reliability between services is becoming more important than ever before.
Sentinel takes "flow" as breakthrough point, and works on multiple fields including **flow control**,
**circuit breaking** and **system adaptive protection**, to guarantee reliability and resiliency of microservices.

![flow-overview](https://raw.githubusercontent.com/sentinel-group/sentinel-website/master/img/sentinel-flow-index-overview-en.jpg)

Sentinel provides the following features:

- **Rich applicable scenarios**: Sentinel has been wildly used in Alibaba, and has covered almost all the core-scenarios in Double-11 (11.11) Shopping Festivals in the past 10 years, such as “Second Kill” which needs to limit burst flow traffic to meet the system capacity, throttling, circuit breaking for unreliable downstream services, distributed rate limiting, etc.
- **Real-time monitoring**: Sentinel also provides real-time monitoring ability. You can see the runtime information of a single machine in real-time, and pump the metrics to outside metric components like Prometheus.
- **Cloud-native ecosystem**: Sentinel Go provides out-of-box integrations with cloud-native components.

## Documentation

See the [中文文档](https://sentinelguard.io/zh-cn/docs/golang/basic-api-usage.html) for document in Chinese.

See the [Wiki](https://github.com/qshuai/sentinel-golang/wiki) for full documentation, examples, blog posts, and other information.

If you are using Sentinel, please [**leave a comment here**](https://github.com/alibaba/Sentinel/issues/18) to tell us your scenario to make Sentinel better.
It's also encouraged to add the link of your blog post, tutorial, demo or customized components to [**Awesome Sentinel**](https://github.com/alibaba/sentinel-awesome).

## Sub-projects

All integration modules and sub-projects are located in [sentinel-group](https://github.com/sentinel-group).

- [Sentinel Go adapters for frameworks](https://github.com/sentinel-group/sentinel-go-adapters)
- [Sentinel Go dynamic data-source modules](https://github.com/sentinel-group/sentinel-go-datasources)
- [Kubernetes CRD data-source for Sentinel Go](https://github.com/sentinel-group/sentinel-go-datasource-k8s-crd)

## Bugs and Feedback

For bug report, questions and discussions please submit [GitHub Issues](https://github.com/qshuai/sentinel-golang/issues).

## Contributing

Contributions are always welcomed! Please see [CONTRIBUTING](./CONTRIBUTING.md) for detailed guidelines.

You can start with the issues labeled with [`good first issue`](https://github.com/qshuai/sentinel-golang/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

## Communication

- DingTalk Group (钉钉群): 23339422
- [Gitter](https://gitter.im/alibaba/Sentinel)
