@title[Electrolux – Assessment BW]


---

## Agenda
1. @color[23315a(]Cenário Atual)
2. Recomendações
3. Projetos

---

## MOTIVADORES DO ASSESSMENT NO SAP BW
<br>
@fa[star]
<br>
-Validar arquitetura e melhores práticas
<br>
@fa[clock]
<br>
-Problemas com a **PERFORMANCE** dos indicadores desenvolvidos
<br>
@fa[frown]
<br>
- **INSATISFAÇÃO** DA ÁREA DE NEGÓCIO
<br>

+++

- @fa[bar-chart](Bar Chart)
- @fa[line-chart](Line Chart)
- @fa[pie-chart](Pie Chart)
- @fa[area-chart](Area Chart)
---

## ANÁLISE DO CENÁRIO ATUAL

Análise realizada com o auxílio do consultor Carlos Souza:
- Objetos utilizados pela query do comercial (ZSD_M99B_Q0001):
	1. PERFORMANCE na execução dos RELATÓRIOS EMPRESARIAIS;
	2. FALTA DE AGILIDADE para análise dos resultados;
	3. FALTA DE FLEXIBILIDADE nas análises e tratamento de dados PARA OS POWER USERS.

- Análise da query SALES MONITORING:
	1. DEMASIADAS KEY FIGURES (>100);
	2. TODOS OS FILTROS marcados COMO OPCIONAIS.

- Análise do MULTICUBO ZSD_M99B:
	1. DEMASIADOS Info-objetos Utilizados (16);
	2. BAIXA GRANULARIDADE DOS DADOS.
	
---

## RECOMENDAÇÕES

- CRIAR DATAMARTS E QUERIES ESPECÍFICAS para cada área de análise/ grupo de dados:
	- Retorno: MELHORIA NA PERFORMANCE de consumo dos dados pré-agregados.

- UTILIZAR A FUNÇÃO REPORT-REPORT INTERFACE para navegar entre os objetos gerencias e analíticos:
	- Retorno: Análises direcionadas através do FILTRO AUTOMÁTICO NA NAVEGAÇÃO.

- Utilizar FERRAMENTA ESPECÍFICA PARA SELF-SERVICE BI para consumo massivo de dados:
	- Retorno: Permite uma MAIOR FLEXIBILIDADE NA TRANSFORMAÇÃO E CONSUMO dos dados localmente.
	
## QUICK WINS

- Remodelar os objetos + Treinamento dos Power Users:
	- Retorno: 
		- melhoria de performance;
		- entendimento dos conceitos de BI, melhor utilização dos relatórios e analises self-service.
	- Tempo de execução: 3 MESES
	- Investimento: 185 K REAIS. 
	
	
		
---?image=images/bg_final.png
	
