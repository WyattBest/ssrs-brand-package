# ssrs-brand-package
When creating your SQL Server Reporting Services brand package, you must edit colors.json. Perhaps you use Visual Studio Code (VSCode) as your JSON editor.

Wouldn't it be nice if VSCode gave you a color picker? Unfortunately, automatic color pickers only appear for CSS and LESS files, but a custom JSON schema can fix this.

Add my JSON schema to your color.json file like this, and the color swatches should appear:

```jso0n
{
	"$schema": "https://raw.githubusercontent.com/bendodge-xwis/ssrs-brand-package/master/colors_schema.json",
	...
}
```

I'm new to GitHub and uncertain if linking like this is allowed. If not, or if there's a better way, please create an issue and let me know!
