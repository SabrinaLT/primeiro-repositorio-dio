## **Tópicos Fundamentais**
<br>

- _Sha1_

<br>

Significa Secure Hash Algorithm (Algoritimo de Hash Seguro), é um conjunto das funções de hash criptográficas projetadas pela NSA (Agência de Segurança NAcional do EUA).
Essa encriptação gera um conjunto de caracteres identificadores de 40 dígitos, para cada alteração realizada no arquivo um novo Sha é gerado.

<br>

- _Objetos fundamentais_

<br>

1- Bloobs
É um objeto que armazena os arquivos, ele armazena metadados dentro dele onde é mostrado o tipo do objeto, o tamanho do arquivo, conteúdo do arquivo e uma \0, o Bloob guarda apenas o Sha do arquivo. 

<br>

2- Trees
As árvores armazenam os Bloobs, ou seja o bloob é o bloco básico e a árvore aponta para os blobs. A árvore também pode apontar para outras árvores, por exemplo, pode haver diretórios dentro de outros diretórios. Como as árvores também armazenam metadados ela também possuí um Sha. 

<br>

3- Commits
O commit ele aponta para uma árvore, aponta para um parente, para um autor e para uma mensagem, ele junta todos arquivos dos bloobs e árvores, ele trás a informação de data e hora de quando foi criado. O Sha1 de um commit é o hash de toda essa informação. 

<br>

- _Sistema distribuído Seguro_

<br>

O código é mantido em um servidor e pode ser baixado localmente em diversas máquinas, por isso caso ocorra um problema no servidor é possível manter o projeto caso estejam salvos nessas máquinas, dificilmente você perderá seu trabalho.

<br>
<br>


# Comandos 

<br>

- ls = lista os repositórios e arquivos
- ls -a = lista arquivos ocultos
- cd c/ ou d/ = acessa o repositório informado após o cd
- cd .. = volta um repositório
- git init = inicia um repositório
- git config --global user.email "email" = inserir seu e-mail
- git config --global --unset user.email = remover seu e-mail
- git config --global user.name "nome sem aspas" = inserir seu nome
- git config --global --unset user.name = remover seu nome
- git config --list = lista de configurações
- git remote add origin "link github sem aspas" = puxa um repositório remoto
- git remote -v = lista os repositórios remotos
- git clone "link sem aspas" = clona um repositório do github para a maquina
- git add . = adiciona os arquivos que foram alterados
- git commit -m "Comentário" = fazer um commit com um comentário
- git status = informa o que está pendente e o que precisa ser feito
- git push origin master = envia o repositório local para o remoto
- git pull origin master = puxa o repositório remoto para a maquina
- mkdir = criar um repositório
- mv arquivo.md ./diretório/ = move um arquivo pra outro diretório

<br>

### **Github é um repositório remoto onde guardamos nosso código, esse código pode ser público, onde qualquer pessoa tem acesso ou privado.**


