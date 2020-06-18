# Guia de estudos Git


> *Olá, seja bem-vindo ao guia de inicialização a Git.
Me chamo Filipe Barbosa e assim como você sou um entusiasta dos códigos e aluno da PodCodar.*




Já ouviu falar em Git? Do que se trata? Para que serve? Bem, vamos responder todas essas questões no decorrer do texto.

Git é uma ferramenta de gerenciamento de controle de versão de código, ou seja, ele registra todas as alterações feitas no decorrer do código. Aí, você ou qualquer membro da organização podem acessar quando quiserem e recuperar versões especificas do produto.

Bacana, não?!

Com o uso do Git os membros do time podem acessar o código a qualquer momento e trazê-los para sua máquina, fazer as alterações necessárias e subir o código novamente. Assim, evitam-se conflitos e garante-se que as alterações são feitas em cima da versão mais atual do código.

Quer aprender um pouco mais? Segue o link de uma boa explicação do que é o Git.

https://www.youtube.com/watch?v=WVLhm1AMeYE

Esta apresentação mostra um pouco de como funciona o Git na máquina, mas para conseguir subir o nosso código precisamos de um lugar na nuvem para que ele fique guardado e também para que possamos subir e baixar o código. Para isso, iremos utilizar o Github, um serviço on-line de hospedagem e gerenciamento de projetos git.


Curso de Git: https://rogerdudler.github.io/git-guide/index.pt_BR.html


 #### Principais Comandos

`git clone`  [link do repositório]
`git status` (Depois do git status você vai ter um log das alterações dos arquivos, quando tá vermelho é que não tá na lista dos arquivos que vai subir)
`git add`*.* (No lugar do . você pode colocar o nome do arquivo que você quer ou só um tipo específico, tipo .já, sobe só arquivos .js)
`git commit -m` "Qualquer mensagem, uma boa prática. _é sempre iniciar o nome do commit com um verbo_"
`git push --set-upstream origin` {nome da branch que vai subir} (se antes você quiser ver quais arquivos que vai subir só você da um git status)
`git branch` **{nome da branch}** (Você cria uma branch com o nome que você coloca)
`git checkout` **{nome da branch}**(Muda pra branch que você colocou)
`git pull` (para baixar uma branch)

Agora que já conhecemos todos esses comandos tem um site muito legal onde da pra aplicar um pouco deles e ver o que está acontecendo em nosso repositório, assim podemos melhorar nosso entendimento e familiarizar com a ferramenta antes de iniciar no ambiente de produção.
[click aqui e comece agora a praticar seus conhecimentos](https://learngitbranching.js.org/?locale=pt_BR)

**Espero que tenham gostado desse material e não se esqueça. [Acesse nosso blog](https://podcodar.github.io/)**

## *Sim, Você PodCodar!!!*



![](/img/img.jpg)