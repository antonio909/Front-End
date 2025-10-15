Noções Básicas HTTP (HTTP Basics):

* **O que é?** O HTTP é um protocolo de camada de aplicação que permite a comunicação
  entre clientes (como seu navegador web) e servidores. É a base para a troca de dados na
  World Wide Web.

* **Modelo Requisição-Resposta:** O HTTP funciona em um ciclo de **requisição-resposta**
  (client-server):

  * O **Cliente** (navegador) envia uma **Requisição HTTP** (HTTP Request) para o servidor.

  * O **Servidor** processa a requisição e envia uma **Resposta HTTP** (HTTP Response) de
    volta ao cliente.

* **Métodos HTTP (HTTP Methods):** Também chamados de verbos, indicam a ação que o
  cliente deseja realizar no recurso do servidor. Os mais comuns são:

  * **GET:** Solicita dados de um recurso específico (usado para carregar páginas).

  * **POST:** Envia dados a um servidor para criar/atualizar um recurso (usado para enviar
    formulários).

  * **PUT:** Atualiza um recurso ou cria um novo se não existir.

  * **DELETE:** Exclui um recurso específico.

* **Componentes da Requisição/Resposta:**

  * **URL:** Endereço do recurso.

  * **Cabeçalhos (Headers):** Informações adicionais sobre a requisição ou a resposta (tipo
    de conteúdo, cookies, etc.).

  * **Corpo (Body - opcional):** Os dados reais que estão sendo enviados ou recebidos (o
    conteúdo da página, dados de formulário, etc.).

* **Códigos de Status (Status Codes):** Números de 3 dígitos na resposta que indicam o
  resultado da requisição. Exemplos:

  * **200 OK:** A requisição foi bem-sucedida.

  * **404 Not Found:** O recurso solicitado não foi encontrado.

  * **500 Internal Server Error:** Um erro ocorreu no servidor.

* **Stateless (Sem Estado):** Originalmente, o HTTP é **stateless**, o que significa que o servidor
  não armazena nenhuma informação sobre requisições anteriores. Para manter o "estado"
  (como um login de usuário ou um carrinho de compras), são usadas tecnologias como
  **Cookies** e **Sessions**.

* **HTTPS:** É a versão segura do HTTP, usando o protocolo SSL/TLS para criptografar a
  comunicação e garantir a segurança dos dados.
