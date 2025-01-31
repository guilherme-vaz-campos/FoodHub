# FoodHub

Declaração do problema - FoodHub (Great Learning Course)

Contexto:

O número de restaurantes em Nova Iorque aumenta dia após dia. Muitos estudantes e profissionais ocupados dependem destes restaurantes devido aos seus estilos de vida agitados. O serviço de entrega de comida online é uma ótima opção para eles. Desta forma, é proporcionado boa comida de seus restaurantes favoritos. Uma empresa agregadora de alimentos, FoodHub, oferece acesso a múltiplos restaurantes através de um único aplicativo de smartphone.

O aplicativo permite que os restaurantes recebam uma encomenda de um cliente diretamente online. O aplicativo designa um entregador da empresa para buscar a encomenda após a confirmação do restaurante. O entregador utiliza um gps para chegar ao restaurante e espera pela encomenda. Assim que o pacote é entregue ao entregador, é confirmado pelo aplicativo e o entregador inicia a viagem até a localização do cliente para a entrega do pacote. O entregador confirma a entrega pelo aplicativo após a entrega do pacote. O cliente pode avaliar a encomenda na aplicação. O agregador de alimentos ganha dinheiro ao recolher uma margem fixa da ordem de entrega nos restaurantes.

Objetivo:

A empresa agregadora de alimentos armazenou os dados de diferentes pedidos feitos pelos clientes registados em seu portal online. Eles querem analisar os dados para ter uma ideia da procura dos diferentes restaurantes, que os ajudará a melhorar a experiência de seus clientes. Suponha que você é contratado como cientista de dados nesta empresa e a equipe de ciência de dados compartilhou algumas das questões-chave que precisam ser respondidas. Realize a análise de dados para encontrar respostas a estas perguntas que ajudarão a empresa a melhorar o negócio.

Descrição de dados:
Os dados contêm os diferentes dados relacionados aos pedidos de comida. O dicionário de dados é apresentado abaixo.

Dicionário de dados:

order_id: ID exclusivo do pedido
customer_id: ID do cliente que fez o pedido
restaurant_name: Nome do restaurante
cuisine_type: Tipo de culinária do pedido
cost_of_the_order: Custo do pedido
day_of_the_week: Indica se o pedido é feito durante a semana ou de fim de semana (Durante a semana é de segunda a sexta e o fim de semana é sábado e domingo)
rating: Avaliação dada pelo cliente de 1 a 5
food_preparation_time: Tempo (em minutos) gasto pelo restaurante para preparar a comida. Isto é calculado através da diferença de indicação de tempo da confirmação de pedido pelo restaurante e da confirmação de recebimento do pacote do entregador.
delivery_time: Tempo (em minutos) tomado pelo entregador para entregar o pedido. Isto é calculado através da diferença de indicação de tempo entre a confirmação de recebimento do pacote do entregador e a informação de entrega
