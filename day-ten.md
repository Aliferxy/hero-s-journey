# Dia 10

## Next.js
> Obs: Arquivos com _ são destinados para configurações.

### WebVitals
Conjunto de métricas feitas pelo Google para finalidade de ranquear os sites.
> As métricas são divididas em:

>> LCP
>>> Largest Contentful Paint

>> FID
>>> First Input Delay

>> CLS
>>> Cumulative Layout Shift

### Next.js: useRouter
Utiliza o router como object exibindo todos os dados sobre a atual página, e permite certos métodos adiocionais. Como por exemplo router.push

### Next.js: getStaticPaths
Caso o site utilizar getStaticProps e ser dinamico, é necessário utilizar getStaticPaths para definir uma lista de caminhos que serão pré renderizados ao utilizar  a aplicação.
