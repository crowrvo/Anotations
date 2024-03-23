Commits são estados do código no qual você pode retornar posteriormente caso necessário, é recomendado fazer constantemente para caso uma alteração no código quebre o aplicativo, seja fácil restaurar até um estado funcional novamente. Para fazer um commit utilize o comando:

```shell
git commit -m "Identificação do commit"
```

É uma boa prática identificar o melhor possível cada commit, para fácil identificação futuramente.

Antes de enviar o seu código para o servidor, você precisa registrar[^1] ele dentro do projeto git, você pode fazer isso usando o comando:

```shell
git remote add origin https://urldoseuservidorderepositorio.com
```

 Após o cadastro, depois de efetuar seus commits, para tornar o código disponível no servidor você precisa executar o seguite comando para enviar ele.

```shell
git push -u origin branch
```

[^1]: É possivel cadastrar mais de um servidor remoto no projeto, por isso é necessário utilizar `-u apelido branch` para informar para qual servidor você deseja enviar essa alteração e qual branch você esta atualizando.