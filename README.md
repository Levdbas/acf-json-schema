# Schemas

ACF block schema that extends the default WordPress block schema from https://github.com/WordPress/gutenberg/tree/trunk/schemas

JSON schemas are used by code editors to offer tooltips, autocomplete, and validation.

## JSON schema usage

Many editors recognize the `$schema` property in JSON files.

Update your `block.json` to include:

```json
{
	"$schema": "https://raw.githubusercontent.com/Levdbas/acf-json-schema/main/acf-blocks.json"
}
```
Visual Studio Code and PhpStorm are two popular editors that work out of the box. However, some editors require a plugin installed, and not all editors recognize the `$schema` property. Check your editor's documentation for details. Additionally, [SchemaStore.org](https://www.schemastore.org/) and [JSON Schema](https://json-schema.org/implementations.html#editors) have lists of editors known to have support if your current editor is unsupported.
