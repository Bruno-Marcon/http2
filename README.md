# Experimento

## 1 - HTTP/2
O HTTP/2 oferece várias vantagens, incluindo:
- Multiplexação: Envio simultâneo de múltiplos recursos em uma única conexão.
- Compressão de cabeçalhos: Reduz o tamanho dos cabeçalhos das solicitações e respostas.
- Priorização de requisições: Permite ao cliente especificar a prioridade das solicitações.
- Server Push: Permite ao servidor enviar recursos adicionais para o cliente antes mesmo de serem solicitados.

## 2 - Benefícios do HTTP/2
As melhorias incluem:
- Melhoria na performance de carregamento de página.
- Compressão de cabeçalhos.
- Server Push: Envio de recursos adicionais pelo servidor.

## 3 - Desafios do HTTP/2
Alguns desafios incluem:
- Maior complexidade na implementação devido à natureza binária e às novas funcionalidades.
- Necessidade de TLS, adicionando overhead em algumas situações.
- Compressão de cabeçalhos pode aumentar a carga de processamento nos servidores e clientes.

## 4 - Server Push
O Server Push permite ao servidor enviar recursos adicionais para o cliente antes mesmo de serem solicitados. Isso é útil quando o servidor sabe que o cliente provavelmente solicitará recursos relacionados após receber a resposta inicial.

## 5 - HTTP/3
O HTTP/3 utiliza o protocolo QUIC (Quick UDP Internet Connection) em vez do TCP, reduzindo a latência e melhorando o desempenho, especialmente em redes com perda de pacotes. Oferece conexões mais rápidas e robustas, além de lidar melhor com a multiplexação de solicitações e oferecer melhor suporte à resiliência contra perdas de pacotes.
