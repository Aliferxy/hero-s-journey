# Dia 5

## React
> *Executa os códigos de forma assíncrona, navega por uma DOM virtual. Ao final, compara o DOM virtual com o local e entrega o resultado.*

## Mocks
São objetos simulados no intuito de fazer testes em comportamentos de outros objetos.

## Jest
Framework que facilita testes em JavaScript. (Funcional com alguns outros framewokrs, como react)
> GitHub oferece alguns projetos em MD que mostra e ensina comandos em Jest

### Testes
#### Unit test
> Tem objetivo de testar apenas uma classe, interface, parametros enviados ou argumentos recebidos.

#### Novo comando aprendido
```
npm test
```
> Executa um teste de verificação de acordo com o que foi proposto. (Arquvivo teste do react)

## React Hooks
> Embora os componentes de classe sejam importantes, é recomendavel que utilize os hooks no lugar dos mesmo.
>> Não utlize Hooks dentro de scopos.

### React: useState
Possui a sintaxe **[state, setState] = useState = ()**, feito exclusivamente para redefinir o problema de uso da palavra this.

### React: useEffect
Funciona como um lifecycle method, porém é capaz de colocar dependencias especificas 

### React: useCallback
É utilizado para otimizações de aplicações, guardando funções em cache e evitando renderizações desnecessárias, embora perca seu aspecto semântico é excelente para o que o mesmo é feito.

### React: useMemo
Age de forma parecida com useCallback, porém ao invés de armazenar funções, armazena valores.

### React: useRef
Possui uma propriedade interna (current), utilizado para referenciar algum elemento (Uma marcação inicial). Utilizado com outros hooks para performance desejada.

