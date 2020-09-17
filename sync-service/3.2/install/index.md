---
title: Installation overview
---

The Sync Service capability for Desktop Sync is delivered as a distribution zip file containing a repository AMP file, server files for the Sync Service, and third-party license information.

You can download the Alfresco Sync Service software from the [Alfresco Support Portal](https://support.alfresco.com/){:target="_blank"}.

## Prerequisites

This section lists the environment/software prerequisites for installing and using the Sync Service.

See [Supported platforms]({% link sync-service/3.2/support/index.md %}) for more.

### General requirements

* Messaging broker
  * See [Setting up ActiveMQ](https://docs.alfresco.com/6.2/tasks/activemq-install.html)(#LINK) for more information about installing ActiveMQ.

* Make sure that search indexing is [enabled](https://docs.alfresco.com/search-enterprise/concepts/search-home.html)(#LINK).

## Installation options

There are several [options]({% link sync-service/3.2/install/options.md %}) for installing the Sync Service:

* Install manually using a distribution ZIP
* Install using Helm charts or Docker Compose