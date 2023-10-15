# java-cli-sbt-ssl-postgresql-data-type-hstore

## Description
Creates a small table `dog` that uses
a key value pair data type.

Uses self-sign ssl.

## Tech stack
- java
- sbt
  - log4j
  - postgresql driver

## Docker stack
- alpine:edge
- postgresql:alpine
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[HStore data type info](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-hstore/)
