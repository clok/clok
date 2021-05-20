<!--
**clok/clok** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

### Howdy! I'm Derek. I could do this all day. <img src="https://cdn.discordapp.com/emojis/778638806877732894.gif" width="25px">

<hr>

<p align=center>
  <a href="https://github.com/anuraghazra/github-readme-stats" title="Go to Source">
    <img height=175 align="center" src="https://github-readme-stats.vercel.app/api?username=clok&show_icons=true&theme=gruvbox&count_private=true">
  </a>
  <a href="https://github.com/anuraghazra/github-readme-stats">
  <img height=175 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=clok&theme=gruvbox&layout=compact&count_private=true" />
  </a>
</p>

<hr>

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