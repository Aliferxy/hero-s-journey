# Dia nove

## Next.js
> Para começar com pé direito, o next oferece um sistema de rotas sem a necessidade de utilizar React: router, desde que você crie uma pasta **pages** dentro da sua aplicação.
>> Obs: Inclusive ele fornece uma página 404 sem a necessidade de você criar.

Diferente de React, o Next.js permite um melhor SEO devido a permissão de SSR e SSG

### CSS-in-JS
Permite utilizar CSS dinamicamente, sem a necessidade de criar um novo arquivo ou as classes de CSS. 

### Next.js: Page _app
> Extrutura padrão

```
export default function Myapp({Component, pageProps}) { 
  return <Component {...pageProps}/>
```

Pagina utilizada para configurações globais, sejam estilos ou componentes.

### Next.js: getStaticProps
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

### Next.js: getServerSideProps
> Extrutura padrão
```
export async function getServerSideProps(context) {
  return {
    props: {}, // Passe seu item aqui
  }
}
```
Funciona parecido com getStaticProps, porém funciona melhor com site dinamico. Roda a cada acesso de cliente, tendo tempo de resposta inferior.
