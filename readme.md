# ⚡ SPAE v2.0 — Simulador de Práticas Administrativas Empresariais

> **Plataforma web interativa de simulação empresarial em arquivo único (`index.html`), desenvolvida para a unidade SENAI São José dos Pinhais (PR) e aplicada ao curso de *Assistente de Processos Industriais Integrados* (Matriz APBG005701/02 — 600h).**

---

## 🎯 Sobre o Projeto

O **SPAE v2.0** é uma solução educacional desenvolvida sob a **Metodologia SENAI de Educação Profissional** (Aprendizagem Baseada em Projetos e Resolução de Situações-Problema). O sistema recria a operação de uma empresa/fábrica corporativa, onde os estudantes assumem papéis funcionais e vivenciam a interdependência real entre os setores.

O simulador funciona em **arquivo único (*Single File Application*) e opera 100% offline**, utilizando a API nativa `BroadcastChannel` para sincronizar os dados entre os computadores dos alunos na rede local ou em abas no mesmo navegador.

---

## ✨ Principais Funcionalidades

### 💼 1. Agência de RH & Onboarding de Alunos
* **Inscrição Flexível:** Acomoda turmas de qualquer tamanho (sem limite rígido de alunos).
* **Cadastro Completo:** Coleta de dados essenciais (*Nome Completo, Data de Nascimento, Celular/WhatsApp e E-mail*).
* **Quiz de Perfil:** Algoritmo que avalia aptidões em Liderança, Atenção a Processos e Mediação.
* **Mural de Oportunidades:** Card dinâmico com salários fictícios, atribuições e requisitos dos cargos.
* **Termo de Aceite:** Aviso transparente sobre a alocação flexível de cargos conforme a necessidade da empresa.

### 🛠️ 2. Gerador Dinâmico de Projetos Especiais por UC
* **Cobertura Integral das 18 UCs:** Mapeamento de todas as disciplinas da matriz curricular (*SST, Rotinas de RH, Gestão da Qualidade, Logística Integrada, etc.*).
* **Editor de Desafios:** Configuração de título, cenário-problema, orçamento e prazo em rodadas.
* **Injeção de Novas Ideias:** Espaço para o professor adicionar exigências personalizadas (ex: *"Exigir cotação formal com 2 fornecedores"*).
* **Decomposição Automática:** Divisão das tarefas do projeto entre RH, Compras, Produção, Qualidade e Financeiro.

### 🏢 3. Arquitetura de Cargos Graduados (Níveis I, II e III)
* **Estrutura Hierárquica:** Suporte para Diretoria, Supervisores de Setor e **Assistentes Administrativos Níveis I, II e III**.
* **Trilha de Aprendizagem:** Diferenciação de rotinas operacionais básicas (Nível I) até análises gerenciais complexas (Nível III).

### 🧭 4. Motor ERP & Guia Luminoso (GPS Neon)
* **HUD Dashboard:** Monitoramento contínuo de Caixa, Estoque de Insumos, SLA e Gargalos Ativos.
* **Navegação Visual Neon:** Botões piscantes em cores neon indicam o próximo passo a ser executado na esteira.
* **Fluxo Encadeado:** Conectividade de ponta a ponta, da Gerência Geral até o Faturamento e Liquidação no Caixa.

### 📖 5. Manual Completo Offline Integrado (`manual.html`)
* Documentação pedagógica e operacional completa acessível numa nova aba ou em ficheiro separado.
* Roteiro de aula em 4 passos (*Briefing, Execução, Fechamento e Debriefing*).
* Detalhamento de todas as 18 Unidades Curriculares e guia de uso dos botões.

---

## 📚 Mapeamento Curricular (Matriz APBG005701/02 — 600h)

| Bloco Curricular | Unidades Curriculares (UCs) Cobertas |
| :--- | :--- |
| **UCs Básicas (176h)** | • UC 01: Relações Socioprofissionais, Cidadania e Ética (20h)<br>• UC 02: Fundamentos da Comunicação e Informação (20h)<br>• UC 03: Saúde e Segurança do Trabalho - SST (20h)<br>• UC 04: Raciocínio Lógico e Análise de Dados (20h)<br>• UC 05: Transformação Digital no Setor Industrial (20h)<br>• UC 06: Planejamento e Organização do Trabalho (20h)<br>• UC 07: Análise de Dados e Informática Aplicada (32h)<br>• UC 08: Noções de Direito (24h) |
| **UCs Específicas I (144h)** | • UC 09: Introdução à Gestão Organizacional (24h)<br>• UC 10: Rotinas de Apoio Administrativo à Área de RH (40h)<br>• UC 11: Marketing e Vendas (20h)<br>• UC 12: Rotinas de Apoio Contábil e Financeiro (40h)<br>• UC 13: Introdução ao Desenvolvimento de Projetos (20h) |
| **UCs Específicas II (160h)** | • UC 14: Gestão da Qualidade (40h)<br>• UC 15: Ferramentas da Qualidade (40h)<br>• UC 16: Desenvolvimento de Ações de Melhoria (40h)<br>• UC 17: Controle Dimensional (40h) |
| **UCs Específicas III (120h)** | • UC 18: Logística Integrada (Conceitos, Modais, Recebimento, Armazenagem e Expedição) (120h) |

---

## 🚀 Como Executar o Simulador

1. **Baixar o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/spae-v2.git](https://github.com/seu-usuario/spae-v2.git)