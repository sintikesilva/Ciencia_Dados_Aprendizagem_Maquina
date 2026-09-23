# Template - Definição do Projeto de Ciência de Dados

**Unidade:** III - Gestão de Projetos  
**Metodologia:** PBL + trabalho em equipes  
**Entregável:** Documento de definição do projeto

> **Finalidade:** delimitar um problema real e orientar o desenvolvimento do projeto de Ciência de Dados. Preencha todos os campos com informações objetivas, verificáveis e coerentes entre si.

## 1. Identificação do projeto

| Campo | Preenchimento |
|---|---|
| Título provisório do projeto | Metodologia e Painel de Avaliação de Segurança da Informação para Pequenas e Médias Empresas (PMEs) |
| Curso / disciplina | Bacharelado em Sistemas de Informação / Gestão de Projetos (Unidade III) |
| Turma | Turma de TCC / Gestão de Projetos 2026 |
| Equipe | Equipe de Avaliação de Conformidade de SI |
| Integrantes e funções iniciais | Sintike Barreira da Silva (Líder do Projeto, Analista de Dados e Especialista em Segurança da Informação) |
| Professor(a) | Prof. Me. Gleidson Porto Batista |
| Data de elaboração | 23/09/2026 |
| Versão do documento | v1.0 |

## 2. Visão geral

### 2.1 Resumo do projeto

Em até 100 palavras, apresente o problema, o público-alvo, a proposta de análise e o resultado esperado.

**Preenchimento:**

Pequenas e médias empresas (PMEs) enfrentam alto risco cibernético, mas carecem de diagnósticos acessíveis de Segurança da Informação. O projeto visa aplicar questionários estruturados baseados nas normas ISO/IEC 27001/27002 e NIST para coletar dados de conformidade em cinco dimensões (controle de acesso, autenticação, atualizações, backup e conscientização). Utilizando análise exploratória e modelagem quantitativa de dados, será calculado um **Índice de Conformidade (Score)** e gerada a classificação automática do nível de risco organizacional. O resultado esperado é um dashboard e relatório de diagnósticos que apoiarão gestores na tomada de decisão estratégica e redução de vulnerabilidades.

### 2.2 Declaração do projeto em uma frase

> Nosso projeto utilizará **dados de questionários diagnósticos estruturados de Segurança da Informação** para compreender/prever **o nível de maturidade e os gargalos de conformidade cibernética**, apoiando **gestores de Pequenas e Médias Empresas (PMEs)** na decisão de **priorizar investimentos defensivos e mitigar riscos operacionais**.

**Versão da equipe:**

Nosso projeto utilizará dados de questionários diagnósticos estruturados de Segurança da Informação para compreender o nível de maturidade e os gargalos de conformidade cibernética, apoiando gestores de Pequenas e Médias Empresas (PMEs) na decisão de priorizar investimentos defensivos e mitigar riscos operacionais.

## 3. Contexto e definição do problema

### 3.1 Contexto

Descreva a situação atual, o ambiente em que o problema ocorre e as evidências iniciais que demonstram sua relevância.

- Onde o problema ocorre? No ambiente corporativo e operacional de Pequenas e Médias Empresas (PMEs).
- Quem é afetado? Gestores, proprietários, colaboradores e clientes de PMEs cujos dados estão expostos a incidentes digitais.
- Quais sinais, dados ou relatos indicam sua existência? O relatório IBM Security (2024) indica custo médio de US$ 4,88 milhões por violação de dados. PMEs frequentemente utilizam softwares desatualizados, senhas fracas, não possuem rotinas de backup testadas e não capacitam colaboradores contra engenharia social.
- Por que é importante investigá-lo agora? A crescente dependência tecnológica e exigências regulatórias (como a LGPD) tornam a segurança um fator estratégico para a continuidade do negócio, mas diagnósticos tradicionais de auditoria são financeiramente inviáveis para PMEs.

**Preenchimento:**

Com o avanço tecnológico, dados pessoais e corporativos estão concentrados em ambientes digitais, aumentando a exposição a ameaças cibernéticas. O relatório da IBM Security (2024) aponta que o custo médio de uma violação atinge US$ 4,88 milhões. PMEs enfrentam barreiras para contratar auditorias tradicionais complexas, resultando em vulnerabilidade a ataques e falhas de conformidade. Investigar isso agora é crucial para permitir diagnósticos acessíveis e fortalecer a proteção de dados no cenário empresarial de menor porte.

### 3.2 Problema central

Formule o problema de maneira específica, sem antecipar uma solução.

> **Modelo:** [Público/organização] enfrenta [problema observável] no contexto de [situação], produzindo [consequência ou impacto].

**Problema definido:**

Pequenas e médias empresas (PMEs) enfrentam a ausência de métodos acessíveis e quantitativos de diagnóstico de Segurança da Informação no contexto de rotinas operacionais com recursos limitados, produzindo alta vulnerabilidade a ataques cibernéticos, perda de dados e insegurança na tomada de decisão estratégica.

### 3.3 Evidências iniciais

| Evidência | Fonte | O que ela indica? | Confiabilidade / limitação |
|---|---|---|---|
| 1. Custo médio global de violação de dados de US$ 4,88 milhões | IBM Security Cost of a Data Breach Report (2024) | O impacto financeiro e operacional de incidentes cibernéticos é crítico e crescente. | Alta confiabilidade. Limitação: reflete médias globais, incluindo grandes corporações. |
| 2. PMEs são alvos frequentes de ransomware e engenharia social | Relatórios Kaspersky / NIST (2022/2018) | Falta de capacitação e controles técnicos em PMEs abre margem para invasões fáceis. | Alta confiabilidade. Dados consolidados de inteligência de ameaças. |
| 3. Diretrizes de conformidade e controles essenciais de SI | Normas ABNT NBR ISO/IEC 27001, 27002 e NIST Framework | Definem os requisitos mínimos de gestão de riscos e controles operacionais de segurança. | Padrão ouro internacional. Limitação: normas são complexas e requerem adaptação para PMEs. |

## 4. Público-alvo e partes interessadas

### 4.1 Público-alvo principal

| Aspecto | Descrição |
|---|---|
| Quem são os usuários ou beneficiários? | Gestores de TI, proprietários de PMEs, consultores de segurança e diretores operacionais. |
| Quais necessidades possuem? | Identificar falhas de segurança de forma rápida, barata e clara, sem termos técnicos excessivamente herméticos. |
| Como são afetados pelo problema? | Sofrem paradas operacionais, vazamento de dados, prejuízos financeiros e sanções legais devido a lacunas não mapeadas. |
| Que decisão ou ação poderão tomar com os resultados? | Definir plano de ação para correção de falhas, aprovar orçamento de TI, implementar treinos e atualizar sistemas prioritários. |

### 4.2 Partes interessadas

| Parte interessada | Interesse no projeto | Influência | Forma de envolvimento |
|---|---|---|---|
| Gestores de PMEs | Avaliar e blindar sua infraestrutura contra perdas de dados | Alta | Respondentes do questionário e tomadores de decisão |
| Prof. Me. Gleidson Porto Batista | Validação metodológica, técnica e acadêmica do TCC | Alta | Orientação, revisão de entregáveis e avaliação bancária |
| Equipe de TI Interna / Operadores | Executar as melhorias técnicas recomendadas | Média | Aplicação de correções técnicas (backup, acessos, atualizações) |

## 5. Objetivos do projeto

### 5.1 Objetivo geral

Escreva um objetivo que indique o que será analisado, para qual finalidade e em qual contexto. Inicie com um verbo no infinitivo.

**Objetivo geral:**

Desenvolver um modelo de avaliação e diagnóstico quantitativo de Segurança da Informação fundamentado em questionários estruturados, para mensurar o nível de conformidade (score) e enquadrar o risco cibernético de pequenas e médias empresas, apoiando a tomada de decisões preventivas.

### 5.2 Objetivos específicos

Defina de três a cinco objetivos mensuráveis e compatíveis com o prazo do projeto.

| Nº | Objetivo específico | Evidência de conclusão |
|---:|---|---|
| 1 | Mapear e estruturar o instrumento de coleta em 5 dimensões (Controle de Acessos, Autenticação, Atualizações, Backup, Conscientização) com base nas normas ISO 27001/NIST. | Questionário de avaliação técnica formalizado em banco de dados. |
| 2 | Modelar a atribuição de pesos e o algoritmo de cálculo para geração do Índice de Conformidade (Score de 0 a 100). | Scripts de pipeline de dados e documentação da fórmula do Score. |
| 3 | Desenvolver a matriz de classificação do Nível de Risco (Baixo, Médio, Alto, Crítico) com base na pontuação atingida. | Tabela parametrizada e regras de decisão integradas. |
| 4 | Construir um painel analítico / relatório interativo para visualização clara das defesas e gargalos da empresa. | Dashboard interativo e modelo de Relatório de Segurança gerado. |

### 5.3 Verificação dos objetivos

Marque após revisar:

- [x] São específicos e escritos com clareza.
- [x] Podem ser verificados por meio de entregáveis ou métricas.
- [x] São viáveis com os dados, recursos e tempo disponíveis.
- [x] Estão diretamente relacionados ao problema central.
- [x] Consideram os usuários e a decisão que será apoiada.

## 6. Perguntas de negócio

As perguntas de negócio orientam a coleta, a análise e a comunicação dos resultados. Evite perguntas que possam ser respondidas apenas com “sim” ou “não”.

| Nº | Pergunta de negócio | Decisão apoiada | Dados necessários | Análise ou indicador possível |
|---:|---|---|---|---|
| 1 | Qual é o Índice Global de Conformidade em Segurança da Informação da empresa avaliada? | Definir se a empresa está apta em termos de maturidade cibernética. | Respostas pontuadas de todas as questões do diagnóstico. | Score Global de Conformidade (0 a 100). |
| 2 | Qual dimensão técnica apresenta o maior gargalo de vulnerabilidade (ex: Backup, Acessos, Conscientização)? | Priorizar a alocação de investimentos imediatos de TI em curto prazo. | Respostas categorizadas pelas 5 dimensões avaliadas. | Média de conformidade por dimensão (Gráfico de Radar). |
| 3 | Em qual faixa de risco a organização se enquadra atualmente? | Avaliar necessidade de contratação urgente de consultoria ou plano de contingência. | Score final calculado vs. limites da matriz de risco. | Matriz/Gauge de Classificação de Risco (Baixo, Médio, Alto, Crítico). |
| 4 | O fator humano (conscientização) apresenta aderência inferior às defesas técnicas (software/backup)? | Decidir entre investir em ferramentas/softwares ou em treinamentos de equipes. | Comparativo da dimensão "Conscientização" vs. demais dimensões. | Análise de Disparidade Humano vs. Técnico. |

## 7. Hipóteses iniciais

Registre suposições que serão investigadas, sem apresentá-las como conclusões.

| Hipótese | Como poderá ser testada? | Resultado que a refutaria? |
|---|---|---|
| H1. A dimensão de "Conscientização de Usuários" apresenta pontuação média significativamente menor que as dimensões de infraestrutura técnica. | Comparando o score médio obtido no eixo de conscientização com o score dos eixos técnicos (Backup/Atualizações). | A média da dimensão de Conscientização ser igual ou superior à média das defesas técnicas nas empresas analisadas. |
| H2. A maioria das PMEs atinge enquadramento nas faixas de Risco "Alto" ou "Crítico" no diagnóstico inicial. | Avaliando a distribuição percentual das empresas avaliadas nas categorias de risco. | Mais de 50% das PMEs avaliadas obterem score suficiente para enquadramento em Risco "Baixo" ou "Médio". |
| H3. A ausência de processos formais de revogação imediata de acesso na saída de funcionários é um dos principais fatores de queda do score de acesso. | Calculando a correlação/peso da questão de desligamento de colaboradores no score total da dimensão Acessos. | A variável de revogação pós-desligamento não demonstrar impacto relevante no score da dimensão. |

## 8. Dados necessários e viabilidade

| Conjunto ou fonte de dados | Variáveis principais | Formato | Acesso / responsável | Qualidade esperada |
|---|---|---|---|---|
| Questionário Diagnóstico de SI | Respostas sobre acessos, senhas, backups, patches, treinos, política de SI | Estruturado (JSON / CSV / SQL) | Sintike Barreira (Coleta via formulário/banco central) | Alta consistência, sem dados nulos nas perguntas obrigatórias. |
| Tabela de Pesos e Parâmetros | ID da questão, Peso da pergunta, Pontuação da alternativa, Faixa de Risco | CSV / Tabela relacional | Sintike Barreira (Modelagem de Dados) | Padronizado conforme ISO/IEC 27001. |

### 8.1 Avaliação inicial dos dados

- **Disponibilidade:** Dados primários obtidos mediante aplicação do questionário diagnóstico estruturado com gestores/empresas.
- **Volume e período coberto:** Coleta pontual por avaliação diagnóstica (cross-sectional), cobrindo a rotina atual da empresa.
- **Dados ausentes, duplicados ou inconsistentes previstos:** Validações de entrada no formulário para evitar campos em branco e inconsistências de preenchimento.
- **Necessidade de integração entre fontes:** Integração entre a base de respostas brutas e a tabela de ponderação/pesos para cálculo do score.
- **Restrições legais, contratuais ou institucionais:** Termo de Consentimento Livre e Esclarecido (TCLE) para garantir sigilo das informações institucionais coletadas.

### 8.2 Privacidade, ética e segurança

- [x] A equipe verificou se há dados pessoais ou sensíveis.
- [x] A coleta e o uso dos dados possuem finalidade legítima e explícita.
- [x] O acesso será limitado às pessoas autorizadas.
- [x] Dados pessoais serão minimizados, anonimizados ou pseudonimizados quando necessário.
- [x] Possíveis vieses e impactos sobre grupos serão analisados.
- [x] A divulgação dos resultados evitará reidentificação ou exposição indevida.

**Cuidados específicos deste projeto:**

As respostas das empresas serão estritamente anonimizadas (ex: Empresa A, Empresa B). Não serão expostos endereços IP, nomes de colaboradores ou detalhes vulneráveis de infraestrutura que possam comprometer a segurança real dos participantes.

## 9. Escopo do projeto

| Dentro do escopo | Fora do escopo |
|---|---|
| Estruturação das 5 dimensões e questões objetivas. | Execução de testes de invasão reais (PenTest) ou varredura técnica de rede. |
| Modelagem da base de dados e pipeline de cálculo do Score. | Correção automática ou implementação direta dos sistemas na empresa. |
| Classificação das faixas de risco (Baixo, Médio, Alto, Crítico). | Auditoria presencial física ou perícia forense digital. |
| Geração de dashboard e relatório de recomendações preventivas. | Desenvolvimento de software comercial completo (SaaS). |

**Restrições conhecidas:** tempo, acesso a dados, ferramentas, infraestrutura, conhecimento técnico ou normas.

Tempo delimitado para o ciclo acadêmico da unidade/TCC; acesso dependente da adesão voluntária de gestores para resposta aos questionários.

## 10. Resultados e entregáveis previstos

| Entregável | Descrição | Formato | Responsável | Critério de aceite |
|---|---|---|---|---|
| Base tratada | Dados das respostas tratadas e pontuadas conforme pesos das normas. | CSV / SQL / Pandas DF | Sintike Barreira | 100% dos registros validados e sem divergência no cálculo. |
| Análise exploratória | Análise descritiva dos scores por dimensão e distribuição das empresas. | Notebook Python / Relatório EDA | Sintike Barreira | Validação das hipóteses H1, H2 e H3 com gráficos claros. |
| Visualizações / painel | Dashboard interativo para visualização do diagnósticos e gráficos de radar/barras. | Power BI / Streamlit / Dash | Sintike Barreira | Atualização dinâmica dos gráficos com base nos dados de entrada. |
| Relatório ou apresentação | Documento consolidado contendo a metodologia, cálculo, conclusões e recomendações. | PDF / Documento final | Sintike Barreira | Aprovação pela banca/orientador segundo normas ABNT. |

## 11. Critérios de sucesso

Defina como a equipe saberá se o projeto alcançou seus objetivos.

| Critério | Indicador ou evidência | Meta | Forma de verificação |
|---|---|---|---|
| Relevância para o problema | Capacidade do modelo em discriminar níveis de maturidade em PMEs. | Mapeamento claro de pelo menos 3 gargalos principais por diagnóstico. | Feedback e validação com orientação/gestores. |
| Qualidade dos dados | Taxa de integridade da base tratada e respostas completas. | 100% de preenchimento sem dados faltantes cruciais. | Execução de scripts de validação e limpeza. |
| Qualidade da análise | Exatidão e reprodutibilidade da fórmula do Score e classificação. | 0% de divergência nos cálculos de pontuação. | Testes unitários com casos de teste sintéticos. |
| Utilidade para o público-alvo | Clareza no Relatório de Segurança gerado ao final. | Orientação clara de tomada de decisão para leigos em TI. | Avaliação qualitativa do formato do relatório. |
| Comunicação dos resultados | Compreensão e usabilidade do dashboard e gráficos. | Apresentação fluida das 5 dimensões e faixas de risco. | Apresentação dos entregáveis na disciplina. |

## 12. Plano inicial de trabalho

| Etapa | Atividades principais | Responsável(is) | Prazo | Dependências |
|---|---|---|---|---|
| 1. Definição | Alinhamento do escopo, revisão bibliográfica (ISO/NIST) e formalização da proposta. | Sintike Barreira | Semana 1 | Aprovado pelo orientador (Prof. Gleidson Porto) |
| 2. Obtenção dos dados | Aplicação do formulário de diagnóstico e coleta de respostas de PMEs. | Sintike Barreira | Semanas 2-3 | Formulário estruturado |
| 3. Preparação dos dados | Limpeza de dados, anonimização e cálculo do Score por dimensão. | Sintike Barreira | Semana 4 | Coleta concluída |
| 4. Análise / modelagem | Avaliação das hipóteses, cruzamento das dimensões e classificação do nível de risco. | Sintike Barreira | Semanas 5-6 | Base tratada |
| 5. Validação | Validação estatística, ajuste das ponderações de risco e testes com amostras. | Sintike Barreira | Semana 7 | Resultados da modelagem |
| 6. Comunicação | Finalização do dashboard, escrita do relatório/artigo e submissão. | Sintike Barreira | Semana 8 | Validação concluída |

## 13. Riscos do projeto

| Risco | Probabilidade | Impacto | Estratégia de resposta | Responsável |
|---|---|---|---|---|
| Low rate de respostas aos questionários por parte das PMEs | Média | Alto | Utilizar amostras sintéticas validadas para testes e expandir contatos via redes acadêmicas. | Sintike Barreira |
| Recusa de empresas por receio de exposição de vulnerabilidades | Média | Médio | Reforçar o compromisso de anonimização e apresentar o Termo de Sigilo (TCLE). | Sintike Barreira |
| Atrasos no pipeline de tratamento de dados e montagem do painel | Baixa | Médio | Utilizar bibliotecas padrão em Python (Pandas/Streamlit) e modelos reutilizáveis. | Sintike Barreira |

## 14. Organização da equipe

| Integrante | Papel principal | Responsabilidades | Apoio necessário |
|---|---|---|---|
| Sintike Barreira da Silva | Líder do Projeto & Analista de Dados | Planejamento, elaboração do questionário, coleta de dados, cálculo de score e redação do entregável. | Orientação acadêmica e validação de parâmetros (Prof. Gleidson). |

## 15. Validação da definição do projeto

Antes da entrega, confirme:

- [x] O problema é real, relevante e delimitado.
- [x] O público-alvo e as partes interessadas estão identificados.
- [x] O objetivo geral e os objetivos específicos são coerentes.
- [x] As perguntas de negócio orientam decisões concretas.
- [x] Há dados potencialmente disponíveis para responder às perguntas.
- [x] O escopo é compatível com o prazo e os recursos.
- [x] Os critérios de sucesso são mensuráveis.
- [x] Riscos, privacidade, ética e segurança foram considerados.
- [x] Funções e responsabilidades foram distribuídas.

## 16. Aprovação e registro de ajustes

| Responsável | Validação / observação | Data |
|---|---|---|
| Representante da equipe | Sintike Barreira da Silva — Documento verificado e pronto para entrega. | 23/09/2026 |
| Professor(a) / orientador(a) | Prof. Me. Gleidson Porto Batista — Aguardando validação final da Unidade III. | --/--/2026 |

### Ajustes solicitados após a apresentação inicial

*(Espaço reservado para inclusão das considerações do orientador após a avaliação do repositório no GitHub)*.
