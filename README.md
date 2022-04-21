# Typescript

[Documentation](https://www.typescriptlang.org/docs/)

[Download](https://www.typescriptlang.org/download_

precisa ter o node instalado, depois digita: "npm install -g typescript" e para ver se instalou: "tsc --version".

as HTMLInputElement

+number

+var      -     +numero1

comando para gerar um arquivo JS inválido(mesmo que tenha erro): "tsc script.ts"

Não criar arquivo com erro: "tsc script.ts --noEmitOnError"

any

padrão para receber parâmetros em funções

charAt(), toUpperCase(), substring(), forEach(), 

function teste(nome:string, idade?:string)      //esse ponto de interrogação diz que ele pode não vir

Union types (múltiplos tipos) -> let idade string|number = 90;

Tipos literais->          function MostrarTexto(texto:string, alinhamento:'left'|'right'|'center'){}

type MathFunction(n1:number, n2:number) => number;        function somar:MathFunction = (n1, n2) => { return n1+n2};

tsc --init;

"exclude": [ "src" ];

"include":[ "src/script.js" ];              ->  "include":[ "src/*", "app.ts" ];

target dentro do tsconfig.json                    ******************************

rootDir e outDir dentro do tsconfig.json        *********************************

exemplo DE "outDir:"public/assets/js"

removeComents na pasta config                   ********************************

noUnusedLocale = true

noUnusedParametres






