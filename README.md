```go
package main

type Programmer struct {
	Name string
	Interests []string
	Languages []string
	Learning []string
}

func main() {
	me := &Programmer{
		Name: "Sam",
		Interests: []string{"Machine Learning/AI"},
		Languages: []string{"TypeScript", "Python", "Java, "Go"},
		Learning: []string{"C++"},
	}
}
