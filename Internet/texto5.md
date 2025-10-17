# HTTP/3 agora é um padrão: por que usá-lo e como começar?

O HTTP/3 é uma padrão que oferece melhor desempenho, confiabilidade
aprimorada e segurança reforçada ao usar o protocolo QUIC em vez do
TCP, reduzindo a latência e resolvendo problemas como o "head-of-
line blocking". Para começar, é preciso garantir que seu servidor web e
seu provedor de hospedagem suportem o protocolo e que a
configuração do QUIC e dos certificados TLS esteja correta;
navegadores modernos como Chrome, Firefox e Edge já o suportam por
padrão.

## Por que usar o HTTP/3

* **Velocidade:** Reduz o tempo de resposta da primeira solicitação ao
  diminuir o número de idas e vindas necessárias para estabelecer a
  conexão.

* **Melhor desempenho em redes ruins:** Ao contrário do HTTP/2, que
  pode ter toda uma conexão bloqueada por um pacote perdido, o
  QUIC gerencia fluxo de dados independentes, o que significa que
  a perda de um pacote afeta apenas o fluxo específico e não toda a
  conexão.

* **Transição de redes sem falhas:** Facilita a mudança de rede (como
  WiFi para dados móveis) sem interromper a conexão, algo que
  o HTTP/1.1 e o HTTP/2 não conseguem fazer.

* **Segurança aprimorada:** A criptografia é integrada ao protocolo
  QUIC, protegendo a conexão de forma mais robusta desde o
  início.

* **Adoção ampla:** A maioria dos navegadores modernos já o
  implementa por padrão, e a adoção em sites está crescendo
  significativamente.

## Como começar a usar

* **Verifique seu provedor de hospedagem:** Confirme se seu
  provedor oferece suporte a HTTP/3. Muitos provedores de CDN,
  como a Cloudflare, já oferecem suporte para que você o ative sem
  alterações no servidor de origem.

* **Configure seu servidor:** Certifique-se de que seu servidor web
  (como Kestrel no .NET) esteja configurado para usar o protocolo
  QUIC.

* **Mantenha os certificados TLS atualizados:** A criptografia é
  essencial no HTTP/3, por isso, certifique-se de que seus
  certificados TLS estejam válidos e atualizados.

* **Monitore o uso:** Utilize ferramentas como o Cloudflare Radar para
  acompanhar a adoção e o desempenho do protocolo em seus
  sites.
