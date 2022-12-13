# React
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

## "Componentizar"
Consiste em "desmembrar" componentes em pequenas partes, com funções únicas. O intuito é separar cada um e no final juntar os mesmos em um arquivo único através de imports.

## Conceito SPA
> Single page application
É uma aplicação web / site que interage com usuário de forma dinamica, sem necessariamente recarregar a página.

## React: Components
São pequenos blocos da aplicação que tem como conteúdo funções ou classes do ECMAScript.

## React: Props
São objetos postos em componentes React, fornecem dados que podem ser compartilhados com outros componentes em um fluxo de dados unidirecional, de um elemnto pai para filho.

## React Hooks - State
Tem função de rastrar o estado de um componente, certificando se ocorreram mudanças durante a aplicação.

## React Hooks - Effect
Age possibilitando utilizar efeitos colaterais em componentes. Semeljante a lifecycles como componentDidMout / ...DidUpdate

## React Hooks: useContext
> Primeiramente precisamos executar o camando **createContext**
>> Quando decidir usar o context, utilize (nome da variavel).provider

A função do useContext é passar dados de maneira global a todos componentes, sem a necessidade de usar propriedades.

## React Hooks: Custom Hooks
> Todo Custom Hooks necessariamente precisar começar com a palavra **use**

É uma função Javascript que pode possuir o valor que você desejar, seja uma array, um conjunto de funções e states ou um valor único.

## React: Style Components (*lib*)
Biblioteca que tem como função escrever códigos CSS dentro do Javascript. Com aprimoramento de compatibilidade para Browsers.

# React: router
É uma biblioteca que permite navegar e alterar entre URL's dentro da mesma aplicação de forma dinâmica, uma boa opção para facilitar a crianção de SPA's.

## router: useLocation
> State exclusivo da lib React: router

Tem como função identificar a url da página.

## Rotas aninhadas
> Necessita ter uma página padrão para renderização das Route filhas.
>> Caso atribuir index a uma rota filha, o redirecionamento será igual à rota pai

Acontece quando uma Route se torna pai de uma Route filha. Geralmente são usadas para reaproveitar uma estrutura de uma página já feita.

## router: Outlet
Componente responsável por indicar onde Route filhas serão renderizadas dentro de uma Route pai. 

## router: useParams
> Útil para aplicações como blogs que utilizam diversos posts, podendo navegar por eles utilizando rotas dinamicas.
 
Retorna um objeto com pares de chaves como valores dentro da URL.

## router: useNavigate
> Muito utilizado junto de botões, principalmente no quisito de voltar uma página caso a página desejada não for encontrada.

O próprio nome já é bem intuitivo, ele serve para navegar entre as páginas da aplicação.

