---
title: Deploy Command Line Interface Tool
description: Understand how the Auth0 Deploy Command Line Interface (CLI) tool works.
topics:
  - extensions
  - deploy-cli
contentType:
  - index
  - concept
useCase: extensibility-extensions
---
# Deploy Command Line Interface Tool

Auth0 supports continuous integration and deployment (CI/CD) of Auth0 tenants through our [source control extensions](/extensions#deploy-hosted-pages-rules-and-database-connections-scripts-from-external-repositories) and integration into existing CI/CD pipelines by using this **auth0-deploy-cli** tool.

The `auth0-deploy-cli` tool supports the importing and exporting of Auth0 tenant configuration data. It supports multiple methods to import and export Auth0 tenant configuration objects to a predefined directory structure or a YAML configuration file. It can be called programmatically. 

The Deploy CLI tool supports the following Auth0 objects:

- Tenant Settings
- Rules (Including Secrets/Settings)
- Connections
- Custom Databases
- Clients / Applications
- Resource Servers (API's)
- Pages
- Email Templates and Provider 
- Guardian Settings

You can also use the tool to replace environment variables. 

::: warning
This tool can be destructive to your Auth0 tenant. Please ensure you have read the documentation and tested the tool on a development tenant before using in production.
:::

## Keep reading

* [Install the Deploy CLI Tool](/extensions/deploy-cli/guides/install-deploy-cli)
* [Upgrade from Deploy CLI v1 to v2](/extensions/deploy-cli/guides/upgrade-v1-v2)
* [Incorporate Deploy CLI into Build Environment](/extensions/deploy-cli/guides/incorporate-deploy-cli-into-build-environment)
* [Import/Export Tenant Configuration to a Directory Structure](/extensions/deploy-cli/guides/import-export-directory-structure)
* [Import/Export Tenant Configuration to a YAML File](/extensions/deploy-cli/guides/import-export-yaml-file)
* [Call Deploy CLI Programmatically](/egtensions/deploy-cli/guides/call-deploy-cli-programmatically)
* [Deploy CLI Tool Options](/extensions/deploy-cli/references/deploy-cli-options)
* [Test Deploy CLI Operations Locally](/extensions/deploy-cli/guides/test-locally)