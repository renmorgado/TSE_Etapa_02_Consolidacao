########################################################################################
NECESSIDADE:
########################################################################################
A necessidade de criar o script surgiu após a conclusão do Mestrado (USP, 2019) quando quase todos os dados da pesquisa foram produzidos manualmente.
Em razão do grande volume de dados busquei conhecimentos para automtizar as tarefas de download, consolidadação e codificação das bases de dados por ano eleitoral e tipo de arquivo.
########################################################################################
OBJETIVO:
########################################################################################
A fase 1 o objetivo foi automatizar os downloads dos arquivos.
Na fase 2 (atual) o objetivo foi consolidar os arquivos de acordo com os tipos disponíveis para 
download.
########################################################################################
DESAFIOS:
########################################################################################
Foi percebido que o TSE realizou uma atualização da base de arquivos.
Até as eleições de 2014 a maioria dos dados estavam no formato ".txt" e não continham cabeçalhos.
Na primeira versão, o script lia o cabeçalho em outro arquivo e consolidava correspondendo o ano eleitoral e o tipo de arquivo.<br>
Com a atualização dos arquivos (para formato .csv), atualmente todos já possuem cabeçalho.
Obs.: no arquivo de "perfil_eleitorado" optei por trabalhar com os arquivos do tipo ".txt" (versão antiga), pois no formato .csv possui menos informações.
########################################################################################
LINGUAGEM:
Python - Jupyter Notebook
########################################################################################