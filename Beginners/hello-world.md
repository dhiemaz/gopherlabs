

## Lets Start With First Hello world Program 



-----



    package main

    import "fmt"

    func main() {
	fmt.Println("Hello world!")
    }
    
----
## A complete program is created by linking a single, unimported package called the main package with all the packages it imports, transitively. The main package must have package name main and declare a function main that takes no arguments and returns no value.

    func main() { â€¦ }

## Program execution begins by initializing the main package and then invoking the function main. When that function invocation returns, the program exits. It does not wait for other (non-main) goroutines to complete.



-----


## Go: Meaning of the 'fmt' package acronym

## fmt is short for format. 

## Package fmt implements formatted I/O with functions analogous to C's printf and scanf. The format 'verbs' are derived from C's but are simpler.
-----

