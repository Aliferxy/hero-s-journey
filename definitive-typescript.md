# Typescript

## Iniciando TypeScript
É um superset set de Javascript, potencializa a linguagem adicionando uma nova sintaxe com tipagem estática.
> Comando necessário para instalar a dependêcia Typescript no seu projeto.
```
$ npm install typescript
```
> Crie um arquivo chamado tsconfig.json para editar suas prefências em Typescript.
>> Crie um compilador no **package.json** com script "tsc", para compilar o código Typescript para Javascript.
>>> É possivel automatizar o processo de compilação utilizando o script "tsc" com parâmetro -w.

### Modificador: private
Utilizando Typescript é possível modificar propriedades, tornando as mesmas privadas. São acessadas apenas por métodos da mesma classe

### Modificador: public
Caso não especificar o modificador private, ou inserir public antes de seu atributo. Ele será publico, sendo possível acessar de qualquer um.

### Type: Any
Tipo padrão adotado por Typescript quando não definimos tipos para nossas variaveis.
> É possivel desabilitar o tipo Any dentro de **tsconfig.json**, utilizando comando **noImplicitAny: true**

### Previnir mutabilidade de listas privadas
Utilizar Spread pode resolver o problema, mas existe outra forma mais "aceita". Renomear o type da lista para **ReadonlyArray**, fara que sua lista tenha o aspecto de array, porém sem as mesmas porpriedades. (O nome em sí é literal, apenas leitura) 

