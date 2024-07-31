# safhire
Safhire(pronounced _Sapphire_) is an implementation of [SQL on FHIR](https://build.fhir.org/ig/FHIR/sql-on-fhir-v2/index.html) in Rust lang.

Safhire is currently in private beta. If you are interested to know more, please send an email to [hello@sereen.io](mailto:hello@sereen.io).

# Usage
```
./safhire --help
Usage: safhire [OPTIONS] --vdf <VDF> --resf <RESF>

Options:
  -v, --vdf <VDF>    Path to a ViewDefinition file or a folder containing ViewDefinition files
  -r, --resf <RESF>  Path to a FHIR resource file or a folder containing FHIR resources
  -n, --ndjson       Flag to indicate that the input FHIR resource files are in newline delimited JSON format
  -f, --fmt <FMT>    Output format, SQL or CSV [default: sql]
  -o, --od <OD>      Output Directory (writes to stdout when not specified)
  -h, --help         Print help
  -V, --version      Print version
```
