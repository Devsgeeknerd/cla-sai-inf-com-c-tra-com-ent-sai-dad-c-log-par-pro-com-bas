<!-- Título -->
# Saída de Informações — O Comando “printf()”

***Conteúdo da Aula:***

Para escrevermos alguma frase no console, podemos utilizar a função `printf()`.

Ela tem a seguinte sintaxe:

```C
printf(<texto a ser escrito com os formatadores>[, <valores dos formatadores>]);
```

Perceba que precisamos dos formatadores que utilizamos na função `scanf()` também no `printf()`, para determinar que tipo de informação que desejamos escrever, quando quisermos utilizar os valores de variáveis.

Verifique o exemplo abaixo:

```C
// Irá escrever "Olá mundo!".
printf("Olá mundo!");
int a = 3;
// Irá escrever "Valor de a: 3" - %d será substituído pelo valor de a, interpretado como um inteiro.
printf("Valor de a: %d", a);
int b = 1;
// Irá escrever "Valor de a e b: 3 e 1.
printf("Valor de a e b: %d e %d", a, b);
```

Também podemos exibir números de ponto que possuem precisão de casas decimais usando a marcação `%f`:

```C
float numero = 123.889999;
printf("%f", numero);
```

Podemos ainda formatar esse o número dizendo quantas casas queremos depois da vírgula, conforme os exemplos abaixo:

```C
float numero = 123.889999;
printf("%.2f", numero);
printf("%.3f", numero);
printf("%.4f", numero);
```

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-sai-inf-com-c-tra-com-ent-sai-dad-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-sai-inf-com-c-tra-com-ent-sai-dad-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-sai-inf-com-c-tra-com-ent-sai-dad-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-sai-inf-com-c-tra-com-ent-sai-dad-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-sai-inf-com-c-tra-com-ent-sai-dad-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-sai-inf-com-c-tra-com-ent-sai-dad-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
