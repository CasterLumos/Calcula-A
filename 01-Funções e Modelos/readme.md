# Funções e Modelos

O objeto fundamental do cálculo são as funções. Este capítulo abre o caminho para o
cálculo, discutindo as ideias básicas concernentes às funções e seus gráficos, bem como
as formas de combiná-los e transformá-los. Destacamos que uma função pode ser
representada de diferentes maneiras: por uma equação, por uma tabela, por um gráfico
ou por meio de palavras. Vamos examinar os principais tipos de funções que ocorrem no
cálculo e descrever o modo de usá-las como modelos matemáticos de fenômenos do
mundo real. Também discutiremos o uso de calculadoras gráficas e de software gráfico
para computadores.

## Definição

    Uma função f é uma lei que associa, a cada elemento x em um conjunto chamado Dominpio, exatamente um elemento, chamado f(x), que pertence ao conjunto chamado Contradominío.

Se $ f(x)=2x²-5x +1$ e $ h \ne 0 $, avalie $\frac{f(a + h)-f(a)}{h}

Solução:

$$
f(a+h)=2(a+h)²-5(a+h)+1 \\
= 2(a²+h²+2ah)-5a-5h+1 \\
= 2a²+2h²+4ah-5a-5h+1
$$

Substituindo a função na expressão temos:

$$
\frac{f(a + h)-f(a)}{h}= \frac{2a²+2h²+4ah-5a-5h+1-(2a²-5a +1)}{h}\\
=\frac{(2h²+4ah-5h)+2a²-5a+1-(2a²-5a +1)}{h}\\
=\frac{(2h²+4ah-5h)+(2a²-5a+1)-(2a²+5a+1)}{h}\\
=\frac{(2h²+4ah-5h)}{h}\\
=4a + 2h - 5
$$

Se aplicarmos o conceito de limite quando $h \rightarrow 0$, temos então:

$$
\lim_{h \rightarrow 0} 4x+2h-5 = 4x-5
$$

Desta forma encontramos a derivada da função $f$ em função da váriavel x.

## Representações de Funções

-   Verbalmente (descrevendo-a com palavras)
-   Numericamente (por meio de uma tabela de valores)
-   Visualmente (através de um gráfico)
-   Algebricamente (utilizando-se uma fórmula explícita)

Uma caixa de armazenamento retangular aberta na parte superior tem um volume de 10 m³. O comprimento da base é o dobro de sua largura. O material da base custa 10 por metro quadrado, ao passo que o material das laterais custa 6 por metro quadrado. Expresse o custo total do material como uma função do comprimento da base.

Solução:

A área da base é $2x²$, dessa forma temos que a base custa $20x²$, para as laterais temos que o custo de um seja $xh$ e do outro seja $2xh$, lembrando que são dois lados para cada, tendo então: $2xh + 4xh$. Montando uma equação geral temos:

$$
f(x)=precoBase + precoLaterais = 10(2x²)+6(2xh+4xh)\\
=20x² +36xh
$$

Precisamos encontrar o valor de $h$ uma vez que temos o volume:

$$
v=10\\2x²h=10\\
h = \frac{10}{2x²}\\
h = \frac{5}{x²}
$$

Substituindo $h$ em $f$ temos:

$$
f(x)=10(2x²)+6(2xh+4xh)\\
=20x² +36xh\\
=20x² + 36x(\frac{5}{x²})\\
=20x²+\frac{180}{x}
$$

## Funções Crescentes e Decrescentes

Uma função $f$ é chamada **crescente** em um intervalo $I$ se

$f(x_1)<f(x_2)$ quando $x_1 <x_2$

É doniminada **decrescente** em um intervalo $I$ se

$f(x_1)>f(x_2)$ quando $x_1 <x_2$
