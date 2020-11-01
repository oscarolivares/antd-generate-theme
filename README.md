Generar estáticos customizados del tema de antd

1. Definir las variaciones del tema en custom-theme.less
2. Ejecutar el comando `yarn run generate-theme`

opciones del comando (opciones por defecto):

    verbose=""
    customThemeFilePath="./custom-theme.less"
    generatedThemeFilePath="./custom-theme.css"
    antdLibraryPath="./node_modules/antd"
    theme="default"

Formato:

`generate-theme [verbose] [customThemeFilePath] [generatedThemeFilePath] [antdLibraryPath]`

Ejemplo para generar sobre los 3 temas principales de antd:

`yarn run generate-theme "./custom-theme.less" "./light-theme.css" "./node_modules/antd"`
`yarn run generate-theme "./custom-theme.less" "./dark-theme.css" "./node_modules/antd" "dark"`
`yarn run generate-theme "./custom-theme.less" "./compact-theme.css" "./node_modules/antd" "compact"`
