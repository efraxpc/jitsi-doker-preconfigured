**Correr os seguintes comandos**
*** O PRIMERO QUE FAZER É CONFIGURAR A IP E O DNS DA AMAZON DENTRO DO REGISTRO BR ***
-   Criar um arquivo  `.env`  copiando o arquivo `env.example`
    -   `cp env.example .env`
-   Setear uma senha forte of  `.env`  correndo o seguinte script
    -   `./gen-passwords.sh`
-   Criar  `CONFIG`  diretórios
    -   `mkdir -p ~/.jitsi-meet-cfg/{web/letsencrypt,transcripts,prosody/config,prosody/prosody-plugins-custom,jicofo,jvb,jigasi,jibri}`
-   Correr  `docker-compose up -d`
-   Entrar a seu dominio. Por Exemplo [https://live.fpass.com.br/](https://live.fpass.com.br/)