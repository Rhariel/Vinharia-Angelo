Vinheria Agnelo

A vinheria agnello:
como  passar o tempo e a modernização do atedimento, a vinheria agnelo precisou se modernizar, este site foi projetado para que a vinheira entre nomercado de vendas remotas.

paginas:
index:Primeira pagina com vinhos mais comuns de serem vendidos e uma mensagem de bem vindo
pag1:pagina contando um pouco da historina da vinheira
pag3:pagina principal de produtos
pag4:pagina para contato


integrantes:
Rhariel RM:566310
Francisco Nogueira de Queiroz RM:566309
Sara Marangon de Macedo RM:563807
Bruna Sadi Duarte RM:561870
Bernardo Moreira Lopes Sousa RM:564103

https://rhariel.github.io/Vinharia-Angelo/

Efeitos visuais:
A animação foi aplicada em todos os H1 que tiverem a classe txtAnimado, essa animação vai fazer com que ao carregar a página, seu título se desloque 20px(com transform: translateY(20px)) pra baixo e depois volte pra posição normal. Como usamos   animation: Subir 1s ease-out forwards, o ease-out vai fazer com que a animação comece rápido e termine devagar, e o forwards vai fazer com que o estado final da animação permaneça depois que a animação terminar.

Foi usado a pseudo-classe "hover" em todos o elementos com a class: "card-vinho", para que quando o usuário passe o cursor pelo card do vinho o texto sofra um efeito alterando sua cor para uma cor vinho escuro e faz com que o texto fique sublinhado. Foi usado também nos botões de "enviar" e "limpar" e nos botões de navegação do menu. Foi aplicado um hover na imagem com a class: "ceo", para que quando o usuário passa o mouse por ela, cria um efeito visual em que ela aumenta de tamanho em escala 1.1 e cria um pouco de sombra a seu redor. Adicionei a pseudo-classe "focus" nos locais de "tetxarea" para que ao clicada para digitação, cria uma borda ao redor da área de texto. Por fim, usei mais uma pseudo-classe chamada "invalid", usada na área do input do email. Se o email digitado for invalido, cria uma cor de fundo alaranjada.

.gallery img:hover{
  transform: translate(10px, 10px); /* Transforma o tamanho da imagem com hover */
  transform: skew(1deg, 1deg); /* Transforma a rotação da imagem com hover */
}

.card-vinho h3::first-letter{
  color: #800000; /* Muda a cor da primeira letra da classe */
  font-size: 20px; /* Muda o tamanho da primeira letra da classe */
}
