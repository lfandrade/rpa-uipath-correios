"# rpa-uipath-correios" 

RESUMO

Projeto: Extração de CEP's no site do Correios
Escopo: Este projeto tem como escopo a busca e extração de CEP's via consulta no site do Correios, a gravação deste resultado em um arquivo excel e envio deste mesmo arquivo para uma lista de email configurada.

##################
CONFIGURAÇÕES

Arquivo de configuração: config.csv

Este projeto possuí um arquivo de configuração com o objetivo de reutilização e flexibilidade. 
Os parâmetros são "inputados" na segunda linha, enquanto a primeira representa o cabeçalho para melhor organização.

Estrutura
LINHA 1:cep;diretorioDeTrabalho;portaEmail;servidorEmail;usuarioEmail;senhaEmail;destinatarioEmail;ccEmail;ccoEmail;

Dados de exemplo
LINHA 2: 29308;c:\ExtracaoDeDados;465;smtp.gmail.com;seuemail@gmail.com;suasenha;outro@gmail.com;maisumemail@gmail.com;aindapodeirmaisemail@gmail.com;

##################
DETALHE DA EXECUÇÃO