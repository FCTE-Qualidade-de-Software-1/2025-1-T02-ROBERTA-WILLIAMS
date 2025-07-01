# 📑 Avaliação de Qualidade e Gestão do Projeto AgroMart

## 1. Visão Geral do Projeto

O AgroMart é um sistema que apoia as operações de uma agropecuária multicanal, abrangendo vendas de rações, medicamentos veterinários, sementes, adubos e produtos de higiene animal. Diante do alto volume de produtos e do atendimento diversificado ao cliente, **avaliar e aprimorar a qualidade do sistema** torna-se essencial para garantir eficiência operacional, satisfação do cliente e escalabilidade do negócio.

---

## 2. Fase 1 – Propósito da Avaliação

### 2.1 Objetivo Geral
Avaliar a qualidade do AgroMart segundo a norma **ISO/IEC 25010**, de modo a:  
• Identificar pontos fortes e fracos do sistema;  
• Priorizar ações de melhoria;  
• Sustentar o crescimento do negócio com processos confiáveis.

### 2.2 Justificativa
• **Fluidez de vendas**: reduzir tempos e cliques em balcão.  
• **Confiabilidade de estoque**: mitigar inconsistências que geram retrabalho.  
• **Satisfação do cliente**: atendimento ágil e informação clara.  
• **Suporte ao crescimento**: manter qualidade com expansão de catálogo e filiais.

### 2.3 Stakeholders
| Categoria | Exemplos | Interesse Principal |
|-----------|----------|---------------------|
| Usuários Finais | Atendentes, vendedores | Velocidade de registro de vendas |
| Clientes | Agricultores, pecuaristas | Agilidade e precisão de informação |
| Equipe Administrativa | Gerentes, financeiro | Controle de estoque/receita |
| Equipe Técnica | Desenvolvedores, suporte | Facilidade de manutenção |

### 2.4 Características de Qualidade Focadas
Com base na ISO/IEC 25010, o time definiu inicialmente cinco características (Usabilidade, Desempenho, Confiabilidade, Manutenibilidade, Portabilidade). **Posteriormente, o escopo foi refinado para concentrar-se unicamente na característica de Usabilidade**, considerada crítica para acelerar vendas e reduzir curva de aprendizado.

### 2.5 Resultados Esperados
• Diagnóstico completo de usabilidade;  
• Métricas que sustentem decisões de UI/UX;  
• Plano de ação priorizado para correções;  
• Melhoria perceptível na satisfação dos usuários-chave.

---

## 3. Fase 2 – Especificar a Avaliação (Foco em Usabilidade)

### 3.1 Subcaracterísticas de Usabilidade Selecionadas
| Subcaracterística | Definição ISO/IEC 25010 | Contexto AgroMart | Prioridade |
|-------------------|-------------------------|-------------------|-----------|
| Reconhecimento de Adequação | Usuário percebe que o sistema atende às necessidades | Vendedores encontram funções de venda rapidamente | Alta |
| Capacidade de Aprendizado | Facilidade de aprender a usar | Onboarding rápido de novos colaboradores | **Muito Alta** |
| Operabilidade | Facilidade de executar tarefas | Registro de vendas sem atrito | **Muito Alta** |
| Proteção ao Erro | Sistema previne/detecta erros | Evitar vendas duplicadas | Alta |
| Estética da Interface | Interface agradável | Layout motivador para uso diário | Média |
| Acessibilidade | Uso por pessoas com limitações | Inclusão de diversos perfis | Média |

#### 3.1.1 Justificativa da Priorização
1. **Capacidade de Aprendizado** e **Operabilidade**: impactam diretamente as margens de lucro e produtividade.  
2. **Reconhecimento de Adequação** e **Proteção ao Erro**: afetam percepção de utilidade e confiabilidade.  
3. **Estética** e **Acessibilidade**: contribuem para satisfação e inclusão.

### 3.2 Métricas e Critérios de Aceitação
| Subcaracterística | Métrica | Unidade | Mínimo | Desejado |
|-------------------|---------|---------|--------|----------|
| Reconhecimento de Adequação | Taxa de reconhecimento de funcionalidade | % | ≥ 80 | ≥ 95 |
|  | Tempo p/ identificar função | s | ≤ 60 | ≤ 30 |
| Capacidade de Aprendizado | Tempo de aprendizado inicial | min | ≤ 30 | ≤ 15 |
|  | Taxa de retenção de conhecimento | % | ≥ 70 | ≥ 90 |
|  | Curva de aprendizado | tarefas/dia | ≥ 5 | ≥ 10 |
| Operabilidade | Tempo de execução de tarefa | s | ≤ 120 | ≤ 60 |
|  | Taxa de conclusão de tarefa | % | ≥ 80 | ≥ 95 |
|  | Eficiência de navegação | cliques | ≤ 8 | ≤ 5 |
| Proteção ao Erro | Taxa de erros do usuário | % | ≤ 10 | ≤ 5 |
|  | Taxa de recuperação de erros | % | ≥ 80 | ≥ 95 |
| Estética da Interface | Satisfação visual | 1-5 | ≥ 3 | ≥ 4 |
|  | Atratividade percebida | 1-5 | ≥ 3 | ≥ 4 |
| Acessibilidade | Conformidade WCAG 2.1 AA | % | ≥ 85 | ≥ 95 |
|  | Suporte a tecnologias assistivas | Sim/Não | Sim | Sim |

### 3.3 Técnicas de Avaliação
1. **System Usability Scale (SUS)** – questionário pós-tarefa; meta SUS ≥ 20 (aceitável) / ≥ 50 (excelente).  
2. **Testes de Usabilidade Moderados** – 5-10 atendentes, cenários reais, coleta de tempos e erros.  
3. **Avaliação Heurística** – 3-5 membros aplicam heurísticas Nielsen.  
4. **Teste de Acessibilidade WCAG** – ferramentas Axe/Wave + inspeção manual.  
5. **Card Sorting & Tree Testing** – validação da arquitetura de informação.  
6. **Análise de Logs** – monitoramento de cliques e caminhos durante 2 semanas.  
7. **Eye Tracking** (opcional) – identificar focos de atenção em telas críticas.

### 3.4 Instrumentos de Coleta
| # | Instrumento | Objetivo | Formato |
|---|-------------|----------|---------|
| 1 | Questionário SUS | Usabilidade percebida | Formulário online |
| 2 | Roteiro de Teste | Medir desempenho real | Script de 8 cenários |
| 3 | Checklist Heurístico | Violação de design | Planilha severidade |
| 4 | Formulário Observação | Registrar erros | Planilha estruturada |
| 5 | Relatório Acessibilidade | WCAG AA | Export Axe/Wave + notas |
| 6 | Dashboard Logs | Métricas de cliques | Grafana |

### 3.5 Procedimento de Avaliação
1. **Preparação**: ambiente de teste com base de produtos fictícia; recrutamento de 12 usuários (6 experientes, 6 novos).  
2. **Execução de Sessões Moderadas**: coleta de tempo, cliques, erros; aplicação do SUS.  
3. **Avaliação Heurística**: especialistas registram problemas e severidade.  
4. **Acessibilidade**: varredura automática + auditoria manual de 10 telas.  
5. **Card Sorting**: sessão remota com 15 usuários para validar categorias.  
6. **Logs em Produção**: análise de duas semanas de uso real.  
7. **Síntese**: cálculo do SUS médio; comparação de métricas com metas; painel de calor de prioridades.

### 3.6 Cronograma da Fase 2 (Usabilidade)
| Atividade | Duração | Responsáveis |
|-----------|---------|--------------|
| Definição final de métricas | 2 dias | membros |
| Criação do questionário SUS | 3 dias | membros|
| Desenvolvimento de roteiros/scripts | 5 dias | membros |
| Preparação de ambiente | 2 dias | membros |
| Configuração de dashboards | 3 dias | membros|
| Validação com stakeholders | 1 dia | membros |
**Total**: **16 dias úteis**

### 3.7 Resultados Esperados
• SUS ≥ 50 (excelente);  
• Tempo médio de tarefa ≤ 60 s;  
• Taxa de erros ≤ 5 %;  
• Conformidade WCAG AA ≥ 95 %;  
• Relatório priorizado de problemas de interface.

---

## 4. Gestão do Projeto – PSM/CID

### 4.1 Calendário do Projeto
• Cronograma global baseado em Gantt no Trello, cobrindo Fases 1-4 e gestão.  
• Marcos principais: conclusão Fase 2 (D+30), execução de testes (D+50), relatório final (D+70).

### 4.2 Processo Adotado
O grupo utiliza um **processo incremental com Sprints de 2 semanas**:
1. **Sprint 0**: setup ambiente, definição métricas (concluído).  
2. **Sprint 1**: criação de instrumentos; revisão stakeholders.  
3. **Sprint 2**: execução testes piloto; ajustes.  
4. **Sprint 3**: coleta oficial; análise e relatório.

### 4.3 Performance do Processo
• Até o momento, cronograma cumprido em 90 %.  
• Ajuste realizado: extensão de Sprint 1 em +2 dias para refinar questionário.  
• Pontos positivos: comunicação ágil via Slack; pontos negativos: disponibilidade limitada de usuários.

### 4.4 Custo e Recursos
| Recurso | Estimativa | Observação |
|---------|-----------|------------|
| Horas Pessoa 1 | 40 h | Planejamento Fase 1 |
| Horas Pessoa 2 | 80 h | Liderança Fase 2 |
| Horas Pessoa 3 | 60 h | Design instrumentos |
| Horas Pessoa 4 | 50 h | Execução testes |
| Horas Pessoa 5 | 30 h | Gestão projeto |
| Ferramentas | R$ 1.500 | JMeter, SonarQube, Axe licenças |
| Infraestrutura | R$ 800 | Servidor teste + backups |
| Total | **R$ 2.300 + 260 h** | Custos fictícios |

### 4.5 Divisão de Responsabilidades
| Integrante | Responsabilidade Principal |
|------------|---------------------------|
| Pessoa 1 | Fase 1 – Propósito |
| Pessoa 2 | Fase 2 – Usabilidade |
| Pessoa 3 | Fase 3 – Projetar |
| Pessoa 4 | Fase 4 – Executar |
| Pessoa 5 | Gestão PSM/CID |

---

## 5. Próximos Passos
1. **Fase 3 – Projetar a Avaliação**: transformar instrumentos em roteiro detalhado de execução.  
2. **Fase 4 – Executar**: aplicar testes, coletar dados e comparar com critérios.  
3. **Retrospectiva de Processo**: revisar desempenho de Sprints e atualizar estimativas.
