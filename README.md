# TCC - Desenvolvimento de Sistema Web
## Trabalho de Conclusão de Curso

---

## 📋 Informações Gerais

- **Formato:** Trabalho em grupo (4 pessoas)
- **Modalidade:** Desenvolvimento de sistema web com versão de aplicativo ou PWA
- **Pontuação Etapa 1 (Escrita):** 3 pontos
- **Pontuação Etapa 2 (Prática):** 5 pontos
- **Data de Entrega Etapa 1:** 02/12/2025
- **Data de Apresentação Final:** 02 e 04/02/2026

---

## 🎯 Objetivo

Desenvolver a **documentação completa** de um sistema web que solucione um problema real, incluindo planejamento de uma versão mobile (aplicativo ou PWA). A Etapa 1 foca na **escrita e planejamento** do projeto.

### Requisitos Técnicos:
- ✅ Sistema web responsivo
- ✅ Versão mobile: aplicativo nativo OU PWA
- ✅ Integração entre as versões

---

## 📝 ETAPA 1: DOCUMENTAÇÃO DO PROJETO

O documento escrito deve conter **obrigatoriamente** os seguintes tópicos:

---

### 1. Identificação do Projeto

#### 1.1 Nome do Sistema
- Nome escolhido para o sistema
- Significado/justificativa do nome
- Deve ser profissional e relacionado à proposta

**Como fazer:**
- Evite nomes genéricos demais ("Sistema X", "App Y")
- Considere palavras que remetem à solução
- Teste se o nome é fácil de lembrar e pronunciar

#### 1.2 Integrantes do Grupo
- Nome completo de cada integrante
- Função no projeto (ex: Front-end Web, Back-end, Mobile/PWA, UX/UI)

---

### 2. Apresentação do Projeto

#### 2.1 Objetivo do Sistema

**O que escrever:**
- O que o sistema faz de forma clara e objetiva
- Qual é a proposta central
- Qual resultado esperado ao utilizá-lo
- Como funcionará nas versões web e mobile/PWA

**Exemplo:**
> "O sistema X tem como objetivo facilitar o controle financeiro pessoal através de um dashboard web intuitivo para análises detalhadas e um aplicativo/PWA para registro rápido de gastos em movimento. Ambas as versões sincronizam dados em tempo real."

**Dicas de escrita:**
- Use linguagem clara e direta
- Seja específico sobre o que o sistema faz
- Mencione as duas versões e como se complementam
- Entre 2 a 3 parágrafos

---

#### 2.2 Problema Identificado (A Dor)

**Esta é a seção mais importante da documentação.**

**O que escrever:**
1. **Qual problema real o sistema resolve?**
2. **Por que você está criando este sistema?**
3. **Qual a dor/necessidade que ele atende?**
4. **Para quem ele serve?** (Público-alvo específico)
5. **Como as pessoas resolvem esse problema hoje?**
6. **Por que sua solução é melhor/diferente?**
7. **Por que é importante ter versões web E mobile/PWA?**

**Como estruturar a escrita:**

**Parágrafo 1 - Contexto do problema:**
- Descreva a situação atual
- Use dados se possível ("70% dos estudantes...", "segundo pesquisa...")
- Mostre o impacto do problema

**Parágrafo 2 - Público-alvo:**
- Seja específico (não apenas "pessoas", mas "estudantes de 18-25 anos")
- Descreva como eles lidam com o problema hoje
- Mostre as limitações das soluções atuais

**Parágrafo 3 - Sua solução:**
- Por que é diferente/melhor
- Qual o diferencial
- Como resolve a dor identificada

**Parágrafo 4 - Justificativa Web + Mobile:**
- Por que precisa de versão web
- Por que precisa de versão mobile
- Como as versões se complementam

**Exemplo completo:**
> "Atualmente, estudantes universitários enfrentam dificuldades para organizar seus horários de estudo, prazos de trabalhos e compromissos acadêmicos. Segundo pesquisa da Universidade XYZ (2024), 70% dos estudantes relatam perder prazos importantes por falta de organização centralizada.
>
> O público-alvo são estudantes de 18 a 25 anos que utilizam múltiplas plataformas (e-mail institucional, WhatsApp, sistemas acadêmicos diversos) para acompanhar suas obrigações, gerando sobrecarga cognitiva e perda de informações importantes. Ferramentas genéricas como Google Calendar não são otimizadas para a realidade acadêmica.
>
> Nossa solução oferece um hub centralizado específico para vida acadêmica, com templates para diferentes tipos de atividades (provas, trabalhos, seminários) e integração com sistemas universitários comuns. O diferencial está na especialização para o contexto educacional.
>
> A versão web permite planejamento detalhado e visualização completa do semestre no computador durante estudos, enquanto a versão mobile/PWA oferece acesso rápido para consultas em movimento e notificações inteligentes de prazos próximos."

**Dicas de escrita:**
- Seja específico, não genérico
- Use dados quando possível
- Mostre empatia com o problema
- Evite soluções "em busca de problema"
- Escreva de 4 a 6 parágrafos bem estruturados

---

#### 2.3 Stack Tecnológica

**O que escrever:**

Liste e **justifique** as tecnologias escolhidas para ambas as versões (web e mobile/PWA).

**Front-end Web:**
- Framework/Linguagem escolhida
- Bibliotecas principais
- **Por que escolheu** (justificativa)

**Versão Mobile:**
- **Se PWA:** Service Workers, Manifest, framework base
- **Se App Nativo:** React Native / Flutter / Ionic
- **Por que PWA ou Nativo** (justificativa importante)

**Back-end:**
- Linguagem/Framework
- Banco de dados
- Tipo de API (REST/GraphQL)
- **Por que escolheu**

**Exemplo:**
```
Front-end Web:
- React com TypeScript
  Justificativa: Equipe tem experiência, componentização facilita
  manutenção, TypeScript adiciona segurança de tipos

Versão Mobile (PWA):
- Mesma base React adaptada para mobile
- Workbox para Service Workers
  Justificativa: PWA permite reutilizar código da web, reduzindo
  tempo de desenvolvimento. Não precisamos de recursos nativos
  avançados, apenas notificações e funcionamento offline básico

Back-end:
- Node.js com Express
- PostgreSQL
  Justificativa: JavaScript full-stack facilita desenvolvimento,
  PostgreSQL adequado para dados relacionais estruturados
```

---

### 📱 Como Decidir: PWA vs App Nativo?

**Esta decisão deve ser justificada na documentação.**

#### Escolha PWA se:

**Vantagens:**
- ✅ Mesma base de código da versão web
- ✅ Desenvolvimento mais rápido
- ✅ Funciona em qualquer plataforma
- ✅ Instalável na tela inicial
- ✅ Pode funcionar offline

**Limitações:**
- ❌ Acesso limitado a recursos nativos avançados
- ❌ Performance inferior em operações pesadas

**Quando usar na sua documentação:**
- Sistema focado em dados e formulários
- CRUD básico (criar, ler, atualizar, deletar)
- Dashboards/relatórios
- Não precisa de câmera, GPS ou sensores

---

#### Escolha App Nativo se:

**Vantagens:**
- ✅ Acesso completo a recursos nativos (câmera, GPS, sensores)
- ✅ Performance superior
- ✅ Notificações push mais confiáveis

**Desafios:**
- ❌ Código separado da versão web
- ❌ Mais tempo de desenvolvimento

**Quando usar na sua documentação:**
- Precisa de câmera ou scanner
- Usa localização em tempo real
- Necessita de sensores
- Requer performance alta

---

### 3. Arquitetura e Fluxo do Sistema

#### 3.1 Mapa de Telas

**Como documentar:**

Apresente **todas** as telas que o sistema terá, para **ambas** as versões (web e mobile/PWA).

**Para cada tela, descrever:**
1. **Nome da tela**
2. **Versão** (Web / Mobile / Ambas)
3. **Objetivo da tela**
4. **Elementos principais** (botões, campos, listas)
5. **Ações possíveis** (o que o usuário pode fazer)
6. **Navegação** (para onde cada ação leva)
7. **Diferenças entre versões** (se houver)

**Formato recomendado:**

```
TELA 1: Login (Web e Mobile)
- Versão: Ambas (com adaptações)
- Objetivo: Autenticar o usuário
- Elementos:
  * Campo de e-mail
  * Campo de senha
  * Botão "Entrar"
  * Link "Esqueci minha senha"
- Ações:
  * Clicar "Entrar" → valida e redireciona para Dashboard/Home
  * Clicar "Esqueci senha" → Tela de recuperação
- Diferenças:
  * Web: Layout horizontal com imagem
  * Mobile: Layout vertical tela inteira

TELA 2: Dashboard (Somente Web)
- Versão: Web
- Objetivo: Visão geral com gráficos detalhados
- Elementos:
  * Sidebar com menu
  * Cards com métricas
  * Gráficos interativos
  * Tabela de dados
- Ações:
  * Clicar em cards → Detalhes
  * Filtrar dados → Atualiza visualização
- Equivalente Mobile: Home (versão simplificada)

TELA 3: Home (Somente Mobile)
- Versão: Mobile/PWA
- Objetivo: Acesso rápido às funções principais
- Elementos:
  * Header com notificações
  * Cards com ações rápidas
  * Bottom navigation bar
- Ações:
  * Pull-to-refresh
  * Tocar cards → Ações específicas
- Equivalente Web: Dashboard (versão expandida)
```

**Dicas de escrita:**
- Liste TODAS as telas (mínimo 5-6)
- Seja detalhado nos elementos
- Explique a navegação entre telas
- Deixe claro as diferenças entre web e mobile

---

#### 3.2 Fluxograma de Navegação

**Como escrever:**

Descreva textualmente ou crie diagrama mostrando como as telas se conectam.

**Exemplo textual:**
```
FLUXO WEB:
Splash → Login → Dashboard → [Menu lateral com:]
  - Relatórios
  - Configurações
  - Perfil
  - Sair

FLUXO MOBILE:
Splash → Login → Home → [Bottom Navigation:]
  - Home
  - Notificações
  - Adicionar
  - Perfil
```

**Ou use formato de lista:**
- Como o usuário navega do início ao fim
- Quais os caminhos principais
- Onde estão os menus/navegação
- Como voltar para telas anteriores

---

### 4. Funcionalidades Detalhadas

**Como documentar:**

Organize as funcionalidades por prioridade:

#### 4.1 Funcionalidades Essenciais (MVP)
Sem essas, o app não funciona.

**Para cada funcionalidade:**
- **Nome:** Login de usuário
- **Descrição:** Sistema de autenticação segura
- **Como funciona:** Usuário insere email/senha, sistema valida e cria sessão
- **Telas envolvidas:** Login, Recuperação de senha
- **Versões:** Web e Mobile

#### 4.2 Funcionalidades Importantes
Agregam valor significativo.

#### 4.3 Funcionalidades Desejáveis
Melhorias futuras (se houver tempo).

**Exemplo:**
```
ESSENCIAIS (MVP):
1. Login/Cadastro de usuário (Web e Mobile)
2. Adicionar novo item (Web e Mobile)
3. Listar itens cadastrados (Web e Mobile)
4. Editar/Excluir item (Web e Mobile)

IMPORTANTES:
5. Notificações push (Mobile)
6. Dashboard com gráficos (Web)
7. Filtros avançados (Web)

DESEJÁVEIS:
8. Exportar relatórios PDF (Web)
9. Modo offline (PWA)
10. Integração com redes sociais
```

---

### 5. Considerações de UX/UI

#### 5.1 Identidade Visual

**O que escrever:**
- Paleta de cores principal (ex: Azul #1E40AF, Branco #FFFFFF)
- Tipografia escolhida (ex: Roboto para textos, Montserrat para títulos)
- Estilo geral (minimalista, colorido, corporativo, moderno)
- **Como manter consistência entre web e mobile**

#### 5.2 Responsividade

**O que escrever:**
- Como a versão web se adapta a diferentes telas
- Breakpoints definidos (ex: mobile <768px, tablet 768-1024px, desktop >1024px)
- Interface touch-friendly na versão mobile

#### 5.3 Diferenças de Experiência

**Versão Web:**
- Aproveita tela maior para visualizações complexas
- Interações com mouse (hover, cliques)
- Múltiplas informações simultâneas

**Versão Mobile/PWA:**
- Interface otimizada para toque
- Gestos nativos (swipe, pull-to-refresh)
- Notificações push
- Acesso rápido e em movimento

---

### 6. Cronograma de Desenvolvimento

**Como escrever:**

Apresente cronograma realista para a Etapa 2 (desenvolvimento):

| Período | Atividade | Responsável |
|---------|-----------|-------------|
| 02/12 - 15/12 | Configuração do ambiente | Equipe |
| 16/12 - 31/12 | Desenvolvimento telas web | Front-end Web |
| 02/01 - 15/01 | Desenvolvimento mobile/PWA | Front-end Mobile |
| 16/01 - 25/01 | Integração e testes | Equipe |
| 26/01 - 01/02 | Ajustes finais | Equipe |

**Dicas:**
- Seja realista com o tempo
- Considere o recesso
- Divida tarefas entre membros
- Deixe tempo para imprevistos

---

## ⚠️ IMPORTANTE: Modificações

Qualquer mudança entre o documentado na Etapa 1 e o desenvolvido na Etapa 2 **precisa de justificativa**.

**Justificativas aceitas:**
- ✅ "Durante desenvolvimento, identificamos melhoria X porque..."
- ✅ "Percebemos que faltava funcionalidade Y para..."
- ✅ "A tecnologia X teve limitação, substituímos por Z..."

**Não aceitas:**
- ❌ Mudanças sem justificativa
- ❌ Simplificações por "preguiça"

---

## 💡 Dicas de Escrita

### Para o Documento

✅ **Faça:**
- Pesquise sistemas similares
- Valide sua ideia com potenciais usuários
- Seja realista sobre o prazo
- Justifique bem escolha PWA vs App Nativo
- Crie protótipos visuais (Figma, wireframes)
- Revise várias vezes
- Peça feedback de colegas
- Use linguagem profissional
- Seja específico, não genérico

❌ **Evite:**
- Propor algo muito complexo
- Escolher tecnologias desconhecidas
- Documentação superficial
- Copiar ideias sem adaptação
- Deixar para última hora
- Erros de português
- Textos vagos ou genéricos

---

### Estrutura do Documento

**Organize assim:**

1. **Capa** (opcional)
   - Nome do sistema
   - Nome dos integrantes
   - Data

2. **Sumário** (se extenso)

3. **Conteúdo** (tópicos obrigatórios acima)
   - Use tópicos e subtópicos
   - Numere as seções
   - Use formatação clara

4. **Referências** (se usar pesquisas/dados)

---

## 📊 Checklist do Documento

Antes de entregar, verifique:

### Conteúdo Obrigatório:
- [ ] Nome do sistema com justificativa
- [ ] Integrantes e funções definidas
- [ ] Objetivo do sistema claro e completo
- [ ] **Problema identificado bem descrito** (seção mais importante!)
- [ ] Público-alvo específico
- [ ] Justificativa da solução
- [ ] Justificativa para ter web E mobile
- [ ] Stack tecnológica completa e justificada
- [ ] Escolha PWA ou App Nativo justificada
- [ ] **Todas as telas documentadas** (web e mobile)
- [ ] Diferenças entre versões explicadas
- [ ] Fluxo de navegação claro
- [ ] Funcionalidades organizadas por prioridade
- [ ] Identidade visual definida
- [ ] Cronograma de desenvolvimento

### Qualidade:
- [ ] Texto revisado (sem erros de português)
- [ ] Linguagem profissional
- [ ] Informações específicas (não genéricas)
- [ ] Justificativas convincentes
- [ ] Documento bem formatado
- [ ] Imagens/diagramas (se houver) com boa qualidade

---

## 🎓 Considerações Finais

### Foco da Etapa 1

A Etapa 1 é sobre **planejamento e escrita**. O sucesso depende de:

1. **Identificar um problema real** e específico
2. **Documentar uma solução viável** e detalhada
3. **Justificar escolhas técnicas** de forma convincente
4. **Planejar todas as telas e fluxos** para ambas versões
5. **Escrever com clareza** e profissionalismo

### Sobre a Complexidade

Desenvolver duas versões (web + mobile) pode parecer desafiador, mas:
- PWA permite reaproveitar código web
- É mais próximo da realidade do mercado
- Demonstra versatilidade técnica
- Com boa divisão no grupo, é viável

### Divisão Sugerida do Grupo

**Para 4 pessoas:**
- **Pessoa 1:** Front-end Web + Responsividade
- **Pessoa 2:** Front-end Mobile/PWA
- **Pessoa 3:** Back-end + API + Banco de Dados
- **Pessoa 4:** UX/UI + Integração + Documentação

---

**Bom trabalho! 🚀**

*Lembre-se: A qualidade da documentação na Etapa 1 determina o sucesso do desenvolvimento na Etapa 2.*

*Documento atualizado: Novembro/2025*
