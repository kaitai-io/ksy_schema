# KSY (Kaitai Struct YAML) specification

This repository holds formal specification of KSY (Kaitai Struct YAML)
files. These files are used by [Kaitai Struct](https://kaitai.io/)
project to specify binary formats / data structures in declarative
fashion.

This specification uses [JSON schema](https://json-schema.org/) — please
note that KSY files are actually YAML-based, so to validate them with
this schema one has to convert them to JSON first.

## Usage

At the moment, the primary consumer of this schema is [Web
IDE](https://github.com/kaitai-io/kaitai_struct_webide), which uses it
for autocompletion in text editor.

## Licensing

MIT license, see [LICENSE](LICENSE) for details.
