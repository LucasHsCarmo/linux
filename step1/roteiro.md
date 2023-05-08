## noções básicas de linha de comando

### Variável local

```bash
nome=Lucas
env echo $nome, bem vindo.

export -n nome
```

### Váriavel de ambiente para buscar os executáveis

```bash
echo $PATH
```

### Como podemos descobrir qual o caminho do executável que será executado ao executarmos um comando?

```bash
which <executavel>
```

### Por outro lado, ele procura apenas os arquivos binários, de origem e de página de manual de um comando

```bash
whereis <executavel>
```

### Extrai as informações das páginas de manual relacionadas.

```bash
whatis <executavel>
```

### Qual seria uma forma de executar dois comandos em sequência de forma que o segundo não dependa do resultado do primeiro?

```bash
ls;echo "Listagem finalizada"
```