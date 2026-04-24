# 🏛️ Malhete - Gestão Maçônica

## 📌 Visão Geral
Sistema desenvolvido para modernizar e organizar a gestão de lojas maçônicas, centralizando processos administrativos, financeiros e operacionais em uma única plataforma.

O foco não é apenas controle — é **clareza e padronização na tomada de decisão baseada em dados.**

---

## 🎯 Problema Resolvido
Muitas lojas ainda enfrentam:
- Controles descentralizados (papel, planilhas e sistemas isolados)
- Dificuldade na gestão financeira e prestação de contas
- Falta de visibilidade sobre membros, eventos e contribuições
- Processos manuais sujeitos a erros

O sistema foi desenvolvido para resolver diretamente esses desafios.

---

## 🚀 Solução Proposta
Uma aplicação completa que integra:

- **👥 Gestão de membros**  
  Cadastro, histórico e organização estruturada

- **💰 Controle financeiro**  
  Registro de receitas, despesas, contribuições e hospitalaria

- **📅 Gestão de eventos**  
  Planejamento e acompanhamento de atividades da loja

- **📊 Relatórios e dashboards**  
  Visualização clara para apoio à tomada de decisão

---

## 🛠️ Tecnologias Utilizadas
- React Native + Expo (desenvolvimento mobile multiplataforma)
- Supabase (backend: autenticação, banco de dados relacional e APIs)
- SQL (modelagem e consulta de dados)
- Power BI (análise e visualização de dados)

---

## 🏗️ Arquitetura do Sistema

O sistema foi desenvolvido utilizando o conceito de **multitenancy**, permitindo que múltiplas lojas utilizem a mesma aplicação de forma isolada e segura.

### 🔐 Isolamento por Loja (Tenant)
Cada loja opera como um tenant independente, garantindo que:
- Dados de membros não sejam acessíveis por outras lojas
- Informações financeiras permaneçam segregadas
- Eventos e registros sejam exclusivos de cada organização

O isolamento é garantido por:
- Identificação de tenant associada aos usuários
- Estrutura relacional no banco de dados (Supabase)
- Controle de acesso nas consultas e operações

---

### 👤 Controle de Acesso
Os usuários são vinculados a uma loja específica, com permissões definidas com base nesse vínculo.

Isso permite:
- Restringir acesso a dados sensíveis
- Garantir integridade das informações
- Evitar cruzamento indevido de dados

---

### 📊 Integração com Análise de Dados
Os dados de cada tenant são utilizados para geração de relatórios e dashboards no Power BI, respeitando o isolamento entre lojas.

---

### 🎯 Benefícios da Abordagem
- Escalabilidade: novas lojas podem ser adicionadas sem alterar a estrutura
- Segurança: separação lógica dos dados
- Manutenção simplificada: uma única base de código

---

## ⭐ Diferenciais do Projeto
- Estrutura pensada para organizações tradicionais com baixa digitalização
- Interface voltada para simplicidade e usabilidade
- Integração entre operação e análise de dados
- Adaptável para diferentes lojas

---

## 📷 Demonstração do Sistema

### 🔐 Tela de Login
Acesso seguro com autenticação vinculada à loja.
![Tela de Login](Tela_login.png)

### 🏠 Tela Inicial
Visão geral com acesso rápido às funcionalidades.
![Tela Inicial](Home.png)

### 💰 Gestão de Mensalidades
Controle de pagamentos com acompanhamento financeiro (restrito ao tesoureiro).
![Mensalidade](Mensalidade.png)

### 🏛️ Peças de Arquitetura
Organização e registro de trabalhos apresentados.
![Peças de Arquitetura](Pecas_Arquitetura.png)

### 📊 Registro Financeiro
Controle detalhado de receitas e despesas.
![Relatório financeiro](Registro_financeiro.png)

---

## 🔒 Código Fonte
Este projeto possui código proprietário e não está disponível publicamente.

---

## 📫 Contato
- LinkedIn: https://www.linkedin.com/in/gabriel-scheidegger-07403b142/
- Email: gmbandeira858@gmail.com
