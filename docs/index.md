---
layout: default
title: File Storage Abstraction for PHP
permalink: /docs/
redirect_from:
    - /
    - /v2/
    - /v2/docs/
---

[![Buy a tree](https://img.shields.io/badge/Buy%20me%20a%20tree-%F0%9F%8C%B3-green)](https://offset.earth/frankdejonge?gift-trees)
[![Author](https://img.shields.io/badge/author-@frankdejonge-blue.svg)](https://twitter.com/frankdejonge)
[![Source Code](https://img.shields.io/badge/source-thephpleague/flysystem-blue.svg)](https://github.com/thephpleague/flysystem)
[![Latest Version](https://img.shields.io/github/tag/thephpleague/flysystem.svg)](https://github.com/thephpleague/flysystem/releases)
[![Software License](https:////img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/thephpleague/flysystem/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/thephpleague/flysystem.svg?branch=v1.0)](https://travis-ci.org/thephpleague/flysystem)
[![Total Downloads](https://img.shields.io/packagist/dt/league/flysystem.svg)](https://packagist.org/packages/league/flysystem)
![php 7.2+](https://img.shields.io/badge/php-min%208.0.2-red.svg)

## About Flysystem

Flysystem is a file storage library for PHP. It provides one interface to
interact with many different types of filesystems. When you use Flysystem, you're
not only protected from vendor lock-in, you'll also have a consistent experience
for which ever storage is right for you. 

## Getting Started

* **[New in V2](/docs/what-is-new/)**: What is new in Flysystem V2/V3?
* **[Architecture](/docs/architecture/)**: Flysystem's internal architecture
* **[Flysystem API](/docs/usage/filesystem-api/)**: How to interact with your Flysystem instance
* **[Upgrade from 1x](/docs/upgrade-from-1.x/)**: How to upgrade from 2.x

### Officially supported adapters

* **[Local](/docs/adapter/local/)**
* **[FTP](/docs/adapter/ftp/)**
* **[SFTP](/docs/adapter/sftp-v3/)**
* **[Memory](/docs/adapter/in-memory/)**
* **[AWS S3](/docs/adapter/aws-s3-v3/)**
* **[AsyncAws S3](/docs/adapter/async-aws-s3/)**
* **[Google Cloud Storage](/docs/adapter/google-cloud-storage/)**
* **[Azure Blob Storage](/docs/adapter/azure-blob-storage/)**
* **[WebDAV](/docs/adapter/webdav/)**
* **[ZipArchive](/docs/adapter/zip-archive/)**

### Third party Adapters

* **[Gitlab](/docs/adapter/gitlab/)**
* **[Google Drive (using regular paths)](https://github.com/masbug/flysystem-google-drive-ext)**
* **[bunny.net / BunnyCDN](https://github.com/PlatformCommunity/flysystem-bunnycdn/tree/v3)**
* **[Sharepoint 365 / One Drive (Using MS Graph)](https://github.com/shitware-ltd/flysystem-msgraph)**
* **[OneDrive](https://github.com/doerffler/flysystem-onedrive)**

You can always [create an adapter](/docs/advanced/creating-an-adapter/) yourself.
