---
title: Azure SDK for .NET (March 2020)
layout: post
date: March 2020
tags: dotnet
sidebar: releases_sidebar
repository: azure/azure-sdk-for-net
---

The Azure SDK team is pleased to announce our March 2020 client library releases.

#### GA

- Event Hubs
- Key Vault (Certificates)

#### Updates

- Key Vault (Keys, Secrets)
- Storage (Blobs, Blobs Batch, Queues, File Shares, DataLake)

#### Preview

- Text Analytics

## Installation Instructions

To install any of our packages, please search for them via `Manage NuGet Packages...` in Visual Studio (with `Include prerelease` checked) or copy these commands into your terminal:

    $> dotnet add package Azure.AI.TextAnalytics --version 1.0.0-preview.2

    $> dotnet add package Azure.Cosmos --version 4.0.0-preview

    $> dotnet add package Azure.Data.AppConfiguration

    $> dotnet add package Azure.Identity

    $> dotnet add package Azure.Messaging.EventHubs
    $> dotnet add package Azure.Messaging.EventHubs.Processor

    $> dotnet add package Azure.Security.KeyVault.Certificates
    $> dotnet add package Azure.Security.KeyVault.Key
    $> dotnet add package Azure.Security.KeyVault.Secrets

    $> dotnet add package Azure.Storage.Blobs
    $> dotnet add package Azure.Storage.Blobs.Batch
    $> dotnet add package Azure.Storage.Files.DataLake --version 12.0.0-preview.9
    $> dotnet add package Azure.Storage.Files.Shares
    $> dotnet add package Azure.Storage.Queues

## Feedback

If you have a bug or feature request for one of the libraries, please [file an issue in our repo](https://github.com/Azure/azure-sdk-for-net/issues/new/choose).

## Changelog

Detailed changelogs are linked from the [Quick Links](#quick-links) below. Here are some of the highlights:

<!--TODO -->

## Latest Releases

{% assign packages = site.data.releases.latest.dotnet-packages %}
{% include dotnet-packages.html %}

{% include refs.md %}
