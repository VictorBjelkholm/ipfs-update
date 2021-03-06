# ipfs update
An updater tool for ipfs. Can fetch and install given versions of go-ipfs.

## Installation

Requirement: Go version 1.5 or higher

```
go get -u github.com/ipfs/ipfs-update
```

## Usage
```
NAME:
   ipfs-update - update ipfs

USAGE:
   ipfs-update [global options] command [command options] [arguments...]
   
VERSION:
   0.1.0
   
AUTHOR(S):
   whyrusleeping 
   
COMMANDS:
   versions	print out all available versions
   version	print out currently installed version
   install	install a version of ipfs
   revert	revert to previously installed version of ipfs
   fetch	fetch a given (default: latest) version of ipfs
   help, h	Shows a list of commands or help for one command
   
GLOBAL OPTIONS:
   --help, -h		show help
   --version, -v	print the version
```
