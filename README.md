# golang_tour

## Setup local dev environment
* Download the package from here:

     [https://golang.org/dl/](https://golang.org/dl/)

* Installation
```
  tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz
```

* Source environment variables into ~/.zshrc or ~/.profile file
```
  export PATH=$PATH:/usr/local/go/bin
  export GOPATH="$HOME/workspace/go"
```

### Test your setup

* Create your workspace directory $GOPATH
* Clone this repo in $GOPATH/src 
```
$ cd $GOPATH/src/golang_tour
$ go build
$ ./golang_tour
Welcome here
```
