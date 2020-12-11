### Arquivos das aulas do Módulo de ES6

> Você pode encontrar esse curso na [Udemy](https://www.udemy.com/js-com-tdd-na-pratica/?couponCode=PROMOGIT)

### Ementa do Módulo

- 1 - Introdução ao ES6 (3:10) - http://es6-features.org/
- 2.1 - Escopo do JS (3:57)
- 2.2 - Variável let no JS (3:40)
- 2.3 - Variável const no JS (3:28)
- 2.4 - Temporal Dead Zone (2:26)
- 3.1 - Introdução a Arrow Function (6:20)
- 3.2 - Arrow Function e o Lexical This (6:21)
- 4.1 - Introdução a Template Literals (4:11) <------>
- 4.2 - Usando Template Literals para Html Fragments (6:15) <------>
- 4.3 - Tagged Template (7:31) <------>
- 5.1 - Shorthand Properties (3:02) <------>
- 5.2 - Default Parameters (3:08)
- 5.3 - Novos métodos para Strings (3:31) <------>
- 6.1 - Array.from() - (3:27)
- 6.2 - Array.of() - (0:53)
- 6.3 - Array.find() e Array.findIndex() -(4:39)
- 6.4 - array.fill() - (2:30)
- 7.1 - Introdução ao Destructuring (5:10) <------>
- 7.2 - Destructuring em Arrays (0:47) <------>
- 7.3 - Fazendo swap de variáveis com destructuring (2:13) <------>
- 8.1 - Introdução ao Spread Operator (4:51) <------>
- 8.2 - Usando o spread dentro de funções (1:30)
- 8.3 - Rest params (4:02)
- 9.1 - Introdução a Promises (6:57) <------>
- 9.2 - Exemplo Real de Promises (4:58)
- 9.3 - Manipulando múltiplas Promises (3:44)
- 10.1 - Herança Prototipal (5:47)
- 10.2 - Criando Classes do ES6 (5:19)
- 10.3 - Usando extended classes (4:33)
- 11.1 - Introdução a Symbols (5:06) <------>
- 11.2 - Iterators e Iterables - for...of (4:44) <------>
- 12.1 - Introdução a Generators (5:17) <------>
- 12.2 - Usando Generators para fluxos assíncronos (6:40) <------>
- 13.1 - Introdução ao Proxy (6:38) <------>
- 14.1 - Introdução ao Set (5:27) <------>
- 14.2 - Introdução ao WeakSet (3:32) <------>
- 15.1 - Introdução ao Map (2:46)
- 15.2 - Introdução ao WeakMap (3:56)
- 16.1 - Introdução a Módulos em JS (10:15) - https://www.freecodecamp.org/news/javascript-modules-a-beginner-s-guide-783f7d7a5fcc/
- 16.2 - Configurando o Webpack (10:49)
- 16.3 - Trabalhando com Imports no ES6 (7:07)
- 16.4 - Trabalhando com Exports no ES6 (8:02)
- 16.5 - UglifyJS no Webpack (2:41)
- 16.6 - Variáveis de Ambiente no Webpack (5:08)
- 16.7 - Adicionando Sourcemaps em nosso código (3:46)
- 16.8 - Inicializando um server com Webpack (3:21)

# ES6
- http://es6-features.org/
- https://kangax.github.io/compat-table/es6/
- https://ponyfoo.com/articles/tagged/es6-in-depth

(
  Template literals: `Isso custa R$ ${value}`;
  Tagged template: function tagging(template, ...values){} <----> tagging `termo1 ${valor} termo2 ${valor2}`;
  Arrow function:
    (param1, param2) => { // multi params and  multi actions };
    param => { // single param and multi actions }
    param => // single param and single action
  Peomises then catch
  Class (
    https://medium.com/javascript-in-plain-english/private-member-in-javascript-class-2359ef666aaf
  )
  Simbol - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol
  Interable (
    for...of: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of
    tx = txt[Simbol.iterator]();
    tx.next()
    function* fn() {yield "term01"; yield "term02";}
    it = fn() --> it.next() --> it.next().value
  )
  new Proxy(a, b)
  new Set()
  new WeakSet()
  new Map()
  new WeakMap()
  Async function / Await fetch
  PadStart / padEnd
)

https://www.npmjs.com/package/swagger
https://guides.github.com/activities/hello-world/

https://levelup.gitconnected.com/how-does-hoisting-work-in-javascript-es6-b0e06727e071
https://levelup.gitconnected.com/arrow-function-vs-regular-function-in-javascript-b6337fb87032
https://www.semrush.com/blog/semantic-html5-guide/

# WEBPACK

- https://ramdajs.com/





