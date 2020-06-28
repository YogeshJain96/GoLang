# GoLang

> To Downlaod Go visit https://golang.org/dl/

> To Install in Linux(Ubuntu)

* Post Downloading the archive and extract it into /usr/local, creating a Go tree in /usr/local/go. For example run:

``` 
tar -C /usr/local -xzf go$VERSION.$OS-$ARCH.tar.gz
```

* Add /usr/local/go/bin to the PATH environment variable. You can do via:

```
export PATH=$PATH:/usr/local/go/bin
```

* Write your first program and save it with *.go* extentension to test the installation:

```
package main

import "fmt"

func main() {
	fmt.Printf("Hello, world\n")
}
```

* Finally Run the program via:
```
go run Hello.go
```

- or you can build an exectable file by compiling:

```
go build Hello.go
```
```
$ ./Hello
Hello, world
```
