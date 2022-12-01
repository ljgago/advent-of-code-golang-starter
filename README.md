# Advent of Code Golang Starter

A template for Advent of Code written in Go.

## Usage

You can follow the steps below to install, test, and run the solutions:

    $ git clone https://github.com/ljgago/advent-of-code-golang-starter aoc-golang
    $ cd aoc-golang

    # install dependencies
    $ go install

    # run tests for day01
    $ go test aoc/cmd/day01

    # run the day01
    $ go run aoc/cmd/day01

## Config

If you like read the inputs directly from web, you needs to set the environment
var `AOC_SESSION`. You can to get the session token from the cookie web browser.

Folder structure:

    ├── cmd
    │   ├── day01
    │   │   ├── day01.go
    │   │   └── day01_test.go
    │   └── template
    │       ├── dayXX.go
    │       └── dayXX_test.go
    ├── internal
    │   └── utils
    │       ├── read_file.go
    │       └── read_http.go
    └── resources
        └── day01.txt

Happy coding!

[MIT License](LICENSE)
