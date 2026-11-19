# Plano de estudos: Ciência de Dados do zero ao sênior

Nov 18, 2026 · @Jahzinho

## Visão geral

Com 30 horas por semana, você fica pronto para vagas júnior em 6 a 7 meses, para vagas pleno em 12 a 15 meses e para vagas sênior em 3 a 4 anos. O conhecimento técnico de sênior dá para alcançar em 1,5 a 2 anos. Já o cargo depende de experiência real em empresa, e é por isso que a última fase é mais longa.

- **Ponto de partida:** estatística em Python com pandas.
- **Meta:** vaga remota internacional de cientista de dados sênior.
- **Ritmo sugerido:** 30 horas por semana, ou seja, 5 horas por dia em 6 dias, com 1 dia de folga. Dessas horas, 18 vão para projetos e código, 7 para teoria e 5 para inglês.
- **Regra de ouro:** toda fase termina com projetos publicados no GitHub. Cada projeto entra no portfólio.
- **Inglês:** acompanha o plano inteiro, com 5 horas por semana. É ele que abre as vagas internacionais.

Dobrar as horas não dobra o aprendizado. Reserve 1 a 2 horas por semana para revisar o que já estudou, com flashcards no Anki, e não abra mão do dia de folga. Se o seu tempo diminuir, mantenha a ordem das fases e estique os prazos.

&#91;embedded content: roteiro · 5 fases e 3 marcos de carreira\]

As fases 1 a 3 cabem nos primeiros 6 a 7 meses. Depois disso, o avanço depende de experiência real em empresa.

## Fase 1 · Fundamentos (semanas 1 a 6)

O objetivo desta fase é limpar, analisar e explicar qualquer conjunto de dados tabular usando Python e SQL.

**O que estudar**

1. Python: funções, listas, dicionários, compreensões de lista, tratamento de erros e o básico de classes.
2. pandas e NumPy: `groupby`, `merge`, `pivot_table`, datas e valores ausentes.
3. Estatística: estatística descritiva, distribuições, intervalos de confiança, testes de hipótese (t, qui-quadrado), correlação e regressão linear simples, usando `scipy` e `statsmodels`.
4. Visualização: matplotlib e seaborn. Aprenda a escolher o gráfico certo para cada pergunta.
5. SQL: SELECT, JOIN, GROUP BY, subconsultas e window functions. Dá para praticar no SQLite ou no PostgreSQL.
6. Ferramentas: Git e GitHub, Jupyter, VS Code e ambientes virtuais.

**Projetos de portfólio**

- **P1. Análise exploratória com dados públicos brasileiros** (IBGE, INMET ou dados.gov.br): faça 3 perguntas de negócio e responda cada uma com gráficos e um resumo escrito.
- **P2. Teste A/B do início ao fim:** use um dataset público do Kaggle. Formule a hipótese, calcule o tamanho de amostra, aplique o teste e escreva a recomendação final.
- **P3. SQL com o dataset de e-commerce da Olist** (Kaggle): calcule receita por estado, retenção por coorte e tempo de entrega. Use só SQL e documente as consultas.

**Pronto para a próxima fase quando:** você conseguir explicar um p-valor sem jargão e escrever um JOIN com window function sem consultar nada.

## Fase 2 · Machine learning clássico (semanas 7 a 12)

O objetivo desta fase é treinar, avaliar e explicar modelos preditivos para problemas de negócio. A maior parte das vagas usa esse tipo de modelo no dia a dia.

**O que estudar**

1. A matemática necessária: vetores, matrizes, derivadas e gradiente, no nível intuitivo.
2. scikit-learn: pipelines, regressão linear e logística, árvores, random forest e k-means.
3. Boosting: XGBoost e LightGBM, os modelos mais usados com dados tabulares.
4. Avaliação: validação cruzada, vazamento de dados, métricas (RMSE, AUC, precisão e recall) e classes desbalanceadas.
5. Feature engineering e explicabilidade com SHAP.
6. Apresentação: um app simples em Streamlit e um README que traduza o resultado em impacto para o negócio.

**Projetos de portfólio**

- **P4. Previsão de churn:** compare 3 modelos e explique os fatores com SHAP. Estime quanto dinheiro uma ação de retenção economizaria.
- **P5. Precificação de imóveis ou carros:** um problema de regressão com features construídas por você e uma análise dos erros do modelo.
- **P6. App em Streamlit publicado:** pegue o P4 ou o P5 e coloque online para que qualquer pessoa possa testar.
- **Kaggle:** participe de uma competição tabular e publique um notebook bem comentado.

**Pronto para a próxima fase quando:** você conseguir explicar por que um modelo com 99% de acurácia pode ser inútil e como evitar vazamento de dados.

## Fase 3 · ML avançado e IA generativa (meses 4 a 7)

O objetivo desta fase é dominar as áreas que mais aparecem nas vagas atuais: séries temporais, deep learning e LLMs. A partir do mês 5, você já começa a se candidatar.

**O que estudar**

1. Séries temporais: decomposição, ARIMA, Prophet e previsão com LightGBM, além de validação temporal.
2. Deep learning com PyTorch: redes densas, treino, regularização e noções de CNN.
3. NLP com Hugging Face: tokenização, embeddings e fine-tuning de um modelo pequeno.
4. LLMs: uso de APIs, engenharia de prompt, RAG com banco vetorial e avaliação de respostas.
5. Inferência causal básica: diferença em diferenças e propensity score.

**Projetos de portfólio**

- **P7. Previsão de demanda ou de vendas:** compare uma linha de base simples com modelos mais sofisticados, usando validação temporal.
- **P8. Classificador de sentimento em português:** use as avaliações da Olist e faça fine-tuning de um modelo BERT em português.
- **P9. Assistente RAG sobre documentos públicos** (leis, editais ou manuais): inclua um conjunto de perguntas para medir a qualidade das respostas.

**Marco de carreira:** monte o currículo em inglês e comece a se candidatar a estágio, vaga júnior ou freelas. Primeiro em empresas brasileiras, depois nas plataformas internacionais. Experiência real acelera muito as próximas fases.

## Fase 4 · ML em produção (meses 8 a 15)

O objetivo desta fase é colocar modelos no ar e mantê-los funcionando. Isso separa o pleno do júnior, e as vagas internacionais cobram bastante.

**O que estudar**

1. Engenharia de software: código modular, testes com `pytest`, tipagem e boas práticas de Git.
2. Servir modelos: APIs com FastAPI e containers com Docker.
3. MLOps: MLflow para rastrear experimentos, CI/CD com GitHub Actions e monitoramento de drift.
4. Cloud: escolha AWS ou GCP e aprenda armazenamento, computação e o serviço de ML da plataforma. Uma certificação de nível associate ajuda o currículo.
5. Dados em escala: Spark ou Databricks, Snowflake ou BigQuery, além de noções de dbt e Airflow.

**Projeto de portfólio**

- **P10. Sistema completo:** um pipeline que coleta dados, treina o modelo e o serve por uma API em Docker hospedada na cloud. Inclua monitoramento e retreino agendado. Escolha um tema que conecte seus projetos anteriores.
- **Open source:** contribua com pelo menos 1 pull request em uma biblioteca de dados (documentação também conta).

**Marco de carreira:** por volta do mês 12 a 15, candidate-se a vagas pleno remotas na América Latina (Jobgether, Remotar, Remote Rocketship, Turing e LinkedIn).

## Fase 5 · Rumo ao sênior (anos 2 a 4)

O objetivo desta fase é transformar conhecimento em impacto comprovado. O que define um sênior não é saber mais ferramentas: é escolher o problema certo, desenhar a solução e influenciar decisões.

**O que desenvolver**

1. Especialização: escolha uma trilha principal entre experimentação e produto, NLP e LLMs, forecasting e pricing, ou MLOps.
2. Desenho de sistemas de ML: saber defender as escolhas de arquitetura, custo, latência e trade-offs em entrevistas.
3. Negócio: traduzir métricas de modelo em receita, custo ou risco e apresentar para a liderança.
4. Liderança técnica: revisar código, ser mentor de júnior e conduzir projetos de ponta a ponta.
5. Visibilidade: artigos técnicos em inglês, palestras em meetups e um portfólio com casos de impacto reais.

**Na prática**

- Para cada projeto que fizer no trabalho, registre o problema, a solução e o resultado em números. Isso vira o seu currículo sênior.
- Publique 1 artigo técnico por trimestre sobre o que aprendeu (sem expor dados da empresa).

**Marco de carreira:** vagas sênior internacionais pagas em dólar, por volta do ano 3 ou 4, somando o estudo e a experiência real.

## Portfólio, inglês e candidatura

Um portfólio com 6 a 8 projetos bem documentados vale mais do que 20 notebooks soltos.

**Padrão para cada projeto no GitHub** (README em inglês)

1. O problema de negócio em 2 frases.
2. Os dados: de onde vieram e quais são as limitações.
3. O método e por que foi escolhido.
4. O resultado em números e o que ele significa para o negócio.
5. Como reproduzir: `requirements.txt` e as instruções de execução.
6. Os próximos passos e o que você faria diferente.

**Presença online**

- **GitHub:** fixe no perfil os 6 melhores projetos e mantenha um README de apresentação.
- **LinkedIn em inglês:** título como "Data Scientist | Python · SQL · ML". Poste um resumo a cada projeto concluído.
- **Kaggle ou Medium:** publique notebooks e artigos explicando os projetos.

**Inglês**

- Leia documentação e faça cursos em inglês desde o primeiro mês.
- A partir do mês 6, pratique conversação toda semana. Simule entrevistas apresentando seus projetos em voz alta.

**Candidatura**

- Currículo de 1 página em inglês, que passe em filtros automáticos (ATS), com resultados em números.
- Plataformas: Jobgether, Remotar, Remote Rocketship, Turing, Working Nomads, Remotive e LinkedIn (filtro LATAM).
- Prepare-se para 4 tipos de etapa: triagem, teste técnico ou case para casa, entrevista técnica de estatística e ML, e entrevista comportamental.

## Checklist de acompanhamento

Marque cada item ao concluir. Os projetos estão na ordem em que devem ser feitos.

- [ ] Fase 1: P1, análise exploratória com dados públicos
- [ ] Fase 1: P2, teste A/B
- [ ] Fase 1: P3, SQL com a Olist
- [ ] Fase 2: P4, previsão de churn com SHAP
- [ ] Fase 2: P5, regressão de preços
- [ ] Fase 2: P6, app Streamlit publicado e notebook no Kaggle
- [ ] Fase 3: P7, previsão de demanda
- [ ] Fase 3: P8, sentimento em português
- [ ] Fase 3: P9, assistente RAG
- [ ] Fase 3: currículo em inglês pronto e primeiras candidaturas enviadas
- [ ] Fase 4: P10, sistema completo na cloud
- [ ] Fase 4: certificação de cloud e 1 contribuição open source
- [ ] Fase 4: primeira vaga pleno remota
- [ ] Fase 5: especialização escolhida e 4 artigos técnicos publicados
- [ ] Fase 5: vaga sênior internacional
