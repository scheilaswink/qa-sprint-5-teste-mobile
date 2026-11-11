# Relatórios de bug — App Urban Lunch (Sprint 5)

Os 8 bugs abaixo foram registrados no Jira durante o teste do aplicativo móvel Urban Lunch. Como o Jira do projeto é privado, eles foram copiados para cá para que qualquer pessoa possa ler os relatórios.

Os IDs (SPRINT5-1 a SPRINT5-8) são os mesmos que aparecem na coluna "Link do relatório de bug" da planilha. Cada bug tem um print anexado no Jira.

## Resumo

| ID | Tela | Título | Prioridade |
|---|---|---|---|
| [SPRINT5-1](#sprint5-1) | Seleção do local de coleta | O mapa não exibe a ordem dos pontos de coleta | Média |
| [SPRINT5-2](#sprint5-2) | Confirmação do pedido | O valor total não inclui o preço de todos os pratos e da entrega | Média |
| [SPRINT5-3](#sprint5-3) | Confirmação do pedido | O nome do restaurante aparece sobreposto ao valor do pedido | Média |
| [SPRINT5-4](#sprint5-4) | Acompanhamento do pedido | O tempo restante para o preparo e a entrega não é exibido | Média |
| [SPRINT5-5](#sprint5-5) | Acompanhamento do pedido | Texto em espanhol: "Tiempo de entrega" em vez de "Tempo de entrega" | Média |
| [SPRINT5-6](#sprint5-6) | Acompanhamento do pedido | O rótulo "Total" aparece como "Geral" | Média |
| [SPRINT5-7](#sprint5-7) | Pedido entregue | O mapa não exibe o ícone de check no ponto de coleta | Média |
| [SPRINT5-8](#sprint5-8) | Pedido entregue | Texto em espanhol: "Recibi el pedido" em vez de "Recebi o pedido" | Média |

---

<a id="sprint5-1"></a>

## SPRINT5-1 — Na tela de seleção do local de coleta, o mapa não exibe a ordem dos pontos de coleta ao abrir o aplicativo

- **Prioridade:** Média

**Descrição:** Ao abrir o aplicativo Urban Lunch e acessar a tela de seleção do local de coleta, os pontos de coleta aparecem no mapa, porém sem a indicação da ordem, contrariando os requisitos.

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Observar os pontos de coleta exibidos no mapa.
3. Verificar se os pontos apresentam a numeração que indica a ordem.

**Resultado esperado:** O mapa mostra a ordem dos pontos de coleta.

**Resultado real:** O mapa não mostra a ordem dos pontos de coleta.

**Evidência:** print anexado no Jira.

---

<a id="sprint5-2"></a>

## SPRINT5-2 — Na tela de confirmação do pedido, o valor total não inclui o preço de todos os pratos e da entrega ao revisar o pedido

- **Prioridade:** Média

**Descrição:** Na tela de confirmação do pedido, o valor total exibido não corresponde à soma do preço de todos os pratos pedidos com o valor da entrega, contrariando os requisitos.

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, conferir o valor total do pedido.

**Resultado esperado:** O valor total inclui o preço de todos os pratos preparados e a entrega.

**Resultado real:** O valor total não inclui o preço de todos os pratos preparados e a entrega.

**Evidência:** print anexado no Jira.

---

<a id="sprint5-3"></a>

## SPRINT5-3 — Na tela de confirmação do pedido, o nome do restaurante aparece sobreposto ao valor do pedido ao exibir a lista de pratos

- **Prioridade:** Média

**Descrição:** Na tela de confirmação do pedido, o nome do restaurante não é exibido corretamente: o texto fica sobreposto ao valor do pedido.

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, observar o nome do restaurante e o valor do pedido.

**Resultado esperado:** O nome do restaurante é exibido corretamente, sem sobrepor o valor do pedido.

**Resultado real:** O nome do restaurante aparece sobreposto ao valor do pedido.

**Evidência:** print anexado no Jira.

---

<a id="sprint5-4"></a>

## SPRINT5-4 — Na tela de acompanhamento do pedido, o tempo restante para o preparo e a entrega não é exibido após fazer o pedido

- **Prioridade:** Média

**Descrição:** Na tela de acompanhamento do pedido, o custo dos pratos pedidos em cada restaurante é exibido, mas o tempo restante para o preparo e a entrega no ponto de coleta não aparece, contrariando os requisitos.

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, tocar no botão "Pedir".
6. Na tela de acompanhamento, conferir as informações exibidas para cada restaurante.

**Resultado esperado:** São exibidos o custo de todos os pratos pedidos no restaurante e o tempo restante para o preparo e a entrega no ponto de coleta.

**Resultado real:** O custo dos pratos é exibido, mas o tempo restante para o preparo e a entrega no ponto de coleta não é exibido.

**Evidência:** print anexado no Jira.

---

<a id="sprint5-5"></a>

## SPRINT5-5 — Na tela de acompanhamento do pedido, o texto aparece em espanhol ("Tiempo de entrega") em vez de "Tempo de entrega" após fazer o pedido

- **Prioridade:** Média

**Descrição:** Na tela de acompanhamento do pedido, o rótulo do tempo de entrega está em espanhol, diferente do layout, que mostra "Tempo de entrega".

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, tocar no botão "Pedir".
6. Na tela de acompanhamento, observar o rótulo do tempo de entrega.

**Resultado esperado:** O texto exibido é "Tempo de entrega", como no layout.

**Resultado real:** O texto exibido é "Tiempo de entrega".

**Evidência:** print anexado no Jira.

---

<a id="sprint5-6"></a>

## SPRINT5-6 — Na tela de acompanhamento do pedido, o rótulo "Total" aparece como "Geral" após fazer o pedido

- **Prioridade:** Média

**Descrição:** Na tela de acompanhamento do pedido, o rótulo do valor total aparece como "Geral", diferente do layout, que mostra "Total".

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, tocar no botão "Pedir".
6. Na tela de acompanhamento, observar o rótulo do valor total.

**Resultado esperado:** O texto exibido é "Total", como no layout.

**Resultado real:** O texto exibido é "Geral".

**Evidência:** print anexado no Jira.

---

<a id="sprint5-7"></a>

## SPRINT5-7 — Na tela de pedido entregue, o mapa não exibe o ícone de check no ponto de coleta quando o temporizador expira

- **Prioridade:** Média

**Descrição:** Na tela de pedido entregue, o mapa mostra a localização do ponto de coleta escolhido, mas sem o ícone de check previsto nos requisitos.

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, tocar no botão "Pedir".
6. Na tela de acompanhamento, aguardar o temporizador expirar.
7. Na tela de pedido entregue, observar o ponto de coleta no mapa.

**Resultado esperado:** O mapa mostra a localização do ponto de coleta escolhido com o ícone de check.

**Resultado real:** O mapa mostra a localização do ponto de coleta escolhido, mas sem o ícone de check.

**Evidência:** print anexado no Jira.

---

<a id="sprint5-8"></a>

## SPRINT5-8 — Na tela de pedido entregue, o texto aparece em espanhol ("Recibi el pedido") em vez de "Recebi o pedido" quando o temporizador expira

- **Prioridade:** Média

**Descrição:** Na tela de pedido entregue, o texto de confirmação do recebimento está em espanhol, diferente do layout, que mostra "Recebi o pedido".

**Passos para reproduzir:**

1. Abrir o aplicativo Urban Lunch.
2. Selecionar um ponto de coleta no mapa.
3. Adicionar um ou mais pratos com o botão "+".
4. Tocar no botão "Avançar".
5. Na tela de confirmação, tocar no botão "Pedir".
6. Na tela de acompanhamento, aguardar o temporizador expirar.
7. Na tela de pedido entregue, observar o texto de confirmação do recebimento.

**Resultado esperado:** O texto exibido é "Recebi o pedido", como no layout.

**Resultado real:** O texto exibido é "Recibi el pedido".

**Evidência:** print anexado no Jira.
