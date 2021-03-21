# ignite-nodejs-typescript
Repositório do módulo TypeScript do Ignite NodeJS - Rocketseat.

## Iniciando com Typescript - Criando setup

Adiciona a extensão do typescript
yarn add typescript -D

Para criar o arquivo de configuração do typescript, tsconfig.json:
yarn tsc --init

Para conseguir rodar o código, é preciso fazer com que os arquivos typescript sejam criados em js, e para isso é necessário informar no parâmetro outDir do arquivo de configuração do typescript para onde esses arquivos reescritos irão ficar:
"outDir": "./dist"

Desta forma, toda vez que rodar o comando yarn tsc, os arquivos ts serão recriados como js e colocados dentro dessa pasta. Assim, poderá ser rodado o código.