Após sua instalação, é necessário configurar algumas opções globais, que são recorrentes em diversas aplicações e bem importa de ser feita logo de inicio. Essas configurações podem ser feita utilizando os seguintes códigos: 

Para definir o nome da branch padrão a ser criada ao iniciar um repositório:
```shell
git config --global init.defaultBranch main
```

Para definir o seu nome de exibição:
```shell
git config --global user.name "name"
```

Para definir o seu email:
```shell
git config --global user.email "name@email.com"
```

Após as configurações, você ja pode livremente criar um repositório utilizando o comando:
```shell
git init
```

Depois de iniciar seu repositório, você deve informar os arquivos que serão versionados utilizando o seguinte comando:
```shell
git add "pasta, arquivo ou glob ou --all para dicionar todos os diretórios"
```

Também é possível ver as alterações feitas utilizando o comando:
```shell
git status
```

É preciso levar em consideração também, quais arquivos estamos levando para o servidor, principalmente em caso de repositórios públicos, pois podemos por acidente subir algum arquivo com informação sensível, como arquivos de build e temporários, arquivos desnecessariamente grandes, senhas ou acessos a banco de dados, algo que realmente queremos evitar. Isso pode ser feito, utilizando o arquivo .gitignore, no qual descrevemos quais arquivos, diretórios ou [[expressões]] que normalmente pode ser adicionado por meio de [[CLI]] das ferramentas.
