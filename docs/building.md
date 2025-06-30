<!-- docs/building.md -->

# Building an executable

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

### Build the Executable

```go
 go build -ldflags -H=windowsgui -o ChatDJ.exe
```