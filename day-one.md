# Dia um

React.Js e Next.js **(Curso)**

## Introdução ao curso
 Três videos introdutórios comentando um pouco sobre React.Js / Next.js.
 
 
## Javascript Essenciais

### Functions
> Executa uma determinada função que for designada.

### Arrays / Object - Atribuição via desestruturação
> É uma sitaxe capaz de extrair ou modificar dados especificos de uma array ou object.

### Array - Filter
> Filtra um item de uma array baseada nas condições impostas.

### Array - Map
> Percorre toda array e retorna uma nova array com base nas condições impostas.

### Array - Reduce
> Reduz a array baseada nas condições impostas.
>> Possui um parametro próprio, 'Acumulador'.

### Array - Foreach
> Percore a array

### Classes
> As classes são funções especiais que descrevem estados de objetos. Possuem foco em heranças.

### Métodos estáticos
> Função pertencente à uma classe, mas não instânciada

### Promises
> Utiliza com aplicações assíncronas, obriga necessariamente uma ordem para que o javascript execute o código. Utiliza os parâmetros (resolve, reject).

### Async/Await
> É uma sintaxe que facilita a leitura de um código assícrono, porém lido pelo javascript como síncrono (Utiliza Try/Catch).

## Primeiros passos
> Novos comandos aprendidos.


```
$ npx create-react-app projectname
```
Tem a função de criar um preset de configurações para um ambiente de desenvolvimento React.


```
$ npm start
```
Executa o pacote de scripts da aplicação.


```
$ npm run build
```
Gera uma build otimizada do código completo.


## Formato JSX
Sintaxe criada com intuito de simplificar a extruturação de componentes utilizando HTML como referência.

## React State
São objetos que armazenam valores de propriedades pertencentes a componentes
> Obs: em casos de mudanças nos valores do State, o componente será novamente renderizado sem que seja necessário um reload na página.

## Componente Stateful / Stateless
### Stateful
> Armazena informações de componentes e é capaz de alterar o mesmo

### Stateless
> Apenas renderiza informações (Componente estático)

## Lifecycle
Componentes Stateful possuem diferentes ciclos de vida, sendo possivel manipular os mesmos durante cada tipo de ciclo desejado
> Ciclos se dividem em:
>> * Ao Montar 
>> * Ao Atualizar
>> * Ao Desmontar
