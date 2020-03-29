# JSON Template Render
Tool to render templates through command line

![.NET Core](https://github.com/crisfervil/JSONTemplateRender/workflows/.NET%20Core/badge.svg)

# Usage

## Parameters

json-file : Path to the JSON file containing the data to feed the template

template-file: Path to the Liquid template file

output-file: Path where to save the rendered file

```console
JSONTemplateRender --json-file quiz.json --template-file quiz.liq --output-file quiz.html
```
# Other links

- [JSON Syntax](https://www.json.org/json-en.html)
- [Liquid Language](https://shopify.github.io/liquid/)
- [Dot Liquid](http://dotliquidmarkup.org/)

# Backlog
- [ ] Improve documentation
- [ ] Add tests
