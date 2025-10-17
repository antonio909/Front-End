# Como funciona o HTTPS?

O HTTPS funciona criptografando a comunicação entre o navegador
de um usuário e um site usando o protocolo de segurança SSL/TLS,
que garante que as informações transmitidas sejam protegidas de
interceptações por terceiros mal-intencionados. Isso é feito através
de um processo de handshake onde o navegador e o servidor trocam
um certificado SSL/TLS e estabelecem uma chave de sessão secreta, a
partir daí toda comunicação usa essa chave para criptografar e
descriptografar os dados.

## Como o HTTPS funciona

1. **Solicitação do certificado:** Quando você acessa um site, seu
   navegador solicita o certificado de segurança (SSL/TLS) do
   servidor.

2. **Verificação da identidade:** O servidor envia de volta seu
   certificado. O navegador verifica a identidade do servidor e a
   autenticidade do certificado.

3. **Início da troca de chaves:** Após a verificação, o navegador
   criptografa uma chave de sessão secreta com a chave pública do
   servidor e a envia a ele.

4. **Descriptografia e confirmação:** O servidor usa sua chave privada
   para descriptografar a mensagem e recuperar a chave de sessão.
   Ele então criptografa uma confirmação com a chave de sessão e a
   envia de volta para o navegador.

5. **Comunicação segura:** A partir deste ponto, tanto o navegador
   quanto o servidor usam a chave de sessão para criptografar e
   descriptografar todas as mensagens trocadas, garantindo uma
   conexão segura.

## Em resumo

* **O "S" de HTTPS:** Significa "Secure" (Seguro) e indica que a
  conexão é criptografada.

* **Criptografia:** O uso do protocolo SSL/TLS embaralha os dados,
  tornando-os ilegíveis para qualque pessoa que os intercepte sem
  as chaves corretas.

* **Chave pública e privada:** Um par de chaves é usado: a chave
  pública criptografa os dados, e a chave privada correspondente
  descriptogafa-os.

* **Porta 443:** Por padrão, o HTTPS utiliza a porta 443 do servidor
  para a comunicação, enquanto o HTTP usa a porta 80.
