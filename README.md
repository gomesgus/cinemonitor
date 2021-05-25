# VETS

<img src="https://i.ibb.co/gz1bcVx/LOGO.png" width="300">



Projeto integrador do curso de Análise e desenvolvimento de sistemas


### 1. APRESENTAÇÃO
Plataforma que conecta clínicas veterinárias e usuários donos de pets em geral, assim facilitando a procura de uma clínica quando necessário, informação que nem sempre é fácil achar pela internet.

### 2. EQUIPE
|Nome|Papel|LinkedIn|
|--|--|--|
|Gustavo Gomes|Dev|https://www.linkedin.com/in/gustavoogomess/|

### 2. ESPECIFICAÇÃO

>Banco de dados Modelo Lógico

<img src="https://i.ibb.co/h8VxBN5/Modelo-L-gico.png" width="700"> 



#### 2.1 -ATORES 
-Usuário </br>
-Clínica

#### 2.2 -FUNCIONAL
- [X] Cadastro de alimentos
- [X] Exclusão de alimentos
- [X] edição de alimentos cadastrados por parte do doador
- [x] Painel de alimentos 
- [x] Informações sobre os alimentos a serem doados 
- [X] Cadastro de usuário 
- [X] Edição do cadastro do usuário
- [x] Notificação em alimentos que estão com tempo para serem doados
- [x] Notificações em tempo real para que o doador receba informações de quem quer o alimeto
- [x] Notificação inversa onde o donatário recebe em tempo real informações e situação de estado do pedido feito

>Use Case

<img src="https://i.ibb.co/1LdGDBr/caso-de-uso-hotfood.jpg">


### 3.1 - Apresentação do Sistema 

<img src="https://i.ibb.co/x1B1cdv/login-hotfood.jpg">

> Tela de login 

<img src="https://i.ibb.co/St6MVB6/index-hotfood.jpg" width="3000">

> Tela inicial da Aplicação 

#### 4 - Tecnologias envolvidas

- [PHP](https://https://www.php.net//)
- [Laravel](https://laravel.com/)


#### 5 - Como rodar o projeto em sua maquina ?

- Para rodar esta projeto em sua maquina você precisará instalar:
- [PHP] maior que 7.4 (https://https://www.php.net//)
- [Laravel] (https://laravel.com/)
- [Composer] (https://getcomposer.org/) 
- Logo após isso quando você clonar o projeto em sua maquina modifique o .envexemple para . envi e faça as configurações em sua maquina.
#### - Configurações:
- 1.composer install && yarn dev
- 2.php artisan key:generate
- 3.php artisan storage:link
- 4.Editar as configurações doo banco para as configurações da máquina 
- 5.composer dump-autoload && php artisan optimize:clear
- 6.yarn dev 
- 7.php artisan serve
