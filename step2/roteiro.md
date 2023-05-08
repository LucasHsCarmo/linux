## Linha de comando para obter ajuda

### Diretório onde encontramos mais documentação sobre os pacotes instalados:

```bash
/usr/share/doc/
```

### O que fazer se desejarmos atualizar a base de dados manualmente a qualquer momento?

```bash
locate
sudo updatedb
``` 

### Como podemos fazer para garantir que a nossa busca retorne apenas entradas que de fato existem sem necessariamente rodar o updatedb sempre que quisermos executar o locate?

```bash
locate -e
```

### find para encontrar todos os arquivos que comecem com log no seu diretório atual

```bash
find -name "log*"
```

### Busque apenas pelos links simbólicos no diretório /etc e que contenham a palavra "teste" em qualquer parte do seu nome

```bash
-type: para o tipo de conteúdo que está sendo procurado, nesse caso é um link simbólico "l"

find /etc -type l -name "*teste*"
```

### Encontrar os arquivos que contém "log" ou "2016" em qualquer parte do nome e acessados na última semana

```bash
-o: busca um arquivo que contenha no nome um termo ou outro
-atime -7: localiza apenas os arquivos que foram acessados na última semana

find -name "*log*" -o -name "*2016*" -atime -7
```