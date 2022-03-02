```go
package main

type Me struct{
  Code string
  Job string
  BestAndFavoriteSkill string
  Twitter string
}

func main() {
  me := &Me{
    Job: "Web2 & Web3 Security",
    Code: "Python,Go and Everythings",
    BestAndFavoriteSkill: "Web,Smart contract hacking",
    Twitter: "https://twitter.com/ArbazKiraak"
  }
  _ = me
}
```
