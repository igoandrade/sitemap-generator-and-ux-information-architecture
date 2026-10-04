Você é um especialista em Arquitetura de Informação, Design de Interação e UX Design. Sua tarefa é criar a arquitetura de informação completa e propor a estrutura de um Sitemap para o projeto descrito a seguir.

---

### 1. CONTEXTO DO PROJETO E PESQUISA DE USUÁRIO
* **Nome da Aplicação/Site:** [Ex: Sistema de Gestão de Frota / E-commerce de Plantas / App de Finanças Pessoais]
* **Objetivo Principal do Produto:** [Descreva em 1-2 frases o que o produto faz]
* **Público-Alvo e Personas:** [Descreva brevemente 1 ou 2 personas do projeto]
* **Principais Dores dos Usuários:** [Liste de 2 a 3 dores identificadas na fase de empatia/pesquisa]
* **Tarefas Principais do Usuário (User Journey Key Tasks):** [O que o usuário PRECISA conseguir realizar do início ao fim?]

---

### 2. ESTRUTURA TÉCNICA E MODELO DE NAVEGAÇÃO EXIGIDO
Crie o sitemap utilizando uma das estruturas abaixo (ou uma combinação híbrida):
* **Estrutura Escolhida:** [Hierárquica / Sequencial / Matriz / Banco de Dados / Híbrida (Hierárquica + Banco de Dados)]
* **Profundidade Esperada:** [Sitemap Plano (até 4 níveis) OU Sitemap Profundo (5 ou mais níveis)]

---

### 3. DIRETRIZES OBRIGATÓRIAS PARA A RESPOSTA (CHECKLIST DE UX)

Certifique-se de que a resposta cumpra integralmente os seguintes requisitos:

1. **Definição do Ponto de Partida:**
   - Especifique a **Página Inicial (Homepage/Landing Page)** para visitantes anônimos.
   - Especifique o **Dashboard / Ponto de Entrada Autenticado** para usuários logados.

2. **Categorias Principais (Páginas Pai / Nível 1):**
   - Nomeie as seções primárias que apareceriam no menu de navegação principal (incluindo padrões comuns da indústria como Busca, Autenticação/Conta, Carrinho/Ações e Configurações).

3. **Subcategorias e Telas Específicas (Páginas Filho / Nível 2 e Nível 3):**
   - Mapeie todas as telas secundárias, incluindo modais, estados vazios e telas de confirmação necessárias para a conclusão das tarefas principais.

4. **Indicadores Visuais e Relacionamento de Navegação:**
   - Apresente o diagrama em um formato hierárquico legível (ex: diagrama de árvore em caracteres Markdown, tabela estruturada ou blocos visuais).
   - Use setas (`-->`, `<--`) ou indentação clara para indicar o fluxo entre telas, rotas de redirecionamento, dados dinâmicos do BD e acessos dependentes de permissão.

5. **Mapeamento de Banco de Dados / Telas Dinâmicas (se aplicável):**
   - Explique quais tabelas do BD alimentam quais telas e subpáginas dinâmicas do sitemap.

6. **Detalhamento das Telas Críticas:**
   - Descreva brevemente o conteúdo principal e as ações de cada tela relevante listada no sitemap.

---

### 4. FORMATO DE SAÍDA ESPERADO

Forneça a resposta dividida nas seguintes seções:
1. **Resumo da Estrutura Escolhida & Justificativa de UX**
2. **Diagrama Árvore do Sitemap (Hierarquia e Fluxos)**
3. **Mapeamento Detalhado Tela por Tela (Nome, Ações, Conteúdo e Relações)**
4. **Mapeamento de Entidades do Banco de Dados para Páginas Dinâmicas**
5. **Código em Mermaid.js** (Para permitir renderização gráfica de diagrama de fluxo com setas e nós).
