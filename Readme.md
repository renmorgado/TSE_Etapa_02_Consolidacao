######################
</br>
NECESSIDADE:
</br>
######################
</br>
A necessidade de criar o script surgiu após a conclusão do Mestrado (USP, 2019) quando quase todos os dados da pesquisa foram produzidos manualmente. <br>
Em razão do grande volume de dados busquei conhecimentos para automtizar as tarefas de download, consolidadação e codificação das bases de dados por ano eleitoral e tipo de arquivo.
</br>
</br>
######################
</br>
OBJETIVO:
</br>
######################
</br>
A fase 1 o objetivo foi automatizar os downloads dos arquivos.
Na fase 2 (atual) o objetivo foi consolidar os tipos de arquivos.
</br>
</br>
######################
</br>
DESAFIOS:
</br>
######################
</br>
Foi percebido que o TSE realizou uma atualização da base de arquivos. <br>
Até as eleições de 2014 a maioria dos dados estavam no formato .txt e não continham cabeçalhos. Na primeira versão, o script lia o cabeçalho em outro arquivo e agrupava correspondendo o ano eleitoral e o tipo de arquivo consolidado.<br>
Com a atualização dos arquivos, hoje, todos estão no formato .csv e já possuem cabeçalho.<br>
Obs.: no arquivo de "perfil_eleitorado" optei por trabalhar com os arquivos do tipo ".txt" (versão antiga), pois no formato .csv existem menos informações.
</br>
</br>
######################
</br>
LINGUAGEM
</br>
######################
</br>
Python - Jupyter Notebook
######################
</br>
</br>