📔 Carteira do Estudante Digital
Projeto desenvolvido para a disciplina de Programação Web, utilizando Vue.js (conforme apostila) e Git para controle de versão.

📋 Descrição
Sistema de Carteira do Estudante dinâmica, onde os dados preenchidos em um formulário são renderizados em tempo real em um modelo de carteirinha.

Funcionalidades Implementadas
✅ Versão 1.0:

Diretivas básicas do Vue (v-text, v-bind, v-for) para exibição de dados.

Estrutura inicial com HTML e JavaScript puro (baseado na apostila).

✅ Versão 2.0:

Formulário com v-model para adicionar itens a uma lista.

Checkbox que altera o tema da página (modo escuro/claro).

✅ Versão 3.0:

Formulário dividido: lado esquerdo (inputs) e pré-visualização da carteirinha (lado direito).

Dados atualizados em tempo real (v-model + vinculação dinâmica).

🛠️ Tecnologias
Front-end: Vue.js 3 (CDN) + HTML/CSS puro.

Controle de Versão: Git + GitHub.

Metodologia: Commits semânticos (ex: 1.0 - PROJETO EM PRODUÇÃO).

📂 Estrutura do Projeto
plaintext
Copy
CARTEIRA-ESTUDANTE/
├── index.html          # Página principal com estrutura Vue
├── app.js              # Lógica Vue (data, diretivas)
├── README.md           # Este arquivo
└── assets/             # (Opcional) Pasta para imagens/CSS
🚀 Como Executar
Clone o repositório:

bash
Copy
git clone https://github.com/TACIO-ai/CARTEIRA-ESTUDANTE.git
Abra o index.html em qualquer navegador moderno.

📌 Diretivas Vue Utilizadas
Diretiva	Exemplo no Código	Função
v-text	<h1 v-text="titulo">	Exibe texto dinâmico.
v-bind	:class="classeDinamica"	Vincula atributos HTML a dados.
v-for	<li v-for="item in lista">	Renderiza listas.
v-model	<input v-model="nome">	Two-way data binding.
📜 Regras do Projeto (Conforme Apostila)
⚠️ Apenas conteúdo da apostila foi usado (até v-for).

🚫 Não foram utilizados: methods, computed, v-on.

📌 Commits documentados conforme evolução do projeto.

📧 Contato
Aluno: [Seu Nome]

E-mail: [seu-email@uninga.edu.br]

Repositório: github.com/TACIO-ai/CARTEIRA-ESTUDANTE

