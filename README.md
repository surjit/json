# json1

This is a fork of [golang's encoding/json](https://github.com/golang/go/tree/master/src/encoding/json)

The semantic versioning for this repository follows that of the go src version that it forks from.

# Changelog


```
type TestStruct struct {
  Text string `json:"text" default:"emptynil"`
}

```

### JSON output when empty string ""

```
{
 "text": null
}
```
