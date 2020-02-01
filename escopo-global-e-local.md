### Local

Ao criar uma função, variável, definir valor da variável e retornar o valor da variável na function
```
function myFunction() {
  var teste = 10;
  return teste;
}
```

Ao executar a function acima
```
myFunction();
```
> 10

Se tentar acessar a variável teste fora da função, qual o resultado esperado?
> O console exibe um erro que a variável não foi definida, ou seja, ela não é conhecida fora da function

### Global

```
var teste2;

function myFunction2 () {
  teste2= 20;
  return teste2;
}
```

Se tentar acessar a variável teste2 fora da função, qual o resultado esperado?
> O valor da variável será exibida já que a variável foi declarada no escopo global, ou seja, é possível ter acesso
