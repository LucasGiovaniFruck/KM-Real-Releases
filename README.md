# KM Real

Aplicativo Android para entregadores do **iFood para Entregadores** saberem, no momento em que a chamada toca, se a corrida realmente compensa.

> 📥 **[Baixar a versão mais recente (APK)](https://github.com/LucasGiovaniFruck/KM-Real-Releases/releases/latest)**

## O que o app faz

- **Cálculo instantâneo na tela de chamada:** lê o valor, a distância e o tempo da oferta no iFood e exibe um card flutuante com:
  - **R$/km líquido** (já descontando o seu custo por quilômetro — padrão **R$ 0,40/km**, ajustável)
  - **Valor líquido em R$** que sobra no bolso
  - **% de lucro** da corrida
  - **Ganho/hora estimado da oferta** (quando a chamada informa duração ou horário limite)
- **Rotas Disponíveis na tela de escolha:** identifica automaticamente a lista de rotas disponíveis no iFood, ordenando a melhor opção (maior R$/km líquido) no topo do card e exibindo as demais corridas logo abaixo.
- **Rotas duplas e triplas (`2x` / `3x`):** identifica automaticamente rotas agrupadas, exibe o selo **2x** ou **3x** no card flutuante e mostra a distância até a coleta e o lucro líquido por entrega.
- **Radar de Lojas Evitadas:** cadastre estabelecimentos que prefere evitar; quando tocar uma chamada dessas lojas, a borda do card pulsa suavemente e exibe um alerta visual logo abaixo das informações.
- **Semáforo personalizável:** configure quanto custa rodar por km e defina os limites para o card acender em **Verde** (boa), **Amarelo** (média) ou **Vermelho** (ruim).
- **Card prático no dia a dia:** arraste para qualquer ponto da tela, escolha entre **Modo Claro** e **Modo Escuro**, ative o **auto-ocultar após 60 segundos** ou deixe os valores zerarem sozinhos após **90 segundos**.
- **Dashboard & Médias (100% offline):**
  - **Gráficos e indicadores exclusivos de corridas aceitas** (a captura identifica automaticamente corridas aceitas sem duplicar registros, com opção de ajuste manual no histórico).
  - **Meta Diária Líquida** configurada e acompanhada diretamente no topo do Dashboard.
  - **Ganho/hora real pelo seu turno:** informe a **hora que saiu de casa** e a **hora que chegou em casa** no Dashboard para calcular seu ganho/hora exato do dia (incluindo turnos que viram a madrugada), ou acompanhe a estimativa automática pelas ofertas.
  - **Gastos extras e gorjetas:** lance gastos de combustível, manutenção, alimentação ou outros, e registre **gorjetas** de forma independente direto no **Dashboard** (**Lançar gorjeta**, ideal para dinheiro vivo) ou automaticamente ao abrir o **Extrato** do iFood (com data e hora preservadas).
  - Filtros por período (*Hoje*, *Últimos 7 dias* e *Todo o período*), tudo salvo apenas no próprio aparelho, sem depender de internet.

## Como instalar e usar

1. Acesse a aba **[Releases](https://github.com/LucasGiovaniFruck/KM-Real-Releases/releases)** deste repositório e baixe o arquivo `.apk` da versão mais recente (`KM-Real-v1.2.0-release.apk`).
2. Instale o APK no seu Android (caso peça, permita a instalação de fontes desconhecidas).
3. Abra o **KM Real**, ajuste seu **Custo por km** (padrão `0,40`), os **Limiares do Semáforo** e, se quiser, cadastre lojas no **Radar de Lojas Evitadas**.
4. Toque em **Iniciar** (ou em **Permissões do Sistema**), leia a divulgação de acessibilidade e siga os passos mostrados na tela para liberar as permissões necessárias.
5. Deixe o serviço ativo (**Monitorando**) e abra o **iFood para Entregadores**. Ao encerrar o dia, toque em **Parar** e confira seus resultados em **Dashboard & Médias**.

## Histórico de Versões

### v1.2.0
- **Rotas Disponíveis na tela de escolha:** detecção da tela de rotas disponíveis do iFood, cálculo de todas as opções com ordenação da melhor rota (maior R$/km líquido) no topo do card e exibição das demais corridas logo abaixo com primeira palavra da loja, líquido, R$/km e semáforo.
- **Rotas agrupadas (`2x` / `3x`):** detecção de entregas duplas e triplas com selo no card flutuante, distância até a coleta e ganho líquido por entrega.
- **Gorjetas independentes (Dashboard e Extrato):** lançamento manual rápido na aba **Dashboard** (`Lançar gorjeta`) para gorjetas em dinheiro ou avulsas sem depender de clicar em corridas, além da captura automática ao visualizar o **Extrato** do iFood com preservação exata de data e hora.
- **Radar de Lojas Evitadas:** cadastro de lojas para alerta visual com borda pulsante no card flutuante e marcação no Histórico.
- **Ajustes de turno e meta no Dashboard:** novo **Custo por km** padrão de **R$ 0,40**, **Meta Diária Líquida** editável diretamente no Dashboard e cálculo de **R$/hora real por turno** informando a hora de saída e chegada em casa.

### v1.1.0
- **Dashboard & Médias completo:** painel exclusivo de corridas aceitas com gráficos (Lucro vs Gastos, Desempenho por Turno e Semáforo das Aceitas), lançamento de gastos extras e registro automático de corridas aceitas sem duplicidade.
- **Ganho por hora na oferta:** estimativa de **R$/h** em tempo real no card flutuante e no Histórico.
- **Transparência na acessibilidade:** tela de divulgação clara antes da ativação do serviço de acessibilidade.

### v1.0.0
- Lançamento inicial com leitura em tempo real das chamadas do iFood, card flutuante arrastável (Modo Claro/Escuro, auto-ocultar 60s e limpeza em 90s), semáforo configurável e histórico local de médias.
