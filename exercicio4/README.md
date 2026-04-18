Explicação:

openssl req -new → Cria uma nova requisição de certificado.

-key aluno.key → Usa a chave privada gerada no exercício anterior.

-out aluno.csr → Salva a requisição no arquivo aluno.csr.

O CSR é um arquivo que contém informações da entidade (nome, organização, país, etc.) e a chave pública. Ele é enviado para uma Autoridade Certificadora (CA) para gerar um certificado válido.
