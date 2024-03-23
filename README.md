# MapeandoDominioRS

Entidades de domínio:
Produto: Cada item individual que está sendo mantido no estoque, com os atributos número de identificação único(Id), nome, descrição, tamanho, preço e cor.
Estoque: O conjunto de todos os produtos mantidos pela empresa em um determinado momento, com informações sobre quantidades disponíveis e histórico de movimentações.
Venda: Transações que envolvem a venda de produtos, registrando detalhes como produtos vendidos, quantidades, datas e valores.
Ordem de compra: Requisições para comprar produtos, geradas com base em quantidades mínimas de estoque e tendências de vendas.
Fornecedor: Entidades externas que fornecem produtos à empresa, com informações sobre produtos, preços e prazos de entrega.

Casos de uso:
Rastreamento de produto: Permitir a atribuição de números de identificação únicos a cada produto e o registro de informações adicionais como tamanho e cor.
Definição de quantidades mínimas de estoque: Permitir que os usuários definam limites mínimos de estoque para cada produto.
Recebimento de alertas de estoque baixo: Enviar alertas por e-mail e notificações no sistema quando os níveis de estoque estiverem próximos dos limites mínimos definidos.
Visualização de histórico de vendas e estoque: Permitir que os usuários vejam informações detalhadas sobre vendas, lucros por produto e tendências de estoque ao longo do tempo, por meio de gráficos ou relatórios.
Criação e gerenciamento de ordens de compra: Automatizar o processo de geração e gerenciamento de ordens de compra com base nas quantidades mínimas de estoque e nas tendências de vendas.
Integração com fornecedores: Permitir a integração com os sistemas dos fornecedores para receber atualizações automáticas sobre preços, prazos de entrega de novas remessas.
