<!--
**clok/clok** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->

### Howdy! I'm Derek. I can do this all day. <img src="https://cdn.discordapp.com/emojis/778638806877732894.gif" width="25px">


```go
package main

import (
	"os"

	"github.com/clok/kemba"
)

var (
	k = kemba.New("human")
)

type engineer struct {
	name      string
	email     string
	motto     string
	languages []string
	tools     []string
	favorites []string
}

func main() {
	_ = os.Setenv("DEBUG", "human")

	derek := engineer{
		name:      "Derek Smith",
		email:     "derek@clokwork.net",
		motto:     "I can do this all day.",
		languages: []string{"go", "node", "javascript", "typescript", "python", "ruby", "perl", "bash"},
		tools:     []string{"docker", "kubernetes", "aws", "gcp"},
		favorites: []string{"hapi", "debug", "lodash", "husky", "urfave/cli", "git-chglog", "jedib0t/go-pretty", "r3labs/diff"},
	}

	k.Log(derek)
	_ = os.Setenv("DEBUG", "")
}
```

<img src="https://github.com/clok/clok/blob/main/code-debug.png?raw=true"/>
