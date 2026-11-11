# Teste de aplicativo móvel — Urban Lunch

Projeto da Sprint 5 do curso de QA Engineer da TripleTen: teste do aplicativo móvel **Urban Lunch**, de pedidos de almoço com retirada em pontos de coleta, com checklist e relatórios de bug no Jira.

## Objetivo

Verificar se o aplicativo segue os requisitos em todo o fluxo do pedido: escolha do ponto de coleta, escolha dos pratos, confirmação, acompanhamento, pedido entregue e mensagens de erro.

## O que foi feito

- **Checklist com 30 verificações**, organizado pelas seções dos requisitos:
  1. Seleção do local de coleta
  2. Escolha dos pratos
  3. Confirmação do pedido
  4. Tela de acompanhamento do pedido
  5. Pedido entregue
  6. Notificações de erro
- **8 relatórios de bug** no Jira, um para cada verificação reprovada, com título (onde, o quê e quando), descrição, passos para reproduzir, resultado esperado, resultado real e print.

## Resultados

| Indicador | Total |
|---|---|
| Verificações executadas | 30 |
| Aprovadas | 22 |
| Reprovadas | 8 |
| Relatórios de bug | 8 |

### Bugs encontrados

- O mapa não mostra a ordem dos pontos de coleta.
- O valor total não inclui o preço de todos os pratos e da entrega.
- O nome do restaurante fica sobreposto ao valor do pedido.
- O tempo restante para o preparo e a entrega não aparece no acompanhamento.
- Textos em espanhol no lugar do português ("Tiempo de entrega" e "Recibi el pedido").
- O rótulo "Total" aparece como "Geral".
- O ícone de check não aparece no ponto de coleta quando o pedido é entregue.

Todos os relatórios estão em [`BUGS.md`](BUGS.md).

## Arquivos

- [`checklist-app-mobile-urban-lunch.xlsx`](checklist-app-mobile-urban-lunch.xlsx): checklist com descrição de cada verificação, status e link para o bug.
- [`BUGS.md`](BUGS.md): os 8 relatórios de bug copiados do Jira, já que o Jira do projeto é privado.

## O que aprendi

- **Teste de aplicativo móvel:** testar o fluxo completo de um app, do primeiro toque até o pedido entregue, comparando com os requisitos e o layout.
- **Android Studio:** usar o emulador de dispositivos móveis para testar aplicativos.
- **Checklists:** separar cada requisito em um item próprio, para saber exatamente o que falhou.
- **Relatórios de bug:** escrever títulos que dizem onde, o quê e quando, e passos detalhados para reproduzir.
