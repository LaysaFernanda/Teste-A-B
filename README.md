# Teste-A-B
Projeto de análise de testes A/B para tomada de decisões

Neste projeto, junto com o departamento de marketing, foi compilado uma lista de hipóteses que podem ajudar a aumentar a receita.
Para isso precisei priorizar essas hipóteses, lançar um teste A/B e a partir dos resultados tomar uma decisão, se é melhor:

- Parar o teste, considere um dos grupos o líder.
- Parar o teste, conclua que não há diferença entre os grupos.
- Continuar o teste.

### Descrição dos dados

A tabela hypotheses (hipóteses):
- Hypotheses — breves descrições das hipóteses
- Reach — alcance do usuário, em uma escala de um a dez
- Impact — impacto nos usuários, em uma escala de um a dez
- Confidence — confiança na hipótese, em uma escala de um a dez
- Effort — os recursos necessários para testar uma hipótese, em uma escala de um a dez. Quanto maior o valor de Effort, mais recursos são necessários para o teste.

A tabela orders (pedidos):
- transactionId — identificador do pedido
- visitorId — identificador do usuário que fez o pedido
- date — do pedido
- revenue — do pedido
- group — o grupo de teste A/B ao qual o usuário pertence

A tabela visits (visitas):
- date — data
- group — grupo de teste A/B
- visits — o número de visitas na data especificada para o grupo de teste A/B especificado

### Bibliotecas usadas:
- pandas
- numpy
- matplotlib
- scipy
