# opencode-history

Este repositório contém o histórico de sessões, trocas de mensagens e execuções de ferramentas do [opencode](https://github.com/anomalyco/opencode), exportadas para fins de documentação, auditoria e consulta.

## Objetivo

Preservar o contexto das interações realizadas com o opencode ao longo do tempo, incluindo:
+- Mensagens do usuário e do assistente
+- Chamadas e resultados de ferramentas
+- Decisões tomadas durante as sessões
+- Evolução de tarefas e investigações

## Estrutura

+- `Export.md` – Exportação mais recente de uma sessão completa (formato markdown legível)
+- `Export.txt` – Versão em texto bruto da exportação
+- `history-*.json` – Históricos em formato JSON (um arquivo por sessão ou exportação)
+- `opencode-*.json` – Exportações diretas do opencode em JSON
+- `session-*.json` – Dados brutos de sessão
+- `*.jsonl` – Logs em formato JSON Lines para análise ou processamento

## Como usar

Você pode ler os arquivos diretamente para:
+
+- **Revisar decisões**: entender por que determinado código/alteração foi feito
+- **Recuperar contexto**: relembrar investigações ou debugging passados
+- **Auditoria**: rastrear o uso de ferramentas
+- **Aprendizado**: estudar abordagens utilizadas em sessões anteriores
+
+Os arquivos `.json`/`.jsonl` são ideais para processamento automatizado. O `Export.md` é o mais prático para leitura humana.
+
+## Observações
+
+- Os arquivos podem conter caminhos locais, logs e informações sensíveis. Revise antes de compartilhar publicamente.
+- Este repositório é um arquivo histórico, não um projeto funcional para executar.
+- Os nomes seguem o padrão de data/ID gerado pelo opencode.
+
+## Licença
+
+Consulte o arquivo `LICENSE` caso exista, ou siga os termos aplicáveis ao projeto original [opencode](https://github.com/anomalyco/opencode).
