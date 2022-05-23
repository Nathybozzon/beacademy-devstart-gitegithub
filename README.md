# beacademy-devstart-gitegithub

Repositório especialmente feito para registro de todos os comandos trabalhados nas aulas de Git.

Comandos das Configurações Iniciais:

git config --global user.name "nome"=> Configura o nome do uuário no git
git config --global user.email "email@email.com" => Configura o e-mail utilizado no git
git => lista de diveros comando do git
 
Comandos Repositório:

git status => Ver o status do repositório
git init => Inicia um repositório vasio
git add "nome arquivo" => Prepara um arquivo para ser commitado.
git rm --cached "nome arquivo" => Desfaz a ação de cima.
git add . => Pega todos os arquivos e coloca dentro do commit que será feito.
clear => Limpa a tela
git commit - m "mensagem" => Você faz o commit dos arquivos que estavam na fila para commitar enviando uma mensagem junto.
git log => Mostra um log das operações que você trabalhou (histórico dos commmits)

Comandos Ramificações:

git branch => Mostra todas as branchs locais que você tem e marca a branch que você está no momento.
git branch nome_da_branch => Faz uma nova branch.
git checkout nome_da_branch => Você muda de uma branch que você está para a outra escolhida.
git checkout -b nome_da_branch => Você cria uma nova branch e muda para ela.
git branch -d nome_da_branch => Remove a branch.
git merge nome_da_branch => Unifica as alterações de uma branch para a outra.

Clone:

git clone site => Clona o projeto do site apontado para o repositório remoto.
git remote -v => Lista as conexões remotas que você tem com outros repositórios, incluindo a URL de cada conexão.
git push => Empurra as alterações do repositório local para o repositório remoto.

Aula ao Vivo:

ls => Lista arquivos do diretório.
git stash => Pega todas as alerações que ja tenham sido rastreadas algumas vez e coloca nessa área reservada.
git stash --include-unctracked => Tem a ação do comando anterior mas faz a ação incluindo os arquivos que não foram rastreados.
git stash list => Lista quais são os stashs disponíveis.
notepad nomearquivo => Inicia o bloco de notas com o arquivo escolhido.
git push --set-upstream branch_principal nome_branch => Pega a brainch nova e coloca no lugar ecolhido, no caso, branch principal. Empurrando pra branch remota.
git stash pop => Você regressa a stash que você estava mexendo.
git stash pop nome_stash => Veocê regressa a stash especifica.
git revert código_commit => desfaz o commit especificado.
