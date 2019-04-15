# DO OFFLINE

Um script que baixa o Diario Oficial do Estado (Legislativo) junta tudo num pdf, reduz o tamanho e encaminha para o grupo de slack do mandato.


## Requerimentos

* python3
* PyPDF2
* fitz

## Instalação

Configure o settings.py e inclua o token de acesso a API do Slack
os canais onde o DO deve ser publicado e as palavras que devem ser
destacadas.


## Como usar

Rodar o script baixado.py com os seguintes parametros:

-d today <- baixa DO de hoje
-d DD/MM/YYYY <- baixa DO do dia especificado
-c "caderno" <- baixa o caderno especifico "legislativo", "exec1", "exec2", etc
-u <- "sobe os arquivos pro slack"


## Rodando diariamente

A sugestão é fazer isso com um cronjob ;)
