# Extracao de CEP - Site Correios
> rpa-uipath-correios


*projeto em constante melhoria

## RESUMO

Projeto:

```sh
Extração de CEP's no site do Correios
```

Escopo:

```sh
Este projeto tem como escopo a busca e extração de CEP's via consulta no site do Correios, a gravação deste resultado em um arquivo excel e envio deste mesmo arquivo para uma lista de email configurada.
```

## CONFIGURAÇÕES

Arquivo de configuração:

```sh
config.csv
```

Sobre:

```sh
Este projeto possuí um arquivo de configuração com o objetivo de reutilização e flexibilidade. 
Os parâmetros são "inputados" na segunda linha, enquanto a primeira representa o cabeçalho para melhor organização.
```

Estrutura:

```sh
LINHA 1:cep;diretorioDeTrabalho;portaEmail;servidorEmail;usuarioEmail;senhaEmail;destinatarioEmail;ccEmail;ccoEmail;
```

Dados:

```sh
LINHA 2: 29308;c:\ExtracaoDeDados;465;smtp.gmail.com;seuemail@gmail.com;suasenha;outro@gmail.com;maisumemail@gmail.com;aindapodeirmaisemail@gmail.com;
```

## Release History
* 0.2.0
    * ADD: Add `Envio de anexo por email`
* 0.1.0
    * Primeira versão
    * CHANGE: Envio de email `static` to `file properties`
* 0.0.1
    * Work in progress
