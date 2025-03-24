## Exercicio-1

## 1 
HTTP: Responsável pela comunicação entre cliente e servidor, permitindo a transferência de páginas web;
HTTPS:Uma versão segura do HTTP que utiliza criptografia SSL/TLS para proteger os dados transmitidos;
TCP/IP: Traduz nomes de domínio (exemplo.com) para endereços IP;
DNS: Garante a entrega confiável dos pacotes de dados na rede;
FTP: Utilizado para transferir arquivos entre cliente e servidor.

## 2
Na arquitetura cliente-servidor, o cliente (como um navegador) envia uma requisição para um servidor web. O servidor processa a solicitação e responde com os dados solicitados, como uma página HTML, uma imagem ou um arquivo JSON. Esse processo ocorre seguindo o protocolo HTTP, onde o cliente sempre inicia a comunicação, e o servidor apenas responde.

## 3 
O HTTP define como as mensagens de requisição e resposta devem ser formatadas e transmitidas entre cliente e servidor. Ele estabelece regras para solicitação de recursos, envio de formulários, carregamento de páginas web e comunicação entre sistemas distribuídos.

## 4
a) - GET: Solicita um recurso do servidor (ex.: uma página da web);
     POST: Envia dados ao servidor (ex.: um formulário preenchido);
     PUT: Atualiza um recurso existente no servidor.
     
b) - 200 OK: Requisição bem-sucedida;
     404 Not Found: O recurso solicitado não foi encontrado no servidor;
     500 Internal Server Error: Ocorreu um erro no servidor ao processar a solicitação.

## 5 
  Long Polling: O cliente mantém uma conexão aberta até que o servidor tenha uma atualização para enviar;
  WebSockets: Cria uma conexão bidirecional persistente entre cliente e servidor para troca de dados em tempo real;    
  Server-Sent Events (SSE): O servidor envia atualizações ao cliente através de uma conexão HTTP mantida ativa.
