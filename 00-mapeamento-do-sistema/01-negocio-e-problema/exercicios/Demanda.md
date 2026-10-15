A EcoLogistics é uma empresa de transporte sustentável que precisa automatizar sua operação de entregas urbanas usando bicicletas elétricas. Atualmente, os operadores de frota recebem solicitações de entrega por telefone e anotam em planilhas, o que causa atrasos e erros no cálculo de rotas. O diretor da empresa relatou que o principal gargalo é a perda de mercadorias por falta de acompanhamento do status do pacote em tempo real, gerando um prejuízo financeiro imenso. Para resolver isso, eles precisam de um sistema central onde o cliente corporativo realiza o pedido de envio indicando peso, endereço de origem e destino. O sistema deve calcular automaticamente a tarifa com base na distância e no peso. Apenas os operadores da frota têm permissão para aprovar o pedido e atribuir uma bicicleta disponível ao entregador. Se a bicicleta estiver com status de manutenção ou com carga de bateria abaixo de vinte por cento, a atribuição deve ser bloqueada imediatamente pelo sistema. O entregador, através da sua interface, só visualiza as entregas atribuídas a ele e deve atualizar o status para em trânsito e posteriormente para entregue. Caso o tempo estipulado para a entrega expire sem a confirmação do entregador, o sistema precisa sinalizar o pedido como crítico no painel do operador. O projeto precisa priorizar respostas rápidas na API e ter uma estrutura de dados consistente para suportar simulações de carga durante os testes de validação.

🎯 Sua Missão de Prática (Nível Prova SPSKILLS)
Sem copiar o texto e lendo uma única vez se possível, extraia a visão completa do sistema respondendo aos 4 pontos de análise rápida:

O Problema de Negócio (A Dor Real): Qual é a dor central que o sistema veio resolver para a empresa?

Core Business (O Coração do Sistema): Qual é o fluxo/módulo vital sem o qual o sistema não tem razão de existir?

Regras de Negócio Críticas & Permissões (As Regras de Ouro):

Mapeie os Personagens/Perfis de acesso.

Identifique as travas de validação usando o padrão: [QUEM] + [PODE / NÃO PODE / SOMENTE SE] + [AÇÃO].

Fluxo de Valor: Qual é o caminho do dado desde a Entrada -> Processamento -> Saída Final?