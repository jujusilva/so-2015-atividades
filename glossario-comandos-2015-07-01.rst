======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Juliana da Silva
:Matrícula: 20121144010087
:Data: 01/07/2015

cat

Conecta os vários arquivos, na ordem especificada, copiando o resultado para a saída padrão. Se não houver argumentos, copia a entrada padrão para a saída padrão. 

Ex: cat /etc/

cd

Este comando nos permite se deslocar entre a árvore de diretórios do sistema.

Ex: cd $USER

cowsay

O programa gera a figura da famosa vaquinha das distros baseadas no Debian. O comando cowsay pode ser utilizado de duas formas, uma é chamar o comando cowsay no terminal e na sequência escrever a frase ou palavra que será dita pela vaca.

Ex: cowsay /lite

Echo

Permite exibir textos na tela. Este comando também exibe toda estrutura de diretórios e arquivos em ordem alfabética, porém sem formatar em colunas a listagem.

Ex: echo $PATH

env

Mostrar o ambiente atual ou, se um ambiente variável é especificado,defina-o para um novo valor e visualizar o ambiente modificado.

exit

Terminar a sessão. 

Ex: exit

help

Exibe informações sobre os comandos internos do Bash.

Ex: help for

HISTTIMEFORMAT="%d/%m/%y"

As informações de carimbo de tempo associado com cada entrada história é escrita para o arquivo de história, marcados com o caráter histórico de comentários.Onde, % d - Dia % m - mês % y - Ano % T - Time Para ver tipo de história.

Ex : HISTTIMEFORMAT="%d/%m/%y %T

hostname

Definir ou exibir o nome do sistema host atual. 

Ex: vim /etc/hostname /etc

ifconfig

Visualizar os ips da nossa máquina, entre outras funções relacionadas com ips.

Ex: ifconfig
 
last

Exibir uma lista dos logins mais recentes, tiradas do arquivo / var / log / wtmp por padrão. 

Ex: last -10

lastb

Exibir uma lista de recentes tentativas de login errados.

Ex: lastb colega ; lastb seunome.

ls

lista os arquivos e diretórios da pasta atuais. 

Ex : ls ; ls /sbin/ 937 .

mkdir

cria diretórios. 

Ex: mkdir juliana

nome="fulano

Descrição do comando

passswd

Altera a senha de um usuário exibindo um prompt para que a nova senha seja fornecida, e logo depois repetida para confirmaçã.

pwd

mostra o nome do diretório corrente.

Ex: pwd

set

Manipula as variáveis shell e funções. 
Ex: set

tree

É uma árvore de comando. 

Ex: cmd>tree

tty

Imprimir o nome do arquivo do terminal conectado à entrada padrão. 

Ex: tty

vim

Editor de texto full-screen melhorado. 

Ex: vim info.php

wait

Espera para cada processo especificado para preencher e devolver o seu estatuto de terminação.

Ex: wait 2585

wall

Escrever para todos os usuários.

Ex: wall

which

Exibe o caminho completo na hierarquia de diretórios para os comandos do sistema.

Ex : which firefox
 
while

Executar consequentes -comandos enquanto test- comandos tem um status de saída zero. 

Ex: while

who

Mostra os nomes dos usuários que estão conectados numa mesma máquina.

whoami

Mostra o nome do próprio usuário que executou o comando whoami.

write

Escrever para outros utilizadores que estejam logados no momento.
