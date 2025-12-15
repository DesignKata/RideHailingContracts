# Contracts

## Description
Contains the proto messages that can be passed around the system. No service definitions should be present in this.

## Requirements

### Protoc Compiler
The latest protoc compiler version is 3.24.4 (as of 2023).

#### Installation Methods:

**For macOS (using Homebrew):**
```bash
brew install protobuf
```

**For Ubuntu/Debian:**
```bash
apt-get install -y protobuf-compiler
```

**For Windows (using Chocolatey):**
```bash
choco install protoc
```

**Manual Installation:**
1. Download the latest release from [GitHub](https://github.com/protocolbuffers/protobuf/releases)
2. Extract the package
3. Follow the installation instructions in the README

Verify installation:
```bash
protoc --version
```

### Java Version
23.0.2

### Gradle Version
This project supports Gradle 8.12.

## Build

```bash
./gradlew shadowJar
```

