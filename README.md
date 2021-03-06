<br><br>

<h1 align="center">Clip</h1>

<p align="center">
  <a href="/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"/></a>
  <a href="https://goreportcard.com/report/github.com/mingrammer/clip"><img src="https://goreportcard.com/badge/github.com/mingrammer/clip"/></a>
</p>

<p align="center">
A simple key-value store for clipboard
</p>

<br><br><br>

It is a command line tool for simple key-value store for clipboard. I often use frequently used text, especially long texts that are hard to remember, on the clipboard. But it is cumbersome to copy the text manually by using trackpad or mouse. So `clip` was developed to solve this problem.

## Installation

### Using go get

```bash
go get github.com/mingrammer/clip
```

It is recommended to also run `dep ensure` to make sure that the dependencies are in the correct versions.

### Using [homebrew](https://brew.sh)

```bash
brew tap mingrammer/clip
brew install clip
```

## Usage

```console
# List all key-value pairs
clip list

# Get a value of a specific key
clip get <key>

# Set a key-value pair
clip set <key> <value>

# Delete a key
clip del <key>

# Copy a value of a specific key to clipboard
clip cp <key>
```

## License

MIT
