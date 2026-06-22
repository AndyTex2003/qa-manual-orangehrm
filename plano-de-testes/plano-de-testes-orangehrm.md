# Plano de Testes - OrangeHRM

## 1. Objetivo

Este documento tem como objetivo definir a estratégia, escopo, abordagem e critérios para execução dos testes manuais da aplicação OrangeHRM.

O projeto visa validar funcionalidades críticas do sistema relacionadas à autenticação, gerenciamento de funcionários e administração de usuários, garantindo que os requisitos funcionais sejam atendidos e que a aplicação apresente comportamento consistente para o usuário final.

---

## 2. Informações do Projeto

| Item | Descrição |
|--------|--------|
| Projeto | OrangeHRM QA Manual |
| Aplicação | OrangeHRM Demo |
| Versão | 1.0 |
| Data | Junho/2026 |
| Tipo de Teste | Teste Manual |
| Ambiente | Homologação / Demo |
| Ferramenta de Gestão | GitHub |
| Responsável | Anderson Batista dos Santos |
---

## 3. Escopo

### Funcionalidades incluídas

- Login
- Logout
- Dashboard
- PIM (Gerenciamento de Funcionários)
- Admin (Gerenciamento de Usuários)

### Funcionalidades fora do escopo

- Recruitment
- Performance
- Directory
- Maintenance
- Claim
- Buzz
- Integrações externas
- Testes de Performance
- Testes de Segurança

---

## 4. Estratégia de Testes

Os testes serão executados manualmente com foco na validação dos principais fluxos funcionais da aplicação.

Serão aplicadas as seguintes abordagens:

- Testes Positivos
- Testes Negativos
- Testes Exploratórios
- Particionamento de Equivalência
- Análise de Valor Limite (quando aplicável)

As evidências dos testes executados serão registradas através de capturas de tela armazenadas no repositório do projeto.

---

## 5. Critérios de Entrada

A execução dos testes poderá ser iniciada quando:

- O ambiente OrangeHRM Demo estiver disponível.
- As credenciais de acesso estiverem válidas.
- Os casos de teste estiverem documentados.
- O escopo estiver definido.

---

## 6. Critérios de Saída

A execução dos testes será considerada concluída quando:

- Todos os casos de teste planejados forem executados.
- As evidências estiverem registradas.
- Os defeitos identificados estiverem documentados.
- A matriz de cobertura estiver atualizada.

---

## 7. Riscos

Os seguintes riscos podem impactar a execução dos testes:

- Instabilidade do ambiente demo.
- Alterações na aplicação realizadas pelos mantenedores do ambiente.
- Dados de teste indisponíveis ou modificados durante a execução.
- Limitações do ambiente público para reprodução de defeitos.

---

## 8. Ambiente de Testes

| Item | Descrição |
|--------|--------|
| Aplicação | OrangeHRM Demo |
| URL | https://opensource-demo.orangehrmlive.com |
| Navegador | Google Chrome |
| Sistema Operacional | Windows 11 |
| Tipo de Teste | Manual |