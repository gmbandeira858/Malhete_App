# Malhete - Gestão Maçônica

# Visão Geral
Sistema desenvolvido para modernizar e organizar a gestão de lojas maçônicas, centralizando processos administrativos, financeiros e operacionais em uma única plataforma.
O foco não é apenas controle - é **clareza e padronização de tomadas de decisões baseadas nos dados.**

# Problema Resolvido
Muitas lojas ainda enfrentam:
- controles descentralizados (papel, planilhas, sistemas isolados).
- Dificuldade na gestão financeira e prestação de contas.
- Falta de visibilidade sobre membros, eventos e contribuições.
- Processos manuais sujeitos a erros.
O intuito foi resolver exatamente esses problemas.

# Solução proposta
Uma aplicação completa que integra:
- **Gestão de membros**
  Com cadastro, histórico e organização estruturada.
- **Controle Financeiro**
  Registro de receitas, despesas, contribuições e hospitalaria
- **Gestão de eventos**
  Planejamento e acompanhamento de atividades da loja, como sessões magnas e festivas.
- **Relatórios e Dashboards**
  Visualização clara para apoio à tomada de decisão.

# Tecnologias utilizadas
- React Native + Expo (desenvolvimento mobile multiplataforma)
- Supabase (Backend: autenticação, banco de dados relacional e APIs)
- Power BI (análise e visualização de dados)

# Arquitetura do sistema
Tudo foi pensado e desenvolvido utilizando o conceito de multitenancy, permitindo que múltiplas lojas maçônicas utilizem a mesma aplicação de forma isolada, segura e sem interferência.

  # Isolamento por loja (Tenant)
  Cada loja opera como um "Tenant" independente dentro do sistema, garantindo que:
  - Dados de membros não seja acessíveis por outras lojas.
  - Informações financeiras permaneçam segregadas.
  - Eventos e registros sejam exclusivos de cada organização.

  Esse isolamento é garantido através de:
  - Identificação de Tenant associada aos usuáirios
  - Estrutura relacional no banco de dados (Supabase)
  - Controle de acesso nas consultas e operações

  # Controle de acesso
  Os usuários vinculados a uma loja específica, e suas permissões são definidas com base nesse vínculo.
  Isso permite:
  - Restringir acesso a dados sensíveis
  - Garantir integridade das informações
  - Evitar cruzamento indevido de dados entre lojas

  # Integração com análise de dados
  Os dados de cada tenant podem ser utilizados de forma estruturada para geração de relatórios e dashboards no Power BI, respeitando o isolamento entre lojas.

  # Benefícios da Abordagem
  - Escalabilidade: novas lojas podem ser adicionadas sem alterar a estrutura do sistema.
  - Segurança: separação lógica dos dados.
  - Manutenção simplificada: uma única base de código para múltiplos clientes.

# Diferenciais do projeto
- Estrutura pensada para organizações tradicionais com baixa digitalização
- Interface voltada para a simplicidade e usabilidade
- Integração entre dados operacionais e análise estratégica
- Possibilidade de adaptação para diferentes lojas

# Prints

