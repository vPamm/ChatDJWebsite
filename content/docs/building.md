---
weight: 10
title: "Building"
description: "Build the source code into an executable program."
icon: "build"
date: "2025-07-25T11:23:55-04:00"
lastmod: "2025-07-25T11:23:55-04:00"
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
## Building the executable

{{< tabs tabTotal="2">}}
{{% tab tabName="Windows" %}}

Build the executable

```go
 go build -ldflags -H=windowsgui -o ChatDJ.exe
```

{{% /tab %}}
{{% tab tabName="Linux" %}}

Actually build the executable

```go
 go build -o ChatDJ
```

Make it executable

```bash
 chmod +x ChatDJ
```

{{% /tab %}}
{{< /tabs >}}