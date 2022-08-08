# O QUE É UM TERMINAL?

Antigamente, a entrada de dados, em um computador, era feita por meio de um Terminal, interface textual, que era constituída por um monitor e teclado, ligados a uma máquina robusta, onde os dados eram processados.

Através dessa máquina, conhecida como Terminal, tinha-se acesso ao sistema de computadores e suas funcionalidades, também acessadas atualmente por meio do teclado e mouse. Portanto, caso o usuário desejasse navegar pelos diretórios, procurando por algum arquivo, ao invés de utilizar o mouse e ir clicando nas pastas, tudo isso era feito através de comandos digitados na interface textual.

Existem diversos programas que emulam um Terminal. Nos computadores da atualidade, ao usarmos o Terminal, que geralmente vêm instalados junto com os Sistemas Operacionais, na realidade estamos executando um programa que simula aquela máquina do passado, entretanto, é possível instalar diferentes Terminais.

# O TERMINAL LINUX

O terminal Linux, que também pode ser chamado de shell, programa que possibilita ao usuário acessar recursos do Sistema Operacional e também garantir a comunicação entre o núcleo do Sistema Operacional e as aplicações/programas, é basicamente uma ferramenta que recebe instruções digitadas por usuários ou usuárias a partir de um periférico como o teclado, ou seja, é um tipo de interface dentre várias, atualmente, uma das mais utilizadas entre os profissionais de TI. Alguns tipos de terminais, também conhecidas como distribuições, usadas são o  Linux Mint, Kali Linux, Manjaro,  Debian,  Tails,  CentOS,  Ubuntu.

# COMANDOS LINUX

Alguns dos comandos mais utilizados no terminal Linux são:

pwd - encontrar o caminho para o diretório atual em que você está.
cd - permite navegar até determinada pasta.
ls - visualizar conteúdos em um diretório.
cat - visualizar o conteúdo de um arquivo na saída padrão.
cp - copiar arquivo do diretório atual em que você estiver.
mv - mover arquivos.
mkdir - criar um novo diretório (pasta).
rmdir - apagar um diretório vazio.
rm - apagar um diretório e todos os conteúdos que estiverem lá dentro.
touch - criar novos arquivos em branco através de uma linha de comando.

# O QUE É GIT?

O Git é um projeto aberto, desenvolvido pelo criador do Linux, Linus Torvalds, disponível para diversos sistemas operacionais, como Linux, Mac e Windows. O objetivo principal do Git é ser um sistema de controle e organização que auxilia no armazenamento e revisão de projetos voltados para códigos de programação e qualquer tipo de arquivo que serão armazenados na plataforma GitHub. Ou seja, é usado principalmente no desenvolvimento, entretanto pode ser usado para registrar o histórico de edições de um projeto de qualquer tipo de arquivo. Através de diversos comandos, usados no terminal, o usuário poderá criar repositórios, armazenar e editar diversos arquivos.

# COMANDOS GIT

“git init” - Este comando é usado para criar um novo repositório GIT.
“git config” - Pode ser usado para definir valores de configuração específicos do usuário como e-mail, nome de usuário e formato de arquivo etc. Exemplo:
git config --global user.name "Seu nome aqui"
git config --global user.email "seu@email.aqui"
“git add” - pode ser usado para adicionar arquivos ao índice. Exemplo:
git add .
“git commit” - usado para confirmar as alterações na cabeça. Normalmente usado:
git commit -m “mensagem”
“git status” - exibe a lista de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados.
“git remote” - permite que um usuário se conecte a um repositório remoto. Exemplo:
git remote add origin https://github.com/user/repositorio
“git log” - exibe uma lista de compromissos em uma ramificação, juntamente com os detalhes pertinentes, como todos os commits.
“git push” - envia as alterações feitas para o ramo mestre do repositório remoto associado ao diretório de trabalho. Exemplo:
git push -u origin main
“git branch” - pode ser usado para listar, criar ou excluir ramos. Exemplo:
git branch -M main
“git rm” - pode ser usado para remover arquivos do índice e do diretório de trabalho. Exemplo:
git rm filename.txt

Após começar um projeto, caso queira criar um repositório e salvar seu projeto online, basta criar uma conta no GitHub (https://github.com/), baixar e depois configurar o Git no seu site oficial (https://git-scm.com/), abrir o terminal na sua máquina, através de comandos, entrar na pasta do seu projeto e digitar os seguintes comandos:

1. git init (Para iniciar o repositório)
2. git config --global user.name "Seu nome aqui" (Para configurar seu nome)
3. git config --global user.email "seu@email.aqui" (
4. git add .
5. git commit -m "Primeiro commit"
6. git remote add origin https://github.com/user/repositorio 
7. git branch -M main
8. git push -u origin main

# REFERÊNCIAS

* <https://dev.to/womakerscode/o-que-e-o-terminal-1bgp>
* <https://blog.betrybe.com/terminal-linux/#1>
* <https://www.hostinger.com.br/tutoriais/comandos-linux?ppc_campaign=google_performance_max&gclid=Cj0KCQjwxb2XBhDBARIsAOjDZ369cFF5AcAX4KLXrekm10XWy_0LMugsCCAt5oRVTdjny8m3jesxCgMaAuZbEALw_wcB>
* <https://help.ubuntu.com/kubuntu/desktopguide/pt_BR/terminals.html>
* <https://www.hostinger.com.br/tutoriais/comandos-basicos-de-git?ppc_campaign=google_performance_max&gclid=Cj0KCQjwxb2XBhDBARIsAOjDZ36wHqtyAKztLQ3EQc1mb66uLpWEhUQxEvSXC-5wB6ctkgp3c_k3B_8aArMOEALw_wcB>
