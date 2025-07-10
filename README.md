## BH-Alertas

Projeto fruto de um trabalho em grupo proposto pela faculdade, onde era necessário o desenvolvimento de um sistema web fullstack.

## Objetivo do Trabalho

Projeto que se consiste em um sistema web que tem como finalidade o alerta e a conscientização da população belo horizontina de problemas ambientais na região, além de permitir
que os usuários denunciem tais problemas as autoridades cabíveis, tudo isso nessa simulação.

## Tecnologias Utilizadas

-HTML5 
-CSS3 
-JavaScript
-Node.js
-Express
-MongoDB

## Integrantes do projeto:
- Asafe Orneles ( Backend - Integração com banco de dados,funções internas e mecanismos para guardar as informações )
- Matheus Serqueira ( Frontend - Página de login e página inicial ) 
- Lucas Tavares ( Backend - Auxílio no Backend )
- Davi ( Frontend - Páginas de conscientização e denúncias, navegação entre páginas )  

## Principais desafios:

- Responsividade 
- Planejamento inicial de como deveria funcionar o sistema
- Desenvolvimento em conjunto

## Responsividade:

Durante a criação das páginas, priorizei o desenvolvimento de interfaces simples, porém funcionais aos usuários, visando também tornar o sistema utilizável em diferentes dispositivos.
Utilizando Media Queries em CSS, consegui tornar responsivas a maioria das páginas,  com exceção da página de educação, que não pude replicar
na mesma qualidade, provavelmente por equívoco na estruturação HTML inicial, ou imagens muito grandes.

## Planejamento do Site:

O Objetivo do trabalho nos fez pensar no desenvolvimento do sistema como se fóssemos entregar um produto, portanto, nos atentamos a organização
de pastas, como poderíamos resumir nosso código e também como facilitar a programação em grupo. O integrante Asafe se responsabilizou por
esquematizar a divisão de pastas e como seria o modelo inicial, enquanto eu, durante chamadas que fazíamos para trabalhar em conjunto, contribui
dando idéias de como poderia ser trabalhada a arquitetura do front-end e as respectivas páginas para facilitar nosso trabalho.

## Desenvolvimento em conjunto:

Trabalhar em conjunto todos com o mesmo código no começo foi algo bem difícil, mas essa dificuldade foi rapidamente superada, pois aprendemos
a utilizar melhor o GitHub com as funções de Fork e realizamos chamadas diariamente para contribuir com a produtividade, portanto no final
conseguimos superar e finalizar o trabalho.

## Considerações Finais:

O Projeto também me ajudou bastante como programador, pois apesar de não ter usado um Framework na minha parte que é o React, trabalhei
com conceitos frequentemente requisitados como HTML, CSS e JavaScript, pude aprender a utilizar e rodar um pouco do banco de dados MongoDB,
trabalhar em grupo e conhecer melhor o uso do Git e GitHub, facilitando o desenvolvimento em conjunto, e trabalhar o pensamento não só
técnico da programação, mas começar a pensar no sistema como um produto e o que seria interessante nesse aspecto. 

## Aqui está o sistema totalmente utilizável online:

Frontend: [BH-Alertas](https://bh-alertas-oyvn.vercel.app/)
Backend: [BH-Alertas Backend](https://bh-alertas-backend.onrender.com)

## Observações sobre deploy e estabilidade:

Por estar deployado online em serviços gratuitos, o backend pode apresentar lentidão ou timeout em algumas situações, 
entretanto, mesmo com isso o frontend funciona normalmente na maior parte do tempo. Além disso, não consegui ter 
acesso as funções de administrador, pois optamos por deixar o acesso com os responsáveis pelo backend.

## Imagens de Demonstração :

![image](https://github.com/user-attachments/assets/f09e66f1-1960-490f-a282-f6cfce1b56f7)
*Página Inicial*

![image](https://github.com/user-attachments/assets/eef1a53c-8c32-4788-b622-f0478c5e4188)
*Página de Educação/Conscientização*

![image](https://github.com/user-attachments/assets/8f368631-5332-4672-b2b8-0701ed83ffb1)
*Página de Denúncias, em baixo um chamado que criei apenas para demonstração*

![image](https://github.com/user-attachments/assets/fdd3217b-6a7a-4741-9d81-cdebdadbc846)
*Página de Alertas, onde é possível ver todos os alertas feitos pelo administrador*

![image](https://github.com/user-attachments/assets/7544aab7-82fd-4f7a-9bba-6c8c57bf54e9)
*Página de Login para administrador*



## Rode o projeto localmente:

### Pré-requisitos:

- Node.js instalado
- Mongo.db instalado ( normal ou versão zip )

### Clone o repositório

git clone https://github.com/DaviAntonioMendesGaiga/BH-Alertas.git

### Instale as dependências do backend

No terminal do seu editor de código digite:

1- cd projet-alertas/backend
2- npm install

### Crie o arquivo .env manualmente 

Na pasta backend/, crie um arquivo chamado .env com o seguinte conteúdo:

MONGO_URI=mongodb://localhost:27017/bh-alertas

OBS: O arquivo .env não está no repositório por motivos de segurança, por isso é necessário criá-lo manualmente.

### Rode o MongoDB no seu prompt de comando:

No cmd, escreva:

"Caminho_para_o_mongodb"\mongod.exe --dbpath "Caminho_para_sua_pasta_data"

OBS: As expressões em aspas significam que esse caminho varia de dispositivo para dispositivo, pois depende de onde você irá instalar o MongoDB.
Importante: Não fechar o CMD durante a execução do código, ele precisa ficar aberto pois representa o banco de dados online.

### Rode o backend 

No editor de código, na pasta backend, digite:

node server.js

OBS: Provavelmente aparecerá

Servidor rodando na porta 5000  
✅ Conectado ao MongoDB!

Se isso aparecer, deu certo.

### Acesse no navegador:

Basta acessar esse link: http://localhost:5000/

OBS: Caso dê erro, substituir o número da porta do localhost para a porta que o servidor está rodando no seu caso.



