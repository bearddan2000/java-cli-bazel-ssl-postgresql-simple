# java-cli-bazel-ssl-postgresql-simple

## Description
A java bazel build, that connects to postgresql database.

Uses self-sign ssl.

## Tech stack
- java
- bazel
  - 6.8.2

## Docker stack
- alpine:edge
- postgresql:alpine
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
