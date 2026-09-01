# controle-financeiro-pessoal

Aplicativo web de controle financeiro pessoal com exportação PDF e histórico mensal.

## Aplicativo

- Abra `controle-financeiro.html` no navegador para usar o aplicativo completo.
- Arquivo único e autocontido (HTML + CSS + JavaScript), funciona offline após o primeiro carregamento (usa Chart.js e jsPDF via CDN apenas para gráficos e exportação de PDF).
- Dados são salvos automaticamente no localStorage do navegador, por mês/ano.
- Funcionalidades:
  - Dashboard com 3 gráficos (distribuição do salário, projeção de previdências, projeção de quitação de dívidas) e totalizadores;
  - Contas fixas e cartões (contas variáveis), com status OK/Pendente;
  - Investimentos: previdências (com projeção 10/20/30 anos) e poupanças/viagens/presentes com comparativo mensal;
  - Dívidas grandes com recálculo automático da data de quitação e aportes extras;
  - Movimentações entre contas, com marcação de devolução;
  - Exportar PDF, Exportar/Carregar JSON (pré-preenchimento do próximo mês) e Salvar Localmente.

## Wireframe visual

- Abra `/home/runner/work/controle-financeiro-pessoal/controle-financeiro-pessoal/wireframe.svg` para visualizar a imagem do wireframe.
- Se preferir uma versão navegável do mesmo esboço, abra `/home/runner/work/controle-financeiro-pessoal/controle-financeiro-pessoal/wireframe.html` no navegador.
- O wireframe inclui:
  - header com navegação;
  - dashboard com gráfico donut, projeção de previdências e quitação de dívidas;
  - tabelas de contas fixas, cartões, investimentos, dívidas e movimentações;
  - footer com ações de exportação/importação.
