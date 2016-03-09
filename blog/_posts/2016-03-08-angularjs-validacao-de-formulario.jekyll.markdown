---
layout: post
title:  "Validando Formulários com AngularJS"
date:   2016-03-08 21:27:36 -0300
categories: javascript angularjs
img: /assets/form-validation-angular.png
---
Essa semana passei por um problema que creio que todos desenvolvedores web já se depararam ( e se você chegou até aqui é porque deve esta passando por ele). Um problema que a princípio é bastante simples, mas dependendo do projeto pode se chato para implementar.  
  
**Validação de Formulários** no front-end sempre é favorável ao UX da aplicação, porém fazer as validações de uma maneira simples para o usuário nem sempre é uma tarefa fácil. O problema que passei foi para fazer estas validações utilizando o **AngularJS** e foi por isso que escrevi este artigo. Então sem mais enrolação e vamos *Kodar*:  

## Validações

- Todos os campos são obrigatórios
- A **senha** e **contra-senha** devem ser iguais
- O campo **cpf** só deve receber números 
- *Bonus Stage:* o **cpf** deve ser um cpf válido

# Estão prontas crianças?  
Vamos começar criando um formulário bastante simples com os campos **usuario**, **senha**, **contra-senha** e **cpf**. Para não ficar apenas o html feio e sem graça, utilizaremos o [Twitter Bootstrap](http://getbootstrap.com/) como base de estilo e um arquivo css chamado *main.css* que utilizaremos como firula (afinal de contas, é disso que o cliente gosta xD).

![teste](/assets/form-validation-angular.png)  
  
# Vamos precisar de 3 arquivos
- ```index.html``` Nossa view para exibir o formulário
- ```main.css``` Nossa firula só para vocês copiarem o meu "design" =]
- ```app.js``` Nossa controller do AngularJs





