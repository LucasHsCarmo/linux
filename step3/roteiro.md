## Diretórios e listagem de arquivos e gerenciamento de arquivos

### Diretório atual

```bash
.
```

### Comandos ls * e ls -R

```bash
ls * : lista tudo que está referenciado apenas no diretório atual
```

```bash
ls -R : além de listar tudo que está incluso no diretório atual, também lista todos os subdiretórios.
```

### Informações sobre o diretório /var em si, e não sobre o conteúdo do diretório, devemos executar

```bash
ls -ld /var
```

### Comando para listar os arquivos com informações detalhadas, incluindo ocultos, ordenados pelo tamanho, do menor para o maior

```bash
ls -laSr
```

### Comanda mkdir -p

```bash
mkdir -p : é utilizado para criar subdiretórios de diretórios de forma recursiva

mkdir -p devops/linux/step{1,2,3}
```

### Comandos para touch

```bash
touch:  define os tempos de modificação e acesso dos arquivos. Se algum arquivo não existir, ele será criado com as permissões padrão.

Alterar apenas a data de modificação
-m

Alterar apenas a data de acesso
-a

Não criar o arquivo caso ele não exista
-c
```

### Comando podemos utilizar para excluir três diretórios VAZIOS de um só vez?

```bash
rmdir -p devops/linux/step3/

-v de verbose -> rmdir -vp devops/linux/step3
```

### Comando remove diretórios de forma recursiva com CONTEÚDO

```bash
rm -r devops/linux/step3/
``` 