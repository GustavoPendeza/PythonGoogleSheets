# Projeto Google Sheets

### Objetivo do projeto:

- Utilizar os dados de uma planilha do Google Sheets (https://docs.google.com/spreadsheets/d/1DYO-AjAZFki21a1ds-E4AKVCPIUoMKA98wneGYCeluk/edit?usp=sharing);
- Automatizar a atualização do status dessa planilha;
- Automatizar o envio de e-mail para as pessoas em que o status for atualizado.

### Contexto da planilha:

- Exemplo de dados cadastrados em alguma plataforma de vendas online;
- Onde a coluna de "Problemas" seria organizada por tipos de problemas para facilitar a automação do status.

### Para utilizar o Projeto

- Copie e atualize os e-mails da planilha de exemplo para e-mails que você use para realizar o teste;
- Utilize sua conta do gmail na função abaixo para poder enviar os e-mails;
- Opcional: Mude o nome no final do texto do e-mail.

### Crie um Projeto no Google Cloud utilizando a API do Google Sheets

- API Google Sheets: https://developers.google.com/sheets/api/guides/concepts
- Criar projeto Google Cloud: https://developers.google.com/workspace/guides/create-project


- Tenha os arquivos 'credentials.json' e 'token.json'.


### Instaladores

- pip install yagmail
- pip install google-api-python-client
- pip install google_auth_oauthlib
