# Projeto-Nos
Repositório destinado a guardar os arquivos do site feito durante a Trilha de Devs para o Projeto Nós

# Workflow:


Guia para o workflow em git: [link](https://guides.github.com/introduction/flow/)
Para garantirmos um fluxo de trabalho bom e eficiente é bom definir algumas regrinhas para conseguirmos nos falar com clareza, a respeito de como vão ser feitas as branchs, os commits e os pull requests para esse trabalho

**NÃO DÊ `git push origin master` EM HIPÓTESE ALGUMA**

sério não faz isso, pode passar por cima pelo trabalho de outras pessoas (dê qualquer forma podemos ainda combinarmos por whats) fora que a ideia por trás da main é o produto que já pode ser encaminhado para o cliente, não faz sentido ter algo não totalmente funcional na main.

Depois de se conversar no whats o que você vai fazer você deve fazer um `git clone` caso ainda não tiver o repositório em sua máquina ou um `git pull` para atualizá-lo:

* `git pull`: Vai atualizar o seu repositório local e deixar ele pareado com o remoto
* `git checkout main`: Use isso logo em seguida e antes de criar uma branch para não zuar todo o fluxo (é mais para garantir que não tenha subramos)
* `git checkout -b nome_da_branch`: comando para você criar uma branch nova e já entrar nela, segue observações:
  * Converse no whats o que você vai fazer e deixe isso muito certinho
  * Converse se já não existe uma branch que está fazendo o que você faz
  * Dê nomes significativos para as pessoas não ficarem perdidas
  * Ex.: "Header" --> branch que vai trabalhar no header, "Footer" --> autoexplicativo né ?
* Dentro da sua branch faça as alterações a vontade, provavelmente você vai ser o responsável por essa branch
* Não esqueça de usar `git add nome_arquivo` para ter o tracking do versionamento
* Quando você for dar um `git commit -m "Mensagem"`, lembre-se:
  * A mensagem deve ser imperativa, pense assim o que esse commit faz? Ex.: Esse commit "Adiciona navbar"
  * Acho que não precisamos ser tão meticulosos quanto aos commits, mas foque em 3 palavrinhas para seu commit
  * "Adiciona", "Arruma" e "Deleta" (caso precise deletar algum arquivo)
 
