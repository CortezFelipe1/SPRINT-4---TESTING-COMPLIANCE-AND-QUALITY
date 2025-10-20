# RELATÓRIO DE TESTES: TESTING, COMPLIANCE AND QUALITY

Este repositório contém a entrega completa da avaliação de Testes, Compliance e Qualidade, cobrindo o Plano de Testes Manuais (Parte A) e os Testes Automatizados (Parte B).

**Branch de Entrega:** `develop`

## 🚀 PROJETO: SPRINT 4 XP

### 🛠️ Funcionalidades Principais Testadas (PBIs)

A entrega focou na validação dos seguintes itens do *Product Backlog*:

* Onboarding guiado com questionário de suitability | (1) 
* Timeline de eventos | (1) 
* Importar saldos e posições automaticamente | (1) 
* Filtros avançados | (2) 
* Excluir conta e dados (LGPD) | (1) 
* Chat de dúvidas | (3) 
* Modo escuro/claro | (1) 
* Recuperar senha | (1) 
* Criar conta com e-mail/telefone | (5)
<img width="1319" height="703" alt="image" src="https://github.com/user-attachments/assets/c1a6efbd-f696-4456-8f36-6f5d73aadb15" />


---

## PARTE A: PLANO DE TESTES MANUAIS (AZURE BOARDS)

O Plano de Testes de Validação de Sistema foi elaborado no Azure Boards. Cada *Caso de Teste* está detalhado com **testes planejados**, **dados de entrada controlados**, **saídas esperadas** e o **procedimento (passos)** necessário.

### 1. Link de Acesso ao Azure Boards

🔗 **LINK COMPLETO:**
`https://dev.azure.com/SPRINT-QA-XP/SPRINT-QA-XP`
<img width="1296" height="625" alt="image" src="https://github.com/user-attachments/assets/7d45b3c8-87a0-42cb-b043-6ee7c48d64f5" />


### 2. Checklists de Validação Cobertos

Os testes manuais cobriram o seguinte escopo de validação funcional:

* Validar cadastro
* Validar fluxo de recuperação de senha
* Validar botão de modo claro/escuro
* Validar pergunta sobre valores de ações
* Validar fluxo de exclusão de conta
* Validar distribuição das ações via app
* Validar importação de dados bancários
* Validar timeline de eventos
* Validar fluxo do questionário
* Validar deslogamento da conta
* Validar perguntas básicas sobre investimento
* Validar card de investimentos recentes
* Validar login
* Validar perguntas que não são sobre ações
* Validar tela de perfil
* Validar login com senha inválida
<img width="1324" height="716" alt="image" src="https://github.com/user-attachments/assets/b299846a-a04e-46e2-9f09-662ed9bc18e9" />

---

## PARTE B: TESTES DE AUTOMAÇÃO

A validação do sistema foi realizada através de automação para garantir a estabilidade das funcionalidades críticas.

### 1. Ferramenta e Foco

* **Ferramenta Utilizada:** **Pytest (com Flask Test Client)**
* **Foco da Automação:** **Testes de Unidade e Integração de API (Backend), cobrindo rotas de autenticação, validação de segurança (input sanitization) e acesso a recursos protegidos.**
* **Total de Casos Automatizados** **6**
### 2. Link do Vídeo de Configuração e Execução

O vídeo a seguir demonstra o processo de configuração da ferramenta, a execução dos casos de testes automatizados e a visualização dos resultados:

▶️ **LINK DO VÍDEO:** **(https://youtu.be/mojwBSscu7o)**

## 👥 MEMBROS DA EQUIPE

André Lambert – RM 99148
Felipe Cortez - RM 99750
Julia Lins - RM 98690
Luis Barreto - RM 99210
Victor Aranda - RM 99667
