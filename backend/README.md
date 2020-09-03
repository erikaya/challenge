## Desafio para Backend Software Engineer

Você está revisando as decisões de design de um software que processa Pedidos online. Por estes pedidos, são realizados pagamentos que recebem tratamentos a depender as situações específicas de cada um como segue:

  - Se o pagamento for para um item físico, você deverá gerar uma label `shipping` para o mesmo ser colocado na caixa do envio;
  - Caso o pagamento seja uma assinatura de serviço, você precisa ativar a assinatura, e notificar o usuário através de e-mail sobre isto;
  - Caso o pagamento seja um livro comum, você precisa gerar uma label `shipping` com uma notificação de que trata-se de um item isento de impostos conforme disposto na Constituição Art. 150, VI, d.
  - Caso o pagamento seja de alguma mídia digital (música, vídeo), além de enviar a descrição da compra por e-mail ao comprador, conceder um voucher de desconto de R$ 10 ao comprador associado ao pagamento.

__O que é necessário fazer?__

Você ficou designado a prototipar como poderá ser feita a nova versão deste fluxo de pagamento/regras de envio, pois a versão atual é frágil, **encadeada em if/else, switch/case**, exigindo modificações grandes a cada nova regra de envio/processamento inserida ou removida.

Crie as classes, métodos e suas respectivas chamadas (a seu critério) para que você consiga tratar os cenários acima.

**Não é necessário** criar as implementações para envio de e-mails, imprimir a label _shipping_, etc. Para estes casos (email, shipping label) crie apenas as chamadas de métodos, para indicar que ali seria o local aonde o envio ocorreria.


__O que está sob avaliação?__

Sua capacidade de analisar, projetar e codificar uma solução guiando-se com **Design Orientado a Objetos** e **Princípios de Orientação a Objetos**.
