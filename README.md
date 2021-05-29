# VETS

<img src="https://i.ibb.co/gz1bcVx/LOGO.png" width="300">



Projeto integrador do curso de Análise e desenvolvimento de sistemas
<br>

### 1. APRESENTAÇÃO
A Vets irá conectar as clínicas veterinárias e usuários donos de pets em geral, assim facilitando a procura de uma clínica quando necessário, informação que nem sempre é fácil achar pela internet. A versão final estará disponível em web e aplicativo mobile, onde um usuário conseguirá localizar clínicas veterinárias e petshops mais próximos assim como seus serviços e contatos. As clínicas poderão ser avaliadas por usuários cadastrados, sendo como diferencial o ranking de avaliação para quem busca o melhor atendimento para os seus pets.

### 2. EQUIPE

👤 **Gustavo Gomes**

- Função: Dev
- Linkedin: [@gustavogomes](https://www.linkedin.com/in/gustavoogomess/)

👤 **Wilson Arid Look**

- Função: Dev
- Linkedin: [@wilsonlook]()

👤 **João Adolfo**

- Função: Dev
- Linkedin: [@joaoadolfo]()

👤 **Deise de Oliveira**

- Função: Dev
- Linkedin: [@deiseoliveira]()

👤 **Marcos Martins**

- Função: Dev
- Linkedin: [@marcosmartins]()

👤 **Davi Jose**

- Função: Dev
- Linkedin: [@davijose]()


### 3. ESPECIFICAÇÃO

> #### 3.1 Banco de dados Modelo Lógico

<img src="https://i.ibb.co/h8VxBN5/Modelo-L-gico.png" width="700"> 


> #### 3.2 Funcional

- [X] Localização de Clínicas: 

Deve haver uma interface de localização das clínicas e
estabelecimentos próximos e podendo visualizar mais informações sobre os mesmos, como
contato, serviços oferecidos e avaliações, sendo opcional ser conforme a localização do usuário
ou não, e não é obrigatório estar logado na plataforma para localizar os provedores de serviços.

- [X] Avaliação das Clínicas:

Nas telas de informações das clínicas, haverá um espaço para avaliação das mesmas, onde usuário cadastrados e logados podem inserir uma curta resenha sobre a
clínica, que poderão ser visualizadas por todos os utilizados junto as principais informações da
clínica em si.

- [X] Portabilidade:

A aplicação deverá funcionar tanto em web quanto em smartphones que possuem acesso à internet.

<img src="https://i.ibb.co/hMvJjRG/Vet-Use-Case.png" width="700"> 


<br> <br> <br> <br>


### 3.1 - Apresentação do Sistema 

<img src="https://i.ibb.co/x1B1cdv/login-hotfood.jpg">

> Tela de login 

<img src="https://i.ibb.co/St6MVB6/index-hotfood.jpg" width="3000">

> Tela inicial da Aplicação 

### 4 Tecnologias envolvidas

<p align="left"> 
<a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/></a>  CSS

<a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/></a>  HTML 

<a href="https://www.java.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/></a>  Java 

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>  JavaScript </p>



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
