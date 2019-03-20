# Pivotal Application Services Workshops

A collection of workshop labs to learn more about Pivotal Application Services, the Steeltoe Framework, and .NET containerization. Each workshop assumes the cf foundation has Windows cells installed.

## PASW-101

A workshop for a .NET savvy group that wants to learn about `cf push` command and Pivotal App Manager. To push the workshop to PAS, for hosting...

```bash
cf push pasw101-workshop -b staticfile_buildpack -p .\pasw-101\
```

## Steeltoe-Basics

A workshop to continue learning centered around environment variables and their role in cloud-native practices, the Steeltoe Framework and all its goodness, and Pivotal App Manager's integrations with Steeltoe. To push the workshop to PAS, for hosting...

```bash
cf push steeltoe-basics-workshop -b staticfile_buildpack -p .\steeltoe-basics\
```

## Azure-Sql

A workshop utilizing the Microsoft Azure Service Broker for Cloud Foundry and the Steeltoe Framework to use an Azure SQL database as a data store. Grab from the cf marketplace, bind to your app, and off you go! To push the workshop to PAS, for hosting...

```bash
cf push azure-sql-workshop -b staticfile_buildpack -p .\azure-sql\
```

## Steeltoe-Advanced

A workshop using the more advacned features of Steeltoe (service discovery, config server, circuit breakers, etc). To push the workshop to PAS, for hosting...

```bash
cf push steelte-advanced-workshop -b staticfile_buildpack -p .\steeltoe-advanced\
```