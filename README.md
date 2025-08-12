# HTTP e HTTPs
Explica que a internet funciona no modelo cliente-servidor, onde um cliente solicita e um servidor responde, usando regras chamadas protocolos. O HTTP é o protocolo mais importante da web, definindo como ocorre a comunicação entre essas duas partes.

Mostra que no HTTP os dados trafegam em texto puro, o que é inseguro para informações sensíveis. Para resolver isso, existe o HTTPS, que adiciona criptografia usando SSL/TLS, protegendo as informações durante o tráfego.

Descreve que o HTTPS usa criptografia de chave pública e privada, validada por um certificado digital emitido por uma autoridade certificadora, garantindo a identidade do site e a segurança da comunicação.

Explica a estrutura de um domínio, subdomínios e endereços IP, além do papel do DNS, que converte nomes de domínio em endereços numéricos para facilitar o acesso aos sites.

Mostra que cada protocolo utiliza uma porta padrão para comunicação: HTTP usa a 80 e HTTPS usa a 443, podendo ser omitidas no endereço.

Define a estrutura de uma URL como protocolo, domínio, porta, caminho e recurso, sendo usada para localizar elementos específicos na web.

Explica que o HTTP é stateless, ou seja, não guarda informações de requisições anteriores, e que para manter dados de usuário entre requisições usa-se sessões, implementadas por meio de cookies.

Apresenta o uso do console do navegador para analisar requisições HTTP, mostrando métodos como GET, códigos de status (200, 301), redirecionamentos e diferentes tipos de conteúdo retornados.

Mostra códigos de resposta HTTP, suas categorias (2xx, 3xx, 4xx, 5xx) e exemplos comuns como 200 (sucesso), 404 (não encontrado) e 500 (erro interno).

Resume que o depurador do navegador permite analisar métodos HTTP, cabeçalhos e códigos de status para entender o que ocorreu com a requisição.

Explica como o status 301 redireciona para HTTPS e que o 200 indica sucesso, reforçando a relação entre códigos HTTP e o processamento da requisição.

Mostra como parâmetros podem ser enviados na URL com GET (visíveis) ou no corpo da requisição com POST (ocultos), sendo GET mais usado para buscas e POST para criação ou envio seguro de dados.

Resume as diferenças entre GET (busca) e POST (envio/criação), e cita outros métodos HTTP como PUT e DELETE, usados para atualizar ou remover recursos, além de mencionar cabeçalhos adicionais.

Apresenta os serviços web e APIs, mostrando formatos de resposta como HTML, XML e JSON, e o uso de cabeçalhos HTTP para especificar o tipo de dado desejado.

Introduz o padrão REST, que combina URIs para recursos, métodos HTTP para operações e formatos de representação como JSON ou XML, padronizando a comunicação entre sistemas.

Resume que REST usa HTTP para acessar recursos via URI, com métodos GET, POST, PUT e DELETE, e cabeçalhos para definir o formato dos dados.

Apresenta o uso do CURL para realizar requisições fora do navegador, descreve a estrutura do HTTP/1.1 e as melhorias do HTTP/2, como compressão de cabeçalhos, TLS obrigatório e mais desempenho.

Explica que no HTTP/2 não é necessário repetir cabeçalhos iguais em requisições consecutivas, reduzindo o tráfego e melhorando a eficiência (Headers Stateful).

Mostra o recurso Server Push do HTTP/2, no qual o servidor pode enviar arquivos necessários antes de o cliente solicitá-los, agilizando o carregamento da página.

Explica o uso do TCP para estabelecer conexões e como o Keep-Alive permite reutilizar conexões. No HTTP/2, o Multiplexing permite múltiplas requisições e respostas paralelas na mesma conexão.

Resume que o HTTP/2 mantém a base do HTTP, mas adiciona melhorias como compressão automática, cabeçalhos binários, Server Push, paralelismo e redução no envio de dados repetidos.

Finaliza destacando a importância do HTTP para todas as áreas do desenvolvimento e a aplicação prática do conteúdo para diversas especializações.
