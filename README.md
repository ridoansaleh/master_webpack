# Master Webpack 4

## Entry
Secara default, webpack mempunyai entry : ./scr/index.js

## Output 
Secara default, webpack mempunyai output : ./dist/main.js

## Mode
Pada webpack 4 (versi terbaru) memiliki 2 mode, yaitu: development dan production

- Development => pada mode ini kita tidak membutuhkan plugin seperti : NamedModulesPlugin, NamedChunksPlugin dan  DefinePlugin (ketiganya merupakan default plugin webpack)
- Production => pada mode ini kita tidak membutuhkan plugin seperti : UglifyJsPlugin (plugin eksternal), DefinePlugin, ModuleConcatenationPlugin dan NoEmitOnErrorsPlugin
