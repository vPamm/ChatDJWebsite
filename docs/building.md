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
```node
  npm install
```

### Build the frontend

Go to the frontend directory

```bash
  cd frontend
```

Install dependencies

```node
  npm install
```

Build the frontend

```node
  npm run build 
```

### Compile the server

```bash
  cd ChatDJ
```
Build the server

```node
 ncc build server.js -o dist
``` 

### Build the Executable

```go
 go build -ldflags -H=windowsgui -o ChatDJ.exe
```