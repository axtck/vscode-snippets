# Visual Studio Code snippets

***Some handy snippets for VS Code***

---

## Configuration

Command palette:

```
>Preferences: Configure User Snippets

# choose language (for example)
>javascriptreact 
```

This will create a json file for configuration

```javascript
{
  // Place your snippets for javascriptreact here. 
  // Each snippet is defined under a snippet name and has a prefix, body and 
  // description. The prefix is what is used to trigger the snippet and the body will be expanded and inserted. 
  // Possible variables are:
  // $1, $2 for tab stops, $0 for the final cursor position, and ${1:label}, ${2:another} for placeholders. 
  // Placeholders with the 
  // same ids are connected.
  // Example:
  // "Print to console": {
  // 	"prefix": "log",
  // 	"body": [
  // 		"console.log('$1');",
  // 		"$2"
  // 	],
  // 	"description": "Log output to console"
  // }
}
```

Example configuration

```javascript
{
  "Print to console": {
 	  "prefix": "log",
 	  "body": [
 		  "console.log('$1');",
 		  "$2"
 	  ],
 	  "description": "Log output to console"
  }
}
```
