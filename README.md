```js
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:":                    "",
		"- 🔭 I’m currently working on":      "Senior Software Developer",
		"- 🌱 I’m currently learning":        "JS, TS, MongoDB, NodeJS, Express, HTML, CSS, Angular, D365FO",
		"- 👯 I’m looking to collaborate on": "JavaScript, Angular, MongoDB",
		"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
		"- 💬 Ask me about":                  "D365, PHP, Angular, SQL, Software Design & Architecture, Web-Dev",
		"- 📫 How to reach me:":              "https://github.com/vargas0912/vargas0912",
	}
}
```
