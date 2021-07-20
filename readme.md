# Dropbox Clone

Projeto com a função de fazer um "clone" do serviço Dropbox, usando Firebase para armazenar os arquivos de upload e dados.

As rotas são feitas pelo módulo Express Generator.

Comandos para iniciar o projeto:

- Dentro da pasta /app:
    ```
    npm install;
    ```
- Dentro da pasta /app/public:
    ```
    bower install;
    ```
- Novamente na pasta /app para (iniciar o projeto):
    ```
    npm start;
    ```

OBS: Necessário cadastrar um projeto no Firebase e criar um banco Realtime Database e habilitar o Storage para armazenar os arquivos, e salvar as configurações do banco no método **connectFirebase()**.

Tecnologias utilizadas:
- HTML
- CSS
- JavaScript
- NodeJS