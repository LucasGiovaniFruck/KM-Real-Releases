# Política de Privacidade — KM Real

**Última atualização:** 13 de novembro de 2026

Esta Política de Privacidade descreve como o aplicativo **KM Real** (`com.kmreal.app`), desenvolvido por **Lucas Giovani Fruck**, trata as informações dos usuários.

---

## 1. Resumo (App 100% Offline)

O **KM Real** é um aplicativo utilitário que funciona de forma **100% offline** no seu dispositivo Android:
- **Não coletamos** dados pessoais identificáveis (nome, CPF, e-mail, telefone ou localização GPS).
- **Não enviamos** nenhuma informação para servidores externos, nuvem ou terceiros.
- **Não exibimos anúncios** e **não utilizamos** ferramentas de rastreamento ou *analytics*.

---

## 2. Uso da API de Acessibilidade (`AccessibilityService`)

Para calcular a rentabilidade das corridas em tempo real e exibir o card flutuante sobre a tela de chamada, o KM Real utiliza a API de Acessibilidade do Android de forma estritamente limitada e transparente:

1. **Consentimento explícito:** A permissão só é solicitada após a exibição de uma tela de **Divulgação em Destaque** explicando exatamente o que será lido e por quê.
2. **Restrição estrita de aplicativo:** O serviço é configurado para atuar **exclusivamente** no pacote do aplicativo **iFood para Entregadores** (`br.com.brainweb.ifood`).
3. **Zero leitura fora de uso:** Quando o monitoramento está **Parado** no KM Real, ou quando você abre qualquer outro aplicativo (incluindo aplicativos bancários, mensageiros ou navegadores), o serviço ignora imediatamente os eventos e **não realiza nenhuma leitura de tela**.
4. **Processamento local:** Os valores exibidos nas chamadas e no extrato do iFood (valor da entrega, distância, tempo estimado, nome do estabelecimento e gorjetas) são processados apenas na memória do aparelho para gerar o cálculo no card flutuante e registrar seu histórico offline. Nenhum dado de tela é transmitido pela rede ou compartilhado.

---

## 3. Armazenamento Local e Exclusão de Dados

Todas as preferências (custo por km, limiares do semáforo, lojas evitadas, meta diária e horários de turno) e os registros financeiros (histórico de corridas, gastos extras e gorjetas) são armazenados **exclusivamente no banco de dados local do seu próprio dispositivo**.

Você tem controle total sobre seus dados e pode removê-los a qualquer momento:
- Limpando os registros diretamente nas opções do aplicativo;
- Limpando os dados do aplicativo nas configurações do Android; ou
- Desinstalando o aplicativo.

---

## 4. Outras Permissões Utilizadas

- **Sobrepor a outros apps (`SYSTEM_ALERT_WINDOW`):** utilizada exclusivamente para exibir o card flutuante com o resultado do cálculo (R$/km, lucro líquido e semáforo) sobre a tela do iFood Entregador.
- **Serviço em primeiro plano (`FOREGROUND_SERVICE_SPECIAL_USE`) e Notificações (`POST_NOTIFICATIONS`):** utilizadas para manter o serviço de monitoramento ativo em segundo plano com uma notificação persistente visível enquanto você estiver com o monitoramento ligado.

---

## 5. Alterações nesta Política

Esta Política de Privacidade pode ser atualizada ocasionalmente para refletir melhorias no aplicativo ou adequações às diretrizes da Google Play Store. A data da última atualização estará sempre indicada no topo desta página.

---

## 6. Contato

Em caso de dúvidas sobre esta Política de Privacidade ou sobre o funcionamento do **KM Real**, entre em contato através da página oficial do projeto:
- Repositório oficial de distribuição: [github.com/LucasGiovaniFruck/KM-Real-Releases](https://github.com/LucasGiovaniFruck/KM-Real-Releases)
