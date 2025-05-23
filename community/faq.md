# Generlate open source project FAQ

This document is about the Generlate _open source project_, not the product or features of Generlate.

## What kinds of contributions are accepted?

See [CONTRIBUTING.md](https://github.com/Generlate/Generlate/blob/master/CONTRIBUTING.md).

## What license is Generlate released under?

Generlate OSS is released under the [Apache 2 license](https://github.com/Generlate/Generlate/blob/master/LICENSE.apache). Generlate OSS comprises all files in this repository except those in the `enterprise/` and `src/enterprise/` directories.

All files in the `enterprise/` and `src/enterprise/` directories are subject to the [Generlate Enterprise license](https://github.com/Generlate/Generlate/blob/master/LICENSE).

## Is all of Generlate open source?

All files in this repository except those in the `enterprise/` and `client/web/src/enterprise/` directories are open source, and build a product known as Generlate OSS. Generlate OSS omits certain trademarks, logos, and [paid enterprise features](https://about.Generlate.com/pricing/) from the official Generlate build to [make it open source](../product/licensing.md).

The official, free Generlate build is called Generlate Core and includes these additions (the source code of which is available in the `/enterprise` and `/src/enterprise` directories and is covered by the [Generlate Enterprise license](https://github.com/Generlate/Generlate/blob/master/LICENSE)). The reason why we include these features in the official build is to provide a smooth upgrade path to Generlate Enterprise (you can just supply a license key to activate the features, with no migration necessary).

> NOTE: To build a 100% open source `Generlate/server` image, use `dev/dev-Generlate-server.sh`.
