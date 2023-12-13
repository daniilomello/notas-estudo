voltar: [[Home]]
tópicos: [[Programação]]
referências:
tags: #temporaria

# Iniciando o ESlint no projeto

Inicie o ``.editorconfig`` no seu editor

Inicie a instalação do lint, selecionando o seguinte
- Check syntax, find problems, enforce code style
- Javascript modules
- React (ou nenhum caso seja back-end)
- Defina se é no browser ou node
- JSON, Spaces, Single, Unix, Semicolons Yes, Yarn

```bash
npm init @eslint/config
```

- Atualize os rules
```JSON
"rules": {
    "indent": [
      "error",
      2
    ],
    "linebreak-style": [
      "error",
      "unix"
    ],
    "quotes": [
      "error",
      "single"
    ],
    "semi": [
      "error",
      "always"
    ],
    "object-curly-spacing": [
      "error",
      "always"
    ],
    "array-bracket-spacing": [
      "error",
      "always"
    ],
    "computed-property-spacing": [
      "error",
      "always"
    ],
    "no-multiple-empty-lines": [
      "error",
      { "max": 1, "maxEOF": 0 }
    ],
    "object-curly-newline": [
      "error", {
        "ObjectExpression": "always",
        "ObjectPattern": { "multiline": true },
        "ExportDeclaration": { "multiline": true, "minProperties": 3 }
      }
    ]
  }
```