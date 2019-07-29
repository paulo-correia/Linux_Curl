# Curl
É uma ferramenta para transferir dados de ou para um servidor, usando um dos Protocolos suportados (DICT, FILE, FTP, FTPS, GOPHER, HTTP, HTTPS, IMAP,IMAPS, LDAP, LDAPS, POP3, POP3S, RTMP, RTSP, SCP, SFTP, SMB, SMBS, SMTP, SMTPS, TELNET e TFTP).
O comando é projetado para funcionar sem Interação do usuário.

Exemplos:
```
curl -I -s localhost:80
Testa a conectitividade de um Apache/Nignx/IIS

curl localhost:3306
Testa se um MySQL/MariaDB está atendendo na porta 3306

curl "localhost?Fisrt=Bruce&Last=Wayne"
Passa as variáveis First e Last com o seu conteúdo via GET

curl localhost -d"Fisrt=Bruce&Last=Wayne"
Passa as variáveis First e Last com o seu conteúdo via POST
```