---
title: Azure SDK for Python (March 2020)
layout: post
date: March 2020
tags: python
sidebar: releases_sidebar
repository: azure/azure-sdk-for-python
---

The Azure SDK team is pleased to make available the March 2020 client library GA release.

This release includes the following:

#### GA


#### Preview

Text Analytics


## Installation Instructions

To install the latest preview version of the packages, copy and paste the following commands into a terminal:

```bash
pip install azure-appconfiguration
pip install --pre azure-eventhub
pip install --pre azure-eventhub-checkpointstoreblob-aio
pip install azure-storage-blob
pip install --pre azure-storage-file-datalake
pip install --pre azure-storage-file-share
pip install azure-storage-queue
pip install azure-keyvault-certificates
pip install azure-keyvault-keys
pip install azure-keyvault-secrets
pip install azure-identity
pip install --pre azure-ai-textanalytics
```

## Feedback

If you have a bug or feature request for one of the libraries, please post an issue to [GitHub](https://github.com/azure/azure-sdk-for-python/issues).

## Changelog

Detailed change logs are linked to in the Quick Links below. Here are some critical call outs.

<!--TODO -->

## Latest Releases

{% assign packages = site.data.releases.latest.python-packages %}
{% include python-packages.html %}

{% include refs.md %}
