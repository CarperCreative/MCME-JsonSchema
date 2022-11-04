## Use with VS Code

To automatically use these schemas with MCME-Scripts in the plugins directory, make sure the `vscode.json-language-features` extension is enabled, and add the following to your VS Code settings:

```json
{
	"json.schemas": [
		{
			"fileMatch": [
				"MCME-Scripts/scripts/*.json"
			],
			"url": "https://raw.githubusercontent.com/CarperCreative/MCME-JsonSchema/master/mcme-scripts-schema.json"
		}
	]
}
```