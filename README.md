# ssrs-brand-package
Snippets to help build an SSRS brand package.

When editing colors.json for an SQL Server Reporting Services brand package, wouldn't it be nice if Visual Studio Code (VSCode)
gave you a color picker? Unfortunately, automatic color pickers only appear for CSS and LESS files currently, so you need a
JSON scehma.

Add this JSON schema to your color.json file like this

{
	"$schema": "./colors_schema.json",
	...
}
