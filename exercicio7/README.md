Explicação:

python3 -m http.server → Inicia um servidor HTTP simples usando Python.

8443 → Porta escolhida (comumente usada para HTTPS).

--bind 0.0.0.0 → Faz o servidor escutar em todas as interfaces de rede.

O que aconteceu no print:

O servidor foi iniciado corretamente, mas ao acessar https://localhost:8443, apareceram erros como “400 Bad Request Syntax” e “400 Bad Request Version”.

Isso ocorre porque o servidor Python padrão não implementa HTTPS de verdade. Ele só serve HTTP.
Quando você tenta acessar com https://, o navegador envia uma requisição criptografada que o servidor não entende, resultando nos erros.

Conclusão do exercício:  
O erro é esperado e serve para mostrar que, sem configuração adequada de SSL/TLS, o servidor não consegue responder a conexões seguras. Para ter HTTPS funcional, seria necessário configurar um servidor como Apache ou Nginx com suporte a certificados.
