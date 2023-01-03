# Estágios do Git
O git possui 3 estágios.
- Working Directory
- Staging Area
- .git directory (Repository)

## Working Directory
Corresponde ao estado do nosso diretorio atual de trabalho.

## Staging Area
Para ir para o staging área é necessário usar o comando ```git add``` onde ele adiciona o arquivo correspondente do Working Directory para o Staging Area.

## .git Directory (Repository)
Para ir para .git Directory é necessário usar o comando ```git commit -m "Message Commit"```. Nesse caso a mensagem deve ser informativa para registrar o que estamos fazendo.
Aqui criamos um ponto no histórico do git.


## Comandos
```git add```

Move o arquivo do Working Directory para Staging Area


```git config --global user.name "Your Name"```

Configura globalmente o nome do usuário para registrar dentro do git.

```git config --global user.email "Your Email"```

Configura globalmente o e-mail do usuário para registrar dentro do git.

```git config -l```
Lista as configurações atuais do git.