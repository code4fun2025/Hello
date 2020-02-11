1. choose a module path (we'll use github.com/user/hello) and create a go.mod file that declares it:
C:\Li\Work\GitHub\Code4Fun\Hello>go mod init github.com/code4fun2025/Hello
go: creating new go.mod: module github.com/code4fun2025/Hello

2. create a file named hello.go inside that directory containing the following Go code:
package main

import "fmt"

func main() {
	fmt.Println("Hello, world.")
}

3. C:\Li\Work\GitHub\Code4Fun\Hello>go env -w GOBIN=C:\Li\Work\GitHub\Code4Fun\Hello\bin

4. C:\Li\Work\GitHub\Code4Fun\Hello>go install