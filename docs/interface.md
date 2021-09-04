---
layout: default
title: Interface
nav_order: 4
description: ""
permalink: /interface
---
# Interface

RockKV has two interfaces.
1. HTTP based API for applications.
2. [REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) interface for administration.

## Available Operations

| Operation           | Effect                                                                         |
| ------------------- | ------------------------------------------------------------------------------ |
| `GET key`           | Retrieves the `value` associated with `key` if it exists.                      |
| `SET key value`     | Inserts the key-value pair. (Will overwrite any existing value)                |
| `REPLACE key value` | Replaces the value corresponding to `key` with `value` if `key` already exists.|
| `DELETE key`        | Deletes the key-value pair identified by `key`.                                |