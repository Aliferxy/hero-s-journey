# Dia 6

## Iniciando TypeScript
É um superset set de Javascript, potencializa a linguagem adicionando uma nova sintaxe com tipagem estática.
> Comando necessário para instalar a dependêcia Typescript no seu projeto.
```
$ npm install typescript
```
> Crie um arquivo chamado tsconfig.json para editar suas prefências em Typescript.
>> Crie um compilador no package.json com script "tsc", para compilar o código Typescript para Javascript.
>>> É possivel automatizar o processo de compilação utilizando o script "tsc" com parâmetro -w.

### Modificador: private
Utilizando Typescript é possível modificar propriedades, tornando as mesmas privadas. São acessadas apenas por métodos da mesma classe

### Modificador: public
Caso não especificar o modificador private, ou inserir public antes de seu atributo. Ele será publico, sendo possível acessar de qualquer um.
