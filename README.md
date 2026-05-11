# Project Dashboard Analytics

## Descricao

Dashboard para acompanhamento de indicadores de projetos, riscos, cronograma, entregas, custos, beneficios e desempenho de portfolios.

## Problema que Resolve

Projetos complexos costumam sofrer com informacoes fragmentadas entre planilhas, atas, cronogramas e relatorios manuais. Isso dificulta a leitura executiva do portfolio, atrasa decisoes e reduz a capacidade de antecipar riscos.

## Para Quem Gera Valor

- PMOs e escritorios de projetos
- Gestores publicos e privados
- Centros de inovacao
- Equipes de PD&I
- Organizacoes que precisam prestar contas de resultados

## Solucao Proposta

Criar uma base sintetica de projetos com indicadores de progresso, risco, custo, prazo e status. A partir dela, gerar analises e visualizacoes que ajudem a priorizar atencao, identificar gargalos e acompanhar entregas.

## Tecnologias e Metodos

- Python
- Pandas
- Power BI ou Streamlit
- SQL
- KPIs e OKRs
- Gestao de riscos
- Metodologias hibridas de gestao de projetos

## Estrutura do Projeto

```text
data/       base sintetica de projetos
notebooks/  calculo de KPIs e analises exploratorias
docs/       modelo de indicadores e regras de leitura
src/        futuras funcoes de ETL e tratamento de dados
```

## Como Executar

```sh
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/project-kpi-demo.ipynb
```

## Resultados e Aprendizados

- Visao consolidada de projetos e portfolios
- Indicadores de risco e desempenho
- Base para dashboard executivo
- Aprendizado sobre governanca, priorizacao e acompanhamento de entregas

## Resultado Demonstrativo

Com os dados sinteticos em `data/projetos_exemplo.csv`, o notebook calcula desvio de custo e indice beneficio-custo para uma carteira de projetos.

| Projeto | Risco | Desvio de custo (kBRL) | Beneficio/Custo |
| --- | --- | ---: | ---: |
| Implantacao PMO | medio | -40 | 2,89 |
| Plataforma DPP | alto | -370 | 1,76 |
| Capacitacao Captacao Recursos | baixo | -2 | 5,00 |
| Dashboard Executivo | medio | -24 | 3,75 |
| Automacao Documental | alto | -220 | 2,69 |

## Autor

Rodrigo Willemann  
Email: rodrigo.willemann@gmail.com

