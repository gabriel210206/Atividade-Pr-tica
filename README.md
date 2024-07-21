# **_Atividade Prática_**
<ol>
<li>Git pode ser dito como um repositório de código, que é um diretório onde os arquivos de código fonte do seu projeto e o histórico completo das revisões ficam armazenados.</li>
<li>Local temporário onde são armazenadas todas as alterações que serão adicionadas no próximo commit.</li>
<li>Todos os arquivos que estão sendo trabalhados no momento.</li>
<li>É um instantâneo (do inglês, snapshot) das modificações adicionadas na staging area, persistindo-as no repositório local.</li>
<li>É um ponteiro que aponta para algum commit ou alguma branch.</li>
<li>Ação de juntar os commits de dois branches.</li>
<li>Os quatro estados explicados um a um são estado untracked, que são os arquivos que não estavam no último commit, unmodified, que são os arquivos não modificados desde o último commit, modified, que são arquivos modificados desde o último commit e staged, que são os arquivos prontos para comitar.</li>
<li>O git init cria um repositório</li>
<li>O git add adiciona um arquivo à staging area, que irá pertencer ao próximo commit.</li>
<li>O comando git status é usado para verificar o estado atual do repositório, incluindo informações sobre arquivos modificados, adicionados ou excluídos.</li>
<li>Com o git log podemos ver o histórico de commits realizados em nosso repositório.</li>
<li>O git reset serve para desfazer um commit, suas três opções são: soft, mixed e hard. A opção soft, move o HEAD para o commit indicado, mas mantém o staging e o working directory inalterados. A opção mixed, move o HEAD para o commit indicado, altera o staging e mantém o working directory. A opção hard faz com que o HEAD aponte para algum commit anterior, mas também altera a staging area e o working directory para o estado do commit indicado, ou seja, todas as alterações realizadas após o commit ao qual retornamos serão perdidas.</li>
<li>O git revert cria um novo commit com as alterações do commit indicado.</li>
<li>O git clone é usado para baixar um repositório remoto na sua máquina.</li>
<li>O git push sobe as alterações do repositório local para o repositório remoto.</li>
<li>O git pull atualiza o repositório local com as informações do repositório remoto.</li>
<li>Para resolver isso, vamos criar o arquivo .gitignore onde vamos colocar todos os arquivos que queremos ignorar ao realizar um commit. O comando echo é utilizado apenas para adicionar a nova linha “main” ao arquivo .gitignore. Agora vamos salvar nossas alterações adicionando os arquivos main.cpp e .gitignore no staging. Podemos fazer isso através do comando “git add .“, que adiciona todos os arquivos modificados no staging. Se checarmos o estado do nosso repositório, podemos observar que todas as modificações foram adicionadas ao staging. Se tentarmos agora adicionar o executável main no staging, recebemos um aviso.</li> 
<li>A branch master representa o ramo principal, de início, a versão v0.0.0, a branch develop receberá todas as modificações para correção ou evolução de funcionalidades já existentes, assim como para o desenvolvimento de novas funcionalidades a branch staging é criado a partir do ramo “develop” e é utilizado para colocar em testes as modificações de código realizadas pelos desenvolvedores, após isso, quando as modificações forem aprovadas, a branch staging é mesclada à branch master, criando uma nova versão v0.0.1.</li>
<ol>
