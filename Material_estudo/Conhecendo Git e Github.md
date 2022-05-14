# Git

É um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo (Exemplo: alguns livros digitais são disponibilizados no GitHub e escrito aos poucos publicamente). O Git foi inicialmente projetado e desenvolvido por Linus Torvalds para o desenvolvimento do kernel Linux, mas foi adotado por muitos outros projetos.

Cada diretório de trabalho do Git é um repositório com um histórico completo e habilidade total de acompanhamento das revisões, não dependente de acesso a uma rede ou a um servidor central. O Git também facilita a reprodutibilidade científica em uma ampla gama de disciplinas, da ecologia à bioinformática, arqueologia à zoologia.

Sendo um software livre, distribuído sob os termos da versão 2 da GNU General Public License. Sua manutenção é atualmente supervisionada por Junio Hamano.



#### Desempenho

As características brutas de desempenho do Git são muito fortes quando comparadas a muitas alternativas. Fazer o commit de novas alterações, branches, mesclagem e comparação de versões anteriores – tudo é otimizado para desempenho. Os algoritmos implementados no Git aproveitam o conhecimento profundo sobre atributos comuns de árvores de arquivos de código-fonte reais, como costumam ser modificados ao longo do tempo e quais são os padrões de acesso.



#### Segurança

O Git foi projetado com a integridade do código-fonte gerenciado como uma prioridade. O conteúdo dos arquivos, bem como os verdadeiros relacionamentos entre arquivos e diretórios, versões, tags e commits, todos esses objetos no repositório do Git são protegidos com um algoritmo de hash de criptografia seguro chamado SHA1. Isso protege o código e o histórico de alterações contra alterações acidentais e maliciosas e garante que o histórico tenha rastreabilidade total.

Com o Git, você pode ter certeza de ter um histórico de conteúdo autêntico do código-fonte.



#### Onde fazer o download

O download pode ser realizado no site oficial. através do link [Git - Downloads (git-scm.com)](https://git-scm.com/downloads)

No sita é possível encontrar versões para Mac, Linux e Windows



#### Como configurar o Git

Após o sistema devidamente instalado, insira o comando abaixo no terminal.
$ git config --global user.emal  "insira seu e-mail" (clique **enter**)

insira um novo comando
$ git config --global user.name " Insira seu usuário" (clique **enter**)

*Observação importante:* é interessante que esse e-mails e usuários possam ser usados posteriormente no seu cadastro do GitHub.



### Alguns comandos de navegação do terminal Git

Comando de como para entrar em um diretório: 
*cd nome do diretório*

![image](https://user-images.githubusercontent.com/105069533/168433402-5b90148b-6f7c-481c-a3f0-e6eb3e9726eb.png)

Comando de como para sairde um diretório:
*cd ..*

![image](https://user-images.githubusercontent.com/105069533/168433980-7355b032-8d5f-4282-9f65-a16199ae199a.png)

Comando para listar o que tem na pasta 
*ls -*

![image](https://user-images.githubusercontent.com/105069533/168435270-1477f38a-92a6-4fa7-8c5c-4f0396e4a43f.png)



Comando para criar pasta 
*mkdir nome da pasta*

![image](https://user-images.githubusercontent.com/105069533/168435797-888d12dd-cdc2-427f-b727-ecf6ffa66b96.png)

Comando para criar um arquivo
*echo > nomedoarquivo.extensão*

![image](https://user-images.githubusercontent.com/105069533/168436503-3ff1def1-d5aa-40a0-8589-c40687209676.png)

Comando para limpar tela
*clear*

![image](https://user-images.githubusercontent.com/105069533/168436814-0251d84f-f1f6-4670-b70c-6a35cb3ea60e.png)



**Comandos referente a projetos criados**

Crie uma pasta no local desejado, após sua criação acesse o Git e entre na pasta onde será inicializado o projeto.

Já no terminal Git na pasta correta digite os comandos pertinentes ao que precisa ser executado.

**git init**» Inicializa um repositório Git
**git status** » Vê o estado atual do projeto
**git add arquivo.txt** » Adiciona o arquivo arquivo.txt ao projeto

*Opções do parâmetro* **add**

![image](https://user-images.githubusercontent.com/105069533/168439071-73a9a84f-5e9a-48a5-9730-386144f82b17.png)

**git commit -m "Minhas mudanças efetuadas"** » Armazena as mudanças efetuadas e descreve o que foi alterado
**git log** » Mostra todas as mudanças que já foram efetuadas: commit, autor e data
**git push -u origin master** » Envia todos os arquivos modificados e “commitados” para o repositório no github
                    **-u** - faz com que o Git armazene esse comando e da próxima vez basta utilizarmos git push
                    **origin**- diz que o repositório no github possui o mesmo nome do projeto/diretório que você está enviando
                     **master** - é o nome da branch (indicador) Clique aqui para saber mais sobre branches
**git pull origin master** » Verifica as mudanças efetuadas por outros colaboradores do projeto
**git diff HEAD** » Verifica as partes dos arquivos alterados no último commit, veja mais opções em man git-diff
**git reset arquivo.txt** » Remove um arquivo do projeto
**git checkout – arquivo.txt** » Desfaz a última alteração feita num arquivo
**git rm "*.txt"** » Remove 1 ou mais arquivos utilizando “curinga”
**git clone https://github.com/FerndnaMarinho/Desafio-DIO.git** » Copia um projeto pro seu PC
**info git** » Obtém a Documentação do git
**man git** » Obtém o Manual do git



#### Alguns vídeos que podem clarear seu entendimento

[06. Configurando o Git - Git e Github para Iniciantes - YouTube](https://www.youtube.com/watch?v=QF0Cdd8ApRk)

[Glossário Git - Todos os principais termos e comandos - YouTube](https://www.youtube.com/watch?v=3SNVz4B1cE0)



# Github 

O GitHub é uma plataforma para hospedagem e controle de versão de código utilizando o sistema Git como base. Também serve como uma comunidade para programadores do mundo todo colaborarem em projetos pessoais e de código-aberto, além de contar com uma versão paga para empresas e profissionais.

A plataforma pode ser acessada através do link https://github.com/

Para ter acesso ao GitHub, o interessado deve realizar um cadastro no site. É grátis, assim como outros apps encontrados dentro do próprio GitHub e usados para melhorar a experiência. Existem opções com planos pagos que aumentam a quantidade de recursos.

### Como usar o GitHub

Os projetos são hospedados em “repositórios”, que podem ter acesso público ou privado. Desde a compra pela Microsoft, todos os usuários têm acesso ilimitado a repositórios particulares.

Todo o gerenciamento dos projetos, como criação de novos repositórios, é feito via comandos do sistema Git. Você também pode gerenciá-los pelo site, mas normalmente os processos são executados via linha de comando do seu computador ou servidor. Saiba mais sobre o Git e seus conceitos básicos no site oficial.

Para sincronizar o projeto do seu computador com o GitHub, é necessário ter o Git instalado na máquina. 

### Git ou GitHub?

Git e GitHub não são a mesma coisa. Git é o sistema de gerenciamento de versão gratuito e de código aberto criado por Linus Torvald, mesmo criador do Linux, em 2005. GitHub é a empresa que desenvolve soluções baseadas no Git que une o gerenciamento e hospedagem de código-fonte a funções de redes sociais, como feed, comunidades, fóruns, etc.

### Como criar um repositório no GitHub

Depois de ter criado a conta na plataforma e instalado o Git na sua máquina, você já pode hospedar o seu primeiro projeto no GitHub.com. Para isso:

1. Abra o terminal de comando do seu sistema operacional;
2. Dentro da pasta do projeto, digite: `git init`
   O comando acima irá criar toda a estrutura básica do repositório;
3. Para adicionar todos os arquivos alterados à fila de atualizações do repositório, execute o comando: `git add .`
4. Antes de sincronizar as alterações, configure seu usuário do GitHub com os comandos:
   `git config --global user.name "seu nome"`
   `git config --global "email no GitHub"`
5. Confirme as alterações com o comando: `git commit -m "mensagem"`
   no qual “mensagem” geralmente é um resumo das alterações.
6. Adicione o *remote*, ou seja, o link para o servidor do seu projeto no GitHub:
   `git remote add origin usuário no GitHub>/<nome do repositório>.git`
7. Por fim, envie as alterações com o comando:
   `git push remote origin`
8. Se tudo deu certo, será exibido uma mensagem confirmando o envio. Você também pode checar na página do repositório do projeto no GitHub.

Existem vários outros recursos importantes para conhecer e utilizar no GitHub, como *branchs*, que são versões paralelas do seu código que facilitam a criação de novas funcionalidades ou correções de bugs sem prejudicar o código-fonte original, e *pull requests*, que são “chamados” à comunidade para correção ou implementação de novos recursos em projetos.

A versatilidade da plataforma também permite que ela seja utilizada de outras formas, como hospedagem de blogs e portfólios pessoais, fóruns de discussão, páginas de divulgação de vagas, publicação de wikis e até de livros completos. 



### Vídeos que podem esclarecer como funciona o GitHub

[GitHub | Guia Completo do Iniciante - YouTube](https://www.youtube.com/watch?v=UbJLOn1PAKw)

[Criando conta no GitHub - @Curso em Vídeo HTML5 e CSS3 - YouTube](https://www.youtube.com/watch?v=1QTi8nIlK1o)

[Criando o primeiro Repositório - Curso de Git e GitHub - YouTube](https://www.youtube.com/watch?v=5BYm7UdCrX0)







