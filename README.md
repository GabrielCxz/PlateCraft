# PlateCraft
**Transforme suas sobras em pratos incríveis!**

## Descrição do Projeto
O PlateCraft é um aplicativo mobile desenvolvido para combater o desperdício de alimentos domésticos, oferecendo uma solução prática e inteligente para aproveitamento de ingredientes disponíveis em casa.

## Problema Identificado
O desperdício de alimentos é uma realidade presente na maioria dos lares brasileiros. Muitas vezes, ingredientes ficam esquecidos na geladeira ou despensa, resultando em perda de alimentos e recursos financeiros. Essa situação se agrava especialmente em residências com muitos moradores, onde as compras são realizadas em maior quantidade.

## Solução Proposta
O PlateCraft permite que os usuários insiram os ingredientes disponíveis em suas casas e recebam sugestões de receitas personalizadas, otimizando o uso dos alimentos e evitando o desperdício. O aplicativo é especialmente útil para:

- Aproveitamento de sobras e ingredientes próximos ao vencimento
- Economia no final do mês
- Descoberta de novas combinações culinárias
- Planejamento de refeições com base no que está disponível

## Como Funciona

### Fluxo Principal
1. **Interface Inicial**: Tela com campo de entrada para ingredientes disponíveis
2. **Processamento**: O sistema busca receitas compatíveis em nossa base de dados
3. **Resultados**: Apresentação de receitas com ingredientes, modo de preparo e imagens
4. **Avaliações**: Sistema de feedback baseado em avaliações dos sites fonte

### Fonte de Dados
O aplicativo utiliza uma base de dados robusta alimentada por três principais fontes:
- Tudo Gostoso: tudogostoso.com.br
- Receitas Globo: receitas.globo.com
- Receiteria: receiteria.com.br

### Sistema de Busca Inteligente
Quando não há receitas disponíveis na base local para os ingredientes informados, o sistema executa uma busca avançada no Google, extraindo automaticamente:
- Lista de ingredientes necessários
- Modo de preparo detalhado
- Imagens das receitas
- Avaliações dos usuários (quando disponíveis)

## Funcionalidades
- Busca de receitas por ingredientes disponíveis
- Interface intuitiva e fácil de usar
- Base de dados extensiva de receitas
- Sistema de backup com busca web
- Visualização de imagens das receitas
- Instruções passo a passo
- Sistema de avaliações
- Sugestões múltiplas para os mesmos ingredientes

## Interface do Usuário
O aplicativo apresenta uma interface clean e objetiva, priorizando a usabilidade:
- **Tela Principal**: Campo de busca centralizado para inserção de ingredientes
- **Resultados**: Cards com preview das receitas encontradas
- **Detalhes**: Tela completa com ingredientes, preparo e avaliações

## Protótipo
Acesse o protótipo visual do aplicativo no Figma:  [PlateCraft - Protótipo](https://www.figma.com/design/Aw0qqlWACh1ZJaazzG7HH7)

## Estrutura de Dados da API
[Seção a ser desenvolvida com base no DER fornecido]

A API do PlateCraft gerencia as seguintes entidades principais:
- Usuários e preferências
- Base de receitas e ingredientes
- Sistema de avaliações e feedback
- Cache de buscas realizadas

## Justificativa Pessoal
Este projeto nasceu da necessidade real observada em uma residência com muitos moradores, onde as compras são realizadas em grande quantidade e frequentemente resultam em sobras. O PlateCraft oferece uma solução prática para transformar esses ingredientes "esquecidos" em refeições deliciosas, contribuindo tanto para a economia doméstica quanto para a sustentabilidade.

## Benefícios Esperados
- Redução do desperdício alimentar em nível doméstico
- Economia financeira através do melhor aproveitamento dos alimentos
- Descoberta culinária com novas receitas e combinações
- Consciência sustentável promovendo hábitos mais responsáveis
- Praticidade no planejamento de refeições
