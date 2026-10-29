# Central do FER — Fresh Eyes Review

Sistema de controle das entrevistas Fresh Eyes Review (FER) com grandes contas — Client Retention, Pluxee.

- **Visão operacional:** Hoje (lembretes e pendências), Régua do FER, Cronograma, Entrevistas, Histórico e Plano de ação.
- **Visão estratégica:** Relatórios com exportação para Excel e Visão executiva para o Comitê.
- **Materiais:** gera o PPT detalhado e o PDF resumido de cada entrevista.

## Como roda hoje

O arquivo `index.html` é a página completa. Hoje ela roda publicada no Claude (claude.ai), que fornece:
- a base de dados compartilhada;
- o login (conta do Claude de cada pessoa) e os perfis admin / operacional;
- as funções com IA (gerar PPT a partir da transcrição, ajustes, leitura para o Comitê).

Aberta fora do Claude (ex.: GitHub Pages), a página carrega, mas sem base de dados e sem as funções de IA. Para rodar fora do Claude, a base e o login precisam ir para um serviço próprio (ex.: Supabase).

**Este repositório guarda só o código. Nenhum dado de cliente fica aqui.**
