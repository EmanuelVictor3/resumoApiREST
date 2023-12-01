# Api REST e RESTFul
## _REST_
 A API REST é uma interface de programação de aplicações que segue os princípios de design do REST estilo de arquitetura do Representational State Transfer. As APIs de REST são uma maneira leve e flexível de integrar aplicativos. Elas surgiram como o método mais comum para conectar componentes em arquiteturas de microsserviços. Basicamente, uma API é um mecanismo que permite que um aplicativo ou serviço acesse um recurso dentro de outro aplicativo ou serviço. O aplicativo ou serviço que está realizando o acesso é chamado de cliente, e o aplicativo ou serviço contendo o recurso é chamado de servidor. As APIs de REST podem ser desenvolvidas usando praticamente qualquer linguagem de programação e oferecem suporte a uma variedade de formatos de dados. O único requisito é que eles devem alinhar aos *[seis princípios]* de design de REST a seguir, conhecidos como restrições de arquitetura:

- Interface uniforme.
- Desacoplamento do cliente-servidor.
- Sem estado definido.
- Capacidade de armazenamento em cache.
- Sistema em camadas.
- Código sob demanda.

Essas restrições de arquitetura ajudam a garantir que as APIs de REST sejam escaláveis, confiáveis e fáceis de manter.

## _RESTFul_
A API RESTful é uma interface de programação de aplicações em conformidade com as restrições do estilo de arquitetura REST, permitindo a interação com serviços web RESTful. Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis: Javascript Object Notation (JSON), HTML, XLT, Python, PHP ou texto sem formatação.

## _Diferenças entre REST e RESTFul_
A arquitetura REST é um conjunto de restrições arquiteturais aplicadas a componentes, conectores e elementos de dados dentro de um sistema de hipermídia distribuído. O objetivo é focar nos papéis dos componentes, nas restrições sobre sua interação com outros componentes e na sua interpretação de elementos de dados significantes. Ela ignora os detalhes da implementação de componente e a sintaxe de protocolo.

Por outro lado, RESTful refere-se a uma API que adere às restrições arquiteturais da arquitetura REST. Em outras palavras, uma API RESTful é simplesmente aquela que realiza a implementação do padrão REST.

Em resumo, REST é um conjunto de restrições arquiteturais, enquanto RESTful é a capacidade de um sistema aplicar essas restrições.

## _HTTP verbs_
HTTP verbs, também conhecidos como métodos HTTP, são ações que indicam a natureza da operação que está sendo solicitada em um recurso específico. Eles são parte fundamental do protocolo HTTP (Hypertext Transfer Protocol).

Os principais sendo:

- [GET]: O método solicita a representação de um recurso específico. Requisições utilizando o método devem retornar apenas dados.
- [HEAD]: Solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.
- [POST]: É utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.
- [PUT]: O método substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
- [DELETE]: Remove um recurso específico.
- [CONNECT]: Estabelece um túnel para o servidor identificado pelo recurso de destino.
- [OPTIONS]: É usado para descrever as opções de comunicação com o recurso de destino.
- [TRACE]: Executa um teste de chamada loop-back junto com o caminho para o recurso de destino.
- [PATCH]: É utilizado para aplicar modificações parciais em um recurso

## _HTTP Status Code_
São códigos numéricos fornecidos em respostas HTTP a uma solicitação feita por um cliente a um servidor. Eles indicam o resultado da solicitação e se a operação foi bem-sucedida, enfrentou algum tipo de problema ou requer alguma ação adicional.

Eles são divididos em cinco classes: respostas informativas (100-199), respostas bem-sucedidas (200-299), mensagens de redirecionamento (300-399), respostas de erro do cliente (400-499) e respostas de erro do servidor (500-599). [Lista de todos os codigos].

Sendo os mais comuns:
Codigo | Resposta
:----:|:---:
100 | Continue
200	| OK
201 | Criado
204	| Sem conteúdo
400	| Solicitação inválida
401	| Não autorizado
403	| Proibido
404	| Não encontrado
500	| Erro interno do servidor
-----

 ## Autor do resumo: Emanuel Victor Souza Xavier Senra - 01518804
 
 
[seis princípios]: https://www.ibm.com/br-pt/topics/rest-apis
[GET]: https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/GET
[HEAD]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/HEAD
[POST]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/POST
[PUT]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/PUT
[DELETE]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/DELETE
[CONNECT]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/CONNECT
[OPTIONS]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/OPTIONS
[TRACE]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/TRACE
[PATCH]:https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods/PATCH
[Lista de todos os codigos]: https://www.tutorialspoint.com/http/http_status_codes.htm