O que foi feito:

Acesso ao https://localhost:8443 no navegador.

O navegador exibiu informações sobre a conexão e o certificado gerado.

Foi possível visualizar os detalhes de segurança, como:

O certificado emitido para Gabriel Dias Ramire.

O emissor sendo o mesmo (autossinado).

Algoritmo de chave pública RSA 2048 bits.

Algoritmo de assinatura SHA-256 com RSA.

Fingerprints (SHA-1 e SHA-256) que identificam unicamente o certificado.

Detalhes de criptografia da conexão (TLS 1.3, AES-128-GCM).

Explicação:

O navegador mostra um erro de segurança inicialmente porque o certificado é autossinado (não foi emitido por uma Autoridade Certificadora confiável).

Mesmo assim, é possível visualizar os detalhes e confirmar que:

O certificado está instalado e ativo.

Ele contém as informações que você definiu no CSR (nome, e-mail, organização, etc.).

A conexão foi estabelecida com criptografia (TLS), garantindo que os dados trafegam de forma segura, mesmo sem validação externa.

Conclusão do exercício:
Esse passo serve para validar que o certificado realmente funciona e foi reconhecido pelo navegador.
O erro é esperado em ambientes de teste, já que navegadores só confiam em certificados emitidos por CAs oficiais.
