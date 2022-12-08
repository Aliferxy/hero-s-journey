# Dia oito

## React: router

### Rotas aninhadas
> Necessita ter uma página padrão para renderização das Route filhas.
>> Caso atribuir index a uma rota filha, o redirecionamento será igual à rota pai

Acontece quando uma Route se torna pai de uma Route filha. Geralmente são usadas para reaproveitar uma estrutura de uma página já feita.

### router: Outlet
Componente responsável por indicar onde Route filhas serão renderizadas dentro de uma Route pai. 

### router: useParams
> Útil para aplicações como blogs que utilizam diversos posts, podendo navegar por eles utilizando rotas dinamicas.
 
Retorna um objeto com pares de chaves como valores dentro da URL.

### router: useNavigate
> Muito utilizado junto de botões, principalmente no quisito de voltar uma página caso a página desejada não for encontrada.

O próprio nome já é bem intuitivo, ele serve para navegar entre as páginas da aplicação.

## Next.js
> Framework feito a partir do React

O framwork possui três modalidades para desenvolvimento de um site.

### SSR
> Server Side Rendering

### SSG
> Static Site Generator

### ISR
> Incremental Static Regenerator
