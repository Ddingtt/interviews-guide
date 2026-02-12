# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Go-based interview guide project, currently in early development stages.

## Development Commands

### Go Module Setup
```bash
go mod init github.com/[username]/interviews-guide
```

### Building
```bash
go build ./...
```

### Testing
```bash
# Run all tests
go test ./...

# Run tests with coverage
go test -cover ./...

# Run a specific test
go test -run TestName ./path/to/package
```

### Formatting & Linting
```bash
# Format code
go fmt ./...

# Run linter (if golangci-lint is installed)
golangci-lint run
```
