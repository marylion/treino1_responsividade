# Treino 1 - Responsividade
Aprendendo sobre responsividade com Media Query.

Media query é uma técnica CSS introduzida no CSS3.
Ele usa a @mediaregra para incluir um bloco de propriedades CSS somente se uma determinada condição for verdadeira.
Com ela podemos adicionar um ponto de interrupção onde certas partes do design se comportarão de maneira diferente em cada lado do ponto de interrupção.

Exemplo
Se a janela do navegador for de 600px ou menor, a cor de fundo será azul claro:

@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
