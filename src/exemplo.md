Rio Tamanduateí
======

QTA - Análise de Águas
---------

Antes de começarmos o handout vamos responder a uma pergunta:


Diferente disso o Counting Sort que é o algoritmo abordado neste handout não utiliza de comparação para ordenar os valores, este algoritmo serve para ordenar **apenas** valores inteiros e positivos de um vetor, assim ele pode ser implementado para criação de rankings ou para ordens de prioridades dea tendimento por exemplo.



* não existe repetição de elementos.

* Todos os elementos do array a ser ordenado são positivos.

* Conhecemos qual o maior valor desse array.

1. Primeiro criamos o vetor auxiliar

    C = [True,False,True,False,False,False,True,True,False,True]

2. Criando o vetor B do tamanho de V somando 1 onde tem True

    B = [1,3,7,8,10]

:::

???

Você também pode criar

1. listas;

2. ordenadas,

assim como

* listas;

* não-ordenadas

* testando entao

e imagens. Lembre que todas as imagens devem estar em uma subpasta *img*.

![](logo.png)

Para tabelas, usa-se a [notação do
MultiMarkdown](https://fletcher.github.io/MultiMarkdown-6/syntax/tables.html),
que é muito flexível. Vale a pena abrir esse link para saber todas as
possibilidades.

| coluna a | coluna b |
|----------|----------|
| 1        | 2        |

Ao longo de um texto, você pode usar *itálico*, **negrito**, {red}(vermelho) e
[[tecla]]. Também pode usar uma equação LaTeX: $f(n) \leq g(n)$. Se for muito
grande, você pode isolá-la em um parágrafo.

$$\lim_{n \rightarrow \infty} \frac{f(n)}{g(n)} \leq 1$$

Para inserir uma animação, use `md ;` seguido do nome de uma pasta onde as
imagens estão. Essa pasta também deve estar em *img*.

;bubble

Você também pode inserir código, inclusive especificando a linguagem.

``` py
def f():
    print('hello world')
```

``` c
void f() {
    printf("hello world\n");
}
```

Se não especificar nenhuma, o código fica com colorização de terminal.


Função para encontrar o maior elemento do array (k):


Exemplo inicial:


Referencia: https://www.javatpoint.com/counting-sort

!!! Aviso
Este é um exemplo de aviso, entre `md !!!`.
!!!


??? Exercício

Este é um exemplo de exercício, entre `md ???`.

::: Gabarito
Este é um exemplo de gabarito, entre `md :::`.
:::

???
