# Central Financeira IA — versão independente

Aplicativo web/PWA simples para controle financeiro da Raffani.

## Como usar
- Abra `index.html` no navegador para testar.
- Para instalar como PWA no iPhone/desktop, publique a pasta em um serviço de hospedagem estática com HTTPS (por exemplo, GitHub Pages).
- No iPhone: abra o endereço no Safari → Compartilhar → Adicionar à Tela de Início.

## Funcionalidades
- Visão geral com entradas, saídas e pendências.
- Cadastro de contas bancárias e saldos iniciais.
- Lançamentos a pagar/receber, pendentes ou confirmados.
- Importação básica de OFX, CSV e Excel.
- Importação de planilhas diretamente em Lançamentos (itens entram como pendentes).
- Leitura assistida de e-mails por arquivo .eml ou texto colado (sugestões entram como pendentes; não acessa automaticamente a caixa de entrada).
- Relatórios por mês e exportação CSV.
- Backup e restauração JSON.

## Privacidade e limitações importantes
- Os dados ficam no armazenamento local do navegador/aparelho.
- Não há login, servidor, sincronização automática nem envio de dados financeiros para a nuvem.
- Faça backup regular e proteja o arquivo exportado.
- A importação depende da estrutura do extrato; confira todos os movimentos antes de considerar a conciliação concluída.
- A importação PDF ainda não está implementada.
- A biblioteca XLSX é carregada de CDN para leitura de planilhas; para uso sem internet, será necessário empacotá-la localmente.
