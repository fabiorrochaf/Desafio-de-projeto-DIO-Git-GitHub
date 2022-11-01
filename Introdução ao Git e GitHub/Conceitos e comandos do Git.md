# Git/GitHub :book:

### O que é Git ?:thinking:

Git é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

### Funcionamento do Git 

- **SHA1** - (Secure Hash Algorithm), é um conjunto de funções hash criptográficas. A encriptação gera um conjunto de caracteres identificador de 40 dígitos (muda a cada alteração). É uma forma curta de representar um arquivo. 

  comando- openssl sha1 "arquivo"

  ### Objetos internos 

- Blobs

- Trees

- Commits

   Blob é o tipo de objeto usado para armazenar o conteúdo de cada arquivo em um repositório. O hash SHA-1 do arquivo é calculado e armazenado no objeto do blob. Esses pontos de extremidade permitem que você leia e grave objetos de blob no banco de dados do Git no GitHub. 

  Tree cria a hierarquia entre arquivos em um repositório do Git. Você pode usar o objeto da árvore do Git para criar a relação entre diretórios e os arquivos que eles contêm. Esses pontos de extremidade permitem que você leia e grave objetos de árvore no banco de dados do Git no GitHub.

  Commit é o objeto mais importante. São as unidades estruturais de um cronograma de projeto Git. Podem ser considerados instantâneos ou marcos ao longo do cronograma de um projeto. 

### comandos básicos de navegação no Git	

ls - Listar diretórios

ls - a - arquivos ocultos

cd- Navegar entre as pastas

cd ..- Retroceder um  nível na navegação

clear/Ctrl L- Limpar terminal

Tab - Auto-completar

mkdir - Criar uma pasta/diretório

echo  >- Criar arquivos

rm -rf- Deletar diretório

mv- Mover



### Comandos básicos para criar um repositório



git init- Inicializa/cria um repositório

git add *- adiciona uma alteração no diretório ativo à área de staging

git commit -m "mensagem de texto"- captura um instantâneo das mudanças preparadas do projeto no momento. 

git status- Exibe as condições do diretório de trabalho e da área de staging





