# Desafio-Vibe-Coding_App-Financas-Pessoais  
Desafio implementado para teste de Vibe Coding

---
## 💡 Objetivo

Criar o **conceito de um aplicativo de Finanças Pessoais** utilizando o método **Vibe Coding**, que consiste em guiar a IA com prompts claros e bem estruturados. O foco não é escrever código, mas sim **usar a IA como parceira criativa** para transformar ideias em soluções simuladas.

---

## ✨ O que é Vibe Coding

**Vibe Coding** é uma abordagem de programação que combina **criatividade**, **colaboração** e **diversão** no processo de desenvolvimento de software.

## Conceitos principais:

**1. Vibe** = Energia/ambiente positivo durante o coding
**2. Coding** = Programação em si

## Características:
- **Trabalho em equipe** com foco em conexão e colaboração
- **Ambiente descontraído** e criativo
- **Aprendizado mútuo** entre desenvolvedores
- **Foco na experiência** e não apenas no resultado final
- **Integração de diversidade** e diferentes estilos de programação

## Objetivo:
Tornar o processo de programação mais **atraente**, **produtivo** e **sustentável** ao criar uma cultura de trabalho colaborativa e positiva, onde o desenvolvedor se sinta parte de uma comunidade.

É uma abordagem que valoriza o **bem-estar** e **o ambiente de trabalho** no desenvolvimento de software.

---

## 🎯 Contexto do Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada manual e tornam a criação de orçamentos algo tedioso.  

Solução: Um app que permita **controlar as finanças por meio de conversas simples**, com agentes de IA capazes de criar **planos de economia personalizados e automatizados**.

## 🛠 Etapas de Entrega

### 1. Definição do PRD (Product Requirements Document)
- Criar um PRD simplificado que descreva:
  - Contexto do aplicativo  
  - Problema a ser resolvido  
  - Público-alvo  
  - Funcionalidades principais  
  - Entregável esperado da IA
---
### Evidência PRD inicial:
```txt
# Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas com o usuário.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem formulários manuais ou planilhas complexas.

# Problema
Muitas pessoas desistem de controlar seus gastos porque os apps atuais exigem muita entrada manual e pouca personalização.  
Quero resolver isso com uma experiência de conversa e recomendações automáticas de economia.

# Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicação, principalmente iniciantes.

# Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural.  
2. Classificar automaticamente as transações.  
3. Definir e acompanhar metas financeiras.  
4. Receber dicas de economia do “Agente Financeiro”.  
5. Visualizar relatórios simples e personalizados.

# Entregável da IA
Gerar um plano de MVP com as principais telas, recursos necessários e um esboço de validação inicial.  
Usar tom educativo e linguagem acessível, em português.
```
---

### 2. Refinamento do Prompt
- Revisão do PRD utilizando o **Copilot** para otimizar clareza e intenção.

---

### 📸 Evidência ajuste do prompt PRD
![Imagem 1](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/1_Ajuste_prompt.png)  

---

### 📸 Evidência ajuste do prompt PRD
![Imagem 2](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/2_Ajuste_prompt.png)  

---
### Documento de MVP pronto para Lovable  
**Aplicativo**: Organização de Finanças Pessoais por Conversa  
**Tom**: educativo, acessível, em português  
**Objetivo**: entregar um MVP conversacional que permita registrar gastos, acompanhar metas e receber recomendações práticas com mínima entrada manual.

---

### 1 Visão Geral do MVP
**Problema que resolvemos**: reduzir a fricção de entrada manual e aumentar a personalização para iniciantes em controle financeiro.  
**Proposta de valor**: permitir que o usuário gerencie finanças por meio de conversas naturais com um Agente Financeiro que registra, classifica, sugere e educa.  
**Público alvo**: iniciantes em finanças pessoais; jovens adultos; pessoas com baixa familiaridade com planilhas; usuários que preferem interação por chat.

---

### 2 Escopo do MVP Funcional e Telas Principais
A tabela abaixo lista as telas essenciais, suas funções e critérios mínimos de aceitação.

| **Tela** | **Função principal** | **Critério mínimo de aceitação** |
|---|---:|---|
| **Chat Principal** | Registrar gastos e interagir com o Agente Financeiro | Registrar transação em linguagem natural; confirmar categoria sugerida; editar antes de salvar |
| **Resumo Diário Semanal** | Mostrar saldo, gastos recentes e alertas simples | Visualização de totais por dia e por semana; destaque de gastos acima da média |
| **Metas** | Criar e acompanhar metas financeiras simples | Criar meta com valor e prazo; progresso atualizado automaticamente |
| **Relatórios Simples** | Visualizar gastos por categoria e evolução | Gráfico de pizza por categoria; gráfico de linha de saldo mensal |
| **Dicas e Educação** | Exibir dicas personalizadas do Agente Financeiro | Lista de 3 dicas acionáveis por semana; explicação curta e educativa |
| **Configurações e Privacidade** | Preferências, exportação limitada e segurança | Opções de backup local; explicação de tratamento de dados; logout seguro |

---

### 3 Experiência Conversacional e Fluxos Principais
#### 3.1 Princípios de design conversacional
- **Entrada mínima**: aceitar frases livres como "almocei R$ 25 no centro".  
- **Confirmação rápida**: o Agente sugere categoria e valor e pede confirmação em até duas trocas.  
- **Tom educativo**: explicações curtas e exemplos práticos quando o usuário demonstra dúvida.  
- **Ações sugeridas**: sempre oferecer um próximo passo claro (ex.: criar meta, revisar relatório).

#### 3.2 Fluxos essenciais
- **Registrar gasto**  
  1. Usuário: "Gastei 45 no mercado"  
  2. Agente: "Anotei R$45; categoria sugerida Supermercado. Confirmo?"  
  3. Usuário confirma ou corrige; transação salva com timestamp.  
- **Criar meta**  
  1. Usuário: "Quero juntar R$1.200 em 6 meses"  
  2. Agente: "Para atingir R$1.200 em 6 meses precisa poupar R$200/mês. Criar meta?"  
  3. Usuário confirma; meta aparece na tela Metas com progresso.  
- **Receber dica**  
  1. Agente envia dica semanal baseada em padrão de gastos.  
  2. Usuário pode pedir "me explique" para receber contexto educativo.

#### 3.3 Exemplos de microcopy educativo
- **Confirmação de gasto**: "Entendi — R$45 em Supermercado. Quer adicionar nota?"  
- **Ao criar meta**: "Ótimo objetivo. Vamos dividir em metas mensais para facilitar."  
- **Ao economizar**: "Parabéns — você economizou 10% a mais que a média do mês passado."

---

### 4 Requisitos Técnicos e Arquitetura Mínima
#### 4.1 Componentes essenciais
| **Componente** | **Descrição** |
|---|---:|
| **NLP** | Interpretar entradas em linguagem natural; extrair valor, categoria, data e nota |
| **Classificador de transações** | Modelo ML para mapear texto em categorias padrão |
| **Motor de regras e recomendações** | Regras simples para metas, alertas e dicas personalizadas |
| **Banco de dados** | Armazenamento seguro de transações e metas; esquema simples por usuário |
| **Autenticação** | Login básico com e-mail ou número de telefone |
| **Criptografia** | Dados sensíveis criptografados em trânsito e em repouso |

#### 4.2 Pilha tecnológica sugerida
- **Frontend mobile**: React Native ou Flutter para entrega rápida mobile-first.  
- **Backend**: Node.js ou Python Flask com API REST.  
- **NLP**: serviço de NLP hospedado (ex.: modelo leve de LLM ou API de NLP) para extração de entidades.  
- **ML**: modelo de classificação treinado com regras e dados sintéticos; pipeline para re-treinamento.  
- **DB**: PostgreSQL ou Firebase para MVP.  
- **Infra**: hospedagem em nuvem com TLS e backups automáticos.

#### 4.3 Modelo de dados mínimo
- **Usuário**: id; nome; email; preferências de idioma; consentimento de dados.  
- **Transação**: id; user_id; valor; categoria; data; nota; origem (manual/chat).  
- **Meta**: id; user_id; objetivo_valor; prazo; contribuição_mensal; progresso.  
- **Interação**: id; user_id; texto_entrada; interpretação_nlp; ação_resultante.

#### 4.4 Segurança e privacidade
- **Consentimento explícito** no onboarding para uso de dados.  
- **Criptografia** TLS para transporte e AES para armazenamento.  
- **Política de retenção** clara e opção de exclusão de conta.  
- **Logs** anonimizados para melhoria do modelo.

---

### 5 Plano de Validação Inicial e Métricas de Sucesso
#### 5.1 Testes e validação
- **Piloto fechado** com 20–30 usuários representativos por 4 semanas.  
- **Tarefas de validação**: registrar 10 transações na primeira semana; criar 1 meta; revisar relatório semanal.  
- **Coleta de feedback**: questionário curto in-app e entrevistas qualitativas com 8 usuários.

#### 5.2 Métricas chave
| **Métrica** | **Meta MVP** |
|---|---:|
| **Taxa de adoção do registro via chat** | ≥ 70% das transações registradas via chat |
| **Taxa de confirmação automática de categoria** | ≥ 80% acerto inicial do classificador |
| **Retenção 7 dias** | ≥ 40% |
| **Engajamento com metas** | ≥ 30% dos usuários criam ao menos 1 meta |
| **Satisfação** | NPS qualitativo médio ≥ 6/10 nas entrevistas |

#### 5.3 Critérios de aceitação do MVP
- Usuário consegue registrar gasto em até 3 trocas de mensagens.  
- Classificador sugere categoria correta em ≥ 80% dos casos no piloto.  
- Relatórios mostram dados coerentes e compreensíveis para o usuário.  
- Dicas semanais são acionáveis e entendidas por pelo menos 70% dos testadores.

---

### 6 Roadmap de Entrega e Riscos
#### 6.1 Cronograma sugerido para 8 semanas
- **Semana 1**: Definição de requisitos detalhados e prototipagem de chat.  
- **Semana 2–3**: Implementação do chat e pipeline básico de NLP.  
- **Semana 4**: Implementação de metas e relatórios simples.  
- **Semana 5**: Integração do classificador e motor de recomendações.  
- **Semana 6**: Testes internos e ajustes de UX.  
- **Semana 7**: Piloto com 20–30 usuários.  
- **Semana 8**: Coleta de feedback, correções e definição de próximos passos.

#### 6.2 Riscos principais e mitigação
- **Classificação imprecisa**: mitigar com regras híbridas e revisão humana inicial.  
- **Baixa retenção**: mitigar com onboarding educativo e notificações suaves.  
- **Questões de privacidade**: mitigar com consentimento claro e criptografia desde o início.  
- **Sobrecarga de NLP**: mitigar com fallback de formulários simples quando a interpretação falhar.

---

### Entregáveis para Lovable
- **Protótipo navegável** das telas listadas.  
- **Documento técnico** com endpoints da API e modelo de dados.  
- **Conjunto de intents e exemplos de frases** para treinar o NLP (mínimo 200 exemplos).  
- **Plano de testes do piloto** com roteiro de entrevistas e questionário.  
- **Checklist de lançamento do MVP** com critérios de aceitação e métricas.

### 📸 Evidência lovable 01
![Imagem 3](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/3_Ajuste_prompt.png)  

---

### 📸 Evidência lovable 02
![Imagem 4](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/4_Ajuste_prompt.png)  

---

### 📸 Evidência lovable 03
![Imagem 5](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/5_Ajuste_prompt.png)  

---

### 📸 Evidência lovable 04
![Imagem 6](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/6_Ajuste_prompt.png)  

---

### 📸 Evidência lovable 05
![Imagem 7](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/7_Ajuste_prompt.png)  

---

### 📸 Evidência lovable 06
![Imagem 8](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/8_Ajuste_prompt.png)  

---

### 📸 Evidência lovable 07
![Imagem 9](https://github.com/FredOnBrasil/Desafio-Vibe-Coding_App-Financas-Pessoais/blob/main/Images/9_Ajuste_prompt.png)  

---

### Resumo das funcionalidades do aplicativo
Funcionalidade principal
Registro por conversa — registrar despesas e receitas usando linguagem natural no chat; confirmação rápida e edição antes de salvar.

Organização e classificação
Classificação automática — categorização instantânea das transações via NLP/ML; sugestão de categoria com opção de correção.

Etiquetas e notas — adicionar notas e tags para contexto e busca.

Metas e planejamento
Criação de metas — definir objetivo, prazo e contribuição mensal calculada automaticamente.

Acompanhamento de progresso — visualização do avanço e alertas quando estiver fora do plano.

Recomendações e educação
Agente Financeiro — dicas personalizadas de economia e micro‑aulas curtas; envio de 1–3 dicas acionáveis por semana.

Ações sugeridas — próximos passos contextuais (ex.: criar meta, rever categoria, reduzir gasto recorrente).

Relatórios e visualização
Relatórios simples — gráficos visuais (pizza por categoria; linha de saldo mensal) e resumo diário/semanal.

Painel resumido — saldo, gastos recentes e alertas de anomalia (gasto acima da média).

Engajamento e usabilidade
Onboarding educativo — tutorial curto e exemplos de frases para facilitar o primeiro uso.

Notificações suaves — lembretes e alertas não intrusivos para manter hábito.

Gamificação leve — conquistas e recompensas por metas atingidas (opcional para MVP).

Configurações e privacidade
Autenticação simples — login por e‑mail ou telefone.

Segurança de dados — criptografia em trânsito e em repouso; consentimento explícito no onboarding.

Opções de exportação e exclusão — backup local e exclusão de conta.

---
---

### 4. Reflexão sobre o processo:  
  - O que funcionou bem.
    o copilot foi bem na revisão apesar de ter sido necessária mais atenção aos detalhes de correção do prompt.
     
  - O que não funcionou como esperado.
    O lovable precisou de mais tempo para gerar as funcionalidades e apresentou algumas pequenas inconsistências.
    
  - O que foi aprendido sobre conversar com IAs.
    Elas estão evoluindo rápido e precisamos acompanhar ou nós seremos irrelevantes no processo de criação.



## 💬 Conclusão

O conhecimento é um processo de construção e aulas como essa resignificam o conceito de aprendizado pois enfatizam a necessidade de um processo constante de aperfeiçoamento.

---

Quer que eu já prepare um **modelo editável de PRD** dentro desse README para você preencher direto, como um template pronto?
