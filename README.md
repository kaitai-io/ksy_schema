# KSY (Kaitai Struct YAML) specification

This repository holds formal specification of KSY (Kaitai Struct YAML)
files. These files are used by [Kaitai Struct](https://kaitai.io/)
project to specify binary formats / data structures in declarative
fashion.

This specification uses [JSON schema](https://json-schema.org/) — while
KSY files are YAML-based, the schema can typically be used as-is on YAML files.

## Usage

The [Web IDE](https://github.com/kaitai-io/kaitai_struct_webide), uses this schema
for autocompletion in text editor.

If your text editor supports it (e.g. Visual Studio Code), this schema may already be automatically associated through the `*.ksy` extension via [SchemaStore.org](https://www.schemastore.org).

If using a validator based on the `yaml-language-server`, you can add the following comment to the top of your yaml file to override the schema on a per-file basis:

```yaml
# yaml-language-server: $schema=https://raw.githubusercontent.com/kaitai-io/ksy_schema/master/ksy_schema.json
```

## Licensing

MIT license, see [LICENSE](LICENSE) for details.
