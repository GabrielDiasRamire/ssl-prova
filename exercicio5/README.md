Explicação:

openssl x509 -req → Cria um certificado X.509 a partir de uma requisição (CSR).

-days 365 → Define a validade do certificado (1 ano).

-in aluno.csr → Usa o CSR como entrada.

-signkey aluno.key → Assina o certificado com a chave privada.

-out aluno.crt → Salva o certificado no arquivo aluno.crt.

O certificado digital é o documento que vincula a chave pública à identidade do dono. Ele pode ser usado para autenticação e comunicação segura.
