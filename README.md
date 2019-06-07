# rst-xsd
[XSD schemas](https://en.wikipedia.org/wiki/XML_Schema_%28W3C%29) for 
[Rhetorical Structure Theory](https://en.wikipedia.org/wiki/Rhetorical_structure_theory)
XML files. Use these schemas to ensure that your RST XML files are what you
expect them to be.

# Usage

## Validation
Download the XSD schema, then use a tool like `xmllint` to validate your XML:

```
wget https://raw.githubusercontent.com/gucorpling/rst-xsd/master/rst_3.1.0.xsd
xmllint --schema rst_3.1.0.xsd myfile.rs3
```

# Release notes 
## 3.1.0
- Add support for the `<signals>` body element used by
  [rstWeb](http://github.com/amir-zeldes/rstWeb).

## 3.0.0
- Modeled after the `.rs3` file format used by
  [RSTTool](http://www.wagsoft.com/RSTTool/)

