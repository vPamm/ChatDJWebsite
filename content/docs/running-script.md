---
weight: 9
title: "Running as a Script"
description: "Run the source code as in script form."
icon: "terminal"
date: "2025-07-25T10:10:36-04:00"
lastmod: "2025-07-25T10:10:36-04:00"
draft: false
toc: true
---

## Install go

https://go.dev/dl/

## Cloning and installing dependencies

Clone the project

```bash
  git clone https://github.com/vpamm/ChatDJ
```

Go to the project directory

```bash
  cd ChatDJ
```

Install dependencies
```go
  go get ./...
```

## Run the program!

```go
  go run .
```