[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fagnerpsantos/)](https://www.linkedin.com/in/fagnerpsantos/)

# Olá e seja bem vindo ao  meu repositório
## Conheça o Semaforo
![](https://github.com/thiagodpaulla/semaforo.github.io/blob/main/Sem%C3%A1foro%20.gif)
## Fique a vontade para interagir com o projeto no link:
https://thiagodpaulla.github.io/semaforo.github.io/

### Entenda um pouco mais sobre como foi criado.


# 💻 Projeto
semaforo.github.io

Procurando fazer um código semântico e limpo, pensando nas funções pequenas e de responsabilidade única
Foram 4 imagens e 4 comandos

Utilizei o VScode
Dentro do HTML eu criei uma div img e na sequencia em outra div criei quatro botões e atribui a eles um id relativos a cor do semáforo e um a função automático.
Dentro do HTML eu fiz a chamada do arquivo JS e também do CSS que é um css básico onde existe uma centralização, e algumas orientações para o main, como altura etc e um gap(espaço) de 10vh entre as duas dives para não ficarem coladas a imagem aos botões.

Dentro do Arquivo JS foram feitas os seguintes passos:

Declarei um objeto const para receber o id img e na sequencia criei um elemento pai e atraves do elemento pai eu sei e qual dos elementos o usuário clicou.
isso foi feito criando um const que recebeu o arquivo o id Button anteriormente declarado e na sequencia usei o addEventListener para escutar em qual botão o usuário estava clicando pela função traffcLigth e atribui a uma errolfunction

Mas como saber em qual botão ele clicou ?
Quando atribuímos uma função ao addEventListener ou callback, este callback recebe um argumento do addEventListener e este argumento é o evento em que foi clicado, e ele armazena uma serie de informações inclusive o target de qual botão foi clicado.
com isso é possível atribuir este evento a uma const e assim poder ter controle do que fazer com cada interseção do usuário.

após isso foi criado uma objeto turnOn onde o programa passou a a receber as funções das imagens.

Mas com se chama o método de um objeto ?
Lembrando que as informações inseridas dentro de um objeto recebe (,) e não (;) pois é como se tudo fosse uma linha só.
usando o evento, o alvo, e o id do alvo ficando [event.target.id]

Usando uma função de intervalo no java script

usando o setInterval que executa uma função dentro de um intervalo de tempo que é determinado a ele, aqui no caso foi definido 1segundo.


Para isso eu tive que criar uma função changecolor, e usando um array com as cores.
depois criando uma variável global tipo let.(pois ela vai mudar)

Função ternaria primeiro ele adiciona mais um, depois ele atribui dentro de uma errol function.




# 🚀 Tecnologias

O projeto foi desenvolvido usando as seguintes tecnologias


➜ JavaScript

➜ HTML

➜ CSS


# 📂 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.


Gostou? entre em contato comigo e vamos conversar 

➜ https://www.linkedin.com/in/thiagodepaulla/ 
