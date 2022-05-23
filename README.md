# beacademy-devstart-gitegithub

Repositório especialmente feito para registro de todos os comandos trabalhados nas aulas de Git.

Comandos das Configurações Iniciais:

git config --global user.name "nome"=> Configura o nome do uuário no git<br/>
git config --global user.email "email@email.com" => Configura o e-mail utilizado no git<br/>
git => lista de diveros comando do git<br/>
 
Comandos Repositório:

git status => Ver o status do repositório<br/>
git init => Inicia um repositório vasio<br/>
git add "nome arquivo" => Prepara um arquivo para ser commitado.<br/>
git rm --cached "nome arquivo" => Desfaz a ação de cima.<br/>
git add . => Pega todos os arquivos e coloca dentro do commit que será feito.<br/>
clear => Limpa a tela<br/>
git commit - m "mensagem" => Você faz o commit dos arquivos que estavam na fila para commitar enviando uma mensagem junto.<br/>
git log => Mostra um log das operações que você trabalhou (histórico dos commmits)<br/>

Comandos Ramificações:

git branch => Mostra todas as branchs locais que você tem e marca a branch que você está no momento.<br/>
git branch nome_da_branch => Faz uma nova branch.<br/>
git checkout nome_da_branch => Você muda de uma branch que você está para a outra escolhida.<br/>
git checkout -b nome_da_branch => Você cria uma nova branch e muda para ela.<br/>
git branch -d nome_da_branch => Remove a branch.<br/>
git merge nome_da_branch => Unifica as alterações de uma branch para a outra.<br/>

Comandos Clone:

git clone site => Clona o projeto do site apontado para o repositório remoto.<br/>
git remote -v => Lista as conexões remotas que você tem com outros repositórios, incluindo a URL de cada conexão.<br/>
git push => Empurra as alterações do repositório local para o repositório remoto.<br/>

Aula ao Vivo:

ls => Lista arquivos do diretório.<br/>
git stash => Pega todas as alerações que ja tenham sido rastreadas algumas vez e coloca nessa área reservada.<br/>
git stash --include-unctracked => Tem a ação do comando anterior mas faz a ação incluindo os arquivos que não foram rastreados.<br/>
git stash list => Lista quais são os stashs disponíveis.<br/>
notepad nomearquivo => Inicia o bloco de notas com o arquivo escolhido.<br/>
git push --set-upstream branch_principal nome_branch => Pega a brainch nova e coloca no lugar ecolhido, no caso, branch principal. Empurrando pra branch remota.<br/>
git stash pop => Você regressa a stash que você estava mexendo.<br/>
git stash pop nome_stash => Veocê regressa a stash especifica.<br/>
git revert código_commit => desfaz o commit especificado.
