## Arquivando arquivos na linha de comando

### Compactar o conteúdo em tar, gzip e bzip2

```bash
compacta em tar

tar -cvf conteudo.tar conteudo/
```

```bash
-z: compacta em gzip

tar -czvf conteudo.tar.gz conteudo/
```

```bash
-j: compacta em bzip2

tar -cjvf conteudo.tar.bz conteudo/
```

### Listar o conteúdo do arquivo .tar

``` bash
-t: listar os arquivos
-f: indica qual arquivo
-v: verbose

tar -tvf conteudo.tar
```

### Descompactar o conteúdo em tar, gzip e bzip2

```bash
descompacta em tar

-x: extrair

tar -xvf conteudo.tar
```

```bash
descompacta em gzip

tar -xzvf conteudo.tar.gz
```

```bash
descompacta em bzip2

tar -xjvf conteudo.tar.bz
```

### Compactando e descompactando conteúdo com zip e unzip

```bash
compactando com zip

-r: recursivo
-q: silencioso

zip -rq conteudo.zip conteudo/
```

```bash
descompactando com zip

unzip -rq conteudo.zip conteudo/
```

### Listar o conteúdo dentro do arquivo, sem que seja necessário descompactar o .zip

```bash
unzip -l conteudo.zip
```