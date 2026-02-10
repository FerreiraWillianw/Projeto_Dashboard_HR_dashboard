Projeto de dashboard: People Analytics - Estratégia, Retenção e Liderança

    Resumo do Projeto: Este dashboard foi desenvolvido para transformar dados brutos de RH em inteligência de negócio. Ele abrange desde a eficiência do gasto com pessoal até a análise de causas de turnover e o diagnóstico de gestão de equipes.

📄 Página 1: Gestão Financeira e Estrutura Salarial

A primeira página responde à pergunta: Como a empresa está investindo seu capital humano?. O foco aqui é a evolução dos custos. Através do gráfico de Custo Médio por Contratação, identificamos se o mercado está ficando mais caro para a empresa ou se estamos mudando o perfil de senioridade ao longo dos anos. O Gráfico de Dispersão cruza esses salários com a performance real, permitindo identificar se os maiores investimentos estão trazendo os melhores resultados (Meritocracia).

    Insight-chave: Identificação de inflação salarial interna e disparidades entre departamentos.

    Visuais: Cartões de Custo Total e Média; Linha de Evolução de Contratação; Dispersão Salário vs. Performance; Treemap de Cargos.

📄 Página 2: Turnover e o Custo da Substituição

Perder um colaborador não é apenas perder um par de mãos, é perder investimento. Nesta página, calculamos o Custo Estimado do Turnover (baseado em 1,5x o salário médio) para mostrar o impacto direto no lucro da empresa. O diferencial aqui é o Treemap de Performance: ele nos diz se estamos perdendo pessoas que 'precisamos' perder (baixa performance) ou se estamos sofrendo um 'brain drain' (fuga de cérebros) de talentos nota máxima.

    Insight-chave: O turnover é financeiramente sustentável ou estamos perdendo nossos melhores ativos?

    Visuais: Taxa de Turnover; Custo de Saída; Desligados por Performance; Motivos de Saída (TermReason).

📄 Página 3: Diagnóstico de Liderança e Eficácia de Gestão

A última camada do projeto foca no fator que mais influencia os dois pilares anteriores: A Liderança. Utilizando uma Matriz de Calor, mapeamos a saúde de cada equipe. Conseguimos isolar se um problema de turnover é sistêmico (da empresa toda) ou se está concentrado em gestores específicos. É a ferramenta definitiva para o RH agir de forma cirúrgica, oferecendo treinamento aos líderes que possuem baixo índice de retenção ou baixa performance média.

    Insight-chave: Identificação de líderes 'formadores de talentos' versus líderes com alta taxa de atrito.

    Visuais: Matriz de Calor (Manager vs Performance); Ranking de Retenção por Gestor; Motivos de Dispensa por Equipe.

🛠️ Como eu fiz:

    Fonte dos dados: Dados extraídos da biblioteca do kaggle

    Tratamento de Dados: Limpeza de colunas irrevlevantes para a análise e criação de colunas calculadas para status de ativos/desligados.

    Cálculos Avançados (DAX): * Taxa de Turnover: Dinâmica para refletir o período selecionado.

        Custo de Contratação: Média salarial baseada na data de admissão.

        Custo de Turnover: Impacto financeiro baseado em benchmarks de mercado.

    UI/UX: Design minimalista feito no FIGMA focado em scannability (leitura rápida) com navegação intuitiva entre as páginas.


Capa: <img width="1088" height="613" alt="image" src="https://github.com/user-attachments/assets/72bc5455-72bb-4b4a-8fbe-8eae058459cf" />

Página 1: <img width="1089" height="607" alt="image" src="https://github.com/user-attachments/assets/900b100c-dbc6-4a2d-8905-08c51094b2b0" />

Página 2: <img width="1087" height="611" alt="image" src="https://github.com/user-attachments/assets/a63d4da5-f429-435d-be57-c8e5a630eb18" />

Página 3: <img width="1087" height="611" alt="image" src="https://github.com/user-attachments/assets/49ce9abf-ac82-4d3a-b684-a0b468d833a3" />




Link do relatório: 

# 🚀 Dashboard Interativo

[![Power BI](https://img.shields.io/badge/Power_BI-Acesse_o_Projeto-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiOWYxNjFlMzUtMDA2OC00ZWIyLTlhZGEtOTNkZGE1MjE1YmMwIiwidCI6IjJlZmMxNDk2LTE4NTktNDEyNy1iMDc4LTUwMTBhNGZlNGI5ZiJ9)

  
