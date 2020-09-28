```go
package main

type Me struct{
  Code string
  Job string
  BestAndFavoriteSkill string
  SweetHeart string
  Twitter string
}

func main() {
  me := &Me{
    Job: "Security Researcher and Full stack developer",
    Code: "Python,Go and Everythings",
    BestAndFavoriteSkill: "Web,Mobile Hacking :D",
    Twitter: "https://twitter.com/ArbazKiraak"
  }
  _ = me
}
```
