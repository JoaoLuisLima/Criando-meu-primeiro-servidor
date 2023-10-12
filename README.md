# Criando-meu-primeiro-servidor
Como criar um servidor e o pôr para rodar usando o VS Code e o Node.Js

Colocando o primeiro servidor para rodar
Crie uma pasta com o nome Servidor
Acesse a pasta no seu VsCode
Crie um arquivo com o nome .gitignore
Crie uma pasta chamada src
Dentro de src crie um arquivo chamado index.js
Abra seu terminal integrado ao VsCode
Inicialize o projeto com os seguintes comando:

npm init -y    
npm install express<br>
npm install nodemon -D

Agora o arquivo package-lock.json foi criado. Este arquivo lista as bibliotecas que já foram baixadas no projeto .<br>
Também foi criado o arquivo node_modules, para armazenar as bibliotecas.
Agora o seu explorer no VS Code deve estar assim:

![imagem](https://user-images.githubusercontent.com/142345770/274467147-5bb162e1-dc8d-408f-bbef-64a082532c80.png)

Entre no arquivo package.json e deixe o seu script assim:

![imagem](https://user-images.githubusercontent.com/142345770/274475164-4dd9825e-3d2c-4585-85ce-24954d6862dd.png)
Isso servirá para iniciar o servidor Node.js usando o pacote Nodemon, fazendo com que o servidor seja reiniciado 
automaticamente sempre que você fizer alterações no código.

Voltando ao seu index instancione o expresse com os seguintes códigos:
![imagem](https://user-images.githubusercontent.com/142345770/274466338-9f8f7e09-0041-4645-b92c-70304e64a8f2.png)

Agora com a pasta do index.js aberta em seu terminal, digite o comando:
npm run dev .
Isso irá inicializar o seu servidor.
O seu terminal deverá ficar assim:

![image](https://github.com/JoaoLuisLima/Criando-meu-primeiro-servidor/assets/142345770/cec8b452-29a9-48fb-9396-844f7294d37e)

Pronto, seu servidor esta rodando. Agora é só testar no navegador.
Use a url:
http://localhost:3000

![image](https://github.com/JoaoLuisLima/Criando-meu-primeiro-servidor/assets/142345770/3769d9a3-77d1-46b8-9c5a-42352fdfe8b8)



