# Next.js
> Framework feito a partir do React

>> Next oferece um sistema de rotas sem a necessidade de utilizar libs, desde que você crie uma pasta **pages** dentro da sua aplicação.
 
>>> Arquivos que começam com _ são destinados para configurações

>>>> Obs: Inclusive ele fornece uma página 404 sem a necessidade de você criar.

O framwork possui três modalidades para desenvolvimento de um site.
> Diferente de React, o Next.js permite um melhor SEO devido a permissão de SSR e SSG

## SSR
> Server Side Rendering

## SSG
> Static Site Generator

## ISR
> Incremental Static Regenerator

## CSS-in-JS
Permite utilizar CSS dinamicamente, sem a necessidade de criar um novo arquivo ou as classes de CSS. 

## Next.js: Page _app
> Extrutura padrão

```
export default function Myapp({Component, pageProps}) { 
  return <Component {...pageProps}/>
```

Pagina utilizada para configurações globais, sejam estilos ou componentes.

## Next.js: getStaticProps
> Extrutura padrão
```
export async function getStaticProps(context) {
  return {
    props: {}, // Passa o seu item aqui
  }
}
```
Todo dado que for passado dentro desse método podera ser visto o HTML do lado do client, melhorando a performance do SEO. Funciona melhor com sites estáticos, já que roda apenas em build time.
> Obs: Possui mais velocidade que getServerSideProps

## Next.js: getServerSideProps
> Extrutura padrão
```
export async function getServerSideProps(context) {
  return {
    props: {}, // Passe seu item aqui
  }
}
```
Funciona parecido com getStaticProps, porém funciona melhor com site dinamico. Roda a cada acesso de cliente, tendo tempo de resposta inferior.

## WebVitals
Conjunto de métricas feitas pelo Google para finalidade de ranquear os sites.
> As métricas são divididas em:

>> LCP
>>> Largest Contentful Paint

>> FID
>>> First Input Delay

>> CLS
>>> Cumulative Layout Shift

## Next.js: useRouter
Utiliza o router como object exibindo todos os dados sobre a atual página, e permite certos métodos adiocionais. Como por exemplo router.push

## Next.js: getStaticPaths
Caso o site utilizar getStaticProps e ser dinamico, é necessário utilizar getStaticPaths para definir uma lista de caminhos que serão pré renderizados ao utilizar  a aplicação.

