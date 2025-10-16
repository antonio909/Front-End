# Como funciona a Internet?

A internet funciona como uma rede global de computadores
interconectados por meio de cabos, fibras ópticas e ondas de rádios,
que transmitem dados em pacotes. Essa comunicação é regida por
protocolos, como o TCP/IP, que garantem a correta divisão dos dados
em pacotes, seu roteamento e montagem no destino. Para
acessarmos sites, um Sistema de Nomes de Domínio (DNS) traduz o
nome do site (ex: `google.com`) para um endereço IP, que é o
identificador único do servidor onde a página está hospedada.

## Componentes principais

* **Infraestrutura física:** A internet depende de uma vasta rede física
  que inclui cabos submarinos (principalmente de fibra óptica),
  cabos terrestres, torres de celular e satélite, que conectam
  continentes e países.

* **Roteadores e switches:** Os roteadores direcionam os pacotes de
  dados entre diferentes redes, enquantos os switches conectam
  múltiplos dispositivos dentro de uma mesma rede.

* **Servidores:** São computadores potentes que armazenam sites,
  vídeos e outros conteúdos. Os servidores recebem as solicitações
  dos usuários e enviam os dados de volta.

* **Dispositivos do usuário:** Computadores, smartphones e outros
  dispositivos se conectam à rede para enviar e receber
  informações.

## Como os dados trafegam

1. **Entrada do usuário:** Quando você digita um endereço web, seu
   navegador primeiro consulta um servidor DNS para converter o
   nome de domínio (ex: `www.google.com`) em um endereço IP
   numérico.

2. **Divisão em pacotes:** O conteúdo solicitado é dividido em
   pequenos pacotes de dados. Cada pacote contém parte da
   informação e o endereço de destino.

3. **Roteamento:** Os roteadores examinam o endereço IP de cada
   pacote e determinam o caminho mais rápido para enviá-lo. É
   possível que pacotes de uma mesma solicitação sigam rotas
   diferentes.

4. **Transmissão:** Os pacotes viajam pela infraestrutura física (cabos,
   fibras, etc.). Sinais elétricos ou pulsos de luz (no caso da fibra
   óptica) transportam os dados.

5. **Remontagem:** Ao chegar ao servidor de destino, os pacotes são
   reorganizados e remontados para formar a solicitação completa. O
   processo inverso ocorre quando o servidor responde, enviando os
   dados de volta para o seu dispositivo.

## Protocolos de comunicação

* **TCP/IP (Transmission Control Protocol/Internet Protocol):** É o
  conjunto de regras padrão da internet. O TCP cuida de quebrar a
  informação em pacotes e garantir que todos cheguem ao destino e
  sejam montados corretamente. O IP cuida do endereçamento e
  roteamento de pacotes.

* **HTTP/HTTPS (HyperText Transfer Protcol/Secure):** O HTTP é o
  protocolo usado para transferir páginas da web, mas não é seguro.
  O HTTPS é a versão segura que utiliza criptografia para proteger a
  comunicação.
